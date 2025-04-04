# Git Basic Mini Project 2
<p> This is a mini project to practice Git commands. </p>
<p> The project is aimed to help you understand the basic commands of Git. </p>

## Task 1: Create a new repository
1. Created a new repository on github and then cloned it to your local machine.
![](./images/cloned_to_localhost_3.png)

2. Cloning the repository using SSH methods.
![](./images/created_using_ssh_key_2.png)

3. Created folder for the repo using `mkdir` command.
![](./img/created-folder-for-the-project_4.png)

4. Cloned to the local machine using the command line.
    <p> This command will create a local copy of the repository on your machine. </p>
```git clone <repository-url>```
    <p> The command will create a directory with the same name as the repository. </p>

![](./images/cloned_to_localhost_3.png)

5. Moved to the cloned directory using `cd` command.

![](./images/cd_into_project_folder_5.png)

6. Created a new file using `touch` command.
```git touch <file-name>```
    <p> This command will create a new file in the current directory. </p>
![](./images/)

7. Checked the status of the repository using `git status` command.
```git status```
    <p> This command will show you the current status of the repository. </p>
![](./images/check_status_of_repo_.png)

8. Added the file to the staging area using `git add` command.
```git add <file-name>```
    <p> This command will add the file to the staging area. </p>
![](./images/)

9. Committed the changes using `git commit` command.
```git commit -m "<commit-message>"```
    <p> This command will commit the changes to the repository. </p>
![](./images/commit_and_ready_to_push_10.png)

10. Successfully pushed the changes to the remote repository using `git push` command.
```git push origin <branch-name>```
    <p> This command will push the changes to the remote repository. </p>
![](./images/push_update_19.png)

11. Check current branch using `git branch` command.
```git branch```
    <p> This command will show you the current branch. </p>
![](./images/check_cuurent_branch_12.png)

12. Created a new branch for Tom using `git checkout -b` command.
```git checkout -b <branch-name>```
    <p> This command will create a new branch and switch to it. </p>
![](./images/git_checkout_b_add-contact-info_22.png)

13. Confirmed the branch using `git branch` command.
```git branch```
    <p> This command will show you the current branch. </p>
![](./images/check_status_of_repo_.png)

14. Editing the html file on Tom's branch.
```git touch <file-name>```
    <p> This command will create a new file in the current directory. </p>
![](./images/created_an_index_file_6.png)

15. Confirmed the changes using `git status` command.
```git status```
    <p> This command will show you the current status of the repository. </p>
![](./images/check_status_of_repo_.png)

16. Added the changes to the staging area using `git add` command.
```git add <file-name>```
    <p> This command will add the file to the staging area. </p>
![](./images/commiting_18.png)

17. Commit and push the changes to the remote repository using `git commit` and `git push` commands.
```git commit -m "<commit-message>"```
```git push origin <branch-name>```
    <p> This command will commit the changes to the repository. </p>
    <p> This command will push the changes to the remote repository. </p>
![](./images/commit_and_ready_to_push_10.png)

18. Switched back to the main branch using `git checkout` command.
```git checkout <branch-name>```
    <p> This command will switch to the specified branch. </p>
![](./images/git_checkout_b_add-contact-info_22.png)

19. Pulled changed from update-nav branch using `git pull` command.
```git pull origin <branch-name>```
    <p> This command will pull the changes from the specified branch. </p>
![](./images/git_checkout_main_21.png)

20. Checkout and switched to add-contact-info branch using `git checkout` command.
```git checkout <branch-name>```
    <p> This command will switch to the specified branch. </p>
![](./images/git_checkout_main_+_20.png)

21. Confirm changes and push to the remote repository using `git status` and `git push` commands.
```git status```
```git push origin <branch-name>```
    <p> This command will show you the current status of the repository. </p>
    <p> This command will push the changes to the remote repository. </p>
![](./images/successfull_pushed_11.png)
![](./images/repo_img_1.png)

