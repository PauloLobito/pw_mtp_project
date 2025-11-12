1. Introduction

Writing commit messages that clearly and concisely describe changes can be very challenging.

In this tutorial, we will study some of the best practices for Git commit messages.

First, we will understand the concept of commit messages and their relevance. Next, we will examine best practices for creating well-structured and informative commit messages. Then, we will see how to create well-structured commit messages through the command line. Finally, we will summarize the best practices.

2.1. What is a commit message?

When working in a Git repository, we make changes to the source code and save them all the time. In this context, we refer to each saved change as a commit.


3.1. Structure for Good Commit Messages
A simple commit message is usually composed of a single sentence. However, it is very common for a single sentence not to be able to provide enough information about the context of the commit.

In this sense, a widely adopted approach to providing more context about changes is the use of structured commit messages. This type of message is made up of three parts:

<Subject>

<Description>

<Tags and External References>


The first line of the message is the subject, intended to describe the commit briefly. Thus, this serves as a title for the commit. Therefore, it should be clear and concise.

The description provides more detailed information about the changes made. Usually, we need more than one sentence to write a good description.

We can add tags and external references to the commit message. In this case, the tags indicate the type of change (feature, bug fix, etc.), and the external references (such as ticket numbers) specify which issue is being addressed.

