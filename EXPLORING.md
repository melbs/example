This is a testing file that is called EXPLORING.md and I'm
just fooling around to see things!

and I'm going to add another line here. This is me exploring.

# The Basics of Markdown #

When we talk about Markdown, it's important to remember that Markdown was
developed based on the de facto standards that people used when writing
documentation in plain text. That means that paragraphs were just lines of
text, and you started a new paragraph by entering a blank line.

This is a new paragraph! We know that because there is a blank line between
the two paragraphs. 
It doesn't matter if the lines of text are all the same length.
Markdown will glue those lines together into a single pargraph.

## Formatting

Basic formatting in Markdown includes
*italic* text or _italic_ text
and
**bold** or __bold__ text.

### Example

*You don't have to use bold or italic on an entire word or phrase.*
You can also use bold or italic on an entire sentence or for part of a word.
For example, the acronym **HTML** stands for
**H**yper **T**ext **M**arkup **L**anguage.


# Firetruck Engine Maintenance

> [!WARNING]
> Always disconnect the main battery prior to servicing the engine block to prevent electrical shock. 

Follow these steps to access the primary manifold:

1. Open the main exterior access panel.
   1. Disengage the left primary latch.
   2. Disengage the right primary latch.
2. Inspect the internal coolant levels.
3. Verify the pressure metrics.

Coolant should only be checked when the engine has rested for at least two hours. [^1]

The baseline pressure requirement can be calculated using the standard formula where Pressure equals Force divided by Area:

$$
P = F / A
$$

[^1]: This is based on standard environmental safety guidelines. 


# Git Configuration Basics

Before contributing to the repository, you must configure your local environment. As the official documentation states:

> The first thing you should do when you install Git is to set your user name and email address.

You will need the following tools installed:
* Git Bash
* A text editor like `VS Code`
* A GitHub account

> [!IMPORTANT]
> Verify that your email address matches your GitHub account to ensure your commits are properly attributed.

To set your global username, open your terminal and run this command:

```bash git config --global user.name "Your Name"```

For more details, refer to the Git Setup Guide.
