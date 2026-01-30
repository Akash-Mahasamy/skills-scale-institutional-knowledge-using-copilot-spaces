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

---

## Additional Personas (proposed)

The following personas are recommended additions to ensure clarity of ownership across release, operations, security, design, data, and customer-facing activities. Each entry includes a short description of responsibilities and how the role typically interacts with existing roles (PM, PdM, Developers, QA, Stakeholders).

### Release Manager

**Role Summary**
Responsible for coordinating release activities, ensuring deployments follow the release checklist, and managing rollback plans and release communications.

**Responsibilities**
- Coordinate deployment windows and communicate release readiness
- Verify pre-release checklists and sign off on go/no-go decisions
- Maintain rollback and mitigation plans

**Interactions**
- Works closely with the Project Manager and DevOps/SRE to schedule and execute deployments
- Notifies Stakeholders and Customer Support of release timelines and impacts


### DevOps / SRE

**Role Summary**
Handles infrastructure, automation, observability, and reliability engineering to support safe and repeatable delivery to production.

**Responsibilities**
- Build and maintain CI/CD pipelines, infrastructure-as-code, and runbooks
- Configure monitoring, alerting, and incident response tooling
- Collaborate on performance and capacity planning

**Interactions**
- Collaborates with Developers on deployment patterns and CI requirements
- Works with the Release Manager and PM during release and incident remediation


### Security Engineer

**Role Summary**
Ensures security considerations are embedded throughout the delivery lifecycle, performs security reviews, and participates in incident response.

**Responsibilities**
- Conduct threat modeling and security reviews for significant changes
- Run security scans, triage findings, and validate remediations
- Support incident response and post-incident analysis

**Interactions**
- Partners with Developers and QA to remediate security findings
- Escalates high-severity issues to PM and Sponsor as needed


### UX Researcher / Designer

**Role Summary**
Focuses on user research, design validation, and ensuring delivered features meet usability and accessibility expectations.

**Responsibilities**
- Conduct user research and usability testing
- Provide design specs and acceptance criteria related to UX
- Advocate for accessibility and human-centered design

**Interactions**
- Works with Product Managers to validate feature direction and acceptance criteria
- Collaborates with Developers and QA on implementation details and user-facing tests


### Data Analyst / Measurement Lead

**Role Summary**
Defines success metrics, builds dashboards, and validates that releases meet expected impact through data analysis.

**Responsibilities**
- Define measurable success metrics and instrumentation needs
- Produce dashboards and post-release analysis
- Validate A/B tests and experiment outcomes where applicable

**Interactions**
- Works with Product Managers to align on KPIs and with Developers to ensure proper telemetry
- Shares findings with PM, PdM, and stakeholders to inform decisions


### Customer Success / Support Lead

**Role Summary**
Serves as the primary liaison for customers and support teams, bringing field feedback to the product and project teams and coordinating customer communications for releases and incidents.

**Responsibilities**
- Capture and prioritize customer-reported issues and feature requests
- Prepare support-facing release notes and troubleshooting guidance
- Coordinate with PMs on customer communications for impactful changes

**Interactions**
- Communicates customer impact to PM and PdM
- Works with QA and Developers to reproduce and prioritize production issues


### Compliance / Legal Advisor

**Role Summary**
Provides guidance on regulatory, contractual, and privacy requirements that affect project scope and deliverables.

**Responsibilities**
- Review features for privacy and compliance implications
- Advise on data handling, contracts, and necessary approvals

**Interactions**
- Engages with PdM and PM during planning for regulated features
- Works with Security and DevOps on controls and audit evidence


### Accessibility Specialist

**Role Summary**
Ensures products meet accessibility standards and that accessibility considerations are included in acceptance criteria and testing.

**Responsibilities**
- Define accessibility acceptance criteria and test cases
- Perform audits and recommend remediation
- Advocate for inclusive design practices

**Interactions**
- Coordinates with UX Designers, Developers, and QA to implement and validate accessibility requirements


---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

