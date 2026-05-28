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
- **QA Engineers**: Work closely to ensure acceptance criteria are clear and testable; support QA in reproducing and fixing defects
- **DevOps/Release Engineers**: Collaborate on deployment requirements and CI/CD integration
- **UX/UI Designers**: Implement design specifications and feedback iteratively

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
- **Business Analysts**: Refine requirements and validate stakeholder alignment before handoff to developers
- **UX/UI Designers**: Collaborate on user research, product vision, and usability validation
- **Project Managers**: Align on priorities, timelines, and resource allocation
- **QA Engineers**: Define success criteria and validation approach

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
- **Product Managers**: Align on scope, priorities, and delivery schedules
- **DevOps/Release Engineers**: Coordinate release schedules and deployment windows
- **Business Analysts**: Ensure requirements are clearly documented and handoff is smooth
- **All roles**: Facilitate communication and resolve escalations

---

## QA Engineers

### Role Summary
QA Engineers ensure software quality through comprehensive testing, defect management, and validation. They collaborate with developers, product managers, and business stakeholders to verify that features meet acceptance criteria and quality standards.

### Responsibilities
- Create and execute comprehensive test plans aligned with acceptance criteria
- Perform manual and automated testing across functional, integration, and end-to-end scenarios
- Identify, triage, and track defects with clear reproduction steps
- Collaborate on Definition of Done and acceptance criteria clarity
- Validate fixes and support sign-off for feature completion
- Contribute to test automation strategy and CI/CD integration
- Perform smoke testing and regression testing before releases
- Document and communicate quality metrics and risk areas

### Goals
- Prevent defects from reaching production
- Reduce cycle time from development to release
- Maintain high quality standards and customer satisfaction
- Build a culture of shared quality ownership

### Typical Communication
- Daily standups and sprint planning
- Test plan reviews with developers and product managers
- Defect reports with clear details for reproduction
- QA sign-off on acceptance criteria

### Interactions with Other Roles
- **Developers**: Clarify acceptance criteria, report defects with reproduction steps, and collaborate on testability during development
- **Product Managers**: Validate features meet business requirements and user expectations
- **DevOps/Release Engineers**: Support pre-release and post-deploy smoke testing
- **UX/UI Designers**: Validate user experience and usability during testing

---

## UX/UI Designers

### Role Summary
UX/UI Designers shape the user experience and visual interface of products. They conduct user research, create prototypes, and collaborate with product and engineering teams to ensure solutions are usable, accessible, and aligned with user needs.

### Responsibilities
- Conduct user research and usability testing to inform design decisions
- Create wireframes, mockups, prototypes, and design specifications
- Develop and maintain design systems and component libraries
- Iterate on designs based on feedback from developers, product managers, and users
- Provide design guidance and review throughout implementation
- Ensure accessibility standards (WCAG) are met
- Collaborate on user flows and information architecture
- Document design decisions and rationale

### Goals
- Deliver intuitive, accessible user experiences that drive adoption and satisfaction
- Reduce time-to-market through early prototyping and validation
- Maintain design consistency across the product

### Typical Communication
- Design review sessions with developers and product managers
- Prototype walkthroughs and user testing feedback
- Design specification docs and component handoff documentation
- Async feedback and iteration cycles

### Interactions with Other Roles
- **Product Managers**: Collaborate on user research, product vision, and feature prioritization
- **Developers**: Provide design specifications, iterate on implementation feedback, and support design QA
- **QA Engineers**: Validate usability and design implementation during testing
- **Business Analysts**: Align on user workflows and business requirements

---

## DevOps / Release Engineers

### Role Summary
DevOps and Release Engineers own the infrastructure, automation, and deployment processes that enable safe, reliable releases. They work across teams to ensure systems are observable, scalable, and resilient.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage environment configuration, infrastructure, and secrets
- Implement monitoring, logging, and alerting for observability
- Support developers in troubleshooting production issues
- Create and maintain rollback and disaster recovery procedures
- Collaborate on release planning and deployment windows
- Conduct pre-release and post-deploy verification
- Document runbooks and incident response procedures

### Goals
- Enable fast, safe releases with minimal manual effort
- Maximize system reliability and uptime
- Reduce mean time to recovery (MTTR) for incidents
- Build a culture of shared operational responsibility

### Typical Communication
- Weekly release coordination and planning
- Deployment runbooks and incident response documentation
- Pre-release readiness reviews
- Post-incident blameless retrospectives

### Interactions with Other Roles
- **Developers**: Support CI/CD integration, environment setup, and production troubleshooting
- **Project Managers**: Coordinate release schedules and deployment windows
- **QA Engineers**: Support pre-release smoke testing and post-deploy verification
- **Business Stakeholders**: Communicate release status and incident updates

---

## Business Analysts

### Role Summary
Business Analysts bridge business needs and technical implementation. They gather, clarify, and document requirements, validate stakeholder alignment, and ensure projects deliver measurable business value.

### Responsibilities
- Gather and document business requirements from stakeholders
- Conduct interviews and workshops to clarify scope and success criteria
- Create process flows, user stories, and acceptance criteria
- Validate requirements alignment with project goals and constraints
- Identify dependencies, risks, and business impacts
- Support scope management and change control
- Communicate requirements clearly to product and engineering teams
- Track project progress against business objectives

### Goals
- Ensure clear alignment between business needs and technical delivery
- Reduce scope creep and rework through thorough requirements validation
- Enable faster decision-making with clear documentation
- Maximize business value and ROI

### Typical Communication
- Requirements gathering sessions with stakeholders
- Requirement documentation and user story refinement
- Scope and change control discussions
- Business impact and metrics tracking

### Interactions with Other Roles
- **Product Managers**: Refine requirements, validate priorities, and define success metrics
- **Project Managers**: Support planning, risk identification, and stakeholder communication
- **Developers**: Clarify requirements during implementation and support acceptance testing
- **Stakeholders**: Gather needs, communicate progress, and validate delivered value

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions with Other Roles" section to understand collaboration patterns and communication expectations.
