 
 # Team Portfolio Project

This repository is created for our team portfolio project.
 



##  Team Members

| Name                         | GitHub Username        |
|------------------------------|------------------------|
| Sara Ikhedji                 | [@IkhedjiSara](https://github.com/IkhedjiSara) |
| Khalil Benyoub               | [@KhalilBenyoub](https://github.com/KhalilBenyoub) |
| Amdjed Takieddine Guellat    | [@Amdjedguellati](https://github.com/Amdjedguellati) |
| Ayaterrahmane Nacer          | [@AyatErrahman](https://github.com/AyatErrahman) |
| Habiba Malak Lehrizi         | [@Lehrizihabiba](https://github.com/Lehrizihabiba) |
| Ithar Bouguendoura (Team Lead) | [@Ithar-Bouguendoura](https://github.com/Ithar-Bouguendoura) |



Sure 👍 — here’s a complete and professional **Team Retrospective Analysis** you can include in your report, along with a placeholder for your **GitHub Pages link** (you’ll just replace it with your actual one).

---

###  **Deployed Website Link**

[Visit the Deployed Website on GitHub Pages](https://ithar-bouguendoura.github.io/team-portfolio-project-/)
 

---

### **Team Retrospective Analysis**

During Phase 2 of development, our team’s most significant technical challenge was managing version control efficiently while multiple members worked simultaneously on separate feature branches. Although Git facilitated collaboration, synchronizing changes to shared files such as `index.html` often led to overlapping edits and merge conflicts. This was particularly evident when each member added their profile link to the same section of the index page, resulting in branch divergence between local and remote repositories.

A specific merge conflict occurred when two branches modified the same `<a>` tag structure in the `index.html` file. Git could not automatically determine which changes to keep, marking the conflict area with `<<<<<<<`, `=======`, and `>>>>>>>`. To resolve this, the responsible member first fetched the latest version of the `develop` branch using:

```bash
git checkout develop
git pull origin develop
```

Then, after switching back to their feature branch and merging:

```bash
git checkout feature/implement-name-profile
git merge develop
```

The conflicting section was manually edited to retain all team members’ profile links in the correct order. After testing locally to ensure that no links were broken, the conflict was resolved, staged, and committed with:

```bash
git add .
git commit -m "fix: resolve merge conflict in index.html"
```

The most frequent issues involved multiple team members modifying the same section of the file, such as inserting their profile images and links. Some members accidentally placed their photo inside the same <div> element as another member’s image, breaking the layout. Others used incorrect or missing image paths, leading to broken links when the page was deployed.

A particularly complex merge conflict occurred in the index.html file when two branches contained overlapping edits within the image container and hyperlink structure. Git flagged the conflicting lines, making it unclear which version to keep. To resolve it, one member pulled the latest updates from the develop branch:

git checkout develop
git pull origin develop


Then merged them into their feature branch:

git checkout feature/implement-name-profile
git merge develop


Afterward, the team met to review the conflict manually. They ensured that each image and link had a unique container and corrected any incorrect image paths. Once verified, the conflict markers were removed, the code was cleaned, and the fix was committed:

git add .
git commit -m "fix: resolve merge conflict and correct image paths"


The pull request and peer review process significantly improved the project’s quality. Each pull request allowed other members to review structure, image paths, and formatting before merging. This not only prevented similar mistakes from recurring but also encouraged team collaboration, as members learned to identify and fix conflicts effectively. Overall, these practices led to a cleaner final result, a better understanding of distributed workflows, and stronger teamwork.
 


 
 
