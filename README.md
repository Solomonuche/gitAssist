# Git Automation Script - gitAssist

## Overview

The Git Automation Script is a Bash script that simplifies and automates common Git tasks, making it easier to manage your version control workflow. This script allows you to easily stage and commit changes, provide meaningful commit messages, and push your changes to a remote Git repository.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Efficient Staging:** Easily stage individual files or all changes in the current directory.
- **Descriptive Commits:** The script prompts you for a commit message, ensuring that your commits are meaningful and well-documented.
- **Remote Push:** Automate the push step to a remote Git repository, whether it's on GitHub, GitLab, Bitbucket, or any other platform.
- **Tab Autocompletion:** Enjoy the convenience of tab autocompletion and Readline editing for file input, making the process smoother.

## Prerequisites

Before using the Git Automation Script, make sure you have the following prerequisites:

- **Git:** The script relies on Git to perform version control tasks. Ensure that Git is installed and configured on your system.

## Installation

1. **Clone or Download:** Clone or download this repository to your local machine.

2. **Move the Script:** Move the script file (`gitAssist`) to a directory that is included in your system's `PATH`, or follow the instructions below to set up a directory for your scripts and add it to your `PATH`.

3. **Make the Script Executable:** Make the script executable by running the following command in your terminal:

   ```bash
   chmod +x gitAssist
   ```

## Usage

To use the Git Automation Script, follow these steps:

1. **Open Your Terminal:** Launch your terminal or command prompt.

2. **Navigate to Your Git Repository:** Use the cd command to navigate to the directory where your Git repository is located.

3. **Run the Script:** Execute the script by typing its name and pressing Enter:
   ```bash
   gitAssist
   ```

4. **Follow the Prompts:** The script will guide you through the following steps:
	- **Staging and Committing:** You can stage and commit individual files by entering their names, separated by spaces.
	- **Staging and Committing All Changes:** If you enter "1" when prompted for filenames, the script will stage and commit all changes in the current directory.
	- **Provide a Commit Message:** You'll be asked to provide a commit message for your changes.
	- **Push to Remote Repository:** The script will push your changes to the remote Git repository.

## Contributing

Contributions are welcome! If you have suggestions, feature requests, or find any issues, please feel free to open an issue or create a pull request. Your contributions are valuable in making this script even better.

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/)
