# Certification Simulator

Public overview of a certification study application currently in active development.
The first learning track is focused on the **Databricks Certified Data Engineer
Associate** exam.

## Purpose

The application is designed to help users practice certification questions, review
mistakes, and understand which topics need more attention. It also serves as a
portfolio project connecting software delivery with analytical data modeling.

## Current Status

**Active private prototype.** The application code is being developed in a private
repository while its data model, authentication flow, question bank, and deployment
process are stabilized. This public repository documents the project without exposing
credentials, unpublished questions, or incomplete implementation details.

## Planned Architecture

| Layer | Technology |
| --- | --- |
| Web application | Next.js, React, TypeScript, Tailwind CSS |
| Database | Supabase PostgreSQL |
| Authentication | Supabase Auth |
| Analytics | Attempt history, topic performance, weak-area analysis |
| Delivery | GitHub workflow and automated deployment |

## Product Scope

- Certification and topic selection.
- Timed practice and study modes.
- Attempt history and score tracking.
- Review of incorrect answers.
- Performance analysis by exam topic.
- Learning-progress and weak-area analytics.

## Data Engineering Roadmap

The next public milestones are:

1. Publish a sanitized relational data model.
2. Document the event and attempt-tracking model.
3. Add analytical queries for topic-level performance.
4. Add validation and automated tests.
5. Publish the application code when it is ready for external review.

## Evidence Policy

Only implemented and documented functionality will be described as complete. Planned
features remain labeled as roadmap items until their code and validation are public.

## Author

[Gabriel Franco](https://gabrielofranco.github.io/portfolio/) ·
[LinkedIn](https://www.linkedin.com/in/gabrielofranco)
