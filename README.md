# Runner

Workflow callers only. Each workflow checks out a separate code repository and runs one composite action from it. Nothing else lives here.

## Workflows

| File | Trigger |
|---|---|
| `daily.yml` | manual dispatch |
| `seminar_block.yml` | manual dispatch |
| `manual.yml` | manual dispatch |

## Configuration

Secrets and variables are set in the repository settings. Their names appear in the workflow files.

## Contributions

This repository does not take contributions. Issues and pull requests are not monitored.
