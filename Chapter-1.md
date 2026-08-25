# Chapter 1: Introduction to GitHub

## 1.1 What Is GitHub?

GitHub is an online platform used to store, manage, and share project files. It is widely used by developers, technical writers, students, and teams to work on projects together.

GitHub uses **Git**, a version control system, to track changes made to files. This allows users to see what was changed, when it was changed, and who made the change.

GitHub can be used for many types of projects. You can store software code, documentation, Markdown files, images, and other project resources.

---

## 1.2 What Is Git?

Git is a **distributed version control system**. It records changes made to files and allows users to return to earlier versions when needed.

For example, imagine that you are writing a documentation project. You update a file several times and accidentally remove an important section. If the project is managed with Git, you can check the previous versions and recover the information.

Git works mainly on your local computer. You can use Git without connecting to GitHub.

Some common Git operations include:
 * Creating a repository
*  Adding files
* Tracking changes
* Creating commits
* Creating branches
* Merging changes

Git is the technology that provides version control, while GitHub provides an online platform for working with Git repositories.

---

## 1.3 Git vs. GitHub

Git and GitHub are often confused because they work together, but they have different purposes.

| Git                         | GitHub                                        |
| --------------------------- | --------------------------------------------- |
| Version control system      | Online development and collaboration platform |
| Runs on your computer       | Available through the web and GitHub tools    |
| Tracks changes              | Hosts Git repositories                        |
| Can work offline            | Provides online collaboration features        |
| Created for version control | Provides tools around Git                     |

A simple way to remember the difference is:

**Git tracks your changes. GitHub helps you store and share those changes online.**

---

## 1.4 Why Use GitHub?

GitHub provides several features that make project management easier.

### Version Control

GitHub keeps a history of changes. You can see previous versions of files and understand how a project has changed over time.

### Collaboration

Multiple people can work on the same project. Team members can create branches, review changes, and discuss work before it is added to the main project.

### Project Storage

Repositories provide a central location for project files. This makes it easier to organize and access project content.

### Documentation

GitHub can be used to create and host documentation. Markdown files can be used to write user guides, tutorials, README files, and other technical documents.

### Open-Source Projects

Many open-source projects use GitHub to share their work with the public. Users can view the project, report problems, suggest improvements, and contribute changes.

---

## 1.5 Understanding Repositories

A **repository**, commonly called a **repo**, is a storage location for a project.

A repository can contain different types of files, such as:

* Source code
* Markdown files
* Images
* Configuration files
* Documentation
* Project information

A repository also stores the project's change history.

For example, a technical-writing project could have the following structure:

```text
github-guide/
├── README.md
├── chapter-1.md
├── chapter-2.md
├── chapter-3.md
├── images/
└── examples/
```

The repository keeps these files together as one project.

---

## 1.6 Public and Private Repositories

When creating a repository, you can usually choose whether it should be **public** or **private**.

### Public Repository

A public repository can be viewed by other people on GitHub.

Public repositories are useful for:

* Open-source projects
* Portfolio projects
* Documentation samples
* Learning projects
* Public resources

### Private Repository

A private repository is only accessible to people who have permission to access it.

Private repositories are useful for:

* Personal projects
* Company projects
* Work in progress
* Projects containing information that should not be public

> **Important:** Making a repository private does not mean that you should store passwords or other sensitive information in it.

---

## 1.7 Creating a GitHub Account

Before using GitHub, you need to create an account.

Follow these general steps:

1. Open the GitHub website.
2. Select **Sign up**.
3. Enter your email address.
4. Create a password.
5. Choose a username.
6. Complete the verification process.
7. Sign in to your account.

After creating an account, you can create repositories and start working on projects.

### Choosing a Username

Your GitHub username is part of your public profile. If you plan to use GitHub as part of your professional portfolio, choose a username that is simple and professional.

For example:

```text
tanya-docs
tanya-writes
tanya-tech
```

Avoid usernames that are difficult to remember or contain unnecessary characters.

---

## 1.8 Understanding the GitHub Interface

After signing in, you will see different areas of GitHub.

### Repositories

The **Repositories** section contains the projects associated with your account.

### Issues

**Issues** can be used to report problems, create tasks, or suggest improvements.

### Pull Requests

**Pull requests** are used to propose changes to a project and allow other people to review those changes.

### Profile

Your profile shows information about your GitHub activity and repositories.

### Settings

The **Settings** area contains options for managing your account and repositories.

---

## 1.9 Common GitHub Terms

Understanding common terms makes GitHub easier to use.

| Term         | Meaning                                        |
| ------------ | ---------------------------------------------- |
| Repository   | Storage location for a project                 |
| Commit       | A saved record of changes                      |
| Branch       | Separate version of a project                  |
| Merge        | Combining changes from one branch into another |
| Pull request | Request to review and merge changes            |
| Issue        | A task, problem, or suggestion                 |
| Fork         | A copy of another user's repository            |
| Clone        | Copying a repository to your computer          |
| README       | File that explains a project                   |

These terms are used frequently when working with GitHub.

---

## 1.10 GitHub for Technical Writers

GitHub is not only for software developers. Technical writers can also use GitHub as part of their documentation workflow.

Technical writers can use GitHub to:

* Write Markdown documentation
* Store user guides
* Track documentation changes
* Review content
* Collaborate with developers
* Manage documentation updates
* Maintain README files

For example, a technical writer may create a product guide using Markdown and store each chapter in a GitHub repository.

This makes GitHub a useful skill for technical-writing professionals.

---

## 1.11 Example Documentation Repository

A simple documentation repository could look like this:

```text
product-guide/
│
├── README.md
│
├── chapters/
│   ├── introduction.md
│   ├── installation.md
│   └── troubleshooting.md
│
├── images/
│   ├── home-page.png
│   └── settings.png
│
└── examples/
    └── sample.md
```

This structure separates different types of content and makes the project easier to maintain.

---

## 1.12 Chapter Summary

In this chapter, you learned:

* What GitHub is
* What Git is
* The difference between Git and GitHub
* What a repository is
* The difference between public and private repositories
* How to create a GitHub account
* The basic GitHub interface
* Common GitHub terms
* How technical writers can use GitHub

In the next chapter, you will learn how to **create and manage a GitHub repository**.

---

**Next:** [Chapter 2 – Creating and Managing Repositories](chapter-2-repositories.md)
