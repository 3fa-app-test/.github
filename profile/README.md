# 3fa-app-test

Independent acceptance organization for **3FA-app**.

Cross-device authentication, recovery, synchronization, SDK, desktop, mobile, API, and browser-extension acceptance.

## Portfolio

| Repository | Class | Readiness | Primary dependency path |
|---|---|---|---|
| `mobile-emulator-e2e` | mobile/emulator | `ready` | `matrix` |
| `desktop-app-e2e` | desktop E2E | `ready` | `matrix` |
| `clients-consumer-matrix` | SDK consumer | `ready` | `matrix` |
| `backend-api-contract` | API contract | `ready` | `matrix` |
| `multi-device-sync` | synchronization | `ready` | `matrix` |
| `offline-background-mode` | mobile/emulator | `ready` | `matrix` |
| `browser-extension-e2e` | browser E2E | `ready` | `matrix` |
| `account-recovery-security` | security | `ready` | `matrix` |

Pull requests run deterministic harness checks. Emulators, desktop matrices, live APIs/providers, databases, chaos, scale, and soaks are scheduled/manual. Missing upstreams or credentials are blocked readiness—not false passes or product regressions.

<!-- org-project-routing:start -->
## Planning and delivery

- [GitHub Project: 3fa-app-test-project](https://github.com/orgs/3fa-app-test/projects/1)
- [Linear planning project](https://linear.app/denman/project/githubcom3fa-app-test-ad9ba775843f)
- [Detailed project-routing contract](../docs/PROJECTS.md)

GitHub owns code and delivery evidence; Linear owns planning and dependencies. The linked organization Project provides the cross-repository execution view.
<!-- org-project-routing:end -->
