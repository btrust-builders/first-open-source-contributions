[![Bitcoin](https://img.shields.io/badge/Bitcoin-f7931a?style=for-the-badge&logo=bitcoin&logoColor=white)](https://github.com/btrust-builders/first-open-source-contributions)
[<img align="right" width="150" src="https://img.shields.io/badge/Join_us_on_Discord!-gray.svg?logo=discord&logoColor=blue&style=social">](https://www.btrust.tech/builders/discord)
[![Open Source Love](https://img.shields.io/badge/Open_Source-gray.svg?logo=undertale&logoColor=EE0000)](https://github.com/btrust-builders/first-open-source-contributions)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

### Contributors Country Flags
<kbd><img title="Nigeria" alt="Nigeria" src="https://cdn.statically.io/gh/hjnilsson/country-flags/master/svg/ng.svg" width="22"></kbd>
<kbd><img title="Kenya"   alt="Kenya"   src="https://cdn.statically.io/gh/hjnilsson/country-flags/master/svg/ke.svg" width="22"></kbd>
<kbd><img title="Benin" alt="Benin" src="https://cdn.statically.io/gh/hjnilsson/country-flags/master/svg/bj.svg" width="22"></kbd>
<kbd><img title="Uganda" alt="Uganda" src="https://cdn.statically.io/gh/hjnilsson/country-flags/master/svg/ug.svg" width="22"></kbd>
<kbd><img title="Kenya"   alt="Kenya flag"   src="https://cdn.statically.io/gh/hjnilsson/country-flags/master/svg/ke.svg" width="22"></kbd>

# First Open Source Contributions

This project aims to simplify and guide the way beginners make their first open source contribution. If you are looking to make your first open source contribution, follow the steps below.

<img align="right" width="300" src="https://github.com/btrust-builders/first-open-source-contributions/blob/main/assets/fork.png" alt="fork this repository" />

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your personal Github account.

## Clone the repository

<img align="right" width="300" src="https://github.com/btrust-builders/first-open-source-contributions/blob/main/assets/clone.png" alt="clone this repository" />

Now to clone the forked repository to your computer, you should go to your forked repository on Github, click on the `Code` button, then select the `SSH` tab and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```bash
git clone "url you just copied"
```

where _"url you just copied"_ (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://github.com/btrust-builders/first-open-source-contributions/blob/main/assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```bash
git clone git@github.com:your-github-username/first-open-source-contributions.git
```

where `your-github-username` is replace by your real GitHub username. Here you're copying the contents of the first-open-source-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```bash
cd first-open-source-contributions
```

Now create a branch using the `git switch` command:

```bash
git switch -c your-new-branch-name
```

<details>
<summary> <strong>If you get any errors using git switch, click here:</strong> </summary>

If the error message "Git: `switch` is not a git command. See `git –help`" appears, it's likely because you're using an older version of git.

In this case, try to use `git checkout` instead:

```bash
git checkout -b your-new-branch-name
```

</details>

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="https://github.com/btrust-builders/first-open-source-contributions/blob/main/assets/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```bash
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```bash
git commit -m "Add your-name to Contributors list"
```

replacing `your-name` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```bash
git push -u origin your-branch-name
```

replacing `your-branch-name` with the name of the branch you created earlier.

<details>
<summary> <strong>If you get any errors while pushing, click here:</strong> </summary>

- ### Authentication Error
     <pre>remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
  remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
  fatal: Authentication failed for 'https://github.com/<your-username>/first-contributions.git/'</pre>
  Go to [GitHub's tutorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) on generating and configuring an SSH key to your account.

  Also, you might want to run 'git remote -v' to check your remote address.
  
  If it looks anything like this:
  <pre>origin	https://github.com/your-username/your_repo.git (fetch)
  origin	https://github.com/your-username/your_repo.git (push)</pre>
  
  change it using this command:
  ```bash
  git remote set-url origin git@github.com:your-username/your_repo.git
  ```
  Otherwise you'll still get prompted for username and password and get authentication error.
</details>

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://github.com/btrust-builders/first-open-source-contributions/blob/main/assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://github.com/btrust-builders/first-open-source-contributions/blob/main/assets/submit-pull-request.png" alt="submit pull request" />

Your changes will be merged into the main branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll often encounter as an open source contributor!

If you'd like more practice, checkout [open source code contributions](https://github.com/btrust-builders/open-source-code-contributions).

Now let's get you started with contributing to other open source projects. We've compiled a list of Bitcoin open source projects with easy issues you can get started on. Check out [curated bitcoin open source projects](https://bitcoindevs.xyz/projects) or
for good first issues see [Good first issues](https://bitcoindevs.xyz/good-first-issues).

### [Additional material](docs/additional-material/git_workflow_scenarios/additional-material.md)

### [How to Contribute to Open Source](docs/how-to-contribute-to-open-source-projects.md)
