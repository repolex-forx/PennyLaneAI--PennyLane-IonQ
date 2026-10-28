# Repolex Knowledge Graph of PennyLaneAI/PennyLane-IonQ

RDF knowledge graph data for [PennyLaneAI/PennyLane-IonQ](https://github.com/PennyLaneAI/PennyLane-IonQ), parsed by [repolex](https://repolex.ai).

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
rlex download PennyLaneAI/PennyLane-IonQ
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 47a9a2d07eba9e05efcebee0c3a82e7580e1c76c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 47a9a2d07eba9e05efcebee0c3a82e7580e1c76c
│           └── chunk-001.nq.gz
├── blob
│   ├── 00bb9552796d5cf6635e326bbb4124220d591e63.nq.gz
│   ├── 0519596a872148560b35d6d917ac461d621572e7.nq.gz
│   ├── 0bc335e10119ce3dfbbcc8f005585b0cbfdf304a.nq.gz
│   ├── 0c1fa56ea485457ab562220aadfda3865f6edace.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2ad508a2b3acb619d064608d6fee05eb9ff1ce18.nq.gz
│   ├── 2c42946a120a09dcfa99dbc4e6a19e810a4168db.nq.gz
│   ├── 3800c1794ebdbfcf71f17c07c3e05551402dbe08.nq.gz
│   ├── 53cf63771a87e869ead5699891de255c6e4d89c0.nq.gz
│   ├── 56346963b76294060c2271f21b218ccd917637cb.nq.gz
│   ├── 62bc8cae3515b9d36ea6a79722eacdf70a9220a3.nq.gz
│   ├── 63e7a82b2fb2f10b1678f3a9836ae3c83d299913.nq.gz
│   ├── 69188f173e8426a292e456f2fd0116a882e317c4.nq.gz
│   ├── 734dc40efffbdeae9dd2e9f1856ec4d32812535f.nq.gz
│   ├── 857d5785b824b34a318c586c48dd9d62a2cc5116.nq.gz
│   ├── 8769bf620d8a34d7045b0e5043b549619d9302a1.nq.gz
│   ├── 8d4d66bf837bb59b127275481c324973cc67ce9d.nq.gz
│   ├── 95046b121230dbc0c2db250a01246a6f3e0aa33a.nq.gz
│   ├── 97a8ab8b63c17eee59e4dce0276bb2044b3f0cd5.nq.gz
│   ├── a00bcb3bf209c86e305033bbeabb62bdf24299fb.nq.gz
│   ├── a5472f0c929eec3b0a9ecf58ac5ce4b0fbc68f8f.nq.gz
│   ├── ab7f0e89739901c2d086fac0a8c343d627d5c074.nq.gz
│   ├── b0fbdf0e313d3fd3138974eabdc3c6f91a78ae25.nq.gz
│   ├── b1d536bd8a84f72bbd0e1bb0d5951f309204657f.nq.gz
│   ├── b26e3835122891a89e11bb8df7bbd223498f72a4.nq.gz
│   ├── b526314b3e38afcda84863e65f406ccb79d09863.nq.gz
│   ├── b69348d97da3e161718a410312935f4746b6cb54.nq.gz
│   ├── bb422ab860d4dc1f0a759874d8a80b083ff235d3.nq.gz
│   ├── bf2ccfb26ab4e6ec75a89d5d18514fa838ad44a5.nq.gz
│   ├── c0ad0648447162f5a4bd205fbe5216c6d0bb4a80.nq.gz
│   ├── c1469e64a78e0a1e2ebcc402fa315d66b210381f.nq.gz
│   ├── c1abf5ce880a2cf740a44abc033326098d8524f3.nq.gz
│   ├── c1b66e6e0b1a0788e5d670d606eaee753ab0e330.nq.gz
│   ├── c51b21f94ad40933b6a7ae315ac80dd9853b347d.nq.gz
│   ├── c58cf967ecb1a2cc6b3afb1605cdfd3ac696441d.nq.gz
│   ├── cac30bf94810b4d09be188f1fc0063aad76f4a78.nq.gz
│   ├── ce71d887237ab201a7625f03fed8fcf40b554469.nq.gz
│   ├── cf510d1b3ccda19d64692a87b998b1b0b134747a.nq.gz
│   ├── cf60f7f8bd30793ce31c41f377ac9bf50ef67339.nq.gz
│   ├── d9a259015802350bb2e9b9ea963b8b95cc1d61f8.nq.gz
│   ├── e40437fe3871732590c0f1edc170a52f919cb55f.nq.gz
│   ├── e56f89c224fc1360f992d9549de219eb518615ea.nq.gz
│   ├── ee87414a0bf28be3695ba2ad1d844c35a894872e.nq.gz
│   ├── f119c421ef54c0e48afad156b8c3baa4bfa45056.nq.gz
│   ├── f67bec815653a41d9d6bb7cda75b00f728640fe0.nq.gz
│   ├── f759043b221f749d93df1d642f3677e01be51f97.nq.gz
│   ├── fa22223f07d476230a99c3fc1e155ae623ec3bfa.nq.gz
│   └── fe183630319770e9463bced6d9d33ed4b96a0b68.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 47a9a2d07eba9e05efcebee0c3a82e7580e1c76c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[PennyLaneAI/PennyLane-IonQ](https://github.com/PennyLaneAI/PennyLane-IonQ)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
