Copy code
# Git Automate - Simple Git Command Line Tool

## Overview

Git Automate is a simple command-line tool written in Rust. It automates the process of adding all files, committing changes, and pushing them to the remote repository. This tool is designed to streamline the Git workflow, making it faster and more convenient.

## Features

- Adds all files recursively to the Git repository.
- Commits all changes with a randomly generated commit message.
- Pushes the changes to the remote repository (origin main branch).

## Installation

To build and install Git Automate, you'll need Rust and Cargo installed on your system. If you haven't already, you can install Rust by following the instructions on the [official Rust website](https://www.rust-lang.org/).

## About Project

Here's how it works: You run the program, and it uses the git command-line tool under the hood to add all the changed files (git add -A), create a commit with a randomly generated commit message (git commit -m <message>), and push those changes to the master branch of your GitHub repository (git push origin master).

I've even added a fun touch to the commit messages by using the names crate to generate a random name for each commit.

This project is really handy for automating repetitive tasks and streamlining the GitHub workflow. Plus, it's all written in Rust, which makes it fast and efficient.

I've documented everything in the README.md file, so it's easy for anyone to understand and use. You can check it out for more details on how to install and use the program.