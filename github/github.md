---
layout: page
title: Gitting Down with GitHub and 9 Dots
permalink: /github/
---

#### Traditionally, when learning a new programming language, you first figure out how to print out "Hello, world!" We're going to try something a bit different.

### Git on [GitHub](https://github.com/)!

If you already have a GitHub account, [log in](https://github.com/login)!

If you don't, [sign up](https://github.com/join?source=header-home)!

1. You should use one of **your** email addresses (not your work email).
2. Select the **Unlimited public repositories for free** option.
3. Verify your email.

### Fork this website's [repository](https://github.com/julescubtree/coding-coordinator-hello-world/)

A repository (repo for short) is a collection of the source code for a software project.

To fork a repo is to make your own copy.

In the open source world, you're encouraged to build on existing code and contribute code back to the community. In a little bit, you're going to do just that, and you'll start by editing your copy of the code.

Click that **Fork** button! ![fork]({{ "/github/fork_button.jpg" | relative_url }})

### Find **your** file

In our repo, and now in yours, there's a file just for you. Can you find it? You'll need to

* find your fork of our repo (maybe find your own GitHub profile page first?)
* poke around in some code and some folders

If you find it really fast, and others in your coding coordinator cohort could use some help, help away.

### Make your file your own

![edit your file]({{ "/github/Edit_file.png" | relative_url }})

Once you've found your file, edit it! You're free to be ultra-traditional and leave "Hello, world!" in there, but you don't have to.

There's a header section up top marked by three hyphens on the top and the bottom; there you can change the page title.

You're also free to change anything outside the header. The file is in a language called [Markdown](https://daringfireball.net/projects/markdown/), which is designed to streamline formatting for websites. (It's certainly quicker than HTML, which is a mark*up* language—hence the nerdy punny name.) You can check out this sweet [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), or even the [source code](https://raw.githubusercontent.com/julescubtree/coding-coordinator-hello-world/gh-pages/github/github.md) of this web page to see **some** *things you can do*.

When you're done editing, you're going to commit (i.e. save) your changes way down at the bottom. Select the option to **Commit directly** to the current branch.

![commit your changes]({{ "/github/Commit_changes.png" | relative_url }})

### Submit a pull request

This means you've made a change in another copy (yours, in this case) of the source code, and you'd like for whoever's in charge to "pull" it into the main version.

To make a pull request, you'll

* head back to the original project repo
* find a button that says **New pull request**—one is immediately visible, and you might stumble upon the other if you clicked on something related to pull requests
* click **![compare across forks]({{ "/github/compare-across-forks-link.png" | relative_url }})**
* on the left, make sure your base fork is **julescubtree/coding-coordinator-hello-world** and your base branch is **gh-pages**
* on the right, make sure the head fork is your own, with base branch **gh-pages**
* enter a title and description for your pull request ![pull request title and description]({{ "/github/pullrequest-description.png" | relative_url }})
* click **![Create pull request]({{ "/github/pullrequest-send.png" | relative_url }})**

### Now what?

Will your pull request be accepted? While waiting and seeing, feel free to explore the repo some more. You might stumble upon others' pull requests—definitely take a look, and add comments to them if you like. Do you want to try editing parts of the code? Go ahead.

If all goes according to plan—if you've submitted a worthy pull request—it should be accepted, and maybe you'll have another surprise in store.
