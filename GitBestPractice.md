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

## Know How to Yak Shave

Yak shaving is the process of solving a series of smaller, often unexpected problems before you can solve the problem you originally intended to work on. It is a normal part of software engineering.

Whether you're working manually or using AI-assisted engineering tools, you'll frequently encounter these detours.

For example, your PostgreSQL container won't start. Before debugging PostgreSQL itself, verify that Docker Desktop is running. Check that another PostgreSQL process isn't already using the port. Confirm you're in the correct development environment. On Windows, PowerShell is often the simplest place to investigate running processes. A colleague on macOS will likely have a different debugging workflow.

Good engineers learn to recognize when they're yak shaving, work methodically through the dependencies, and then return to the original problem rather than becoming lost in the detour.

This is also why experienced developers care so much about project organization. Consistent folder structures, naming conventions, and predictable workflows reduce unnecessary yak shaving by making it easier to find code, understand a project, and identify where problems are actually coming from.

## Other Prototyping Layers

Figma is a collaborative interface design and prototyping tool that has become a standard part of many frontend workflows. It is also an impressively sophisticated web application in its own right, blending high-performance systems engineering with modern frontend technologies.

Visual prototyping is often a valuable step before implementation. Sketching layouts, user flows, and interactions in Figma can expose usability issues, clarify requirements, and improve communication long before code is written. Like any tool, it has tradeoffs, but there is significant value in exploring ideas visually before committing to an implementation.

Miro provides another layer of prototyping. It excels at flowcharts, system diagrams, and process mapping, making it particularly useful for automation workflows, integrations, and larger architectural discussions. Sometimes the best way to understand a complex system is to draw it before attempting to build it.



