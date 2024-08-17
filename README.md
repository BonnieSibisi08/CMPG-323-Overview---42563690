# PROJECT 1: OVERVIEW

### Structuring of Projects:
Multiple repositories will be created, each project will have its own repository. All repository will be linked under one Kanban project so the progress of each project can be tracked easily.

- Project 1 (Agile & Scrum Implementation): This repository  
- Project 2 (Web API Development): [CMPG-323-Project-2-Web-API-42563690 ](https://github.com/BonnieSibisi08/CMPG-323-Project-2-Web-API---42563690)  
- Project 3 (Patterns & Standards): [CMPG-323-Project-3--42563690 ](https://github.com/BonnieSibisi08/CMPG-323-Project-3--42563690)   
- Project 4 (RPA & Testing): [CMPG-323-Project-4---42563690 ](https://github.com/BonnieSibisi08/CMPG-323-Project-4---42563690)   
- Project 5 (Reporting & Monitoring): [CMPG-323-Project-5---42563690 ](https://github.com/BonnieSibisi08/CMPG-323-Project-5---42563690)   

The diagram below shows how all repositories will be linked to the Kanban Guide project. This is how I will my work will be structrured through out the semester.  
![projStruct drawio](https://github.com/user-attachments/assets/a360aba5-27bd-4c83-916c-d8f22320e70f)    

### Documentation
The link to the documentation I have created:  
[Lean document](https://docs.google.com/document/d/1UF9rpYQHOIypGd4BshBgNmWwu8SEWhkD/edit?usp=sharing&ouid=104985369547771360207&rtpof=true&sd=true)  

### Branching Strategy
As these are individual projects, the branching strategy I have decided to use is the Github Flow. Although it does have its disadvantages but there are reasons for choosing this strategy.  
- This strategy allows quick recovery of issues, if there is an error with a release you can quickly rollback to the previous one.  
- Since the code deployed is way less, it eliminates a lot of errors.  
- This strategy is particularly effective for small teams/indivudual projects. Since this is an individual project it will work perfectly, this can be a drawback if you have a big team as it will be hard to keep everyone on the same page all the time.

The diagram below depicts the branching strategy to be used throughout the project.  
![branchStrategyFlow drawio (1)](https://github.com/user-attachments/assets/83eabb72-6746-4d25-b961-19b8c57b300f)   

### The Use of Gitignore's
Each project will contain its own .gitignore file. I will be using them throughout the semester as I am working on each project, simply because the are very important.  
Gitignore files are crucial for a few reasons:

1. **Keeps Unnecessary Files Out**: They stop unnecessary files, like temporary files and local settings, from being tracked by Git. This will help keep my repository clean and focused on the important source code and files.
2. **Manages Repository Size**: By leaving out large and unnecessary files, the .gitignore file helps keep the repository size manageable, which boosts Git's performance and efficiency.
3. **Enhances Security**: Sensitive information like passwords, API keys, and personal data can be kept out of the repository, preventing accidental leaks of confidential info.
4. **Simplifies Workflow**: When developing, I can work locally without worrying about accidentally committing unwanted files, which allows me to focus on coding and other important tasks.  

### Storage of Credentials and Sensitive Information
The .gitignore files is initially intended to allow developers to filter out certain files that should not be committed, and it can be used (among other things) to prevent files that with disclose secrets from being leaked. I will make use of the gitignore files to store sensitive information. I will also make use of Github Secrets for the store login credentials. Sensitive information will also not be hardcoded in my source code, rather I will make use of environmental variables effectively.

### Burndown Chart
Below is a burndown chart I have created using excel. I will update the chart regularly as I progress throughout the semester. This will help me to keep track of my progress, as I will be able to compare the planned tasks with tasks in progress or completed.  

![Screenshot 2024-08-16 124329](https://github.com/user-attachments/assets/9562271b-94e4-4a9a-9ff6-b395b678f2a9)

### References
Below is a list of references which I used in research of the branching strategies, .gitignore files and other important information.

- https://youtu.be/gW6dFpTMk8s?si=TD3x_kq714NBE-_m
- https://www.abtasty.com/blog/git-branching-strategies/
- Vincent, W. S. (2022). Django for Professionals. Still River Press.
- Meli, M., McNiece, M. R., & Reaves, B. (2019, February). How bad can it git? characterizing secret leakage in public github repositories. In NDSS.
- https://www.visual-paradigm.com/scrum/scrum-burndown-chart/  
