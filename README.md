# Advanced-data-processing-with-R

This project accompanies the course

**"R2 - Advanced data processing in R"**

at the Dr. Eberle Centre for digital competencies at the University Tübingen.

## Tutorials

-   [Git-ing started](Tutorials/git-started.md)

## Overview

-   [Project descriptions](#project-descriptions)
    -   [Phase 1 - Drafting a project description](#phase-1---drafting-a-project-description)
    -   [Phase 2 - Reviewing a project description](#phase-2---reviewing-a-project-description)
    -   [Phase 3 - Finalizing your project description](#phase-3---finalizing-your-project-description)
-   [Tackling a suggested project](#tackling-a-suggested-project)
    -   [Phase 1 - Posting your initial solution](#phase-1---posting-your-initial-solution)
    -   [Phase 2 - Reviewing and finalizing](#phase-2---reviewing-and-finalizing)

------------------------------------------------------------------------

## Project descriptions {#project-descriptions}

During the course, you have to formulate a data wrangling project.
That is, you should name or provide a data set, say how the data should be (re)structured and set some visualization goals.
You can use a data set you are working on (note, you might have to make it anonymous to share it) or a data set freely available online, from a publication, whatever.
I strongly suggest "dirty" data that has to be cleaned up and reformatted!
Data cleanup, transformation and extension should be one (big) part of your project!

The formulated projects are the set of exercises you and your fellow students will pick from during the rest of the course, which is discussed below.
But first, some details concerning project definition.

------------------------------------------------------------------------

### Phase 1 - Drafting a project description {#phase-1---drafting-a-project-description}

<img src="https://img.icons8.com/external-flaticons-lineal-color-flat-icons/344/external-project-web-development-flaticons-lineal-color-flat-icons.png" width="100px"/>

Before you can define a project you need some data!
In order to select something, you might want to "reach high"!
That is, think about something you would like to know or see and what data might be needed for that.
Don't think in terms of "I know how to do" but more "I would like to see" (like "A BOSS")!
Given an idea, start looking for data sets that might help you to provide the information for your idea.
Either you find something useful, or you might change your idea while looking for and investigating available data.

#### Data sets

Best are data set you are working on anyway or that are connected to your field of interest, such data makes most sense to you and you are most creative about possible analyses.
Or something you have discussed in some other course or project.
It would be **best**, if the data is already in some **table form but not tidy**, i.e. there is still need for some (extensive) data cleaning, formatting, ...

You might not have a data set at hand, so check out open data repositories, websites, etc.
Some open data repositories or search engines are listed at

-   [https://libguides.graduateinstitute.ch](https://libguides.graduateinstitute.ch/rdm/repositories)
-   [https://handsondataviz.org](https://handsondataviz.org/opendata.html)
-   [https://github.com/awesomedata](https://github.com/awesomedata/awesome-public-datasets)

Note down where you got your data from, since you will later have to provide some details about your data!

#### Visualization goals

Next, formulate some rough idea what you would like to see.
If you want to (re)produce a plot you have seen, store the image.
Or just draw a sketch by hand of how it should look like and make a photo.
Anything to transport your idea is fine.

Double check that you think the data set you picked provides (somehow) all information needed to draw your plot of interest.

#### Write up your project description

Write an R Markdown file `project-description.Rmd` to

-   introduce shortly the general topic of your task (to put it in context)
-   introduce the data set, it's origin and important information of what-is-what, etc.
-   define the visualization goal(s) and possible intermediates

It is fine to be vague at some points but you should formulate a clear goal and roadmap.

#### Upload to GitHub

In order to submit your project proposal, you have to upload it to GitHub as part of this project!
To this end:

-   (if not done already) create a subfolder with **your user account name** in the `Project` folder
-   copy the following files to the folder:
    -   your `project-description.Rmd` file from above
    -   all files linked to, loaded or referenced within the project description (data sets, images, ...)
-   knit the file to `HTML` output
-   check if all is nicely rendered within the created HTML file
-   `Pull` the recent project version from the GitHub repository
-   `Commit` all new files to git versioning
    -   Markdown, images, .html output file, ...
-   `Push` your changes to GitHub
-   Check online if your HTML file is listed on GitHub
-   Change this `README.md` file and add your project to the following list of `Available projects` below
    -   to this end, you have to put a relative link to the html page, see example link
-   `Commit` and `Push` your changes to GitHub
-   wait a minute (to get things published automatically)
-   check the [project website](https://dr-eberle-zentrum.github.io/Advanced-data-processing-with-R/) if your project draft is listed, linked and correctly rendered

#### Available projects

-   [example project by Martin](Projects/martin-raden/project-description.html)
- [first draft of Dana's project](Projects/dana-jabari/cloze-task-project.html)
-   [Project by Bernhard](Projects/bernhard-ebersbach/readme.html)
-   [Project by Fanyi](Projects/meng/project-description.nb.html)
- [Project by Ferdinand](Projects/FerSoe/Project1/Projectdescription.html)
- [Project by Jan](Projects/jan-boethling/project-description_Jan.html)
- [Project by Zoé](Projects/zoebuerger/mood_stress_ZB.html)
- [Project by Eric](Projects/offi24/Beispiel_R_Markdown.html)


#### Goals

At the end of Phase 1 you will have a better understanding of

-   How to write stuff in R Markdown
-   How to produce presentable output from it
-   How to get things into version control in GitHub
-   See the integration of Markdown and HTML pages in GitHub Pages

------------------------------------------------------------------------

### Phase 2 - Reviewing a project description {#phase-2---reviewing-a-project-description}

<img src="https://img.icons8.com/external-filled-outline-geotatah/344/external-comment-customer-satisfaction-filled-outline-filled-outline-geotatah.png" width="100px"/>

To ensure the drafted projects are understandable and doable, we will do a peer reviewing.
To this end, you will get assigned to two projects to give feedback for them.
Review comments should be done via GitHub issues, where you can also discuss you ideas and suggestions with the respective project owner.

#### Raising issues

For each project draft, we will assign two reviewers at random.

**Each reviewer** is supposed to

-   read the respective project draft on GitHub Pages
-   open an Issue on GitHub within the project
-   provide constructive feedback w.r.t.
    -   understandability
    -   missing information
    -   possible extensions or other ideas in the scope of the project and data
-   "ping" the project owner by referencing his/her user name with an "\@", like `Hi @martin-raden, what do you think about my comments!`

**Each project owner** is supposed to

-   carefully check the reviews for his/her project
-   respond to the reviews (verbosely! not just *"Yes, sounds good!"*)
    -   you can also argument why you don't want to do this or that etc..
    -   it is YOUR rebuttal of the review!

**DON'T CHANGE THE PROJECT DRAFT SO FAR!!!** (Since this will interfere with the second review!)

#### Goals

At the end of Phase 2 you will

-   Get used to the Issue-based communication on GitHub
-   Practice your "constructive criticism" skills
-   Get and discuss feedback on your own project draft

------------------------------------------------------------------------

### Phase 3 - Finalizing your project description {#phase-3---finalizing-your-project-description}

<img src="https://img.icons8.com/external-phatplus-lineal-color-phatplus/344/external-project-design-thinking-phatplus-lineal-color-phatplus-2.png" width="100px"/>

Now it is time to rework your project draft in the light of the received reviews and the project drafts you have reviewed yourself.
You might want/need to change a few bits and pieces.
In the end, you might do the following:

-   `Pull` the current state of the project (just to be up-to-date)
-   revise your R Markdown project description
-   double check the Issues with the review comments to see if you incorporated everything
-   knit your description to HTML output
-   `Pull` again the current project state from GitHub
-   `Commit` your changes
-   `Push` your committed changes to GitHub
-   Check your changes on the [project website](https://dr-eberle-zentrum.github.io/Advanced-data-processing-with-R/) (after a minute or two)
-   Close the Issues *you received for your project* (with a nice comment) :-)

#### Goals

At the end of Phase 3 you will

-   have exercised a feedback loop of project work
-   be familiar with basic git commands in RStudio
-   have experienced the Issue feature of GitHub from both sides (raise and close)

------------------------------------------------------------------------

## Tackling a suggested project {#tackling-a-suggested-project}

Given a project description, you will try to solve the task.
In order to practice real work flow life cycles, you will create your solution first in your own git branch and suggest it via a pull request on GitHub.
This provides the project owner the possibility to review your solution and to give you feedback, which you can discuss within the pull request.
Once all are happy with the solution it can be merged into the main branch of the course repository and thus be published.

This workflow is described and summarized in

-   [Section 6.5 Your repo with branching](https://edav.info/github.html#your-repo-with-branching)
-   [Step 4: Branch](https://edav.info/github.html#step-4-branch)
-   [Step 5: Work, commit and push](https://edav.info/github.html#step-5-work-commit-and-push)

Note: we are still working all on ONE GITHUB REPOSITORY!
We do *not create a fork*, i.e. our own copy of the repository on GitHub, which is also detailed in the linked material.
The latter (forking) is needed, if you don't have writing permissions to a repository.
But the overall workflow is more or less the same.

------------------------------------------------------------------------

### Phase 1 - Posting your initial solution {#phase-1---posting-your-initial-solution}

<img src="https://img.icons8.com/external-justicon-lineal-color-justicon/344/external-coding-responsive-web-design-justicon-lineal-color-justicon-3.png" width="100px"/>

#### Prepare the file

-   **before you start** working on your project solution:
    -   create YOUR branch (remember [Step 4: Branch](https://edav.info/github.html#step-4-branch))
    -   **ensure** you have switched to the branch in RStudio (upper right corner in "Git" pane)
-   now you are ready to **create your solution file**:
    -   go into the project folder of the project you are working on
    -   create a new *R Notebook* (File \> New File \> ...) with name `youGithubName.Rmd`
        -   your will program your solution within this file
        -   on "Save", RStudio will automatically create an HTML output file for you
            -   you can check it using Ctrl+Shift+K (or Cmd on Mac)
-   add the `yourGithubName.Rmd` file to `.gitignore` (to keep your solution local)
    -   "Git" pane \> right-click on the file \> "Ignore" \> "Save"
-   Commit and Push the following files
    -   the changed `.gitignore` file
    -   your solution output file `yourGithubName.nb.html` (knit it, if not existing yet)

#### Work on your solution and call for help

When you work on your solution, you should at least once a day

-   Commit and Push your changes to GitHub (remember [Step 5: Work, commit and push](https://edav.info/github.html#step-5-work-commit-and-push))

This ensures you will not loose your work (backup) and store the stuff where it belong.

Furthermore, it opens up a new way to get help!
In case you **get stuck somewhere**, it is a good idea to

-   **Commit and Push to GitHub**
-   **Call for help** (*and tell us the branch, file and problem*)
    -   either by [raising an Issue](https://github.com/Dr-Eberle-Zentrum/Advanced-data-processing-with-R/issues), describing your problem (*preferred solution*)
    -   or writing an Email to us
    -   or rushing our office (hope we are there)
    -   or ...

#### Create your pull request

At some point you will be satisfied with your project solution and all changes are **committed and pushed to GitHub**.

Now it is time to [open a pull request](https://github.com/Dr-Eberle-Zentrum/Advanced-data-processing-with-R/pulls).

-   create a new pull request of *your branch* (select from dropdown) into *main* branch
-   post a (Markdown) **link in the pull request** that allows to see your HTML page in the browser:
    -   this can be done via <https://htmlpreview.github.io/>
    -   just use `https://htmlpreview.github.io/?MYHTMLLINK`
    -   here `MYHTMLLINK` corresponds to the URL of the HTML file when you click it in the GitHub page
    -   e.g. `https://github.com/Dr-Eberle-Zentrum/Advanced-data-processing-with-R/blob/main/Projects/martin-raden/project-description.html`
-   check the link (here an [example link](https://htmlpreview.github.io/?https://github.com/Dr-Eberle-Zentrum/Advanced-data-processing-with-R/blob/main/Projects/martin-raden/project-description.html))
-   **invite** the project owner as a **reviewer**
    -   suggest him/her as reviewer (upper right in GitHub Pull Request interface)
    -   send him/her a message via a comment "@USERNAME"

#### Goal

At the end of Phase 1 you will

-   know about branches in git and how to use them in RStudio
-   have worked on a data wrangling and visualization project (in your own independent git branch)
-   have created a pull request on GitHub to incorporate your suggested project solution

### Phase 2 - Reviewing and finalizing {#phase-2---reviewing-and-finalizing}

<img src="https://img.icons8.com/external-parzival-1997-outline-color-parzival-1997/344/external-training-human-resource-management-parzival-1997-outline-color-parzival-1997.png" width="100px"/>

Now it is time for the *project owner* to **check** your solution and for *both of you* to **discuss** possible changes, extensions, ... This should, as before, be done on GitHub, but now **directly within the pull request**!
All comments, answers, changes etc. will be listed there.
Even **if you are meeting in person**, please **note down** the main points and goals *within the pull request* (together).

The **project owner** should

-   check the solution using the link provided in the pull request
-   compare the solution with your own project description
-   provide **constructive feedback** within the pull request
    -   positive writing
    -   suggest changes, extensions, ...
    -   you can even (in discussion and agreement) change the goal of this solution! Your are not fixed to the initial project plan from this point on!
    -   provide hints/ideas how to tackle the project (if known to you or needed)
    -   ...

The **solution author** should

-   be open minded to suggestions and criticism
-   at the end **formulate a plan of changes**, i.e.
    -   what will you change
    -   try to implement
    -   ...
-   your can use [GitHub Markdown checkboxes](https://www.w3schools.io/file/markdown-checkbox-github/) to later keep track what you have done and what is still open
-   best put your plan *in the first post of the pull request* by editing it. That way it is found and updated most easily!

You can already **work on the changes while you are discussing**!
Any change you commit to your branch is automatically visible in the pull request (and this HTML visualizing link you provided).

Thus, you can directly discuss if you meet the ideas of the project owner or suggest alternative ideas.

*You will get a loooot of GitHub emails this week!* :grin:


#### Goal

At the end of Phase 2 you will

-   have experienced the pull request workflow from both sides
-   have integrated an interactive reviewing cycle in your project solution
-   be ready for the next project! :grin:
