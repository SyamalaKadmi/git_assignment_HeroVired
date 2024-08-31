# git_assignment_HeroVired
Repository for Git &amp; GitHub assignment

This repository contains the detailed steps performed to complete each task

Assignment related steps should be clearly mentioned in the README.md file of the GitHub repository with steps performed to complete each task

**Calculator plus application**
  1. "git_assignment_HeroVired" repository is created in Github
  2. cloned repository to local using "Git clone https://github.com/SyamalaKadmi/git_assignment_HeroVired.git"
  3. created dev branch using "Git checkout -b dev"
  4. created a python file CalculatorPlus.py which contains basic arithmetic operations
  5. committed the changes using "git commit -am "Calcuator with basic arithmetic operations"
  6. Pushed the branch to Github using "git push --set-upstream origin dev"
  7. Branch protection rule is enabled on dev branch for mandatory pull request & code review
  8. Merged this to main branch using "git checkout main" & "git merge dev"
  9. Created 1st version of release with "calculator_plus_app_v1" tag
  10. Added one of the class members as collaborators
  11. created feature/sqrt branch using "git checkout -b feature/sqrt" for implementing sqrt functionality
  12. updated the calculatorPlus.py file with sqrt functionality
  13. committed the changes using "git commit -am "Calcuator with sqrt operations"
  14. Pushed the branch to Github using "git push --set-upstream origin feature/sqrt"
  15. For bug fix in dev branch, "git checkout dev"
  16. Fixed divide functionality and committed & psuhed the changes to remote dev branch
  17. The bug fix is merged to feature/sqrt branch and a pull request with code review is submitted to merge to main branch
  18. After pull request is approved, "feature/sqrt" branch is merged into the ‘dev’ branch.
  19. Dev branch is merged to main branch
  20. Created 2nd version of release with "calculator_plus_app_v2" tag

**Git LFS (Large File Storage) integration**
  1. Created a new branch "lfs" in local Git "git checkout -b lfs"
  2. Downloaded a large binary file of size > 200 MB
  3. To integrate Git LFS, git lfs track "*.bin" --> extension type
  4. It creates .gitattribute file with detailed of lfs tracked files
  5. add the binary file & .gitattribute file to the repository by following the below steps
        git add .
        git commit -m "Adding large binary files to the repository"
        git push --set-upstream origin lfs
  6. clone the repository in another machine and verified the files are downloaded correctly

**Geometry Calculator**
  1. Created a new branch named "feature/circle-area" to work on the circle area feature - git checkout -b feature/circle-area
  2. Added a new file "geometry-calculator.py" and added the changes --> git add .
  3. stashed the changes using "git stash" and ensured the working directory is clean using "git status"
  4. Created a new branch named "feature/rectangle-area" to work on the rectangle area --> git checkout -b feature/rectangle-are
  5. Added the rectangle area changes using git add .
  6. stashed the changes using "git stash" and ensured the working directory is clean using "git status"
  7. switched to feature/circle-area using git checkout feature/circle-area
  8. retrieved the stashed changes using "git stash pop"
  9. committed the changes and pushed the changes to remote using --> "git commit -m "message" & git push --set-upstream origin feature/circle-area"
  10. Repeat the same steps from 7 to 9 for feature/rectangle-area
  11. Created pull requests from feature/rectangle-area & feature/circle-area to dev branch and had them reviewed by a peer
  12. Merged the dev branch to main branch

   
