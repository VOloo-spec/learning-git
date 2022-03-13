# Project Summary

Practice using git + Github

This project will consist of three separate mini-projects to get you comfortable with the kinds of activities you'll be using git for throughout the class. 

In the first mini-project, you'll be mimicking the steps you'll take when you first start your personal project. Creating a repository, linking it to your computer, then pushing those changes up to your GitHub.

In the second mini-project, you'll be mimicking the steps you'll take with nearly every Tech LnD project you do. You'll 'fork' this repository, link your computer with your fork, then push those changes up to your GitHub.

Finally, you'll make a 'Pull Request' into your this repo with what changes you've made.

## Mini-Project 1: Personal Project

## Step 1

### Summary

In this step we will create a repository on GitHUB.

### Instructions

* Go to <a href="https://github.com/">GitHub</a>.
* Sign in to GitHub.
* On the right side of the page, click on the green `New repository` button.
* Give your repository any name you like and make sure that the repository is public.
* Also make sure that the `Initialize this repository with a README` is <b>NOT</b> checked.

## Step 2

### Summary

In this step we will setup the origin for the repository. We'll do this by connecting code on our computer to the GitHub repository we just created.

### Instructions

* Create a folder called `myProject`.
* Go into that folder.
* Create a file and add your name to that file.
* Save the file and open a terminal window.
* In your terminal window, `cd` to your `myProject` folder. O
* Run `git init`. 
  * <details>

    <summary> What just happened? </summary>

    <br />

    You've just told your computer that you want git to watch the `myProject` folder and to keep track of any changes. This also allows us to run git commands inside of the folder. (Warning:  Be very careful to make sure you're in the right directory when you run `git init`!)

    </details>
* Run `git remote add origin [Repository URL goes here]`. You can get your URL from going to repository you made earlier in your browser and copying the address.
  * <details>

    <summary> What just happened? </summary>

    <br />

    Basically, we tell our computer "Hey, I created this repo on GitHub, so when I push, I want my code to go to this GitHub repo." Now whenever you run `git push origin main` your computer knows that origin is pointing to your repo you made on GitHub and it pushes your changes there.

    <br />

    ( If you accidentally DID initialize your repository with a README, you must do a `git pull origin main` first - to get the README file on your computer - before you'll be able to push. ) 

    </details>

## Step 3: Push your code to GitHub

### Summary

In this step, we will push code to GitHub.

### Instructions

* Open a terminal window and make sure it is in the directory of `myProject`.
* Run `git status`.
  * <details>

    <summary> What does this do? </summary>

    <br />

    This will show what files have been changed. This also helps us determine what files we want to add to GitHub and what files we don't want to add to GitHub.

    </details>
* Run `git diff`.
  * <details>

    <summary> What does this do? </summary>

    <br />

    This will show the actual code that has been changed. Again, we want to make sure we don't push anything to GitHub that shouldn't be there.

    </details>
* Run `git add nameOfMyFile.fileExtension`.
  * <details>

    <summary> What does this do? </summary>

    <br />

    This adds our file(s) to the 'staging area'. This is basically a fail safe if you accidentially add something you don't want. You can view items that our staged by running `git status`.

    </details>
* Run `git commit -m "The sentence I want associated with this commit message"`.
  * <details>

    <summary> What does this do? </summary>

    <br />

    This tells your computer: 'Hey, the next time code is pushed to GitHub, take all of this code with it.' The message also specifies what GitHub will display in relation to this commit.

    </details>
* Run `git push origin main`
  * <details>

    <summary> What does this do? </summary>

    <br />

    Your code is now pushed to GitHub. Be sure to include `origin main`, as this tells GitHub which branch you want to push to, and creates the branch if it doesn't exist yet.

    </details>
* Go to your repository on GitHub and see your updates.

* Once you're done with these steps head over to the UPDATE.md file and proceed with the next steps
