# Contributing Guidelines for Kyverno

Thanks for your interest in contributing! We welcome all contributions, suggestions, and feedback, so please do not hesitate to reach out!

These guidelines apply to [Kyverno and all of its sub-projects](https://github.com/kyverno#projects).

Before you contribute, please take a moment to review and agree to abide by our community [Code of Conduct](./CODE_OF_CONDUCT.md).

## Engage with us

The Kyverno website has the most updated information on [how to engage with the Kyverno community](https://kyverno.io/community/) including its maintainers and contributors. 

Join our community meetings to learn more about Kyverno and engage with maintainers, other contributors, and end users.

## Ways you can contribute

### 1. Report issues

Issues to Kyverno help improve the project in multiple ways including the following:
- Identify potential bugs
- Request features
- Request documentation and samples

### 2. Fix or Improve Documentation

Good documentation is essential for the success of a project. Contributing to the documentation benefits others and enhances your knowledge and skills.

### 3. Code Changes

New contributors may easily view all [open issues labeled as "good first issue"](https://github.com/orgs/kyverno/projects/10) allowing you to get started with code changes in an approachable manner.

[Pull requests](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) (PRs) allow you to contribute back the changes you've made on your side enabling others in the community to benefit from your hard work. They are the main source by which all changes are made to this project and are a standard piece of GitHub operational flows.


## Developer Certificate of Origin (DCO) Sign off

For contributors to certify that they wrote or otherwise have the right to submit the code they are contributing to the project, we are requiring everyone to acknowledge this by signing their work which indicates you agree to the DCO found [here](https://developercertificate.org/).

To sign your work, just add a line like this at the end of your commit message:

```sh
Signed-off-by: Random J Developer <random@developer.example.org>
```

This can easily be done with the `-s` command line option to append this automatically to your commit message.

```sh
git commit -s -m 'This is my commit message'
```

## How to Create a PR

Head over to the project repository on GitHub and click the **"Fork"** button. With the forked copy, you can try new ideas and implement changes to the project.

1. **Clone the repository to your device:**

Get the link of your forked repository, paste it in your device terminal and clone it using the command.

```sh
git clone https://hostname/YOUR-USERNAME/YOUR-REPOSITORY
```

2. **Create a branch:**

Create a new brach and navigate to the branch using this command.

```sh
git checkout -b <new-branch>
```

Great, it's time to start hacking! You can now go ahead to make all the changes you want.

3. **Stage, Commit, and Push changes:**

Now that we have implemented the required changes, use the command below to stage the changes and commit them.

```sh
git add .
```

```sh
git commit -s -m "Commit message"
```

The `-s` signifies that you have signed off the commit.

Go ahead and push your changes to GitHub using this command.

```sh
git push
```
