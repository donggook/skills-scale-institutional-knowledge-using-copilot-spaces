# OctoAcme Cross-Functional Handoff Checklist

Use this checklist to ensure smooth handoffs between personas and project phases.

## Planning → Development Handoff

- [ ] Acceptance criteria clearly defined and agreed by PdM + Developers
- [ ] Design specs or wireframes reviewed by UX + Developers + PM
- [ ] Dependency map created and communicated (e.g., API integrations, data requirements)
- [ ] Data Analyst identified tracking requirements (events, metrics, dashboards)
- [ ] DevOps confirmed environment requirements and CI/CD readiness
- [ ] Technical Writer notified of new features for documentation planning
- [ ] QA provided with test scenarios and acceptance criteria
- [ ] Risk register updated with technical and dependency risks
- [ ] Resource allocation confirmed (developers, QA, DevOps capacity)

## Development → Testing Handoff

- [ ] All acceptance criteria implemented and code reviewed
- [ ] CI pipeline passing (tests, linting, security scans)
- [ ] Feature branch deployed to staging environment
- [ ] QA provided with a summary of changes, test scenarios, and known limitations
- [ ] Data Analyst confirmed instrumentation is in place
- [ ] DevOps confirmed staging environment is stable
- [ ] Technical Writer confirmed documentation draft is available for review
- [ ] Release notes template updated with feature summary

## Testing → Deployment Handoff

- [ ] All acceptance criteria verified and signed off by QA
- [ ] No critical or high-priority bugs outstanding
- [ ] Smoke tests and integration tests passing
- [ ] Rollback plan documented by DevOps
- [ ] Release notes finalized
- [ ] Customer Support briefed on new features and known issues
- [ ] Deployment window scheduled and stakeholders notified
- [ ] DevOps confirmed production environment is ready
- [ ] Post-deployment monitoring plan confirmed (DevOps + Data Analyst)

## Deployment → Release Communication Handoff

- [ ] Deployment completed successfully by DevOps
- [ ] Post-deploy smoke tests passing
- [ ] Customer Support ready to handle incoming questions
- [ ] Release announcement ready (internal and external)
- [ ] Knowledge base / documentation live and accessible
- [ ] Metrics dashboard configured for monitoring adoption and issues
- [ ] Status page updated (if applicable)
- [ ] Incident contact information and escalation path confirmed

## Post-Release → Retrospective Handoff

- [ ] Deployment metrics captured (time, success rate, rollback incidents)
- [ ] Customer Support feedback on issue volume and types compiled
- [ ] Data Analyst report on key metrics and early adoption trends
- [ ] DevOps incident log and response times documented
- [ ] Product Manager assessment of feature adoption and customer feedback
- [ ] Retrospective scheduled within 1 week of release or milestone completion
- [ ] All team members invited and agenda shared in advance

## Ongoing: Communication & Escalation

- [ ] Risks and blockers raised immediately in daily standups
- [ ] Escalation path known: Team → PM → Product Lead → Sponsor
- [ ] Weekly status updates sent to stakeholders
- [ ] Decision log updated with key trade-offs and approvals
- [ ] Retrospective action items tracked with clear owners and due dates