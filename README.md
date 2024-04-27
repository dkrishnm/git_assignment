# Git Assignment - dkrishnm

a. What is an issue?

Issues are items/ tasks created in a repository to track work and progress. These help in collboration with team mates, share feedbacks.

b. What is a pull request?

 Pull requests are used to suggest/receive changes to a project. They also can be used to address issues in pull requests, such as merge conflicts. Pull requests can be used to let know reviewers about changes pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.

c. How do I open up a pull request?

 1. Create a feature branch from the main branch to work on the changes. Once the changes are committed and pushed to the feature branch, go to the forked repository on GitHub.
 2. Click on the compare "Compare & pull request" button on the feature branch
 3. Review the changes made and hit "Create pull request" button
 4. Add description to the PR and update the reviewers if need be.
 5. Submit the PR 
 6. once the review comments if any are addressed merge to the default main branch


d. Give me a step by step guide on how to add someone to your repository.

   1. Know the collborators GitHub username
   2. Navigate to the Repository -> Click on Settings -> In the access section click on Collaborators- > Click on Add    people-> Type in the collaborator username -> Add name
   3. Once the user accepts the email invitation, the user will have access to your repository



e. What is the difference between git and GitHub?

GitHub is a cloud-based platform where you can store, share, and work together with others to write code.Collaborative working on GITHUB is made possible by the open-source software, Git, upon which GitHub is built.

Git is a version control system that intelligently tracks changes in files. Git is particularly useful when you and a group of people are all making changes to the same files at the same time.

When you upload files to GitHub, you'll store them in a "Git repository." This means that when you make changes (or "commits") to your files in GitHub, Git will automatically start to track and manage your changes.


f. What does git diff do?

git diff lists out the changes between the current working directory and staging area.

Commands to show diff in GIT

git diff [<options>] [<commit>] [--] [<path>…​]
git diff [<options>] --cached [--merge-base] [<commit>] [--] [<path>…​]
git diff [<options>] [--merge-base] <commit> [<commit>…​] <commit> [--] [<path>…​]
git diff [<options>] <commit>…​<commit> [--] [<path>…​]
git diff [<options>] <blob> <blob>
git diff [<options>] --no-index [--] <path> <path>

g. What is the main branch?

GitHub creates the repository with a single branch. This first branch in the repository is the default branch. The default branch is the branch that GitHub displays when anyone visits your repository. The default branch is also the initial branch that Git checks out locally when someone clones the repository. The default branch is named as the main branch in any repoistory.


h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?


It is best to create a feature branch, complete the task and then create a pull request to the main branch and open it for comments from peer reviewers. Once approved can merge the code to the main branch. This would help in maintaining a  main branch which is always production ready.