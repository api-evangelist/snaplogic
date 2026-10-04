---
name: snaplogic-users-and-groups-update-access
description: Update a user's app access and then retrieve their user settings.
api: openapi/snaplogic-users-and-groups-api-openapi.yml
operations:
- updateUserAppAccess
- getUserSettings
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/snaplogic-users-and-groups-api-openapi.yml ; every operationId checked against the contract
---

# snaplogic-users-and-groups-update-access

Update a user's app access and then retrieve their user settings.

## Steps

1. 1. Call `updateUserAppAccess` with the required request body fields as defined in the contract.
2. 2. Call `getUserSettings` with any required query parameters or headers as defined in the contract.

## Rules

- Authentication: include either a Basic Auth header or a Bearer token header as specified by the `basicAuth` or `bearerAuth` schemes.
