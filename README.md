Hello， git_assignment
Hello, again



a. What is an issue?
An issue is a way to keep track of tasks, improvements, and bugs in your projects. It’s like a to-do list where you can discuss new features, report problems, or ask questions. You can assign issues to team members, add labels, and link them to pull requests.

b. What is a pull request?
It is  a way to propose changes to a project. It lets your team know that you’ve finished a feature or bug fix and want it reviewed before merging it into the main codebase.

c. Describe the steps to open a pull request?
1. Fork the repo, clone the repo and create a branch Make a new branch for your changes using git checkout -b branch-name.
2. Make changes on the file, then push changes - Push the branch to the forked repository using git push origin branch-name.
3. Open a pull request: Go to the original repository on GitHub, click on the “Pull requests” tab, and then “New pull request”. Choose your branch and create the PR with a title and description.

d. Describe the steps to add a collaborator to a repository (share write permissions)
Go to the repo > Settings > Manage access > Invite a collaborator > Enter username or email of the person want to add > Add collaborator > The person accept the email invitation on email > the person will have write access

e. What is the difference between git and GitHub?
Git: A version control system that tracks changes in your code. It works locally on computer.
GitHub: A platform that hosts Git repositories online, providing a web interface for Git. It helps with collaboration, code review, and project management.

f. What does git diff do?
It shows the differences between commits, branches, or files. It’s useful for seeing what changes have been made but not yet committed, or for comparing changes between branches or commits.

g. What is the main branch?
It is the default branch in a Git repository. It usually represents the production-ready state of the code and is where the final version of the project is maintained.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
Would be better not to pushing changes directly to the main branch, especially in a team work. Better to create a new branch for my changes, commit the work there, and then open a pull request to merge the changes into the main branch. This allows for code review and testing before the changes are integrated.