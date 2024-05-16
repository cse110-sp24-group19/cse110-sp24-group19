---
parent: Decisions
date: 2024-05-12
title: Implementation of Branch Protection Rules
deciders: Allison, Brandon, Charlie, David, Ginger, Julie, Julio, Milana, Nikolas, Riana, Wenzhe
---

# Implementation of Branch Protection Rules

## Context and Problem Statement

In order to ensure the integrity and quality of our main branch, we need to implement branch protection rules. This will help prevent unauthorized changes and ensure that all code changes are properly reviewed and tested before being merged.

## Decision Drivers

* Ensuring code quality and integrity
* Preventing unauthorized changes
* Ensuring all changes are reviewed and approved
* Maintaining up-to-date branches before merging

## Considered Options

* Implement branch protection rules with strict settings
* Implement branch protection rules with moderate settings
* Do not implement branch protection rules

## Decision Outcome

Chosen option: "Implement branch protection rules with strict settings", because this option ensures the highest level of code quality and integrity by enforcing thorough review and testing processes.

## More Information

The chosen branch protection rules include:
- Requiring a pull request before merging
- Requiring one approval for pull requests targeting the main branch
- Requiring the "run-lint" status check to pass before merging
- Requiring branches to be up-to-date before merging
- Disallowing bypassing of the above settings by administrators or custom roles
