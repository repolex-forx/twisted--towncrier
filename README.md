# Repolex Knowledge Graph of twisted/towncrier

RDF knowledge graph data for [twisted/towncrier](https://github.com/twisted/towncrier), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/towncrier
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f92fbf5180f70e797af62932a4346573023d4001
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f92fbf5180f70e797af62932a4346573023d4001
│           └── chunk-001.nq.gz
├── blob
│   ├── 006574a704b0302366cdcef0848b582b971b4290.nq.gz
│   ├── 03b97a3a4083d97ba3dbcbf0b97c7493bf39f983.nq.gz
│   ├── 03fb195ce0a51159b53d95a067c2bb848a5a9645.nq.gz
│   ├── 0c504e1f34f3168f656913f231bdbee8abf29f48.nq.gz
│   ├── 0deb8392f4a63444a1136f6262c0ba72e897e9cf.nq.gz
│   ├── 0e709bc72b11b2bf1f565881e900a660c642d170.nq.gz
│   ├── 0f25f2f41eddbc1482a2a08117d69e7f80a56b8f.nq.gz
│   ├── 10334b47c7b18968620c2109cad3e13f24037547.nq.gz
│   ├── 165f9e55003833c67518c7bbd311a615d68eb4d8.nq.gz
│   ├── 17e1a2c534895367f41dac5e26f494f17dc5edf8.nq.gz
│   ├── 1872b84253cc56569db4fc5565d44fb9a35520a5.nq.gz
│   ├── 1932bd6e001d119362ec359926b4a1e868a60b58.nq.gz
│   ├── 1db3ddd5510dad06248310154cbcfeedb031c296.nq.gz
│   ├── 1e68397691c9f70a536b8d01543bedb3c6e1f081.nq.gz
│   ├── 2368e5bd3eb66f313b90fca4a72755e93f6db2f3.nq.gz
│   ├── 25ae18091261fd413d07d1ec2bad65bc94aac167.nq.gz
│   ├── 2670e23de7a0ccdd93454b3f3918d1ff2dfcce2f.nq.gz
│   ├── 291074a136cd594ceaf5ce8d772a157f05dbad2e.nq.gz
│   ├── 2f9d07816fc68f4d41da03feeef0a2b2042fc031.nq.gz
│   ├── 3d377898d005f5bd8629d31dd9499657bc3c42e1.nq.gz
│   ├── 406e375d82b6041df46db873ac7c341b8b59123f.nq.gz
│   ├── 420a30b01ecf686b5965eb1333fb4314c85fe38e.nq.gz
│   ├── 455e571d1b3fdaf6f8fff850a7063435628333ea.nq.gz
│   ├── 45fdfe1e368ff1ac1c9285dcf81bcbcb32cfa17c.nq.gz
│   ├── 4cd5352b53af35fceaca84b20bf71f86ef3e7dda.nq.gz
│   ├── 4fc689cc97e5be28c432ac3a0d2501e219be9e69.nq.gz
│   ├── 515c3e241cf2f05b13f3978a32b99bf6585fdacb.nq.gz
│   ├── 5357e8345fb2f782e3806f53a19a3c9614e36b8c.nq.gz
│   ├── 53db295a690a151ee0b1df3fdb9147565a9b9f23.nq.gz
│   ├── 5947413f11a98507cddfeab1e1d5936b26023405.nq.gz
│   ├── 5b83c515f652bbaf9bd64b3b0e30ecfcf9619294.nq.gz
│   ├── 634b5f1956c00dea425203cf7031319322e29c21.nq.gz
│   ├── 6694510291ff3c1879ad910a4ecef000968c5392.nq.gz
│   ├── 68c4f793ac11e056fdad9259094a65f2dec04930.nq.gz
│   ├── 6a702c8a1e5e0f92fa52cda3f8e383d7fff30aed.nq.gz
│   ├── 6c101c362c6e990c936a48d4e2fc3b608f878792.nq.gz
│   ├── 72912bfa6163452b16cb349e5e364b9f808a24bd.nq.gz
│   ├── 7a7a8c615c107c4ab4df97c19d526d098155e70a.nq.gz
│   ├── 80e89fafc2c8d43176eae6377c6174b3e41ad0da.nq.gz
│   ├── 8bf919daa35a3cfa698197a0d0604377397bf068.nq.gz
│   ├── 8fa91acbcdfcdb16b05de7d5642212b288e8fc67.nq.gz
│   ├── 91522a1bb3e6c6668b2a6cf7ba5958bfd010ed65.nq.gz
│   ├── 99be2bdc9e479fb55458f3697c9a6d5d9611b372.nq.gz
│   ├── a05cf419bc9ac3a1e38d5e31f03e55b56f7c750a.nq.gz
│   ├── a17a60d6f21c52a82a100252366d9d0925b20b90.nq.gz
│   ├── a689634e84e31f1eb4ff1398348720600be3df15.nq.gz
│   ├── a7b8541f748e517129bcb810a1149f971f23662d.nq.gz
│   ├── a875d70a6e6197c44623e4a9f3bf586645fcade9.nq.gz
│   ├── ab8e98acba4a1b8bd1657058bfd0f9baefef6f4a.nq.gz
│   ├── b2d2c22ed0fceb2d4f43202d422cc0343519d266.nq.gz
│   ├── b39daf1b63f11bef95078d9f8a5ace90fde5e5ad.nq.gz
│   ├── b5a8110885dd2f360cbc65b4f9c2172735ddffb0.nq.gz
│   ├── b8ca989726e569a01ad51ca6ceede14776ee77b5.nq.gz
│   ├── b96baa5140cc670d97eb0c1853fc1e343d9e1cb4.nq.gz
│   ├── bac25b905322296c9141f177e4305dc92716feb4.nq.gz
│   ├── bee157200294d44fdfb2013a666f78945a51722a.nq.gz
│   ├── c6238df9cc54349e81c0e9ee6c77206ba230b849.nq.gz
│   ├── c71d45d7995128d80bf5168751a3ba3bc0d291b7.nq.gz
│   ├── cf8d93783d3765fdd4b97c33a342aa5e96d5fd4f.nq.gz
│   ├── d1b95fdfbbd413f09cc93c7d54fe563a0116bc75.nq.gz
│   ├── dae0be29bcb309925bd65cac864f58bbcafb548b.nq.gz
│   ├── e101cbb7b89aa7afea57ba4dddf5ab282fd9ddbe.nq.gz
│   ├── e25b0b5c9332986f7e9f948ef487dac33661bcd3.nq.gz
│   ├── e35d8850c9688b1ce82711694692cc574a799396.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7ae4a1ab35fa2c2b79800b8e089737d5bb716a6.nq.gz
│   ├── ebf04b54ba01901200dccfd8aaebe91f328fb6d5.nq.gz
│   ├── ef7d53db26cade84e1f8c2fff74d8c6f5be8138f.nq.gz
│   ├── f681bf6a9ba0aa484b31bbc09ca474b1b0be73c9.nq.gz
│   ├── f6cda3e39137ab2837a6650ed6d040f87b9558ae.nq.gz
│   ├── f83e8ce4130d5546796eb6dda3b86797cb2ae88b.nq.gz
│   └── f935021a8f8a7bd22f9d6703cafa5134bb6a57f8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f92fbf5180f70e797af62932a4346573023d4001.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 81 files
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

[twisted/towncrier](https://github.com/twisted/towncrier)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
