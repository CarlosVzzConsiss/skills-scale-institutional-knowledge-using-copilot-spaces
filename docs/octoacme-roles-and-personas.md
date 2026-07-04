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

## Scrum Masters / Agile Coaches

### Role Summary
Scrum Masters facilitate agile processes and remove impediments for development teams. They serve the team by promoting self-organization, continuous improvement, and adherence to agile practices.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove blockers and impediments preventing team progress
- Coach team members on agile practices and mindset
- Maintain sprint metrics and burndown visibility
- Help resolve conflicts and foster team collaboration
- Support adoption of agile tools and processes

### Goals
- Enable teams to self-organize and make decisions autonomously
- Maximize team velocity and predictability
- Foster a culture of continuous improvement and psychological safety
- Reduce process overhead and ceremony waste

### Typical Communication
- Facilitate sprint ceremonies and team huddles
- Impediment tracking and escalation reports
- Metrics dashboards (velocity, burndown, cycle time)
- Coaching conversations and retrospective action items

### Interaction with Existing Roles
- Works closely with Project Managers to align schedules and dependencies
- Supports Developers by removing technical and organizational blockers
- Partners with Product Managers on backlog refinement and prioritization clarity
- Reports escalations to Project Managers when organizational barriers emerge

---

## Quality Assurance (QA) Engineers

### Role Summary
QA Engineers ensure product quality through testing, test automation, and quality standards enforcement. They work cross-functionally to identify defects, validate acceptance criteria, and improve quality.

### Responsibilities
- Design and execute test plans for features and releases
- Develop and maintain automated test suites
- Perform exploratory testing and identify edge cases
- Report and track defects with clear reproduction steps
- Define quality gates and acceptance criteria with developers and product managers
- Collaborate on test coverage and observability improvements

### Goals
- Achieve high product quality and customer satisfaction
- Reduce defects escaping to production
- Build confidence through comprehensive test coverage and traceability
- Enable rapid, risk-managed releases

### Typical Communication
- Test plans and test case documentation
- Defect reports with severity and reproduction details
- Quality metrics (pass rates, defect trends, coverage reports)
- Release readiness assessments and sign-offs

### Interaction with Existing Roles
- Partners with Developers on test-driven development and automation
- Validates acceptance criteria with Product Managers before development
- Provides quality status to Project Managers for release planning
- Supports Scrum Masters in defining definition-of-done and quality standards

---

## DevOps / Site Reliability Engineers (SRE)

### Role Summary
DevOps and SRE roles focus on infrastructure, deployment automation, system reliability, and operational excellence. They enable safe, frequent releases and ensure systems remain stable and performant.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage infrastructure, environments, and configuration as code
- Monitor system health, performance, and security
- Respond to incidents and conduct post-mortems
- Optimize system reliability, scalability, and cost efficiency
- Document runbooks and operational procedures
- Collaborate on production readiness and deployment strategies

### Goals
- Enable rapid, safe deployments with low change failure rates
- Maximize system uptime and performance
- Reduce toil through automation
- Ensure security, compliance, and disaster recovery posture

### Typical Communication
- Deployment checklists and release notes
- Infrastructure and deployment documentation
- Incident reports and post-mortems
- Monitoring dashboards and alerting configuration
- SLO/SLA metrics and operational reviews

### Interaction with Existing Roles
- Works with Developers on deployment practices and observability instrumentation
- Partners with Project Managers on release timing and rollout strategies
- Supports QA Engineers with test environment provisioning and production validation
- Advises on risk mitigation and reliability concerns during planning

---

## Stakeholders / Business Sponsors

### Role Summary
Stakeholders represent business, customer, or organizational interests. They provide direction, approval, and resources, and hold the team accountable for outcomes.

### Responsibilities
- Define business objectives and success criteria
- Approve roadmap priorities and resource allocation
- Provide executive sponsorship and organizational support
- Review and approve project status, risks, and decisions
- Communicate outcomes and impact to broader organization
- Make strategic trade-off decisions

### Goals
- Achieve business objectives and ROI
- Maintain alignment across organizational priorities
- Reduce risk of project failure or misalignment
- Enable informed decision-making with clear visibility

### Typical Communication
- Executive steering meetings and governance reviews
- Roadmap and business case reviews
- Risk escalations and decision requests
- Status summaries and impact reports

### Interaction with Existing Roles
- Works with Product Managers to align product strategy with business objectives
- Receives status and risk updates from Project Managers
- Escalates organizational barriers and provides executive support
- Reviews quality and delivery outcomes from the full team

---

## Additional Personas (new)

### Technical Program Manager (TPM)

#### Role Summary
Coordinates complex, cross-team technical programs and translates technical dependencies into planable work.

#### Responsibilities
- Drive cross-team schedules and program milestones
- Own program-level risks and mitigations
- Coordinate integration testing, cutovers, and release windows
- Maintain program status and dashboards

#### Typical Communication
- Program-level status updates, dependency lists, and integration notes
- Weekly syncs with PMs, engineering leads, and SRE

#### Interaction with Existing Roles
- Works with Project Managers and Product Managers to align timelines and scope
- Collaborates with Developers and SRE on technical dependencies and integration testing
- Escalates organization-level blockers to Stakeholders when needed

---

### UX Researcher / Designer

#### Role Summary
Owns user research, interaction design, and ensures solutions meet usability goals.

#### Responsibilities
- Plan and run user research and usability tests
- Create prototypes and interaction specs
- Define usability acceptance criteria and collaborate on accessibility checks
- Handoff assets and guidelines to engineering

#### Typical Communication
- Research reports, design specs, and prototype links
- Design reviews and acceptance criteria conversations

#### Interaction with Existing Roles
- Partners with Product Managers to inform requirements and prioritization
- Works with Developers to clarify designs and acceptance criteria
- Collaborates with QA on usability and exploratory testing

---

### Data Engineer / Analyst

#### Role Summary
Ensures data pipelines, metrics, and instrumentation needed to measure success are available and reliable.

#### Responsibilities
- Design and maintain data schemas and ETL pipelines
- Implement telemetry and event instrumentation
- Create dashboards and validate success metrics
- Support ad-hoc analysis and reporting

#### Typical Communication
- Dashboards, data contracts, and instrumentation checklists
- Metric definition meetings with Product and PMs

#### Interaction with Existing Roles
- Works with Product Managers to define measurable success and KPIs
- Collaborates with Developers to implement instrumentation
- Helps QA validate metrics during testing

---

### Security Engineer

#### Role Summary
Provides security guidance, threat modeling, and reviews to reduce security risks.

#### Responsibilities
- Conduct threat modeling and security reviews
- Coordinate vulnerability remediation and patches
- Ensure compliance with security policies and standards
- Advise on secure design patterns and controls

#### Typical Communication
- Security review reports, risk assessments, and remediation timelines
- Security triage meetings and advisories

#### Interaction with Existing Roles
- Embedded during planning and design phases to identify risks early
- Works with SRE/Platform for production fixes
- Advises Product and PM on risk acceptance and compliance

---

### Release Manager

#### Role Summary
Owns release coordination, cutovers, and post-release validations for complex deployments.

#### Responsibilities
- Schedule releases and maintain release calendar
- Validate release readiness and run release checklists
- Coordinate rollback plans and communicate changes to stakeholders
- Facilitate post-release verification and monitoring

#### Typical Communication
- Release readiness checklists, deployment windows, and post-release summaries
- Cross-functional release coordination meetings

#### Interaction with Existing Roles
- Coordinates with PMs, DevOps/SRE, QA, and Product for release readiness
- Works with Platform teams for deployment support and monitoring

---

### Customer Success / Product Support Liaison

#### Role Summary
Represents customer-facing teams and ensures operational concerns and feedback are captured and prioritized.

#### Responsibilities
- Surface customer issues and feature requests
- Validate acceptance against real customer scenarios
- Coordinate escalations and provide post-release guidance to customers
- Maintain communication with stakeholders and support teams

#### Typical Communication
- Customer issue summaries, support tickets, and feedback reports
- Post-release customer impact analyses and recommendations

#### Interaction with Existing Roles
- Works with Product and PMs on prioritization of customer-facing issues
- Collaborates with QA to reproduce and validate reported bugs
- Escalates production issues to SRE and Project Managers as needed

---

### Accessibility Specialist

#### Role Summary
Ensures products meet accessibility standards and regulations.

#### Responsibilities
- Conduct accessibility audits and provide remediation guidance
- Create accessibility test cases and validation steps
- Advise on inclusive design and assist with policy compliance

#### Typical Communication
- Accessibility reports, test cases, and remediation plans
- Design and engineering guidance documents

#### Interaction with Existing Roles
- Partners with Designers, Developers, and QA to integrate accessibility into Definition of Done and acceptance criteria
- Works with Product to prioritize accessibility-related work

---

### Platform / Infrastructure Engineer

#### Role Summary
Manages shared infrastructure, CI/CD pipelines, and platform services teams rely on.

#### Responsibilities
- Maintain platform reliability and performance
- Support deployments and operational runbooks
- Implement scalability, security, and observability improvements
- Provide platform-aware guidance during planning

#### Typical Communication
- Platform status reports, runbooks, and incident summaries
- CI/CD pipeline and infrastructure change notices

#### Interaction with Existing Roles
- Supports Developers during planning for operational concerns
- Works with SRE on runbooks and post-incident improvements
- Coordinates with Release Manager for deployment readiness

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understanding cross-functional interactions helps teams coordinate effectively and reduce silos.
