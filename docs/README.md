# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs! This folder contains comprehensive guides and best practices for delivering projects at OctoAcme. Whether you're a new team member or an experienced contributor, these docs will help you understand our workflows, roles, and quality standards.

## About OctoAcme Project Management

OctoAcme follows an **iterative delivery model** that prioritizes customer value, clear ownership, and data-informed decisions. Our project lifecycle spans from initiation through retrospective, with each phase guided by well-defined artifacts and communication cadences. Projects are led by a **Project Manager (PM)** who coordinates delivery, schedules, and risk management, working closely with a **Product Manager (PdM)** who defines outcomes and prioritizes the backlog. Developers and QA teams collaborate throughout to build, test, and deliver high-quality features in small, testable increments.

Our **key workflows** emphasize transparency and quality: we use GitHub Projects to track work through defined stages (Backlog → Ready → In Progress → In Review → QA → Done), enforce small pull requests with automated CI checks, and require peer reviews before merging. Each project maintains essential artifacts including a project charter, roadmap, risk register, and release checklist. We hold regular standups (twice weekly or as agreed), weekly PM/PdM syncs, and monthly stakeholder updates to maintain alignment and quickly surface blockers.

**Communication and risk management** are central to our process. Teams maintain a risk register that captures identified risks with their impact, likelihood, mitigation plans, and ownership. Escalation paths are clearly defined, moving from team-level triage through PM and Product Lead to sponsor-level decisions when needed. We use standardized templates for weekly status updates and incident communications to ensure consistency and clarity across all stakeholder groups.

**Quality assurance practices** are embedded throughout our delivery process. We require unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. Security scanning runs automatically in CI, and we perform manual QA for feature acceptance when needed. Before any release, teams must complete a deployment checklist that includes smoke tests in staging, rollback plans, and post-deploy verifications. This comprehensive approach to quality, combined with our emphasis on psychological safety and learning through retrospectives, enables OctoAcme to deliver reliable, customer-focused solutions iteratively and sustainably.

## Process Documentation Index

Explore our project management process guides:

- [**OctoAcme Project Management Overview**](octoacme-project-management-overview.md) — High-level introduction to principles, roles, artifacts, and lifecycle
- [**OctoAcme Roles & Personas**](octoacme-roles-and-personas.md) — Definitions of key roles (PM, PdM, Developers, BA, UX, QA, DevOps) and their responsibilities
- [**OctoAcme Role Onboarding & Cross-Team Collaboration**](octoacme-role-onboarding-and-collaboration.md) — Onboarding checklists, responsibility matrix, and hand-off protocols for effective collaboration
- [**OctoAcme Project Initiation**](octoacme-project-initiation.md) — Guidance for starting new projects with clear problem statements and stakeholder alignment
- [**OctoAcme Project Planning**](octoacme-project-planning.md) — Turn initiatives into actionable plans with prioritized backlogs and release timelines
- [**OctoAcme Execution & Tracking**](octoacme-execution-and-tracking.md) — Day-to-day execution, PR workflows, quality practices, and progress tracking
- [**OctoAcme Risk Management & Communication**](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies effectively
- [**OctoAcme Release & Deployment**](octoacme-release-and-deployment.md) — Standardized release processes, deployment checklists, and rollback procedures
- [**OctoAcme Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive ongoing process enhancements

## How to Use These Docs

### For Project Teams
- **Reference the main project README**: Keep your project-specific charter and status updated in your repository's main README. Link to these process docs for detailed guidance on specific phases.
- **Add context for Copilot Spaces**: Copy relevant process docs into your project's `.copilot/` directory to give GitHub Copilot Spaces additional context about OctoAcme's methodologies and help it provide more tailored guidance.
- **Follow the lifecycle**: Use these docs as checkpoints through your project journey—from initiation and planning through execution, release, and retrospective.

### Contributing & Updates
Found a gap or have a suggestion? We welcome contributions to improve these docs!

- **Use the issue template**: Create a new issue using [`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose additions or updates.
- **Review the acceptance criteria**: Ensure your proposed changes:
  - ✓ Align with existing process docs
  - ✓ Improve clarity or close a documented gap
  - ✓ Have been reviewed with stakeholders (if needed)
- **Submit a pull request**: Follow our standard PR workflow with clear descriptions and link to the related issue.

## Acceptance Criteria

When contributing to or reviewing updates to these docs, verify:

- [ ] Content aligns with existing process docs
- [ ] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)

---

**Questions?** Reach out to your Project Manager or Product Lead for guidance on applying these processes to your specific project.
