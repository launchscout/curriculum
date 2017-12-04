# Topics

* What is git
  * A collection of commands and subtools
  * Explain commits and hashes
  * What is a diff?
* Typical git flow
  * Branch for working code
  * Git log
  * Rebase
  * Bisect
  * Cherry-pick

* Git config
* Hooks
* Gitlab
  * Review UI
  * Merge requests (code reviews)
  * CI Runners


# Videos to watch before class

* [What is version control](https://git-scm.com/video/what-is-version-control)
* [What is git](https://git-scm.com/video/what-is-git)

# Additional Resources

* [Git Flight Rules](https://github.com/k88hudson/git-flight-rules)

# Hands on class work

The goal of the hands on class work is to pair up and build a node or java script to spit out a changelog markdown file based on commit messages.

## User stories

* As a developer, I want to run a script to generate a markdown file based on the git log so that I can see what has happened recently.
  * Output each git commit entry message as a bullet point item
  * Use repo name as h1 in file
* As a developer, I want to parse the git log for special characters to control the output of the changelog so that we can be more exacting in the output.
  * Handle [skip changelog]
  * Handle # Release X.Y.Z
