# git_assignment_HeroVired
Repository for Git &amp; GitHub assignment

This repository contains the detailed steps performed to complete each task

Assignment related steps should be clearly mentioned in the README.md file of the GitHub repository with steps performed to complete each task

1. Calculator plus application
   --> "git_assignment_HeroVired" repository is created in Github
   --> cloned repository to local using "Git clone https://github.com/SyamalaKadmi/git_assignment_HeroVired.git"
   --> created dev branch using "Git checkout -b dev"
   --> created a python file CalculatorPlus.py which contains basic arithmetic operations
   --> committed the changes using "git commit -am "Calcuator with basic arithmetic operations"
   --> Pushed the branch to Github using "git push --set-upstream origin dev"
   --> Branch protection rule is enabled on dev branch for mandatory pull request & code review
   --> Merged this to main branch using "git checkout main" & "git merge dev"
   --> Created 1st version of release with "calculator_plus_app_v1" tag
   --> Added one of the class members as collaborators
   --> created feature/sqrt branch using "git checkout -b feature/sqrt" for implementing sqrt functionality
   --> updated the calculatorPlus.py file with sqrt functionality
   --> committed the changes using "git commit -am "Calcuator with sqrt operations"
   --> Pushed the branch to Github using "git push --set-upstream origin feature/sqrt"
   --> For bug fix in dev branch, "git checkout dev"
   --> Fixed divide functionality and committed & psuhed the changes to remote dev branch
   --> The bug fix is merged to feature/sqrt branch and a pull request with code review is submitted to merge to main branch
   --> After pull request is approved, "feature/sqrt" branch is merged into the ‘dev’ branch.
   --> Dev branch is merged to main branch
   --> Created 2nd version of release with "calculator_plus_app_v2" tag

2.  Git LFS (Large File Storage) integration
   --> Created a new branch "lfs" in local Git "git checkout -b lfs"
   --> Downloaded a large binary file of size > 200 MB
   --> To integrate Git LFS, git lfs track "*.bin" --> extension type
   --> It creates .gitattribute file with detailed of lfs tracked files
   --> add the binary file & .gitattribute file to the repository by following the below steps
        git add .
        git commit -m "Adding large binary files to the repository"
        git push --set-upstream origin lfs
   --> clone the repository in another machine and verified the files are downloaded correctly
   
