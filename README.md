# HiveMono

Unified OpenHive workspace assembled from independently versioned repositories.

HiveMono does not own product code. Repositories are mounted as Git submodules under `vendors/<org>/<repo>`.

## Workspace layout

```text
vendors/openhive-labs/
├── hivemesh/                # official implementation and product docs
├── hivemesh-protocol/       # normative protocol, schemas, and conformance
├── docs/                    # documentation aggregation and publication
├── openhive-labs.github.io/ # organization homepage
├── .github/                 # organization profile and shared templates
└── roadmap/                 # private planning; skipped by public clones
```

Make changes in the repository that owns the subject, push that repository's commit, and then update its pinned pointer here. See `.agents/docs/repository-map.md` for source-of-truth boundaries.
