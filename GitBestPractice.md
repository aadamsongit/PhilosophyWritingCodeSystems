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
