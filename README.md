# Junaid Hussnain

Software engineer in Lahore, Pakistan. I build backend products, operational
tools, and the interfaces that make complicated systems easier to run.

[Portfolio](https://hijunaid.com) · [Engineering notes](https://hijunaid.com/blog) · [LinkedIn](https://www.linkedin.com/in/junaid-hussnain-a951791bb/) · [Email](mailto:junaidhussnain369@gmail.com)

## Selected public work

| Project | What it solves | Engineering focus |
| --- | --- | --- |
| [Stackline](https://github.com/Junaid-PK/stackline) | Builds ATS-friendly resumes without sending career data to a server | Local-first React architecture, explainable scoring, tested export logic |
| [E-Manager](https://github.com/Junaid-PK/e_manager) | Brings invoices, banking, expenses, projects, and workforce operations into one model | Laravel, Livewire, authorization boundaries, signed exports, feature tests |
| [Laravel Development Workflow](https://github.com/Junaid-PK/laravel-development-workflow) | Turns feature requests and bug reports into repeatable, verifiable delivery steps | Acceptance criteria, regression-first testing, realistic boundary states |

## Current open-source work

- **Merged:** [Verdict — evaluation CLI](https://github.com/fissible/verdict/pull/6), adding validated evaluation baselines, regression reporting, stable CI exit codes, and redacted GitHub Actions annotations.
- **In review:** [Meilisearch PHP — Dynamic Search Rules backport](https://github.com/meilisearch/meilisearch-php/pull/942), bringing the Meilisearch 1.50 API to `v1.x` while preserving PHP 7.4 support, typed contracts, and the branch's task conventions.

Verdict was merged after its complete PHP, Laravel, Linux, and Windows test matrix passed. The Meilisearch contribution remains an open, mergeable upstream pull request awaiting maintainer review.

## Latest engineering note

[Backporting Meilisearch Dynamic Search Rules Without Dropping PHP 7.4](https://hijunaid.com/blog/backporting-meilisearch-dynamic-search-rules-to-php-74) — a field note on translating a modern feature into an older branch without importing unrelated architecture or weakening verification.

## How I approach engineering

- Model the real workflow: users, permissions, failure states, and the decisions a system must preserve.
- Make operations visible: imports, queues, reporting, observability, and deployment are part of the product.
- Reduce the cost of the next change with narrow contracts, readable tests, and maintainable infrastructure.

I work primarily with **PHP / Laravel, TypeScript, Python, PostgreSQL, Redis,
Docker, and GitHub Actions**. Current focus: shipping Stackline and publishing
practical notes from open-source and product engineering work.
