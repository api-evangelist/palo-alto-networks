---
name: palo-alto-networks-manage-users
description: Create a new user, update its details, and then delete the user.
api: openapi/palo-alto-networks-users-api-openapi.yml
operations:
- post-users
- put-users
- delete-users-id
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/palo-alto-networks-users-api-openapi.yml ; every operationId checked against the contract
---

# palo-alto-networks-manage-users

Create a new user, update its details, and then delete the user.

## Steps

1. 1. `post-users` – send a POST request to `/api/v34.03/users` with the required user fields in the JSON body.
2. 2. `put-users` – send a PUT request to `/api/v34.03/users` with the user ID and updated fields in the JSON body.
3. 3. `delete-users-id` – send a DELETE request to `/api/v34.03/users/{id}` where `{id}` is the user ID.

## Rules

- Auth: Include an authentication header as defined by one of the supported schemes (e.g., `Authorization: Bearer <token>`).
- Idempotency: DELETE operations are idempotent; repeated calls with the same user ID will result in the same final state.
- Errors: The API returns standard HTTP error codes (e.g., 400 for bad request, 401 for unauthorized, 404 for not found).
