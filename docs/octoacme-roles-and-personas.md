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

## Additional Personas

### QA / Test Engineer

#### Role Summary
QA and Test Engineers ensure quality, validate acceptance criteria, and identify defects before release. They collaborate with developers and product managers to define test strategies and maintain quality standards.

#### Responsibilities
- Create and execute test plans aligned with acceptance criteria
- Perform manual and automated testing (unit, integration, end-to-end)
- Report and triage defects with clear reproduction steps
- Define test coverage goals and quality metrics
- Participate in sprint planning to understand scope and design tests
- Conduct smoke tests and regression testing before releases
- Collaborate on Definition of Done to ensure quality gates

#### Goals
- Ensure features meet acceptance criteria and quality standards
- Minimize production defects and customer-impacting issues
- Provide early feedback to developers during development
- Build confidence in releases through comprehensive testing

#### Typical Communication
- Test plans and reports in project documentation
- Daily standup updates on test status
- Bug reports and defect tracking in issue system
- Pre-release sign-off and smoke test results

#### Interaction with Existing Roles
- **Developers:** Review acceptance criteria together, discuss test strategies, resolve defects
- **Product Managers:** Clarify acceptance criteria and test scope
- **Project Managers:** Report on quality metrics and testing readiness for releases

---

### Technical Lead / Engineering Lead

#### Role Summary
Technical Leads provide technical direction, mentor developers, and ensure architectural quality and alignment. They bridge technical execution with product and project management.

#### Responsibilities
- Define technical architecture and design patterns
- Guide developers on implementation approaches and trade-offs
- Conduct technical code reviews and design reviews
- Mentor junior developers and foster technical growth
- Identify technical risks and propose mitigation strategies
- Collaborate with Product Managers on technical feasibility
- Advocate for technical debt reduction and quality improvements

#### Goals
- Deliver technically sound, scalable solutions
- Build team capability and reduce knowledge silos
- Minimize rework and technical debt accumulation
- Enable sustainable pace and code maintainability

#### Typical Communication
- Technical design docs and architecture decisions
- Code review feedback and mentoring conversations
- Technical risk assessments in planning and standups
- Architecture and technical roadmap discussions

#### Interaction with Existing Roles
- **Developers:** Provide guidance, mentoring, and architectural oversight
- **Project Managers:** Flag technical risks and dependencies early
- **Product Managers:** Discuss technical feasibility and trade-offs
- **QA / Test Engineers:** Collaborate on test design and quality strategies

---

### Stakeholder / Business Owner

#### Role Summary
Stakeholders represent business interests, provide approvals, and ensure the project aligns with organizational strategy and goals. They may include business leads, sponsors, or executive sponsors depending on project scope.

#### Responsibilities
- Define business value and success criteria (working with Product Managers)
- Provide or secure budget and resource approval
- Review progress and approve major milestones
- Make go/no-go decisions at key decision gates
- Communicate project impact to their teams and leadership
- Escalate blockers or issues that require organizational decisions
- Participate in kickoff and release announcements

#### Goals
- Ensure project delivers expected business value
- Align project execution with organizational priorities
- Reduce delivery risk and scope creep
- Maintain stakeholder confidence and communication

#### Typical Communication
- Stakeholder briefings and monthly updates
- Decision gate approvals (initiation, planning, release)
- Risk escalations and resource requests
- Announcement of releases and project outcomes

#### Interaction with Existing Roles
- **Project Managers:** Primary escalation point for decisions and resource needs
- **Product Managers:** Collaborate on business value and success metrics
- **Developers:** Indirect communication via PM and Project Manager

---

### Release Manager / Delivery Manager

#### Role Summary
Release Managers coordinate deployment activities, verify readiness, and ensure smooth transitions to production. They work across development, QA, operations, and support teams to manage release execution.

#### Responsibilities
- Create release plans and coordinate deployment schedules
- Verify pre-release requirements (tests passing, approvals obtained, docs ready)
- Orchestrate deployment process across environments (staging, production)
- Document rollback plans and incident procedures
- Coordinate with support and operations on release readiness
- Monitor deployments and verify post-release functionality
- Document release notes and communicate changes to stakeholders

#### Goals
- Execute releases with minimal risk and downtime
- Ensure post-release visibility and quick issue identification
- Reduce deployment cycle time and manual effort
- Maintain runbook and incident playbooks

#### Typical Communication
- Release checklists and deployment plans
- Pre-release readiness reviews with development and QA
- Release notes and deployment instructions
- Post-deployment verification and incident communication

#### Interaction with Existing Roles
- **Developers:** Verify code is ready for deployment, coordinate hotfixes
- **QA / Test Engineers:** Confirm smoke tests and QA sign-off before release
- **Project Managers:** Communicate release status and dependencies
- **Support / Operations:** Coordinate on deployment timing and runbooks

---

### Support / Operations Representative

#### Role Summary
Support and Operations Representatives manage production systems, respond to customer issues, and provide feedback on product stability and usability. They bridge customer needs with product and development teams.

#### Responsibilities
- Monitor production systems and respond to operational incidents
- Triage and escalate customer issues to appropriate teams
- Provide production telemetry and usage data
- Communicate customer feedback to Product Managers
- Participate in post-incident retrospectives and runbook updates
- Document operational procedures and troubleshooting guides
- Support release deployments and post-deployment verification

#### Goals
- Minimize production downtime and customer impact
- Improve mean-time-to-resolution (MTTR) for incidents
- Provide product teams with real-world usage and stability insights
- Build operational resilience and observability

#### Typical Communication
- Incident reports and status updates
- Customer feedback summaries to Product Managers
- Operational metrics and system health dashboards
- Runbook and troubleshooting documentation updates

#### Interaction with Existing Roles
- **Developers:** Report production issues and provide system metrics for debugging
- **Product Managers:** Share customer pain points and usage patterns
- **Project Managers:** Escalate production impacts and operational dependencies
- **Release Manager / Delivery Manager:** Coordinate deployments and rollback procedures

---

### Security / Compliance Reviewer

#### Role Summary
Security and Compliance Reviewers ensure projects meet security, privacy, and regulatory requirements. They conduct reviews, provide guidance on secure design, and manage security incidents.

#### Responsibilities
- Review design and implementation for security risks
- Conduct security assessments and penetration testing (as needed)
- Ensure compliance with regulatory and organizational standards
- Provide security guidance on data handling, encryption, and authentication
- Review and approve security-related changes
- Participate in incident response for security incidents
- Maintain and update security standards and best practices

#### Goals
- Prevent security vulnerabilities and breaches
- Ensure compliance with regulations and organizational policy
- Build secure-by-default practices into development workflows
- Reduce security incidents and data exposure risk

#### Typical Communication
- Security review feedback and recommendations
- Threat assessments and risk evaluations
- Security standards and compliance checklists
- Incident notifications and security advisories

#### Interaction with Existing Roles
- **Developers:** Provide security guidance and code review feedback
- **Technical Leads:** Collaborate on secure architecture decisions
- **Project Managers:** Flag security risks and compliance dependencies
- **QA / Test Engineers:** Coordinate on security testing and penetration testing

---

## Persona Interaction Map

The following diagram illustrates how these personas typically collaborate across key project activities:

| Activity | Primary Owner | Key Collaborators |
|----------|---------------|-------------------|
| **Initiation** | Product Manager, Project Manager | Stakeholder/Business Owner, Technical Lead |
| **Planning** | Project Manager, Product Manager | Technical Lead, QA/Test Engineer, Security Reviewer |
| **Design & Development** | Technical Lead, Developers | QA/Test Engineer, Security Reviewer, Product Manager |
| **Testing & QA** | QA/Test Engineer | Developers, Product Manager |
| **Risk & Issue Escalation** | Project Manager | All roles (depending on type) |
| **Release Preparation** | Release Manager | Developers, QA/Test Engineer, Support/Operations |
| **Deployment** | Release Manager, Operations | Developers, Support/Operations, Security Reviewer |
| **Post-Release & Incident Response** | Support/Operations, Project Manager | Developers, Product Manager, Security Reviewer |
| **Retrospective & Learning** | Project Manager | All roles |

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Persona Interaction Map to understand dependencies and communication flows across project phases.
