# Git-ing started

In order to get RStudio working with git and GitHub, we need to do a couple of steps.

These have to be done only once and will be forgotten soon after. ;)

1.  Understand what git is: [Section 1. - 1.7](https://happygitwithr.com/big-picture.html)

2.  Create a [GitHub account](https://github.com/signup?user_email=&source=form-home-signup)

    -   you can use your university email address if you only want to create a temporary account
    -   if you want to keep your account, you might want to use your private email address
    -   maybe check these [advices for github user names](https://happygitwithr.com/github-acct.html)

3.  Post your GitHub user name within the respective course exercise submission

4.  Updating your R and RStudio version might be a good idea if you installed them *years ago*

5.  Install git (if not available): [Section 6.2 - 6.4](https://happygitwithr.com/install-git.html)

6.  **RESTART RStudio** and check if it finds git: [Section 13](https://happygitwithr.com/rstudio-see-git.html)

7.  Configure git using RStudio and the `usethis` package:

    -   `install.packages("usethis")` to get the package
    -   `library(usethis)`
    -   use `use_git_config(..)` to register your GitHub credentials: [Section 7](https://happygitwithr.com/hello-git.html)
    -   use `git_default_branch_configure()` to reset `main` branch name: [Section 7 + 7.1.2](https://happygitwithr.com/hello-git.html)

8.  Generate a PAT to enable RStudio-GitHub communication via `usethis` package: [Section 9](https://happygitwithr.com/https-pat.html)

    -   `library(usethis)`
    -   use `git_default_branch_configure(description="R2 course")`
        -   set an **Expiration** *date after the end of the course* (or "No expiration")
        -   *keep the generated PAT website open for Copy-and-Paste !!!*
    -   use `credentials::set_github_pat()` (already installed) to store the PAT: [Section 9.4.1.1](https://happygitwithr.com/https-pat.html#credentials-package)
    
9.  Check if you can [access the project on GitHub](https://github.com/Dr-Eberle-Zentrum/Advanced-data-processing-with-R) (i.e. we registered you as a collaborator already)
    - **if not** you will have to *wait until we have added you...* you will get an email notification from GitHub when done and ready

10. Once you can access the repository online, you will need to get a local copy via RStudio: [Section 16.2.2](https://happygitwithr.com/existing-github-first.html#rstudio-ide-1)
    - the HTTPS URL is `https://github.com/Dr-Eberle-Zentrum/Advanced-data-processing-with-R.git`

11. Change and `push` your changes!
    - create a subfolder within the **Project** folders named as your **FIRSTNAME**
    - create *within* your new folder a new file (best a Markdown file ending in .md) and say "Hi I am here" within the file
    - add the file to git control and push the file to GitHub
    - check online if you can see your file and all is good!
    - **ATTENTION:** if you are working on the repository *at the same time as one of your peers* you might get a notification that you  