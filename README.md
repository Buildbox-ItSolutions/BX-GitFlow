
# BX GitFlow

BX GitFlow is the model of GitFlow that we use at Builbox. As part of our team you should understand and internalize such concepts if you want to survive.
On this model, the repository has two main branches.

## Master
  This is a highly stable branch that is always production-ready and contains the last release version of source code in production.

## Development
  This is the main branch of development, and serves as a branch for integrating different features for an upcoming release.

  ![Developer and Master branch](https://raw.githubusercontent.com/Buildbox-ItSolutions/BX-GitFlow/master/devAndMaster.png)

Apart from these features there are 4 other kind of branches.

## Feature
These branches derives from the development branch  and is used to implement new features.

![Feature Branch](https://raw.githubusercontent.com/Buildbox-ItSolutions/BX-GitFlow/master/featureBranches.png)

To create a new feature branch, we use the corresponding Jira issue. Look for development section on the details of the issue and click on **create branch**.

![Feature Branch](https://raw.githubusercontent.com/Buildbox-ItSolutions/BX-GitFlow/master/createBranch.png)

## Hotfix
  This derives from the master branch and is used to fix a bug in the production branch that was identified after a release.

## Bugfix
  This derives from the release branch and is used to fix bugs specific to tests.

# References

  If you still have some doubts about the process you can ask your coworkers for help, or checkout these articles that were used as reference.

  [GitFlow Workflow - Bitbucket](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
