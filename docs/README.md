# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs. This directory contains standardized processes, templates, and guidance for running projects at OctoAcme. Whether you're starting a new project, managing execution, or closing out a release, you'll find practical workflows and checklists here.

## Quick Start

New to OctoAcme projects? Here's where to go:

- **First time here?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Planning sprint work?** See [Project Planning](./octoacme-project-planning.md)
- **Managing daily execution?** Check [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Handling risks and updates?** Refer to [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Preparing a release?** Review [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Running retrospectives?** See [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- **Understanding team roles?** Check [Roles & Personas](./octoacme-roles-and-personas.md)

## Our Project Management Approach

OctoAcme runs projects with five core principles:

### 1. **Customer-First**
We prioritize customer value and usability in all decisions. Every feature, sprint, and release is evaluated through the lens of customer impact.

### 2. **Iterative Delivery**
We deliver small, testable increments rather than big-bang releases. This allows for faster feedback, reduced risk, and continuous improvement.

### 3. **Clear Ownership**
Each project has a named Project Manager (PM) and Product Manager (PdM). Clear roles and responsibilities ensure accountability and faster decision-making.

### 4. **Data-Informed Decisions**
We measure impact and iterate based on evidence. Success metrics are defined upfront, tracked throughout execution, and inform post-release analysis.

### 5. **Psychological Safety**
We encourage feedback, learning, and blameless retrospectives. Team members feel safe raising concerns, suggesting improvements, and sharing lessons learned.

## Project Lifecycle

All OctoAcme projects follow a consistent five-phase lifecycle:

```
Initiation → Planning → Execution → Release → Close & Retrospective
```

### Phase 1: Initiation
**Goal:** Validate the business need and get stakeholder alignment

- Confirm the problem statement and measurable outcome
- Identify stakeholders and champions
- Define success criteria and initial timeline
- Create a lightweight Project One-pager
- **Gate:** Is the problem clear? Are stakeholders aligned? → Move to Planning

### Phase 2: Planning
**Goal:** Turn an approved initiative into an actionable plan

- Conduct project kickoff with team and stakeholders
- Break work into shippable increments with acceptance criteria
- Estimate scope using T-shirt sizing or story points
- Define Definition of Done and quality standards
- Identify dependencies and integration points
- Create release plan and milestone map
- **Gate:** Is work ready to start? Are dependencies clear? → Move to Execution

### Phase 3: Execution
**Goal:** Deliver work while maintaining quality and communication

- Run daily standups (15 min) to surface blockers
- Weekly delivery syncs with PM, PdM, and stakeholders
- Use project board (GitHub Projects) to track work flow
- Execute PR workflow with automated testing and code review
- Conduct regular demos and reviews at sprint or milestone end
- Track velocity and update risk register weekly
- Escalate blockers through defined channels

### Phase 4: Release
**Goal:** Deploy features to production safely and predictably

- Verify all acceptance criteria met and PRs merged
- Confirm passing CI, security scans, and smoke tests
- Draft release notes and document rollback plan
- Deploy to staging and run final verifications
- Deploy to production using automated pipeline when possible
- Run post-deploy checks and announce release
- **If issues occur:** Execute rollback and trigger incident response

### Phase 5: Close & Retrospective
**Goal:** Capture learnings and convert them into improvements

- Run a retrospective (45–75 min) covering what went well, what to improve, and action items
- Prioritize 2–3 top action items to avoid overload
- Track improvements in the backlog with owners and due dates
- Review outstanding actions in weekly PM sync
- Measure impact of improvements and celebrate wins

## Core Roles

Every OctoAcme project uses these key roles. Individual team members may wear multiple hats:

### Project Manager (PM)
**Owns:** Delivery schedule, risk management, cross-team coordination, stakeholder communication

**Key Activities:**
- Create and maintain project plans and timelines
- Identify and escalate risks and dependencies
- Facilitate meetings (kickoff, planning, retrospectives)
- Produce weekly status reports and stakeholder updates
- Ensure consistent project documentation

**Success Looks Like:** Projects deliver on time and within scope with minimal unplanned work

---

### Product Manager (PdM)
**Owns:** Product vision, backlog prioritization, success metrics, outcome validation

**Key Activities:**
- Define problem statements and success criteria
- Prioritize the roadmap and backlog based on customer value
- Write acceptance criteria for backlog items
- Validate solutions through user research and metrics
- Collaborate with engineering on trade-offs

**Success Looks Like:** Features deliver customer value and move key metrics

---

### Developers
**Owns:** Implementation, code quality, testing, technical design

**Key Activities:**
- Implement features to meet acceptance criteria
- Write and maintain unit and integration tests
- Participate in design and code reviews
- Assist in estimating and planning work
- Identify and propose mitigations for technical risks

**Success Looks Like:** Reliable, maintainable code ships quickly with high test coverage

---

### QA / Testing
**Owns:** Quality validation, acceptance criteria verification, test coverage

**Key Activities:**
- Validate features against acceptance criteria
- Design and execute integration and end-to-end tests
- Perform manual QA when needed
- Identify and triage quality issues
- Contribute to test coverage and automation strategy

**Success Looks Like:** Features pass quality gates before release with high confidence

---

### Stakeholders
**Owns:** Business context, approvals, resource allocation

**Key Activities:**
- Provide inputs on problem statement and success metrics
- Approve project charter and major decisions
- Attend milestone reviews and demos
- Provide feedback and context during execution
- Escalate business-impacting risks

**Success Looks Like:** Business objectives are met and stakeholder expectations are aligned

## Communication Cadence

OctoAcme projects maintain regular touchpoints to ensure alignment:

- **Daily:** Team standups (15 min)
- **2x per week:** Delivery team sync or sprint planning
- **Weekly:** PM + PdM alignment meeting
- **Monthly:** Stakeholder updates and roadmap review
- **As needed:** Escalations and incident response

## Key Artifacts

Every project maintains these core documents:

| Artifact | Owner | Purpose |
|----------|-------|---------|
| Project One-pager | PM + PdM | Define problem, goal, metrics, timeline, risks |
| Backlog & Roadmap | PdM | Prioritized list of work with acceptance criteria |
| Release Plan | PM + PdM | Milestones, dependencies, and release schedule |
| Risk Register | PM | Track risks, likelihood, impact, and mitigations |
| Sprint/Iteration Board | Team | Visual workflow (Backlog, Ready, In Progress, Review, QA, Done) |
| Retrospective Notes | PM | Capture learnings and action items |

## How to Use These Docs

### For New Team Members
1. Start with the **Project Management Overview** for context
2. Read **Roles & Personas** to understand your team
3. Skim the other docs to see where information lives
4. Bookmark this README for easy reference

### For Project Managers
1. Use **Project Initiation** checklist when kicking off a new project
2. Reference **Project Planning** when creating the backlog and milestones
3. Follow **Execution & Tracking** for daily team management
4. Use **Risk Management & Communication** for status updates and escalations
5. Use **Release & Deployment** checklist before shipping
6. Run retrospectives using **Retrospective & Continuous Improvement** guide

### For Product Managers
1. Use **Project Initiation** to define the One-pager and success metrics
2. Reference **Project Planning** when writing acceptance criteria
3. Collaborate with PM on **Execution & Tracking** metrics and demos
4. Use **Risk Management & Communication** for stakeholder updates
5. Participate in **Retrospective & Continuous Improvement** to measure impact

### For Developers and QA
1. Review **Roles & Personas** to understand your responsibilities
2. Reference **Project Planning** for acceptance criteria and Definition of Done
3. Follow **Execution & Tracking** for PR workflow and quality standards
4. Check **Release & Deployment** before shipping

---

## Questions or Feedback?

These docs are living artifacts. If you have feedback, find gaps, or want to propose improvements:
1. Create an issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
2. Tag it with `documentation` and `process improvement` labels
3. Include your suggested content and rationale

Let's continuously improve how we run projects at OctoAcme.
