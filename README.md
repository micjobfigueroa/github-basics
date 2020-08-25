# git and GitHub

_(version control, collaboration, and open source)_

**what is Git and GitHub?**

GitHub is a website for hosting and collaborating on projects.
And Git is a version control system that's typically used with GitHub.
There's millions of projects on GitHub right now like J-Query, Swift, and Node.

**What's the best part of using Git and GitHub on a team?**

With Git every developer has a local copy of the repository on their computer.
And then as they make changes they can upload those changes to GitHub and
share them with a larger team.
GitHub also has other collaboration features like issues and pull requests that help teams collaborate more effectively.

**What about open source software? What is it, and how do you use it?**

open source software is software that has been licensed so the community can use it and make changes to it.
Projects like Rails, Note, and Apache are open source projects.
You can pull down the code, make some changes, and then contribute back to the main project so the larger community can benefit.
GitHub has millions of open source projects that you can read and use right now.

## Git Configuration:

```
git --version
git config --list
git config --global user.name "Firstname Lastname"
git config --global user.email "email associated with your GitHub account"

```

## Git Commands:

```
git init: initialize a git repository in your directory
git status: check the status of the repository
git add file_name: add one file
git add .: add all files
git commit -m “commit message”: commit your files along with a message
git remote add origin https://github.com/username/reponame.git - the remote url to your GitHub repo
git push origin master: push your files up to github on the master branch
```

## Markdown:

- [GitHub Guide to Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Markdown Cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
- [Emoji Cheatsheet](https://www.webfx.com/tools/emoji-cheat-sheet/)
- [Daring Fireball Markdown Basics](https://daringfireball.net/projects/markdown/basics)

## Create a Branch

```
git branch
* list out branches

git branch branch-name
* create a new branch

git checkout branch-name
* switch to the newly created branch

git checkout -b branch-name
* shortcut! - use this command to create & switch to the new branch

git push origin branch-name
* push branch & changes to github
```
