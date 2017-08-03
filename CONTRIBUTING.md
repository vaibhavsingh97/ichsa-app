# Contributing

This is an Open Source project and we would be happy to see contributors who report bugs and file feature requests submitting pull requests as well. When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a [code of conduct](https://github.com/OpenSourceHelpCommunity/OpenSourceHelpCommunity.github.io/blob/develop/CODE_OF_CONDUCT.md), please follow it in all your interactions with the project.

## Getting Started

- Make sure you have a [GitHub account](https://github.com/signup/free)
- Submit a ticket for your issue, assuming one does not already exist.

  - Clearly describe the issue including steps to reproduce when it's a bug.
  - Make sure you fill all the points mentioned in the issue template.

- Fork the repository on GitHub

## How to contribute

The preferred workflow for contributing to ichsa-app is to fork the main repository on GitHub, clone, and develop on a branch. Steps:

1. Fork the [project repository](https://github.com/vaibhavsingh97/ichsa-app.git) by clicking on the 'Fork' button near the top right of the page. This creates a copy of the code under your GitHub user account. For more details on how to fork a repository see [this guide](https://help.github.com/articles/fork-a-repo/).

2. Clone your fork of the ichsa-app repo from your GitHub account to your local disk:

  ```bash
  $ git clone git@github.com:YourLogin/ichsa-app.git
  $ cd ichsa-app
  ```

3. Create a `feature` branch to hold your development changes:

  ```bash
  $ git checkout -b my-feature
  ```

  Always use a `feature` branch. It's good practice to never work on the `master` branch!

4. Develop the feature on your feature branch. Add changed files using `git add` and then `git commit` files:

  ```bash
  $ git add modified_files
  $ git commit
  ```

  to record your changes in Git, then push the changes to your GitHub account with:

  ```bash
  $ git push -u origin my-feature
  ```

5. Follow [these instructions](https://help.github.com/articles/creating-a-pull-request-from-a-fork) to create a pull request from your fork. This will send an email to the committers.

(If any of the above seems like magic to you, please look up the [Git documentation](https://git-scm.com/documentation) on the web, or ask a friend or another contributor for help.)

At this point you're waiting on us. We like to at least comment on pull requests within three business days (and, typically, one business day). We may suggest some changes or improvements or alternatives.

## New contributor tips

A great way to start contributing to ichsa-app is to pick an item from the list of [Easy issues](https://github.com/vaibhavsingh97/ichsa-app/issues?labels=Easy) in the issue tracker. Resolving these issues allow you to start contributing to the project without much prior knowledge. Your assistance in this area will be greatly appreciated by the more experienced developers as it helps free up their time to concentrate on other issues.

Some things that will increase the chance that your pull request is accepted:

<!-- - Write tests. -->

 - Follow our [style guide][style].
 - Write a [good commit message][commit].

## Contacting us

The best way to contact us is to [post a message in our issue tracker](https://github.com/vaibhavsingh97/ichsa-app/issues/new). Our issue tracker doubles as a discussion forum. You can use it for things like asking questions about the project or requesting technical help.

<!-- Alternatively (less preferred), you can email us at **email@example.com**. -->

[commit]: http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
[style]: https://github.com/thoughtbot/guides/tree/master/style
