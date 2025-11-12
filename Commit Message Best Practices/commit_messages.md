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



3.2. How to Elaborate the Content of the Message

In addition to adopting a well-defined structure, we need to know what to say and how to use the message. In practice, this involves knowing some basic principles about writing the subject and description of a commit message.

The most essential principle when writing the subject is to use the imperative mood. Therefore, instead of saying “Adding…”, “Fixing…”, “Reverting…”, etc., we need to use “Add…”, “Fix…”, and “Revert…”, respectively.

Another good practice is to emphasize the “why” and not just the “how”. For example, instead of writing “Add import_key() function” in the subject, it would be better to write something like “Add support for users to import keys”.

This idea extends to the description of the commit. In particular, we should write the description so that other contributors can understand the changes and why. As an example, a good description for the subject presented in the previous paragraph would be something like this:

"Currently, users can only use keys created within the platform. Adds the
import_key() function to allow the import of keys created externally."



3.3. The 50/72 Rule
The 50/72 rule is a widely adopted standard for normalizing the commit message format. 50 refers to the maximum number of characters of the commit message’s subject (or title). Meanwhile, 72 indicates that we should format the body of the message in columns of up to 72 characters.

These limits were established based on analyzing good practices in relevant projects. An example of this is the commit messages in the Linux kernel, which have titles that summarize the changes well, usually using around 50 characters.

Similarly, the widely accepted standard for the length of readable lines is 80 characters, which contributed to the column limit of up to 72 characters. Of the 80 characters, 8 are purposely cut off: 4 because Git automatically adds a 4-character padding to the left of the commit message body and the other 4 characters should be padded to the right to keep everything centred.


