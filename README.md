# Repolex Knowledge Graph of canonical/sdcore-upf-operator

RDF knowledge graph data for [canonical/sdcore-upf-operator](https://github.com/canonical/sdcore-upf-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/sdcore-upf-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bfaaa4903e8f10618f5c8ff2d1b243b221fa0cfb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bfaaa4903e8f10618f5c8ff2d1b243b221fa0cfb
│           └── chunk-001.nq.gz
├── blob
│   ├── 015ffbe0d55b93c12b905312e3fc0b17cf02ae5e.nq.gz
│   ├── 044048104842dfd29f77b9f08dc54415e7abc776.nq.gz
│   ├── 064fc8952a2f2c84654cbd9fcdbe07978cfcbb45.nq.gz
│   ├── 07e10a08514124ce2ce63de2bd3fccecb89797e1.nq.gz
│   ├── 1281d190b63786d4799b253befee706dd83df0b0.nq.gz
│   ├── 13324d783792ad130553f8aa27b20b407c86441e.nq.gz
│   ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
│   ├── 1afecba4246aeafd90aac7d6564f4882fa63122f.nq.gz
│   ├── 2074475e5f84231c841964035e2ce9f159ccea74.nq.gz
│   ├── 2bfbad0891f45eb52428fdddbb6b5773d8fb2457.nq.gz
│   ├── 2d0d11234d51dbfa01a74b55e365e0a0fd206346.nq.gz
│   ├── 3bcd8a9f726c1e7ff32172d0ed5d95ab6436a34c.nq.gz
│   ├── 52401cd72bd8202289df0e5a8a0a5fe2b3cef5f7.nq.gz
│   ├── 5785a317f88640228174acf04f2e20e0b944e55a.nq.gz
│   ├── 5dcb6d7296de6b9b1b9361373ca9821eef77b3a2.nq.gz
│   ├── 65d0af5e1773f553f54e0fd24b9819739a1c17e2.nq.gz
│   ├── 6b16d35c1dfe14f8c3e029c7f88a2aefe1222290.nq.gz
│   ├── 71102f9b2c0bc84efecc44b2966c4a8d481aee44.nq.gz
│   ├── 732de3d473e4b9ce94ce7bc80660d5e89ec05905.nq.gz
│   ├── 7ae998a6deca5d662dc3eecea9c6fb986be5ffbb.nq.gz
│   ├── 7bf777367b1e643484636a5994062f30db19f68b.nq.gz
│   ├── 833929521ea04c9c4f5f9ffb79efaaa3693c4e8e.nq.gz
│   ├── 83e1adc982680b4f1f48d5e42bb0079c5b681b3e.nq.gz
│   ├── 870ba62a175ed866ef4d8bc0003e78d9e02663be.nq.gz
│   ├── 871ff5de2c4eb8a42331184325d7665e4871d5e1.nq.gz
│   ├── 9b52b60c49a2adde5f805375a5bf189b476e886f.nq.gz
│   ├── 9bdec77ac5b29e31199d9f45b0a26f8714ffe787.nq.gz
│   ├── 9ca56a8830a92c94a3be6a6aeb3dfe77d9cd869b.nq.gz
│   ├── 9f283771712bdd44501e76bcd51e06780e15920a.nq.gz
│   ├── b7f83c28d745e1f364f1eeed65c0253e2d0d172f.nq.gz
│   ├── bb4cae4c30bbc2c7e3450e78649140c9db5f3205.nq.gz
│   ├── bbe77cb69558e274639017d0079c3ebd6bc948a5.nq.gz
│   ├── c02cfd9af999b31f71e2d5bf63594fff617b7c13.nq.gz
│   ├── cefe49ef603d5341ebe9ebe750f2489624206601.nq.gz
│   ├── d54e174965cd46628cb383227260a3687f776d53.nq.gz
│   ├── d5f5ac1d1c897409c5e404c5c80df0b425aac5eb.nq.gz
│   ├── d9d907e39cfdd97b969c536ec9f3b941aa0d4aae.nq.gz
│   ├── deeee1bf7fe5db55d48ba7134c9418c9c19b6dd2.nq.gz
│   ├── e09c0ff9545d0545e2abe5927a6f596e764bfd01.nq.gz
│   ├── e6dab24f660f5a4f62a9079a23fc146ed642676f.nq.gz
│   ├── f02a7127b3043b535d5dcd580ede26967f2f3de6.nq.gz
│   ├── f62e4f34d361a5d19d1b64cc3d1e56b68ae4e794.nq.gz
│   ├── f6d63bcbb9c5cc8de1ca152504c16c0e9a891eed.nq.gz
│   ├── f71781c474310dff76214c17ac9e5827d3b381a5.nq.gz
│   ├── f85c58a5183f66631c5aa65044a6e14b4c5adc57.nq.gz
│   └── fa3f04cf4b5628ef5297ff611b8f7dd54ee8f88c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bfaaa4903e8f10618f5c8ff2d1b243b221fa0cfb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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

[canonical/sdcore-upf-operator](https://github.com/canonical/sdcore-upf-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
