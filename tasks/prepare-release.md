# Task: prepare-release

Steps to execute when asked to prepare a release:

1. Remove the `-SNAPSHOT` suffix from the version in the project module's `build.gradle`.
2. Commit with message `Release <version>` (e.g. `Release 25.12.15`).
3. Collect all commit messages between the previous release commit and this one.
4. Categorize them into: **New Features**, **Improvements**, **Bugfixes**. If the category cannot be determined, place in **Unknown**.
5. Ignore commits with the message `Update to new version`.
6. Format the release notes using the template below, with the current date filled in.
7. Export the release notes as a markdown file named `<project-name>-release-notes.md` to `~/Desktop`.

## Release Notes Template

```
**25.12.15 | 2025 December 15**

**New Features**
-

**Improvements**
-

**Bugfixes**
-
```
