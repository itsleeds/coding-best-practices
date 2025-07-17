# ITS Development Guide

This document provides a list of tips, tools, and resources for coding / software development within the Institute for Transport Studies.

## Languages

### Python

#### Project setup and dependancy management

Isolating dependencies is key to reproducible research. Using a virtual environment for each project is highly encouraged. The best tool often depends on the project's complexity. Some links to get you started
- A comparison of dependancy management tools, and when to use which: https://alan-turing-institute.github.io/rse-course/html/module06_software_projects/06_02_managing_dependencies.html#which-to-choose

### R

## High Quality Code

Writing clean, tested, and documented code is very helpful for collaboration and long-term project maintenance.

- Code Style: Following a consistent style guide like PEP 8 for Python improves readability. Tools like Black can format code automatically.
- Linting: Linters like Flake8 can catch common errors and style issues before they become bugs.
- Testing & Documentation
- For a comprehensive guide on creating high-quality, sustainable research software, you can check out:
    - [Build a Reproducible and Maintainable Data Science Project](https://khuyentran1401.github.io/reproducible-data-science/README.html)

 ## Version Control

Version control is important for tracking changes and collaborating effectively.

- Git Workflow: A simple, effective approach is to create a new branch for each new feature or bugfix. When the work is complete, open a Pull Request on GitHub to merge the changes into the main branch. This allows for code review and discussion before changes are finalized.
- GitHub Features: Beyond version control, GitHub provides useful project management tools. Using GitHub Issues to track tasks, bugs, and feature requests is a great way to keep project development organized and transparent.

If you are new to GitHub and the worflow, checkout the short interactive courses on [GitHub Skills](https://skills.github.com/).

## IDEs and AI Assistants


| IDE          | Primary Languages   | Key Features                                                              |
|--------------|---------------------|---------------------------------------------------------------------------|
| **VS Code** | Python, R, Java, etc   | Highly extensible, great Git integration, huge library of extensions. Good AI integration through copilot   |
| **PyCharm** | Python               | Powerful debugging, refactoring, and testing tools specific to Python.    | 
| **RStudio** | R                    | Excellent environment for interactive R analysis, plotting, and packages. |
| **Positron** | R, Python           | From the creators of RStudio, a modern IDE for R and Python development.  |

AI assistants can be powerful tools for generating boilerplate code, writing tests, and explaining code blocks.

- Popular Tools: GitHub Copilot is well-integrated into many IDEs, including VS Code and PyCharm.
- A Word of Caution: Always critically review AI-generated code. You are ultimately responsible for what you commit. Be especially careful with complex logic and be mindful of data privacy.

