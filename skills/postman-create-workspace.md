---
name: postman-create-workspace
description: Create a new workspace and retrieve its details.
api: openapi/postman-workspaces-api-openapi.yml
operations:
- createWorkspace
- getWorkspace
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/postman-workspaces-api-openapi.yml ; every operationId checked against the contract
---

# postman-create-workspace

Create a new workspace and retrieve its details.

## Steps

1. 1. Call `createWorkspace` with the required request body fields for the new workspace.
2. 2. Call `getWorkspace` using the `workspaceId` returned from the create step to verify creation.

## Rules

- Auth: include the API key in the `x-api-key` header (PostmanApiKey or apiKeyAuth).
- Rate limiting: none defined; no special handling required.
