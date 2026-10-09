---
name: palo-alto-networks-create-and-test-integration
description: Create a new integration, test its connectivity, and retrieve its details.
api: openapi/palo-alto-networks-integrations-api-openapi.yml
operations:
- create-integration-v1
- test-integration-v1
- get-integration-v1
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/palo-alto-networks-integrations-api-openapi.yml ; every operationId checked against the contract
---

# palo-alto-networks-create-and-test-integration

Create a new integration, test its connectivity, and retrieve its details.

## Steps

1. 1. Call `create-integration-v1` with the required request body fields for the integration definition.
2. 2. Call `test-integration-v1` with the integration ID returned from step 1 to verify connectivity.
3. 3. Call `get-integration-v1` with the same integration ID to retrieve the created integration details.

## Rules

- Auth: Include an authentication header as defined by one of the supported schemes (e.g., `Authorization: Bearer <token>` or `X-API-KEY: <key>`).
- Idempotency: The `create-integration-v1` operation is not idempotent; repeat calls will create duplicate integrations.
- Errors: On failure, the API returns standard HTTP error codes (e.g., 4xx for client errors, 5xx for server errors) with a JSON error payload.
