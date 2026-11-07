# Repolex Knowledge Graph of kivy/kivy-sdk-packager

RDF knowledge graph data for [kivy/kivy-sdk-packager](https://github.com/kivy/kivy-sdk-packager), parsed by [repolex](https://repolex.ai).

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
rlex download kivy/kivy-sdk-packager
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8c7b6d2c8ff04460c604eb0a7d460a70f29d669e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8c7b6d2c8ff04460c604eb0a7d460a70f29d669e
│           └── chunk-001.nq.gz
├── blob
│   ├── 07f3d4973938850cce212005dc4c48894f7ee3b0.nq.gz
│   ├── 0a392f3ebe39f75262920a134ff1f41dc9415cfa.nq.gz
│   ├── 114d952fb250d4323a9828e17aa83374fbb6a760.nq.gz
│   ├── 11c3db05b377e74f72ce0f5479bba9c97492da46.nq.gz
│   ├── 15b915c4dcf3692dc286c6848044445c96787b3f.nq.gz
│   ├── 16b2b485300b2ce8d2ee1a533c2a91ee6dec8798.nq.gz
│   ├── 1751ee3af82e8aadc286d07bde9f4cd381a269da.nq.gz
│   ├── 1cfe26e8cedefd7fe3570645192853e1764b69af.nq.gz
│   ├── 1e5a5c1958b6eadde64cff622ba88385e1eb4da8.nq.gz
│   ├── 1e676985a89d40ed7603f352a56c70a54238b7fc.nq.gz
│   ├── 1e9347eb7c7f77fef4200fbc976af4ab2755bb4d.nq.gz
│   ├── 20d6e16954723278b0d1e9badde1d731c26695b4.nq.gz
│   ├── 2270824dc138031a484253bff0c4b2bd27efe0d4.nq.gz
│   ├── 2422649deb2e39387afc8a74250cf995e349a1c3.nq.gz
│   ├── 29d18faa24b01a0961febdbc549acede3d161a63.nq.gz
│   ├── 2a065140ac10974bb7be0b1cf4a706814a7de685.nq.gz
│   ├── 2e8928c4bfc6972fa8a36ba581bfcc0760a0a7ef.nq.gz
│   ├── 327af3f9ec2cdd3cf812764d6b9eecda89b2d65d.nq.gz
│   ├── 3799b91ce7f7b5bca5a322fc800680bcfe52e19c.nq.gz
│   ├── 389a733ed11a13575d0e9c0d531fb75572350dba.nq.gz
│   ├── 3f868c81e9b367270f1bec96572de226f3fa76a9.nq.gz
│   ├── 462ee24c8048576cd35fe41939290f390d68b1a9.nq.gz
│   ├── 4d9045ef6bfc4f0c8fe8a3bb2ba1326e762276e4.nq.gz
│   ├── 4de80c4722dd1877da0ba00cd5374604eff5c7f9.nq.gz
│   ├── 53ac0d956b4fba50d58285a7d06e957d1d01b317.nq.gz
│   ├── 56105ea56c7b87348106b01c3b109e15ab027722.nq.gz
│   ├── 59ee54917e3eb0e17125fa39fab0f1d11434ee2f.nq.gz
│   ├── 5a3b2ee99cfdff2259b7f25eaeca77409ec2e4e8.nq.gz
│   ├── 5cc6a7c996fbf45da185184e579b5a54a2a9da4b.nq.gz
│   ├── 5f77a2995085863936e3eeda8f4ba87e5a315c62.nq.gz
│   ├── 61580e96e64a1e34582eec7fc9814c8ddc62dd55.nq.gz
│   ├── 66732f996a68493704cd8429abc792ababe14745.nq.gz
│   ├── 69523d329a219396e4840b18d3e4671f808e6193.nq.gz
│   ├── 6d30f8770108592c87baffae0d875e6b8ead7fe6.nq.gz
│   ├── 6d6ae188ae665447c87b4632c611d2456d15e331.nq.gz
│   ├── 868b13834ae04263bf3ad79b4a771eb1d4c7dbea.nq.gz
│   ├── 88fb11d44c93d29698db6b9c92d5387e0c0ea50c.nq.gz
│   ├── 8d799e5d4c736968925c87e014ccf244dc9d1728.nq.gz
│   ├── 9362efb91275195721f33621e5cb8d4174e7d53f.nq.gz
│   ├── 953850ad654a680e1e7706d00330bd24e3cbff9a.nq.gz
│   ├── 9a35b3ccb05a312edc5295f4dbd24ce5c8cd9276.nq.gz
│   ├── 9cc76ff87b9ff97c58f03ccdf9f4c6e6d9ca4780.nq.gz
│   ├── a0419fd7948adf004d1e9b0b2254b4fc7d0dc850.nq.gz
│   ├── acb7e104dae30a61cca125485625568d737e0f84.nq.gz
│   ├── b49587b7bb2c30be1d2ed97b93b760d344826474.nq.gz
│   ├── bd4dd19828113fdcb0a3e7229e5b4db5fd90d199.nq.gz
│   ├── c23091879d29ad50cf130a8fbf2815c22bdf4e1d.nq.gz
│   ├── cbdd8b39d5338612e80a0b8b8c05584bbcdb92a1.nq.gz
│   ├── d104352fef95fc4e2b35f04a4272b8a83ee7d4d2.nq.gz
│   ├── d41ca435a920d5f4b1f323d77454d51a1d42de89.nq.gz
│   ├── d57b625fdc7c26a92f828c0671fbf6d840a1aef9.nq.gz
│   ├── d86394877cf93eeb37b85864534a393f15df1af9.nq.gz
│   ├── d8eb35b87c3457876fa05179136ecc8da79b172f.nq.gz
│   ├── d9442cab8f725282d3c4cc49971e6367781dc244.nq.gz
│   ├── e19a33c124508561f817ce90569a71bf71a36c5f.nq.gz
│   ├── e2cde7cc0421b6f40f4102500fac2438c15f3bbd.nq.gz
│   ├── e3f64bd37ddfa6647e2681c0a523216f60939975.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e96b3f541aa61bcf7f0c046fbdd940f84bd70a96.nq.gz
│   ├── ea08d57a29af19b5fcc4ed96ff3cca0b95dcff04.nq.gz
│   ├── ea990da18df0243e52f87a1300ee35915faa9f1a.nq.gz
│   ├── edf7d77a26d9a445c85b9aa871df1fcbb95f0d83.nq.gz
│   ├── ee786572b658a19587bfb6653ffbc486a11f0c53.nq.gz
│   ├── f034125d2deaf341be6382890d5aab28ed6bd29b.nq.gz
│   ├── f08912482b5721c321fca8924a97a2482132c304.nq.gz
│   ├── f2944bdcd41d4e90f9e93ef6fc5287f4bd07eeb3.nq.gz
│   └── f3b9b0bb664bcd0d8a9aa89933784935b2dcd33e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8c7b6d2c8ff04460c604eb0a7d460a70f29d669e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 75 files
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

[kivy/kivy-sdk-packager](https://github.com/kivy/kivy-sdk-packager)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
