---
name: snaplogic-asset-management-grant-revoke
description: Grant and then revoke asset access privileges for a specific asset path.
api: openapi/snaplogic-asset-management-api-openapi.yml
operations:
- getAssetPrivileges
- grantAssetAccess
- revokeAssetAccess
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/snaplogic-asset-management-api-openapi.yml ; every operationId checked against the contract
---

# snaplogic-asset-management-grant-revoke

Grant and then revoke asset access privileges for a specific asset path.

## Steps

1. 1. Call `getAssetPrivileges` with the `path` header to retrieve current privileges.
2. 2. Call `grantAssetAccess` with the `path` header and required body fields to add new privileges.
3. 3. Call `revokeAssetAccess` with the `path` header and required body fields to remove privileges.

## Rules

- Auth: Use either `basicAuth` or `bearerAuth` HTTP authentication schemes.
- Rate limit: None; on exhaustion HTTP None.
