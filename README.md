
## Step 1: Install Git

To use git, you first need to install it. 

- **Mac OSX**
  - Download the [Git installer](https://sourceforge.net/projects/git-osx-installer/)
  - Run the installer and follow the instructions
- **Windows** 
  - Download the [Git installer](https://git-scm.com/download/win)
  - Run the installer and follow the instructions
  
## Step 2: Create a GitHub Account

Create an account on [GitHub](https://github.com/).

## Step 3: Set Up Git

Once Git is installed, you will need to configure it. Run the following commands in your terminal:
```
git config --global user.name "<Your Name>"
git config --global user.email "<your-email-address>"
```

## Step 4: Create a Repository

To create a new repository on GitHub, go to the [GitHub homepage](https://github.com/). Click the **+** icon in the top right corner and select **New repository**.

Name your repository and select **Create repository**.

## Step 5: Clone the Repository

Once the repository is created, you will need to clone it to your local machine. To do this, open a terminal window and navigate to the directory where you want the repository to be located. Then, run the following command: 
```
git clone <repository-url>
```

Where `<repository-url>` is the URL of the repository on GitHub.

## Step 6: Make Changes to the Repository

Now that you have cloned the repository to your local machine, you can make changes to the files. When you are done making changes, you will need to commit them to the repository. To do this, run the following commands:

```
git add <file-name>
git commit -m "<commit-message>"
```

Where `<file-name>` is the name of the file you want to add and `<commit-message>` is a message describing the changes you have made.

## Step 7: Push Changes to GitHub

Once you have committed your changes, you will need to push them to GitHub. To do this, run the following command:

```
git push origin master
```

This will push your changes to the `master` branch of the repository on GitHub.

## Step 8: Create a Pull Request

If you want to share your changes with others, you can create a pull request. To do this, go to the repository page on GitHub and click the **Pull requests** tab. Then, click the **New pull request** button.

Add a title and description for the pull request and click **Create pull request**.

Once the pull request is created, others can review your changes and merge them into the repository if they decide to accept your changes.