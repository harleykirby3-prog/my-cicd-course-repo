# My CI/CD Course Repository

## Repository Purpose

This repository is used for my CI/CD course labs. It provides a place to practice software development, version control, automated testing, security scanning, build artifacts, and software releases using GitHub Actions.

## Week 1: Branch Practice

This section introduces GitHub branches and version control. Branches allow developers to make changes separately from the main project before merging approved changes.

## Week 2: GitHub Actions

This week introduces a basic GitHub Actions workflow. GitHub Actions helps automate development tasks whenever changes are pushed or pull requests are submitted.

## CI/CD Workflows

This repository contains several workflows that help automate and improve the development process.

- **hello-ci.yml:** Introduces basic continuous integration using GitHub Actions.
- **python-tests.yml:** Runs automated Python tests to check that the calculator program works as expected.
- **security-scan.yml:** Performs security scanning to help identify potential issues in the project.
- **release.yml:** Supports the software release process by automating release-related tasks.

## Testing and Security

Automated testing helps identify errors before changes are merged into the main project. Security scanning adds another layer of protection by checking for potential vulnerabilities.

These processes help improve software quality, reliability, and security.

## Build Artifacts and Releases

Build artifacts are generated outputs that can be saved and accessed after a workflow runs. They provide a way to retain important files produced during the CI/CD process.

Releases help organize and distribute completed versions of the project. Together, artifacts and releases help make software easier to track and manage.

## How to Know the Pipeline Is Working

The GitHub Actions tab provides information about workflow runs and their results.

- A green checkmark indicates that a workflow completed successfully.
- A red X indicates that a workflow failed and may need troubleshooting.
- Individual workflow logs provide details about tests, security scans, and other automated tasks.

When the workflows run successfully, it indicates that the automated processes are functioning as expected.
