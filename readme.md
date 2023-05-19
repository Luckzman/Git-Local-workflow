Steps for code review

-   create a new branch of your master branch
-   commit your change i.e git add . && git commit -m "message"
-   push your changes to github
-   create a pull request against your master branch.

Git Workflow
There are three categories of branches

1. Production branch: master branch | main branch (only merge from develop branch into this branch)
2. Development branch: develop branch | staging branch (Don't push directly to this branch)
3. Feature branch: bug_fix/feature/chore (developers work on)
   git checkout -b develop
   git push --set-upstream origin develop
