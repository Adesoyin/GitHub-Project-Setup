# GitHub-Project-Setup
This project is created to learn and practice the installation of Git, GitHub Distributed Version Control Exercise.  Also to practice the staged, modified and committed types of activities.

# Git Installation
Git can be downloaded from [this embedded link](https://git-scm.com/downloads/) After Installation. Follow the steps below to creating a repository and local folder repository.

**Steps**
1. Click on + sign on your Github account from the profile
2. Enter your preferred repository name e.g., "_GitHub Project Setup_"
3. Add description (optional)
4. Change visibilty to preferred state (public or private)
5. Add ReadMe (Optional) which can be used for longer desription of the project (advisable). And clcik on _**create repository**_
   <img width="797" height="832" alt="image" src="https://github.com/user-attachments/assets/954c4741-f16c-4c1e-b4cb-e60a141a1494" />

6. Open your command prompt or gitbash to run some command, creating folder for hosting your project in your local desktop or create a folder in Visual studio code, ensure your terminal is running on gitbash.
   <img width="1018" height="286" alt="image" src="https://github.com/user-attachments/assets/62c4e7b5-5f80-402d-bb35-953e82a69a0a" />
   <img width="1845" height="574" alt="image" src="https://github.com/user-attachments/assets/f4d483c3-0cc8-4589-98d0-27f8c8af4d25" />

7. Create new files e.g., .gitignore that ensures all secrets are hidden from the pubblic, add hidden files there; main.py to write codes; 
  
8. It is advisable to create a virtual environment in your local repo. This will ensure all packages installed is only applicable to the current project to avoid global interference with other projects.
   
     To create the venv (virtual environment): follow the script below:
   
      python -m venv <venv; name of folder for the virtual environment>
   
      source venv/Scripts/activate    (To activate the venv)
   
      pip freeze > requirement.txt  (This will redirect every installed package in venv folder to requirement.txt)
   
9. Add python script in your main.py and commit to staging for tracking process.
    
       git status (to see the status of the project in your local environment)
   
       git init  (to initialized empty git repository)
    
   <img width="752" height="79" alt="image" src="https://github.com/user-attachments/assets/63d9ee42-c879-41f9-9955-fd12152d9433" />
   
10. To track every changes in the staging

<img width="607" height="59" alt="image" src="https://github.com/user-attachments/assets/9385be6b-4c11-4a3e-830e-e88031088c8d" />

<img width="646" height="105" alt="image" src="https://github.com/user-attachments/assets/2e91b3d4-b6c9-4ef4-9c11-fe58d256add5" />

11. Linking up the local repo changes with the remote repo on github, copy the url link of the created repo from github.
    




