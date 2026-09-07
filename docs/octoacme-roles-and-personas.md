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
QA/Testing Leads define and execute testing strategies, ensure acceptance criteria are validated, and maintain quality standards across releases. They collaborate with developers and product teams to prevent defects and validate user experience.

### Responsibilities
- Define test strategies and acceptance criteria validation plans
- Create and maintain test plans, test cases, and QA documentation
- Coordinate QA resources and execution across sprints
- Identify quality risks and advocate for test coverage
- Conduct manual testing and validate acceptance criteria
- Collaborate with developers on reproducible test scenarios

### Goals
- Deliver high-quality features that meet acceptance criteria
- Prevent production defects through proactive testing
- Enable fast, confident releases

### Typical Communication
- Sprint planning and acceptance criteria reviews
- QA status updates in standups
- Test results and quality reports in release checklists

### Interaction with Other Roles
- **Developers**: Collaborate on test scenarios, share test results, and discuss acceptance criteria clarity
- **Product Managers**: Validate feature requirements and define quality acceptance criteria
- **Project Managers**: Report quality metrics, risks, and testing timelines in project syncs

---

## Technical Lead

### Role Summary
Technical Leads provide architectural guidance, identify technical risks, and ensure technical decisions align with product and business strategy. They mentor developers, conduct code reviews, and champion best practices.

### Responsibilities
- Review technical design and architecture decisions
- Identify technical risks and propose mitigations
- Mentor and guide development team on best practices
- Conduct or oversee code reviews
- Advocate for technical debt paydown
- Collaborate with product and project leads on technical trade-offs

### Goals
- Maintain code quality and system reliability
- Reduce technical risk and technical debt
- Enable sustainable, scalable development

### Typical Communication
- Technical design reviews and architecture discussions
- Code review comments and guidance
- Technical risk identification in planning and retrospectives

### Interaction with Other Roles
- **Developers**: Provide architectural guidance, mentor on best practices, and conduct code reviews
- **Project Managers**: Escalate technical risks and dependencies impacting project timelines
- **Product Managers**: Discuss technical trade-offs and feasibility of product requirements

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors provide business context, approve resource allocation, and escalate strategic risks. They represent the broader business interests and ensure project alignment with organizational goals.

### Responsibilities
- Provide business context and strategic alignment
- Approve project scope, timeline, and resource requests
- Escalate strategic and business-level risks
- Make go/no-go decisions at key gates
- Communicate project value to executive leadership

### Goals
- Ensure projects deliver business value
- Align resources with organizational priorities
- Manage business and strategic risk

### Typical Communication
- Monthly or milestone-based status updates
- Gate approval meetings
- Escalation of strategic issues

### Interaction with Other Roles
- **Project Managers**: Review project status, approve scope changes, and escalate critical blockers
- **Product Managers**: Align on business priorities, success metrics, and strategic direction
- **Developers & QA**: Communicate business context and release priorities at key milestones

---

## Subject Matter Expert (SME)

### Role Summary
Subject Matter Experts bring domain expertise on specific components, systems, or functional areas. They advise the team on implementation approaches, best practices, and integration points within their area of specialization.

### Responsibilities
- Provide expert guidance on domain-specific design and implementation decisions
- Review solutions for compliance with domain best practices and standards
- Advise on integration points and dependencies within their specialty
- Support documentation and knowledge transfer on specialized areas
- Identify risks and opportunities based on domain expertise

### Goals
- Ensure solutions leverage domain best practices and standards
- Reduce implementation risk in specialized areas
- Build team capability in domain expertise

### Typical Communication
- Design reviews and consultation on complex technical decisions
- Documentation and training sessions
- Risk identification and mitigation planning for specialized areas

### Interaction with Other Roles
- **Developers**: Mentor on domain-specific implementation and provide technical guidance
- **Technical Leads**: Collaborate on architectural decisions within their specialty
- **QA/Testing Lead**: Define quality criteria and test scenarios specific to the domain

---

## Operations/DevOps Engineer

### Role Summary
Operations and DevOps Engineers manage deployment infrastructure, production monitoring, and post-deployment support. They enable fast, reliable releases and maintain production system health.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment infrastructure
- Execute releases and coordinate deployment windows
- Monitor production systems and respond to operational issues
- Implement security scanning and compliance checks in CI
- Conduct post-deployment verification and rollback coordination
- Provide on-call support and incident response

### Goals
- Enable safe, fast deployments
- Maintain high system reliability and uptime
- Reduce mean time to recovery (MTTR) for incidents

### Typical Communication
- Release coordination and deployment planning
- Production incident alerts and post-mortems
- Infrastructure and CI/CD improvements in retrospectives

### Interaction with Other Roles
- **Developers**: Coordinate on build and deployment requirements, infrastructure setup
- **Project Managers**: Provide deployment timelines, infrastructure readiness, and incident impact
- **QA/Testing Lead**: Coordinate smoke tests and post-deployment verification

---

## UX/Design Lead

### Role Summary
UX/Design Leads collaborate with product and development teams to define user experience, interaction design, and visual consistency. They ensure features are usable, accessible, and aligned with product vision.

### Responsibilities
- Define user experience and interaction design for new features
- Create wireframes, prototypes, and design specifications
- Conduct user research and usability testing
- Establish and maintain design systems and consistency standards
- Collaborate with developers on implementability of designs
- Advocate for accessibility and user-centered design principles

### Goals
- Deliver intuitive, usable, and accessible user experiences
- Ensure consistent, cohesive product design across releases
- Maximize user satisfaction and adoption

### Typical Communication
- Design reviews and feedback sessions with product and development
- Usability testing findings and recommendations
- Design system updates and consistency guidelines

### Interaction with Other Roles
- **Product Managers**: Define feature requirements, user needs, and success metrics
- **Developers**: Collaborate on feasibility and implementation of designs
- **QA/Testing Lead**: Define acceptance criteria for user experience and accessibility

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When managing cross-functional projects, refer to the "Interaction with Other Roles" sections to understand communication and collaboration patterns.
