# Complete Git and GitHub Tutorial for Beginners
We will learn about Git and GitHub in detail from scratch. 

# `Git`  <img src="https://github.com/ZiaUrRehman-bit/Complete-Git-and-GitHub-Tutorial-for-Beginners/assets/77435711/bac25d1f-6152-42dd-97c3-a735c013ff8e" alt="Image" width="30"/>


Version control system is a tool that helps to track changes in code<br>
Git is a Version Control System.
+ Popular
+ Free & Open Source
+ Fast & Scalable
  
Git is mainly used for two things.<br>
+ To track the history of changes
+ To collaborate (work in a team)

# `GitHub`  <img src="https://github.com/ZiaUrRehman-bit/Complete-Git-and-GitHub-Tutorial-for-Beginners/assets/77435711/4a13c429-2641-4a41-a025-6d98f7ee977f" alt="Image" width="30"/>
`Website` that allows programmers to store and manage their code using Git.<br>
https://github.com

# `Setting Up Git on Windows`

<p>Follow these steps to set up Git on your Windows machine:</p>

<ol>
  <li>Download Git for Windows from the official website: <a href="https://git-scm.com/download/win">https://git-scm.com/download/win</a></li>
  <li>Run the installer and follow the installation instructions.</li>
  <li>Open a command prompt or Git Bash and configure your name and email:</li>
</ol>

```bash
$ git config --global user.name "Your Name"
$ git config --global user.email "youremail@example.com"
```

<h2>Basic Git Commands</h2>
<p>Here are some essential Git commands:</p>
<ul>
  <li><strong>git init</strong>: Initialize a new Git repository.</li>
  <li><strong>git clone</strong>: Clone a repository from GitHub.</li>
  <li><strong>git add</strong>: Stage changes for commit.</li>
  <li><strong>git commit</strong>: Commit changes to the repository.</li>
  <li><strong>git pull</strong>: Fetch and merge changes from a remote repository.</li>
  <li><strong>git push</strong>: Push changes to a remote repository on GitHub.</li>
  <li><strong>git status</strong>: Shows the status of file.</li>
</ul>
<h2>Learn More</h2>
<p>For a comprehensive guide on Git and GitHub, please check out our detailed tutorial in the <a href="https://github.com/ZiaUrRehman-bit/Complete-Git-and-GitHub-Tutorial-for-Beginners/blob/main/git-cheat-sheet-education.pdf">Git Cheat Sheet</a> file in this repository.</p>

## Steps of method 01 to Publish to GitHub

### Step 1: Create a GitHub Repository

- Go to the GitHub website (https://github.com) and log in to your GitHub account.
- Click the "+" icon in the top-right corner and select "New repository."
- Fill in the repository name, description, and other settings.
- Choose the repository visibility (public or private).
- Optionally, initialize the repository with a README file or add a .gitignore file and a license.
- Click the "Create repository" button.

### Step 2: Method 02 Install Git

If you haven't already installed Git on your computer, download and install it from the official website (https://git-scm.com/).

### Step 3: Open Your Project in Visual Studio Code

- Open Visual Studio Code.
- Use the "File" menu to open your project folder.

### Step 4: Initialize a Git Repository

- Open the integrated terminal in Visual Studio Code by pressing `Ctrl + ` (backtick) or selecting `Terminal > New Terminal` from the menu.
- Navigate to your project directory using the terminal.
- Run the following command to initialize a Git repository in your project folder:

   ```bash
   $ git init
   ```
### Step 5: Add and Commit Your Code

- In Visual Studio Code, make changes to your project files as needed.
- Use the integrated terminal to add your changes to the staging area. Replace <file(s)> with the file(s) you want to stage or use '.' to stage all changes:
  
   ```bash
   $ git add fileName
   ```
   for all files
  ```bash
   $ git add .
   ```
  Commit your changes with a descriptive commit message:
  ```bash
   $ git commit -m "Your commit message here"
   ```
### Step 7: Push Your Code to GitHub
Push your local code to GitHub by running the following command:

  ```bash
   $ git push origin main
   ```
<h2>Contributing</h2>
<p>Contributions are welcome! If you have suggestions, bug reports, or want to improve this tutorial, please create an issue or submit a pull request.</p>
