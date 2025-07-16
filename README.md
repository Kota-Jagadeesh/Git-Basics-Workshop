# Git Basics

Take your first step into the world of version control!

This workshop is designed for complete beginners, including those with little or no experience with coding or command-line tools.You'll learn how to track your code changes, undo mistakes, and collaborate with others using Git.

## Fork this Repository

Go to the top of this page and click the **Fork** button.

This will create a **copy of this repository** into your GitHub account.

## Clone the Forked Repository

Next, you'll **clone** your fork to your computer.

-  In your forked repo, click the green **Code** button and copy the URL
-  In your terminal:
    ```bash
    git clone <paste-the-url-here>
    ```
-  Change into the cloned directory:
    ```bash
    cd Git-Basics-Workshop
    ```
## Create a new branch
```bash
git checkout -b your-name
```
# Make Your First Contribution!
Create a new file named `Day4.md` and document a summary of all the concepts and commands covered today. Then, push your branch to GitHub using the following commands:
```
git add Day4.md
git commit -m "Add add a commit message"
git push -u origin your-branch-name
```