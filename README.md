# Repolex Knowledge Graph of sympy/sympy-notebooks

RDF knowledge graph data for [sympy/sympy-notebooks](https://github.com/sympy/sympy-notebooks), parsed by [repolex](https://repolex.ai).

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
rlex download sympy/sympy-notebooks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1878319fce86df62bb8944492b8a211e259c8078
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1878319fce86df62bb8944492b8a211e259c8078
│           └── chunk-001.nq.gz
├── blob
│   ├── 05f0bb7f49490ec0ac4b02d6c6c01deaf8769b1f.nq.gz
│   ├── 08070e21b6b47b2b56bd8ad55e33a8a348bfe6ed.nq.gz
│   ├── 0be10e0d4a054a1b4cfb798f50a2619e700cc2f6.nq.gz
│   ├── 0d4f9c8374bd73fd083998fa3ef6dbd538e8263c.nq.gz
│   ├── 0d86e61f87fbc5aedd31cf3bc87a4a7bb7488a88.nq.gz
│   ├── 0da1ec2d38856bdc5571d2798c7ba30d5ab8db5c.nq.gz
│   ├── 0eb437e8e5b36f7ea3f6bb136f6bd6156b485cf6.nq.gz
│   ├── 135e19a95eff23755f077e977c4b3bc3431a68c9.nq.gz
│   ├── 158feba0ef191febc900bb157cc02842e4aa8932.nq.gz
│   ├── 176e6a21aa554d89b61bcad2c57070bd3e6e1ae6.nq.gz
│   ├── 1b1c1ce1baf1484e5c2c327e377bd09c0442fd7d.nq.gz
│   ├── 21004f62bab601aea947ceb0055148c8dcd2526e.nq.gz
│   ├── 252c4c6f37d5b2b67b451c1099b939889ca34c0e.nq.gz
│   ├── 28679ff682c327f2bb6cfc5b53d15cf3d24b8cf3.nq.gz
│   ├── 2b04ec4d584afea168705921543cb528dc1c9d49.nq.gz
│   ├── 2eb7767cc8ff69e84dd7c9f463bab55f1b24ab3e.nq.gz
│   ├── 342a1cf38fdc757cb4b76ca7f4a8b087f6ce3f62.nq.gz
│   ├── 37e5969a24e0fac5d35d9fe3e0c57318fa684375.nq.gz
│   ├── 386b00d367017e480df5b363109ce40e87d59a40.nq.gz
│   ├── 3fbfdf7aae12f050c0a1f9142fce945f28dfa86d.nq.gz
│   ├── 408dd72e25a6e102471948b82b31581a840e56cc.nq.gz
│   ├── 4c62e4d003bd52663f285f67f320b31687a5f82a.nq.gz
│   ├── 4f7e75a479b21c09a8a8994d1c5769bada0a8c63.nq.gz
│   ├── 52e752e4fc829e3ab48e629f1b52f6d9f79f1310.nq.gz
│   ├── 56a9eafd449d5c9c37e01e92e6ea26332b60f173.nq.gz
│   ├── 5d52c28408e334270390f006054ee713ebaac2ea.nq.gz
│   ├── 5e508e7b7299e38e94e0b4854597dfeac1c82f75.nq.gz
│   ├── 646b26ce38313d1966fd26085a1f1333c2b05ec6.nq.gz
│   ├── 66b1cb5d0f698e0e11e8aeb5afb2d2e3601d5cf4.nq.gz
│   ├── 6ea50692feb92a1de53932f3bc441602b6d71ffa.nq.gz
│   ├── 72364f99fe4bf8d5262df3b19b33102aeaa791e5.nq.gz
│   ├── 73035db125505a15954b2b2f23df24f721faa8c5.nq.gz
│   ├── 732a2c4a801364957133457d9787882b4e3d5baf.nq.gz
│   ├── 7365aa9a4cfbe5e31e092e8449b78ca802453bc1.nq.gz
│   ├── 758ebea0e1a38ec54c2e4125e16e181de0d35d05.nq.gz
│   ├── 7a8359e05d7ea1b59bcefdaa7b6510883afa5071.nq.gz
│   ├── 80652d12dc8e1c26b8e72b2415ed699f81ae264b.nq.gz
│   ├── 8578be891bae9b4db7ba0c3905b4eaf6b3c735c5.nq.gz
│   ├── 8f27731388be1576e2873f9f075b4241081a4718.nq.gz
│   ├── 921c36d6c4d28fbd42ba1215b6a49ddcc27f2c22.nq.gz
│   ├── 9591510e1c80e7507990ab8a86ba8ce359656525.nq.gz
│   ├── 9930c359b7b85612b2a5e83191ea6ce13af00816.nq.gz
│   ├── 9d3d42ea9cc9df77758b929d8536279a8ae9d52d.nq.gz
│   ├── 9d5f7d056528674c60888b4d0fce8a3dc891d68d.nq.gz
│   ├── 9eaf02496aabe294e0574fdf31ad89a806e2c1c8.nq.gz
│   ├── a58d81ad6366b3fd55c28d775a9adb118b277748.nq.gz
│   ├── a6c304abb5d452b3f4bf137ce9de8a44a6d5e1a1.nq.gz
│   ├── acdbab33aca90b6bf1275f0c41409c3d4cd74523.nq.gz
│   ├── b6ecd4a4e650f9cfdf372e25658630814f1d4193.nq.gz
│   ├── bd46e0346275fdef6781a831e1bb64baac2d1e8b.nq.gz
│   ├── c1acbeac1c43721060781f1c97f080bf4b24d813.nq.gz
│   ├── c3bd9b0971c80f3119bbc6db50a24ea9fcea068e.nq.gz
│   ├── dcf388070c864a23e5da224a3aafce207877d63c.nq.gz
│   ├── e99c3186f4db881b06f50d8c6a42553299402e47.nq.gz
│   ├── ec9cc1c80aeda6c560b6e839cbbf8c9384ee6963.nq.gz
│   ├── ee1ea8d503d52e91cb63f6903f8681ecd9147b4e.nq.gz
│   ├── f6755845a9949a7686f441b00cfd007ef3564d33.nq.gz
│   ├── f7069b9815e494f22b325cf5351985e71d4a10bc.nq.gz
│   └── fa70f4b2dc1d5324fff73854949560d9b2528099.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1878319fce86df62bb8944492b8a211e259c8078.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 67 files
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

[sympy/sympy-notebooks](https://github.com/sympy/sympy-notebooks)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
