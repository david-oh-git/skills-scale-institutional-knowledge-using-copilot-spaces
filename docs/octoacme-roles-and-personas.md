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

## UX Designers

### Role Summary
UX Designers conduct user research, create interface prototypes, and establish usability standards. They translate requirements into intuitive, accessible designs and validate solutions with users and stakeholders.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Establish design systems and accessibility standards
- Review implementations to ensure fidelity to design
- Collaborate on design trade-offs and feasibility with engineering
- Advocate for user needs throughout the project lifecycle

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce user friction and support burden
- Build a cohesive design language across products

### Interaction with Other Roles
- **Product Managers/PdMs**: Translate feature requirements into design specs; validate user research findings
- **Developers**: Conduct design reviews; provide guidance on implementation of UI/UX
- **QA Leads**: Define acceptance criteria for UX quality; collaborate on usability test plans
- **Support/CS**: Incorporate user feedback and common pain points into future iterations

### Typical Communication
- Design critiques and stakeholder reviews
- Design specification documents and component libraries
- Usability test reports and user research findings
- Async design feedback in design tools (Figma, Adobe XD, etc.)

---

## QA Leads

### Role Summary
QA Leads own the quality strategy for projects, manage test case development and execution, coordinate defect triage, and ensure that deliverables meet acceptance criteria before release.

### Responsibilities
- Define test strategy, test plans, and acceptance criteria
- Develop and maintain automated and manual test cases
- Execute test plans and coordinate test execution across environments
- Triage, prioritize, and track defects through resolution
- Establish quality metrics and reporting dashboards
- Validate critical flows through smoke testing before release
- Mentor QA team members and advocate for quality early in development

### Goals
- Ensure features meet acceptance criteria before release
- Reduce post-release defects and customer impact
- Improve test coverage and automation over time

### Interaction with Other Roles
- **Developers**: Clarify acceptance criteria; triage defects collaboratively; plan integration testing
- **Product Managers/PdMs**: Define success criteria and test scope; validate business requirements
- **Project Managers**: Report quality status and release readiness; escalate blockers
- **Release Managers**: Coordinate pre-release smoke testing; validate deployment quality gates

### Typical Communication
- Test plans and test case documentation
- Defect reports and quality dashboards
- Daily standups and sprint reviews
- Pre-release quality sign-off

---

## Release Managers

### Role Summary
Release Managers plan and execute releases, manage deployment windows, ensure runbook adherence, and coordinate rollback and incident response. They serve as the central coordinator for moving code from staging to production.

### Responsibilities
- Create and maintain release schedules and deployment plans
- Coordinate pre-release activities (testing, documentation, communication)
- Execute deployments following runbooks and safety checks
- Manage deployment windows and communicate status to stakeholders
- Plan and execute rollback procedures if issues are detected
- Ensure post-deployment verifications are completed
- Document release notes and migration steps
- Coordinate incident response and post-mortem activities

### Goals
- Deploy releases with minimal risk and downtime
- Maintain clear communication throughout the release cycle
- Reduce time-to-recovery in case of deployment issues

### Interaction with Other Roles
- **Developers**: Coordinate code cutoff dates; prepare deployment artifacts and runbooks
- **QA Leads**: Validate pre-release smoke tests; ensure quality gates are met
- **Support/CS**: Communicate release details; prepare support teams for changes
- **Project Managers**: Report on release status and timeline adherence

### Typical Communication
- Release schedules and deployment windows
- Deployment runbooks and change requests
- Release notes and migration documentation
- Incident response communications

---

## Technical Writers

### Role Summary
Technical Writers create and maintain technical documentation, user guides, API documentation, and release notes. They translate complex features into clear, accessible content for developers, operators, and end users.

### Responsibilities
- Create and maintain user documentation and help content
- Develop API documentation and technical references
- Write release notes and migration guides
- Ensure consistency in terminology and voice across documentation
- Collaborate with developers to capture technical details
- Review documentation for clarity, completeness, and accuracy
- Maintain documentation in accessible formats (web, PDF, in-app)

### Goals
- Reduce support burden through clear documentation
- Improve user adoption and self-service success
- Maintain accurate, up-to-date technical references

### Interaction with Other Roles
- **Developers**: Extract technical details; collaborate on code examples and API specs
- **Product Managers/PdMs**: Understand feature context and user scenarios
- **Support/CS**: Capture frequently asked questions and common issues
- **Release Managers**: Create release notes and migration documentation

### Typical Communication
- Documentation drafts and reviews
- Content management system (wiki, knowledge base)
- Feature specification kickoff meetings
- Post-release documentation updates

---

## Support & Customer Success Representatives

### Role Summary
Support and Customer Success Representatives serve as the voice of the customer within the project. They escalate customer issues, gather feedback, ensure knowledge transfer to support teams, and drive customer satisfaction.

### Responsibilities
- Escalate critical customer issues and bugs to the product team
- Gather and synthesize customer feedback and pain points
- Conduct customer interviews and usability sessions
- Prepare support teams for new features and changes
- Create knowledge base articles and FAQ content
- Track customer satisfaction metrics and NPS
- Identify patterns in customer issues for future improvements

### Goals
- Maximize customer satisfaction and reduce support burden
- Ensure customer voice informs product decisions
- Enable rapid support team onboarding to new features

### Interaction with Other Roles
- **Product Managers/PdMs**: Share customer feedback; inform prioritization
- **Developers**: Provide context on customer issues; validate fixes
- **Technical Writers**: Contribute to knowledge base and support documentation
- **Project Managers**: Report customer impact and escalation patterns

### Typical Communication
- Customer feedback summaries and issue escalations
- Customer interviews and session notes
- Support metrics and satisfaction reports
- Training sessions for support teams

---

## Governance & Compliance Leads

### Role Summary
Governance and Compliance Leads ensure that projects adhere to regulatory requirements, company policies, security standards, and audit requirements. They serve as guardians of risk mitigation and compliance.

### Responsibilities
- Define compliance requirements and standards for the project
- Review project artifacts (design, code, data handling) for compliance
- Conduct security and compliance audits
- Document compliance decisions and exceptions
- Ensure data privacy and protection measures are in place
- Coordinate with external auditors and regulatory bodies if needed
- Maintain compliance documentation and evidence

### Goals
- Ensure zero critical compliance violations
- Reduce regulatory and legal risk
- Build a culture of compliance and security awareness

### Interaction with Other Roles
- **Project Managers**: Define compliance checkpoints in timeline; escalate violations
- **Developers**: Review code and architecture for security and compliance
- **Product Managers/PdMs**: Ensure feature design meets privacy/compliance standards
- **Release Managers**: Validate deployment meets compliance requirements

### Typical Communication
- Compliance review documents and sign-offs
- Audit reports and risk assessments
- Security and compliance training materials
- Exception requests and approval logs

---

## Agile Coaches & Scrum Masters

### Role Summary
Agile Coaches and Scrum Masters facilitate Agile ceremonies, improve process adherence, remove delivery impediments, and foster a culture of continuous improvement. They act as servant leaders enabling the team to deliver effectively.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Coach the team on Agile principles and practices
- Identify and help resolve process impediments
- Maintain the project board and workflow visibility
- Coach the team on estimation, velocity tracking, and capacity planning
- Foster psychological safety and open communication
- Drive continuous improvement initiatives based on retrospectives
- Mentor new team members on Agile practices

### Goals
- Improve team velocity and predictability
- Foster a culture of psychological safety and continuous learning
- Reduce cycle time and delivery risk

### Interaction with Other Roles
- **Project Managers**: Collaborate on timelines and milestone planning
- **Product Managers/PdMs**: Facilitate backlog refinement and prioritization
- **Developers**: Coach on team ceremonies and process adherence
- **All Roles**: Support removal of impediments and process improvements

### Typical Communication
- Sprint planning and retrospective facilitation
- Impediment logs and escalation
- Velocity charts and burndown reports
- Improvement action items and tracking

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning a project, identify which roles are needed and ensure clear ownership and communication protocols.
