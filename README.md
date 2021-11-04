# Learning GIT Part 2

[GIT documentation](https://git-scm.com/docs/git)

**Table of Contents**

5. [*Command line Fundamentals*](#Command-Line-Fundamentals)
6. [*Undoing bad commits*](#undoing-bad-commits)
7. [*Forking*](#forking)
8. [*Learning markdown*](#learning-markdown)
---
> The computer programmer is the creator of a universe for which he alone is responsible. 
>
> --<cite> Joseph Weizenbaum</cite>

## Command Line Fundamentals

1. if we need help in git
    - git help <verb>
or 
git <verb> --help

1.  to remove file
    - rm -rf filename
eg rm -rf .git

1.  suppose we want to work on a file but i don't want others to see it. for that:
    - touch .gitignore


## Undoing bad commits

1.  suppose we accidentally added a wrong message in commit and we want to change it.
    - git commit --amend -m "you can type correct message here"
1. suppose we forgot to commit a file.
    - git commit --amend
1. suppose we accidentally added something to wrong branch
    - git cherry-pick hashwecopied

## Forking

Forking means to create copy of repository from another account to our account.

## Learning markdown

markdown is a simplified markup langauge that is used for formatting text. it gives you a way to write your text so that we can compile to html.

markdown is there since 2004.

markdown is introduced by john gruber.

why and where to use it?
markdown is much easier to use and read then standard html.

what we can do with markdown?
we can text for blogs, python notebooks, creating tables, flowcharts using markdown.

github supports markdown and has default standard README
and github provides some extra features if we use markdown on their platform

apps that support markdown Bear App, Standard Notes, Joplin and Obisidian

we can write codes, format text, put headers etc in python notebooks


