---
title: Configuration files
author: SlugLUG
institute: UCSC
theme: Copenhagen
aspectratio: 169
---
# Configuration
- When I want to make changes to a program's configuration, usually I want them
  to be **saved** across multiple sessions.
- For this to happen, *configuration files* need to be stored on my computer.

# Usage
- On Unix-like systems (like Linux), user configuration files are stored in the
  user's home directory, just like any other user data.
- These files are not removed when uninstalling the associated program.
  - Programs can be reinstalled with no effect on your configuration.
- Configuration files can be backed up and restored, even across reinstalls and
  different computers.
  - This makes it possible to easily save and share an entire workflow.

# Location
- Programs used to store their own configurations directly in the home folder,
  usually in a folder called `.programname` or a file called
  `.programnamerc`^†^.

^†^where **rc** stands for **run commands**: commands executed when running the
program.

# Standardization
- As users started installing more and more programs, this convention lead to
  messier and messier home folders.
- To fix this, the *XDG Base Directory Specification* was adopted by many (but
  not all) programs on Unix-based systems.
- Under the XDG standard, each user has folders for *data*, *config*, and
  *cache*. Program files are supposed to be in those folders only.
  - *Cache* is for temporary files.
  - So theoretically, when copying configs, you should only have to worry about
    two folders: *data* and *config*, instead of one for every program.
  - This also reduces the amount of clutter in your home folder.
