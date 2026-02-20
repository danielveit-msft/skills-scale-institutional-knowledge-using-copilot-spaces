# OctoAcme — Release Readiness Checklist

**Owner:** [Release Manager](./octoacme-roles-and-personas.md#release-manager)

Use this checklist before every release to confirm all teams are aligned and the release is ready to proceed. Copy this checklist into the release PR or issue for tracking.

---

## 1. Scope & Code Readiness

- [ ] All planned features and fixes are merged and verified in the target branch
- [ ] No P0/P1 (critical/blocker) defects are open
- [ ] Release notes drafted and reviewed by Product Manager
- [ ] Release branch or tag created

## 2. Quality Sign-Off

- [ ] QA Lead has signed off on test completion (see [Quality & Test Plan Checklist](./octoacme-quality-test-plan-checklist.md))
- [ ] Automated test suite passes in CI
- [ ] Security scans completed and no unresolved high/critical findings
- [ ] Accessibility checks completed (if applicable)

## 3. Deployment & Operations

- [ ] Deployment window scheduled and communicated to stakeholders
- [ ] Staging deployment verified with smoke tests
- [ ] Rollback / mitigation plan documented and reviewed
- [ ] On-call coverage confirmed for the deployment window
- [ ] Database migrations (if any) tested and reversible

## 4. Stakeholder Communication

- [ ] Release announcement drafted and approved
- [ ] Support team briefed on new features and known issues
- [ ] Internal teams (sales, customer success, etc.) notified
- [ ] Customer-facing documentation updated (if needed)

## 5. Post-Release

- [ ] Post-deploy verifications complete
- [ ] Monitoring dashboards reviewed (no anomalies)
- [ ] Release announcement sent
- [ ] Release retrospective scheduled (if major release)

---

## Release Metadata

| Field | Value |
|---|---|
| Release name / version | |
| Target release date | |
| Release Manager | |
| QA Sign-off | |
| Deployment environment | |

---

_See also: [OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md) · [Roles & Personas](./octoacme-roles-and-personas.md)_
