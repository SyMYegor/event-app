<!-- LR4 2.3 and 2.7: Project structure and Git process -->
# Event App
Mobile application for organizing events.
Author: Yegor Sadkovyi, group 491.

## Features
- Create events
- Manage participants

## Setup Instructions
1. Open event-app in Visual Studio Code.
2. Open src/index.html in a web browser.
3. Use Source Control to review and commit changes.

## Project Structure
- src/index.html: event page with a blue heading
- src/style-note.txt: style branch demonstration
- docs/readme.md: project description and Git process
- docs/workflow.md: GUI Git workflow
- docs/remote-note.md: file received from GitHub
- docs/cherry-note.md: single commit transfer demonstration
- docs/style-pr.md: style Pull Request documentation
- commits.txt: exported history before the export commit

## Git Process in VS Code
Initialize Repository creates the local repository.
Stage Changes prepares files, Commit records changes and Push shares them.
feature-style and feature-docs isolate independent work.
Merge Branch integrates completed changes into main.
Resolve conflicts before completing a merge.
Create a Pull Request on GitHub to review a branch difference.

## Asynchronous Fetch
Asynchronous fetch for remote changes: Fetch updates origin/main without
changing working files. Pull integrates the fetched remote changes.
The two steps separate downloading history from applying it.

## Resilience
Alternative path: revert to restore previous state.
Revert creates a new commit and preserves shared history.
In VS Code 1.140.0 the graphical revert demonstration uses Git Graph.
Undo Last Commit removes an unpushed commit and keeps staged changes.
Discard Changes removes an uncommitted edit without changing history.

## Cherry Pick
Cherry-pick copies the change from one selected commit to another branch.
It creates a new commit without merging the entire source branch.

## Bottleneck
Manual heading conflict resolution delays integration.
Short branches, regular updates and splitting work across files reduce
the risk. HTML validation helps detect errors before merging.