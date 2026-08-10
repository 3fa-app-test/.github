## Purpose

Describe the contract, failure mode, and why this test repository owns the change.

## Planning and dependencies

- Linear issue or project: [github.com/3fa-app-test](https://linear.app/denman/project/githubcom3fa-app-test-ad9ba775843f)
- Product repository, revision, package, or pull request under test:
- Related test repositories or external contracts:

## Architecture and compatibility

Describe affected repositories, APIs, schemas, fixtures, generated artifacts,
infrastructure, deployment behavior, and external dependencies.

## Validation

List the exact local and remote commands, environments, and results. Distinguish
real-system checks from fixtures or permitted external-service doubles.

## Conflict-resolution record

- [ ] Remote state was fetched before editing and before pushing.
- [ ] Concurrent local and remote work was preserved without rewriting history.
- [ ] Conflicts, if any, were resolved semantically using both sides, relevant history, tests, contracts, and related repositories.
- [ ] No `ours`/`theirs` side was accepted wholesale without conceptual review.
- [ ] The complete worktree was scanned for unresolved conflict markers.

## Acceptance change

- [ ] Source commits are immutable.
- [ ] Product assertions execute.
- [ ] Failure and recovery paths execute.
- [ ] Logs contain no secrets or raw private media.
- [ ] Emulator, browser, and database matrices are justified.
- [ ] Failure classification is explicit.
- [ ] Upstream revision or package is recorded.
- [ ] Fixtures are synthetic and secret-free.
- [ ] Expensive checks are scheduled or manual.
- [ ] A superseded PR contributed at least one traced substantive idea when applicable.
- [ ] No credentials, personal data, production data, or private-repository inventory is included.

## Risks and roll-forward plan

Describe residual uncertainty, operational cost, compatibility, and reversible
roll-forward handling.
