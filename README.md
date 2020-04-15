# Terminal & Shell

As a developer, your shell is your best friend. For those that don't know, a shell is a computer program that takes commands and performs actions based on them. On Windows, you may have seen this before in `Powershell` or `cmd`. On Mac/Linux, this is commonly `bash`, although there are others.

A terminal is a graphical program that accepts inputs, and sends those inputs to a shell

We will be using the `bash` shell throughout the lessons, because it's available on all platforms.

> If you're on windows, you will have to visit [this](https://docs.microsoft.com/en-us/windows/wsl/install-win10) and follow the instructions to install the `Ubuntu` shell on your system

## Setup

Learn how to open a terminal running bash on your platform
  * On Mac, search for `terminal`
  * On Windows, after following instructions above search for `Ubuntu`
  * On Linux, you probably already know


## Exercise

> the commands `ls`, `cd`, `touch`, `mkdir`, `rmdir`, `mv` and `rm` will probably be useful throughout this exercise. To see documentation for these commands, you can run `man <command>`. For example: `man cd` will teach you how to use the `cd` command. `ls` will be useful for verifying that you have completed a step.

1) Navigate to your home directory (i.e. `~` or `$HOME`)
2) Create a new directory here called `essentials`
3) Move into this new directory
4) Create a new directory called `first`
5) Create a new file called `a.txt`
6) Create a new file in the `first` directory without moving into it called `b.txt`
  * i.e. the path of the file should be `~/essentials/first/b.txt` and you should still be in `~/essentials`
7) Move the `a.txt` to `first/a.txt`
8) Rename the `first/b.txt` file to `first/c.txt`
9) Move all the files in `~/essentials/first` to `~/essentials`
  * hint: you will want to use `*`, you can look at [glob - wikipedia](https://en.wikipedia.org/wiki/Glob_(programming))
10) Remove the `first` directory
11) Run `ls` in `~/essentials`
  * you should see `a.txt` and `c.txt`
  * you should not see `first` or `b.txt`
  
  
# git

git is an important tool for every developer. It's how most developers preserve their work and work together. Here are several resources to help you learn the basics of git:

1) Github has a good resource [here](https://guides.github.com/introduction/git-handbook/) covering the basics
2) There are a couple of interactive tutorials [here](https://www.katacoda.com/courses/git) and [here](https://learngitbranching.js.org/)
