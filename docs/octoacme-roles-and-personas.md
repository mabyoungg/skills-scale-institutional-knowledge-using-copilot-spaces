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

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove delivery blockers, coach the team on agile best practices, and bridge collaboration among roles.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Identify and remove delivery impediments
- Coach the team on agile practices and continuous improvement
- Support collaboration and shared accountability across roles

### Goals
- Maximize team velocity and predictability
- Foster psychological safety and healthy team dynamics
- Remove delivery friction before it affects outcomes

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospectives and process improvement discussions
- One-on-ones to resolve blockers

### Interaction with Existing Roles
- Works closely with Project Managers on planning and delivery cadence
- Supports Developers by removing blockers and improving team flow
- Collaborates with Product Managers to keep prioritization and sprint goals clear

---

## UX Designer/Researcher

### Role Summary
UX Designers/Researchers lead user experience strategy, perform user research, create wireframes and prototypes, and collaborate with Product Managers to validate solutions.

### Responsibilities
- Conduct user research and usability studies
- Create wireframes and prototypes for proposed solutions
- Validate design decisions with users before development
- Ensure accessibility requirements are incorporated
- Collaborate on acceptance criteria from a usability perspective

### Goals
- Ensure product usability and accessibility
- Validate design decisions with real user feedback
- Reduce rework caused by poor UX assumptions

### Typical Communication
- Design reviews with Developers
- User research sessions and synthesis readouts
- Collaboration with Product Managers on requirements
- Design documentation and handoff artifacts

### Interaction with Existing Roles
- Partners with Product Managers to refine requirements and user outcomes
- Collaborates with Developers on implementation feasibility and handoff clarity
- Influences acceptance criteria to include usability and accessibility quality bars

---

## Release Manager

### Role Summary
Release Managers schedule, coordinate, and lead release activities across the project to ensure smooth and predictable deployments.

### Responsibilities
- Plan and schedule release windows
- Coordinate release readiness across Development, QA, and Operations
- Verify deployment prerequisites and approval checkpoints
- Track release status, risks, and go/no-go decisions
- Communicate release timelines, dependencies, and risks

### Goals
- Ensure smooth, low-risk releases
- Minimize deployment issues and rollback events
- Maintain clear release communication across stakeholders

### Typical Communication
- Release planning meetings
- Deployment coordination updates
- Status reports before and during releases
- Incident management communication during release windows

### Interaction with Existing Roles
- Coordinates timing and milestone readiness with Project Managers
- Works with Developers on code readiness and release packaging
- Partners with QA/Testing on validation completion and release sign-off

---

## Business Analyst

### Role Summary
Business Analysts gather and document requirements, translate business needs into actionable user stories, clarify open questions for delivery teams, and validate delivered value.

### Responsibilities
- Gather and document business requirements from stakeholders
- Translate requirements into user stories and acceptance criteria
- Clarify ambiguities and assumptions for Developers
- Validate that delivered features meet business needs
- Support backlog refinement with clear scope definitions

### Goals
- Align business needs with technical delivery
- Minimize requirement churn and rework
- Improve story clarity and implementation confidence

### Typical Communication
- Stakeholder interviews and discovery sessions
- Requirements workshops and backlog refinement
- Clarification discussions with Developers and Product Managers
- Validation meetings for delivered features

### Interaction with Existing Roles
- Works with Product Managers to refine and prioritize backlog items
- Collaborates with Developers to resolve requirement ambiguities
- Partners with QA/Testing to validate acceptance criteria coverage

---

## Persona Interaction Matrix (Issue #4)

This matrix clarifies collaboration points between new and existing personas to improve accountability and onboarding clarity.

| Persona | Primary Collaboration Partners | Collaboration Focus |
| --- | --- | --- |
| Scrum Master | Project Managers, Product Managers, Developers | Ceremony facilitation, blocker removal, delivery flow improvements |
| UX Designer/Researcher | Product Managers, Developers, QA/Testing | User research, accessibility, design validation, acceptance quality |
| Release Manager | Project Managers, Developers, QA/Testing | Release planning, readiness checks, deployment coordination |
| Business Analyst | Product Managers, Developers, QA/Testing | Requirement clarity, story refinement, acceptance criteria validation |
| Project Managers | Scrum Master, Release Manager, Product Managers | Plan integrity, risk management, schedule and release alignment |
| Product Managers | Business Analyst, UX Designer/Researcher, Scrum Master | Prioritization, requirement quality, outcome validation |
| Developers | Scrum Master, UX Designer/Researcher, Business Analyst, Release Manager | Feasible implementation, blocker escalation, release readiness |
| QA/Testing | Release Manager, Business Analyst, UX Designer/Researcher, Developers | Validation quality, test readiness, acceptance and accessibility checks |

### Collaboration Guidance
- Keep a shared backlog refinement cadence including Product Managers, Business Analysts, and Developers.
- Include UX and QA/Testing input in acceptance criteria before sprint commitment.
- Run release readiness checkpoints led by Release Managers with Development and QA/Testing sign-off.
- Use Scrum Masters and Project Managers together to escalate cross-functional blockers early.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
