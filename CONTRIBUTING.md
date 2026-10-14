# Contributing to EasyMenu AI

The project is in planning and development. Please coordinate work through issues and keep documentation accurate about what is planned, implemented, and evaluated.

## Team workflow

1. Open or claim an issue describing the change.
2. Create a branch from the latest `main`, such as `feature/menu-extractor` or `docs/setup`.
3. Make focused changes and use clear commit messages.
4. Open a Pull Request to `main` explaining the problem, changes, validation, and limitations.
5. Request a review from another team member and address feedback before merging. The normal team workflow requires at least one approval.

## Code and experiments

- Use readable Python and document dependencies and setup when adding a module.
- Run checks relevant to your change; state clearly when something was not tested.
- For experiments, record data provenance, model/version, configuration, random seeds, metrics, and reproducible steps.
- Keep credentials, personal/customer data, datasets, model weights, and large outputs out of Git. The `.gitignore` provides common exclusions but does not replace reviewing files before committing.
- Document licenses and permissions for datasets and models.
- Do not present proposed technology or unmeasured results as completed work.

## Review

Keep Pull Requests small enough to review. Discuss changes respectfully and flag unresolved limitations. Repository owners retain administrative control for recovery and maintenance.
