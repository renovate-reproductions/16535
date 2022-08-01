# Renovate Yarn Issue Reproduction

## Current behaviour

When a PR to update a new version for a package is created, it tries to run `--ignore-platform` on the installed yarn version, which it doesn't seem to find. This flag however is undocumented, and seems to have been removed from yarn versions >2.

## Expected behaviour

Creating a PR to update a version should be possible with any version of yarn.
