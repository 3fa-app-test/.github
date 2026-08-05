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
