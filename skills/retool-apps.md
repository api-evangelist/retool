---
name: retool-apps
description: Operations for managing Retool apps via the Apps API.
api: retool-apps-api-openapi.yml
operations:
  - listApps
  - createApp
  - getApp
  - updateApp
  - deleteApp
---

## Steps
1. **List Apps** – Call `GET /apps` (`listApps`) to retrieve all apps.
2. **Create App** – Use `POST /apps` (`createApp`) with required payload to create a new app.
3. **Get App** – Retrieve a specific app via `GET /apps/{appId}` (`getApp`).
4. **Update App** – Modify an app with `PATCH /apps/{appId}` (`updateApp`).
5. **Delete App** – Remove an app using `DELETE /apps/{appId}` (`deleteApp`).

All operations follow standard REST conventions and require authentication via the provider's MCP endpoint.
