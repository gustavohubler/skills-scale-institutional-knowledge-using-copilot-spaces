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

## UX/UI Designer or Researcher

### Role Summary
UX/UI Designers and Researchers translate customer needs into usable, accessible, and valuable experiences. They help the team understand user pain points, design the interaction model, and validate assumptions before and during delivery.

### Responsibilities
- Conduct user research, interviews, and usability validation
- Create wireframes, prototypes, and design specifications
- Ensure accessibility, clarity, and consistency across user journeys
- Partner with Product Managers on problem framing and feature prioritization
- Review implementation with Developers and QA/Testing to confirm the experience matches the intended design

### Goals
- Improve customer satisfaction and product usability
- Reduce rework by validating needs early
- Create clear and consistent experiences across key workflows

### Typical Communication
- Product discovery and design reviews
- Weekly status updates with PM and product team
- Design handoff documents, prototypes, and feedback loops

### Interaction with Existing Roles
- Works closely with Product Managers to define problems, assumptions, and success criteria.
- Collaborates with Developers to ensure designs are feasible and implementation remains aligned to the intended experience.
- Shares validated findings with QA/Testing so acceptance criteria reflects usability and accessibility requirements.
- Keeps Project Managers informed of design risks, dependencies, or milestones that impact delivery.

---

## Technical Lead or Architect

### Role Summary
Technical Leads and Architects guide the technical direction of the solution, balance trade-offs, and reduce delivery risk across systems, integrations, and dependencies.

### Responsibilities
- Define technical direction, standards, and integration patterns
- Review architecture decisions and identify technical risks early
- Support estimation, sequencing, and dependency planning with the delivery team
- Guide Developers on implementation quality, maintainability, and operational readiness
- Partner with Product Managers on feasibility, complexity, and long-term impact

### Goals
- Deliver a scalable, maintainable solution
- Reduce avoidable technical debt and delivery risk
- Align implementation decisions with business goals and constraints

### Typical Communication
- Architecture reviews and technical design discussions
- Dependency planning with PM and delivery leads
- Design guidance during sprint planning and code review

### Interaction with Existing Roles
- Works with Product Managers to assess trade-offs between business objectives and technical feasibility.
- Supports Developers with technical strategy, code-quality guardrails, and architectural consistency.
- Advises Project Managers on major dependencies, technical milestones, and delivery risks.
- Collaborates with Security and DevOps roles to ensure the solution is secure, operable, and release-ready.

---

## DevOps / Site Reliability Engineer

### Role Summary
DevOps and Site Reliability Engineers ensure that the solution can be built, deployed, monitored, and supported reliably in production and non-production environments.

### Responsibilities
- Maintain deployment pipelines, environments, and release automation
- Define reliability, observability, and incident-response practices
- Monitor production health, alerting, and service performance
- Support rollback, recovery, and post-deploy validation planning
- Partner with Developers and QA/Testing to ensure operational readiness and troubleshooting capability

### Goals
- Improve release reliability and service availability
- Reduce time to detect and recover from incidents
- Enable confident, automated delivery across environments

### Typical Communication
- Release readiness reviews and deployment checklists
- Incident triage and escalation updates
- Monitoring and reliability dashboards with engineering stakeholders

### Interaction with Existing Roles
- Works with Developers to improve CI/CD, environment configuration, and deployment safety.
- Partners with QA/Testing on smoke tests, validation checkpoints, and release verification.
- Advises Project Managers on deployment windows, release risk, and operational dependencies.
- Coordinates with Security and Support roles on incident readiness, recovery planning, and production health signals.

---

## Security / Privacy Lead

### Role Summary
Security and Privacy Leads help teams identify and manage risk related to data protection, vulnerabilities, compliance, and secure delivery practices.

### Responsibilities
- Review requirements, designs, and implementations for security and privacy risks
- Define controls, security requirements, and validation criteria
- Support threat modeling, vulnerability reviews, and compliance checkpoints
- Escalate high-risk issues and recommend mitigations
- Partner with product and engineering teams to balance strong controls with delivery needs

### Goals
- Reduce security and privacy risk across the lifecycle
- Increase trust with customers, partners, and stakeholders
- Ensure required controls are in place before release

### Typical Communication
- Security reviews and risk assessments
- Escalation updates for high-severity concerns
- Release and compliance readiness check-ins

### Interaction with Existing Roles
- Works with Product Managers to ensure requirements reflect compliance, data handling, and risk considerations.
- Reviews technical decisions with Developers and Technical Leads to validate secure patterns and implementation choices.
- Reports escalating concerns to Project Managers and sponsors when the project may face delivery, compliance, or trust risks.
- Coordinates with DevOps and Support roles to ensure operational controls and incident handling are prepared.

---

## Customer Support / Operations Representative

### Role Summary
Customer Support and Operations representatives bring in real-world usage patterns, service issues, and user-impact context that helps the team deliver a smoother customer experience.

### Responsibilities
- Share recurring support issues, customer pain points, and service trends
- Help prepare rollout communications, support guidance, and escalation paths
- Validate operational readiness for launch and post-release support
- Collaborate on bug triage and customer-impact prioritization
- Provide post-release feedback to Product and Engineering teams

### Goals
- Improve customer experience and service quality
- Reduce avoidable support friction and escalation volume
- Ensure teams are ready for real-world usage after release

### Typical Communication
- Support intake, bug triage, and customer feedback cycles
- Launch readiness and post-release review meetings
- Weekly or milestone updates with PM and product teams

### Interaction with Existing Roles
- Partners with Product Managers on customer needs, service gaps, and feature prioritization.
- Shares issues and trends with Developers and QA/Testing to improve fixes and validation.
- Provides Project Managers with operational risk information and support-readiness signals.
- Coordinates with DevOps and Security leads during rollout, incident handling, and operational follow-up.

---

## Data / Analytics Lead

### Role Summary
Data and Analytics Leads define how success and product impact are measured so the team can learn from usage, quality, and outcome data throughout the project lifecycle.

### Responsibilities
- Define metrics, instrumentation, dashboards, and reporting needs
- Validate whether product success criteria are measurable and actionable
- Support experiment design, analysis, and insights for product decisions
- Help connect usage data to business outcomes and adoption trends
- Partner with teams to ensure key signals are available before and after release

### Goals
- Improve decision-making with evidence and measurable outcomes
- Make product impact visible to stakeholders
- Ensure the team can learn and adapt using real data

### Typical Communication
- KPI and measurement planning with PM and Product teams
- Dashboard reviews and post-release reporting
- Analysis summaries for milestone and release updates

### Interaction with Existing Roles
- Works with Product Managers to define goals, success metrics, and reporting thresholds.
- Collaborates with Developers to confirm instrumentation and quality of captured data.
- Provides Project Managers with evidence on progress, risks, and milestone outcomes.
- Shares findings with Stakeholders and Support roles to inform communications and operational decisions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For smaller teams, multiple roles may be combined, but the responsibilities and interaction boundaries should still be clear.

