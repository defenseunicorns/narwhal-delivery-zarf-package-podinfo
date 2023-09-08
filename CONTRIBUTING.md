# Contributor Guide

TODO: Add more content

## Testing

This repo doesn't do any testing yet. We need to add some.

## Release Process

This repo uses [release-please](https://github.com/googleapis/release-please). To create a new release, which will automatically build and publish a new OCI artifact of the package, just merge the PR that release-please creates.

## Commit Messages

- Because we use release-please, all commits to main need to follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) format.
- Because we use Merge Queue, the title of the PR needs to follow Conventional Commits format as well, since that is what is used as the commit message when the Merge Queue merges the PR.
