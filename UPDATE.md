## Mini-Project 2: Influx LnD Project

## Step 1

### Summary

In this step, we will fork this tutorial repository.

### Instructions

* On this current GitHub repository, scroll to the top and look for a button that says `fork`.
* Click the `fork` button.
  * <details>

    <summary> What does this do? </summary>

    <br />

    This will essentially copy all of the code from this repository, but make it as a new repository under your account. As you can imagine, you can't push directly to the Influx repo, because that would not be secure for Influx (anyone could make any changes they want). What you should do is create a fork of this repo, then push to your own fork because it's under your own account.

    </details>

## Step 2

### Summary

In this step, we will take the forked repository and clone it down to our machine.

### Instructions

* Go to your forked repository on GitHub. It should appear under `Your repositories` which is next to the `New repository` button.
* Click on the green `clone or download` button and copy the URL.
* Open a terminal window and navigate to your Desktop.
* Run `git clone [the url you copied]`.
  * <details>

    <summary> What does this do? </summary>

    <br />

    This takes what's on GitHub and essentially downloads it so you can now make changes to it on your local computer.

    </details>

## Step 3

### Summary

In this step, we will make changes to our clone and push them to GitHub.

### Instructions

* Open the folder in your coding IDE.
* Make a change in a file.
* Run through the steps outlined in `Step 3` of the first project ( status, diff, add, commit, push ).
  * Since you've cloned this repository, it is already pointing to your forked version. Therefore, you don't need to tell your computer where to push the code.

## Mini-Project 3: Sample Project

## Step 1

### Summary

To help this process stick in memory we are going to repeat the process of the second project. We'll delete our current fork on our machine and restart the process.

### Instructions

* Delete the folder on your Desktop that is the forked repository.
* Re-clone the fork to your desktop.
* Make a change to any file.
* Run through the process of pushing to GitHub ( status, diff, add, commit, push ).

## Step 2

### Summary

Here is where things start to get different. Let's imagine we're working in groups. If we have everyone pushing to one repo without verifying the quality of the code, things can get messy pretty quick. GitHub fixed this solution with 'Pull Requests.' Basically, you fork a project, make changes to your fork, then you make a Pull Request (PR) back into the original project requesting that some piece of code be added to the original repo. This is how the vast majority of open source code projects work. In this step, we will make a pull-request.

### Instructions

* Go to your forked repo on GitHub.
* Locate the button that says `Pull Request` and click it.
* Locate the green button that says `New pull request` and click it.
  * You should now see the file changes you've made and how they differ from the original repo.
* Click on the `Create pull request` button to submit your PR.
* Now if you navigate to the <a href="https://github.com/influx-tech-lnd/learning-git/pulls">original repository</a> and take a look at the `Pull Requests` yours should be there.

## Contributions

If you see a problem or a typo, please fork, make the necessary changes, and create a pull request so we can review your changes and merge them into the master repo and branch.
