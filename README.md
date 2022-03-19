# Contributing-to-open-source
- The aim of this project is to guide beginners to make their first contribution. If you are looking to make your first contribution, follow the steps below.

![visitor badge](https://visitor-badge.glitch.me/badge?page_id=TG922/Contributing-to-open-source&left_color=default&right_color=red)

### :star: Before starting please kindly read the [Code of Conduct](/CODE_OF_CONDUCT.md) of the repo where you are contributing :star:

## :point_right: Table of Contents :point_left:
  - How to Contribute?
  - How to make a Pull Request? 

    **Task 1: Forking the repo**
    <br>
    **Task 2: Clone the forked repo**
    <br>
    **Task 3: Creating a new branch**
    <br>
    **Task 4: Make Changes in Code**
    <br>
    **Task 5: Commit and Push**
    <br>
    **Task 6: Create Compare and Pull Request**
    <br>
    **Task 7: Create a PR**
    <br>
    **Task 8: Congratulations! 🎉 🎉 You've made your first contribution!**
    <br>

## :thinking:💻 How to Contribute?

- Take a look at the existing ```Issues```
- Create a ```Pull Request```, which will be promptly reviewed and given suggestions for improvements by the community.
- Add screenshot in your ```Pull Request``` to help ```Project Admin``` understand the effects of the changes that are included in your commits.


## :man_shrugging: How to make a Pull Request?

# Task 1: Forking the repo

- To work on a project, we will need to make exact copy of your repo. For doing this, we first fork the repo and then clone it so that we have a local working copy. get your own copy of repo by clicking ```Fork``` button right upper corner !!

![Image19](https://user-images.githubusercontent.com/70098839/159141607-c7198256-1ce7-4704-a62f-1caf4b531a96.PNG)

 

# Task 2: Clone the forked repo

- After the repo is forked, we can now clone it so that we can have a local copy of the codebase. To make our local copy of the do follow these steps,

**:star: Note: Origin = Repo link of our forked project where we are contributing**

![Image18](https://user-images.githubusercontent.com/70098839/159141625-02c35529-a069-40af-b7bc-13287945ac38.PNG)

- Open the Command Prompt
- Type this command:

```bash
$ git clone https://github.com/<your-github-username>/Repo Name
```

# Task 3: Creating a new branch

- This is VIMP step that must be followed to contribute to Open Source organization. A branch helps to manage the workflow, by isolating our code and does not create a mess. To create a new branch,

```bash
$ git branch <name_of_branch>
$ git checkout -b <name_of_branch>
```

- After this we keep our cloned repo up-to-date by pulling from the upstream (this will also avoid any merge conflicts while committing new changes)

**:star: Note: Upstream = Repo link of project where we are contributing**

```bash
git pull origin main
```

# Task 4: Make Changes in Code

- We will make our changes according to the issue that we are assigned for !!


# Task 5: Commit and Push

- Once we have modified an existing file or added a new file to the project, you can add it to your local repo, which we can do with the git add command.

```bash
git add .
```

- With our file staged, we’ll want to record the changes that we made to the repo with the git commit command.
- The commit message is an important aspect of your code contribution; it helps the other contributors fully understand the change you have made, why you made it, and how significant it is.

```bash
git commit -m "Fixed Issue Number message"
```

At this point we can use the **git push command** to push the changes to the current branch of our forked repo **i.e origin**,

```bash
git push origin <branch-name>
```


# Task 6: Create Compare and Pull Request

Now, we are ready to make a **PR** to the original repo **i.e, Upstream**. Now, we should navigate to our **origin repo**, and press the ```Compare & pull request``` button on the page. We should add in a title, a comment, and then press the ```Create pull request``` button.


# Task 7: Create a PR

Detailed Document for [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)!

# Task 8: **Congratulations!** :tada: :tada: You've made your first contribution!

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src= "https://github.com/TG922/Contributing-to-open-source/blob/main/Images/Leonardo%20congrats.gif">


# For those who see the below message in their forked repo

![Image16](https://user-images.githubusercontent.com/70098839/159141733-9f71f0f4-9db6-46ed-a066-718bb36655f1.PNG)

- First Fetch and merge
- Go to terminal and pull the upstream default branch

**:star: Note: Sometimes the default branch name may not be master/main, So we need to check default branch name before pulling the upstream branch**

- Repeat Task 4 to 8 for contributing

 **Congratulations!** :tada: :tada: You've made your first contribution!
 
</br>


