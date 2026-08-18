# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management framework. This folder contains the processes, templates, and guidance used to plan, deliver, and improve projects at OctoAcme. The README below provides a brief overview of our approach, links to each process document, and quick pointers for new team members.

## Overview

OctoAcme runs projects with an emphasis on iterative delivery, clear ownership, and lightweight, documented plans. Work starts with Project Initiation (a one‑pager: problem, goals, success metrics) and moves into Planning once success metrics and team availability are confirmed. Planning breaks approved initiatives into a prioritized backlog, defines a Definition of Done, and results in a release plan. Execution is coordinated on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and supported by a risk register that records impact, likelihood, owner, and mitigation.

## Roles and Communication

The process defines clear personas and responsibilities to reduce ambiguity: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate schedules, risks, and communications; Developers implement features and tests; QA validates acceptance criteria; and Stakeholders provide inputs and approvals. Core ceremonies include daily standups to surface progress and blockers, regular sprint/milestone demos and reviews, and weekly PM–PdM alignment. Communication cadence also includes regular delivery standups, monthly stakeholder updates, and a single source of truth for status (project README or release docs) with a clear escalation path from team → PM → Product Lead → Sponsor.

## Quality & Releases

Key workflows emphasize small, reviewable changes and automated verification: pull requests should be small (≤ 400 lines when possible), include linked issues and acceptance criteria, run automated tests and linting in CI, and require at least one approval before merging. QA is layered — unit tests, integration tests when applicable, end‑to‑end smoke tests for critical flows, security scanning in CI, and manual QA as needed. Releases follow documented checklists and include rollback/incident playbooks and post‑deploy verification.

## Process Documents (links)
- Project Management Overview: ./octoacme-project-management-overview.md  
- Project Initiation: ./octoacme-project-initiation.md  
- Project Planning: ./octoacme-project-planning.md  
- Execution & Tracking: ./octoacme-execution-and-tracking.md  
- Risk Management & Communication: ./octoacme-risks-and-communication.md  
- Release & Deployment: ./octoacme-release-and-deployment.md  
- Retrospective & Continuous Improvement: ./octoacme-retrospective-and-continuous-improvement.md  
- Roles & Personas: ./octoacme-roles-and-personas.md

## Quick Start
- New to OctoAcme: read the Project Management Overview first.
- Starting a project: complete the Project One-pager in Project Initiation.
- Running a sprint: use the Project Planning and Execution & Tracking docs.
- Need role clarity: see Roles & Personas.
