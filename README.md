# Repolex Knowledge Graph of dtolnay/async-trait

RDF knowledge graph data for [dtolnay/async-trait](https://github.com/dtolnay/async-trait), parsed by [repolex](https://repolex.ai).

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
rlex download dtolnay/async-trait
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a7e91e98a5d2de2ceae52d9459eed309939a98bf
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a7e91e98a5d2de2ceae52d9459eed309939a98bf.nq.gz
│   └── repolex
│       └── a7e91e98a5d2de2ceae52d9459eed309939a98bf
│           └── chunk-001.nq.gz
├── blob
│   ├── 01981e6de431f29fcb39a39b458e6b3fcaddce7f.nq.gz
│   ├── 12105177e1f44d28e5cdad9ed230712b2fa49be9.nq.gz
│   ├── 14939459e1ef656271212d3ae2042f6d13fcadec.nq.gz
│   ├── 151b0311b0a890ac9793f727f50abf7df300bd20.nq.gz
│   ├── 1531be62e76b518ddfccdead88dc30e7b0b9310f.nq.gz
│   ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
│   ├── 237cf667f10385a44a3a4fb79e9ddea40a71e578.nq.gz
│   ├── 23a6a065ec960a031726c8c26222b0405d4f5851.nq.gz
│   ├── 242d17aed7f5adc9bdd663d781ecf66df99b2fb2.nq.gz
│   ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
│   ├── 3a5f58c3ace29f188515f1d93b116cc5f0dcc9d1.nq.gz
│   ├── 3b3105a4d39255467406302206f1fcc065d00639.nq.gz
│   ├── 3cdc6e1bc35dbf3eabb6d8310690a9852d6fb19f.nq.gz
│   ├── 3e3f80470512731deaefdb4c56098c568b67f86d.nq.gz
│   ├── 47db09870b79b882e7f093afe73c3b5cd3b33070.nq.gz
│   ├── 47e4ca0497b31522a4071109d3cfee6dae5af09f.nq.gz
│   ├── 51a44a24b5be122641706eb7972b3ae90d0ab0ac.nq.gz
│   ├── 5675c605982ecad6ff4516b6055b4bc84f528968.nq.gz
│   ├── 56fea7a1f8cae2f8bbee1ae74eb0c16a5c22e342.nq.gz
│   ├── 5868c614ad8cfb574532c4a520896a3dadb5d678.nq.gz
│   ├── 6065861601769fcda39859c58d11104bb9f21e09.nq.gz
│   ├── 72d97e9525b38e5c9266a67c5c572d69ded58e18.nq.gz
│   ├── 750707701cdae985156601cc906195021ba6a6e5.nq.gz
│   ├── 7ad0d9bf33d9b41576f0546e929619351878e88e.nq.gz
│   ├── 851560b17ba9b385524fec289f5d46e00c006c1d.nq.gz
│   ├── 912fb798442e7510ab0ab7d0bb28ff045990462a.nq.gz
│   ├── 939708a2d117854d218d9a3699f283a09d71738a.nq.gz
│   ├── 98c12b812af01bda80ced2ce463d2a0c72502c5b.nq.gz
│   ├── 9c94b228f300ee9f8981765766eae707b44c408d.nq.gz
│   ├── 9ffef5b4abaf7266504c4f7a31eb5cea2ecc6e91.nq.gz
│   ├── a3c4e7b4d922c5009dfd3d7d1096616e401f1b3a.nq.gz
│   ├── a4e74cfac898a824bf0fd77da1b9891d3bdba345.nq.gz
│   ├── aefe0d6b1053ef7b9c09528bbda393fc8dfbe337.nq.gz
│   ├── afcd6b44c3332d26f50c81b4f38c34e45fcc5d3d.nq.gz
│   ├── b01f247032d55dcd1f7f15484ef73ee463b435c2.nq.gz
│   ├── b13063866a0990114ee39d9726def1b0d9b7e4f0.nq.gz
│   ├── b83aa72fcf2eef3998abdde2b88dd839f06ef4f8.nq.gz
│   ├── bdc30a846402a657e93dc8b8ddf2b93c9a476a94.nq.gz
│   ├── befd90fe238061201ba80d078e72621e1483dbba.nq.gz
│   ├── c0fb431bf391eb487096d98afc66ce08152d3315.nq.gz
│   ├── c14f0c8fb39ad02ad11ed822341fbe0e1ef967af.nq.gz
│   ├── cac282644428e1369bc31decc75eeffb9ee86bf5.nq.gz
│   ├── d064f6ee1f312acd09f31c2f19ac17658500d6e3.nq.gz
│   ├── d69da0e8d4d8334e0fd220f9c99fcd3faa5fb528.nq.gz
│   ├── d8883fb498c1aa72685b320498bb87094fb56c4c.nq.gz
│   ├── e6ddb425f950aeef60b9fa7b38e59ce269b5fb9b.nq.gz
│   ├── e7426888882ee9f15404d9b70bb8ecbef6daebe0.nq.gz
│   ├── e9e21997b1aca0707f8749ea13c09aec66c899d2.nq.gz
│   ├── ebd253514f84b5a63787d2e60277599ce53df89a.nq.gz
│   ├── f0bc5d80530661a7b436a8a8c36478bf0dd6ace6.nq.gz
│   └── f3e1126d1d5b5a6d42419dd16ba7d73e3dfc03b1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── a7e91e98a5d2de2ceae52d9459eed309939a98bf.nq.gz
├── filetree
│   └── a7e91e98a5d2de2ceae52d9459eed309939a98bf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 61 files
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

[dtolnay/async-trait](https://github.com/dtolnay/async-trait)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
