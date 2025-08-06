# Creating a Git Repository, Cloning, Adding Folders, Committing, and Pushing (Deadly Weapon Edition)

This guide walks you through the process of creating a Git repository, cloning it to your local machine, creating folders inspired by the "Deadly Weapon" movie series, committing your changes, and pushing them to the remote repository.

## 1. Creating a New Repository on GitHub

1.  **Sign in to GitHub:** Go to [https://github.com/](https://github.com/) and sign in to your account. If you don't have one, create a new account.
2.  **Create a New Repository:**
    *   Click the "+" button in the upper-right corner and select "New repository".
    *   Give your repository a name (e.g., `deadly-weapon-files`).
    *   Add a description (e.g., "Files and scripts related to the Deadly Weapon movie series").
    *   Choose whether to make the repository public or private.
    *   You can optionally initialize the repository with a README file. This is a good practice.
    *   Click "Create repository".

## 2. Cloning the Repository to Your Local Machine

1.  **Get the Repository URL:** On your GitHub repository page, click the "Code" button. You'll see options for cloning with HTTPS, SSH, or GitHub CLI. Choose the method you prefer and copy the URL.
2.  **Open Your Terminal:** Open your terminal or command prompt.
3.  **Navigate to Your Desired Directory:** Use the `cd` command to navigate to the directory where you want to store the cloned repository (e.g., `cd Documents/Projects`).
4.  **Clone the Repository:** Use the `git clone` command followed by the repository URL you copied:

    ```bash
    git clone <repository_url>
    ```

    For example:

    ```bash
    git clone https://github.com/your-username/deadly-weapon-files.git
    ```

    This will create a local copy of the repository on your machine.

## 3. Creating Folders (Deadly Weapon Style)

1.  **Navigate into the Cloned Repository:** Use the `cd` command to enter the newly cloned repository:

    ```bash
    cd deadly-weapon-files
    ```

2.  **Create Folders:** Create folders relevant to the "Deadly Weapon" theme. For example:

    ```bash
    mkdir murtaugh_files riggs_files leo_getz_files scripts evidence
    ```

    These commands will create the following folders:

    *   `murtaugh_files`: For files related to Roger Murtaugh.
    *   `riggs_files`: For files related to Martin Riggs.
    *   `leo_getz_files`: For files related to Leo Getz.
    *   `scripts`: For scripts or screenplays from the movies.
    *   `evidence`: For any evidence or case files.

## 4. Staging, Committing, and Pushing Your Changes

1.  **Stage Your Changes:** Use the `git add` command to stage the newly created folders. You can add all changes using:

    ```bash
    git add .
    ```

2.  **Commit Your Changes:** Use the `git commit` command to commit the staged changes with a descriptive message:

    ```bash
    git commit -m "Added Deadly Weapon themed folders"
    ```

3.  **Push Your Changes:** Use the `git push` command to push your local commits to the remote repository on GitHub:

    ```bash
    git push origin main
    ```

    If you have set up a different branch name, replace `main` with your branch name.

## Conclusion

You have successfully created a Git repository, cloned it to your local machine, created "Deadly Weapon" themed folders, committed your changes, and pushed them to GitHub. Now you can start adding files and content to your repository!
