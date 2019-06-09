# The Basics

[[toc]]

## Creating Projects

Vapor projects are created via the Vapor UI or the `vapor init` CLI command. This command should be executed within the root directory of the Laravel project you wish to deploy. The `init` command will prompt you to select the AWS account that the project should be associated with, as well as the AWS region that it should be deployed to.

The `init` command will generate a `vapor.yml` file within the root of your project. This is the primary configuration file for your Vapor project and contains things like build steps, deployment hooks, linked databases / caches, and other project settings. Each time you deploy, Vapor reads this configuration file and deploys your project appropriately.

## Project Settings

### GitHub Repository

Within Vapor's "Project Settings" screen, you may provide the GitHub repository information for a project. Providing this information simply allows Vapor to provide links to GitHub for each deployment's commit hash. You are not required to provide repository information for Vapor to function.

## Deleting Projects

You may delete a project using the Vapor UI or the `project:delete` CLI command. The `project:delete` command should be run from the root directory of your project.