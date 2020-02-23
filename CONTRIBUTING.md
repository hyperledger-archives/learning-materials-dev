# How to Contribute

## Project-specific guidelines
Please refer to the ACTIVE/\<project\>/CONTRIBUTING.md file for project-specific guidelines regarding contributions.  Below are some general guidelines to follow.

## Issues
* Issues against projects in ARCHIVE/ will be closed without resolution. ARCHIVE projects are no longer being maintained.
* Issues against projects in ACTIVE/ should be reported using the GitHub issues mechanism.  
  * Check if the issue has already been reported, using the GitHub issue search
* For bug reports
  * Check if it still reproduces on the master or latest development branch of the repo
  * Once you are sure this is a new bug that hasn't been fixed:
    * Give it a clear title that describes the problem.  Include which ACTIVE/\<project\> the issue is referring to.
    * Provide details about the environment in which the issue was encountered
    * Provide a testcase or detailed steps for reproducing
    * Provide any additional details you think would be helpful for debugging/resolving the issue
* We request for the maintainers to respond to issues within a week.
  * Not that they would necessarily be able to resolve the issue within a week, but at minimum some sort of acknowledgement of receipt, perhaps beginning dialogue with the issue reporter or giving some timeframe to look into a bug.

## Contributions
* All contributions should be associated with a GitHub Issue.  If a GitHub Issue does not exist for the work that you would like to contribute, please file one and indicate that you will be working on it.  It gives visibility to everyone that this work is happening and provides an opportunity for discussion and collaboration.
* It's recommended to begin a dialogue with the ACTIVE/\<project\> maintainer(s) before starting work on a big new feature, to increase likelihood of integration & reduce re-work that would be required to get it merged.
* Contributions should be submitted by GitHub Pull Request.  
  * This is a useful step-by-step guide for making a GitHub pull request: https://tkuhrt.github.io/git-workflow/
* For anything that involves code, it must have a test suite to ensure nothing breaks and passing tests and instructions for others to run the test suite.  
* New contributions to and ACTIVE/\<project\> must also pass the ACTIVE/\<project\>'s test suite
  * If implementing new features not covered by the test suite, new tests should also be submitted to the test suite & everything should pass.  
