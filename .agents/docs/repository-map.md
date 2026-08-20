# Repository Map

| Repository | Owns | Does not own |
|---|---|---|
| `roadmap` | private product planning, research, provisional decisions, milestones, and risks | released protocol, implementation behavior, public user docs |
| `hivemesh` | official implementation, product behavior, user docs, and maintainer constraints | normative wire protocol or private strategy |
| `hivemesh-protocol` | peer identity, resources, catalogs, leases, HiveLink, invocation, receipts, schemas, and conformance | UI, database choice, transport-vendor implementation, product strategy |
| `docs` | source allowlist, aggregation, navigation, presentation, and publication | product or protocol source content |
| `openhive-labs.github.io` | OpenHive homepage, public project index, and release-accurate summaries | detailed docs or private roadmap |
| `.github` | organization profile and shared templates | product-specific rules |

`roadmap` is registered as a private Submodule with `update = none`, so public recursive clones skip it. Authorized maintainers may initialize it explicitly.
