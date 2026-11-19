# .github: instructions for agents

## This repository is public

Everything here is publicly visible. Never add names, structure or content of the organization's private repositories, host names, domains, IP addresses, infrastructure details, credentials or internal links. Scan the diff for such details before every commit.

## Organization rules

The organization's full rules for agents live in its private governance repository; agents with organization access read them there.

- Every change: issue → draft pull request → ready for review (CI runs only then) → squash merge after all required checks are green. Never push to the default branch.
- Changes here affect every organization repository: the shared docs-lint workflow and configuration, and the default issue form, pull request template and security policy.
- `docs / lint` (Vale and markdownlint) is a required check; lint changed Markdown locally before pushing.
- Never commit secrets, tokens or credentials.
