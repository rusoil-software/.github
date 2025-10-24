# Rusoil Software

Rusoil Sofrtware is a student working group to create awesome projects and a singular place where they could collaborate across faculties and groups.

> **Team Lead:** Rusoil Software — Student Organization
> A collaborative space for student projects across faculties and groups: learn, build, review, and share code together.

---

## Table of contents

* [What this is](#what-this-is)
* [Getting started](#getting-started)
* [Contribution guidelines](#contribution-guidelines)
* [Repository templates & useful resources (placeholder)](#repository-templates--useful-resources-placeholder)
* [Governance & roles](#governance--roles)
* [Disclaimer & funding policy](#disclaimer--funding-policy)
* [Code of Conduct](#code-of-conduct)
* [License](#license)
* [Contacts](#contacts)

---

## What this is

**Rusoil Software** is a student-run GitHub organization and study group created to host and collaborate on learning projects across faculties and student groups.
Our goals are to:

* Provide a low-pressure, educational environment for students to practice software engineering.
* Share knowledge, code reviews, and feedback across disciplines.
* Build small-to-medium scale projects that teach best practices (version control, testing, CI, documentation, collaboration).

This is **not** a commercial company. Projects here are for **study and educational purposes only**.

---

## Getting started

1. Browse the organization repositories and read each repo's `README.md`.
2. If you'd like to contribute:

   * Fork the repository (unless the repo asks you to join as a collaborator).
   * Create a topic branch: `git checkout -b feat/your-short-description`.
   * Write tests for new behavior where applicable.
   * Open a Pull Request (PR) against the repository's default branch and follow the PR checklist below.

---

## Contribution guidelines

We follow common good practices from open-source communities. If you're new to open-source contribution, use this as a checklist.

### Before you code

* Read the repository `README.md`, `CONTRIBUTING.md`, and issue templates.
* Check existing issues and open PRs — don’t duplicate effort.
* Ask on the project's communication channel if something is unclear.

### Branch & commit style

* Branch names: `feat/`, `fix/`, `docs/`, `chore/`, `refactor/` e.g. `feat/auth-login`.
* Keep commits small and focused. Use present-tense verbs, e.g.:

  ```
  feat(auth): add token refresh flow
  fix(api): handle 404 on user fetch
  docs: update contributor setup steps
  ```
* Sign commits if the repo requires DCO (Developer Certificate of Origin).

### Pull Requests

* Create a clear PR title and description:

  * What changed
  * Why it changed
  * How to test it (commands / steps)
  * Related issue number (if any)
* Include screenshots or logs if the change affects UI or CI.
* Link to issues using `#<issue-number>`.
* Request reviewers and tag maintainers if needed.

**Suggested PR template**

```md
<!-- PR Title -->
## Summary
Short description of the change.

## Related issue
Closes #<issue-number> (if applicable)

## How to test
1. Step one
2. Step two

## Checklist
- [ ] Tests added/updated
- [ ] Documentation updated
- [ ] Code follows style guidelines
```

### Issues

* Use a descriptive title and steps to reproduce (if bug).
* Tag issue type: `bug`, `enhancement`, `question`.
* Provide environment details and logs where applicable.

### Code quality & tests

* Add tests for new features and bug fixes where feasible.
* Keep code readable — prefer clarity over cleverness.
* Follow the language-specific style guide for the repo (e.g., PEP 8 for Python, ESLint rules for JS).
* Use CI (GitHub Actions, etc.) to run tests and linting before merging.

### Reviews & approvals

* PRs should be reviewed by at least one other contributor; maintainers may require two.
* Be polite and constructive in reviews. Explain reasoning and suggest improvements.
* Respect decisions from maintainers if they have final merge rights.

---

## Repository templates & useful resources (placeholder)

Placeholders for resources that repositories in this organization should link to or include:

* `.github/ISSUE_TEMPLATE.md` — Issue templates (bug, feature request).
* `.github/PULL_REQUEST_TEMPLATE.md` — PR template (see suggested above).
* `CONTRIBUTING.md` — repo-specific rules and setup steps.
* `CODE_OF_CONDUCT.md` — behavior expectations and reporting.
* `LICENSE` — chosen license file.
* `README-SHORT.md` — short repo intro for quick browsing.
* `docs/` — design docs, API specs, architecture notes.
* `ci/` — CI configuration examples (GitHub Actions workflows).
* `examples/` — runnable example code / demo.

**General learning resources (add per-project links):**

* Git & GitHub guides
* Language style guides (PEP 8, Google Java Style, etc.)
* Testing libraries & best practices
* Continuous integration basics (GitHub Actions)
* Code review & UX basics

*(Maintainers: please replace placeholders with project-specific links.)*

---

## Governance & roles

* **Team Lead(s)** — coordinate organization-wide activities, approve org-level policies.
* **Maintainers** — own individual repositories, review and merge PRs, manage issues.
* **Contributors** — anyone who contributes code, docs, tests, or reviews.
* **Observers/Students** — participants who learn, comment, and test.

If you want to take on a maintainer role, contact the Team Lead and show prior contributions.

---

## Disclaimer & funding policy

* **Educational purpose only.** This GitHub organization and all repositories under it are part of a study group. Content published here is intended for study, teaching, and research. It is not professional advice.
* **No commercial/profit intent.** No for-profit propositions, sales, or commercial contracts are arranged through this organization.
* **No donations accepted.** Neither the organization nor its members accept donations or financial contributions for the work hosted here. If, in the future, funding is required for an explicit educational activity, it will be decided transparently and only after community agreement; explicit opt-in and documented governance will be required.
* Contributors retain responsibility for the code they publish. Use code at your own risk and always verify before using in production environments.

---

## Code of Conduct

We are a learning community. Harassment, discrimination, or other abusive behavior will not be tolerated. Every repository must include a `CODE_OF_CONDUCT.md` describing:

* Expected behavior
* Unacceptable behavior
* Reporting procedure
* Enforcement

If you witness or experience misconduct, please contact the Team Lead or maintainers listed in the repo.

---

## License

Each repository should include a `LICENSE` file. We recommend permissive licenses for educational projects (e.g., MIT or Apache-2.0), but license choice is per-repo and must be explicit in the `LICENSE` file.

> Note: Choosing a license is an important legal decision — pick one that fits the project's goals.

---

## Contacts

* Team Lead: `team-lead@rusoil.example` *(replace with actual contact)*
* Maintainers: see each repository's `MAINTAINERS.md` or `README.md`
* Communication channels: [Discord/Slack/Matrix — placeholder] (add links)

---

## Acknowledgements

Thanks to everyone who teaches and mentors here. This organization exists to practice good engineering and collaboration habits in a safe, educational environment.

---

*Last updated: — October 24, 2025*
