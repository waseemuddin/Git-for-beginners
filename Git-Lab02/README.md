
Please follow the below links for more updates and Projects

💾 <a href="https://shaikhwaseem.com" target="_blank">shahikhwaseem.com</a> <br>

💾 <a href="https://www.youtube.com/@waseeemuddin" target="_blank">Follow my YouTube channel</a>


##  GIT Lab 02 - How to Create and Manage Git Branches

In this lab-02 we will look at the Git Brnach and how to create git branch and manage branches

# ![gitbranch](src/gitbranch.png)


### Example - Consider as real case project

Let's consider a real-world project example: building a website. Imagine you and your team are working on a website project, and you decide to use Git to manage your code.

1- **Main Branch (Master/Branch):**  Your main branch, often called "master" or "main", represents the stable version of your website that's ready to be published. It contains all the finished features and bug fixes.

2- Creating a New Branch: Let's say you want to add a new feature to your website, like a contact form. You create a new branch called "contact-form".

``` shell

$ git checkout -b contact-form

```
3- Making Changes: On the "contact-form" branch, you work on adding the contact form feature to your website. You create HTML, CSS, and JavaScript files for the form.

4- Committing Changes: Once you're done, you commit your changes to the "contact-form" branch.

``` shell
$ git add .
$ git commit -m "Added contact form feature"

```

5- Switching Between Branches: Now, let's say your team needs you to fix a critical bug on the main website. You switch back to the main branch to address it.

``` shell

$ git checkout main

```
6- Making Changes: On the main branch, you fix the bug by editing the affected files.

7- Committing Changes: After fixing the bug, you commit your changes to the main branch.

``` shell

$ git add .
$ git commit -m "Fixed critical bug"

```

8- Merging Branches: Once the bug is fixed and the contact form feature is complete, you merge the "contact-form" branch into the main branch.

``` shell

$ git checkout main
$ git merge contact-form

```
9- Deleting a Branch: After merging, you can delete the "contact-form" branch.

``` shell

$ git branch -d contact-form

```

