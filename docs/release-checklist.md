# Release & Deployment Checklist (OctoAcme)

Purpose: A concise checklist to standardize releases, reduce risk, and ensure the right stakeholders are notified.

Pre-release (planning)
- [ ] Release scope confirmed and linked to issues/epics
- [ ] Release Manager assigned and communicated
- [ ] Stakeholders and Customer Success informed of planned window
- [ ] Rollback/mitigation plan documented
- [ ] Release train ticket / milestone created (if applicable)

Pre-deploy (staging)
- [ ] All PRs merged for the release and passing CI
- [ ] Automated tests (unit / integration) passing
- [ ] Security scans completed and high-priority findings addressed
- [ ] Migration steps documented and dry-run verified (if applicable)
- [ ] Staging deploy completed and smoke tests run and signed off by QA

Deploy (production)
- [ ] Deployment executed through CI/CD pipeline or documented manual steps
- [ ] Post-deploy smoke tests executed and results recorded
- [ ] Monitoring dashboards / alerts verified
- [ ] Release Manager confirms successful deploy or triggers rollback if needed

Post-release
- [ ] Customer Success / Support notified of release and relevant notes
- [ ] Stakeholder announcement published (release notes / summary)
- [ ] Roll-forward actions / improvements captured as issues
- [ ] Post-release verification logged (metrics, incidents, user reports)

Notes:
- For patch/hotfix releases, follow a scaled-down checklist focusing on scope, quick validation, and rollback readiness.
- Keep the release checklist in the release PR description for traceability.
