 
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



 
 
 

###  **Deployed Website Link**

[Visit the Deployed Website on GitHub Pages](https://ithar-bouguendoura.github.io/team-portfolio-project-/)
 

 


 ## Team Retrospective Analysis

During the collaborative development of our team portfolio project, the most significant technical challenge we encountered was managing multiple concurrent feature branches while maintaining consistency across shared files, especially index.html and the main CSS files. Each team member was responsible for creating their own profile page and linking it to the main index, which required everyone to edit the same HTML section. This led to overlapping code changes, duplicate elements, and broken image links when merging different branches. These issues tested our coordination and understanding of Git workflows.

A specific merge conflict occurred when two members placed their profile photos in the same <div> container within index.html, while another member accidentally provided an incorrect image path. When their branches were merged into the develop branch, Git flagged conflicts in the section related to image placement and links. To resolve this, the team leader took responsibility for handling the conflict. The process involved several steps: (1) identifying the conflicting lines through Git’s conflict markers, (2) discussing as a team which version of the code should be preserved, (3) manually editing index.html to separate each member’s photo into distinct containers, (4) correcting the broken image paths, and (5) verifying that all profiles displayed correctly before pushing the resolved version. Afterward, the team leader completed the merge and final edits to ensure the layout was consistent.

The pull request and peer review process proved very effective in maintaining the project’s quality. Each feature branch was reviewed before merging into develop, allowing members to spot errors, inconsistent styles, and missing links early. The final merge from develop into main was also performed by the team leader after confirming that all pages worked correctly. This structured workflow improved not only the technical quality of the final website but also our teamwork, communication, and understanding of version control practices in collaborative software development.
