---
name: palo-alto-networks-create-policy
description: Create a new policy, preview it, and validate the policy definition.
api: openapi/palo-alto-networks-policies-api-openapi.yml
operations:
- savePolicy
- policyPreview
- validateCustomPolicy
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/palo-alto-networks-policies-api-openapi.yml ; every operationId checked against the contract
---

# palo-alto-networks-create-policy

Create a new policy, preview it, and validate the policy definition.

## Steps

1. 1. Call `savePolicy` with the required request body containing the new policy definition.
2. 2. Call `policyPreview` with the request body referencing the saved policy to generate a preview.
3. 3. Call `validateCustomPolicy` with path parameter `queryId` and request body to validate the policy code.

## Rules

- Authentication: include an Authorization header (e.g., Bearer token) as defined by the Auth, Bearer, or BearerAuth schemes.
- Idempotency: not applicable for these operations.
