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
QA and Testing professionals ensure that delivered features meet acceptance criteria, quality standards, and regulatory requirements. They collaborate with developers and product teams to validate functionality, usability, and performance.

### Responsibilities
- Define and execute test plans aligned with acceptance criteria
- Conduct manual and automated testing throughout the development lifecycle
- Identify and document defects with clear reproduction steps
- Validate that Definition of Done includes quality checkpoints
- Coordinate end-to-end smoke tests before release
- Participate in retrospectives to improve testing processes

### Goals
- Ensure features meet quality standards before production
- Reduce post-release defects and customer impact
- Enable fast feedback loops for development teams

### Typical Communication
- Sprint planning and Definition of Done discussions
- Defect reports and test result summaries
- Pre-release sign-off and smoke test coordination

### Interaction with Other Roles
- Works closely with **Developers** to define testable acceptance criteria and provide rapid feedback on code quality
- Collaborates with **Product Managers** to validate feature specifications against user expectations
- Partners with **Project Managers** to track quality metrics and manage testing schedules
- Coordinates with **Technical Leads** on testing strategy and automation frameworks
- Supports **Support/Operations** by providing production readiness validation

---

## Security Owner

### Role Summary
Security Owners integrate security practices throughout the project lifecycle, ensuring compliance, vulnerability prevention, and incident response readiness.

### Responsibilities
- Review security requirements and acceptance criteria
- Conduct or coordinate security assessments and scans in CI/CD
- Advise on secure design patterns and threat mitigation
- Manage security incidents and coordinate response
- Ensure compliance with organizational security policies

### Goals
- Prevent security vulnerabilities in production
- Maintain customer trust and regulatory compliance
- Build security awareness across the team

### Typical Communication
- Security reviews during planning and code review
- CI/CD scan results and remediation tracking
- Security incident notifications and post-incident reviews

### Interaction with Other Roles
- Advises **Developers** on secure coding practices and architecture decisions
- Partners with **Product Managers** to define security requirements and feature specifications
- Works with **Project Managers** to manage security risks and compliance timelines
- Collaborates with **Technical Leads** on threat modeling and secure design patterns
- Communicates with **Stakeholders/Sponsors** on compliance status and risk posture

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors represent business interests, provide approvals, and ensure project alignment with organizational goals and strategy.

### Responsibilities
- Define business requirements and success metrics
- Approve project charter and resource allocation
- Provide feedback on prioritization and trade-offs
- Remove escalated blockers and organizational barriers
- Participate in key decision gates (initiation, release approval)

### Goals
- Ensure projects deliver measurable business value
- Align delivery with organizational strategy
- Reduce rework by validating scope early

### Typical Communication
- Weekly or milestone-based status updates
- Kickoff and planning meetings
- Decision gate reviews and escalations

### Interaction with Other Roles
- Sets strategic direction and priorities with **Product Managers**
- Receives regular updates and escalations from **Project Managers**
- Reviews business impact and success metrics with all team members
- Makes final approvals on scope, budget, and timeline
- Escalates organizational barriers that block delivery

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects guide technical strategy, design decisions, and system integration. They balance innovation, scalability, and maintainability.

### Responsibilities
- Define technical architecture and design patterns
- Review design decisions for scalability and risk
- Guide developers on best practices and coding standards
- Identify and mitigate technical risks and dependencies
- Ensure integration with existing systems and platforms

### Goals
- Deliver solutions that are maintainable, scalable, and secure
- Reduce technical debt and design rework
- Enable knowledge sharing and team growth

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and mentoring
- Dependency and technical risk escalations

### Interaction with Other Roles
- Mentors and reviews code with **Developers** on technical decisions
- Collaborates with **Product Managers** on feasibility and technical trade-offs
- Communicates technical risks and mitigation plans to **Project Managers**
- Partners with **Security Owner** on threat modeling and secure architecture
- Works with **QA/Testing Lead** to design testable and automated test strategies
- Ensures operational readiness with **Support/Operations Lead**

---

## Support / Operations Lead

### Role Summary
Support and Operations teams ensure deployed solutions run reliably in production, diagnose issues, and support customer success.

### Responsibilities
- Define operational requirements and monitoring needs
- Participate in release planning and rollback preparation
- Manage production incidents and troubleshooting
- Provide customer support and issue resolution
- Contribute operational insights to retrospectives

### Goals
- Maintain high system reliability and uptime
- Respond quickly to production issues
- Proactively prevent operational problems

### Typical Communication
- Release readiness and deployment coordination
- Incident reports and post-incident reviews
- Operational metrics and monitoring feedback

### Interaction with Other Roles
- Provides feedback to **Developers** on production issues and reliability patterns
- Shares operational metrics and customer impact insights with **Product Managers**
- Works with **Project Managers** on deployment schedules and rollback plans
- Collaborates with **Technical Leads** on monitoring, logging, and incident response design
- Coordinates with **QA/Testing Lead** on pre-release smoke tests and production readiness
- Escalates critical production issues to **Security Owner** if security-related

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction patterns to understand how roles collaborate across the project lifecycle.
