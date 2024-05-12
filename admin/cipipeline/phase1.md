# Pipeline: Phase 1 Overview

![Phase 1 Diagram](phase1.png)


## Current Funcitonality   

### Codacy

* Code quality metrics reporting
  * Quality evolution chart tracks quality of issues, complex files, duplication, and code coverage. Currently based on Codacy default quality gates.
    
* Automatic issue generation and breakdown by severity and category
  
* Linters enabled for
*
*

### JSDocs

* 
* 

### Branch Protection Rules

* Require a pull request before merging
  * All commits must be made to a non-protected branch and submitted via a pull request before they can be merged into a branch that matches main.
 
* Require approvals
  * Pull requests targeting main require one approval and no changes requested before they can be merged.
 
* Require status checks to pass before merging
  * run-lint must pass before branches can be merged into main. When enabled, commits must first be pushed to another branch, then merged or pushed directly to main after status checks have passed.
  * (Tentative) Require branches to be up to date before merging. This ensures pull requests targeting a matching branch have been tested with the latest code.

* Lock branch 
  * main is read-only. Users cannot push to main.

* Do not allow bypassing the above settings

### Super-Linter

* 
* 



## Planned/In Progress


