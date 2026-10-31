# Dashboard project

A framework-neutral starting point for this dashboard project.

**Status:** repository scaffold only. There is no application, recovered source code, development server, dependency manifest, or deployment yet. The repository name does not imply a ChatGPT integration.

## Folder structure

| Path | Purpose |
| --- | --- |
| `src/` | Future application source; currently a placement guide only |
| `assets/` | Approved design and brand assets; currently a placement guide only |
| `tests/` | Future automated tests; currently a validation checklist |
| `docs/requirements.md` | Inputs and decisions required from the project owner |
| `docs/implementation-plan.md` | Phased delivery plan with acceptance criteria |
| `docs/decisions.md` | Record of confirmed and pending technical decisions |
| `.github/pull_request_template.md` | Change and verification checklist |
| `.editorconfig` | Basic whitespace conventions |
| `.gitattributes` | Consistent text line endings |
| `.gitignore` | Local environment and temporary-file exclusions |

The folder guide files keep otherwise empty directories tracked by Git. Adapt these folders to the selected stack rather than forcing a framework into this layout.

## Setup now

Prerequisites: Git and a text editor. No application runtime is required for this scaffold.

```sh
git clone https://github.com/kvgudu-pixel/chatgpt.git
cd chatgpt
git switch -c feat/dashboard-foundation
```

1. Read and fill in [requirements](docs/requirements.md).
2. Record confirmed choices in [decisions](docs/decisions.md).
3. Follow the [implementation plan](docs/implementation-plan.md).
4. Submit changes with the repository's pull request template.

There is no install, start, build, or test command yet. Add exact commands and supported runtime versions here when the stack is selected. Do not run a framework generator over this repository without reviewing what it will overwrite.

## What is ready and what comes later

| Ready now | Must be supplied or decided later |
| --- | --- |
| Folder conventions and contributor checklist | Dashboard purpose, users, pages, and first workflow |
| Setup and implementation plan | Framework, language, runtime, and package manager |
| Requirements and decision templates | Approved design reference, branding, and assets |
| Local secret-file exclusions | Data contracts, authorized API access, and sanitized examples |
| Planned validation criteria | Authentication, roles, hosting, and deployment configuration |

No credentials are needed now. When configuration is introduced, document only actual variable names in a tracked example file with dummy values; keep credentials in ignored local files or the deployment platform's secret store. Ignore rules do not remove secrets already committed.

## Verification

This scaffold can be reviewed by checking file links, the folder map, and the outstanding decisions. Application tests and CI are not configured. Once implementation begins, replace the test guide with executable checks and document how to run them.

## Licensing

No license has been selected. The owner must choose one before representing the project as licensed for reuse.
