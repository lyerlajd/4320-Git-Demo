# Git Demo in Class

This repository explains several git commands from INFOTC 4320 - Software Engineering

## Topics

### Cloning a Repository:
1. On GitHub, click the green **<> Code** button and copy the HTTPS
2. In the VS Code terminal, enter **git clone [paste HTTPS link]**
3. In the VS Code terminal, navigate to the correct folder, then enter **ls** to check that the repository was copied
> entering clear in the VS Code terminal will clear the terminal screen but won't delete anything

### Pulling from a Repository to a Clone:
1. In the VS Code terminal, enter **git pull**
2. This will download any changes from the repository
> For help overriding files, go to this link [reddit: How do I force "git pull" to overwrite local files?](https://stackoverflow.com/questions/1125968/how-do-i-force-git-pull-to-overwrite-local-files)

### Checking Your Status
1. In the VS Code terminal, enter **git status**
2. This will send a message that has the status of the repository
- Modified: A file from the repository that you have edited locally but not pushed to the repository
- Untracked: A file that was created locally and the repository does not possess the file at all

### Adding Files to a Repository
1. In the VS Code terminal, enter **git add [fileName.type]**
> **git add .** will add all files in the current directory

### Committing Changes to a Repository
1. In the VS Code terminal, enter **git commit -m "title" -m "desciption"**
> Each commit needs at least one -m message
2. Finally, in the VS Code terminal, enter **git push** to push your local repository to the one on GitHub