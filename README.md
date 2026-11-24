# .github

NobleFactor's own repository. GitHub serves the community health files and issue templates kept here to every
NobleFactor repository that doesn't have its own, and offers the workflow templates in `workflow-templates/` on every
repository's New workflow page. It also holds the organization's issue model.

| File | What it is |
| --- | --- |
| `model.yaml` | NobleFactor's issue model: its issue types, issue fields, teams, labels and project templates, as `star github model pull` writes it; star reads it from here |
| `CONTRIBUTING.md` | The terms of a contribution: the sign-off and the AI disclosure on every pull request |
| `SECURITY.md` | How to report a vulnerability privately |
| `SUPPORT.md` | Where to ask a question or report a problem |
| `.github/ISSUE_TEMPLATE/` | The issue forms, one for each issue type |
| `.github/pull_request_template.md` | The description every pull request starts from |
| `workflow-templates/` | The workflow templates: Triage, which the New workflow page offers, and the daily credentials check with its script and permissions file, which it doesn't, since the workflow alone can't run. Their source is noblefactor-engprod's `workflow-templates/`. A repository takes the credentials check by hand, all three files: `credentials-check.yml` in `.github/workflows/`, and `credentials-check.sh` and `credentials-check.json` in `.github/credentials-check/`; the secrets and variables it reads, and how to run it once to check it, are in [the credentials guide, § 7](https://github.com/NobleFactor/noblefactor-engprod/blob/develop/docs/reference/issue-tracking-credentials.md#checking) (noblefactor-engprod#613) |
| `.github/workflows/triage.yml`, `credentials-check.yml` and `.github/credentials-check/` | This repository's own Triage and daily credentials check, copies of the templates |
| `.github/workflows/quality-gate.yml` | This repository's own check: every YAML and JSON file parses |
