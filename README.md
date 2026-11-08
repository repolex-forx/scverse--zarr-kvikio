# Repolex Knowledge Graph of scverse/zarr-kvikio

RDF knowledge graph data for [scverse/zarr-kvikio](https://github.com/scverse/zarr-kvikio), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/zarr-kvikio
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d10d27a70e6b5813453ab52cb21728f51cd2411e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d10d27a70e6b5813453ab52cb21728f51cd2411e
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ad6a6ea9418df96256615a564065e38c8332ea.nq.gz
│   ├── 097268bf7fc3a260262e83e7b2826fc6c47d88cf.nq.gz
│   ├── 0a7a0ef1dc1d9beba8a3ca997ca27dd82228da8d.nq.gz
│   ├── 18f930a2b8d39e884e9bed3f152e4c917e13e4c9.nq.gz
│   ├── 1be3dbaffca36b9711a4bbee6a751aa18dc018d9.nq.gz
│   ├── 1ed034700560543d00714a53af40ae2958fad583.nq.gz
│   ├── 31690d43d8955edc3c9c90bf80853011f8d777d3.nq.gz
│   ├── 322793040792b8440f6bb6db6e29660b8e54b266.nq.gz
│   ├── 350c37d5f5d4137cea684867c40bfdcf575f56d5.nq.gz
│   ├── 39bd71ed6b19f19b1bd1d328f1438212ff426b42.nq.gz
│   ├── 3e9244fd0d4aa255875b8376ebb2f51a7683ab7d.nq.gz
│   ├── 4cffec6b4d85363286befaf2a28e876d48f81847.nq.gz
│   ├── 4f5b8da8f6083400f452a5cf9f6975b7d152db2b.nq.gz
│   ├── 5191c01deed093a87ab11a04383f6ff7da7fb241.nq.gz
│   ├── 539df5ed5c3e6522a4306900efa572756189074d.nq.gz
│   ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
│   ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
│   ├── 67eb948d72ad9ee53fd1cbe38e72bcccaa753334.nq.gz
│   ├── 72bc2b72bb939cce51710706be5f94c7531ed6a1.nq.gz
│   ├── 7315eb3689d4e5b108573f4873eb63727f13517d.nq.gz
│   ├── 740322d6dac2da362be2e82b09d4466dba9a3b7f.nq.gz
│   ├── 74d9abcbe3c8862d917ebb695e7a5015c0837555.nq.gz
│   ├── 75b941788b05b9e47ac50c6399c9ed953c183e60.nq.gz
│   ├── 7bf3de59f2d4d526d6d301cea4f44d3c8a1823d5.nq.gz
│   ├── 8ba8ec6b2ea2618514cf18732934d0b79312744d.nq.gz
│   ├── 9f5bed44ec106502c159a68e71e8308abddeb4f9.nq.gz
│   ├── 9f8f2208c4bdc0f0b0cafb4c0d0b5c79d32c32da.nq.gz
│   ├── a1d50655bfde82f937b3a1e4d097de205f5b84ff.nq.gz
│   ├── b8c8d47fa0a99101c675af913b08144664399119.nq.gz
│   ├── be5b2b862a636d4736393aa9a9cdc7ec6ba902e1.nq.gz
│   ├── c2b6f9dbc557698f9905bac1700766358bb4fe08.nq.gz
│   ├── cc32eda8a90cc20e1e9fdc7039b83be81e3d1445.nq.gz
│   ├── e32b6d4bd85cc04b06ddd963db2323f606149ac2.nq.gz
│   ├── e495695163c24626402220e27cc9ff91326df874.nq.gz
│   ├── e670e4ca860f0cb66c4a4bd7a128de234933daf5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8d141e51d0cee6b072bebb3d97698c9ece8c8f4.nq.gz
│   ├── eaf663994f201fa783526d368a41ac3809c15368.nq.gz
│   ├── ec16715804668bb2309c0c2524dac779ac18d68c.nq.gz
│   ├── f45bd473a964fbb783ab5793aae02ba8cf07d5e2.nq.gz
│   ├── f5687c010fe1e2c01155b5a26a9a07deea3f654c.nq.gz
│   ├── f685dc2f504e502ac786e3ec3fc6278f2f3b6bfa.nq.gz
│   ├── f93b7b149d277d7f7fd1688d80cefb9beb7e9d15.nq.gz
│   └── ff0b40fd16093f7aef90f7d3b4c8ecedffcc62a8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d10d27a70e6b5813453ab52cb21728f51cd2411e.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 51 files
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

[scverse/zarr-kvikio](https://github.com/scverse/zarr-kvikio)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
