# Software Engineering Process Module

Standard software engineering process module for Catalyst.

This module defines entity schemas, template artifacts, and slash-command specifications for managing software engineering processes within a Catalyst deployment.

## Contents

- **`module.yaml`**: Module specification and metadata.
- **`version.txt`**: Module version indicator (`1.0.0`).
- **`schemas/`**: Entity schemas for software engineering artifacts (`BUG`, `REQ`, `HK`, `TEST`, `STEP`, `FEAT`, `RM`, `WORKFLOW`, `RECON`).
- **`templates/`**: Document templates for creating new software engineering artifacts.
- **`commands/`**: Slash-command specifications for agent interactions (`create-req`, `create-bug`, `create-test`, `create-feature`, `create-step`, `check-rules`, `show-backlog`, `cut-release`).
