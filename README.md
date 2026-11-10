# intune-policy-changes-oidc

**Public intent repo** for the Intune CI/CD OIDC federated-credential POC.

Push JSON under `changes/` → validate → `repository_dispatch` → private [`intune-cicd-oidc-poc`](https://github.com/SureshVijayaraghavan/intune-cicd-oidc-poc) (approve → GitHub OIDC → Entra App Registration → Graph → Intune).

## Required secret

| Secret | Purpose |
| --- | --- |
| `EXECUTOR_DISPATCH_TOKEN` | Token with Actions write on `intune-cicd-oidc-poc` |

Optional variable: `EXECUTOR_REPO=SureshVijayaraghavan/intune-cicd-oidc-poc`
