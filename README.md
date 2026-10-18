# Repolex Knowledge Graph of Pylons/hupper

RDF knowledge graph data for [Pylons/hupper](https://github.com/Pylons/hupper), parsed by [repolex](https://repolex.ai).

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
rlex download Pylons/hupper
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b2c564c915bbb94999602820a587f39be02eee29
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b2c564c915bbb94999602820a587f39be02eee29
│           └── chunk-001.nq.gz
├── blob
│   ├── 0f1bdd6bbd971da3741a50de7b482926397f829f.nq.gz
│   ├── 1bc3a5cac3f50d99da3d7ee7a73cdd2bc2dfe08e.nq.gz
│   ├── 1edf7608793951aed8c431fe8fc13a78bdb17b15.nq.gz
│   ├── 25f2bdab57a08b2af60d7699f158b5862571e3e1.nq.gz
│   ├── 293b9fcbd3a8a5bea693bab6cbf2d565d7d3c2c1.nq.gz
│   ├── 3113a6b9c39116d877e8a0da6bf0d840c47f2cd1.nq.gz
│   ├── 3914d040a4f7f52928ee492f1d03de48e7f221f2.nq.gz
│   ├── 3e128537044b78addc2e62602bd09066cf65be7e.nq.gz
│   ├── 3ed74ec69af5c1f83155e0837465769822a6034a.nq.gz
│   ├── 44d53bb2fd8d07cc72de00e59b8f21f93626b9c4.nq.gz
│   ├── 49dc1a9142a6b84a134eb9a4c5fd8fcb96fc468e.nq.gz
│   ├── 4e164e5d702e81f21b9a6aab41a46f177f261d59.nq.gz
│   ├── 51fae0cfefc132159308095c742e77258217fc51.nq.gz
│   ├── 52880b72b65164152ba921dd8c4ec6eaf685e70d.nq.gz
│   ├── 538a6ad49af5dc73963c9ae4155ecdbc4d0b0f84.nq.gz
│   ├── 539153cb3f2d2dbe2c03c0dd5799b79cff3d7c4b.nq.gz
│   ├── 5564ff2633b66c4decd5dcc51d1d7788d9eb5dbf.nq.gz
│   ├── 56cad12d9cd41c7c1c6e75656418fe27fe4bcac6.nq.gz
│   ├── 5737055179c779b424f85fe92776d847c5e82905.nq.gz
│   ├── 59eeb875d8156e80df4f35fba8ff09973945a108.nq.gz
│   ├── 5ba0a605c223df6384ccd24252af6cc6975eb14f.nq.gz
│   ├── 5bcb5f283354344958b3b1fa0691233386112380.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 6973fc203201386a9810413f250d549f5c89b672.nq.gz
│   ├── 7bdc6d7b77c5477632555f273f010ce34702aa94.nq.gz
│   ├── 7d3f59de8007e87d66fafcbb3e2339bf9376e919.nq.gz
│   ├── 82823f72538f2aecaa2152b5b489611452e5fd4a.nq.gz
│   ├── 836f2ee0afff1d1d27e86c85bf1b7f487a317f6d.nq.gz
│   ├── 8467e7aa1960fd6b03d71e7e66e3600aa7b72c3b.nq.gz
│   ├── 86423dbfddadb22075ff7a54cd56eee88587f7b8.nq.gz
│   ├── 86787d6612cf136e574c7b4532a4a4aba4668437.nq.gz
│   ├── 8cd4bbd2207f1ef0a3b38941dca19162d3913613.nq.gz
│   ├── 8ed461bb49ab7205e2f05ab4f9d99a72611c5143.nq.gz
│   ├── 93b354d7f869dd82aeeb25157d6ccc7fd3d74724.nq.gz
│   ├── 9b33f515bba224ecc4daa37f28dcea5026c27aff.nq.gz
│   ├── a9e17a7fc38b84ba7b6afac5b542ad712e430f74.nq.gz
│   ├── aa7d1e845b79f384e402d2a8818bf8bb3e243fe5.nq.gz
│   ├── b39acb92005fe58e865cada6213d8c73b2b8409e.nq.gz
│   ├── bf0bf4d50cadc8d760a9524df834e5684495363c.nq.gz
│   ├── c320f7083bc227b1f3b56fa0c4fcee04a6aa8f62.nq.gz
│   ├── c68bbdc9da89d745ad805e24cc4f7027c59e3f03.nq.gz
│   ├── d81af5f4f5b62aa8a626fdf8db5f92cf27c06b5e.nq.gz
│   ├── e2489f2d13f4aa4c67fbe8435f35088c537dfd58.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── ff1621bbf3cfddd8fe58424489bce4569a5b19ff.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b2c564c915bbb94999602820a587f39be02eee29.nq.gz
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

[Pylons/hupper](https://github.com/Pylons/hupper)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
