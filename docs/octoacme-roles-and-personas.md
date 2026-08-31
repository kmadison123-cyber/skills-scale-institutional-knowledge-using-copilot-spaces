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
- Works with **QA/Testing Leads** on test design and acceptance criteria validation
- Collaborates with **Product Managers** on feature specifications and acceptance criteria
- Engages with **Project Managers** on scheduling and dependency management
- Partners with **Security/Compliance Officers** on security requirements and code scanning

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
- Aligns with **Product Leads** on strategic priorities and trade-offs
- Works with **QA/Testing Leads** to define acceptance criteria and quality gates
- Collaborates with **Developers** on feature feasibility and design
- Engages with **Stakeholder Groups** to gather input and validate outcomes

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
- Escalates blockers to **Product Leads** and **Sponsors** as needed
- Works with **QA/Testing Leads** on test scheduling and release readiness
- Coordinates with **Security/Compliance Officers** on compliance checklists and security approvals
- Manages communication with **Stakeholder Groups** on project status and dependencies

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy and execution. They ensure features meet acceptance criteria, maintain test coverage, and prevent defects from reaching production.

### Responsibilities
- Define test strategy and test plan for each project
- Validate features against acceptance criteria
- Manage test automation and regression testing
- Conduct security and performance testing where applicable
- Participate in release readiness reviews
- Triage and document defects; work with Developers on resolution
- Track test metrics and coverage

### Goals
- Deliver high-quality features with minimal post-release defects
- Reduce time-to-release by automating repetitive testing
- Maintain transparency on quality risks

### Typical Communication
- Planning: Define test approach in sprint/release planning
- Execution: Daily standup updates on test progress and blockers
- Release: Lead smoke testing and sign-off on readiness
- Retrospectives: Report on quality metrics and improvement areas

### Interactions with Other Roles
- Collaborates with **Developers** on test design, acceptance criteria, and defect resolution
- Works with **Product Managers** to understand and validate acceptance criteria
- Partners with **Project Managers** on test scheduling and release timelines
- Provides quality metrics and risk assessments to **Product Leads** and **Sponsors**
- Conducts security testing in coordination with **Security/Compliance Officers**

---

## Product Lead / Head of Product

### Role Summary
Product Leads set product strategy and serve as the escalation authority for product-related decisions. They ensure portfolio-level alignment and remove cross-project blockers.

### Responsibilities
- Approve project initiation and scope decisions
- Resolve prioritization conflicts between projects
- Provide guidance on strategic alignment and trade-offs
- Serve as escalation point for Project Managers and Product Managers
- Coordinate across multiple product teams
- Review and approve major release announcements

### Goals
- Ensure all projects ladder up to product strategy
- Maximize business impact across the portfolio
- Enable teams to deliver with clarity and confidence

### Typical Communication
- Weekly sync with Project Managers and Product Managers
- Monthly stakeholder reviews of portfolio progress
- Ad-hoc escalation calls when blockers emerge
- Approval of project charters and major scope changes

### Interactions with Other Roles
- Receives escalations from **Project Managers** on scope, priority, and resource conflicts
- Partners with **Product Managers** on strategic alignment and roadmap decisions
- Approves project charters prepared by **Project Managers**
- Escalates organizational blockers to **Sponsors** for resolution
- Reviews quality and release readiness assessments from **QA/Testing Leads**
- Aligns security and compliance requirements with **Security/Compliance Officers**

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors represent the business and customer interests at the executive level. They provide approval authority at key decision gates and remove organizational blockers.

### Responsibilities
- Approve project initiation and business case
- Define success metrics and business outcomes
- Allocate budget and resources
- Participate in go/no-go gates
- Remove organizational and cross-team blockers
- Receive monthly status and risk updates
- Communicate project outcomes to broader leadership

### Goals
- Ensure strategic alignment with business objectives
- Maximize return on investment (ROI)
- Reduce organizational risk and bottlenecks

### Typical Communication
- Monthly status updates and risk summaries
- Gate meetings (initiation, release, retrospectives)
- Escalation calls for critical blockers
- Post-release briefings and outcome reviews

### Interactions with Other Roles
- Receives escalations from **Product Leads** on organizational blockers and strategic decisions
- Reviews business impact summaries from **Product Managers**
- Receives risk and progress updates from **Project Managers**
- Approves release decisions based on quality and compliance input from **QA/Testing Leads** and **Security/Compliance Officers**
- Provides executive guidance to resolve cross-team dependencies with **Stakeholder Groups**

---

## Security / Compliance Officer

### Role Summary
Security Officers ensure projects meet security and compliance requirements. They integrate security into the development lifecycle and manage incident response.

### Responsibilities
- Review security requirements during planning
- Approve security approach and mitigations
- Conduct or oversee security scanning in CI
- Validate secure deployment processes
- Lead security incident response and communication
- Provide guidance on regulatory compliance

### Goals
- Minimize security vulnerabilities and risk exposure
- Ensure regulatory and compliance requirements are met
- Enable secure, confident releases

### Typical Communication
- Planning: Security requirements review
- Execution: Security scan results and guidance
- Release: Security readiness approval
- Incidents: Lead incident communication and response

### Interactions with Other Roles
- Collaborates with **Developers** on secure coding practices and security scanning results
- Works with **QA/Testing Leads** on security and compliance testing
- Advises **Product Managers** on security features and requirements
- Partners with **Project Managers** to integrate compliance checklists into release planning
- Provides security assessment summaries to **Product Leads** and **Sponsors** for approval decisions
- Engages with **Stakeholder Groups** on compliance impact and incident communication

---

## Stakeholder Groups

### Role Summary
Stakeholders represent diverse organizational functions that provide input, feedback, or are affected by project outcomes. Common groups include Engineering Leadership, Sales, Customer Support, Marketing, and Finance.

### Responsibilities
- Provide domain expertise during planning and design
- Participate in retrospectives and feedback sessions
- Receive tailored status updates aligned to their interests
- Escalate concerns or dependencies early

### Goals
- Ensure cross-functional alignment
- Capture diverse perspectives to improve outcomes
- Reduce surprises and miscommunications

### Typical Communication
- Planning kickoff: Provide input on scope and impact
- Weekly status: Updates tailored to stakeholder interests (e.g., Sales impact, Support burden)
- Retrospectives: Participate when directly affected
- Release: Coordinated announcements and customer communication

### Interactions with Other Roles
- Consult with **Product Managers** on business and customer needs during planning
- Provide feedback to **Project Managers** on cross-functional dependencies and timeline impact
- Receive quality and readiness updates from **QA/Testing Leads** relevant to their functions
- Engage with **Product Leads** on portfolio impact and priority trade-offs
- Partner with **Sponsors** on executive escalations and business outcome alignment
- Coordinate with **Security/Compliance Officers** on compliance and security impact (e.g., Support team on customer communication)

---

## Roles at a Glance

| Role | Initiation | Planning | Execution | Release | Retrospective |
|------|-----------|----------|-----------|---------|---------------|
| **Developers** | Input | Collaborate | Primary | Execute | Participate |
| **Product Managers** | Define | Collaborate | Advise | Advise | Participate |
| **Project Managers** | Coordinate | Lead | Lead | Coordinate | Facilitate |
| **QA/Testing Leads** | Input | Define | Lead | Lead | Report |
| **Product Leads** | Approve | Advise | Escalate | Approve | Advise |
| **Sponsors** | Approve | Allocate | Escalate | Approve | Review |
| **Security/Compliance Officers** | Review | Review | Scan/Advise | Approve | Review |
| **Stakeholder Groups** | Consult | Participate | Advise | Coordinate | Participate |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Roles at a Glance" table to understand when each role engages across the project lifecycle.
- Use the interaction sections to understand cross-functional handoffs and dependencies.
