# Repolex Knowledge Graph of MaximeBeasse/KeyDecoder

RDF knowledge graph data for [MaximeBeasse/KeyDecoder](https://github.com/MaximeBeasse/KeyDecoder), parsed by [repolex](https://repolex.ai).

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
rlex download MaximeBeasse/KeyDecoder
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 325477dab71201da9f437d66d00063a310b77eb1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 325477dab71201da9f437d66d00063a310b77eb1
│           └── chunk-001.nq.gz
├── blob
│   ├── 0864677c830841f2cd270a347095452d9db9f72b.nq.gz
│   ├── 0b387fb0b34aa3bed70a9ef79acde381deafa717.nq.gz
│   ├── 0bfa0971c11d1e928d518501d6f7f355a9661466.nq.gz
│   ├── 0f869bf55a260852a0d2cbca4b9576d47811f8b0.nq.gz
│   ├── 100793c61e0bf9e4daf8dec7fafb58bf9ec06bb8.nq.gz
│   ├── 104a9d4d01f8696e2a6d6670a8621c02d4f0ef4f.nq.gz
│   ├── 10c33df11c76255fd319d2f0e2219c359114c982.nq.gz
│   ├── 12534966712de1ab2465acec40ba6c681d2beb27.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 1a30ac3e2fd39eaafb3b74a2a716fec58909ce61.nq.gz
│   ├── 1d526a16ed0f1cd0c2409d848bf489b93fefa3b2.nq.gz
│   ├── 1f83a33fd4f2c45c5ffa5b6c1b729c431fd445fc.nq.gz
│   ├── 2342e70a85b6a0e57bc2506bd65e51ade435573d.nq.gz
│   ├── 25905d6a43a0728903da435b56a0e6b16ee55eaa.nq.gz
│   ├── 27a911c7f84c1ec8c47a3a8ba36abd28ab52e635.nq.gz
│   ├── 29d2f5ffa9f78a2d7ba6af8e8d99f69a881df5a4.nq.gz
│   ├── 2cbcfaace6f28d3715c2926585912f407a4a2fb6.nq.gz
│   ├── 2f191e537cfb8433ac60b7fc9e2a7d0738ac0584.nq.gz
│   ├── 304732f8842013497e14bd02f67a55f2614fb8f7.nq.gz
│   ├── 308a2a560b42f17aaf3c36e4e9c8cd07182fbb7e.nq.gz
│   ├── 32e24e0229247f3be834a12b77dba5591eb49c5c.nq.gz
│   ├── 33ca305f6519b8eb7b6a5ade6980d30d32a77be1.nq.gz
│   ├── 388b1cbcca7432fe41e0bf2d8d134d8eaf59347a.nq.gz
│   ├── 38c8d4544ff1c4419409796aa6c1caee2c262ff7.nq.gz
│   ├── 3964dd3f5b7fea7ecf391254ba292fcfe96bb513.nq.gz
│   ├── 3cda1babf92643728264b02ea37e8aa7954531d6.nq.gz
│   ├── 3dc246ea9a61c09d11eba63f39de5b44692a8211.nq.gz
│   ├── 3efc419d085299f8a4b30187d7da1f505f9a1e36.nq.gz
│   ├── 4721b8570713e5d72959e6f20bab89ee3d1a85e6.nq.gz
│   ├── 485d2ef543fef4dd9c0f950c2eb47a3fde30b32b.nq.gz
│   ├── 4d141965f5afaeaa48a06f31f0297b054ab64241.nq.gz
│   ├── 58001d1b6da587b568a088a23ad63409979e9cd7.nq.gz
│   ├── 592ceee85b89bd111b779db6116b130509ab6d4b.nq.gz
│   ├── 624aa9c7ea1851cbb33ee147079d208cbf3f79a7.nq.gz
│   ├── 645d620f5492a5bb3bb9028a675d5a3b9e258822.nq.gz
│   ├── 688ba2bc13d0a6ae0517625983aff75e6d03ca8f.nq.gz
│   ├── 6b4c0f78a7850094f62713858e533a2fc8eda617.nq.gz
│   ├── 70693e4a8c128fc4350b157416374ca599ac8c7b.nq.gz
│   ├── 721c77e88f4f715cd0a487203c34dd7abc276ef5.nq.gz
│   ├── 769d1389c6696372ab19dc35e7c86106f65a37e1.nq.gz
│   ├── 7896417d0a254bd5d573349778fd80d83bf91d6f.nq.gz
│   ├── 7fa6c30812897f48d3a1d43939b19eb17f7cbce3.nq.gz
│   ├── 89c2725b70f1882be97f5214fafe22d27a0ec01e.nq.gz
│   ├── 8b06db058d454f4c03a52cbe6a77db478ecfc8cd.nq.gz
│   ├── 8bb02fe9e23383dcbc618228b1f0f0b512d0d099.nq.gz
│   ├── 8f89a7a06edf224225502ed9a48a566596342f57.nq.gz
│   ├── 917840a1f748a7daf7f44699e38e033ad9ec1fd3.nq.gz
│   ├── 9d7712e2b17a2844a43a3a6d2a66a1fd9c9e6b66.nq.gz
│   ├── 9da19eacad3b03bb08bbddbbf4ac48dd78b3d838.nq.gz
│   ├── 9fa5f8ca49302e6812a458ae6a3eac3a103e6aee.nq.gz
│   ├── a1a70ee525cda12223def074fbdfd14c10486d48.nq.gz
│   ├── a28140cfdb3ff9b7a11a9497b84546d615db2afa.nq.gz
│   ├── a4222c2de01db09241c531a7bbe2d830d138b4e2.nq.gz
│   ├── aaebf06dbdc9cae4e798dab93e0a72e345fa7e8e.nq.gz
│   ├── ac485d7c3e627d997f59da65ac961160079a0143.nq.gz
│   ├── ade6bc9875ff16660c1e3944875abe6836b09d55.nq.gz
│   ├── b1886adb46c085de842f1283c1a3c25151bfc988.nq.gz
│   ├── b608e41ccb656d249dcfa8b8529c5445215a1049.nq.gz
│   ├── b7042adcdad5fe3ec3db2c8c53170d1055b1a94b.nq.gz
│   ├── b8e876c10a177a71b6f14593095cf4118f04997b.nq.gz
│   ├── bc561210393320bd5fb3e220c893572313d26020.nq.gz
│   ├── c0307a259db86d2e58bde37d8838bdc3e4b6dd4d.nq.gz
│   ├── c31314fb481b65b3c1c88b26e7a7d51e97fde777.nq.gz
│   ├── c41920416d9a27e979f42604a327f33af9506c3c.nq.gz
│   ├── c614bbeea93737be5b3752a42a4744b4d033e8c0.nq.gz
│   ├── cc2b5a1462c1d541beda604c26228cb31d4adcef.nq.gz
│   ├── ce44a4f0b5e2c47b9d37c252dd0dffce9e459b16.nq.gz
│   ├── d47bf79864fbd29cb445f577b63a59f275e2999c.nq.gz
│   ├── d5189d58701655bff99706cfcbbe170a493855c9.nq.gz
│   ├── d6562e87915fd357e94f37641b4a75864a4c2839.nq.gz
│   ├── d714bd1bf032052095bce8a7d73fca51ab1c9e4c.nq.gz
│   ├── d82b5613c97409593e436a825d4e22aa215e9f7f.nq.gz
│   ├── eb19361b5711e614b090eac2f1b51309da2ec1e4.nq.gz
│   ├── f112e4baadddac5747f2281994e494f94449a474.nq.gz
│   ├── f29e5f0d1f796c3a3e976739ef18ee8bcaec330c.nq.gz
│   ├── f2e259c7c9390ff69a6bbe1e0907e6dc366848e7.nq.gz
│   ├── f3c28516fb38e64d88cfcf5fb1791175df078f2f.nq.gz
│   ├── f9b0d7c5ea15f194be85eb6ee8e6721a87ff4644.nq.gz
│   ├── fae5778b82e5c5b3460b70f741c3233a81fef307.nq.gz
│   ├── fdfe90b6c4ddf4b050187048e8f823c83f16f649.nq.gz
│   └── ff60c41a19ac3ddea97283151589d76c48e1e5b9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 325477dab71201da9f437d66d00063a310b77eb1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 89 files
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

[MaximeBeasse/KeyDecoder](https://github.com/MaximeBeasse/KeyDecoder)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
