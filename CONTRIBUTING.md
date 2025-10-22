# Contribution Guide for Craftech Projects

## Index

1. [Introduction](#introduction)
2. [How to Contribute: Two Main Paths](#how-to-contribute-two-main-paths)
    1. [Proposing Changes, Ideas, and Experiments (Discussions)](#a-proposing-changes-ideas-and-experiments-discussions)
        1. [When to Use Discussions](#when-to-use-discussions)
        2. [Discussion Categories](#discussion-categories)
            1. [Ideas](#ideas)
            2. [RFC's (Request for Comments)](#rfcs-request-for-comments)
            3. [Experiments](#experiments)
            4. [Show and tell](#show-and-tell)
    2. [Reporting Bugs and Specific Tasks (Issues)](#b-reporting-bugs-and-specific-tasks-issues)
        1. [Rules for Contributing and Avoiding Duplication](#rules-for-contributing-and-avoiding-duplication)
3. [Code Development Process](#code-development-process)
    1. [Solution Development](#1-solution-development)
        1. [Branching Model (LibFlow)](#branching-model-libflow)
        2. [Conventional Commits](#commit-standard-conventional-commits)
        3. [Documentation](#documentation)
    2. [Pull Requests (PR)](#2-pull-requests-pr)
    3. [Release and Communication](#3-release-and-communication)

# Introduction

First and foremost, thank you for your time and dedication to contributing! At Craftech, we value the effort of every team member in improving our processes and tools.

This document outlines our standard process, designed to ensure quality, organization, and efficiency, whether you're proposing a new idea or implementing a change in the code.

# How to Contribute: Two Main Paths

There are two main ways to contribute, depending on the nature of your input: through Discussions for proposals and ideas, or through Issues for specific tasks and bugs.

## A. Proposing Changes, Ideas, and Experiments (Discussions)

For proposals that require debate, new ideas, or significant changes to a project, we use GitHub Discussions. This is the place for more extensive and organized conversations before a concrete task is created.

### When to Use Discussions

Use "discussions" to present ideas, feature requests, or more complex and detailed RFCs. Discussions allow for a broader and more organized conversation around the proposal, which facilitates debate and collaboration among community members.

### Discussion Categories

When creating a new discussion, select the appropriate category:

#### Ideas

An [IDEA](.github/DISCUSSION_TEMPLATE/idea.md) is a more informal and general proposal that can encompass a wide range of concepts or suggestions.
Typically, an idea is the starting point for a discussion or a new feature request.
It can be presented more openly, without requiring a specific structure, and its objective is simply to share a possibility or a notion.
The idea may not be fully developed in terms of implementation or technical details.

#### RFC's (Request for Comments)

An [RFC](.github/DISCUSSION_TEMPLATE/rfc.md) is a more formal and structured process for proposing significant changes, key decisions, or new features to a project.
It typically follows a specific format and may require extensive documentation, analysis, and justification.
RFCs often involve a more detailed evaluation of technical, design, performance, security, and other implications.
They are commonly used in larger projects or communities where important decisions need to be discussed and approved by a group of contributors.
RFCs typically have a review and discussion period before a final decision is made.

#### Experiments

This category is for publishing and documenting things that are being experimented with within the Squads. It's a space to share learnings from tests and prototypes that are not yet official features.

#### Show and tell

A space to showcase something you've built. It's ideal for sharing demos, project results, or any finished work that might be of interest to the community.

## B. Reporting Bugs and Specific Tasks (Issues)

An issue is a way to track and manage problems, bugs, tasks, or any other type of request in a project.
Unlike an idea or an RFC, an issue focuses on specific problems that need to be addressed or specific tasks that need to be completed.
Issues can be used to report bugs, request support, propose improvements, and much more.
They can be more concrete and detailed than an idea, as they are expected to provide specific information about the problem or request.
### Rules for Contributing and Avoiding Duplication

* Search first: Before creating an Issue or Discussion, be sure to search the repository to avoid duplicates.
* Use templates: Please use the provided templates to create new "issues." This helps us maintain a consistent structure.
* Stay focused: When adding comments or creating new entries, make sure to stay focused on the specific problem or request.
* Respect and courtesy: We foster a friendly and constructive environment. Respect the opinions and comments of others.

# Code Development Process

Once an Issue has been approved and is ready to be implemented, the code development cycle begins.

## 1. Solution Development

### Branching Model (LibFlow)

The main branch is main and it is protected. For each new contribution, a branch must be created from main following this naming convention:
* feat/: For new features.
* enhancement/: For backward-compatible improvements to existing features.
* fix/ or hotfix/: For bug fixes.
* doc/: Exclusively for documentation changes.
* test/: For adding or updating tests and examples.

### Commit Standard (Conventional Commits)

The use of Conventional Commits is mandatory. This allows us to automate versioning and changelog generation.
Examples:
* New features: feat: add support for custom provider
* Bug fixes: fix: correct typo in module outputs

Best Practices:
* Keep commits small and focused on a single logical change.
* Maintain a clean history by using squash commits when merging Pull Requests into main.

### Documentation

* Quality code is always accompanied by good documentation.
* Update the README.md when you introduce a significant change.
* Include clear comments in the code, especially for complex logic.

Provide functional implementation examples.

## 2. Pull Requests (PR)

* Once development is complete, open a Pull Request (PR) against the main branch.
* Start in draft mode: Keep the PR as a draft until the initial development is complete.
* Title and Description: The title should follow the Conventional Commits format. The description is crucial and must contain the information for the release, following the PR template.
* Link the Issue: Make sure to link the Issue that the PR resolves (e.g., Closes #123).

Review Process:
* Automated CI checks must pass successfully.
* Approval from at least one CODEOWNER is required.

## 3. Release and Communication

Once a PR is approved and merged into main, the release process begins.
* Semantic Versioning (SemVer): Our releases follow SemVer (MAJOR.MINOR.PATCH).
* CHANGELOG: It is mandatory to record changes in the CHANGELOG.md file.
* Communication: Releases with a significant impact are communicated to the team through designated Slack channels.

Thanks again for your contribution!
