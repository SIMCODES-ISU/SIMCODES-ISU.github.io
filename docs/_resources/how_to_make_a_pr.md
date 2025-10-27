---
title: How to Make Pull Requests (PRs)
layout: page
permalink: /resources/how_to_make_a_pr/
image:
  thumbnail: /resources/images/presentations.png
  path: /resources/images/presentations.png
---

This page is intended for people who are not already familiar with git and
GitHub. If you are already familiar with git/GitHub feel free to make a pull
request using your usual workflow. This tutorial will walk you through
creating PRs from the GitHub website directly. This is highly inefficient for
most purposes. However, for the purposes of adding/updating a website page it
can be convenient. 

## What is a pull request?

The short answer is a PR is a suggested change to a GitHub repository.
Maintainers of GitHub repositories usually want to vet changes before deploying 
them in order to avoid accidentally breaking the code base. The SIMCODES
website is maintained as a GitHub repository and thus we must use PRs to change
it.

## Tutorial: Adding a New Student Profile

This tutorial will walk you through the process of creating a new student 
profile. The tutorial was written for the 2026 cohort and thus uses the 2026 
year throughout. As you work through the tutorial please use the actual year of 
your cohort and not 2026 (unless you are part of the 2026 cohort or a time 
traveler). Also please let us know if your experience differs significantly
from what is shown here as that may mean we need to update the tutorial.

### Step 1. Navigate to the SIMCODES-ISU.github.io repository

The source code for the SIMCODES website lives 
[here](https://github.com/SIMCODES-ISU/SIMCODES-ISU.github.io). The actual 
website should look something like:

![SIMCODES Website](/resources/images/pr_tutorial/simcodes_website.png)

The view in front of you is a file system similar to what you see when
you use Finder or MacOS or File Explorer on Windows. Like on your local
system, files are organized into folders. The source code for the website
lives in the `docs` directory (I don't know why it's called `docs` as opposed
to `source` or something more sane...). If you click on `docs` it should take
you to a new file system view that looks something like:

![SIMCODES Website](/resources/images/pr_tutorial/simcodes_website2.png)

From this page you'll need to click on the directory `_students-2026`.