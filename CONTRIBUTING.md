<h1 align='center'>Contributing</h1>
(Even after a recent refactor the code is still a bit sloppy, in a bit of a segwit rush, apologize in advance for any "wtf is this?")

## Overview
Please join us on [slack](https://join.slack.com/t/zaphq/shared_invite/enQtMzA4OTgxNTQ4NzUzLTQwYjkzZGM0ZWMwYmYyZTE2Y2E1YjM5NTIwOTU0M2I1Zjc2YWY1NTc4NjdhZWQxNTM1YzEzOGM2YTVlNWIwODc) and check [open issues](https://github.com/LN-Zap/zap-desktop/issues) to see what contributions are needed before tackling a task to avoid duplicate work. 

## Pull Requests
The `master` branch will be used for all pull requests for the time being. This may change as the repo and contributors grow.

### Branch Names

Branch names should start with `feature` or `fix` followed by `/description_of_branch`.

#### Example

```bash
git branch feature/list-onchain-txs
```

### Commit Messages

Commit messages should start with `feature`, `fix`, or `test` followed by `(subject_of_commit)` and ending with `: description_of_commit`.

#### Example

```bash
git commit -m "feature(list-onchain-txs): create hard code mock of onchain-txs list"
```

## eslint
This project has eslint rules and pull requests should pass `npm run lint` before being merged. The eslint rules are not final by any means and can be changed if necessary

## Tests
Tests should try to be written for every feature/fix and pass `npm run test` before being merged. With the demand for the Lightning Network and Zap rising, rapid development will naturally leave some code untested but we should all try our best.