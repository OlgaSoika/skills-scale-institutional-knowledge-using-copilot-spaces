# OctoAcme Project Management Docs

This README serves as an entry point to all OctoAcme project management process documentation, capturing living knowledge and empowering anyone in the organization to understand and contribute to how projects are run.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a clear project lifecycle consisting of five phases: Initiation, Planning, Execution, Release, and Retrospective. Our core principles emphasize customer-first delivery, iterative development with small testable increments, clear ownership with named Project Managers and Product Leads, data-informed decisions based on evidence, and psychological safety that encourages feedback and learning.

Our project teams consist of well-defined roles with clear responsibilities. Project Managers coordinate delivery activities, manage schedules, risks, and communications. Product Managers define what should be built to deliver customer and business value, own the product vision, and prioritize the backlog. Developers design, build, test, and deliver software components while collaborating with leads to implement features that meet acceptance criteria. Each role has defined communication cadences including weekly syncs between PM and Product Lead, twice-weekly standups for delivery teams, and monthly stakeholder updates.

Quality assurance is integrated throughout the development process. We maintain unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. Security scanning is part of our CI pipeline, and manual QA is performed for feature acceptance when needed. Our risk management approach includes maintaining a risk register with impact assessments, likelihood ratings, owners, and mitigation plans, with consistent escalation paths from team-level to PM to Product Lead to Sponsor.

Key artifacts produced during projects include the Project Charter/One-pager, Roadmap and Release Plan, Sprint/Iteration Backlog, Acceptance Criteria and Definition of Done, Risk Register, and Retrospective notes with action items. These artifacts ensure transparency, alignment, and continuous improvement across all stakeholders.

## Docs Index

1. [Project Management Overview](octoacme-project-management-overview.md) - Introduction to how OctoAcme runs projects, roles, and key artifacts
2. [Project Initiation Guide](octoacme-project-initiation.md) - Initial steps to validate and authorize work, align stakeholders
3. [Project Planning](octoacme-project-planning.md) - Turn initiatives into actionable plans and backlogs
4. [Execution & Tracking](octoacme-execution-and-tracking.md) - Day-to-day execution and tracking progress
5. [Risk Management & Communication](octoacme-risks-and-communication.md) - Identify, manage, and communicate risks and dependencies
6. [Release & Deployment Guide](octoacme-release-and-deployment.md) - Standardize feature releases to production
7. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and convert them into improvements
8. [Roles and Personas](octoacme-roles-and-personas.md) - Typical roles and responsibilities in OctoAcme projects

## How to Use

- **Link from repo root:** Consider adding a link to this README from the repository's main README.md for easy discoverability.
- **Request updates:** To propose new content or updates to any process document, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
- **Add new guides:** When creating new process documentation, add it to the `docs/` folder and update this README's Docs Index for discoverability.
