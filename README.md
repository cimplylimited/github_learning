# github_learning
Some instructions on how to setup github on your computer


  - [Creating Pull Requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)



  - The entire [Pro Git Book](https://git-scm.com/book/en/v2) , written by Scott Chacon and Ben Straub and published by Apress, is available here. All content is licensed under the Creative Commons Attribution Non Commercial Share Alike 3.0 license. Print versions of the book are available on Amazon.com.

  - The version found here has been updated with corrections and additions from hundreds of contributors. If you see an error or have a suggestion, patches and issues are welcome in its GitHub repository. 


  - https://www.youtube.com/watch?v=5BSpJ0bpE14
How to use the github desktop app to use a repository from a Graphical User Interface.



  - https://docs.pyup.io/docs/securing-your-python-environments
Helping secure your github environment

## Best practice when working with existing repositories
To begin working with a GitHub repository locally, follow these steps:

1. **Clone the Repository:**

   The first step is to clone the GitHub repository to your local machine. Cloning creates a local copy of the remote repository on your computer. Use the `git clone` command with the repository URL. Replace `<repository-url>` with the actual URL of the GitHub repository:

   ```bash
   git clone <repository-url>
   ```

   For example:

   ```bash
   git clone https://github.com/username/repository.git
   ```

   This command creates a directory with the same name as the repository and initializes a Git repository within it.

2. **Navigate to the Local Repository:**

   Use the `cd` (change directory) command to navigate to the directory created by the `git clone` command:

   ```bash
   cd repository
   ```

   Replace `repository` with the name of the cloned repository.

3. **Configure Git:**

   If you haven't already, configure your Git identity with your name and email address. These settings will be associated with your commits:

   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your@email.com"
   ```

   Replace "Your Name" and "your@email.com" with your actual name and email address.

4. **Check Remote Information:**

   You can check the remote repository associated with your local repository using the following command:

   ```bash
   git remote -v
   ```

   This command will show you the fetch and push URLs for the remote repository. By default, the "origin" remote points to the GitHub repository you cloned.

5. **Create and Switch to a Branch (Optional):**

   If you plan to work on a specific feature or fix, it's a good practice to create a new branch for your work. Use the following command to create a new branch and switch to it:

   ```bash
   git checkout -b your-branch-name
   ```

   Replace `your-branch-name` with the name of your new branch.

6. **Make Changes:**

   Start making changes to the files in your local repository using your preferred text editor or development environment.

7. **Add and Commit Changes:**

   After making changes, you need to stage and commit them. Stage the changes with the `git add` command and commit them with a descriptive message using `git commit`:

   ```bash
   git add .
   git commit -m "Your commit message"
   ```

8. **Push Changes (Optional):**

   If you want to share your changes with the remote GitHub repository, use the `git push` command. For example, to push changes to the "main" branch:

   ```bash
   git push origin main
   ```

   Replace "main" with the name of the branch you're working on.

9. **Pull Changes from the Remote Repository (Optional):**

   If you're working with a team or if others have pushed changes to the GitHub repository, you can use the `git pull` command to fetch and merge the latest changes from the remote repository into your local branch:

   ```bash
   git pull origin main
   ```

   Replace "main" with the name of the branch you're working on.

10. **Repeat:**

    Continue making changes, committing, and pushing as needed. When you're ready to contribute to the GitHub repository, you can create a pull request from your branch to the repository on GitHub.

By following these steps, you can start working with a GitHub repository locally, make changes, and collaborate with others on your project.




