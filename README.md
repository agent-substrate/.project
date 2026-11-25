# Agent Substrate `.project`

`.project` (dot-project) is a CNCF initiative to centralize and automate metadata management for CNCF projects.
This repository holds the canonical metadata for [Agent Substrate](https://github.com/agent-substrate/substrate).

## What's in this repo

| File | Purpose |
|------|---------|
| `project.yaml` | Canonical project metadata (name, maturity, repositories, governance links) |
| `maintainers.yaml` | Maintainer roster used by CNCF automation for Service Desk and mailing-list access |
| `.github/workflows/validate.yaml` | CI — validates `project.yaml` and `maintainers.yaml` on every PR |

## Maintainer records

`maintainers.yaml` lists GitHub handles and teams only; it does not store names, email addresses, or company affiliations. Keep each maintainer's name, primary email, and current affiliation accurate in their LFID profile at [openprofile.dev](https://openprofile.dev), and keep current affiliations visible in [`MAINTAINERS.md`](https://github.com/agent-substrate/substrate/blob/main/MAINTAINERS.md). Updating one record does not update the other.

## Resources

- [`.project` documentation](https://github.com/cncf/automation/tree/main/utilities/dot-project)
- [Schema reference](https://github.com/cncf/automation/blob/main/utilities/dot-project/SCHEMA.md)
