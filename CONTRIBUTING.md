# Contributing

Contributions are welcome.

Bug fixes, documentation improvements, tests, refactoring, feature proposals, accessibility improvements, performance improvements, and other useful changes are all valid forms of contribution.

Repository-specific contribution instructions take precedence over this document.

## Before contributing

Before opening an issue, discussion, or pull request:

* Read the repository README and relevant documentation.
* Search existing issues, discussions, and pull requests for similar work.
* Check whether the repository contains additional contribution instructions.
* Make sure the proposed change fits the scope of the project.

If you are unsure whether an idea belongs in the project, opening a discussion before implementing it can save unnecessary work.

For help using the project, see `SUPPORT.md`.

For security vulnerabilities, see `SECURITY.md` and do not open a public issue.

## Issues

Use GitHub Issues for reproducible bugs and concrete feature requests.

When reporting a bug, include enough information for someone else to understand and reproduce the problem whenever possible.

Useful information may include:

* What you were trying to do.
* What you expected to happen.
* What actually happened.
* Steps to reproduce the problem.
* Relevant versions and environment information.
* Error messages or logs.
* A minimal reproduction.

Remove credentials, tokens, private information, and other secrets before publishing logs or configuration.

Questions, general help, architectural discussions, and early-stage ideas are usually better suited to GitHub Discussions when Discussions are enabled.

## Feature requests

Feature requests should explain the problem or use case being addressed, not only a preferred implementation.

Useful proposals may include:

* The current limitation.
* The desired behavior.
* Why the change would be useful.
* Alternatives or workarounds already considered.
* Compatibility or maintenance implications.

Large or architectural changes should normally be discussed before substantial implementation work begins.

## Pull requests

Keep pull requests focused on a single logical change whenever practical.

A pull request should make it reasonably clear:

* What changed.
* Why the change is needed.
* How the change was tested.
* Whether behavior, configuration, documentation, or compatibility changed.

Avoid combining unrelated refactoring, formatting changes, dependency updates, and functional changes in the same pull request unless they are genuinely part of the same change.

Small and focused pull requests are generally easier to review than large ones.

## Development environment

Follow the setup and development instructions provided by the repository.

Before submitting a pull request, run the relevant checks documented by the project. Depending on the repository, these may include:

* Tests.
* Linters.
* Formatters.
* Type checks.
* Static analysis.
* Security checks.
* Build validation.
* Documentation checks.

Do not assume that every repository uses the same commands or development environment.

## Tests

Add or update tests when they are relevant to the change.

Tests should primarily verify externally meaningful behavior rather than implementation details.

Bug fixes should ideally include a regression test when one can reasonably be created.

If a change cannot be tested automatically, explain how it was validated.

## Documentation

Update documentation when a change affects:

* Public behavior.
* Configuration.
* Installation or setup.
* APIs or command-line interfaces.
* User-facing functionality.
* Supported environments.
* Important architectural assumptions.

Documentation changes are also welcome as independent contributions.

## Code style

Follow the conventions already used by the repository.

Prefer consistency with the existing codebase over introducing a new style without a clear reason.

When automated formatting, linting, or static-analysis tools are configured, their output should normally be treated as the source of truth.

Avoid unrelated formatting changes that make the actual contribution harder to review.

## Dependencies

Avoid adding dependencies when the same result can reasonably be achieved using existing project capabilities.

When introducing a dependency, consider:

* Maintenance status.
* Security history.
* License compatibility.
* Runtime and build impact.
* Transitive dependencies.
* Long-term maintenance cost.

Explain significant new dependencies in the pull request when their purpose is not obvious.

## Backward compatibility

Avoid unnecessary breaking changes.

If a breaking change is required, clearly describe:

* What is changing.
* Why the change is necessary.
* Who may be affected.
* Whether a migration path exists.

Repositories may define their own compatibility or versioning policies.

## Commits

Keep commits understandable and reasonably scoped.

Commit messages should describe the change clearly enough to be useful when reviewing project history.

A repository may define additional commit conventions. If it does, follow those repository-specific rules.

There is no global requirement to use a particular commit message convention unless the repository explicitly defines one.

## Generated files

Avoid manually editing generated files unless the repository specifically requires it.

When generated output must be committed, update it using the project's documented generation process whenever possible.

Changes to generated files should correspond to the source changes that produced them.

## AI-assisted contributions

AI-assisted development is welcome, but contributors remain responsible for everything they submit.

Before submitting AI-generated or AI-assisted code, documentation, tests, or configuration:

* Review and understand the generated content.
* Verify that it actually solves the intended problem.
* Test it appropriately.
* Check for security issues.
* Check for unnecessary complexity or dependencies.
* Verify licensing and provenance when relevant.
* Remove fabricated references, APIs, behavior, or assumptions.

AI-generated content is held to the same standards as any other contribution.

Do not submit large amounts of generated code that you have not reviewed or cannot reasonably explain.

## Licensing

By contributing to a repository, you agree that your contribution may be distributed under that repository's license unless the project explicitly states otherwise.

Do not submit code, documentation, media, or other material that you do not have the right to contribute.

When adapting work from another source, preserve required attribution and comply with the original license.

## Review process

Opening a pull request does not guarantee that it will be merged.

Changes may be declined because of:

* Project scope.
* Technical constraints.
* Maintenance cost.
* Compatibility concerns.
* Duplication.
* Architectural direction.
* Lack of sufficient testing or documentation.
* Availability of simpler alternatives.

Review feedback should focus on the contribution rather than the contributor.

You may be asked to revise a change before it can be accepted.

## Conduct

Be respectful and constructive when participating in project discussions and reviews.

By participating in the project, you agree to follow the repository's `CODE_OF_CONDUCT.md`.
