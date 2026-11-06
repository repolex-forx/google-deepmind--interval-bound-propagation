# Repolex Knowledge Graph of google-deepmind/interval-bound-propagation

RDF knowledge graph data for [google-deepmind/interval-bound-propagation](https://github.com/google-deepmind/interval-bound-propagation), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/interval-bound-propagation
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 217a14d12686e08ebb5cfea1f2748cce58a55913
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 217a14d12686e08ebb5cfea1f2748cce58a55913
│           └── chunk-001.nq.gz
├── blob
│   ├── 1173c6fe818ac0f500f8f97cd314f268c151a306.nq.gz
│   ├── 1227a7cb6ee5904c1b988f6b23852151c0095086.nq.gz
│   ├── 17d0870cf9ba7674ccf733eed3af558ac9ee6f50.nq.gz
│   ├── 1aefb1f0a69b65c23a9fcdfb614b34d7ec551189.nq.gz
│   ├── 217ec9936e5a1c8145c865f2bac159212e2b9934.nq.gz
│   ├── 29b1520c0c75bdb22893fb9882ba647e0cdcd87b.nq.gz
│   ├── 357926440ada35b9834444a1691f705f038becd7.nq.gz
│   ├── 36410189cc548e225de9bcb45efc023051c087c4.nq.gz
│   ├── 5478bd269f5eb9990d426bcbaebb22a64a6841dd.nq.gz
│   ├── 571e65ea1d6360b74866fec0ca60eee2f8215c29.nq.gz
│   ├── 5b38abd4c63f2d25870e76acb1d94ab634cf3b35.nq.gz
│   ├── 5bcb50d66eff483a1fd38564fd2296735f7c19e6.nq.gz
│   ├── 5d2b23642451e79f7ee5122a69c49d2d2234f835.nq.gz
│   ├── 63c5c3631d1b16a26e343bca53fb12fbfaa829f5.nq.gz
│   ├── 696406042f252c1ba31535fb13e191253de7c0f0.nq.gz
│   ├── 6b6f2eddd01a5f244ef1075eeb0ee6d6220b62da.nq.gz
│   ├── 7a750fae6df65ed13a06d6aabec07b103fa0dc79.nq.gz
│   ├── 7c00385069899880f3e7bd583e2a209bfc0c43a3.nq.gz
│   ├── 7f0ecb532add80a7c5e8fd92818188b61a0b79ed.nq.gz
│   ├── 830b922f3006e7062da691769ef72dd830f294dd.nq.gz
│   ├── 885269392230f4f270bd8bc4004aae8235dcf5a9.nq.gz
│   ├── 8a5e8d201b0e6733304a21090bc24f4a5d8f5fc3.nq.gz
│   ├── 907f465ff0d5ce0ba133e3c449d805fde5d7f762.nq.gz
│   ├── 90a8b5a570663c37dca868cb2f1d27d1a0f3c06b.nq.gz
│   ├── 9123524b9d1dfeb0031493c350bd2d667db2ca3f.nq.gz
│   ├── 9e3b8d3d27b0a46f64be24ea072e38447f1c7b74.nq.gz
│   ├── a635b510df7277431fc2475faa7e34090c2c88f2.nq.gz
│   ├── a87721e1b27902bb0e4028e01e2774ae8257aa2c.nq.gz
│   ├── c399e501b011e019e613ac66d4240bd0d85bae8f.nq.gz
│   ├── c42f1496ca4139ccd3e5eebc9cc60798a4bd7619.nq.gz
│   ├── cc8cd87e34492bdfa231cdf803fb675c7bec277a.nq.gz
│   ├── d2f25063c08ba54624e63c40fe04d55868626ac7.nq.gz
│   ├── d3233eb14e35057be42f25d6a7ce48b7759bc4e5.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d77fee084ee790306757b18d9caa232223f87cc9.nq.gz
│   ├── db177d4ac70f76c2172ce65ca33c830d6cbd3ac5.nq.gz
│   ├── e278636a997f1f6c4572184e967788178f5e4c43.nq.gz
│   ├── e472cd76240fd248c2c23b8880b6a0120eb0b5c7.nq.gz
│   ├── e672ab1b3c5262837d7b8fbf10802ea2b9706875.nq.gz
│   ├── eadb86f01b51f17924fb323b8f9b94cfdc7f97cc.nq.gz
│   └── ee118b85eb8d511abbfa3656b45897f9b41746ad.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 217a14d12686e08ebb5cfea1f2748cce58a55913.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 48 files
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

[google-deepmind/interval-bound-propagation](https://github.com/google-deepmind/interval-bound-propagation)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
