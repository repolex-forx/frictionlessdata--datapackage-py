# Repolex Knowledge Graph of frictionlessdata/datapackage-py

RDF knowledge graph data for [frictionlessdata/datapackage-py](https://github.com/frictionlessdata/datapackage-py), parsed by [repolex](https://repolex.ai).

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
rlex download frictionlessdata/datapackage-py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fd3a9af665cc0e5052437904258b063fb565c6e2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fd3a9af665cc0e5052437904258b063fb565c6e2
│           └── chunk-001.nq.gz
├── blob
│   ├── 05aa6ccef6538fe0b4f400fc464b7cb9df3c5e96.nq.gz
│   ├── 07aa940e8cd44c6fe1a8eaf6df2c486764e4977d.nq.gz
│   ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
│   ├── 0d815fac8758cf9b85efe03457f3d2e651f2b1d7.nq.gz
│   ├── 1462c9c816eb1598ea19d44105fd71e5dbc66584.nq.gz
│   ├── 17e1f06ef12cad0d514e385c0c8d714505a4f873.nq.gz
│   ├── 19bdf10533946eccfb6ebaa678fd3923f753037c.nq.gz
│   ├── 1e1e019e7bdab9ec41e9b1705b8709c64d6a1bdf.nq.gz
│   ├── 1e7878f673ef53ed88b864afffa44e4d6a9c5f0b.nq.gz
│   ├── 23a993ccb451dc704c1175e4f7f0004af475f027.nq.gz
│   ├── 2406580b63df8b92a7f43687989e487ca86c3184.nq.gz
│   ├── 257cc5642cb1a054f08cc83f2d943e56fd3ebe99.nq.gz
│   ├── 274087db1806993aa1c5e4453fbcafdf1eb94766.nq.gz
│   ├── 284272164c55762559e2dc8b373a24b5f6cfa401.nq.gz
│   ├── 285ca9756e54ecbb1352bbc7579c48023f9f2266.nq.gz
│   ├── 2869c53cad7847d8a587064a47662144a7e0c2fb.nq.gz
│   ├── 295bfe20fe1db33a3d8a3f92bb93654a3df37fd5.nq.gz
│   ├── 2a9acf13daa95e85642ea255d3e3bd1ef8252804.nq.gz
│   ├── 2be91211aa2cd002a7fbc6a0dd8945309569bdbf.nq.gz
│   ├── 31a8dd6cdde13ceaf5ca025c1fe523885764588e.nq.gz
│   ├── 384d3a0c4305d6d95543a7495e8a34fee29135c2.nq.gz
│   ├── 39bb70085f9c986edb1b2ac8d2013200f3ab1205.nq.gz
│   ├── 3b6126192f85a884c0a5393606f3fd547d56a22d.nq.gz
│   ├── 3bd1f0e29744a1f32b08d5650e62e2e62afb177c.nq.gz
│   ├── 3fec5649c5f4d54218c6534a3abe0e3fa6d8d997.nq.gz
│   ├── 405f31781c58533fb8719a29b075445d2c4d78e1.nq.gz
│   ├── 40a4bf5e2dfb2dc78511cbb4eed288f3faf680d8.nq.gz
│   ├── 41db2f14cb08f5f3b9120acb8bf43d04368f69de.nq.gz
│   ├── 456e8ca6c611bd24b677cfc0aee7cd134b507f53.nq.gz
│   ├── 46f5342064d91a42e246d832ec6b4ac4eaf7213a.nq.gz
│   ├── 491b387d8d6d91068118d761ee1acb5a9f757077.nq.gz
│   ├── 49b84ef7cdcbb07e5f10ceadf4d25a3917a79bba.nq.gz
│   ├── 4d8696220a5543125c1d6946b1b2d106c4569dcc.nq.gz
│   ├── 533542fdd39f9aced18b127139b437c82d70f627.nq.gz
│   ├── 5795f32f3933fd42c13926071a1066db0ae4a3b1.nq.gz
│   ├── 597a7330cdb8944887046e17416b9835dde6b2d3.nq.gz
│   ├── 59a2269cb02a86809613bccf67fc3b7f98abf744.nq.gz
│   ├── 5ee6477165727539aa0701c22b47da2ceaedeff5.nq.gz
│   ├── 620ab76a896f72e26c009cb36cfcc9d172115ae4.nq.gz
│   ├── 64bf820e0e354b97c4f1ae56cb8ddfe00755c702.nq.gz
│   ├── 6640fe4200a01ac841793cde9556eba440a7ee78.nq.gz
│   ├── 67740870bdd2f9839f320621677538312cb85ece.nq.gz
│   ├── 6abc26ffa7fe70761680d290562fb061bd1e2583.nq.gz
│   ├── 6b1f3473823ee503ed49c9ca9d490765e1fb85d1.nq.gz
│   ├── 6ed112012336ae3aaf6c9205badb81c037daa7ff.nq.gz
│   ├── 6eedc6bf8be3ab34832211a5c3648fa6d8ef8025.nq.gz
│   ├── 7014079f65d71e3f1c37c9eb967c42f1081d72c2.nq.gz
│   ├── 7188312aaef925fd5a60bbd1350c82c426f4db14.nq.gz
│   ├── 723707443d702267339393dfe0d4ac267705cf19.nq.gz
│   ├── 73bdff7311add0678910e8b0d57d83c197004e4b.nq.gz
│   ├── 74f2012ea7289d85726792e64853e915507698c1.nq.gz
│   ├── 79b1ea256032cf04d1a2ca510707c98ade030701.nq.gz
│   ├── 7af9ef63745b43cf460b12fbcbd00e4a755ddf58.nq.gz
│   ├── 926b7366460297ea1f25046e8b40a022715f3e93.nq.gz
│   ├── 9c29ee9489c5473cff55079ed16a8681f7376291.nq.gz
│   ├── 9fa207648f15f9804eb5e28f2d72d17c2ece51b9.nq.gz
│   ├── a0a382a22052de1dc6ce04a4ef423a73a7db88a7.nq.gz
│   ├── a1b0ae96bab7bce61f34e54387676412237ff8ec.nq.gz
│   ├── a26d95e2f84d054b7974b1b83cd76030e8038ab7.nq.gz
│   ├── a3431d7cb094026f84360540b7c44cc0b33d2c08.nq.gz
│   ├── a5b36e0f923748dc2f8dfc155371ff615142f61f.nq.gz
│   ├── ac4cde72abd8ddc04000c0db5b1cbe49f0eddb74.nq.gz
│   ├── ae591a7615259ce7aa8abcba1125f65ded719567.nq.gz
│   ├── af043c264bf2a8f08ed9e15896eb9f7fbd5b9020.nq.gz
│   ├── bb5273aa1b52cd8fd45eb810bce8929878af3f77.nq.gz
│   ├── bb7df0b6142674a8fac18e0cef5635d01ec24c89.nq.gz
│   ├── bd546a7c11825d3a804f769e83351b2644751a15.nq.gz
│   ├── c057c45c846316ac8740f4d76fd79eaa8a2dc7f7.nq.gz
│   ├── c3ebd065743f27d76fb9396080504a511ecfd9c3.nq.gz
│   ├── cc7278093cce88f10c3348a9c45df31d31c1be14.nq.gz
│   ├── cd505058dd5028b40f03d34f98269e35e74af977.nq.gz
│   ├── d7fa4094a8c43b28851df2e2242c22ade8a71a1e.nq.gz
│   ├── d83ec256d32631fb9a1b6cd05d36e4a44634884e.nq.gz
│   ├── d86a124e686c9097bd5913c1a32fe23cc7af16e4.nq.gz
│   ├── e34208c9371c00049587efdc6bb6fba86412c35f.nq.gz
│   ├── e52f55f4f06381955709abdfc1ddd0ce02db77bd.nq.gz
│   ├── e8d45fd4971c0a4e76408a91e51091fcfaf47813.nq.gz
│   ├── ee19b45d9eb6b758567868b0af5dcb1dd3be34cc.nq.gz
│   ├── f6fa7f5d76f7bb52398f233624b4e214a2bdc1e9.nq.gz
│   ├── f7574d0a32717321f53630ad454d135d41bbcbf4.nq.gz
│   ├── fd849b14996faa70ea1da88508d9a06d170c3ad4.nq.gz
│   ├── fe51488c7066f6687ef680d6bfaa4f7768ef205c.nq.gz
│   └── fee66a8c5785e2600182c1517740563cd97f2025.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fd3a9af665cc0e5052437904258b063fb565c6e2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 91 files
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

[frictionlessdata/datapackage-py](https://github.com/frictionlessdata/datapackage-py)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
