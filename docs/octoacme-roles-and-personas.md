# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

### Related Process Templates & Checklists
| Template / Checklist | Owned By |
|---|---|
| [Release Readiness Checklist](./octoacme-release-readiness-checklist.md) | Release Manager |
| [Quality & Test Plan Checklist](./octoacme-quality-test-plan-checklist.md) | QA Lead |
| [Requirements Clarification Template](./octoacme-requirements-clarification-template.md) | Business Analyst |
| [Customer Feedback Intake Template](./octoacme-customer-feedback-intake-template.md) | Customer Advocate |

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Release Manager

### Role Summary
The Release Manager coordinates the end-to-end release process, ensuring features are ready to ship, risks are mitigated, and all stakeholders are informed about release timelines and outcomes.

### Responsibilities
- Own the release calendar and coordinate release windows with Engineering and Operations
- Drive pre-release readiness checks: acceptance criteria, CI status, security scans, and rollback plans
- Communicate release plans, status, and outcomes to all stakeholders
- Maintain and iterate on the release process and runbooks
- Gate releases based on quality and risk thresholds

### Key Deliverables / Artifacts
- [Release Readiness Checklist](./octoacme-release-readiness-checklist.md)
- Release notes and announcement communications
- Post-release incident or rollback summaries (if needed)

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Aligns on release dates and scope; escalates blockers |
| QA Lead | Confirms test sign-off before release gates |
| Engineering Lead / Developers | Coordinates deployment steps and rollback procedures |
| Product Manager | Validates release scope matches product intent |
| Stakeholders | Communicates release timeline and announcements |

### RACI Notes
- **Responsible**: Release Manager owns execution of the release plan
- **Accountable**: Release Manager is accountable for release outcomes
- **Consulted**: QA Lead, Engineering Lead, Product Manager
- **Informed**: All stakeholders, support teams

---

## QA Lead

### Role Summary
The QA Lead defines and oversees the testing strategy for each release. They ensure test plans are executed, quality metrics are tracked and reported, and the team maintains a shared definition of done.

### Responsibilities
- Define the test strategy and acceptance criteria for each release or sprint
- Maintain and evolve the test plan and quality checklist
- Coordinate manual and automated testing activities with developers
- Track and report on quality metrics (defect rates, coverage, test pass rates)
- Sign off on release readiness from a quality perspective

### Key Deliverables / Artifacts
- [Quality & Test Plan Checklist](./octoacme-quality-test-plan-checklist.md)
- Test plans and test case documentation
- Quality metrics reports and dashboards

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Release Manager | Provides test sign-off as a release gate |
| Developers | Collaborates on testability, reviews test coverage, triages defects |
| Project Manager | Reports quality status and risks in weekly syncs |
| Product Manager | Validates acceptance criteria coverage in test plans |

### RACI Notes
- **Responsible**: QA Lead owns the test plan and quality sign-off
- **Accountable**: QA Lead is accountable for quality outcomes
- **Consulted**: Developers, Product Manager, Release Manager
- **Informed**: Project Manager, stakeholders

---

## Business Analyst

### Role Summary
The Business Analyst bridges business objectives and technical delivery. They gather and document requirements, reduce ambiguity in scope, and ensure deliverables map to measurable business goals.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Translate business objectives into clear user stories and acceptance criteria
- Identify and resolve scope ambiguity by facilitating stakeholder discussions
- Maintain a requirements traceability matrix linking deliverables to business goals
- Support Product Manager in backlog refinement and prioritization

### Key Deliverables / Artifacts
- [Requirements Clarification Template](./octoacme-requirements-clarification-template.md)
- Business requirements documents (BRDs) or user story specifications
- Requirements traceability matrix

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Product Manager | Co-defines user stories; supports backlog refinement |
| Project Manager | Informs scope changes and dependency identification |
| Developers | Clarifies requirements and acceptance criteria during planning and sprints |
| Customer Advocate | Incorporates customer feedback into requirements |
| Stakeholders | Primary interface for gathering and validating requirements |

### RACI Notes
- **Responsible**: Business Analyst owns requirements documentation
- **Accountable**: Product Manager is accountable for final scope decisions
- **Consulted**: Developers, Customer Advocate, Stakeholders
- **Informed**: Project Manager, QA Lead, Release Manager

---

## Customer Advocate

### Role Summary
The Customer Advocate represents the voice of the customer throughout the project lifecycle. They collect and synthesize user feedback, review deliverables for end-user impact, and ensure customer needs are reflected in prioritization decisions.

### Responsibilities
- Collect, organize, and synthesize customer feedback from support channels, interviews, and surveys
- Review features and releases from an end-user perspective before shipping
- Communicate customer sentiment and top issues to Product Manager and Business Analyst
- Champion usability and accessibility improvements in design and delivery discussions
- Track resolution of high-priority customer-reported issues

### Key Deliverables / Artifacts
- [Customer Feedback Intake Template](./octoacme-customer-feedback-intake-template.md)
- Customer feedback summaries and prioritized issue lists
- Release impact assessments from the customer perspective

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Product Manager | Provides customer feedback to inform backlog prioritization |
| Business Analyst | Supplies real customer data to validate or refine requirements |
| Release Manager | Reviews releases for end-user communication and impact |
| Project Manager | Escalates critical customer issues that may affect scope or timeline |
| Developers | Communicates customer-reported bugs and usability concerns |

### RACI Notes
- **Responsible**: Customer Advocate owns feedback collection and synthesis
- **Accountable**: Product Manager is accountable for acting on customer feedback
- **Consulted**: Business Analyst, Release Manager, Developers
- **Informed**: Project Manager, QA Lead

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

