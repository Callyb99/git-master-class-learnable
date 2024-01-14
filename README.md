# git-master-class-learnable
# Version control

Version control is a system that tracks changes to files over time, allowing multiple contributors to collaborate on a project. It helps manage different versions of files, track changes, and enables teams to work on the same codebase efficiently. Popular version control systems include Git and SVN. Developers can create branches to work on specific features, and the system keeps a history of changes, making it easy to revert to previous states if needed. This ensures collaboration, accountability, and a structured approach to software development.

# explain the difference between git and github

Git is a distributed version control system that allows developers to track changes in their source code during software development. It enables collaboration among multiple developers on a project by providing tools to manage and merge code.

GitHub, on the other hand, is a web-based platform that utilizes Git for version control. It serves as a hosting service for Git repositories, making it easier for developers to collaborate, contribute, and manage their code. GitHub provides additional features like issue tracking, project management, and collaboration tools beyond what Git offers locally.

# Other GitHub alternatives are

1) GitLab
2) Bitbucket
3) SourceForge

# Difference between git Fetch and git pull

git fetch and git pull are both Git commands used to update your local repository with changes from a remote repository, but they have key differences:

git fetch: This command retrieves the latest changes from the remote repository, but it does not automatically merge them into your working branch. It updates your remote-tracking branches (e.g., origin/main) with the latest changes, allowing you to inspect them before deciding to merge. It's a safe way to see what has changed without making any immediate modifications to your working directory.

git pull: This command, on the other hand, not only fetches the latest changes from the remote repository but also automatically merges them into your current working branch. It's a combination of git fetch and git merge. While convenient, it might lead to unexpected conflicts if your local changes conflict with the remote changes.

# Explain in simple terms git rebase and the command for it

 Git rebase is a way to integrate changes from one branch into another. It helps streamline your project's commit history. The basic command for interactive rebase is:


git rebase -i <base_branch>

This command lets you interactively choose which commits to pick, edit, or squash onto the specified base branch.

# Explain in simple terms git cherry-pick and the command for it

Git cherry-pick is a command that lets you apply a specific commit from one branch to another. It's like picking a commit from one branch and placing it onto another.

Here's the basic command:


git cherry-pick <commit-hash>

Replace <commit-hash> with the actual hash of the commit you want to cherry-pick.

This is useful when you want to bring changes from one branch into another without merging the entire branch.