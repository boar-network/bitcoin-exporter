# Boar Network - notes

## Our Docker image

Boar Network stores Docker image for this repository in:
https://github.com/orgs/boar-network/packages

> Docker tag matches Git tag.

## How to update tags?

1. Clone this repository
2. Run:
`git remote add upstream https://github.com/jvstein/bitcoin-prometheus-exporter`
3. Run: `git fetch --tags upstream`
4. Run: `git push --tags`
