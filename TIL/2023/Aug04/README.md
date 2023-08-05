# Overview

GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your build, test, and deployment pipeline. You can create workflows that build and test every pull request to your repository, or deploy merged pull requests to production.

If you really want to get to know it, go to the vendor's [site](https://docs.github.com/actions) to get all the information!

# High Level Architecture

![GHA-high-level.png](GHA-high-level.png)

# The components of GitHub Actions

| Component Name | Description | Example |
| --- | --- | -- |
| Workflow/s | A workflow is a configurable automated process that will run one or more jobs. Workflows are defined by a YAML file checked in to your repository and will run when triggered by an event in your repository, or they can be triggered manually, or at a defined schedule.

Workflows are defined in the .github/workflows directory in the repository. | 
