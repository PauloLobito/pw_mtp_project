# ✍️ Best Practices for Git Commit Messages

## 1. Introduction

Writing commit messages that clearly and concisely describe changes can be very challenging.

In this tutorial, we will study some of the **best practices** for Git commit messages.

First, we will understand the concept of commit messages and their relevance. Next, we will examine best practices for creating well-structured and informative commit messages. Then, we will see how to create well-structured commit messages through the command line. Finally, we will summarize the best practices.

---

## 2.1. What is a Commit Message?

When working in a Git repository, we make changes to the source code and save them all the time. In this context, we refer to each saved change as a **commit**.

---

## 3.1. Structure for Good Commit Messages

A simple commit message is usually composed of a single sentence. However, it is very common for a single sentence not to be able to provide enough information about the context of the commit.

A widely adopted approach to providing more context is the use of **structured commit messages**. This type of message is made up of three parts:

<Subject>

<Description>

<Tags and External References>

* **Subject**
    The first line briefly describes the commit and serves as its title. It should be **clear and concise**.

  * **Description**
    The description provides more detailed information about the changes made. It commonly requires more than one sentence.

  * **Tags and External References**
    Tags indicate the type of change (**feature**, **bug fix**, etc.), while external references (such as ticket numbers) specify which issue is being addressed.

-----

## 3.2. How to Elaborate the Content of the Message

Beyond using a well-defined structure, it's important to know what to say and how to use the message. This involves knowing some basic principles for writing the subject and description.

### Imperative Mood

The most essential principle for writing the subject is the use of the **imperative mood**:

  * **Instead of:** “Adding…”, “Fixing…”, “Reverting…”
  * **Use:** “Add…”, “Fix…”, “Revert…”

### Emphasize the “Why”

A better subject explains **purpose**, not just action:

  * **Weak:** “Add import\_key() function”
  * **Strong:** “Add support for users to import keys”

**Example Description:**

> Currently, users can only use keys created within the platform.
> Adds the import\_key() function to allow the import of keys created externally.

-----

## 3.3. The 50/72 Rule

The **50/72 Rule** is a widely adopted standard for commit message formatting.

  * **50 characters** → maximum length of the **subject**
  * **72 characters** → maximum width of each line in the **body**

These limits follow conventions seen in major projects (e.g., the Linux kernel) and readability guidelines.

-----

## 3.4. Conventional Commits

The **Conventional Commits** specification is a lightweight convention that adds human- and machine-readable meaning to commit messages, enabling automation.

### Common Commit Types

| Type | Description |
| :--- | :--- |
| `feat` | Introduce a new feature |
| `fix` | Fix a bug |
| `docs` | Create/update documentation |
| `style` | Styling updates |
| `refactor` | Refactor code |
| `test` | Add/update tests |
| `chore` | Maintenance tasks |

### Subject Format

(optional scope):

**Example:**

`feat(api): Add support to create coupons`

### Breaking Changes

You can indicate breaking changes using:

BREAKING CHANGE:

or adding `!` after the type:

`chore!: Update Python version to use newer libs`

-----

## 5\. Summary

To achieve great Git commit messages:

  * Create a **subject** and a **description** (separated by one blank line)
  * Specify the commit **type** (`feat`, `fix`, `style`, etc.)
  * Use the **imperative mood** in the subject
  * Explain in the description **what changed and why**
  * Keep the subject **under 50 characters**
  * Format the description in **72-character** columns

-----

## 6\. Conclusion

In this tutorial, we’ve studied the main best practices for writing good Git commit messages. Many common practices—such as the 50/72 rule and conventional commits—help us write well-structured and informative messages.

### Content Checklist

  * [x] All required topics are covered
  * [x] No spelling or grammar errors

### Git Checklist

  * [x] All team members have commits
  * [x] Commit messages are clear and follow conventions
  * [x] No merge conflicts with target branch

<!-- end list -->