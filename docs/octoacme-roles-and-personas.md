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

## Engineering Lead / Technical Lead

### Role Summary
Engineering Leads own technical direction, architecture decisions, and technical delivery quality across the project lifecycle.

### Responsibilities
- Define and communicate architecture and implementation approach
- Identify technical risks, trade-offs, and mitigation plans
- Guide developers on design, standards, and delivery readiness
- Partner with QA/Testing on testability and quality gates

### Interaction and Accountability Guidance
- **Developers**: provide design guidance, unblock implementation, and review technical quality
- **Product Managers**: align feasibility and sequencing with product priorities
- **Project Managers**: surface technical dependencies and delivery risks for planning
- **QA/Testing**: align on test strategy, automation priorities, and defect triage decisions
- **Stakeholders**: explain major technical trade-offs, risks, and constraints as needed
- **Decision accountability**: final technical decision owner when trade-offs remain unresolved within engineering

### Typical Communication
- Technical design docs and architecture reviews
- Engineering planning sessions and risk reviews
- Implementation and release readiness checkpoints

---

## Designer / UX Researcher

### Role Summary
Designers and UX Researchers represent user needs through research, workflows, prototypes, and usability insights.

### Responsibilities
- Define user flows, interaction patterns, and prototype concepts
- Run research and usability validation to reduce product risk
- Translate findings into actionable design requirements and acceptance inputs
- Collaborate on accessibility and usability quality expectations

### Interaction and Accountability Guidance
- **Developers**: align design intent with technical feasibility and implementation detail
- **Product Managers**: refine user outcomes, priorities, and acceptance criteria
- **Project Managers**: coordinate design milestones, reviews, and dependency timing
- **QA/Testing**: clarify expected behavior and usability validation criteria
- **Stakeholders**: share user evidence that informs scope and priority decisions
- **Decision accountability**: accountable for design intent and user experience rationale

### Typical Communication
- Design reviews and prototype walkthroughs
- Research readouts and usability findings
- UX acceptance notes in stories/specs

---

## Business Analyst / Requirements Lead

### Role Summary
Business Analysts ensure requirements are clear, traceable, and aligned to business objectives.

### Responsibilities
- Elicit and document functional and process requirements
- Maintain traceability from business goals to backlog items and test conditions
- Resolve requirement ambiguity and manage assumptions
- Support scope and change-impact analysis

### Interaction and Accountability Guidance
- **Developers**: provide detailed requirement clarifications and business rules
- **Product Managers**: align requirements with product goals and prioritization
- **Project Managers**: document decisions, scope changes, and dependency impacts
- **QA/Testing**: ensure acceptance conditions are testable and unambiguous
- **Stakeholders**: validate business process needs and approval points
- **Decision accountability**: accountable for requirement clarity and traceability quality

### Typical Communication
- Backlog refinement and requirement workshops
- Decision logs and requirement traceability updates
- Scope and change-impact briefings

---

## QA Lead / Test Engineer

### Role Summary
QA Leads define validation strategy and quality risk visibility, ensuring releases meet acceptance and reliability expectations.

### Responsibilities
- Define test strategy, coverage priorities, and quality gates
- Coordinate test execution across functional and non-functional needs
- Track defects, quality trends, and release risk signals
- Recommend release readiness based on evidence

### Interaction and Accountability Guidance
- **Developers**: collaborate on testability, automation, and defect resolution
- **Product Managers**: confirm acceptance outcomes and quality trade-offs
- **Project Managers**: report readiness, blockers, and quality risks
- **QA/Testing**: organize test roles, standards, and escalation paths
- **Stakeholders**: communicate quality posture and residual risk clearly
- **Decision accountability**: accountable for quality assessment and go/no-go recommendation input

### Typical Communication
- Test plans, defect triage, and regression summaries
- Quality dashboards and release readiness reports
- Post-release defect and incident reviews

---

## DevOps / Site Reliability Engineer

### Role Summary
DevOps/SRE roles own deployment enablement, service reliability, observability, and operational readiness.

### Responsibilities
- Build and maintain CI/CD and environment reliability
- Define observability, alerting, and rollback capabilities
- Improve operational resilience and incident response preparedness
- Support release orchestration and production validation

### Interaction and Accountability Guidance
- **Developers**: align build/deploy workflows, runtime standards, and reliability improvements
- **Product Managers**: clarify operational constraints that affect product commitments
- **Project Managers**: track release dependencies, environment risks, and readiness milestones
- **QA/Testing**: provide stable test environments and deployment validation support
- **Stakeholders**: communicate reliability posture and operational risk
- **Decision accountability**: accountable for platform/reliability controls and deployment guardrails

### Typical Communication
- Release runbooks and deployment checklists
- Incident reviews and reliability reports
- Environment and pipeline status updates

---

## Security / Privacy Lead

### Role Summary
Security/Privacy Leads identify and manage security, privacy, and compliance risks throughout delivery.

### Responsibilities
- Define required security and privacy controls for scope
- Conduct risk/threat assessments and mitigation planning
- Review designs and implementations for policy/compliance alignment
- Escalate unresolved high-impact risks before release

### Interaction and Accountability Guidance
- **Developers**: guide secure implementation and remediation priorities
- **Product Managers**: align risk trade-offs with product value and obligations
- **Project Managers**: integrate security/privacy checkpoints into plans and escalation paths
- **QA/Testing**: align on validation evidence for controls and risk closure
- **Stakeholders**: report risk posture and compliance implications for decisions
- **Decision accountability**: accountable for security/privacy risk sign-off recommendations

### Typical Communication
- Threat/risk review sessions
- Security/privacy checklist updates and sign-off notes
- Release risk escalations when required

---

## Operations / Customer Support Representative

### Role Summary
Operations and Support representatives bring customer-impact and service-operability insight into planning and release decisions.

### Responsibilities
- Define support readiness needs (documentation, runbooks, escalation paths)
- Share customer pain points and operational trends
- Help prepare incident response and post-release support workflows
- Close feedback loops from support signals into product and delivery planning

### Interaction and Accountability Guidance
- **Developers**: provide reproducible customer issues and support-driven improvement feedback
- **Product Managers**: prioritize customer-impact fixes and service usability improvements
- **Project Managers**: coordinate release communications and support readiness timelines
- **QA/Testing**: validate support scenarios and known customer workflows
- **Stakeholders**: communicate service impact and customer-facing risk
- **Decision accountability**: accountable for support readiness recommendations and escalation clarity

### Typical Communication
- Support trend reports and incident summaries
- Release communication plans and enablement notes
- Customer-impact retrospectives

---

## Executive Sponsor / Business Owner

### Role Summary
Executive Sponsors and Business Owners provide strategic direction, resource commitment, and final arbitration on major scope and priority decisions.

### Responsibilities
- Set business outcomes and strategic constraints
- Approve major investment, scope, and priority shifts
- Resolve escalations beyond team-level authority
- Champion cross-functional alignment and accountability

### Interaction and Accountability Guidance
- **Developers**: receive high-level context on strategic constraints and delivery expectations
- **Product Managers**: align on business outcomes, priorities, and value realization
- **Project Managers**: review status, major risks, and delivery confidence
- **QA/Testing**: review critical quality risk posture when release decisions are escalated
- **Stakeholders**: align decisions when cross-team trade-offs require executive arbitration
- **Decision accountability**: accountable for final business-priority and escalation decisions

### Typical Communication
- Executive steering updates
- Milestone decision meetings
- Escalation and risk arbitration reviews

---

## Applying Personas by Project Context
- Not every project requires every persona as a separate individual role.
- On smaller teams, one person may combine multiple personas (for example, Engineering Lead + Developer, or Product Manager + Business Analyst).
- On larger or regulated efforts, split personas to preserve clear accountability, faster decisions, and better risk control.
- Keep role expectations explicit in kickoff and planning so collaboration touchpoints remain clear.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
