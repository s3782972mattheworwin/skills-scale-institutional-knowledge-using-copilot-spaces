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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality assurance strategy, test planning, and validation of acceptance criteria. They work with developers and product to ensure features meet quality standards before release.

### Responsibilities
- Define test plans and QA approach aligned with project scope
- Execute manual and automated testing across acceptance criteria
- Validate features meet acceptance criteria before handoff
- Identify, document, and track defects with clear severity and reproduction steps
- Coordinate with developers on test automation strategy and coverage
- Provide quality metrics and reports (test coverage, defect trends, release readiness)
- Contribute to Definition of Done to include testability requirements

### Goals
- Deliver high-quality, reliable software to production
- Minimize bugs and regressions reaching production
- Maintain high test coverage and observability
- Enable developers to build testable, quality-focused features

### Typical Communication
- Sprint planning and estimation (for test effort)
- PR reviews focused on testability and test coverage
- Daily standups and blocker escalation
- QA metrics dashboards and release readiness reviews
- Defect triage and handoff communication with developers

### Interaction with Other Roles
- **Developers**: Collaborate on test automation, testability in PRs, defect resolution
- **Product Managers**: Align on acceptance criteria and test scenarios
- **Project Managers**: Report on quality metrics and release readiness status
- **Technical Architect**: Advise on test infrastructure and automation strategy

---

## Technical Architect / Tech Lead

### Role Summary
Technical Architects provide technical direction, design system architecture, and ensure solutions align with long-term technical strategy. They guide developers on complex technical decisions and conduct design reviews.

### Responsibilities
- Review and guide architectural decisions for alignment with long-term strategy
- Conduct technical design reviews on complex features and integrations
- Identify technical risks and propose mitigations and solutions
- Mentor developers on best practices, design patterns, and code quality
- Oversee system performance, scalability, and maintainability concerns
- Manage technical debt and propose refactoring priorities
- Collaborate with Security/Compliance on architectural security and compliance requirements

### Goals
- Deliver technically sound, maintainable, and scalable solutions
- Reduce technical debt and accelerate feature delivery through good design
- Build resilient systems that support long-term business growth
- Foster a culture of technical excellence and continuous learning

### Typical Communication
- Technical design reviews and architecture documentation
- Code reviews on complex or high-risk areas
- Weekly syncs with PM and Project Manager on technical blockers
- Escalation of technical risks and trade-offs
- Mentoring sessions and technical guidance for developers

### Interaction with Other Roles
- **Developers**: Provide design guidance, review complex implementations, mentor on best practices
- **Product Managers**: Advise on feasibility and technical implications of requirements
- **Project Managers**: Escalate technical blockers and timeline impacts
- **Security/Compliance Officer**: Collaborate on secure and compliant architecture
- **QA/Testing Lead**: Advise on test infrastructure and automation strategy

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure projects meet security and compliance requirements. They partner with teams to embed security practices throughout the project lifecycle, from planning through release.

### Responsibilities
- Review security and compliance requirements during project initiation and planning
- Conduct security assessments and threat analysis for new features and integrations
- Guide secure coding practices and provide security training for developers
- Perform security reviews and penetration testing before release
- Manage compliance documentation, audit trails, and regulatory adherence
- Identify and escalate security risks and compliance gaps
- Support incident response and security incident investigations

### Goals
- Minimize security and compliance risk to the organization
- Ensure regulatory adherence and audit readiness
- Build secure products by design rather than bolting on security later
- Enable teams to ship confidently with security built-in

### Typical Communication
- Project initiation and planning reviews (security requirements)
- Security design reviews on sensitive features (authentication, data storage, APIs)
- Pre-release security validation and sign-off
- Incident response and escalation during security events
- Compliance and audit communications with stakeholders

### Interaction with Other Roles
- **Developers**: Guide on secure coding, review security-sensitive code, support secure implementation
- **Product Managers**: Advise on security and compliance implications of features
- **Project Managers**: Escalate security risks and compliance gaps
- **Technical Architect**: Collaborate on secure architecture and infrastructure
- **Sponsor/Executive Stakeholder**: Report on compliance and risk status

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide business context, make strategic decisions, and remove organizational blockers. They approve significant scope or timeline changes and escalate business-impacting risks. They represent executive alignment and ensure projects deliver strategic value.

### Responsibilities
- Clarify business objectives, constraints, and strategic context
- Approve project charter, scope, and resource allocation
- Make trade-off decisions between scope, schedule, and resources
- Remove cross-organizational blockers and coordinate with dependent teams
- Review milestone achievements and return on investment (ROI)
- Escalate business-impacting risks and make go/no-go decisions
- Communicate project progress to broader executive leadership

### Goals
- Ensure project delivers strategic business value and ROI
- Maintain executive alignment and stakeholder confidence
- Optimize resource allocation across the project portfolio
- Enable teams to succeed by removing organizational barriers

### Typical Communication
- Project initiation reviews and charter approvals
- Milestone reviews and major progress updates
- Escalated risks and blockers requiring executive decision
- Monthly stakeholder updates and board-level reporting
- Go/no-go decisions at key gates (planning, release)

### Interaction with Other Roles
- **Project Manager**: Regular syncs on status, risks, and blockers; escalation partner
- **Product Manager**: Align on business objectives and success metrics
- **Developers/Technical Architect**: Provide context on business priorities and trade-offs
- **QA/Testing Lead**: Review quality and release readiness for go-live decision

---

## Support / Customer Success

### Role Summary
Support and Customer Success roles act as the voice of the customer and support team. They provide feedback on usability and identify support implications of new features. They ensure customers can easily adopt and use features, and reduce support burden.

### Responsibilities
- Provide customer perspective during project planning and feature design
- Identify support implications, training needs, and documentation gaps
- Validate feature usability and ease of customer adoption
- Contribute to release notes, customer communications, and training materials
- Escalate critical customer issues and usability concerns
- Provide customer feedback loops to product and engineering teams
- Support go-to-market activities and customer onboarding for new features

### Goals
- Ensure features are easy for customers to use and for support to assist with
- Reduce support burden and customer escalations
- Maintain high customer satisfaction and retention
- Enable customers to realize value from new features quickly

### Typical Communication
- Project planning and design reviews (customer perspective)
- Acceptance criteria validation and usability testing
- Release readiness reviews and customer communication planning
- Customer feedback loops and support escalation tracking
- Post-release customer adoption and support metrics

### Interaction with Other Roles
- **Product Managers**: Provide customer feedback and adoption insights
- **Developers**: Identify usability concerns and feature clarity issues
- **Project Managers**: Escalate customer-impacting issues and support concerns
- **QA/Testing Lead**: Participate in acceptance testing from customer perspective
- **Sponsor/Executive Stakeholder**: Report on customer adoption and satisfaction metrics

---

## Role Interaction Matrix

| Role | Developers | Product Managers | Project Managers | QA/Testing Lead | Technical Architect | Security/Compliance | Sponsor/Executive | Support/Customer Success |
|------|-----------|------------------|------------------|-----------------|---------------------|---------------------|-------------------|------------------------|
| **Developers** | Code review, pair programming | Requirements, acceptance criteria | Estimation, blocker escalation | Testability, defect resolution | Design guidance, technical review | Secure coding guidance | Trade-off context | Usability feedback |
| **Product Managers** | Acceptance criteria, feature spec | Roadmap prioritization | Scope & timeline alignment | Test strategy alignment | Feasibility & implications | Compliance requirements | Business objectives | Customer feedback loops |
| **Project Managers** | Status & blockers | Scope & priority | Schedule coordination | Quality metrics & readiness | Technical risk escalation | Compliance milestones | Risk escalation & approvals | Customer impact & blockers |
| **QA/Testing Lead** | Test automation & coverage | Test strategy alignment | QA metrics & readiness | Test planning & coordination | Test infrastructure guidance | Compliance validation | Quality sign-off | Customer usability validation |
| **Technical Architect** | Design guidance & review | Feasibility & implications | Technical risk escalation | Test infrastructure | Architecture decisions | Security architecture | Technical feasibility | Design for usability |
| **Security/Compliance Officer** | Secure coding guidance | Security requirements | Compliance milestones | Security validation | Security architecture | Compliance coordination | Risk reporting | Privacy & compliance for customers |
| **Sponsor/Executive Stakeholder** | Trade-off context | Business objectives | Risk escalation & approval | Quality sign-off | Technical feasibility | Risk reporting | Executive alignment | Satisfaction & ROI metrics |
| **Support/Customer Success** | Usability feedback | Customer feedback & adoption | Customer impact & blockers | Customer perspective testing | Design for usability | Privacy & compliance questions | Adoption & satisfaction metrics | Customer feedback loops |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Role Interaction Matrix to understand how personas collaborate and communicate.
- When planning projects, ensure all relevant personas are engaged at appropriate stages.
