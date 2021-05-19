# Calculator-poc-github-actions

Our goal is to automate building, testing and deploying an iOS project without the need for external tools besides Github Actions. Therefore we will not use Travis, Jenkins, Circle Ci, Fastlane, App Center or any other CI/CD tool.

A workflow is a configurable automated process made up of one or more jobs. You must create a YAML file to define your workflow configuration.

A workflow can be triggered from a pull request or push to a specific/any branch. It can also be triggered with tags, scheduled or in other ways. A workflow must have at least one job. A job contains a set of steps that perform individual tasks and steps that can run commands or use an action. These so-called actions can be shared and used by the GitHub community.

Medium [story](https://engineering.talkdesk.com/test-and-deploy-an-ios-app-with-github-actions-44de9a7dcef6) that I follow.
