# OctoAcme — Role Onboarding & Cross-Team Collaboration

## Purpose
Provide clear guidance for onboarding new team members to specific roles and facilitate effective cross-team collaboration on projects. This document ensures role clarity, smooth hand-offs, and accountability across all project phases.

---

## Role Onboarding Checklist

### For All New Team Members
- [ ] Review the [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [ ] Read the [OctoAcme Roles & Personas](octoacme-roles-and-personas.md) document
- [ ] Understand the project lifecycle phases and key artifacts
- [ ] Meet with Project Manager to understand current projects and priorities
- [ ] Get access to project boards, repositories, and communication channels
- [ ] Review the team's communication cadence and meeting schedule
- [ ] Identify your role's key stakeholders and interaction points

### Role-Specific Onboarding

#### Business Analyst
- [ ] Review existing requirements documents and user stories in the backlog
- [ ] Shadow requirements gathering sessions with Product Managers
- [ ] Understand the current business process documentation and workflows
- [ ] Meet with key stakeholders to understand their needs and pain points
- [ ] Review acceptance criteria templates and standards
- [ ] Familiarize yourself with the organization's business domain and terminology

#### UX Designer
- [ ] Review the design system and style guides
- [ ] Access design tools (Figma, Sketch, etc.) and asset repositories
- [ ] Review existing user research and persona documentation
- [ ] Shadow usability testing sessions
- [ ] Understand the design review and approval process
- [ ] Meet with Product Managers and Developers to understand current design needs
- [ ] Review accessibility standards and requirements

#### Quality Assurance Lead
- [ ] Review the test strategy and QA processes
- [ ] Access test automation frameworks and tools
- [ ] Review the bug tracking system and defect management process
- [ ] Understand the Definition of Done and acceptance criteria standards
- [ ] Review test coverage reports and quality metrics
- [ ] Shadow release readiness reviews
- [ ] Meet with DevOps Engineers to understand test environment setup

#### DevOps Engineer
- [ ] Review the CI/CD pipeline architecture and configuration
- [ ] Get access to infrastructure management tools and cloud platforms
- [ ] Review monitoring, logging, and alerting systems
- [ ] Understand the deployment process and release schedule
- [ ] Review infrastructure as code repositories
- [ ] Shadow a production deployment
- [ ] Meet with security team to understand compliance requirements

#### Developer
- [ ] Clone repositories and set up local development environment
- [ ] Review coding standards and PR guidelines
- [ ] Access CI/CD pipelines and understand the build process
- [ ] Review the architecture documentation and technical design docs
- [ ] Complete a starter task or bug fix to practice the workflow
- [ ] Shadow code reviews and learn the review culture
- [ ] Meet with senior developers for technical onboarding

#### Product Manager
- [ ] Review the product roadmap and current priorities
- [ ] Access analytics tools and dashboards
- [ ] Review customer feedback channels and research repositories
- [ ] Meet with stakeholders and understand their goals
- [ ] Review the backlog and understand prioritization criteria
- [ ] Shadow customer interviews or user research sessions
- [ ] Understand success metrics and OKRs

#### Project Manager
- [ ] Review active projects and their status
- [ ] Access project management tools and boards
- [ ] Review risk registers and issue logs
- [ ] Understand the escalation process and stakeholder communication plan
- [ ] Shadow project status meetings and retrospectives
- [ ] Review project templates and documentation standards
- [ ] Meet with all team leads to understand team dynamics

---

## Cross-Team Collaboration Guidelines

### Project Kickoff Responsibilities

When starting a new project, ensure all key roles are represented and aligned:

**Project Manager**
- Schedule and facilitate the kickoff meeting
- Ensure all stakeholders and team members are invited
- Prepare the project charter or one-pager
- Document decisions and action items

**Product Manager**
- Present the problem statement and business goals
- Define success metrics and expected outcomes
- Provide context on customer needs and market conditions
- Clarify product vision and priorities

**Business Analyst**
- Confirm stakeholder list is complete
- Outline initial requirements gathering approach
- Identify open questions and clarification needs
- Propose requirements documentation structure

**UX Designer**
- Outline design approach and deliverables
- Identify user research needs
- Clarify design review touchpoints
- Highlight accessibility and usability considerations

**Quality Assurance Lead**
- Outline test strategy and approach
- Identify testability requirements
- Clarify acceptance criteria expectations
- Define release quality gates

**DevOps Engineer**
- Outline deployment approach and infrastructure needs
- Identify environment requirements
- Clarify CI/CD integration points
- Highlight security and compliance considerations

**Developers**
- Ask clarifying questions on technical scope
- Provide initial feasibility feedback
- Identify technical dependencies and risks
- Propose technical approach or architecture options

---

## Responsibility Matrix (RACI)

Use this matrix to clarify ownership and accountability across key project activities. Roles: **R** = Responsible (does the work), **A** = Accountable (final decision), **C** = Consulted (provides input), **I** = Informed (kept updated).

| Activity | PM | PdM | Dev | BA | UX | QA | DevOps |
|----------|----|----|-----|----|----|----|----|
| Define problem statement | C | A | I | C | C | I | I |
| Gather requirements | C | C | I | A/R | C | C | I |
| Design user experience | I | C | C | C | A/R | C | I |
| Develop features | C | C | A/R | C | C | C | C |
| Write acceptance criteria | C | C | C | R | C | A/R | I |
| Test strategy & execution | C | I | C | I | C | A/R | C |
| Code review | I | I | A/R | I | I | C | C |
| CI/CD pipeline setup | I | I | C | I | I | C | A/R |
| Deployment execution | R | I | C | I | I | C | A/R |
| Release decision | A/R | C | I | I | I | C | I |
| Risk management | A/R | C | C | C | C | C | C |
| Stakeholder communication | A/R | R | I | C | I | I | I |
| Retrospective facilitation | A/R | C | R | R | R | R | R |

**Notes:**
- Multiple roles can be Responsible for collaborative activities
- Only one role should be Accountable for each activity
- Adjust based on your team structure and project needs

---

## Hand-off Protocols

### Requirements to Design
**From**: Business Analyst  
**To**: UX Designer  
**Hand-off includes**:
- Documented user stories with acceptance criteria
- Business process flows and use cases
- Stakeholder validation notes
- Constraints and non-functional requirements

**Success criteria**: UX Designer confirms requirements are clear and sufficient to begin design work.

---

### Design to Development
**From**: UX Designer  
**To**: Developers  
**Hand-off includes**:
- Finalized wireframes and mockups
- Design specifications and asset files
- Interaction patterns and navigation flows
- Accessibility requirements

**Success criteria**: Developers confirm they have all assets and specifications needed to implement the design.

---

### Development to QA
**From**: Developers  
**To**: Quality Assurance Lead  
**Hand-off includes**:
- Completed feature implementation
- Unit tests and test documentation
- Acceptance criteria verification
- Known issues or limitations

**Success criteria**: QA Lead confirms the feature is ready for testing and meets DoD for QA phase.

---

### QA to Deployment
**From**: Quality Assurance Lead  
**To**: DevOps Engineer  
**Hand-off includes**:
- Test results and defect status
- Release readiness sign-off
- Smoke test plan for production
- Rollback criteria and conditions

**Success criteria**: DevOps Engineer confirms release package is ready and meets quality gates.

---

## Common Collaboration Challenges & Solutions

### Challenge: Unclear Requirements
**Symptoms**: Frequent clarification requests, rework, missed acceptance criteria  
**Solution**:
- Business Analyst schedules requirements review with PM, PdM, and key stakeholders
- Use the "Three Amigos" meeting (BA, Dev, QA) to validate stories before sprint
- Adopt a requirements checklist to ensure completeness

### Challenge: Design-Development Misalignment
**Symptoms**: Implementation doesn't match designs, late design changes  
**Solution**:
- UX Designer conducts design handoff sessions with Developers
- Use design review checkpoints at wireframe and high-fidelity stages
- Developers flag technical constraints early in the design process

### Challenge: Late Quality Issues
**Symptoms**: Bugs found in production, missed acceptance criteria  
**Solution**:
- QA Lead participates in requirements and design reviews to catch testability issues
- Developers and QA collaborate on test automation during development
- Implement shift-left testing practices

### Challenge: Deployment Delays
**Symptoms**: Last-minute environment issues, failed deployments  
**Solution**:
- DevOps Engineer participates in planning to identify infrastructure needs early
- Establish regular deployment rehearsals in staging environments
- Maintain deployment runbooks and rollback procedures

### Challenge: Communication Gaps
**Symptoms**: Missed hand-offs, duplicated work, conflicting assumptions  
**Solution**:
- Project Manager facilitates regular cross-functional sync meetings
- Use the responsibility matrix (RACI) to clarify ownership
- Document decisions in a shared location (wiki, project board, etc.)

---

## Cross-Functional Meeting Templates

### Three Amigos Meeting (Story Refinement)
**Participants**: Business Analyst, Developer, Quality Assurance Lead  
**Duration**: 30 minutes  
**Agenda**:
1. Review user story and business context
2. Discuss acceptance criteria and edge cases
3. Identify test scenarios and validation approach
4. Clarify technical approach and constraints
5. Confirm story is ready for sprint planning

### Design Review
**Participants**: UX Designer, Product Manager, Business Analyst, Developer (optional)  
**Duration**: 45 minutes  
**Agenda**:
1. Present design rationale and user research insights
2. Walk through user flows and key interactions
3. Discuss accessibility and usability considerations
4. Gather feedback and identify action items
5. Confirm next steps and approval process

### Release Readiness Review
**Participants**: Project Manager, QA Lead, DevOps Engineer, Product Manager  
**Duration**: 30 minutes  
**Agenda**:
1. Review test results and defect status
2. Validate acceptance criteria are met
3. Confirm deployment plan and rollback procedures
4. Review monitoring and observability readiness
5. Make go/no-go decision

---

## Quick Reference: Who to Contact

| Need | Contact |
|------|---------|
| Clarify business requirements | Business Analyst |
| Prioritize features or scope | Product Manager |
| Coordinate timeline or resources | Project Manager |
| Review design or user experience | UX Designer |
| Discuss technical implementation | Developer |
| Validate quality or test coverage | Quality Assurance Lead |
| Deploy or troubleshoot infrastructure | DevOps Engineer |

---

## Best Practices for Collaboration

1. **Over-communicate early**: Share context, constraints, and assumptions upfront to prevent rework.
2. **Use the RACI matrix**: When in doubt about ownership, refer to the responsibility matrix.
3. **Document decisions**: Capture key decisions and rationale in a shared location.
4. **Respect hand-off protocols**: Complete your deliverables before passing to the next role.
5. **Ask questions**: If something is unclear, ask early rather than making assumptions.
6. **Provide feedback constructively**: Focus on solutions and improvements, not blame.
7. **Celebrate successes**: Recognize cross-team collaboration wins in retrospectives.

---

**Questions?** Reach out to your Project Manager or consult the [OctoAcme Roles & Personas](octoacme-roles-and-personas.md) document for role-specific guidance.
