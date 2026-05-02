# Retool

Retool is a low-code platform for building internal tools, dashboards, and admin panels quickly using pre-built UI components that connect to any database or API. Retool provides a management REST API for programmatically administering users, groups, apps, resources, permissions, and source control integrations. It supports enterprise features including SSO, SCIM 2.0 provisioning, self-hosting, and AI-powered app generation.

**URL:** [https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Admin Panel, Dashboard, Internal Tools, Low Code, No Code

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-02

## APIs

### Retool Management API

The Retool Management API enables administrators to programmatically manage users, groups, permissions, apps, resources, workflows, folders, spaces, and source control integrations. Authenticated via Bearer token.

**Human URL:** [https://docs.retool.com/reference/api/v2](https://docs.retool.com/reference/api/v2)

#### Tags

- Administration, Apps, Groups, Permissions, Users

#### Properties

- [Documentation](https://docs.retool.com/reference/api/v2)
- [Authentication](https://docs.retool.com/org-users/concepts/retool-api)
- [OpenAPI](openapi/retool-management-api-openapi.yml)

### Retool SCIM 2.0 API

Retool implements SCIM 2.0 for automated user provisioning through identity providers like Okta and Azure AD. Available on Enterprise plan.

**Human URL:** [https://docs.retool.com/org-users/concepts/scim](https://docs.retool.com/org-users/concepts/scim)

#### Tags

- Enterprise, Identity, Okta, Provisioning, SCIM, SSO

### Retool Platform

Low-code visual development environment with 100+ pre-built components, 70+ native data source connectors, AI-powered app generation (AppGen), workflow automation, and mobile app support.

**Human URL:** [https://retool.com/](https://retool.com/)

#### Tags

- AI, Dashboard, Internal Tools, Low Code, Mobile, Workflows

## Artifacts

### OpenAPI Specifications

- [`openapi/retool-management-api-openapi.yml`](openapi/retool-management-api-openapi.yml) — Retool Management API covering users, groups, apps, resources, and folders.

### JSON Schemas

- [`json-schema/retool-user-schema.json`](json-schema/retool-user-schema.json) — Schema for Retool user accounts.
- [`json-schema/retool-group-schema.json`](json-schema/retool-group-schema.json) — Schema for Retool permission groups.
- [`json-schema/retool-app-schema.json`](json-schema/retool-app-schema.json) — Schema for Retool applications.

### JSON Structure

- [`json-structure/retool-management-api-structure.json`](json-structure/retool-management-api-structure.json) — Entity relationships and endpoint structure.

### JSON-LD Context

- [`json-ld/retool-context.jsonld`](json-ld/retool-context.jsonld) — JSON-LD context mapping Retool entities to schema.org.

### Examples

- [`examples/retool-list-users-example.json`](examples/retool-list-users-example.json) — List users request/response example.
- [`examples/retool-create-user-example.json`](examples/retool-create-user-example.json) — Create user request/response example.
- [`examples/retool-list-groups-example.json`](examples/retool-list-groups-example.json) — List groups request/response example.

### Rules

- [`rules/retool-management-api-rules.yml`](rules/retool-management-api-rules.yml) — Spectral ruleset enforcing Retool API conventions.

### Capabilities

- [`capabilities/shared/retool-management-api.yaml`](capabilities/shared/retool-management-api.yaml) — Shared Naftiko capability definition for the Retool Management API.
- [`capabilities/org-administration.yaml`](capabilities/org-administration.yaml) — Workflow capability for organization administration (16 MCP tools).

### Vocabulary

- [`vocabulary/retool-vocabulary.yml`](vocabulary/retool-vocabulary.yml) — Domain vocabulary covering 18 key Retool platform terms.

## Links

- **Website**: [retool.com](https://retool.com/)
- **Documentation**: [docs.retool.com](https://docs.retool.com/)
- **API Reference**: [docs.retool.com/reference/api/v2](https://docs.retool.com/reference/api/v2)
- **Community**: [community.retool.com](https://community.retool.com)
- **GitHub**: [github.com/tryretool](https://github.com/tryretool)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
