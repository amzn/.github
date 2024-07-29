# Contributing Guidelines

Thank you for your interest in contributing to our project. Whether it's a bug report, new feature, correction, or additional
documentation, we greatly value feedback and contributions from our community.

Please read through this document before submitting any issues or pull requests to ensure we have all the necessary
information to effectively respond to your bug report or contribution.

## Security issue notifications

If you discover a potential security issue in this project we ask that you notify AWS/Amazon Security via our [vulnerability reporting page](http://aws.amazon.com/security/vulnerability-reporting/). Please do **not** create a public GitHub issue.

## Reporting Bugs/Feature Requests

We welcome you to use the GitHub issue tracker to report bugs or suggest features.

When filing an issue, please check existing open, or recently closed, issues to make sure somebody else hasn't already
reported the issue. Please try to include as much information as you can. Details like these are incredibly useful:

- A reproducible test case or series of steps
- The version of our code being used
- Any modifications you've made relevant to the bug
- Anything unusual about your environment or deployment

## Contributing via Pull Requests

Contributions via pull requests are much appreciated. Before sending us a pull request, please ensure that:

1. You are working against the latest source on the _main_ branch.
2. You check existing open, and recently merged, pull requests to make sure someone else hasn't addressed the problem already.
3. You open an issue to discuss any significant work - we would hate for your time to be wasted.

#### Making major changes (e.g. new features)

1. Fork the public AmazonAppDev repo to your GitHub account.
2. Clone your fork locally:

```
git clone https://github.com/your-username/repo-name.git
```

3. Create a new branch for your changes e.g. left-hand-navigation-drawer

```
git checkout -b your-feature-branch
```

4. Make changes, test, commit, and push to your fork:

```
git add .
git commit -m "Clear commit message"
git push origin your-feature-branch
```

4. Create a pull request from your branch to the original repo using the feature template.
5. After approval, the original repo maintainer shall merge your changes.
6. Update your fork's main branch

#### Making bug fixes

1. Create an issue in the repo describing the bug
2. Create a fix branch locally from the main repo:

```
git checkout -b fix/issue-number-description
```

3. Make changes and once finished commit to your branch

```
git push origin fix/issue-number-description
```

4. Create a pull request linking to the issue use the fix template.
5. After approval, squash merge the fix
6. Delete the fix branch

GitHub provides additional document on [forking a repository](https://help.github.com/articles/fork-a-repo/) and
[creating a pull request](https://help.github.com/articles/creating-a-pull-request/).

## Code of Conduct

This project has adopted the [Amazon Open Source Code of Conduct](https://aws.github.io/code-of-conduct).
For more information see the [Code of Conduct FAQ](https://aws.github.io/code-of-conduct-faq) or contact
opensource-codeofconduct@amazon.com with any additional questions or comments.

## Licensing

See the LICENSE file for our project's licensing. We will ask you to confirm the licensing of your contribution.
