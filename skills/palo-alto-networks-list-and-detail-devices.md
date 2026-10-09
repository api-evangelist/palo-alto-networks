---
name: palo-alto-networks-list-and-detail-devices
description: Retrieve a list of discovered devices and then fetch detailed information for a selected device.
api: openapi/palo-alto-networks-devices-api-openapi.yml
operations:
- listDevices
- getDeviceDetail
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/palo-alto-networks-devices-api-openapi.yml ; every operationId checked against the contract
---

# palo-alto-networks-list-and-detail-devices

Retrieve a list of discovered devices and then fetch detailed information for a selected device.

## Steps

1. 1. Call `listDevices` (GET /device/list) – no request body, uses standard query parameters if any.
2. 2. Call `getDeviceDetail` (GET /device/detail) – include the device identifier in the query string or header as specified by the contract.

## Rules

- Auth: Include an authentication header as defined by one of the supported schemes (e.g., `Authorization: Bearer <token>` or `X-API-KEY: <key>`).
- Errors: The API returns standard HTTP error codes; handle 4xx for client errors and 5xx for server errors.
