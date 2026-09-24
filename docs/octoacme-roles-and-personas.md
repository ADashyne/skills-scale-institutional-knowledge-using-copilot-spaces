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

## Technical Leads

### Role Summary
Technical Leads own technical direction for a project or feature. They guide architecture and implementation decisions, coordinate engineering dependencies, and help ensure the solution is reliable, maintainable, and feasible.

### Responsibilities
- Define or review technical designs and architecture decisions
- Coordinate technical dependencies and sequencing across developers or teams
- Identify technical risks, trade-offs, and mitigation options
- Support estimation, implementation planning, and engineering quality
- Facilitate technical decisions and document important conclusions

### Interaction with Existing Roles
- Partner with the Product Manager to translate product outcomes and acceptance criteria into feasible technical approaches.
- Partner with the Project Manager to surface dependencies, delivery risks, estimates, and schedule impacts.
- Guide Developers through design reviews, implementation questions, and code quality expectations without replacing their implementation ownership.
- Provide technical input to stakeholders and escalate decisions that require broader product, security, or sponsor alignment.

---

## Security and Compliance Partners

### Role Summary
Security and Compliance Partners identify security, privacy, regulatory, and policy requirements that affect the project. They provide risk guidance and help the team demonstrate that the solution is ready for release.

### Responsibilities
- Review requirements, designs, and workflows for security and compliance risks
- Define or validate required controls, assessments, and evidence
- Track security and compliance findings through mitigation or accepted-risk decisions
- Advise on incident preparedness, data handling, and access controls
- Confirm security and compliance readiness before applicable releases

### Interaction with Existing Roles
- Work with the Product Manager to incorporate security and compliance requirements into scope and acceptance criteria.
- Work with the Project Manager to record findings in the risk register, establish owners and due dates, and escalate unresolved risks.
- Advise Developers and Technical Leads on secure design and implementation choices.
- Coordinate with stakeholders and release owners when a risk requires a decision, exception, or deployment hold.

---

## Customer Success and Support Liaisons

### Role Summary
Customer Success and Support Liaisons represent customer-facing needs throughout delivery. They bring user feedback, adoption considerations, support readiness, and operational concerns into project decisions.

### Responsibilities
- Share customer feedback, common support issues, and adoption risks
- Review proposed changes for customer impact and usability concerns
- Help prepare support guidance, FAQs, enablement materials, and communication plans
- Coordinate pilot or early-adopter feedback when appropriate
- Monitor post-release customer signals and report emerging issues

### Interaction with Existing Roles
- Partner with the Product Manager to connect customer needs and feedback to prioritization, outcomes, and acceptance criteria.
- Partner with the Project Manager to plan stakeholder communications, readiness activities, and post-release follow-up.
- Work with Developers and Technical Leads to clarify user-impacting behavior and reproduce customer issues.
- Coordinate with Security and Compliance Partners when customer communications or support procedures involve sensitive data or regulated workflows.

---

## Release Managers

### Role Summary
Release Managers coordinate the operational readiness and execution of releases. They ensure that deployment plans, verification steps, communications, and rollback options are understood before production changes occur.

### Responsibilities
- Maintain release scope, sequencing, readiness criteria, and deployment timelines
- Confirm that acceptance criteria, CI checks, security reviews, smoke tests, and release notes are complete
- Coordinate staging validation, production deployment, and post-deployment verification
- Ensure rollback or mitigation plans are documented and actionable
- Communicate release status, decisions, and incidents to affected teams and stakeholders

### Interaction with Existing Roles
- Work with the Project Manager to align release milestones, dependencies, risks, and stakeholder communications.
- Work with the Product Manager to confirm scope, business readiness, and customer-facing messaging.
- Coordinate with Technical Leads and Developers on deployment steps, verification, observability, and rollback decisions.
- Partner with Customer Success and Support Liaisons on support readiness and release announcements.
- Confirm required Security and Compliance Partner approvals or risk decisions before deployment.

---

## Data and Analytics Partners

### Role Summary
Data and Analytics Partners help teams define, instrument, interpret, and report the measures used to evaluate project outcomes. They turn product and delivery data into evidence for decisions and continuous improvement.

### Responsibilities
- Define measurement plans and clarify how success metrics will be calculated
- Identify instrumentation, data quality, and reporting requirements
- Establish baselines and monitor adoption, performance, and outcome trends
- Provide analysis for prioritization, launch evaluation, and retrospectives
- Document assumptions, limitations, and interpretation of reported results

### Interaction with Existing Roles
- Partner with the Product Manager to connect success metrics to customer and business outcomes.
- Partner with the Project Manager to include measurement work, dependencies, and reporting milestones in the project plan.
- Work with Developers and Technical Leads to define instrumentation and validate data collection.
- Share release and post-release insights with Customer Success and Support Liaisons to identify adoption or customer-impact trends.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign a role owner for each applicable responsibility during initiation or planning, and document handoffs and escalation paths in the project plan or risk register.

