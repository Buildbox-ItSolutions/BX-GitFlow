
# BX GitFlow

BX GitFlow is the model of GitFlow that we use at Builbox. As part of our team you should understand and internalize such concepts if you want to survive.
On this model, the repository has two main branches.

## Master
  This is a highly stable branch that is always production-ready and contains the last release version of source code in production.

## Development
  This is the main branch of development, and serves as a branch for integrating different features for an upcoming release.

  ![alt text](dev&master.png)
## Release
  This contains the release version of source code, ready for tests. This branch must be merged on master after the tests and possible bug fixes.

Apart from these features there are 4 other kind of branches.

## Feature
  This derives from the development branch and is used to develop features.

## Hotfix
  This derives from the master branch and is used to fix a bug in the production branch that was identified after a release. Every fix made at this branch, must be replied at development branch.
  
## Bugfix
  This derives from the release branch and is used to fix bugs specific to tests.
  

