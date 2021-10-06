<img src="./utils/MSAC.jpg" width="110px" style="border-radius : 21%">

# First Contributions

This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below:

If you're not comfortable with command line, [here are tutorials using GUI tools](tutorials-using-other-tools).

If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git).

---

## Fork the Repository

Fork this repository by clicking on the `Fork` button on the top of this page. This will create a copy of this repository in your account.

<img align="right" width="300" src="https://MSCKIIT/first-contributions/.github/assets/README/fork.png" alt="Fork the Repository"/>

---

## Clone the Repository

Clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the `Code` button and then click the `Copy to Clipboard` icon.

<img align="right" width="300" src="https://MSCKIIT/first-contributions/.github/assets/README/clone.png" alt="Clone the Repository"/>

Open a terminal and run the following git command:

```
git clone https://github.com/<your_username>/MSCxHacktoberfest.git
```

<img align="right" width="300" src="https://MSCKIIT/first-contributions/.github/assets/README/copy-url.png" alt="Copy URL to Clipboard"/>

---

## Create a Branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-msc-kiit
```

The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.

---

## Make Necessary Changes and Commit the Changes

Now open `CONTRIBUTORS.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add CONTRIBUTORS.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors' List"
```

By replacing `<your-name>` with your full name.

---

## Push Changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

By replacing `<add-your-branch-name>` with the name of the branch you created earlier.

---

## Submit Your Changes for Review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

Now submit the pull request.

Soon all your changes will be merged into the master branch of this project. You will also get a notification e-mail once the changes have been merged.

---

## Where to Go from Here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll encounter often as a contributor.

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on. Check out the list of projects.

---

[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/cc-0.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

---

## License

**[MIT License](https://github.com/MSCKIIT/first-contributions/blob/main/LICENSE "MSC First Contributions License")**

---
   
## About Us
   
Visit **[MSC KIIT](https://www.instagram.com/msckiit/ "Instagram")** for more information
