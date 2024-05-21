---
parent: Decisions
date: 2024-05-21
title: Search Functionality
deciders: Brandon, Charlie, David, Ginger, Julie, Milana, Riana
---

# Decided what functionality our search will have

## Context and Problem Statement

To make note search implementable we want to specify what you can search for and how that will work.

## Considered Options

* Title (by keyword)
* Date (a specific date)
* Date range
* Filter by label (same behavior as clicking on the label button)
* Entry (by keyword)

## Decision Outcome

We will implement
* Title (by keyword) 
* Date (a specific date)
* Filter by label (same behavior as clicking on the label button)
Because these all are critical info for the note. They also should be reasonably straightforward to implement.

We will not implement
* Date range
* Entry (by keyword)
These would be nice to haves that can go in our backlog.
