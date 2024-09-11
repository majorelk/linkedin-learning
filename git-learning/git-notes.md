
- *Version Control*: Git helps you keep track of changes in your code by creating versions, known as commits, so you don't need to create multiple files like Code1, Code2, etc.
- *Commit Process*: Instead of creating new files for each version, you commit changes to Git, which stores the history of your code, allowing you to revert to previous versions easily.
- *Local and Remote Repositories*: Git can store your version history locally on your computer and also with a Git provider in the cloud, ensuring your code is safe even if something happens to your local machine.
- Code Sharing: Git allows you to share code with others easily, avoiding issues like spam filters in emails or outdated methods like USB sticks.
- *Git Provider*: By using a Git provider, you can add your code to a repository and share it with coworkers or friends, who can then access and download it.
- *Version Control*: Others can install Git and use version control while working in the shared repository, ensuring smooth collaboration and code management.
- *Collaboration*: Git allows multiple people to work on the same file by creating copies of the file for each person. Changes can be pushed back to the Git provider and pulled by others to keep everyone updated.
- *Merge Conflicts*: Git has the capability to intelligently merge changes from different versions of a file, though manual intervention may be needed if changes occur at the same level.
- *Version Control*: By using Git, you can see the newest versions of files and understand what changes others have made, facilitating effective teamwork.
- Open Source Definition: Open source means that the code behind the software is publicly available, allowing anyone to download, modify, and use it.
- Community Contribution: The open-source community can contribute by reporting bugs, suggesting features, or directly making changes to the code if they have the skills.
- Branching for Safety: To manage multiple contributors and avoid breaking the main code, Git uses branches. Changes are made in branches and merged into the main code after review, ensuring stability and security.
- *Local Workflow*: Git operates on a local level with a local folder, staging area, and local repository to manage your files.
- *Staging Area*: You add files to the staging area using `git add` to decide which changes to snapshot.
- *Commit Process*: Once changes are staged, you commit them to the local repository using `git commit`, creating a snapshot of the current state of your files.
- *Pushing Code*: You can push your committed files from your local repository to a remote repository using the `git push` command, making them accessible from other devices or to other people.
- *Pulling Code*: To get the latest files from a remote repository to your local device, use the `git pull` command, ensuring you always have the most up-to-date version.
- *Centralised vs. Distributed*: Unlike centralised version control systems where the history is stored only on the server, distributed version control systems like Git store the complete history on every client.
- *Data Safety*: With distributed version control, even if the server fails, every client has a full copy of the history, ensuring data safety.
- *Synchronisation*: The Git provider acts as a central point for synchronisation, but every client has the same files and versions stored locally.
- *Git Complexity*: Git can be challenging to learn initially, but it's important to start with the basics and gradually build your knowledge.
- *Incremental Learning*: You don't need to know all the features of Git to begin using it effectively. Focus on the essentials covered in this course.
- *Community Support*: Many Git users don't know every option or solution. If you encounter issues, you can find answers online.

## Windows Installation
- *Download Git*: Visit (git-scm.com)[https://git-scm.com] to download Git for Windows. The website automatically suggests the appropriate version for your operating system.
- *Installation Wizard*: Use the installation wizard, which provides explanations for various options. You can mostly proceed with the default settings.
- *Configuration Options*: During installation, you can configure settings like the default editor (e.g., Visual Studio Code) and the default branch name (e.g., main).

## Linux Installation
- *Installation Commands*: Visit (git-scm.com/download/linux)[https://git-scm.com/download/linux] to find the appropriate installation commands for your Linux distribution.
- *Ubuntu Pre-installed*: On Ubuntu, Git is often pre-installed. You can check the version using `git --version`.
- *Updating Git*: If you need to update Git, use the command sudo `apt-get install git` to ensure you have the latest version.

## MacOS Installation
- *Check Existing Version*: Open Terminal and use `git --version` to check if Git is already installed and whether it is up to date.
- *Installation Methods*: If you need to install or update Git, you can use Homebrew (`brew install git`), MacPorts, or Xcode.
- *Binary Installer*: While a binary installer is available, it may be outdated. Using Homebrew or MacPorts is recommended for the latest version.

### Git Gui Clients
- *Visualization*: Git GUI clients help visualize the Git process, making it easier to understand and manage large or long-running repositories.
- *Options Available*: There are many GUI clients available on (git-scm.com)[https://git-scm.com], with various options for different operating systems, both free and paid.
- *Visual Studio Code*: Visual Studio Code has built-in Git support and additional extensions like Git History, Git Lens, and Git Graph to enhance your Git experience.

## Installing VSCode
This is entirely Optional but recommended for new people

- Navigate to the official Visual Studio Code website: [https://code.visualstudio.com/](https://code.visualstudio.com/).
- Click the **Download for Windows** (or appropriate operating system) button.
- Once the download completes, open the installer.
- Follow the prompts in the installation wizard:
  - Accept the **Licence Agreement**.
  - Choose the installation location (or leave it as the default).
  - Select any additional tasks (e.g., creating a desktop icon, adding VS Code to the PATH).
- Click **Install** to begin the installation.
- After installation, check the box to **Launch Visual Studio Code** and click **Finish**.

### 2. Install Git
- Navigate to the official Git website: [https://git-scm.com/](https://git-scm.com/).
- Click **Download for Windows** (or select the appropriate operating system version).
- Once the download is complete, open the installer.
- Follow the setup instructions:
  - Accept the **Licence Agreement**.
  - Choose the installation location (or leave the default).
  - Select components (leave the default options if unsure).
  - Choose the default editor used by Git. Select **Use Visual Studio Code as Git's default editor**.
  - Choose the remaining default options unless you have specific preferences.
- Click **Install** to complete the installation process.

### 3. Configure Git with Visual Studio Code
- Open **Visual Studio Code**.
- Press ``Ctrl + ` `` to open the terminal within VS Code.
- Verify Git is installed by typing the following command and pressing **Enter**:
```bash
git --version
```
You should see the version of Git installed.
- Set your user name and email for Git by running these commands (replace with your own details):
```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
### 4. Optional: Install GitLens Extension for Visual Studio Code
- Open Visual Studio Code.
- Click the Extensions icon on the left-hand side or press Ctrl + Shift + X.
- In the search bar, type GitLens and press Enter.
- Click Install to add GitLens to Visual Studio Code. This extension provides advanced Git features directly within VS Code.

### 5. Optional: Install Git Bash (for a more powerful terminal)
- Navigate to Git for Windows.
- Download the Git Bash installer.
- Once downloaded, run the installer and follow the prompts.
- After installation, you can use Git Bash as a terminal in VS Code by selecting it in the terminal dropdown (or by typing bash).

### 6. Verify Integration Between VS Code and Git
- Open Visual Studio Code and create a new folder.
- Open the terminal and initialise a new Git repository with:
```bash
git init
```
- You should now be able to use Git commands in VS Code's terminal and see Git status indicators on files and folders within the editor.