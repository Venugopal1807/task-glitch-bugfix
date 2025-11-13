# Bugfix Assignment

## Overview

In This project fixed core bugs.  
Each bug was addressed in a branch, thoroughly tested, and merged into `main`.

## Bugfixes

- **Bug 1: Double fetch**
  - Fixed excessive data fetching, ensured tasks load only once.
- **Bug 2: Undo snackbar**
  - Resolved improper undo state and made deletion robust.
- **Bug 3: unstable sorting**
  - Ensured table sorting is deterministic and ties are handled correctly.
- **Bug 4: Double dialog opening**
  - Prevented action buttons (Edit/Delete) from bubbling to row click.
- **Bug 5: ROI Erros**
  - Fixed validation for ROI, revenue, time columns, and excluded malformed rows.

All bugfixes were implemented as described, tested such as manual and code review, and confirmed working.

## Workflow

- Each bug addressed in a separate branch.
- Merges performed via VS Code, with merge conflicts resolved carefully.
- Final project tested using `npm start`.
- See commit history for detailed progress.

## Setup/Run

