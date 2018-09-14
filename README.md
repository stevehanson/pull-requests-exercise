
# Intro to git

This repo is a companion to my Intro to Git talk from the 2018 Women Who Code
Diversity Hackathon in Austin, TX.

The slides for this talk are available [here](https://files.shanson.co/git-2018.pdf).

### Attendees

Add your name and GitHub profile to the list below:

* Stephen Hanson: [https://github.com/stevehanson](github.com/stevehanson)
* My name: [https://github.com/my-name](github.com/my-name)

### Follow these steps to add your name:

* Fork this repository (this allows you to make changes and push to your fork)
  * Clone (download) your fork
  * Create a `branch` off `master` and switch to it
  * Open this file in your text editor and add your name and GitHub account to the above list
  * Commit your changes
  * Push your changes
  * Open a pull request

#### Sync with upstream

  To minimize the likelihood of merge conflicts, ensure that your fork is up to
  date with the destination repo of your pull request. Do this _before_ creating a
  branch off master:

  * `git remote add upstream https://github.com/stevehanson/pull-requests-exercise.git`
  * `git fetch upstream`
  * `git checkout master`
  * `git rebase upstream/master`

  For additional instructions, visit [GitHub Help](https://help.github.com/categories/collaborating-on-projects-using-pull-requests/).

