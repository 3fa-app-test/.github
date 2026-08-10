# 3fa-app-test

Independent acceptance organization for **3FA-app**.

Cross-device authentication, recovery, synchronization, SDK, desktop, mobile, API, and browser-extension acceptance.

## Coverage profiles

- `api-contract`
- `desktop-e2e`
- `extension-e2e`
- `flutter-emulator`
- `interop-e2e`
- `mcp-contract`
- `protocol-e2e`
- `sdk-consumer`
- `security-e2e`

## Portfolio

| Repository | Class | Readiness | Primary dependency path |
|---|---|---|---|
Private repository details are intentionally withheld from this public document.

Pull requests run deterministic harness checks. Emulators, desktop matrices, live APIs/providers, databases, chaos, scale, and soaks are scheduled/manual. Missing upstreams or credentials are blocked readiness—not false passes or product regressions.

<!-- org-project-routing:start -->
## Planning and delivery

- [GitHub Project: 3fa-app-test-project](https://github.com/orgs/3fa-app-test/projects/1)
- [Linear planning project](https://linear.app/denman/project/githubcom3fa-app-test-ad9ba775843f)
- [Detailed project-routing contract](../docs/PROJECTS.md)

GitHub owns code and delivery evidence; Linear owns planning and dependencies. The linked organization Project provides the cross-repository execution view.
<!-- org-project-routing:end -->


<!-- ore-org-baseline:begin -->
## Planning and governance

- Canonical Linear project: https://linear.app/denman/project/githubcom3fa-app-test-ad9ba775843f
- Organization defaults: https://github.com/3fa-app-test/.github
- Canonical agent policy: https://github.com/3fa-app-test/.github/blob/main/agents.md
- Security policy: https://github.com/3fa-app-test/.github/security/policy

Repositories in this organization use semantic conflict resolution with 3–10 relevant prior commits when useful, full cross-repository context, pull-request delivery, and a hard automated-agent denylist for destructive or history-rewriting operations.
<!-- ore-org-baseline:end -->

<!-- BEGIN MANAGED REPOSITORY RELATIONSHIPS v1 -->
## Repository relationship registry

`3fa-app-test` declares repository roles, dependency edges, cross-organization capabilities, deployment ownership, and the git-submodule/Zed-package contract:

- [Human-readable map](architecture/REPOSITORY_RELATIONSHIPS.md)
- [Machine-readable manifest](architecture/repository-relationships.json)
- [JSON Schema](architecture/repository-relationships.schema.json)

The public registry withholds private repository names and edges.
<!-- END MANAGED REPOSITORY RELATIONSHIPS v1 -->

Generated pull-request workflows use least privilege, immutable action pins,
and no persisted checkout credential. Integration workflows are gated by
organization variables and credentials.
