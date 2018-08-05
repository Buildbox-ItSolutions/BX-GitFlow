
# BX GitFlow

BX GitFlow is the model of GitFlow that we use at Builbox. As part of our team you should understand and internalize such concepts if you want to survive.
On this model, the repository has two main branches.

### Master
  This is a highly stable branch that is always production-ready and contains the last release version of source code in production.

### Development
  This is the main branch of development, and serves as a branch for integrating different features for an upcoming release.

  ![Developer and Master branch](https://raw.githubusercontent.com/Buildbox-ItSolutions/BX-GitFlow/master/devAndMaster.png)

Apart from these there are 4 other kind of branches.

### Feature
These branches derives from the development branch  and are used to implement new features.

![Feature Branch](https://raw.githubusercontent.com/Buildbox-ItSolutions/BX-GitFlow/master/featureBranches.png)

To create a new feature branch, we use the corresponding Jira issue. Look for development section on the details of the issue and click on **create branch**.

![Feature Branch](https://raw.githubusercontent.com/Buildbox-ItSolutions/BX-GitFlow/master/createBranch.png)

After finishing a feature, you should create a pull request into development. The pull request must be reviewed by someone from your team. Pull requests can be made through some version control softwares, like GitKraken. On Bitbucket site, you just have to go to the pull request section.

Refer to these for more help.
* **Sourcetree** - [Shortcut to pull request on Sourcetree](https://community.atlassian.com/t5/Sourcetree-questions/How-do-I-configure-a-pull-request-in-source-tree/qaq-p/1860)
* **GitKraken** - [Pull Requests on GitKraken](https://support.gitkraken.com/working-with-repositories/pull-requests)

After the pull request is approved, someone on your team should integrate it into development. It will be usually a pre-defined person, so nothing to worry here.

### Release
  When enough features have been developed. A release branch will be created. This branch is the one where tests will be made before going into production.
  ![Release Branch](https://raw.githubusercontent.com/Buildbox-ItSolutions/BX-GitFlow/master/release1.png)

  The bugs that the QA team identify for this release must be fixed here  and integrated back into the development branch eventually.

### Bugfix
  This derives from the release branch and is used to fix bugs specific to tests.

### Hotfix
  This derives from the master branch and is used to fix a bug in the production that was identified after a release.

  ![Hotfix Branch](https://raw.githubusercontent.com/Buildbox-ItSolutions/BX-GitFlow/master/hotfix1.png)

# References
  If you still have some doubts about the process you can ask your coworkers for help, or checkout these articles that were used as reference.

  [GitFlow Workflow - Bitbucket](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
