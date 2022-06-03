---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Versioning. Git"
subtitle: "github"
summary: ""
authors: [Varvara Kabanova]
tags: []
categories: []
date: 2022-05-05T17:20:53+03:00
lastmod: 2022-05-05T17:20:53+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'Image credit'
  focal_point: ""
  placement: 2
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

**What is a "version control system" and why is it important?**

A Version Control System (VCS) is software that makes it easier to work with changing information. The version control system allows you to store multiple versions of the same document, revert to earlier versions if necessary, determine who made a change and when, and much more. Such systems are most widely used in software development to store the source codes of the program being developed.

GIT is a distributed version control system created by Linus Torvalds to manage the development of the Linux kernel and is currently very widespread among software developers.

GIT uses a distributed model instead of the traditional client-server model. Thus, GIT repositories do not need a centralized repository: the entire history of document changes is stored on each computer, in local storage, and, if necessary, individual fragments of the local storage history are synchronized with the same storage on another computer.

Today, GIT has become the standard version control system for so many developers, and GitHub source code hosting is the largest such service. Examples of projects using Git are the Linux kernel, Android, Ruby on Rails, Drupal, Wine, Chromium, Compiz Fusion, jQuery, PHP, MediaWiki, and some Linux distributions

**Why should a beginner learn Git?**

Git is used in most companies where at least two developers work on a project:

- A new person comes to the company and clones the project repository on the PC.
- Gets an issue, creates a new branch, and writes the code.
- When everything is ready - sends a request to add code to the master branch.
- Other developers look at the code, leave comments and point out bugs.
- A beginner refines the code, updates the master branch and moves on to the next task.

This is a general outline of how teamwork works in a project. It does not take into account the rules for using Git, which each team writes for itself. For example, each team has its own code review order and its own criteria for its readiness to be added to the master branch.

Knowing Git and knowing how to use Git in a team are two different skills that can be compared to knowing how to drive a car and knowing the rules of the road. If you know how to drive a car, it is easier for you to concentrate and quickly learn the rules. With Git, the situation is similar: if you know how to manage the version control system, then you can immediately join the project, not be distracted by secondary things and focus on the quality of the code.