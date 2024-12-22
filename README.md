# Git-task
<!-- What is Version Control? -->
Version control, also known as source control, is the practice of tracking and managing changes to software code. It is an essential tool for software development, enabling teams to work collaboratively and efficiently. Version control systems (VCS) are software tools that help manage changes to source code over time

<!-- Explain difference between git and github -->
*Git: Git is a distributed version control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows.
*GitHub: GitHub is a web-based Git repository hosting service, which offers all of the distributed revision control and source code management (SCM) functionality of Git as well as adding its own features.

<!-- List 3 other github alternatives -->
*Azure DevOps 
*GitLab
*GitKraken Git GUI & Git Hosting

<!-- Explain the difference between git fetch and git pull -->
*Git fetch: This is a git command that allows you to contact the remote repository and fetches all new command all new commits, all branches, all all tags from it but doesn't merge or update your working repository
*Git pull: This is a git command that allows you to contact and fetch the remote repository and then it automatically merges the changes to the current branch

<!-- Explain in simple terms git rebase and the command for it -->
Git rebase in simple terms can be defined as a powerful git tool which is used to move or combine a series of commits from one branch to another. Unlike merging, which creates a new commit to combine the histories of two branches, rebasing moves or replays commits from one branch onto another, resulting in a linear and cleaner project history.
The command used for For example, if you want to rebase the experiment branch onto the master branch, you would use the following commands:
$ git checkout experiment
$ git rebase master

<!-- Explain in simple terms git cherry-pick and the command for it -->
Git cherry-pick in simple terms is a powerful git comman that allows you to select a specific commits from one branch and apply them to another branch.
The command for git cherry-pick is *git cherry-pick <commit-hash>*

