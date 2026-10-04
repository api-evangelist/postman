---
name: postman-collection-items-create
description: Create a new folder in a collection, add a request to it, and attach a response to that request.
api: openapi/postman-collection-items-api-openapi.yml
operations:
- createCollectionFolder
- createCollectionRequest
- createCollectionResponse
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/postman-collection-items-api-openapi.yml ; every operationId checked against the contract
---

# postman-collection-items-create

Create a new folder in a collection, add a request to it, and attach a response to that request.

## Steps

1. 1. Use `createCollectionFolder` – provide `collectionId` path parameter and request body fields for the folder (e.g., `name`).
2. 2. Use `createCollectionRequest` – provide `collectionId` path parameter and request body fields for the request (e.g., `name`, `method`, `url`).
3. 3. Use `createCollectionResponse` – provide `collectionId` path parameter and request body fields for the response (e.g., `status`, `code`, `body`).

## Rules

- Include the API key in the `x-api-key` header (PostmanApiKey or apiKeyAuth).
- All operations are idempotent only when using unique identifiers; otherwise repeated calls may create duplicates.
