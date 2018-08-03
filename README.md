
# BX GitFlow

BX GitFlow is the model of GitFlow that we use at Builbox. As part of our team you should understand and internalize such concepts if you want to survive.
On this model, the repository has two main branches.

## Master
  This is a highly stable branch that is always production-ready and contains the last release version of source code in production.

## Development
  This is the main branch of development, and serves as a branch for integrating different features for an upcoming release.

  ![Developer and Master branch](https://github.com/Buildbox-ItSolutions/BX-GitFlow/raw/master/dev%26master.PNG)

Apart from these features there are 4 other kind of branches.

## Feature
  This derives from the development branch and is used to develop features.

    ![Developer and Master branch](https://github.com/Buildbox-ItSolutions/BX-GitFlow/raw/master/featureBranches.png)


## Hotfix
  This derives from the master branch and is used to fix a bug in the production branch that was identified after a release.

## Bugfix
  This derives from the release branch and is used to fix bugs specific to tests.
