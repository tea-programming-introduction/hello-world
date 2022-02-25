# Homework 0: Environment Setup and Hello World

This is a **non-graded** homework. The goal is to work you through the process
of setting up a functioning programming environment and get `Hello World!` show
up from your own code!

## Environment Setup

### For Windows Users

For Windows users, we will use [Windows Subsystem for Linux
(WSL)](https://docs.microsoft.com/en-us/windows/wsl/) and [Visual Studio
Code](https://aka.ms/vscode). The rationale behind it is to simplify the work of
the TAs (that are not very familiar with MSVC, the native C/C++ compiler on
Windows platform), and Linux environment is more common in future classes that
require programming.

A guide with automated script to setup is provided on https://tea-programming-introduction.github.io/wsl-rootfs-minimal/

### For macOS Users

For macOS users, please lookup `Terminal.app` (`终端.app`) to access the
command line interface.

Type `xcode-select --install` to install command line tools, including the
compiler we will need throughout this class.

Then install [Visual Studio Code on the same website](https://aka.ms/vscode)

## Requirement

Modify `hello.c` so that it always output a single line

```
Hello World!
```

And push the commit back to GitHub.

## Guide

- Generate a SSH keypair with `ssh-keygen` and upload the public key to GitHub.
- Clone the repo with the link provided by pressing the green `Code` button and choose `SSH` option.
- `git add .` to stage your local changes
- `git commit`
- `git push` and then watch autograde!
