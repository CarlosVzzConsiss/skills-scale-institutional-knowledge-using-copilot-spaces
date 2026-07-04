# Process Improvements: Templates & Checklists

This new document contains process templates and checklists to close gaps identified in the OctoAcme process docs. Place supporting artifacts in docs/ to keep them versioned and discoverable.

## Release Readiness Checklist
- [ ] PRs merged and linked to issues with acceptance criteria
- [ ] All CI checks passing
- [ ] Security scan completed and no critical findings
- [ ] Smoke tests defined and executed in staging
- [ ] Rollback plan documented
- [ ] Release notes drafted
- [ ] Stakeholders notified and release window confirmed

## Integration & Handoff Template
- Context / Summary:
- Owner:
- Stakeholders:
- Required environments & data:
- Integration steps:
- Known limitations / caveats:
- Acceptance criteria & validation steps:
- Rollback / mitigation steps:

## Data & Instrumentation Checklist
- [ ] Metrics defined for success (with owners)
- [ ] Events and telemetry instrumented
- [ ] Dashboards created for key metrics
- [ ] Alerts defined for SLO violations
- [ ] Data schema reviewed by Data Engineer

## Security Review Template
- Feature or change:
- Owner:
- Threat model summary (brief):
- Sensitive data involved?
- Third-party dependencies:
- Mitigations / controls:
- Remaining risk / acceptance decision:

## Accessibility Acceptance Snippet
- Accessibility acceptance criteria:
  - Keyboard navigable
  - Semantic markup
  - ARIA roles and labels where required
  - Color contrast meets WCAG AA
  - Screen reader walkthrough complete

## How to use these templates
- Copy the relevant checklist into the project repo under docs/ or in the issue for the work item.
- Assign owners and include these as part of the "Definition of Done" for features that require them.
