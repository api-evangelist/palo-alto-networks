---
name: palo-alto-networks-alerts-list-and-view
description: Retrieve a list of alerts and view details for a specific alert.
api: openapi/palo-alto-networks-alerts-api-openapi.yml
operations:
- post-alerts
- get-alert
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/palo-alto-networks-alerts-api-openapi.yml ; every operationId checked against the contract
---

# palo-alto-networks-alerts-list-and-view

Retrieve a list of alerts and view details for a specific alert.

## Steps

1. 1. Call `post-alerts` with the request body fields defined in the contract to filter and retrieve alerts.
2. 2. Use the `id` field from a selected alert in the response and call `get-alert` with the path parameter `id` to get full alert information.

## Rules

- Auth: Include an authentication header as defined by one of the supported schemes (e.g., `Authorization: Bearer <token>`).
- Pagination: The `post-alerts` operation supports pagination via the `page` and `pageSize` fields in the request body as described in the contract.
