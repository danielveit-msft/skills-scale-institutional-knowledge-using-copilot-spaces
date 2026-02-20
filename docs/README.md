# OctoAcme Project Management Docs

This README serves as the central index and onboarding guide for all of OctoAcme's project management process documentation. The goal of this Copilot Space is to centralize project management knowledge, make it searchable and version-controlled, and improve onboarding and consistency for both new and existing team members.

## Project Management Processes Overview

**Initiation & Planning:** Every OctoAcme project begins with a lightweight Project One-pager that captures the problem statement, SMART objectives, success metrics, stakeholders, and a high-level timeline. A decision gate confirms stakeholder alignment and team availability before moving into planning. During planning, the delivery team holds a kickoff meeting, creates a prioritized backlog with acceptance criteria, defines the Definition of Done, identifies dependencies, and produces a release plan and milestone map.

**Execution & Tracking:** Day-to-day delivery follows a structured team rhythm: daily standups, weekly delivery syncs, and sprint demos. Work is managed on a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done). Pull requests are kept small (≤ 400 lines where possible), must link to their issue, and require passing CI (automated tests, linting, security scanning) plus at least one approval before merging. Quality is maintained through unit, integration, and end-to-end smoke tests; velocity and burndown are tracked against the success metrics established at initiation.

**Risk Management & Communication:** Risks are captured in a Risk Register (ID, description, impact, likelihood, owner, mitigation, status) and reviewed at weekly syncs. Stakeholder communication follows a regular cadence—weekly PM/PdM syncs, twice-weekly team standups, and monthly stakeholder updates—using a single source of truth for project status. Escalation paths run from team-level triage through the PM and Product Lead up to the Sponsor for business-impacting issues.

**Release, Retrospective & Continuous Improvement:** Releases are categorized as patch, minor, or major and require all acceptance criteria to be met, CI and security scans to pass, release notes drafted, and a rollback plan in place before deployment. After each sprint, release, or significant milestone, the team runs a structured retrospective (what went well, what to improve, action items with owners and due dates). Action items feed back into the backlog, and their impact is measured to sustain a culture of small, iterative improvement.

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and the project lifecycle at a glance |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize work, align stakeholders, and create a lightweight plan |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into an actionable backlog and release plan |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day workflows, PR conventions, quality practices, and escalation paths |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, communication cadence, templates, and escalation paths |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklist, and rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, tracking improvements, and continuous improvement culture |
| [Roles and Personas](octoacme-roles-and-personas.md) | Definitions and responsibilities for Developers, Product Managers, and Project Managers |

---

Feel free to suggest improvements or request additions using the [issue template](https://github.com/danielveit-msft/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new).
