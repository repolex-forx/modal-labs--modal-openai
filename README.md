# Repolex Knowledge Graph of modal-labs/modal-openai

RDF knowledge graph data for [modal-labs/modal-openai](https://github.com/modal-labs/modal-openai), parsed by [repolex](https://repolex.ai).

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
rlex download modal-labs/modal-openai
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b72516cbc5f48a768faf548637c981784dd1858f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b72516cbc5f48a768faf548637c981784dd1858f
│           └── chunk-001.nq.gz
├── blob
│   ├── 050daa0d7acca1829e0119f6125bbcff48872e8c.nq.gz
│   ├── 053b02374114aaf40f75c40fd1e6c7cd2b5c21a6.nq.gz
│   ├── 0a5af2054490c7b2c52fed92796f410858824102.nq.gz
│   ├── 0bea46f4f7a2be620b323838098f5498b2d35465.nq.gz
│   ├── 0f04496ff126133192ac1b25f480a0ffd4b7c717.nq.gz
│   ├── 19e4f01e7cf00fba0dad863f9eaa5b417f0f62e1.nq.gz
│   ├── 1a288193203acf946ad4b9b492fc3bd30ce8aafa.nq.gz
│   ├── 3cfd4d0820a99d6e0f22ecaa02b510e930ef3806.nq.gz
│   ├── 3eec3bf1c78695cb97adbefb9eec56173b25ebb0.nq.gz
│   ├── 3fc6577287375aa5bb08694a7c09dbed6e532664.nq.gz
│   ├── 44c6b3fa75d961b81f7caab90de74a599eaf9d28.nq.gz
│   ├── 46674b39cdf252b0515752e9ab6639cd4d786de6.nq.gz
│   ├── 492beec58dad84d5dbaa25263b7e404d8f65e764.nq.gz
│   ├── 4aabe8577f8bb7aa63a2a0d7c6f340c19f2d92a4.nq.gz
│   ├── 4b9d3f22c7d6f4692b2272314dc47756616188bb.nq.gz
│   ├── 4bc2b0c943c27279148635f7d63dded893f97d8c.nq.gz
│   ├── 51b752ec689401c619e27d540fe29f20caf0909b.nq.gz
│   ├── 51d76da80394778577c4d4630a4cfea72ad1116e.nq.gz
│   ├── 59fdc0e5eb3e1f2136346a4e4c615064ac8f2196.nq.gz
│   ├── 5d068806cffda4d6580fe68338d5b02ae3ea7965.nq.gz
│   ├── 6324d401a069f4020efcf0ff07442724b52f47c2.nq.gz
│   ├── 67e14321623c51ff76176efc35874699d6f130d1.nq.gz
│   ├── 7af41327fa39dc67d353d73025bef4c4d812fb4d.nq.gz
│   ├── 7dde2a1fcb3042eb0025af6d6e9a83065858b037.nq.gz
│   ├── 7e85368197268c32475c64e73ca9c79d00571dbf.nq.gz
│   ├── 84338952f42a0bcdd598c682b18553c7ae3db6b2.nq.gz
│   ├── 85fcd3558e77bc44277df20c14b8dd85e90f482f.nq.gz
│   ├── 89d1b582469b9c97935fbd1d4cf6fa78e6fb5a12.nq.gz
│   ├── 8df853ee8fc698808b57df83f509d01bb1f3f87f.nq.gz
│   ├── 933cca9640f111114f85efd82c2c6aa270309bb5.nq.gz
│   ├── 93a340db644f3d122a9dfb1df79a9e723848ac79.nq.gz
│   ├── 95a1058bdd5e40a0e2961a9340b2b26abde42360.nq.gz
│   ├── 96b8a9647a700c3b70b78ec4de272682ae5b3ae6.nq.gz
│   ├── 9cfb32aa7e5cdf47812caa8abed29dbc52e6fc88.nq.gz
│   ├── 9eb457e95c114aed9e480e9fbf98381b0feb4d1b.nq.gz
│   ├── 9f61eae676b79bbda9df0bbb0e2d7a1f94e737a2.nq.gz
│   ├── a2ec17f9ef0045da317a1a33eef83d51d06cc3a1.nq.gz
│   ├── b7a45c96315e81469b966d9033f355d082a7e1bd.nq.gz
│   ├── be4adb124d8060e6e5aaceb3e6c4a10ddd4524f8.nq.gz
│   ├── cd07bce97bde95546e010c1258f35bbc9b78f75b.nq.gz
│   ├── cfd73b98660d4ff6203474c69b9f3e5ec20e2c96.nq.gz
│   ├── d993fdd564413ceb5b8677a88c5945e56c722afb.nq.gz
│   ├── e1378c5234b610981330d434c0547f30d0456736.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── f7c2528c6c61daf018d39e4db3d1b8a9f3e70133.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b72516cbc5f48a768faf548637c981784dd1858f.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 52 files
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

[modal-labs/modal-openai](https://github.com/modal-labs/modal-openai)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
