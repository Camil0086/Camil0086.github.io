---
layout: default
title: GitHub and GitHub Desktop Guide
parent: GitHub
grand_parent: Technical Communication
nav_order: 3
---

GitHub and GitHub Desktop Guide
===============================

## GitHub registration

To register on GitHub, please go to [GitHub homepage](https://github.com) and click **Sign up** in the right corner or **Sign in** if you already have an account. In the former please follow the instructions to join GitHub.

## GitHub Desktop installation guide
Visit [GitHub Desktop download link](https://desktop.github.com) and choose the proper OS System. Download and install GitHub Desktop. 

## GitHub first steps
After GitHub Desktop installation, open the client and follow the steps below:
1. After the first run please click **Authorize desktop** to authorize GitHub Desktop 
2. Choose **Create a New Repository on your hard drive...** on start-up page or **File => New repository** in the top menu.
3. Type the **Name** and **Description**
4. Carefully choose the **Local path** of your repository. Although you can change the path, it is good practice to choose as short path as possible and don't change it after creating a repository. 
5. Mark **Initialize this repository with a README**. Although it is not essential, it will create a readme file together with the repository. It contains the description you typed in the second step.
6. Leave **Git ignore** and **License** as it is.
7. Click **Create repository**

You have created your first repository. Choose **Repository => Show in Explorer** in the top menu to view your repository. You can also find it on your hard drive by the path you have chosen. 

## How to Publish your repository to GitHub?
After creating a repository click **Publish repository** on GitHub Desktop main page and follow the steps below:
1. In the pop-up window, mark **keep this code private** if you wish to publish your repository only to those GitHub users you invite.
2. Leave **Organization** as it is.
3. Click **Publish repository**.

You have published your first repository to GitHub. Please go to [GitHub homepage](https://github.com) and click your account icon in the top right corner. Choose **Your repositories** from the dropdown menu to find your repository. 

## How to update your repository and add new files or changes to it  
To add new files to your repository please open your local path repository destination folder and follow the steps below:

1. Paste to your destination folder all new files you want to add to GitHub. You can do it with each file separately or by the entire folder. 
For the purpose of this exercise please add all your files concerning Markdown basics together with all pictures and additional files necessary.
2. Go to GitHub Desktop and choose **Changes** on the left sidebar to view all changes made in your local copy of the repository. Please remember that these changes are not yet confirmed and add to your local repository.
3. Please fill the field **Summary (required)** with something that describes the changes you have made and click **Commit to main** to confirm those changes to your local repository. Please remember that those changes are not yet published to GitHub.

To publish your local changes to GitHub repository please click **Push origin** on GitHub Desktop main window or choose **Repository => Push** on the top menu.

You have **committed** and **pushed** your first changes to GitHub repository. You can work on your local repository files and push all changes to GitHub whenever you want them to be available online to your coworkers or any other GitHub users who have access to your repository. It is good practice to **commit** and **push** after every relatively important piece of work.

You can create or upload a new file to your repository directly from your browser. To do it please go to GitHub homepage and choose your repository. On a main page choose **Add file => Create new file / Upload files.** After creating / uploading a new file click **Commit new file / Commit changes** at the bottom of the page. To download changes locally pull up-to-date file to GitHub Desktop.

## How to Pull up-to-date file from GitHub
To download any changes of GitHub repository made by your coworkers or any other users who have access to it, choose in GitHub Desktop **Repository => Pull** on the top menu or click **Fetch origin** under the top menu and then click **Pull origin** on the main window. It is good practice to begin your work with **Pull/Fetch origin**.  
Choose **History** on the left sidebar to view all changes download to your local repository. In the middle section, all files added are marked by a green plus icon ![Green plus icon](../../../../../Camil0086.github.io/docs/images/plusIco.png). All files changed are marked by a yellow dot icon ![Yellow dot icon](../../../../../Camil0086.github.io/docs/images/changesIco.png). In the right section, a color indicates changes. Green if something was added or red if removed.

## How to invite a collaborator to your repository
To grant access to your repository please choose **Settings => Manage Access => Invite a collaborator.** Type the username, full name, or email and add a user to this repository. When you invite someone, you always grant access to the repository you are currently working on. The user will receive an email to confirm the invitation. 

## Troubleshooting

| Trouble | Solution|
| ------- | ------- |
| GitHub doesn't want to verify my email address | click your account icon in the top right corner and choose **settings**. In the left sidebar choose **E-mails**  and resend the verification e-mail. If you see the note **Could not send e-mail verification**, please scroll down the page and unmark **keep your email address private** |
| VSCode shows a note *Git not found. Install it or configure it using the 'git.path' settings* | for the purpose of this exercise you don't need to install Git extensions in VSCode if you are using GitHub Desktop. |
| How to change a local path of your repository | 1. Push all the latest local changes to GitHub. 2. Create a new local path for your repository. 3. close GitHub Desktop and VSCode, and delete the old local path together with all files in it. 4. Open GitHub Desktop and Choose **Clone a repository from the Internet...** on start-up page or **File => Clone repository** in the top menu. 5. Choose your repository from the list. 6. Choose the new local path 7. Click **Clone**