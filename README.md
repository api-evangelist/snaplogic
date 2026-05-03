# SnapLogic

SnapLogic is an AI-powered generative integration platform (iPaaS) that unifies data and streamlines workflows across enterprise systems. The platform provides Snaps (pre-built connectors), visual pipeline design, AI-assisted integration, API management, and programmatic platform management through the SnapLogic Public APIs.

## APIs

- [SnapLogic Public APIs](https://docs.snaplogic.com/public-apis/public-apis-about.html) - Programmatic management for pipeline execution control, asset management, user/group administration, Snaplex infrastructure, tasks, projects, and API Management lifecycle.
- [SnapLogic API Management](https://www.snaplogic.com/products/api-management-development) - API gateway and lifecycle management for exposing pipelines as managed APIs.
- [SnapLogic Snap Development SDK](https://developer.snaplogic.com/) - Java-based SDK for building custom Snaps.

## Properties

- [Website](https://www.snaplogic.com)
- [Documentation](https://docs.snaplogic.com/)
- [Developer Documentation](https://developer.snaplogic.com/)
- [GitHub Organization](https://github.com/SnapLogic)
- [Community Forum](https://community.snaplogic.com)
- [Pricing](https://www.snaplogic.com/pricing)
- [Blog](https://www.snaplogic.com/blog)
- [Training](https://learn.snaplogic.com/)

## Artifacts

### OpenAPI
- [snaplogic-public-apis-openapi.yml](openapi/snaplogic-public-apis-openapi.yml) — SnapLogic Public APIs (Runtime, Asset Management, Projects, Users, Tasks)

### Rules
- [snaplogic-rules.yml](rules/snaplogic-rules.yml) — Spectral ruleset enforcing SnapLogic API conventions (camelCase operationIds, JWT auth, server org variables)

### Capabilities
- [pipeline-operations.yaml](capabilities/pipeline-operations.yaml) — Unified workflow for SnapLogic pipeline monitoring, control, and asset management

#### Shared Definitions
- [capabilities/shared/public-apis.yaml](capabilities/shared/public-apis.yaml) — SnapLogic Public APIs shared capability definition

### JSON Schema
- [snaplogic-pipeline-execution-schema.json](json-schema/snaplogic-pipeline-execution-schema.json) — Schema for SnapLogic pipeline execution objects

### JSON Structure
- [snaplogic-platform-structure.json](json-structure/snaplogic-platform-structure.json) — Hierarchical structure of SnapLogic organizations, project spaces, projects, pipelines, and tasks

### JSON-LD
- [snaplogic-context.jsonld](json-ld/snaplogic-context.jsonld) — JSON-LD context for SnapLogic integration platform linked data semantics

### Examples
- [snaplogic-list-pipeline-executions-example.json](examples/snaplogic-list-pipeline-executions-example.json) — List failed pipeline executions via the Runtime API

### Vocabulary
- [snaplogic-vocabulary.yml](vocabulary/snaplogic-vocabulary.yml) — Domain vocabulary covering Snaps, Snaplex, pipelines, tasks, and generative integration concepts
