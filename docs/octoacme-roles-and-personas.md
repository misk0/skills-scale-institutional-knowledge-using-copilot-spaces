# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---
## Purpose of updates
This page was extended to add commonly encountered personas that were previously not documented, plus guidance on interactions and handoffs to reduce ambiguity in ownership. Changes respond to issue #4: https://github.com/misk0/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4

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

## Additional Personas (new)

### UX / UI Designer
**Role Summary**
Designs user experiences and interfaces that meet business goals, accessibility, and usability standards.

**Responsibilities**
- Create wireframes, prototypes, and visual designs
- Validate designs with user research and usability testing
- Provide accessibility guidance and checks
- Produce design assets and handoff documentation for development

**Interaction**
- Works with Product Managers to align designs with success criteria
- Partners with Developers during implementation for design fidelity
- Reviews acceptance criteria and supports QA during UI verification

---

### Data Analyst
**Role Summary**
Provides data-driven insights, defines and tracks success metrics, and supports experiments and retrospectives.

**Responsibilities**
- Define event/metric instrumentation and dashboards
- Run analyses to inform prioritization and product decisions
- Support A/B experiments and measure impact
- Provide regular reports to PMs and stakeholders

**Interaction**
- Collaborates with Product Managers and Project Managers to set and measure success metrics
- Shares findings in planning and retrospective meetings
- Works with Developers/DevOps to ensure proper instrumentation

---

### Customer Success (or Customer Advocate)
**Role Summary**
Represents customer needs, surfaces feedback and support trends, and helps with adoption and communication.

**Responsibilities**
- Collect and summarize customer feedback and support issues
- Communicate product updates and assist with onboarding
- Escalate major customer-impacting issues to PM/PMs and on-call teams

**Interaction**
- Bridges users and the product/delivery team, participates in release readiness reviews when customer impact or communications are required

---

### DevOps Engineer (or Site Reliability Engineer)
**Role Summary**
Focuses on deployment automation, reliability, monitoring, and operational readiness.

**Responsibilities**
- Maintain CI/CD pipelines and deployment automation
- Implement monitoring, alerting, and runbooks
- Support incident response and reliability improvements
- Collaborate on deployment and rollback plans

**Interaction**
- Works with Developers to streamline deployments
- Coordinates with Project Managers during releases and incidents
- Partners with QA to ensure staging environments mimic production

---

### Compliance / Privacy Lead
**Role Summary**
Ensures product and process compliance with regulatory, legal, and privacy obligations.

**Responsibilities**
- Conduct privacy and compliance reviews, risk assessments
- Maintain checklists and controls required for regulated releases
- Participate in design or release reviews when policies apply

**Interaction**
- Reviews changes with Product and Developers; signs off on releases requiring compliance gates
- Collaborates with PM/Legal/Security for incident and audit response

---

## Interaction guidance & handoff checklist
To avoid gaps, use this short checklist when a role interaction is required (e.g., design handoff, release, incident, launch):

- Identify primary owner and secondary contact for each deliverable
- Confirm acceptance criteria and success metrics with Product Manager
- Ensure instrumentation/metrics are defined with Data Analyst before release
- Verify accessibility and design handoff artifacts with UX Designer
- Run a release readiness check with DevOps and Compliance (if applicable)
- Document communication plan and notify Customer Success for external communication

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---
