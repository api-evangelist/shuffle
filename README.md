# Shuffle

Shuffle is an open source security automation platform (SOAR) built for and by security professionals. The platform enables security teams to orchestrate workflows across their entire security tool stack using a no-code/low-code interface powered by OpenAPI integrations. Shuffle provides workflow automation, app integration, webhook triggers, scheduled executions, file storage, and organization management via a comprehensive REST API. It follows the Unix philosophy of doing one thing well — connecting security tools through REST APIs.

**Human URL:** [https://shuffler.io/docs/API](https://shuffler.io/docs/API)

## APIs

### Shuffle API v1
- **Documentation:** https://shuffler.io/docs
- **API Reference:** https://shuffler.io/docs/API
- **Base URL (Cloud):** `https://shuffler.io/api/v1`
- **Base URL (On-Premises):** `https://{domain}/api/v1`
- **Authentication:** Bearer token — `Authorization: Bearer <APIKEY>` from profile settings
- **Open Source:** https://github.com/Shuffle/Shuffle
- **Community:** https://discord.com/invite/B2CBzUm

## Artifacts

### OpenAPI Specifications
- [shuffle-openapi.yml](openapi/shuffle-openapi.yml)

### JSON Schemas
- [shuffle-workflow-schema.json](json-schema/shuffle-workflow-schema.json)
- [shuffle-execution-schema.json](json-schema/shuffle-execution-schema.json)

### JSON Structure
- [shuffle-workflow-structure.json](json-structure/shuffle-workflow-structure.json)

### JSON-LD Context
- [shuffle-context.jsonld](json-ld/shuffle-context.jsonld)

### Examples
- [shuffle-execute-workflow-example.json](examples/shuffle-execute-workflow-example.json) — Trigger a security automation workflow
- [shuffle-create-workflow-example.json](examples/shuffle-create-workflow-example.json) — Create a new workflow

### Rules
- [shuffle-rules.yml](rules/shuffle-rules.yml)

### Capabilities
- [security-workflow-automation.yaml](capabilities/security-workflow-automation.yaml) — Workflows, executions, apps, webhooks, files, notifications, and user management for security automation

### Vocabulary
- [shuffle-vocabulary.yml](vocabulary/shuffle-vocabulary.yml)

## Maintainers

**Kin Lane** - kin@apievangelist.com
