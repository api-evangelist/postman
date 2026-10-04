---
name: postman-collection-create-and-publish
description: Create a new collection and publish its documentation.
api: openapi/postman-collections-api-openapi.yml
operations:
- createCollection
- publishDocumentation
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/postman-collections-api-openapi.yml ; every operationId checked against the contract
---

# postman-collection-create-and-publish

Create a new collection and publish its documentation.

## Steps

1. 1. Use `createCollection` with request body containing the collection JSON.
2. 2. Use `publishDocumentation` with path parameter `collectionId` from the created collection and request body specifying documentation settings.

## Rules

- Include the API key in the `x-api-key` header (PostmanApiKey or apiKeyAuth).
- No rate limiting is documented; assume unlimited calls.
