## A Simple Git Workflow

For each new project, create an empty folder using your IDE or a command-line interface such as PowerShell or WSL. Enter the folder and create a Markdown file. Start with skeleton notes describing the project, goals, ideas, or requirements before writing code.

Initialize Git:

```bash
git init
```

Run this in your IDE terminal or from your command line. This creates a local Git repository for your project.

Make your first commit:

```bash
git add .
git commit -m "First commit"
```

At this point, nothing has been pushed to GitHub. You're simply creating a local history of your work. Commit early and commit often. Frequent commits make it easier to experiment, understand how your project evolved, and recover from mistakes.

Once you've learned to create a local history of your work, the next step is to learn to set up a remote repo and connect the two.

Git/version control does not only work with Github. There are alternatives, but it's a well-known version control system and workflow.

## Git Push, Git Pull, and Pull Requests

`git push` sends your local commits to a remote Git repository, such as GitHub. `git pull` retrieves changes from the remote repository and updates your local branch.

A pull request is different. Rather than moving code, it is a collaborative workflow for proposing changes, reviewing code, discussing implementation details, and ultimately merging one branch into another.

In many projects, the `main` branch serves as the primary source of truth. Changes are typically developed on feature branches, reviewed through pull requests, and merged into `main` once they have been approved.

