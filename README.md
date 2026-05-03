# Weave Net (weave-net)
Weave Net is an open source container networking plugin that creates a virtual network connecting Docker containers and Kubernetes pods across multiple hosts. It provides automatic IP address management (IPAM), DNS resolution via WeaveDNS, network policy enforcement, and optional encryption. The Weave Net daemon exposes a local HTTP API on port 6784 for programmatic network management.

**URL:** [https://github.com/weaveworks/weave](https://github.com/weaveworks/weave)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Containers, Networking, Kubernetes, Docker, IPAM, Open Source, CNCF

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-03

## APIs

### Weave Net HTTP API
The Weave Net local HTTP API exposed on port 6784 for managing container networking including IP address allocation, peer connections, WeaveDNS registration, and network bridge exposure.

**Human URL:** [https://github.com/weaveworks/weave](https://github.com/weaveworks/weave)

#### Tags:

 - Containers, Networking, IPAM, DNS

#### Properties

- [Weave Net OpenAPI](openapi/weave-net-openapi.yml)
- [Documentation](https://github.com/weaveworks/weave)
- [API Reference](https://github.com/weaveworks/weave/tree/master/api)

## Common Properties

- [GitHub Repository](https://github.com/weaveworks/weave)
- [GitHub Organization](https://github.com/weaveworks)
- [Terms of Service](https://github.com/weaveworks/weave/blob/master/LICENSE)
- [Security](https://github.com/weaveworks/weave/blob/master/SECURITY.md)
- [Change Log](https://github.com/weaveworks/weave/blob/master/CHANGELOG.md)
- [Support](https://github.com/weaveworks/weave/issues)

## Features

| Name | Description |
|------|-------------|
| Container Overlay Network | Creates a virtual network connecting containers across multiple hosts without requiring any configuration of the physical network. |
| Automatic IPAM | Automatically allocates IP addresses to containers from a configurable subnet using distributed consensus. |
| WeaveDNS | Built-in DNS resolution for containers by hostname, making services discoverable by name on the Weave network. |
| Network Encryption | Optional encryption of all network traffic using NaCl for secure container-to-container communication. |
| Kubernetes Integration | Native Kubernetes CNI plugin for pod-to-pod networking across nodes. |
| Docker Integration | Docker network plugin for seamless multi-host Docker container networking. |
| Fast Datapath | Kernel-level packet forwarding using Open vSwitch for high-performance networking. |

## Use Cases

| Name | Description |
|------|-------------|
| Multi-Host Docker Networking | Connect Docker containers across multiple physical or virtual machines without complex network configuration. |
| Kubernetes Pod Networking | Provide pod-to-pod networking for Kubernetes clusters as a CNI-compliant network plugin. |
| Automated IP Management | Automate container IP allocation and release in orchestration workflows. |
| Service Discovery | Enable container service discovery by DNS name using WeaveDNS. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Weave Net HTTP API OpenAPI](openapi/weave-net-openapi.yml)

### JSON Schema

7 JSON Schema files covering Weave Net status, router, IPAM, DNS, peer, and connection schemas.

### JSON Structure

7 JSON Structure files (json-structure.org) converted from JSON Schema.

### JSON-LD

- [Weave Net JSON-LD Context](json-ld/weave-net-context.jsonld) — 7 type declarations and 20 property mappings

### Examples

7 example JSON files generated from schemas.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Weave Net HTTP API](capabilities/shared/weave-net-api.yaml) — 8 operations covering status, IPAM, peer management, and DNS

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Container Networking](capabilities/container-networking.yaml) | Weave Net HTTP API | 9 | DevOps Engineer, Platform Operator, Container Administrator |

## Vocabulary

- [Weave Net Vocabulary](vocabulary/weave-net-vocabulary.yml) — Unified taxonomy mapping 7 resources, 10 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Weave Net Spectral Rules](rules/weave-net-spectral-rules.yml) — 22 rules across 8 categories enforcing Weave Net API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
