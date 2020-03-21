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
### General contribution guidelines
* All contributions should be associated with a GitHub Issue.  If a GitHub Issue does not exist for the work that you would like to contribute, please file one and indicate that you will be working on it.  It gives visibility to everyone that this work is happening and provides an opportunity for discussion and collaboration.
* It's recommended to begin a dialogue with the ACTIVE/\<project\> maintainer(s) before starting work on a big new feature, to increase likelihood of integration & reduce re-work that would be required to get it merged.
* Contributions should be submitted by GitHub Pull Request.  
  * This is a useful step-by-step guide for making a GitHub pull request: https://tkuhrt.github.io/git-workflow/
* For anything that involves code, it must have a test suite to ensure nothing breaks and passing tests and instructions for others to run the test suite.  
* New contributions to an ACTIVE/\<project\> must also pass the ACTIVE/\<project\>'s test suite
  * If implementing new features not covered by the test suite, new tests should also be submitted to the test suite & everything should pass.  

### Guidelines for contributing a new ACTIVE/\<project\>
Please reach out to the Learning Materials Development Working Group (LMDWG) to discuss if contributing your project to this repository makes sense.  Good ways to get in touch are via the mailing list or by attending a LMDWG call.  Details of how to join can be found on the [LMDWG wiki page](https://wiki.hyperledger.org/display/LMDWG)

Once we have decided that this is the right place for the project:

1. Read this step-by-step guide for making a GitHub pull request: https://tkuhrt.github.io/git-workflow/
2. Choose a good name for your project directory. It should be descriptive, yet succinct. From here onward, we will refer to it as \<project\>.
3. Fork this repository
4. Under the ACTIVE/ directory, create the directory \<project\>.
5. Under your ACTIVE/\<project>\/ directory, create a README.md file that explains what \<project\> is, how to use it, and its intended destination.
6. Under your ACTIVE/\<project\>/ directory, create a CONTRIBUTING.md file that gives requirements for how to contribute to your \<project\> if there are any requirements that are more specific than the top-level CONTRIBUTING.md of this repository.  If there aren't more specific requirements, then just write in the file to refer to the top level one.  This prevents ambiguity.
7. Under your ACTIVE/\<project\>/ directory, create a MAINTAINERS.md file that lists who is responsible for \<project\>.  At a minimum, you should list your GitHub ID & if you like, you can put your name.  If you have co-maintainers, then list them too.  If your e-mail address isn't in your GitHub profile, then give some kind of contact information so people who want to contribute or ask questions can reach you, keeping in mind that this is out on the internet for the world to see.
8. Under your ACTIVE/\<project\>/ directory, create a TESTING.md that explains how to run the tests for the project.  If your project has working code, you should include tests to ensure this code keeps working when others contribute to your project.
9. Under your ACTIVE/\<project\>/ directory, put the files for your project.
10. Once you have done the above steps and confirmed that your TESTING.md instructions work in the current directory structure, create a Pull Request using the steps from https://tkuhrt.github.io/git-workflow/.
