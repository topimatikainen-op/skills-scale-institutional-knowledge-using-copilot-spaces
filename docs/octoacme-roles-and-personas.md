# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
This file expands the existing core roles to include additional personas that improve clarity and accountability
for cross-cutting activities such as releases, reliability, security, UX handoffs, and customer outcomes.

---

## Core Roles (brief)

- Developers
  - Responsibilities: Implement features and fixes, write tests and docs, participate in design and code reviews.
  - Interaction: Works with PdM on acceptance criteria, with PM on scheduling, and with QA for validation.

- Product Managers (PdM)
  - Responsibilities: Define outcomes, prioritize backlog, craft acceptance criteria, measure success.
  - Interaction: Works with PM and Developers to prioritize and clarify scope.

- Project Managers (PM)
  - Responsibilities: Coordinate delivery, run planning and retrospectives, maintain risk and status artifacts.
  - Interaction: Facilitates cross-team coordination and escalations.

---

## Additional / Recommended Personas

- Release Manager
  - Responsibilities:
    - Own release planning and coordination across teams.
    - Approve production deployments and verify rollback plans.
    - Coordinate release communication and post-release verification.
  - Interaction:
    - Works with PM and PdM to align release timing and scope.
    - Coordinates with Developers, DevOps/SRE, and QA for staging verification and smoke tests.
    - Notifies Customer Success/Support and stakeholders prior to major releases.

- Engineering Manager
  - Responsibilities:
    - Support team-level capacity planning and resourcing.
    - Drive technical staffing, career growth, and code-quality practices.
    - Facilitate technical escalations and manage technical debt prioritization.
  - Interaction:
    - Coordinates with PM on capacity and delivery risk.
    - Helps translate architectural decisions to PdM and supports Developers in complex designs.

- DevOps / SRE (Reliability Engineer)
  - Responsibilities:
    - Maintain CI/CD pipelines, deployment automation, observability, and runbooks.
    - Manage operational readiness and support incident response.
    - Improve system reliability and performance.
  - Interaction:
    - Partners with Developers for smooth, testable deployments.
    - Works with Release Manager to automate releases and rollback.
    - Collaborates with Security Liaison for infra security controls.

- Security Liaison
  - Responsibilities:
    - Identify security requirements and coordinate scans, audits, and remediation.
    - Ensure security considerations are applied during planning and release.
    - Support threat modeling and secure-by-design practices.
  - Interaction:
    - Works with Developers and DevOps on fixes and with PM/PdM to prioritize security work.

- UX / Product Designer
  - Responsibilities:
    - Lead user research, design flows, accessibility checks, and UX acceptance.
    - Provide design specs and acceptance criteria for visual and interaction work.
  - Interaction:
    - Collaborates with PdM on feature definition and acceptance criteria.
    - Works with Developers during implementation and reviews.

- Customer Success / Support Representative
  - Responsibilities:
    - Provide day-to-day customer feedback and surface customer-impacting issues.
    - Help prioritize customer-impacting bugs and communications for rollouts.
    - Participate in release rollout monitoring and post-release feedback.
  - Interaction:
    - Feeds stakeholder inputs to PdM and PM and supports post-release communications.

---

## Role interaction matrix (quick reference)

- Release timing → Release Manager
- Production incidents → DevOps / SRE
- Security findings → Security Liaison
- UX acceptance or accessibility questions → UX / Product Designer
- Customer-impacting issues & escalations → Customer Success / Support Representative
- Capacity / people decisions → Engineering Manager
- Schedule / external dependencies → Project Manager
- Product decisions / prioritization → Product Manager

---

## How to use this file
- Add the role that most closely matches a responsibility when creating backlog items or ownership fields.
- For cross-cutting tasks (releases, incidents, security), name the responsible persona in the issue/PR to avoid ambiguity.
- When assigning action items from retrospectives, use the Role + Person pattern (e.g., "Release Manager — Alice") where possible.
