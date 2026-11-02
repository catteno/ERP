# ERP TIM

Central project repository for all systems belonging to ERP TIM.

## Repository organization

Each system lives in its own directory under `systems/`:

```text
systems/
  <system-name>/
```

Systems can use different technology stacks. Keep each system's source code,
dependency configuration, and tests together in its directory.

## Adding a system

1. Create `systems/<system-name>/` using a descriptive, lowercase, hyphen-separated name.
2. Add the system's source code and tests.
3. Include a README in the system directory describing:
   - Its purpose and responsibilities.
   - Prerequisites and dependency installation.
   - Configuration and commands to run it locally.
   - Commands to build, lint, and test it, where applicable.
   - Integrations with other ERP TIM systems.
4. Keep credentials and environment-specific secrets out of the repository.
   Document required configuration using placeholders instead.

## Development

This repository currently provides an organizational foundation; no systems have
been added yet. There are no repository-wide build, lint, or test commands.
Once systems are added, follow the instructions in each system's README.
