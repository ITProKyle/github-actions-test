# github-actions-test

![Actions Status](https://github.com/ITProKyle/github-actions-test/workflows/Hello%20World/badge.svg)

A repo for trying out github actions

test

## Setup

This section outlines how to setup portions of the repo that cannot be reasonably automated.

### Labels

1. Install [git-labelmaker](https://github.com/himynameisdave/git-labelmaker).
   - `npm i -g git-labelmaker`
2. [Generate a GitHub token](https://github.com/settings/tokens) with **repo** permissions.
3. Run `git-labelmaker` to initialize your session using the token.
4. Select the `Add Labels From Package` in the `git-labelmaker` menu and enter `./.github/labels.json`.
