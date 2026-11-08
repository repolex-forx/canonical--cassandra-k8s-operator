# Repolex Knowledge Graph of canonical/cassandra-k8s-operator

RDF knowledge graph data for [canonical/cassandra-k8s-operator](https://github.com/canonical/cassandra-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/cassandra-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 871c3695a60d204975c0e1c526874d7b3c736859
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 871c3695a60d204975c0e1c526874d7b3c736859
│           └── chunk-001.nq.gz
├── blob
│   ├── 02ba586ede3aac4cedd1594b15e21a9ccfec67b4.nq.gz
│   ├── 0440b2ad617e5dcbd03a7f00de2cb76498835512.nq.gz
│   ├── 135971a67c4f585ef2e087b0360f4fa3ee555487.nq.gz
│   ├── 143ca561b5be1e8df9ffb7d6863eecf8024d8234.nq.gz
│   ├── 1cee0cc955a97fccb3bc48a93eb63ca1fa389452.nq.gz
│   ├── 1da3c5a0ba22a903e2a697f865ea7fc4be8c643f.nq.gz
│   ├── 23c2ff37b868faad1ea43a03094aa0c94851a715.nq.gz
│   ├── 2677632fc1bb5dd9d4adc015a806dc0913c05dba.nq.gz
│   ├── 27a5f37552c6c8f72f8fd33b3a7783b9a925bc8f.nq.gz
│   ├── 2a086ca6fe95ac72397c2004c19d25eceb13de5f.nq.gz
│   ├── 2f853b914ceb3adb1b61856c07790ca877d9ce14.nq.gz
│   ├── 3036539a746ce30f98ae73eaab262c9f7d9027b7.nq.gz
│   ├── 3b14ad23ad29eed278308c40b937706deab76587.nq.gz
│   ├── 49ac18f49b0585d049a3b93b137a75d5cc612e01.nq.gz
│   ├── 5e5e177d0603f6b95eaddd2d2a02e5202f7217f6.nq.gz
│   ├── 5ed8e4334a5851118d6007c28cd250a9bb7d30f3.nq.gz
│   ├── 619f6fa818195df5a5bb701a6f2242cb309a623a.nq.gz
│   ├── 647ef8055537cf7ae940e28cfdb09a98e0b73f69.nq.gz
│   ├── 6ccd559eabeae93e4d23215fa450130fa9b37ace.nq.gz
│   ├── 6ce7b2bf3ed5f522c37a051766e87da24738e7d5.nq.gz
│   ├── 7c02c3648189ce53d5b048e1b9dfb43d8cf9d841.nq.gz
│   ├── 8260bf47f6eaea74c89c518d84f2c499f0e33a13.nq.gz
│   ├── 826145f52a6a3ec0a5ded2f587b94914e61a1d0c.nq.gz
│   ├── 8e7711c572d54c20bad5e06cc5fdf11943941cfd.nq.gz
│   ├── 923a703bc6e5392ee2d41548c028ee30f3230a65.nq.gz
│   ├── a2d1e3a3df00b3b181f92ff22cc8ba69d395a1a8.nq.gz
│   ├── a2e8195360d2ba94342beae688a306cf6f7b4cf6.nq.gz
│   ├── a73ecfee24be11781eb9accb79aa47e7a52e67e0.nq.gz
│   ├── bb86dce2133ff51c2b15badc29fc0c552f5f8dd6.nq.gz
│   ├── bbf15ed7ab22a1982427180f6ab427d27d968110.nq.gz
│   ├── bee8030a633dfde7a1b8711ec1111043dda7a23a.nq.gz
│   ├── c1a7b07118c0e3e24f3cd99d5174566018c5d2be.nq.gz
│   ├── cf0d61673873052512f92bfe309c8b2401ba87c8.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d6ae0f1340f1dad8b42725c1510215519e8c5071.nq.gz
│   ├── dd441821b04102897e0226d2d98b3235dd3ffc04.nq.gz
│   ├── e3081f84d73e20def6f51bc918b31b367e34062b.nq.gz
│   ├── e314668374c8a8394cd46d53a75995a9ece907a1.nq.gz
│   ├── e49b190958313ce6ff24e2ddedb2663351ebe3a2.nq.gz
│   ├── ea22df7f9cc7d55e999b36f268f7880540b8c67d.nq.gz
│   ├── efb82125df229ec243bc6b8cc175b8f46d1018da.nq.gz
│   └── f9c9d4490030ac95e76a16e976a690da0108e96a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 871c3695a60d204975c0e1c526874d7b3c736859.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[canonical/cassandra-k8s-operator](https://github.com/canonical/cassandra-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
