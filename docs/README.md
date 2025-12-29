# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This folder contains the canonical process documents used to plan, execute, and improve cross-functional projects at OctoAcme. Use this README as the entry point to find key workflows, roles, communication patterns, and quality practices used across projects.

OctoAcme runs projects using an iterative, cross-functional lifecycle that begins with a lightweight initiation phase and moves through planning, execution, release, and retrospective. Initiation centers on a Project One-pager to capture the problem, success metrics, stakeholders, and a high‑level timeline; once success criteria and stakeholder alignment are confirmed, teams create a prioritized backlog and release plan. Planning breaks work into shippable increments, defines a Definition of Done, identifies dependencies and risks in a Risk Register, and produces a sprint/iteration backlog used to guide execution and releases.

Day-to-day execution follows a structured workflow (Backlog → Ready → In Progress → In Review → QA → Done) using a project board and small pull requests that link to issues and acceptance criteria. Team rhythm includes short daily standups, weekly delivery syncs for progress and risk review, and demos at the end of each sprint or milestone. Tracking uses velocity, burndown, and dashboards for success metrics and operational signals; an execution checklist (branching/PR conventions, CI, demos, weekly risk register updates) keeps work predictable and transparent.

Roles and responsibilities are explicit: Project Managers coordinate delivery, schedules, and communications; Product Managers (PdMs) own outcomes and backlog prioritization; Developers implement and test features; QA validates acceptance criteria; and stakeholders provide input and approvals. Quality assurance is integrated across the pipeline—unit and integration tests, CI gating with automated test and security scans, end‑to‑end smoke tests for critical flows, and manual QA when needed—plus a checklist-driven release process with rollback plans and post‑deploy verification. Retrospectives capture learnings and convert them into backlog action items to drive continuous improvement.

Docs in this folder
- octoacme-project-management-overview.md — Project management overview and principles
- octoacme-project-initiation.md — Project One-pager and initiation checklist
- octoacme-project-planning.md — Planning, backlog, estimation, and risk management
- octoacme-execution-and-tracking.md — Execution workflows, PR conventions, metrics, and blockers
- octoacme-risks-and-communication.md — Risk register, stakeholder communications, and escalation paths
- octoacme-release-and-deployment.md — Release types, deployment checklist, rollback playbook
- octoacme-retrospective-and-continuous-improvement.md — Retrospective structure and action tracking
- octoacme-roles-and-personas.md — Role summaries and responsibilities

How to use
- Keep this README and the referenced files up to date as the single source of truth for project management processes.
- Link the Project One-pager and release notes from your project repo into these docs when applicable.
- Add action items from retrospectives back into the project backlog and track their status in the weekly PM sync.
