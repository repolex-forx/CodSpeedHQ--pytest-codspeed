# Repolex Knowledge Graph of CodSpeedHQ/pytest-codspeed

RDF knowledge graph data for [CodSpeedHQ/pytest-codspeed](https://github.com/CodSpeedHQ/pytest-codspeed), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download CodSpeedHQ/pytest-codspeed
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a24abfe8f2e4c789d961daa90b47c082ad6e6f96
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a24abfe8f2e4c789d961daa90b47c082ad6e6f96.nq.gz
│   └── repolex
│       └── a24abfe8f2e4c789d961daa90b47c082ad6e6f96
│           └── chunk-001.nq.gz
├── blob
│   ├── 0132b3f6b671017923762706d3179ed1c7c3bf03.nq.gz
│   ├── 03d0af6e8a8a69ebb8acb5a83e4ee6cb30509fda.nq.gz
│   ├── 0e1621c3906d6b7de13b733ba3f8e6675c0a67b4.nq.gz
│   ├── 1174f8bacf01dcf4ee64ac80190dd22c90479b62.nq.gz
│   ├── 13da753a0b077c0cbea50a05e8bc02548e9123a0.nq.gz
│   ├── 161763a07a00c407ed10f8949c051aa5dfb92dc4.nq.gz
│   ├── 17673a36223e6f47da842174a122c119c9252602.nq.gz
│   ├── 17c1c50af68869487db6706b406164ec9f93f08d.nq.gz
│   ├── 1932a8e030241f1ed458edbb3670d6e22f19ec46.nq.gz
│   ├── 19e9d2ee0967cea9c9ca820ebc8cda4add4ba896.nq.gz
│   ├── 1e6de1a1cf97b826284e5e4d83ab911f82da0d5d.nq.gz
│   ├── 22b3137ade49eef061c4f61833d6ea6c62a55492.nq.gz
│   ├── 2e810b3233d26e9a131e53f72b98245b620186a1.nq.gz
│   ├── 32198a51ccf8ec07f4c0165a881a9b31f09948cc.nq.gz
│   ├── 452e9da29a8f176cc3316adcafe552366c1d53b7.nq.gz
│   ├── 510ab307d3036e60739d304616f47d145eebbf2c.nq.gz
│   ├── 6a77448c89d4f22eca1ba46bdffbe61f38251169.nq.gz
│   ├── 6c2414322628b34fdb640e77f4e3b20fb161cbb6.nq.gz
│   ├── 6f73f82156481c5defae6f6682abcb5dad0cf48a.nq.gz
│   ├── 8c0ca4999449110e9ee4abb60efd008b0da56f58.nq.gz
│   ├── 914b4ee73af99f23a13ca2a07f25fe12ee297a2a.nq.gz
│   ├── 99525ad0ca9061783222b9b3f4dd2d97adfb95a1.nq.gz
│   ├── 9ae6a4128e66a69141282640861629581441361d.nq.gz
│   ├── 9c24f19c05975527c607af323b77be857f239d99.nq.gz
│   ├── a88f226309310c8ea08020c162eb922e75878ca4.nq.gz
│   ├── a8b91cdd4c70c3d120dcb3fdd2d4ca44ba9d366a.nq.gz
│   ├── a9aaf54047202046a06627cebdf581a2f2df833f.nq.gz
│   ├── acec9b82ea384a391850bb34ea28917f66108146.nq.gz
│   ├── ad23fac484852bcc19767895bae64244e8e904dc.nq.gz
│   ├── bc92b50e18faedef20fa599f1f59b49e694d718d.nq.gz
│   ├── c786367538c1f39ec49c3c56d0d6fc67739722ce.nq.gz
│   ├── c9d2e0109f9d2f30f16b9458042f1676e290c0f7.nq.gz
│   ├── ca0db186737ef588be4b406fdc2f4c5b253c18cd.nq.gz
│   ├── d0d60bf05e40887fb07cec9eeff469ae97bdfb12.nq.gz
│   ├── d969f962b02e2ab149883239d92ce027ab6a9095.nq.gz
│   ├── e0657bb73b07bb55e74459456b6d52c0eaf81f6a.nq.gz
│   ├── e37487113fc0bfb6e3edc320500ec5be9b1403b9.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8a56252a44f25170561a70011408745eb1b3d43.nq.gz
│   ├── eb2dc00725a14870415122e76a443235d95db1e9.nq.gz
│   ├── f215e2aad9e2c11b94f19f8c64cb6a7cf38f3118.nq.gz
│   ├── f4b30b7814aa816cc91ac5778c4db06c08c798ab.nq.gz
│   └── f9fb2e455bfe8598edd778d9924764c822249257.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── a24abfe8f2e4c789d961daa90b47c082ad6e6f96.nq.gz
├── filetree
│   └── a24abfe8f2e4c789d961daa90b47c082ad6e6f96.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 53 files
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

## Source repository

[CodSpeedHQ/pytest-codspeed](https://github.com/CodSpeedHQ/pytest-codspeed)

---
*Parsed on 2026-04-20 by [repolex](https://repolex.ai)*
