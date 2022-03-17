# DevSecOps POC
## GITHUB ACTIONS CRUD PROJECT WITH .Net Core

## An introduction to GitHub Actions
Developers that use GitHub for managing their git repositories have a powerful continuous integration (CI) and continuous delivery (CD) feature with the help of GitHub Actions. A common developer scenario is when developers propose changes to the default branch (typically main) of a GitHub repository. These changes, while often scrutinized by reviewers, can have automated checks to ensure that the code compiles and tests pass.

GitHub Actions allow you to build, test, and deploy your code right from your source code repository on https://github.com. GitHub Actions are consumed by GitHub workflows. A GitHub workflow is a YAML (either *.yml or *.yaml) file within your GitHub repository. These workflow files reside in the .github/workflows/ directory from the root of the repository. A workflow references one or more GitHub Action(s) together as a series of instructions, where each instruction executes a specific task.

## The GitHub Action terminology
To avoid mistakenly using some of these terms inaccurately, let’s define them:

GitHub Actions: GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your build, test, and deployment pipeline.
workflow: A workflow is a configurable automated process that will run one or more jobs.
event: An event is a specific activity in a repository that triggers a workflow run.
job: A job is a set of steps in a workflow that execute on the same runner.
action: An action is a custom application for the GitHub Actions platform that performs a complex but frequently repeated task.
runner: A runner is a server that runs your workflows when they’re triggered.
For more information, see GitHub Docs: Understanding GitHub Actions
