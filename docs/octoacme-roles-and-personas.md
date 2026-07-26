# OctoAcme Personas

This document defines roles and responsibilities used in OctoAcme projects. It includes both **core personas** that are essential to every project and **extended personas** that provide specialized capabilities as needed.

---

## Core Personas

These three personas are present in most OctoAcme projects and form the foundation of our delivery model.

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Extended Personas

These personas provide specialized capabilities and are included in projects based on specific needs. They collaborate closely with core personas to ensure quality, security, and successful delivery.

### QA/Testing Lead

#### Role Summary
QA/Testing Leads own the quality strategy for a project, define testing approaches, and ensure acceptance criteria are validated before release. They collaborate with Product Managers on requirements clarity and with Developers on test implementation.

#### Responsibilities
- Define test strategy and testing approach (unit, integration, end-to-end, user acceptance)
- Create test plans and acceptance criteria validation checklists
- Conduct manual QA testing for feature acceptance
- Coordinate with Developers on test coverage and quality gates
- Participate in Definition of Done reviews
- Triage and prioritize bugs and quality issues
- Ensure compliance with quality standards before release

#### Goals
- Deliver high-quality features that meet acceptance criteria
- Minimize defects in production
- Provide confidence in release readiness

#### Interaction with Existing Roles
- **Product Managers**: Align on acceptance criteria and quality expectations
- **Developers**: Collaborate on test design, coverage, and quality gates
- **Project Managers**: Report on quality metrics and blockers during standups

#### Typical Communication
- Quality metrics in weekly standups
- Test plan reviews with Product and Dev teams
- Bug triage and prioritization discussions
- Quality gate sign-offs before release

---

### Technical Architect

#### Role Summary
Technical Architects lead technical design decisions, ensure solutions are scalable and maintainable, and identify technical risks that could impact project success. They work with Developers to validate implementation approaches and with Project Managers to surface architectural risks.

#### Responsibilities
- Lead technical design and architecture decisions
- Review design proposals and implementation approaches
- Identify technical risks, dependencies, and scalability concerns
- Ensure adherence to technical standards and best practices
- Collaborate on trade-off analysis between technical and business needs
- Provide technical guidance to the development team
- Document architectural decisions and rationale

#### Goals
- Ensure scalable, maintainable, and reliable technical solutions
- Reduce technical debt and rework
- Enable sustainable team velocity

#### Interaction with Existing Roles
- **Developers**: Guide technical implementation and validate design decisions
- **Product Managers**: Inform feasibility and trade-off analysis
- **Project Managers**: Surface technical risks and dependencies

#### Typical Communication
- Technical design reviews
- Architecture decision records (ADRs)
- Risk identification during planning
- Code review participation for complex changes

---

### Stakeholder/Sponsor

#### Role Summary
Stakeholders and Sponsors provide business context, strategic alignment, and approvals for projects. They remove organizational blockers and ensure projects align with business priorities and resource constraints.

#### Responsibilities
- Define business context and strategic objectives
- Approve project charter and resource allocation
- Remove organizational blockers and dependencies
- Provide periodic reviews and decision-making
- Communicate project importance and priority to the organization
- Validate business outcomes and success metrics
- Escalate unresolved issues to executive leadership

#### Goals
- Ensure projects deliver business value
- Maintain alignment with organizational strategy
- Enable effective resource allocation

#### Interaction with Existing Roles
- **Project Managers**: Receive regular status updates and escalations
- **Product Managers**: Align on business priorities and success metrics
- **Development Team**: Provide context during kickoffs and demos

#### Typical Communication
- Monthly stakeholder updates
- Project kickoff and approval meetings
- Escalation path for blockers
- Release announcements and retrospectives

---

### Scrum Master / Agile Coach

#### Role Summary
Scrum Masters facilitate team ceremonies, remove process impediments, and coach teams on Agile best practices. They work with Project Managers to maintain process discipline and with the team to optimize workflow.

#### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Identify and help remove process blockers and impediments
- Coach team on Agile practices and continuous improvement
- Maintain sprint board and burndown visibility
- Protect team from scope creep and external distractions
- Escalate organizational impediments to Project Manager
- Track and encourage team velocity improvements

#### Goals
- Maintain team efficiency and predictability
- Enable continuous process improvement
- Foster psychological safety and team autonomy

#### Interaction with Existing Roles
- **Project Managers**: Coordinate on impediments and escalations
- **Development Team**: Facilitate ceremonies and coach on practices
- **Product Managers**: Ensure backlog is ready for sprint planning

#### Typical Communication
- Daily standup facilitation
- Retrospective hosting and action tracking
- Impediment escalations to Project Manager
- Metrics and velocity reporting

---

### Security / Compliance Officer

#### Role Summary
Security and Compliance Officers ensure projects meet security requirements, comply with regulatory standards, and follow organizational security policies. They collaborate with Architects and Developers to embed security throughout the project lifecycle.

#### Responsibilities
- Define security and compliance requirements
- Participate in technical design reviews for security implications
- Coordinate security scanning and vulnerability assessments
- Review acceptance criteria for security-related features
- Conduct security training and awareness for teams
- Manage incident response and post-incident reviews
- Track compliance metrics and audit readiness

#### Goals
- Protect organizational and customer data
- Maintain regulatory compliance
- Reduce security risks and incidents

#### Interaction with Existing Roles
- **Technical Architects**: Collaborate on security design decisions
- **Developers**: Ensure secure implementation and testing
- **Project Managers**: Surface security blockers and compliance risks
- **QA/Testing Leads**: Validate security test coverage

#### Typical Communication
- Security requirement reviews during planning
- CI/CD security scanning results
- Vulnerability triage and remediation tracking
- Security incident escalations
- Compliance audit participation

---

### DevOps / Release Engineer

#### Role Summary
DevOps and Release Engineers manage deployment pipelines, infrastructure provisioning, and release processes. They work with Developers to automate testing and deployment, and with Project Managers to ensure smooth releases.

#### Responsibilities
- Design and maintain CI/CD pipelines
- Automate testing, building, and deployment processes
- Manage production infrastructure and environments
- Create and maintain deployment documentation
- Conduct pre-release verification and smoke tests
- Manage rollback and disaster recovery procedures
- Monitor production systems and alerting
- Support incident response and post-incident analysis

#### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize deployment risk and downtime
- Maintain system reliability and performance

#### Interaction with Existing Roles
- **Developers**: Automate deployment and testing processes
- **QA/Testing Leads**: Coordinate deployment verification and smoke tests
- **Project Managers**: Coordinate release timing and rollback decisions
- **Technical Architects**: Ensure infrastructure meets scalability requirements

#### Typical Communication
- CI/CD pipeline updates and failures
- Deployment coordination during releases
- Infrastructure and monitoring discussions
- Incident response participation
- Post-release verification reports

---

## How to Use These Personas

### In Project Planning
- **Identify required personas** during the Initiation phase based on project scope, complexity, and risk
- **Core personas** are required for all projects
- **Extended personas** are added based on project needs:
  - QA/Testing Lead: For projects with quality-critical features
  - Technical Architect: For projects with significant technical complexity or architectural impact
  - Stakeholder/Sponsor: For all projects; may be filled by Product Manager on smaller projects
  - Scrum Master/Agile Coach: For cross-functional teams or teams new to Agile practices
  - Security/Compliance Officer: For projects handling sensitive data or regulatory requirements
  - DevOps/Release Engineer: For projects with complex deployment or infrastructure needs

### In Project Execution
- **Assign clear owners** for each persona role present in the project
- **Document interactions** between personas in project kickoff
- **Clarify communication patterns** and meeting attendance expectations
- **Reference personas** in project charters and team agreements

### For New Team Members
- Use these persona definitions to frame scenarios and understand roles
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance
- Reference the "Interaction with Existing Roles" sections to understand collaboration patterns

---

## Persona Selection Matrix

Use this matrix to help determine which extended personas to include in your project:

| Extended Persona | Low Complexity | Medium Complexity | High Complexity | High Risk | Data/Security Critical |
|---|---|---|---|---|---|
| QA/Testing Lead | Optional | Recommended | Required | Recommended | Required |
| Technical Architect | Optional | Optional | Required | Required | Optional |
| Stakeholder/Sponsor | Required | Required | Required | Required | Required |
| Scrum Master/Agile Coach | Optional | Recommended | Recommended | Recommended | Optional |
| Security/Compliance Officer | Optional | Optional | Recommended | Recommended | Required |
| DevOps/Release Engineer | Optional | Recommended | Required | Required | Recommended |
