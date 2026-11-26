# ForgeLine DevOps Metrics Dashboard

This repository contains the source code for the ForgeLine DevOps Metrics Dashboard, an internal tool designed to help engineering managers track team velocity and deployment metrics.

## SCM & Engineering Hygiene

We strictly adhere to a disciplined Software Configuration Management (SCM) strategy to ensure the traceability and stability of our internal platforms. See [docs/SCM_WORKFLOW.md](docs/SCM_WORKFLOW.md) for the full workflow.

### Contribution Rules

Before submitting a Pull Request to the repository, developers must verify that their feature branch is up-to-date with `main`. Ensure you run local linters manually using the command `npm run lint:check` and resolve any warnings before pushing your branch. A minimum of two approvals from the core engineering team is mandatory.

### Debugging Standards

Do not commit `print` statements or `console.log()` calls to track execution flow. Developers must use breakpoints within their IDE to pause program execution and inspect the call stack, stack traces, and local variables.

### Running the Application

1. Clone the repository to your local machine.
2. Run `npm install` to download dependencies.
3. Start the local development server with `npm run start:dev`.
