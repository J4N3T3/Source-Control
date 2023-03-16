# Source-Control

## What's Git?
Git is a distributed version control system that tracks changes in any set of computer files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems).

## What's Source Control
Source control is the practice of tracking and managing changes to software code. Source control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, source control systems help software teams work faster and smarter. They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.

## Branches
Branching means you diverge from the main line of development and continue to do work without messing with that main line. There are multiple ways to work with these branch logic, such as the following.

## Feature branch workflow
The core idea behind the Feature Branch Workflow is that all feature development should take place in a dedicated branch instead of the main branch. This encapsulation makes it easy for multiple developers to work on a particular feature without disturbing the main codebase. It also means the main branch will never contain broken code, which is a huge advantage for continuous integration environments.

## Pull request
It has nothing to do with branches, only the fact that it uses the same methodology, because this is just asking the creator of an external repository (pulling the request) to copy its repository and make it your own. When this request is accepted it turns into a fork, and your repository gets forked to the original one. You can either make some changes and update the original repository with your version or just modify your repository and go your own way.

## Codespaces
A codespace is a development environment that's hosted in the cloud. You can customize your project for GitHub Codespaces by committing configuration files to your repository (often known as Configuration-as-Code), which creates a repeatable codespace configuration for all users of your project. Basically it's the web browser version of Visual Studio Code, you can edit code and commit changes without having to download an external software.

