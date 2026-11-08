# Repolex Knowledge Graph of UKPLab/acl2025-stricta

RDF knowledge graph data for [UKPLab/acl2025-stricta](https://github.com/UKPLab/acl2025-stricta), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download UKPLab/acl2025-stricta
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1c74d73fab737335ad3d1a827f3324909c09a5f6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1c74d73fab737335ad3d1a827f3324909c09a5f6
│           └── chunk-001.nq.gz
├── blob
│   ├── 0d03bf268c448d14aeb9becbc045bcde4ae6c9b7.nq.gz
│   ├── 0d39a67c24f01c1af1e9cb675f380c3a1d1b2422.nq.gz
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 1049cc394ef051d72d0cc5bab272bbb86af4549d.nq.gz
│   ├── 1063b6b19bdd74fca19f81aa682dd93613ec5980.nq.gz
│   ├── 10b1aab31f1dd3ddf7a4639685641bf2fc0b361d.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 19ef4b66647a6784928582b582b8b598f95b2b3c.nq.gz
│   ├── 1c2c63661c674eb8c1b16439a917daaa2df235a4.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 24b3fb77249f3e064dcabcf83b0442eaffa1c509.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 27a5bed50e58a6b0601d3706ec24e6b26c4121e9.nq.gz
│   ├── 2caad0d9cc61f6717c9662be85b00d8d3434c221.nq.gz
│   ├── 471472f3ca412f2cf6e90b27f7da1871df56e66d.nq.gz
│   ├── 4af847a2d0f0c95761fd4a7d53aefd2175adb3ec.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 56484c7e12b8173e898b31d561b4e144b53a5295.nq.gz
│   ├── 574e6fe33d9cdb4d3fea3411eb6b063956bd1007.nq.gz
│   ├── 5ba9dd6de747be4abe183a7ac8f4b3355e29f1dc.nq.gz
│   ├── 5ceca72f9f4776f9cf06a40e67fc4c5e42d769f9.nq.gz
│   ├── 6258cc173e3c0aebab7988827f64293e01ac6f49.nq.gz
│   ├── 6d7eeeda519cfe9181d79640886b2c54e077c269.nq.gz
│   ├── 6f802614407c65afa6f17d554865b6f4938c6346.nq.gz
│   ├── 7527c7363151a8c03ff34995ede931c0bdbd4d39.nq.gz
│   ├── 795119a038fffe7dbdf669b34ed23d5fd7a139d9.nq.gz
│   ├── 7b3f0b575ba80eefc3c39d166d7129d196255213.nq.gz
│   ├── 7df8265820c2b2cbadec0e1905ed96516bba83b8.nq.gz
│   ├── 7f986d49d1f724e6df4e7ab73cc6215ebefdb0f6.nq.gz
│   ├── 829cafe545fbc5b6a622128620b975639019a6ef.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8f156a91f50b1482268c04e2c6e5547b9b304a17.nq.gz
│   ├── 94a0ec8b1b1e4226fa0f4bd9e853902fff7f6769.nq.gz
│   ├── 9505ef6c1d39d336275796844cabec84f95bad9c.nq.gz
│   ├── 96b000b5ddcf1a3149cdb4c4c30fc2a6af715644.nq.gz
│   ├── 976ca8b67118277dcb30cada601ec1e7640ae22d.nq.gz
│   ├── 99ca3672b3c3f92c058fa19083b19334dae59255.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── 9ccc7363dcc9155dec920e64a9820737d3fff0e3.nq.gz
│   ├── 9f6fcfbcffb35b1df8b9785299c76d36d02ad17c.nq.gz
│   ├── 9fc04c07f2b4ad3b02e7a04b587331b3a7b93b20.nq.gz
│   ├── a16e6af9d45c19894a6eba93288fb2e5ebdc61f4.nq.gz
│   ├── a8a028f29e4c731cb9057bb14745ae6828db69fc.nq.gz
│   ├── ad079e31eb8013392b6af1a1807379b5360609c5.nq.gz
│   ├── b6460cda59de308755e8d71883b4081cc424050e.nq.gz
│   ├── b829d34b77ecae090b0b9a3e1fa4a367b6efaa46.nq.gz
│   ├── b94fede04c2cedd7c8b07c4472b54bfeb800b60f.nq.gz
│   ├── bc677eb23084ed50d19a30a575531b3b237b9ae7.nq.gz
│   ├── beb2e7a03497c5c454b4a9e460b7c005a5cdace6.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c3bd20591c812ec5a809e260cc78e558cecab0e4.nq.gz
│   ├── c433bd64e133665d98e9046f983a7c19d75926b9.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c7759c58443e703dbf7c460a2ed6b7262e6cb50b.nq.gz
│   ├── c806c8aa2d2823b11a1d6c78447f635ff7f67ceb.nq.gz
│   ├── c8c2ec97f16155d556a897f70ed986e3ae7358ab.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── cd6c00ffa6d693fdebaa50f5f491de309838d59e.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── d8ba56d58ced5756e2a0f94640ffb5bafc95db8b.nq.gz
│   ├── db484b5d9234540d31f1c4f996abee6b6f3f50f6.nq.gz
│   ├── dfc9d77dfb11e66fa36ecd6a7531e6dbc1c294df.nq.gz
│   ├── ea6bf18324f9f4913c1dd2c863c86e187fcc0d8b.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── ed45bea8ff513288a2aefb3fe5545c892847747a.nq.gz
│   ├── fc02c6fc060da3bac7e7834dc9ec1b67ceb8dfe7.nq.gz
│   └── ff039bba086c8c4c6b919977abf59d1757aca4df.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1c74d73fab737335ad3d1a827f3324909c09a5f6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 76 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[UKPLab/acl2025-stricta](https://github.com/UKPLab/acl2025-stricta)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
