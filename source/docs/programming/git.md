# Using Git

## Resources

[Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)  
[Git Website](https://git-scm.com/)

## About Git

Git is a version control system for your code that manages changes over time. It makes it easier for multiple people to work on code together, keeps track of your edits, and allows you to roll back to working code if something breaks.

!!! info "Mind the Platform"

    This guide assumes you are using GitHub as your git server. If you are using a different platform (such as GitLab), most of the git-related steps are still the same, but there may be some variations.

## Git Lingo

| Term                  | What It Means                                                                     |
| --------------------- | --------------------------------------------------------------------------------- |
| Repository (repo)     | A project folder managed by Git                                                   |
| Commit                | A saved snapshot of your code at a specific moment                                |
| Branch                | A separate workspace for working on new features                                  |
| Merge                 | Combining changes from one branch into another                                    |
| Pull/Push             | Downloading (pull) or uploading (push) changes between your local repo and GitHub |
| Organization          | A group of repositories all managed and owned by multiple people                  |

## Advantages of Git
Using git, especially in the FIRST Tech Challenge has many advantages, such as:

- Allowing for quick and easy rollbacks if a mistake is made
- Making it easier and safer for multiple people to work on a codebase
- Recording a history as the code evolves, which can potentially be used as evidence for awards
- Making experimenting safer, as new ideas can be tried in a different branch without breaking the main code

## Getting Started with Git for FTC

Now that you've opted to use git for your code, let's get you and your programmers ready to contribute and make new code!

!!! info "Written for FTC"

    These instructions for setting up git are designed specifically for use in the FIRST Tech Challenge.

### Setting Up GitHub

1. Instruct your programmers to create a GitHub account if they haven't already.
2. Create a GitHub organization.
3. Invite the rest of your programmers to the organization.
4. Create your repositories for your code.

### Install Git

Have your programmers follow these instructions to set up git on their system if they haven't already:

1. [Download](https://git-scm.com/downloads) and install git for your operating system.

    !!! tip "Download Git Even If Your IDE Has It"

        Even if your IDE (such as Android Studio and Visual Studio Code) has git support built-in, it's still a good idea to have a dedicated install of git, as many IDEs don't support the full feature set of git.

    !!! tip "Try a GUI"

        Use a GUI if you aren't familiar with the command line interface, as the CLI can be more intimidating to use at first. You can find a list of GUIs [here](https://git-scm.com/downloads/guis). If you don't know which one to pick, start with [GitHub Desktop](https://desktop.github.com/download/).

### Clone the Repo

Now that you have a repository for your code, now it's time to save the code to the programmer's computer.

=== "Git CLI"

    1. Open your terminal app.
    2. Navigate to the folder you want to store the code in.
    3. Copy the URL to the repository you want to clone.
    4. Run `git clone [pasted-link]`.

=== "Github Desktop"

    1. Click the `Current Repository` option.
        ![GitHub Desktop Repo Selector](../assets/ghdesktop/reposelector.png)
    2. Click `Add`, then `Clone Repository`.
        ![GitHub Desktop Add Repo](../assets/ghdesktop/addrepol.png#only-light)
        ![GitHub Desktop Add Repo](../assets/ghdesktop/addrepod.png#only-dark)
    3. Search for your repo in the list, or paste in the URL.
        ![GitHub Desktop Clone Repo](../assets/ghdesktop/clonerepol.png#only-light)
        ![GitHub Desktop Clone Repo](../assets/ghdesktop/clonerepod.png#only-dark)
    5. Set the path you want the repository to clone to.
    6. Click `Clone`.

## Organizing Your Repo

* Keep your working code in your default branch (usually called `main`)
* For your main branch, stick to a simple name, such as `main` or `master`, to keep things simple
* Create new branches for new ideas or major edits
* Commit frequently, and write meaningful commit messages
* Merge branches once testing is complete
* Consider using GitHub issues for task tracking
* Use `.gitignore` to prevent unnecessary files from clogging up your repo, such as `DS-Store`.