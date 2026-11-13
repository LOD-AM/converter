> [!IMPORTANT]
> **This repository has moved to [LOD-AM/knowledge-graph](https://github.com/LOD-AM/knowledge-graph).**
> It is archived and no longer updated. Its full history was merged into
> knowledge-graph in November 2026, together with `ontologies`, `vocabularies`
> and `converter`. Please use, link and cite the new repository.

## Where things are now

| Here (old) | In knowledge-graph (current) |
|---|---|
| `scripts/fetchType.js`, `scripts/README.md` | [`converter/`](https://github.com/LOD-AM/knowledge-graph/tree/main/converter) (`npm run aat`, with tests) |
| `aat_types_cidoc.ttl` | [`data/aat/aat_types_cidoc.ttl`](https://github.com/LOD-AM/knowledge-graph/blob/main/data/aat/aat_types_cidoc.ttl) |

The old files below are kept as they were, so links from older blog posts on
[lod-am.net](https://lod-am.net) still work. They **don't** reflect the current model:
several terms used here were corrected (see
[knowledge-graph#10](https://github.com/LOD-AM/knowledge-graph/pull/10)). The current rules are in
[CONVENTIONS.md](https://github.com/LOD-AM/knowledge-graph/blob/main/CONVENTIONS.md).

---

# converter
This repository contains all converter-scripts used in the LOD-AM project to convert data from various sources into the data-schema used in the project.
