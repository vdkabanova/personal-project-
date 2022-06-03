---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Create a report"
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
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

**Introduction**

A small recipe that will be useful when creating dynamic reports.

Quite often there is a situation when the size and content of the reporting form will depend on the composition of the data transmitted to the input. We are talking about a story-telling report, and not about a simple table output. In this case, depending on the content of the input data, individual items, graphs, tables, text may appear or disappear.

What will a classic Excel-Word analyst do? For each new request, make a custom report and save it to a separate file. But you can look a little under the hood and make the computer do everything on its own.

R Markdown lets you do all this in an elegant way. Some technical details below.

**Main idea**

We have data, the content of which may change. For example, it is necessary to build a report on cars delivering goods (abstract example). The number and numbers of cars leaving for the flight are different every day, but the summary for each car is the same in its structure. Let's move on from this.

R Markdown is done in multiple passes. At the same time, .md is first formed from Rmd, and then the output representation is formed from it, the most popular is the html format.

In total, there are 2 options.

- You can insert the necessary blocks (assembled or templated) into the compiled .Rmd at the stage of compiling the report.

- You can insert the necessary markdown inserts into the intermediate .md at the stage of compiling the report.

**Implementation**

Below is just an example of code that anyone can run on their machine. It covers implementations of both examples and is minimal to get the point across.

- Dynamically insert hyperlinks received from an external source.

- Dynamically generate document sections based on data.
