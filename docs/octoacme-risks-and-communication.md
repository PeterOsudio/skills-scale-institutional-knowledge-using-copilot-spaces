# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies. This guide defines roles and their interactions in risk management and stakeholder communication processes.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call

## Role Interactions in Risk Management

### Risk Identification
**All Team Members** can identify risks:
- **Developers** identify technical risks, dependencies, and implementation challenges
- **DevOps Engineers** identify infrastructure and operational risks
- **QA Lead** identifies quality and testing risks
- **Product Manager** identifies market, customer, and scope risks
- **Project Manager** consolidates risks from all sources into risk register

### Risk Assessment and Prioritization
**Project Manager** leads assessment:
- Facilitates risk assessment sessions with team
- Works with **Product Manager** to understand business impact
- Consults **Developers** and **DevOps Engineers** on technical likelihood
- Documents risk assessment in risk register

### Risk Mitigation Planning
**Risk Owner** (assigned by Project Manager) develops mitigation:
- Creates mitigation plan specific to the risk area
- Coordinates with **Project Manager** on resource needs
- Engages relevant Subject Matter Experts (SMEs) (e.g., **DevOps Engineer** for infrastructure risks)
- Reports progress on mitigation actions

### Risk Monitoring and Communication
**Project Manager** monitors and reports:
- Reviews risk status weekly with team leads
- Escalates high-impact risks to **Product Manager** and stakeholders
- Updates **Stakeholder Liaison** on risks requiring external communication
- Maintains risk register and historical record

## Role Interactions in Stakeholder Communication

### Regular Status Updates

**Project Manager** prepares status:
- Gathers progress updates from **Developers**, **QA Lead**, and **DevOps Engineer**
- Compiles risks, blockers, and decisions needed
- Reviews with **Product Manager** for prioritization context
- Provides status to **Stakeholder Liaison** for distribution

**Stakeholder Liaison** distributes updates:
- Translates technical status into business-relevant updates
- Tailors messaging for different stakeholder audiences
- Distributes through appropriate channels
- Collects and synthesizes stakeholder feedback
- Reports feedback and concerns to **Project Manager** and **Product Manager**

### Release Communication

**Release Manager** coordinates release communication:
- Prepares release announcement with key changes and impacts
- Works with **Product Manager** on customer-facing messaging
- Coordinates timing with **Stakeholder Liaison**
- Provides technical details to support teams

**Stakeholder Liaison** manages release communication:
- Announces release to stakeholder groups
- Coordinates with customer success and support teams
- Monitors stakeholder reactions and questions
- Escalates issues to **Release Manager** or **Product Manager**

### Incident Communication

**Incident Commander** (typically Release Manager or DevOps Engineer) leads response:
- Declares incident and severity level
- Establishes incident communication channel
- Provides regular status updates during incident
- Coordinates with **Stakeholder Liaison** on external communication
- Makes decisions on mitigation actions

**Stakeholder Liaison** manages external communication:
- Crafts incident notifications for affected stakeholders
- Provides regular status updates based on incident commander input
- Manages stakeholder expectations on resolution timeline
- Communicates post-incident summary and learnings

**Project Manager** tracks post-incident actions:
- Documents incident timeline and decisions
- Facilitates blameless post-mortem with all involved roles
- Tracks action items to completion
- Updates risk register based on incident learnings

## Communication Flow for Decision Escalations

1. **Team Level**: 
   - Issue identified by any team member
   - Discussed in standups or team meetings
   - **Project Manager** facilitates decision if consensus reached

2. **PM Level**:
   - **Project Manager** escalates if team cannot resolve
   - **Product Manager** involved for scope/priority decisions
   - **Release Manager** involved for release timeline decisions

3. **Leadership Level**:
   - **Product Manager** escalates to Product Lead for strategic decisions
   - **Stakeholder Liaison** involved for stakeholder impact assessment
   - Executive sponsor engaged for high-impact decisions

4. **Cross-Functional Escalations**:
   - **DevOps Engineer** escalates infrastructure issues to infrastructure team
   - **QA Lead** escalates quality concerns to **Product Manager** and **Release Manager**
   - **UX Designer** escalates design conflicts to **Product Manager**

## Communication Best Practices by Role

**Developer**: Focus on technical details, provide clear reproduction steps for issues, document assumptions

**Product Manager**: Provide business context, explain priority rationale, maintain clear acceptance criteria

**Project Manager**: Maintain transparency, use data-driven status reports, proactively communicate risks

**Release Manager**: Communicate release schedules clearly, provide adequate notice for changes, document decisions

**DevOps Engineer**: Alert on infrastructure issues early, provide clear incident status, document system changes

**QA Lead**: Provide objective quality assessments, document test coverage gaps, escalate quality risks promptly

**UX Designer**: Explain design rationale, provide user research context, communicate design constraints

**Stakeholder Liaison**: Translate technical jargon, tailor message to audience, respond to feedback promptly
