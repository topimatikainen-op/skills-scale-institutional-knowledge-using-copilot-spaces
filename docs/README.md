# OctoAcme Project Management Docs

This README collects the OctoAcme program management process documents and provides a short summary of the project management approach. It is intended to be a single, discoverable entry point for the team's process documentation so new contributors and stakeholders can quickly find and reference the materials.

OctoAcme runs projects with an iterative, customer-first approach that emphasizes small, measurable increments and clear decision gates. Work begins with a lightweight initiation (a project one‑pager capturing problem, objectives, success metrics, stakeholders, and a high‑level timeline). Planning breaks approved initiatives into a prioritized backlog with acceptance criteria, estimates, and a Definition of Done so items are shippable and testable; a release plan and a simple risk register are created alongside the backlog.

Execution is organized around a disciplined workflow and project board (Backlog → Ready → In Progress → In Review → QA → Done). Pull requests are kept small where possible, include issue links and acceptance criteria, and require CI checks (tests, linting, security scans) and at least one approval before merging. Teams use daily standups to surface blockers, a weekly delivery sync for progress and risk review, and demos at the end of sprints or milestones to validate outcomes with stakeholders.

Roles and communication are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate schedules, risks, and stakeholder updates; Developers implement and test; QA validates acceptance criteria; stakeholders provide inputs and approvals. Releases follow a checklist (pre‑release validation, deploy to staging and smoke tests, production deployment, post‑deploy verification) and include rollback/mitigation plans. Retrospectives and tracked action items feed continuous improvement.

## Documents
- docs/octoacme-project-management-overview.md — Overview, principles, roles, and lifecycle  
- docs/octoacme-project-initiation.md — Initiation guide and one-pager template  
- docs/octoacme-project-planning.md — Planning activities, backlog template, and checklists  
- docs/octoacme-execution-and-tracking.md — Team rhythm, workflows, PR practices, and execution checklist  
- docs/octoacme-risks-and-communication.md — Risk register format, communication templates, and escalation paths  
- docs/octoacme-release-and-deployment.md — Release types, deployment checklist, and rollback playbook  
- docs/octoacme-retrospective-and-continuous-improvement.md — Retrospective structure and tracking improvements  
- docs/octoacme-roles-and-personas.md — Role definitions and responsibilities

## How to contribute
If you have updates or new process documents, please open an issue using the "Add Content to Project Management Process Docs" template (located in .github/ISSUE_TEMPLATE/) and propose your change. Link the issue to your PR so reviewers can see acceptance criteria and rationale.
