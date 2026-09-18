# Security Policy

Security issues are taken seriously.

If you believe you have found a vulnerability in one of my projects, please report it privately rather than opening a public issue or discussion.

## Reporting a vulnerability

Use GitHub Private Vulnerability Reporting when it is available for the repository.

You can usually find it under:

`Security` → `Report a vulnerability`

If private vulnerability reporting is not available, use another private contact method published by the project or maintainer.

Do not disclose suspected vulnerabilities through:

* Public GitHub Issues.
* GitHub Discussions.
* Pull requests.
* Public comments.
* Social media or other public channels.

## What to include

Provide as much relevant information as reasonably possible, such as:

* A description of the vulnerability.
* The affected component or feature.
* The affected version or commit, when known.
* Steps to reproduce the issue.
* A minimal proof of concept, when appropriate.
* The security impact you believe the issue may have.
* Relevant logs, requests, responses, or configuration.
* Possible mitigations or fixes, if you have identified any.

You do not need to provide a complete security analysis before reporting an issue. If you have reasonable evidence that something may represent a vulnerability, report it privately.

## Sensitive information

Do not include unrelated sensitive information in a report.

Avoid sharing:

* Passwords.
* Access tokens.
* API keys.
* Private keys.
* Session cookies.
* Personal data.
* Credentials belonging to third parties.

If credentials are necessary to demonstrate the issue, prefer creating temporary or dedicated credentials that can be revoked afterward.

## Responsible disclosure

Please allow reasonable time for the vulnerability to be investigated and, when appropriate, fixed before publicly disclosing technical details.

Depending on the issue, disclosure may be coordinated with the reporter.

Please avoid actions that could unnecessarily expose users or systems while investigating a vulnerability, including:

* Accessing data that does not belong to you.
* Modifying or deleting third-party data.
* Disrupting services.
* Performing denial-of-service testing.
* Attempting to maintain persistent access.
* Expanding testing beyond what is reasonably necessary to demonstrate the issue.

## Supported versions

Support depends on the individual project.

Unless a repository documents a different policy, security fixes will generally target versions that are currently maintained by that project.

Older releases, development branches, experimental features, or unsupported environments may not receive security updates.

A repository-specific `SECURITY.md` takes precedence over this default policy.

## Security improvements

General security hardening, dependency updates, defensive improvements, and similar changes may normally be proposed through regular issues or pull requests when they do not reveal an undisclosed vulnerability.

If discussing the change would disclose an exploitable security issue, report it privately first.

## After reporting

Reports will be reviewed when maintainer availability permits.

You may be asked for additional information or reproduction details.

A report may be determined to be:

* A confirmed vulnerability.
* A security hardening opportunity.
* Expected behavior.
* Outside the project's supported scope.
* Not reproducible with the available information.

Please keep vulnerability details private while the report is being investigated.
