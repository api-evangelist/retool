# Retool GraphQL Schema

This directory contains a GraphQL schema representation of the Retool platform API surface, derived from the Retool Management REST API (v2) and SCIM 2.0 API documentation.

## Source

- REST API Reference: https://docs.retool.com/reference/api/v2
- SCIM API: https://docs.retool.com/org-users/concepts/scim
- GitHub: https://github.com/tryretool

## Schema Overview

The schema covers the full Retool platform domain including:

- **Apps & Versions** — App, AppVersion, AppPermission, AppEmbed, AppEnvironment
- **Resources & Queries** — Resource, ResourceConfig, Query, QueryLibrary
- **Workflows** — WorkflowJob, WorkflowTrigger
- **Organization** — User, Group, Permission, Folder, Space
- **Enterprise** — SSO, SSOConfig, SCIM, EnterpriseConfig, AuditLog
- **Database** — RetoolDB, Table, TableRow, Row, Column
- **Platform** — Theme, BrandingConfig, CustomComponent, GlobalWidget
- **Developer** — ApiToken, Agent, Secret
- **Source Control** — SourceControl, GitBranch, Commit, Deployment
- **Analytics** — Usage

## Types Count

50+ types defined in `retool-schema.graphql`.

## Authentication

All Retool API operations require a Bearer token passed in the `Authorization` header. Tokens are generated in the Retool admin console under **Settings > API**.

## Notes

Retool does not publish a native GraphQL endpoint; this schema is a structural representation of the REST API types for documentation, tooling, and integration mapping purposes.
