---
name: postman-manage-request-comments
description: Create, retrieve, update, and delete comments on a request within a collection.
api: openapi/postman-collection-requests-api-openapi.yml
operations:
- getRequestComments
- createRequestComment
- updateRequestComment
- deleteRequestComment
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/postman-collection-requests-api-openapi.yml ; every operationId checked against the contract
---

# postman-manage-request-comments

Create, retrieve, update, and delete comments on a request within a collection.

## Steps

1. 1. Use `getRequestComments` with path parameters `collectionId` and `requestId` to list comments.
2. 2. Use `createRequestComment` with path parameters `collectionId` and `requestId` and a request body containing the comment text to add a new comment.
3. 3. Use `updateRequestComment` with path parameters `collectionId`, `requestId`, and `commentId` and a request body with the updated comment content.
4. 4. Use `deleteRequestComment` with path parameters `collectionId`, `requestId`, and `commentId` to remove a comment.

## Rules

- Include an API key in the `x-api-key` header (PostmanApiKey, apiKeyAuth, or scimApiKey).
- No rate limit is imposed; exhaustion returns no specific HTTP status.
