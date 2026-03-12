ReadMe - Github and R Markdown
================
Caroline Himbert and Tierney O’Sullivan
Tue Dec 02, 2025 12:07:48 PM

- [CTE Lunch and Learn Session - R Markdown and
  Github](#cte-lunch-and-learn-session---r-markdown-and-github)
  - [Overview](#overview)
  - [What is Github and how it helps](#what-is-github-and-how-it-helps)
    - [What Git Does](#what-git-does)
    - [Why Git helps (especially in data and research
      workflows)](#why-git-helps-especially-in-data-and-research-workflows)
    - [Key Github terminology](#key-github-terminology)
  - [Hot to get started](#hot-to-get-started)
  - [Good habits](#good-habits)
  - [Collaboration and Communication on
    Github](#collaboration-and-communication-on-github)
    - [Issues](#issues)
    - [Pull Requests (PRs)](#pull-requests-prs)
    - [Reviews](#reviews)
    - [Projects](#projects)
  - [R Markdown](#r-markdown)
    - [What is R Markdown](#what-is-r-markdown)
    - [How it works](#how-it-works)
    - [Output options](#output-options)
  - [Live Demo on Cookie Recipe](#live-demo-on-cookie-recipe)
  - [Tips and best Practices](#tips-and-best-practices)

# CTE Lunch and Learn Session - R Markdown and Github

## Overview

**By the end of this session, you will know how to:**

- Use Git and GitHub for tracking changes and collaborating
- Communicate effectively with issues, pull requests, and reviews
- Structure a data project with R Markdown in a version-controlled
  workflow
- Share and publish analyses using GitHub

## What is Github and how it helps

Git is a version control system - a tool that allows you to track
changes to files over time. It is a great tool to track changes, resolve
issues, work on a project with multiple team members, change log, and
facilitates code sharing.

### What Git Does

- Tracks every change you make to your files
- Allows you to “rewind” to any previous version
- Shows who changed what and when
- Enables safe experimentation through branches
- Makes collaboration smoother and more transparent

### Why Git helps (especially in data and research workflows)

- Prevents lost work - no more “analysis_final_FINAL_v7.Rmd”
- Supports teamwork - multiple people can work on the same project
  without overwriting each other
- Improves reproducibility - every change is documented and recoverable
- Enhances communication - comments, reviews, and clear history
- Encourages good workflow practices - small changes, clear
  documentation, and shared ownership

### Key Github terminology

- **Repository (repo):** A project folder stored on GitHub. It contains
  your files, history, and settings. Think of it as the home base for
  your project (e.g., everything relevant to one manuscript).
- **Clone:** A local copy of a GitHub repository on your computer. You
  clone once—then sync changes through pull/push.
- **Commit:** A snapshot of your changes. Each commit includes what
  changed, when it changed, who did it, a message describing it
- **Push:** Fetch and download changes from Github to your computer.
  Pull before you start new work to avoid conflicts.
- **Branch:** A parallel line of development where you can make changes
  without touching the main project.
- **Merge:** Combine changes from one branch into another.
- **Pull request:** A request to merge your changes into another branch.
  Also a conversation hub where teammates can review code, ask
  questions, suggest edits, approve changes.
- **Issue:** A place to track ideas, bugs, questions, enhancements, or
  tasks.

## Hot to get started

- Create a new Github repository
- Clone repository locally (your computer)
- **Note**: you can save any files in a github repository, even the
  manuscripts etc.

## Good habits

- Commit early and often (GitHub Copilot is helpful!)
- Write descriptive commit messages
- Keep changes small and focused

![xkcd comic on commit messages](https://imgs.xkcd.com/comics/git_commit.png)

## Collaboration and Communication on Github

### Issues

- Use for questions, tasks, and discussion
- Tag teammates & apply labels
- Link issues to pull requests

### Pull Requests (PRs)

- Open a PR to propose changes
- Write helpful PR descriptions
- Request reviews and leave comments
- Approve, merge, and delete the branch

### Reviews

- Use comments, suggestions, and conversations
- Resolve comments to keep communication clear

### Projects

- Projects can help assign and keep track of tasks

## R Markdown

R Markdown is a powerful format that allows you to combine code,
narrative text, and results in a single document. It’s one of the most
effective ways to create well-documented, reproducible analyses.

### What is R Markdown

**R Markdown (.Rmd) lets you:**

- Write prose and run code in the same file
- Automatically include output such as tables, plots, or summaries
- Keep your analysis transparent, readable, and reproducible
- Maintain a clear record of your analytical workflow over time

**It blends documentation + code + results into one cohesive report.**

### How it works

**You write your content in a .Rmd file, which contains:**

- Markdown text (your explanations)
- Code chunks (your R code)
- YAML header (settings such as title and output format)

**When you “knit” the .Rmd file, R processes each code chunk and
automatically generates an output document.**

### Output options

**R Markdown can create multiple output formats:**

- Markdown (.md): often used for GitHub display
- HTML: interactive, nicely formatted reports
- PDF: publication-ready documents
- Word (.docx): editable documents for stakeholders

## Live Demo on Cookie Recipe

- Editing an R Markdown file
- Committing and pushing changes
- Opening a pull request
- Leaving review comments
- Merging the PR
- Viewing the updated file in GitHub
- Opening an issue
- Referencing markdown chunks in issue
- Addressing issue in commit

## Tips and best Practices

- Make small, atomic commits
- Write helpful commit messages and PR descriptions
- Use Issues for documentation of decisions
- Ask questions through Comments to keep communication visible
- Review teammate code with kindness and clarity
- Keep your repository clean and organized
- Be aware of file sizes when using github, git keeps track of all versions of large files so repos can reach capacity quickly
- Use `.gitignore` for files in your repo that you don't want to share publicly or with collaborators

## Git Resources
- [Oh S**t, Git!?!](https://ohshitgit.com/): Website that will help with common git errors to get you out of a pickle!
- [Github Skills](https://skills.github.com/): Free interactive courses for all levels of Git and GitHub experience
- [Git x UofU's CHPC](https://www.chpc.utah.edu/documentation/software/git-scm.php): Overview of using Git in conjunction with the University of Utah's Center for High Performance Computing. Also check out their [Git cheatsheet](https://www.chpc.utah.edu/presentations/git_handout.pdf)

## R Resources
- [Quarto Guide](https://quarto.org/docs/guide/)
- [SLC R User's Group](https://www.meetup.com/slc-rug/): SLC has a really active R Users Group with monthly remote presentations and additional in-person meet-ups

