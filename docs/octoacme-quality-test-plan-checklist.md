# OctoAcme — Quality & Test Plan Checklist

**Owner:** [QA Lead](./octoacme-roles-and-personas.md#qa-lead)

Use this checklist when planning or executing a testing cycle for a sprint or release. Copy it into the relevant issue or PR to track test progress and provide a quality sign-off record.

---

## 1. Test Planning

- [ ] Test scope defined: features, user flows, and acceptance criteria to be tested
- [ ] Test cases created or updated in the test management tool
- [ ] Regression scope identified (areas at risk from recent changes)
- [ ] Test environments provisioned and verified
- [ ] Test data prepared

## 2. Test Execution

- [ ] Unit tests pass (coverage meets team threshold)
- [ ] Integration tests pass
- [ ] End-to-end / acceptance tests pass
- [ ] Regression suite executed and results reviewed
- [ ] Performance / load tests run (if applicable for this release)
- [ ] Security tests run (SAST, DAST, dependency scan)
- [ ] Accessibility tests run (if applicable)

## 3. Defect Management

- [ ] All defects logged with severity and priority
- [ ] P0/P1 defects resolved or have an approved exception
- [ ] Defect trends reviewed with team (new vs. resolved)
- [ ] Known issues documented in release notes

## 4. Quality Metrics

| Metric | Target | Actual |
|---|---|---|
| Unit test coverage | ≥ 80% | |
| Open P0/P1 defects at release | 0 | |
| Regression pass rate | ≥ 95% | |
| Test cases executed | 100% | |

## 5. Sign-Off

- [ ] QA Lead reviewed all test results
- [ ] Acceptance criteria for all in-scope features verified
- [ ] QA Lead sign-off given to Release Manager

| Field | Value |
|---|---|
| QA Lead | |
| Sign-off date | |
| Release / Sprint | |
| Outstanding risks | |

---

_See also: [Release Readiness Checklist](./octoacme-release-readiness-checklist.md) · [Roles & Personas](./octoacme-roles-and-personas.md)_
