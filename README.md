# Repolex Knowledge Graph of pytest-dev/pytest-django

RDF knowledge graph data for [pytest-dev/pytest-django](https://github.com/pytest-dev/pytest-django), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/pytest-django
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ad5867df0bbb8ba4743694fbf5489a6b58c00a07
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ad5867df0bbb8ba4743694fbf5489a6b58c00a07
│           └── chunk-001.nq.gz
├── blob
│   ├── 045b783a77c069e69bde2fd46c773e5d9b4809a5.nq.gz
│   ├── 05c84694f6018798e97d5da0580df1f7405df3b2.nq.gz
│   ├── 065696d99bb9fa9c91fc8f007333e75c80f213d7.nq.gz
│   ├── 0ac49e9614656d10e7adcd16be78b4816e823701.nq.gz
│   ├── 0c4ef024f277d4755e983894d0b69a3f5e992018.nq.gz
│   ├── 132bbd234e169682f6fcdfd450f6bc8e67c1cd95.nq.gz
│   ├── 177c8062b160788d8a5e0593f8264b37a95d8768.nq.gz
│   ├── 1b5442d4f4360f1bd7cf8f800ef21aebe7f25537.nq.gz
│   ├── 1e01a4834bec0ac923a67b114bc50f16c1f17046.nq.gz
│   ├── 1e4691812f100d297a90083d9bdbb515322b80e8.nq.gz
│   ├── 27011bfa97c52551c22c998dc0279fc466b79eb4.nq.gz
│   ├── 2acf0e2feb8287b48d46331c6dff148fc52b30e1.nq.gz
│   ├── 301114a8f1e8d7cb130dc81363dd41b3f1123463.nq.gz
│   ├── 3cb04dbf9ec4554ae668335713d11d16a449445c.nq.gz
│   ├── 47d636d5a3a7a31788aa6387524b68f9bfcc0381.nq.gz
│   ├── 4e6787f630a98d9888c0f8b6ef0505dbe3a7c88f.nq.gz
│   ├── 50ee89967e366fb7f9e744a5b2b5dd0e686ce3b0.nq.gz
│   ├── 5545545c9aafce26f3c54b0634fef6a9c4451286.nq.gz
│   ├── 561ef822c3f52c30980440401964c948d7456adc.nq.gz
│   ├── 5626de011b5ea821d205447e73f134911543de12.nq.gz
│   ├── 5a4f4d88ca836c70af8c2a9e0ad95d30a8edf75c.nq.gz
│   ├── 5ac1357fd96ae1d169bf1529de1467b35e6dc50e.nq.gz
│   ├── 636185d9d5cd394da83447f14bb62b0f7892c9ac.nq.gz
│   ├── 688458fbf3ee60f24b488b8741482b7b22535e20.nq.gz
│   ├── 68d587e9866025bc6c54b9f46b89068d1bad3a6c.nq.gz
│   ├── 6a058a2d78d28e315c993bc28a3cb4c54c2d826e.nq.gz
│   ├── 6c15babfe562d3a35a84377b25edf222daa96e47.nq.gz
│   ├── 6e9822c673794d3b735f82540cc2211b7ca03549.nq.gz
│   ├── 72d9c183cdc431f136b55a441eaecd61d6f9beb8.nq.gz
│   ├── 75f247e2eec50092ac6143c3c7f6e2f6f27c261b.nq.gz
│   ├── 76ec8ad7fd9b2bf8a2156a88bbb8a9a2e4d84b32.nq.gz
│   ├── 78c55d5c92eccf10ee4e8f4c555ff03e771e78f2.nq.gz
│   ├── 79a8adf99e01fdcbd8a0d392c2f011e703706a61.nq.gz
│   ├── 7bef403fc8283a74011cf84df32bd285f2dd8370.nq.gz
│   ├── 7c77098f7b831f723585286ab96fa4fbe6bd0061.nq.gz
│   ├── 7dbbf7104faa357d224c4c38efab27735c573b73.nq.gz
│   ├── 8383a7b54d853a815ccb877be5d110ed291ca3c1.nq.gz
│   ├── 85b1fe7b64f2c86de6a8e7422eaebcce98208275.nq.gz
│   ├── 8ac6b8c4984dcd382e54c7923325af6d226ca3df.nq.gz
│   ├── 903556cd96d21caab7d2afacdf95b8364fea225e.nq.gz
│   ├── 91a5ab49a2683a5c779fdee4e04abca88ed5a8d0.nq.gz
│   ├── 9288359ee93d793b9a744e2db892733848ce848b.nq.gz
│   ├── 956dcef936d3b55620bdd04621bcb4fa95e3044a.nq.gz
│   ├── 980c720c1152d5edb1c8fe2bdc6cfbbbf02c21ff.nq.gz
│   ├── 9a7643f4a78a24b57cf2af1c0533b23f1fcfaf75.nq.gz
│   ├── a0bee059621efdf6bbf5f415c271e46c38021ba3.nq.gz
│   ├── a7b13a042c4381573970ae9655a98b71fef15945.nq.gz
│   ├── a7f8d9e5dcf3a68fdd2bfb727cde12029875260b.nq.gz
│   ├── a935769aca229aea61f56cf2c45372629bd3458a.nq.gz
│   ├── aa45ff38a665f254d8cd2e0cc86e5e838052b89d.nq.gz
│   ├── aaff070e1ac76d04c6e769fd8326c7400e4f69b6.nq.gz
│   ├── b20b7904ee532a1dff0743a490fa84c275b4de35.nq.gz
│   ├── b5cd41d8b44b0bc143820afa4fd558de59f27ee5.nq.gz
│   ├── b8a4b84fe7d00b447f615d6642dd5c1a75e6f2e4.nq.gz
│   ├── b9efe86ddb30b1cc37e8bb55f5cb9daa312a8d9f.nq.gz
│   ├── c13e1e00c5498b71c60218b524aaeb61ecfa35ea.nq.gz
│   ├── c2545f1614d7e8f7e64e70d1da7519363158597b.nq.gz
│   ├── c52c2ca334b20ce6ffc42bbfc2b8bdc9f113aa62.nq.gz
│   ├── cd376fa6828500b6d68a81ec8991a1e55292ce15.nq.gz
│   ├── cefb1bc74aa857d961f62f244b0975c8f610e223.nq.gz
│   ├── d19ec1e5b647ca922438da4552bf3c177bd12caa.nq.gz
│   ├── df1c6bb47302c54300dd0a0464244db2f1531f7a.nq.gz
│   ├── e1c8a982531e20b378034e03c45882562c8936b4.nq.gz
│   ├── e24f65fe6239bd3062ff3e37692d66276a4d4049.nq.gz
│   ├── e43b7e7b5047f544487b2175e4c083957fa17f80.nq.gz
│   ├── e6273bbc8be5f37f51519474241304d87b25b9e5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f05b86084adb81a597fa74d77dff2e945636f463.nq.gz
│   ├── f1cc869733883292e9feda92cf6fe28225b87a3a.nq.gz
│   ├── fb23703c58f74526886ce9dadcec5b1815825fdc.nq.gz
│   └── fcdd219a5178f819d29e122d4483f7b254044ac1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ad5867df0bbb8ba4743694fbf5489a6b58c00a07.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 79 files
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

[pytest-dev/pytest-django](https://github.com/pytest-dev/pytest-django)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
