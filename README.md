# Weave Net (weave-net)

Weave Net is an open source container networking plugin that creates a virtual network connecting Docker containers and Kubernetes pods across multiple hosts. It provides automatic IP address management (IPAM), DNS resolution via WeaveDNS, network policy enforcement, and optional encryption for container-to-container communication. The Weave Net daemon exposes a local HTTP API on port 6784 for programmatic network management. Weave Net is maintained by Weaveworks and is archived but remains widely used in production environments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/weave-net/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/weave-net/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Containers
- Networking
- Kubernetes
- Docker
- IPAM
- Open Source
- CNCF

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-19

## APIs

### Weave Net HTTP API

The Weave Net local HTTP API exposed on port 6784 for managing container networking including IP address allocation (IPAM), peer connections, WeaveDNS registration, and network bridge exposure.

- **Human URL:** [https://github.com/weaveworks/weave](https://github.com/weaveworks/weave)

#### Tags

- Containers
- Networking
- IPAM
- DNS

#### Properties

- [OpenAPI](openapi/weave-net-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weave-net.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weave-net.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://github.com/weaveworks/weave)
- [API Reference](https://github.com/weaveworks/weave/tree/master/api)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/weaveworks)
- [GitHub Repository](https://github.com/weaveworks/weave)
- [GitHub Organization](https://github.com/weaveworks)
- [Terms of Service](https://github.com/weaveworks/weave/blob/master/LICENSE)
- [Security](https://github.com/weaveworks/weave/blob/master/SECURITY.md)
- [Changelog](https://github.com/weaveworks/weave/blob/master/CHANGELOG.md)
- [Support](https://github.com/weaveworks/weave/issues)
- [Spectral Rules](rules/weave-net-spectral-rules.yml)
- [Vocabulary](vocabulary/weave-net-vocabulary.yml)
- [Features](undefined)
- [Use Cases](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
