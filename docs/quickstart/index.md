# Beavercreek Coding Quickstart

## Prerequisitites  

Before you can create a project and clone it to your computer, you'll need to complete these steps:

1. With your parent's permission, setup your own user account on [github](https://github.com). For the rest of these steps, we assume you are logged into github.
2. Request to join our [Beavercreek Robotics team site](https://github.com/Beavercreek-Robotics)
3. If you are using a Windows computer, install [TortoiseGit](https://tortoisegit.org/). Note that you might need to reboot.
4. Install one of the VEXcode Options:

    1. The [VS Code Extension](https://www.vexrobotics.com/vexcode/vscode-extension) which requires installing [VS Code](https://code.visualstudio.com/). VEX hosts an [installation guide for vscode](https://kb.vex.com/hc/en-us/articles/8608960771092-V5-VS-Code-Installation-Guide).
    2. Install the [VEXcode Pro V5](https://www.vexrobotics.com/vexcode/install/v5)

## Starting a New Robot Project

There are several ways to start a new project.  Since we want to use the VEXcode v5 templates, we're going to start with a copy on your local computer, then import it into github.  It will look something like this:

![git project flow](/static/git-project-flow.png)

You will do your work in the VEX editor (or VSCode) and that will edit files in a local folder.  Git will then synchronize all those file changes to github.

1. Create a project for your team to use this year. DO NOT "Initialize with a Readme or a license." We want this to be blank. The project name should include:

    1. The competition season
    2. Your team name

    ![New Repository Settings](/static/github-new-repository-settings.png)

2. <a id="local-dir">Browse to a folder</a> on your computer where you have your VEXcode V5 project.  `[[Shift]] Right-click` in your code's folder and chose `Git create repository here...`: ![Context menu showing tortoise Git Create Repository](/static/tortoise-git-shift-right-click.png). Ignore the "Make it bare" option. Leave it unchecked.
3. Right-click, navigate to Tortoise Git, and chose `Switch/Checkout`. Then Create a New Branch named `main`.
    ![Tortoise Git dialog with "Create New Branch" checked](/static/tortoise-git-createmain-branch.png)
4. `Right-click` then chose `Commit -> "main"` from the Tortoise git menu.  Click `All` above the list of files and enter a message like "Initial commit of code" as your commit message. Click OK.
5. In the project on github, copy the https link to your repository as shown here: ![Click code, then https](/static/github-code-https.png)
6. In your project folder on your local computer, `Right-Click`, then chose `Sync` from the Tortoise Git menu. Paste your project's url into `Remote URL`, then click `Push`.

If all goes well, your local files should be copied to the github server and preserved and shared.  From here on out, you'll use "Commit" and "Push" or "Pull." For a description of how git works, see [Resources](/resources#tracking-code-versions).

## New Project in VEXcode Pro

In `VEXCode Pro`, Click the new project option. Chose the project options.  Once you're done, return to [step 2 above](#local-dir).

## Opening your Project in VSCode

Assuming you've installed the VSCode VEX extension according to the instructions above, you'll have the VEX icon on your sidebar. Click it, then import a project.  Browse to the directory where you cloned your vex repository and open your `v5code` file.

![VSCode UI](/static/vscode-import-screenshot.png)

## Opening Your Project in VEXcode Pro

In `VEXCode Pro`, Open the directory where you cloned your project and begin to code.

## Opening your Project in VSCode

Assuming you've installed the VSCode VEX extension according to the instructions above, you'll have the VEX icon on your sidebar. Click it, then import a project.  Browse to the directory where you cloned your vex repository and open your `v5code` file.

![VSCode UI](/static/vscode-import-screenshot.png)
