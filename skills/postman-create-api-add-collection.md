---
name: postman-create-api-add-collection
description: Create a new API in Postman and attach a collection to it.
api: openapi/postman-apis-api-openapi.yml
operations:
- createApi
- addApiCollection
- syncCollectionWithSchema
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/postman-apis-api-openapi.yml ; every operationId checked against the contract
---

# postman-create-api-add-collection

Create a new API in Postman and attach a collection to it.

## Steps

1. 1. Use `createApi` with required body fields for the API definition and include the header `x-api-key` for authentication.
2. 2. Use `addApiCollection` with the `apiId` returned from step 1, providing the collection payload, and include the header `x-api-key`.
3. 3. (Optional) Use `syncCollectionWithSchema` with the same `apiId` and `collectionId` to synchronize the collection with its schema, including the header `x-api-key`.

## Rules

- Include the authentication header `x-api-key` (PostmanApiKey, apiKeyAuth, or scimApiKey) on every request.
- POST and PUT operations are not idempotent; avoid repeating them without checking the result.
