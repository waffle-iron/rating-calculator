# Contributing
This will be an ever evolving document, so it might be worthwhile to check back in.

## Getting started
This is a [yarn](https://yarnpkg.com/) managed project. If you want to acoid problems,
then you are goign to want to do `yarn install` to get your development environment
into a working state.

## Quick checklist to contributing
- [ ] Addresses an open issue
- [ ] Your changes are tested
- [ ] Test and linting pass

## Addresses an open issue
In the interest of keeping PRs focused on the implementation details of work, PRs will
generally only be accepted for open Issues. The issues is where we will deal with the
details of the problem/feature, and how a solution will be implemented.

__Note:__ Common sense takes precedence here. If you are fixing a typo don't feel like
it is necessary to open an issue for that.

## Your changes are tested
Obviously this doesn't apply to documentation PRs. but if you are adding new code, or
changing existing code, make sure that you have tests that cover your changes. If you have
to change existing tests to implement your feature be aware that it may be pushed to the 
next major release branch as that will normally be considered a breaking change.

##
Run `yarn test` (or `npm test` for the sake of running tests this shouldn't make a difference).
It should come back completely clean. If it doesn't you can basically count on the PR not
being merged. If you don't understand why a test, or tests, are failing let us know.
