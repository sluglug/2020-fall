---
title: Command line basics
author: SlugLUG
institute: UCSC
theme: Copenhagen
aspectratio: 169
---
# Introductions

# Command line vs. shell vs. prompt vs. terminal?
- People use these terms interchangably. What's the difference? Is there a
  difference?
- A **command line interface** (CLI) is a type of computer user interface in
  which the user types *commands*.
- A **terminal** processes raw data as input and prints the appropriate output
  to the display.
  - Inside a terminal, there is usually a **shell**. A shell is a type of CLI
    intended primarily to facilitate interaction with various other programs on
    a system.
    - Shells have **prompts** to show the user important information.

# In practice
- I open my **terminal**.
  - The terminal opens my **shell**. Everything the shell outputs is passed to
    the terminal, which prints it to the screen.
    - The terminal outputs my **prompt**.

# Why use CLI?
- Lower system requirements.
  - Run more quickly and consume fewer system resources (especially on
    older/lower end systems).
  - Can run without a graphical environment (like when accessing a remote
    machine over SSH.
- More flexible.
  - The shell allows you to easily and consistently do what you want with a
    program's output, including saving it to a file and using it as the input
    to another program.
    - This makes it easier to use multiple programs together.
    - Programs can be simpler if they can delegate some of their
      responsibilities to other programs.
  - Automate text-based commands by putting them in a script.

# Command-line programs
- CLI programs are often called with **options** and/or **arguments**.
