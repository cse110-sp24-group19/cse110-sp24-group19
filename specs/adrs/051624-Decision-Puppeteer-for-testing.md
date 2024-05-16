---
parent: Decisions
date: 2024-05-16
title: ADR Template
deciders: Allison, Brandon, Charlie, David, Ginger, Julie, Julio, Milana, Nikolas, Riana, Wenzhe
---

# Use Puppeteer for Testing

## Context and Problem Statement

As we develop our project, we want to incorporate End-to-End testing to make sure that our UI is functional and works when changes are made such as adding new features. This should be a tool that multiple people on the team feel comfortable using, that is used in industry or by other developers so we know it is reliable, and is free for us to use (has a license that allows us to use it).

## Considered Options

* Puppeteer
* Selenium: Web automated testing or other from https://katalon.com/resources-center/blog/end-to-end-e2e-testing-tools-frameworks

## Decision Outcome

Chosen option: Puppeteer, because everyone on the team has experience using this tool from lab 6. Therefore we will all be able to use it, contribute, and debug the tests, limiting our bus factor.
