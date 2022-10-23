# Introduction to Git

This repository is an introduction to git and GitHub.
There are no prerequisites required.

If you want to learn more about version control, git and why to use it in software development, I recommend these tutorials from Atlassian:

- [What is version control](https://www.atlassian.com/git/tutorials/what-is-version-control)
- [Source code management](https://www.atlassian.com/git/tutorials/source-code-management)
- [What is git](https://www.atlassian.com/git/tutorials/what-is-git)

In general, I found the [Atlassian](https://www.atlassian.com/git) and [GitHub](https://github.com/git-guides) tutorials very helpful when it comes to learn git and how to use it. Next to the official [Documentation](https://git-scm.com/docs) and [Guide](https://git-scm.com/book/en/v2) from git itself.

## Setting up a GitHub account and cloning a repository

In this section, you will learn how to create your own GitHub Account and set it up to clone a repository to your PC.
But before we start, you should read this [introduction](https://docs.github.com/en/get-started/using-git/about-git) to git and GitHub (until _GitHub and the command line_), to get an understanding about why you should use it and what you can gain from it.

1. Create a free GitHub account - [Join GitHub](https://github.com/join)
2. Generate SSH keys and connect them with your GitHub account - [How to add SSH keys to your GitHub Account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)  
   Additional tutorials that maybe of help here:
   - [Generate SSH keys - by GitHub](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=linux) or [Generate SSH keys - by Atlassian](https://www.atlassian.com/git/tutorials/git-ssh)
3. Clone this repository to your PC - [How to clone a repository from GitHub](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)

Bravo, now you can follow this guide on your own computer. Therefor, open the repository in an IDE of your choosing, like _IntelliJ_ or _VS Code_.


## Create your own repository and publish it on GitHub

in this section, you will learn the basic principles of git and how to use it on your local PC. We will do that with the help of an example repository

1. Create your own repository - [Init your own repository](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-init).  
   You can skip the explanation about _Bare repositories_, later GitHub will do that for us. The name and purpose of the example repository (project) is up to you. For example, mine was about a cat feeding schedule.
2. Add a _README.md_ file to your repository - [What is a README.md and how to write a good one](https://bulldogjob.com/readme/how-to-write-a-good-readme-for-your-github-project)  
   This is a very lengthy explanation of README, for us only the beginning until _Writing a good README..._ is relevant. Also, you don't have to include all sections the tutorial is talking about. For now, it is fine if you only include a Title and a short Introduction/Text.
   - Use this [Markdown Cheat Sheet](https://github.com/hnsreeny/markdown/blob/master/markdown-cheatsheet-online.pdf) if you like.
   - For more information about Markdown, have a look at [Getting Started with Markdown](https://www.markdownguide.org/getting-started/)
3. Save the README.md to the repository   
   For that, use `git commit` and `git add` - [Explanation of basic git commands](https://docs.github.com/en/get-started/using-git/about-git#basic-git-commands) & [Example of contributing to a repository](https://github.com/git-guides/git-commit)  
   Here we tap in to the power and complexity of git. More detailed explanations about this process can be found here:

   - By GitHub: [git add](https://github.com/git-guides/git-add), [git commit](https://github.com/git-guides/git-commit)
   - By Atlassian: [git add](https://www.atlassian.com/git/tutorials/saving-changes), [git commit](https://www.atlassian.com/git/tutorials/saving-changes/git-commit)
4. Publish your repository on GitHub - [Create a new repository on GitHub](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)
   1. Create the public repository without any files
   2. Visit your GitHub repository after creation. GitHub will give you examples on how to populate it. Go with the _push an existing repository_ example.
   3. Don't worry about the LICENSE and .gitignore file, we will add them later.
      - But if you can't wait, I usually use the [MIT](https://choosealicense.com/licenses/mit/) license - [Licensing a repository](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)

Well done, your README is now out there on the internet,  if you have a peer, checkout his Repository ;)

## One warning and two tips
The warning first:
**Never add, commit or push sensitive information in your repository!!!**  
Sensitive information can be Passwords, SSH keys, API keys, credit card numbers, PINs and more.
Because of the nature of git, it is hard to delete something once it is pushed. If it happened any way, don't worry, there are plenty of guides to help you in this situation, for example this one - [Remove sensitive data from a repository].

**Now the tips:**
1. If you ever found your self lost in git and don\`t know what is going on, use `git status`. It will tell you what is going on and sometimes even provides tips what to do next. - [What does 'git status' do?](https://github.com/git-guides/git-status)
2. If the CLI (Command Line Interface) isn't your home, you can use a GUI (Graphical User Interface) to manage your repository. Modern IDEs (integrated development environment) mostly have a GUI for git included. Or you can use tools like [Fork](https://git-fork.com/home) or [GitKraken](https://www.gitkraken.com/).


## Next Steps

Now that we up to speed with git and GitHub, you can, checkout the [BOGY-express](https://github.com/SputnikTea/BOGY-express) repository and start writing a backend Server with JavaScript.

## Optional:

If you still have time, you can follow the tutorials in this section to learn more about git.

### What are branches and how to use them

1. Create a branch - [git branch](https://www.atlassian.com/git/tutorials/using-branches)
2. Checkout another branch - [git checkout](https://www.atlassian.com/git/tutorials/using-branches/git-checkout)
3. Merge your branch back to `main` - [git merge](https://www.atlassian.com/git/tutorials/using-branches/git-merge)

### How to use a remote repository

1. See if there are any updates from other contributors - [git fetch/pull](https://github.com/git-guides/git-pull)
2. Upload your changes to GitHub (the remote repository) - [git push](https://github.com/git-guides/git-push)

