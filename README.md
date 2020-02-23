# Purpose
Hosting content for the Hyperledger Learning Materials Development Working Group (LMDWG) that makes sense to have in GitHub (i.e. where source control makes sense, as opposed to using the Hyperledger LMDWG wiki) that the LMDWG members want to share for collaboration.  Ideally, this should just be a "development" area where it is being prepped for some greater purpose in the published Hyperledger documentation space.  This should not be the final destination where a contribution comes to grow old and die, since we're a development working group.

# Structure to be followed
* LICENSE is the license governing the contents of the repo.  
* README.md shall explain the purpose of the repo
* CONTRIBUTING.md shall explain how to contribute a \<project\> and how to file issues. It would point to ACTIVE/\<project\>/CONTRIBUTING.md files for specifics on how to contribute to each \<project\>
* MAINTAINERS.md shall list the maintainers of the learning-materials-dev repository
* ARCHIVE/<old-project> shall hold projects that are no longer being maintained.  
* ACTIVE/\<project\> shall hold active projects
* ACTIVE/\<project\>/README.md shall explain what \<project\> is, how to use it, and its intended destination
* ACTIVE/\<project\>/CONTRIBUTING.md shall give requirements for how to contribute to each \<project\>  
* ACTIVE/\<project\>/MAINTAINERS.md shall list who is responsible for \<project\>
* ACTIVE/\<project\>/TESTING.md shall explain how to run the tests for the project

# Rules
* Anyone who contributes a new ACTIVE/\<project\> must be willing to be the maintainer of that ACTIVE/\<project\>.  This means answering questions, responding to issues, keeping things up-to-date, and driving the contribution to its destination in the published Hyperledger documentation space.  They may have co-maintainers.
* Any ACTIVE/\<project\> that has had no updates for a year will be moved to ARCHIVE/ and all the Issues & PRs for it will be closed as obsolete.  This can happen sooner at the request of the \<project\> maintainer.
