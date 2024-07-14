# Steps for Setting up Github with VS Code
---

## Background

To be familier with using github and its set up with VS code, there are certain tasks you should be able to do such as creating gmail account or creating github account as going through every basic steps is necessary. Today, we'll be focusing on the following:
1. Steps to create a Gmail account
2. Steps to create a Github account
3. Steps to connect Github account with VS Code
4. Steps to clone/pull repository
5. Steps to push folder to Github
6. Steps to host a website in Github

## 1. Creating a Gmail account
    1. Open gmail in your browser or go to "accounts.google.com".
    2. Click on "Create account".
    3. You will be provided with account types. Click on "For my person use" or "For my child" or "For work or my business".
    4. Enter your details: First Name, Last Name, Date of Birth, Gender, Desired mail id and set a strong password.
    5. Create verification methods and also verify your phone number.
    6. Click on "Agree to terms and conditions"
    7. You just created your own gmail account.

## 2. Creating a Github Account 
    1. Go to "www.github.com".
    2. Click on "Sign up".
    3. Enter all the details: your email, password and verify the email using OTC and set a unique username.
    4. Select "Free Plan" or pro if you are willing to pay for advanced features.
    5. You just created your own github account.

### 3. Steps to connect Github account with VS Code
    1. Install and open VS code in your computer.
    2. Install "Github Pull Requests and Issues" extensions from the Extensions tab on your left
    row.
    3. Sign in to github by opening Command Palatte.
    4. Now your default browser will open prompting you to authorize VS Code to access your Github account.
    5. Click on " Authorize Visual Code".
    6. Your github account is connected to VS Code.

## 4. Cloning/Pulling a Repository from Github

### Cloning Repository
    1. Open the VS Code.
    2. Open the command palatte (press F1) and type "Git: Clone" and select the command.
    3. Copy and paste the URL of the repo you want to clone.
    4. Choose the local directory where your repository will be cloned.
    5. Now, your repo is cloned in your local device.

### Pulling Repository
    1. In the VS Code, open the terminal pannel.
    2. Type 'cd' command to navigate to your local repository directory.
    3. Type 'Git Pull' and enter to pull the latest changes from the remote repo to the local.

## 5. Pushing a folder/repo to the github
    1. In the VS Code, open the terminal pannel and navigate to your local repository directory by using 'cd' command.
    2. Initialize git by typing 'git init' if your repo is new.
    3. Stage your all the files by typing 'git add' command.
    4. Commit your changes with a message by typing 'git commit -m "Initial Commit" '.
    5. Add the remote repository by typing 'git remote add origin (repo url)'.
    6. Push your changes to the remote repository by typing 'git push -u origin master'

## 6. Hosting a Website in Github
    1. Open github and go to your desired repository.
    2. Click on "Settings" at the top write of your repository window.
    3. Scroll down to the "Pages" section.
    4. Select source which is usually "Deploy from your branch" and select branch "main".
    5. Click "Save".
    6. Wait few moments, refresh the page and your website will now be hosted at the provied url.

    


