---
title: "Selected Work"
description: "Examples of DevOps, platform engineering and software development projects delivered by Deft Devs."
---

Client names are withheld for confidentiality.

## Enterprise Software Delivery Platform

*Large logistics enterprise · multi-year engagement*

Development and operation of the CI/CD platform behind the company's internal software development tools, running on Kubernetes in Azure.

- Migration of all in-scope services from on-premises to Azure Kubernetes Service, with high availability and regional disaster recovery
- Deployment times cut from about 3 hours to about 10 minutes by strictly separating build and deployment and introducing proper configuration management
- Single sign-on across all services, automated end-to-end tests, and production-like anonymized test data for non-production environments
- Shared Jenkins pipeline library with about 40 reusable steps for Helm releases, Azure Key Vault integration, database lifecycle and release approvals
- Organization-wide automated dependency updates with self-hosted Renovate across GitHub Enterprise and GitLab
- Migration of source code hosting from TeamForge to GitLab, and later from GitLab to GitHub Enterprise Cloud
- Tooling for the migration of Atlassian applications to the cloud: merging migrated content with dry-run, undo and audit logging

## From AI Prototype to Production App

*AI startup for mental wellbeing · contract CTO, 2025–2026*

Led engineering of an AI companion app, turning an AI-generated prototype into a reviewed, tested product with preview, staging and production environments.

- Infrastructure as code with OpenTofu and Terragrunt across Supabase, DigitalOcean and Cloudflare, with self-hosted GitHub runners on NixOS
- A single pipeline that builds the frontend, deploys edge functions, syncs secrets and rolls out infrastructure changes together
- A unified, normalized data model replacing a sprawl of overlapping tables
- An in-house AI stack with a custom MCP server and skills, conversation caching, and LiteLLM routing across providers, powering streaming chat and real-time voice sessions
- The frontend split into a monorepo of marketing site, app, admin and blog, migrated to Material Design, with a type-safe filesystem router and localized URLs
- Nix dev shell, automated dependency updates, pre-commit checks, unit tests and Playwright end-to-end tests

## Open Source

- [BootstrAPI](https://github.com/deftdevs/bootstrapi): declarative, idempotent REST APIs and startup configuration for Jira, Confluence and Crowd Data Center
- Upstream contributions to Helmfile, Renovate, NixOS, and the GitLab, Atlassian, Bitnami and JFrog Helm charts
