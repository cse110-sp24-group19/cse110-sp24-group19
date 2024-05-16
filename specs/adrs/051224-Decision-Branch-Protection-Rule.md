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

### Consequences

* Good, because it ensures that all code changes are reviewed and approved before being merged, improving overall code quality.
* Good, because it requires branches to be up-to-date before merging, reducing the risk of integration issues.
* Bad, because it may slow down the development process due to the additional steps required for merging changes.
* Bad, because it may require additional administrative effort to manage the branch protection rules.

## Validation

The implementation of the branch protection rules will be validated through regular code reviews and monitoring of the pull request process. We will also collect feedback from the development team to identify any issues or areas for improvement.

## Pros and Cons of the Options

### Implement branch protection rules with strict settings

* Good, because it ensures thorough review and testing of all changes.
* Good, because it prevents unauthorized changes to the main branch.
* Neutral, because it may require additional administrative effort.
* Bad, because it may slow down the development process.

### Implement branch protection rules with moderate settings

* Good, because it provides a balance between code quality and development speed.
* Good, because it still ensures some level of review and testing.
* Neutral, because it may require some administrative effort.
* Bad, because it may not be as effective in preventing issues as the strict settings.

### Do not implement branch protection rules

* Good, because it allows for faster development and merging of changes.
* Neutral, because it requires minimal administrative effort.
* Bad, because it increases the risk of unauthorized changes and integration issues.
* Bad, because it may compromise code quality and integrity.

## More Information

The chosen branch protection rules include:
- Requiring a pull request before merging
- Requiring one approval for pull requests targeting the main branch
- Requiring the "run-lint" status check to pass before merging
- Requiring branches to be up-to-date before merging
- Disallowing bypassing of the above settings by administrators or custom roles

These rules will be monitored and adjusted as necessary based on team feedback and observed effectiveness. Links to other decisions and resources may be added here as well.
