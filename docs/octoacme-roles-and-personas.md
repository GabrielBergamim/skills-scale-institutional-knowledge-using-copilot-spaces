# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

### Interactions with Other Roles
- **Product Managers**: Collaborates on translating requirements into technical solutions; provides effort estimates and feasibility feedback
- **Project Managers**: Participates in planning and estimation; reports progress and identifies blockers
- **Business Analyst**: Seeks clarification on requirements and business rules; validates technical approach
- **UX Designer**: Implements designs and provides feedback on technical constraints or opportunities
- **Quality Assurance Lead**: Writes testable code and supports test automation; fixes defects and improves quality
- **DevOps Engineer**: Collaborates on CI/CD pipelines, deployment strategies, and infrastructure needs

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

### Interactions with Other Roles
- **Developers**: Defines what to build and validates solutions; provides acceptance criteria and prioritizes backlog
- **Project Managers**: Aligns on roadmap and priorities; collaborates on scope and timeline trade-offs
- **Business Analyst**: Provides business context and validates requirements alignment with product vision
- **UX Designer**: Collaborates on user journeys and feature specifications; validates design alignment with product goals
- **Quality Assurance Lead**: Defines quality expectations and acceptance criteria; reviews release readiness
- **DevOps Engineer**: Reviews observability data and metrics to inform product decisions

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

### Interactions with Other Roles
- **Product Managers**: Aligns on priorities, scope, and timeline; collaborates on stakeholder management
- **Developers**: Coordinates delivery timelines and removes blockers; facilitates planning and retrospectives
- **Business Analyst**: Supports requirements gathering and scope definition; tracks requirement changes
- **UX Designer**: Integrates design activities into project timeline; ensures design handoffs are on schedule
- **Quality Assurance Lead**: Coordinates testing activities and release readiness; manages quality risks
- **DevOps Engineer**: Schedules deployments and coordinates release activities; manages infrastructure dependencies

---

## Business Analyst

### Role Summary
Business Analysts bridge stakeholder needs and technical implementation. They gather requirements, analyze business processes, and translate feedback into actionable tasks that developers and project managers can execute.

### Responsibilities
- Gather and document business requirements from stakeholders
- Analyze current processes and identify improvement opportunities
- Translate stakeholder feedback into user stories and acceptance criteria
- Create process flows, data models, and functional specifications
- Facilitate requirements workshops and validate solutions with stakeholders

### Goals
- Ensure requirements are clear, complete, and testable
- Minimize rework by catching ambiguities early
- Bridge communication gaps between business and technical teams

### Typical Communication
- Requirements review sessions with Product Managers
- Clarification meetings with Developers
- Progress tracking with Project Managers
- Stakeholder validation workshops

### Interactions with Other Roles
- **Product Managers**: Collaborates on defining features and success metrics; validates that requirements align with product vision
- **Developers**: Provides clarifications on business rules and acceptance criteria; reviews technical solutions for business fit
- **Project Managers**: Supports effort estimation and timeline planning; flags requirement changes that impact scope
- **Quality Assurance Lead**: Defines test scenarios based on business requirements; validates acceptance criteria completeness

---

## UX Designer

### Role Summary
UX Designers create intuitive, user-centered experiences. They design interfaces, conduct user research, and ensure that products meet usability standards and delight users.

### Responsibilities
- Design user interfaces, wireframes, and interactive prototypes
- Conduct user research, usability testing, and gather feedback
- Create design systems and maintain consistency across products
- Collaborate on accessibility and inclusive design practices
- Validate designs with users and iterate based on insights

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support adoption
- Ensure design consistency and brand alignment

### Typical Communication
- Design reviews with Product Managers and stakeholders
- Handoff sessions with Developers
- Usability testing feedback sessions
- Design critique meetings with peers

### Interactions with Other Roles
- **Product Managers**: Collaborates on feature specifications and user journeys; validates designs against product goals
- **Developers**: Provides design assets and specifications; works together on feasibility and implementation details
- **Quality Assurance Lead**: Defines usability acceptance criteria; participates in testing to validate user experience
- **Business Analyst**: Aligns designs with business processes and user workflows

---

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads own the test strategy and ensure that deliverables meet acceptance criteria and quality standards. They coordinate QA activities, track defects, and validate release readiness.

### Responsibilities
- Define and maintain the overall test strategy and QA processes
- Coordinate testing activities across unit, integration, and end-to-end tests
- Track defects, prioritize fixes, and verify resolutions
- Ensure acceptance criteria are testable and met before release
- Validate release readiness and sign off on deployments

### Goals
- Minimize production defects and customer-impacting issues
- Ensure comprehensive test coverage for critical flows
- Maintain high quality standards across all releases

### Typical Communication
- Test planning sessions with Developers and Project Managers
- Defect triage meetings
- Release readiness reviews with stakeholders
- Post-release quality retrospectives

### Interactions with Other Roles
- **Developers**: Collaborates on test automation and defect fixes; reviews code changes for testability
- **Project Managers**: Provides quality metrics and release readiness status; escalates quality risks
- **UX Designer**: Validates usability and accessibility requirements; conducts user acceptance testing
- **DevOps Engineer**: Coordinates test environment setup; validates deployment quality in staging
- **Product Managers**: Validates that acceptance criteria reflect quality expectations; provides feedback on feature readiness

---

## DevOps Engineer

### Role Summary
DevOps Engineers enable reliable, efficient software delivery by managing CI/CD pipelines, infrastructure, and deployment automation. They ensure system reliability, observability, and rapid feedback loops.

### Responsibilities
- Design and maintain CI/CD pipelines for automated builds, tests, and deployments
- Manage infrastructure as code and environment configurations
- Monitor system health, performance, and security
- Automate deployment processes and rollback procedures
- Ensure observability through logging, metrics, and alerting

### Goals
- Minimize deployment time and manual intervention
- Maximize system uptime and reliability
- Enable rapid, safe releases with automated quality gates

### Typical Communication
- Infrastructure planning with Developers and architects
- Deployment coordination with Project Managers
- Incident response and post-mortems
- Security and compliance reviews

### Interactions with Other Roles
- **Developers**: Provides build and test automation support; collaborates on deployment strategies and troubleshooting
- **Project Managers**: Coordinates release schedules and deployment windows; communicates infrastructure constraints
- **Quality Assurance Lead**: Sets up test environments and automation infrastructure; ensures quality gates in CI/CD
- **Product Managers**: Provides observability data for feature usage and performance metrics

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

