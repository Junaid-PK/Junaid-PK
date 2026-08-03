# Junaid Hussnain

Software engineer in Lahore, Pakistan. I build backend products, operational
tools, and the interfaces that make complicated systems easier to run.

[Portfolio](https://hijunaid.com) · [Engineering notes](https://hijunaid.com/blog) · [LinkedIn](https://www.linkedin.com/in/junaid-hussnain-a951791bb/) · [Email](mailto:junaidhussnain369@gmail.com)

## Selected public work

| Project | What it solves | Engineering focus |
| --- | --- | --- |
| [hijunaid.com](https://github.com/Junaid-PK/me) | Makes private product experience, public code, writing, and upstream work discoverable in one evidence-led portfolio | Vue static generation, entity SEO, RSS/IndexNow, hardened automated VPS delivery |
| [Stackline](https://github.com/Junaid-PK/stackline) | Builds ATS-friendly resumes without sending career data to a server | Local-first React architecture, explainable scoring, tested export logic |
| [E-Manager](https://github.com/Junaid-PK/e_manager) | Brings invoices, banking, expenses, projects, and workforce operations into one model | Laravel, Livewire, authorization boundaries, signed exports, feature tests |
| [Laravel Development Workflow](https://github.com/Junaid-PK/laravel-development-workflow) | Turns feature requests and bug reports into repeatable, verifiable delivery steps | Acceptance criteria, regression-first testing, realistic boundary states |

## Current open-source work

- **Merged:** [Verdict — evaluation CLI](https://github.com/fissible/verdict/pull/6), adding validated evaluation baselines, regression reporting, stable CI exit codes, and redacted GitHub Actions annotations.
- **In review:** [Verdict — redacted provenance ledger](https://github.com/fissible/verdict/pull/7), tracking explicitly labeled user, retrieval, tool, and application inputs through canonical fingerprints without retaining their raw content.
- **In review:** [Rector — safe constructor default inlining](https://github.com/rectorphp/rector-src/pull/8281), preventing property initialization from changing when a child class bypasses its parent constructor.
- **In review:** [Meilisearch PHP — Dynamic Search Rules backport](https://github.com/meilisearch/meilisearch-php/pull/942), bringing the Meilisearch 1.50 API to `v1.x` while preserving PHP 7.4 support, typed contracts, and the branch's task conventions.

Both Verdict contributions passed the complete PHP, Laravel, Linux, and Windows matrix plus a clean Laravel consumer install; the evaluation CLI is merged and the provenance ledger awaits maintainer review. The Rector fix is open and mergeable with all 62 executed upstream checks passing across Linux, Windows, PHP 8.4, and PHP 8.5. The Meilisearch backport is also open and mergeable, with upstream CI awaiting maintainer approval.

## Latest engineering notes

- [Designing a Redacted Provenance Ledger for Laravel AI Agents](https://hijunaid.com/blog/designing-a-redacted-provenance-ledger-for-laravel-ai-agents) — explicit trust labels, canonical fingerprints, recorder boundaries, additive evidence storage, and the limits of deterministic hashes.
- [Designing CI-Safe Evaluation Baselines for Laravel AI Agents](https://hijunaid.com/blog/designing-ci-safe-evaluation-baselines-for-laravel-ai-agents) — the threat model, atomic persistence, failure taxonomy, and CI protocol behind the merged Verdict contribution.
- [Backporting Meilisearch Dynamic Search Rules Without Dropping PHP 7.4](https://hijunaid.com/blog/backporting-meilisearch-dynamic-search-rules-to-php-74) — translating a modern feature into an older branch without importing unrelated architecture or weakening verification.

## How I approach engineering

- Model the real workflow: users, permissions, failure states, and the decisions a system must preserve.
- Make operations visible: imports, queues, reporting, observability, and deployment are part of the product.
- Reduce the cost of the next change with narrow contracts, readable tests, and maintainable infrastructure.

I work primarily with **PHP / Laravel, TypeScript, Python, PostgreSQL, Redis,
Docker, and GitHub Actions**. Current focus: shipping Stackline and publishing
practical notes from open-source and product engineering work.
