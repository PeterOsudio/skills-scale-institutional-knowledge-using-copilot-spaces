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
- **Product Managers**: Clarifies requirements and acceptance criteria
- **Project Managers**: Provides estimates and reports on progress
- **DevOps Engineers**: Collaborates on infrastructure and deployment needs
- **QA Lead**: Works with on test coverage and bug fixes
- **UX Designer**: Implements designs and provides implementation feedback
- **Release Manager**: Coordinates code freeze and release readiness

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
- **Developers**: Provides requirements and accepts completed features
- **Project Managers**: Aligns on roadmap priorities and timelines
- **UX Designer**: Collaborates on user needs and design direction
- **Stakeholder Liaison**: Shares product vision and receives market feedback
- **QA Lead**: Defines acceptance criteria and quality expectations
- **Release Manager**: Prioritizes features for release planning

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
- **Product Managers**: Aligns on priorities and scope decisions
- **Developers**: Tracks progress and removes blockers
- **Release Manager**: Coordinates release schedules with project plans
- **DevOps Engineer**: Manages infrastructure dependencies and risks
- **Stakeholder Liaison**: Provides status for stakeholder communication
- **QA Lead**: Coordinates testing schedules and quality gates

---

## Release Manager

### Role Summary
Release Managers coordinate and oversee the release process, ensuring that software is delivered to production safely, on schedule, and with appropriate quality controls. They work closely with Developers, DevOps Engineers, QA Leads, and stakeholders to orchestrate releases.

### Responsibilities
- Plan and schedule releases in coordination with Product and Project Managers
- Coordinate release readiness reviews and go/no-go decisions
- Manage release documentation, including release notes and deployment runbooks
- Facilitate release retrospectives and continuous improvement
- Communicate release status and risks to stakeholders
- Ensure compliance with release policies and approval processes

### Goals
- Deliver predictable, low-risk releases
- Minimize production incidents related to deployments
- Improve release velocity and reduce lead time
- Maintain clear release documentation and audit trails

### Typical Communication
- Release planning meetings with PMs and engineering leads
- Go/no-go meetings with stakeholders before major releases
- Release announcements and status updates
- Post-release retrospectives

### Interactions with Other Roles
- **Developers**: Reviews code freeze schedules, coordinates merge readiness
- **DevOps Engineers**: Collaborates on deployment automation and monitoring
- **QA Lead**: Validates test completion and quality gates
- **Product Managers**: Aligns release scope with roadmap priorities
- **Project Managers**: Coordinates release timelines with project schedules
- **Stakeholder Liaison**: Provides release updates for external communication

---

## Stakeholder Liaison

### Role Summary
Stakeholder Liaisons serve as the primary interface between the project team and external stakeholders (executives, customers, partners, support teams). They translate technical progress into business-relevant updates and gather feedback to inform project decisions.

### Responsibilities
- Identify and map stakeholder groups and their communication needs
- Prepare and deliver status updates, presentations, and reports
- Gather stakeholder feedback and requirements
- Manage stakeholder expectations and escalations
- Coordinate cross-functional alignment meetings
- Ensure stakeholder concerns are addressed and documented

### Goals
- Maintain stakeholder confidence and alignment
- Minimize surprises and miscommunication
- Ensure stakeholder input informs product decisions
- Build strong relationships across organizational boundaries

### Typical Communication
- Weekly or milestone-based stakeholder updates
- Executive briefings and presentations
- Stakeholder feedback sessions
- Escalation management and resolution updates

### Interactions with Other Roles
- **Product Managers**: Translates product vision for stakeholders and brings market feedback
- **Project Managers**: Coordinates on project status and risk communication
- **Release Manager**: Communicates release schedules and impacts
- **Developers**: Gathers technical context for stakeholder questions
- **UX Designer**: Shares user feedback and stakeholder design preferences

---

## DevOps Engineer

### Role Summary
DevOps Engineers build, maintain, and improve the infrastructure, deployment pipelines, and operational tools that enable rapid, reliable software delivery. They bridge development and operations, focusing on automation, observability, and reliability.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage infrastructure as code and cloud resources
- Implement monitoring, logging, and alerting systems
- Optimize build times and deployment processes
- Respond to production incidents and participate in on-call rotation
- Ensure security best practices in infrastructure and deployments

### Goals
- Achieve high deployment frequency with low failure rates
- Minimize mean time to recovery (MTTR) for incidents
- Maintain infrastructure reliability and performance
- Enable developer productivity through automation

### Typical Communication
- Daily standups and sprint planning
- Incident response and post-mortems
- Infrastructure design reviews
- Deployment coordination with Release Managers

### Interactions with Other Roles
- **Developers**: Provides tooling, reviews infrastructure requirements
- **Release Manager**: Executes deployment plans and provides deployment status
- **QA Lead**: Maintains test environments and test automation infrastructure
- **Project Managers**: Reports on infrastructure risks and dependencies
- **Product Managers**: Advises on technical constraints and infrastructure costs

---

## QA Lead

### Role Summary
QA Leads define and oversee quality assurance strategy, processes, and execution. They ensure that products meet quality standards through test planning, automation, and continuous improvement of testing practices.

### Responsibilities
- Define test strategy and quality standards
- Plan and coordinate test execution across releases
- Build and maintain test automation frameworks
- Review and approve test coverage and results
- Identify quality risks and coordinate mitigation
- Lead bug triage and prioritization sessions
- Mentor QA team members and promote quality culture

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and automation rates
- Reduce time spent on manual testing
- Improve product quality and user satisfaction

### Typical Communication
- Test status reports and quality dashboards
- Bug triage meetings
- Test plan reviews with Developers and Product Managers
- Quality gate approvals for releases

### Interactions with Other Roles
- **Developers**: Reviews test coverage, collaborates on test automation
- **Release Manager**: Provides quality sign-off for releases
- **DevOps Engineer**: Coordinates on test infrastructure and CI integration
- **Product Managers**: Validates acceptance criteria and user scenarios
- **UX Designer**: Tests user flows and accessibility standards

---

## UX Designer

### Role Summary
UX Designers research user needs, design intuitive interfaces, and ensure products deliver excellent user experiences. They collaborate with Product Managers, Developers, and stakeholders to balance user needs with technical and business constraints.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define user flows and interaction patterns
- Establish and maintain design systems and style guides
- Validate designs through user testing and feedback
- Collaborate with Developers on implementation feasibility
- Ensure accessibility and inclusive design standards

### Goals
- Create intuitive, user-centered product experiences
- Improve user satisfaction and engagement metrics
- Reduce user friction and support escalations
- Maintain design consistency across products

### Typical Communication
- Design reviews and critique sessions
- User research presentations
- Collaborative design workshops
- Implementation reviews with Developers

### Interactions with Other Roles
- **Product Managers**: Translates product requirements into user experiences
- **Developers**: Collaborates on design implementation and feasibility
- **QA Lead**: Defines user acceptance testing scenarios
- **Stakeholder Liaison**: Gathers stakeholder design feedback and preferences
- **Project Managers**: Provides design milestone estimates and dependencies

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

