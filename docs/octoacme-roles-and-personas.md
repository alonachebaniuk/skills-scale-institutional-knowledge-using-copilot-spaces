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

## QA/Testing Lead

### Role Summary
The QA/Testing Lead defines and owns the quality strategy for the project. They work with developers and product managers to ensure features meet acceptance criteria, identify risks early, and coordinate testing efforts.

### Responsibilities
- Develop and maintain test plans and test strategies
- Define acceptance criteria and Definition of Done (testing aspect)
- Coordinate manual and automated testing efforts
- Identify quality risks and propose mitigation
- Report test coverage and defect metrics
- Validate features meet acceptance criteria before release

### Goals
- Ensure high-quality releases with minimal production defects
- Build confidence in the product through comprehensive testing
- Enable fast iteration with reliable automated tests

### Typical Communication
- Sprint planning and review meetings
- Test case design and QA status updates
- Defect reports and triage discussions
- Release readiness assessments

### Interaction with Other Roles
- **Developers**: Collaborate on test automation, code review from testability perspective
- **Product Managers**: Define acceptance criteria, prioritize test scenarios
- **Project Managers**: Flag quality risks, provide test readiness status

---

## Technical Lead/Architect

### Role Summary
The Technical Lead provides technical direction, design guidance, and architectural oversight. They work with the development team to make sound technical decisions that balance innovation, maintainability, and timeline.

### Responsibilities
- Guide technical design and architecture decisions
- Conduct design reviews and provide feedback
- Identify technical risks and propose solutions
- Mentor developers and foster technical growth
- Ensure alignment with organizational standards and best practices
- Advise on technology trade-offs and dependencies

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and support long-term scalability
- Enable team to make confident technical decisions

### Typical Communication
- Design review meetings and tech spec discussions
- Architecture decisions and RFCs (Request for Comments)
- Technical risk assessments
- Code review guidance and mentoring

### Interaction with Other Roles
- **Developers**: Mentor and guide on technical decisions
- **Product Managers**: Advise on feasibility and technical trade-offs
- **Project Managers**: Flag technical risks and dependencies

---

## Scrum Master/Agile Coach

### Role Summary
The Scrum Master facilitates agile processes, removes impediments, and coaches the team on continuous improvement. They work to foster psychological safety, transparency, and iterative delivery.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove blockers and impediments to team progress
- Coach team on agile principles and practices
- Maintain sprint backlog and burndown visibility
- Foster a culture of continuous improvement and learning
- Escalate systemic issues that block team effectiveness

### Goals
- Enable the team to operate efficiently and deliver consistently
- Build a high-performing, self-organizing team
- Maximize team velocity and reduce cycle time
- Create psychological safety for feedback and innovation

### Typical Communication
- Sprint ceremonies (planning, standup, review, retrospective)
- One-on-ones and team coaching conversations
- Impediment tracking and escalation
- Retrospective action item follow-up

### Interaction with Other Roles
- **Developers**: Coach on estimation, technical practices, and team dynamics
- **Product Managers**: Help prioritize backlog, manage scope changes
- **Project Managers**: Coordinate timelines, track impediments, escalate risks
- **Technical Leads**: Support technical coaching and design discussions

---

## Business Analyst

### Role Summary
The Business Analyst bridges the gap between business requirements and technical implementation. They gather, clarify, and document requirements to ensure solutions align with business needs and user expectations.

### Responsibilities
- Conduct stakeholder interviews and requirements gathering
- Document functional and non-functional requirements
- Create use cases, user stories, and acceptance criteria
- Validate requirements against business objectives
- Serve as liaison between business stakeholders and technical team
- Identify gaps and dependencies in requirements

### Goals
- Ensure clear, unambiguous requirements that reduce rework
- Maximize alignment between business needs and product delivery
- Minimize scope creep through clear definition of done
- Enable early identification of risks and trade-offs

### Typical Communication
- Stakeholder interviews and discovery sessions
- Requirements documentation and specifications
- User story creation and refinement
- Clarification discussions during planning and execution
- User acceptance testing coordination

### Interaction with Other Roles
- **Product Managers**: Collaborate on prioritization and business value assessment
- **Developers**: Clarify requirements and acceptance criteria during implementation
- **QA/Testing Lead**: Define test scenarios based on requirements
- **Project Managers**: Track requirement dependencies and change requests

---

## Release Manager

### Role Summary
The Release Manager coordinates and oversees the planning, preparation, and execution of software releases. They ensure releases are executed smoothly, with minimal risk and maximum communication.

### Responsibilities
- Create and maintain release plans and schedules
- Coordinate pre-release activities (testing, documentation, rollback planning)
- Manage deployment windows and communication with stakeholders
- Verify successful deployment and perform post-release checks
- Document release notes and known issues
- Coordinate rollback procedures if issues occur post-deployment

### Goals
- Deliver releases with minimal downtime and production issues
- Ensure all stakeholders are informed and prepared for releases
- Maintain clear audit trail and documentation for compliance
- Enable rapid response to post-deployment issues

### Typical Communication
- Release planning and stakeholder coordination meetings
- Pre-release checklists and readiness assessments
- Release notes and deployment instructions
- Post-deployment verification and incident coordination
- Stakeholder announcements and support briefings

### Interaction with Other Roles
- **Developers**: Coordinate code freeze, branch management, and deployment procedures
- **QA/Testing Lead**: Ensure smoke tests and acceptance criteria are met pre-release
- **Project Managers**: Track release schedule and identify dependencies
- **Operations/DevOps**: Coordinate infrastructure, monitoring, and deployment execution
- **Support/Customer Success**: Brief on new features and known issues

---

## Security Lead

### Role Summary
The Security Lead oversees security practices, threat assessment, and compliance throughout the project lifecycle. They work to ensure the product meets security standards and protects customer data.

### Responsibilities
- Conduct security threat modeling and risk assessments
- Define security requirements and acceptance criteria
- Review design and code for security vulnerabilities
- Coordinate security testing and remediation
- Ensure compliance with security standards and regulations
- Lead security incident response and post-incident reviews
- Provide security guidance and training to the team

### Goals
- Deliver secure-by-design products that protect customer data
- Identify and remediate security risks early in the lifecycle
- Maintain compliance with regulatory and organizational standards
- Build a security-aware culture across the team

### Typical Communication
- Security design reviews and threat modeling sessions
- Code review feedback on security best practices
- Security incident reports and remediation tracking
- Compliance and audit documentation
- Security training and awareness sessions

### Interaction with Other Roles
- **Developers**: Review code and provide security guidance, review secure coding practices
- **Technical Leads**: Advise on architecture and technology choices from security perspective
- **QA/Testing Lead**: Coordinate security testing and vulnerability scanning
- **Project Managers**: Flag security risks and escalate critical vulnerabilities
- **Release Manager**: Ensure security verification before production deployment

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, decision-making authority, and resource support for projects. They ensure projects align with strategic objectives and have necessary backing.

### Responsibilities
- Define business objectives and success criteria
- Make decisions on scope, timeline, and resource trade-offs
- Provide executive visibility and support for the project
- Ensure alignment with organizational strategy
- Remove organizational blockers and escalations
- Approve major milestones and gate decisions

### Goals
- Ensure projects deliver business value and ROI
- Maintain alignment across stakeholders and dependent teams
- Enable rapid decision-making to minimize delays
- Communicate project value to broader organization

### Typical Communication
- Project initiation and charter sign-off
- Milestone reviews and progress updates
- Executive steering committee meetings
- Escalation and blocker resolution
- Stakeholder engagement and communication

### Interaction with Other Roles
- **Project Managers**: Provide oversight, approve plans, and support escalation resolution
- **Product Managers**: Align on business objectives and success metrics
- **Developers**: Communicate business context and priorities
- **All Roles**: Ensure project stays aligned with business strategy

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference interaction patterns between roles to inform collaboration and communication practices.
