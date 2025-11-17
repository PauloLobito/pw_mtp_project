
# Introduction

## 📂 Structure Overview

### 🏁 Introduction
- **[Objectives](introduction/objectives.md)**  
  Learn about the project’s purpose, goals, and key outcomes. This section sets the context for all contributors and helps align efforts with the project’s vision.


## 📂 Contents

### 🗣️ [Issues and Discussions](collaboration/issues_and_discussions.md)
Learn how to **communicate effectively** about project needs and ideas.  
- **Issues** are used to report bugs, request features, or track specific tasks.  
- **Discussions** provide an open space for community interaction, brainstorming, and Q&A that doesn’t directly affect the codebase.  
Together, they keep collaboration transparent and organized.

---

### 🔄 [Pull Requests and Reviews](collaboration/pull_requests_and_reviews.md)
Understand how to **propose, review, and integrate code changes** in a structured way.  
Pull requests (PRs) let contributors suggest modifications, while code reviews ensure quality and consistency across the project.  
You’ll learn how to create a PR, request reviews, resolve feedback, and follow best practices for merging contributions.

---

### 📖 [Wiki and Documentation](collaboration/wiki_and_documentation.md)
Explore how to **create and maintain clear project documentation**.  
This section covers the use of the GitHub Wiki and Markdown files to record key information — such as installation steps, architecture notes, and contributor guides.  
Well-maintained documentation helps onboard new members and preserves project knowledge for the future.

---

### 📊 [Project Management](collaboration/project_management.md)
Discover how to **organize, prioritize, and track project work** using GitHub’s project management tools.  
You’ll learn how to use Projects, Milestones, and Labels to plan tasks, monitor progress, and coordinate team efforts efficiently.  

---

### **Advanced Git Concepts** module.

While basic Git commands like `add`, `commit`, and `push` are sufficient for saving your work, professional software development requires a deeper understanding of how to curate and manage project history.

In this module, we will move beyond the basics and master three powerful strategies to maintain a pristine repository:

1.  **Git Rebase:** To maintain a linear, easy-to-read history.
2.  **Git Squash:** To condense noisy "work in progress" steps into polished features.
3.  **Git Cherry-pick:** To surgically move specific commits across branches without merging unwanted code.

[Link of the work] (/git_best_practises/grupo2)
### Project Documentation

Welcome to the project documentation! This repository is designed to provide a **comprehensive guide for contributors** and users, covering the project’s objectives, collaboration workflows, and reference materials.  

The documentation is structured to make it easy to navigate and find the information you need, whether you are starting as a new contributor or looking to understand specific project practices.

This section helps keep development aligned with goals and timelines.

### Best Practices
In software development, tags and releases are fundamental concepts used to manage, version, and distribute a project's history. While closely related, they serve distinct purposes.

Tags: A tag is a feature of version control systems like Git. It acts as a bookmark or a pointer to a specific, significant commit in your project's history. Tags are most commonly used to mark version points (e.g., v1.0, v2.1-beta). Because they are static and don't move as new commits are added, they provide a reliable way to check out the exact state of the code for a specific version.

Releases: A release is a more formal package built from a tag. While the tag just marks the code, the release is what you deliver to your users. On platforms like GitHub or GitLab, a release is anchored to a specific tag and includes additional, user-focused items:

Release Notes: Detailed descriptions of what's new, what's fixed, and any breaking changes.

Compiled Binaries: Pre-built, downloadable files (like .exe or .zip files) so users don't have to build the software from the source code.

Source Code Snapshots: Packaged .zip or .tar.gz files of the repository at that specific tag.

In short: you tag a specific commit in your code history to create a version marker, and then you create a release from that tag to formally package and document that version for your users.

[Link to Tags and Releases](/git_best_practices/tags_and_releases)

## **What is Branch Naming?**
Branch naming is a methodological convention , not a Git requirement, that acts as the first line of documentation for your standalone work.

The fundamental concept is that a branch name should immediately answer two questions: What (the type of work) and Why (the context or task).

[Link to Branch naming](/git_best_practices/branch_naming)

## **What are Workflow Patterns?**
Workflow Patterns, or Branching Strategies , are the set of methodological rules and conventions that a team adopts to manage software development using Git (the terminal tool) and GitHub (the collaboration platform).

💡 Introduction to Git Commit Messages
In any project that uses Git for version control, the commit is the fundamental unit that records changes in the code. Think of a commit as a "save point" or a checkpoint in the timeline of your project.

[Link to Commit Messages Best Pratices](/pw_mtp_project/Commit%20Message%20Best%20Practices/commit_messages)

These aren't new Git commands; it's about how and when your team uses commands like git branch`git pull` git mergeor `git git pushgit add`. The main goal is to standardize collaboration so everyone is on the same page when adding a feature or fixing a bug .

[Link to WorkFlow Patterns](/git_best_practices/workflow_patterns)

