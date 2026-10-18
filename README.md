# Repolex Knowledge Graph of python-validators/validators

RDF knowledge graph data for [python-validators/validators](https://github.com/python-validators/validators), parsed by [repolex](https://repolex.ai).

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
rlex download python-validators/validators
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6ffd8625ee4272dade063653bff615014bdc4734
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6ffd8625ee4272dade063653bff615014bdc4734
│           └── chunk-001.nq.gz
├── blob
│   ├── 0027e271b4bc1f227e8ed76ab404b2319656a54a.nq.gz
│   ├── 00e543b23085e8b4f20605befbb99a9cea1c3d93.nq.gz
│   ├── 0173d9e802859eee2cf2edc13e846fb081a8c517.nq.gz
│   ├── 038b44ba3d10d15fdb40b2dce48bc627cf1c834e.nq.gz
│   ├── 052281acca1fee46a4ed366e21fe639606e58cc7.nq.gz
│   ├── 0749e60e7cb36da25c3f3d52f0ac86f30a9fe54b.nq.gz
│   ├── 0a5726f7f8c23b6fb0d4ae2f83b097d46d65b2aa.nq.gz
│   ├── 0df5fce0c1452d9ba25f5fab1a604978b6334ab6.nq.gz
│   ├── 12a44a911c4e629abe823c12658f2b6fbeed5ac8.nq.gz
│   ├── 12fb281bd63d8e30f14df2259443353c101d4178.nq.gz
│   ├── 13aa96a5cf7162843f37784b0cdffbe273d97960.nq.gz
│   ├── 1485d2659e63fd079f4cd71113ee3f0f4682ed2d.nq.gz
│   ├── 1927ca97157a1adb29dcd3723ae0d9cc21835a45.nq.gz
│   ├── 1aa6736eccf3455474fbb4bd5ab453eb9a04b85f.nq.gz
│   ├── 1ac24a0cf5d584b3e3d3cadea8ed168c9ad0238a.nq.gz
│   ├── 1c6c28f4a63fdd1b3d1ffb898ddfe6e905dc7438.nq.gz
│   ├── 1ce4a26204bdff76174f44dfca2f89729075d6bc.nq.gz
│   ├── 1eb7ea62a50ff9e3ed0334100ed2f4765b92e282.nq.gz
│   ├── 1f1110879200ae90801698fd095f3bd0b375319f.nq.gz
│   ├── 1fe24686eaf5ff04a6993967b03558d818dc9e47.nq.gz
│   ├── 214aa9bc0a2c75c190f44b4ff7933ae72a217f32.nq.gz
│   ├── 22f4c4b010ba46b7a8ae8d20b5bf9436ee30bd3a.nq.gz
│   ├── 2554c933ae8a964e8df73f5b93ffc2457a0f4459.nq.gz
│   ├── 25e53bb3d17214329b8c169bb474c68ba41f35c0.nq.gz
│   ├── 2649584291e30adc21d0f8126051c3525fd134c7.nq.gz
│   ├── 26a8221db8a396cec4d2d16062a748e9657513b5.nq.gz
│   ├── 28d3c8579c43c923efa3364bd5a295a69bf0b776.nq.gz
│   ├── 29a58e2d935e804c3a64afca019215272cbad2c8.nq.gz
│   ├── 2a613d729ac318862d147f8393eca8a8c9e42477.nq.gz
│   ├── 2d63d977d4a36f3b7614332b9adaaa634ab4830a.nq.gz
│   ├── 2fb99eee9e331ca53c08e1129b2dac3130d0e07b.nq.gz
│   ├── 30c1588acba4854bcbe26d24c98d5e8ef1c4efe6.nq.gz
│   ├── 329a20e046ba49cce04f6f3e951a571528e6cddb.nq.gz
│   ├── 32bb24529f92346af26219baed295b7488b77534.nq.gz
│   ├── 33f17f19698fa039e65598268d7b458fe07fc480.nq.gz
│   ├── 36aae6d15908493da41351f87f131fac40f10992.nq.gz
│   ├── 39c24ec4f6a12caa0f7dfcbe8bf76fbcec9eea55.nq.gz
│   ├── 3b90a417e17ad2a52ec72adb94a2b24092b2662d.nq.gz
│   ├── 3d4b1ba31dac627f730b7385e53ad4b6663a27ca.nq.gz
│   ├── 3ed9feb9c318c19a1633198dcf7c4aa49f54eae5.nq.gz
│   ├── 3faa638b4c2f890da9dc8db38098939ac130faec.nq.gz
│   ├── 412d20929dbcf37b68a44a52702c2c4d04b1d0d4.nq.gz
│   ├── 43092d5afcba7269b15601010342a8f654361bd0.nq.gz
│   ├── 456027864eca477f114199dbe1b395a8df63f9af.nq.gz
│   ├── 45b598137beee2f3170f85aba3545d1384e95465.nq.gz
│   ├── 46cc5946f572c84d44790410077582a752f418d6.nq.gz
│   ├── 484a9dc068bba9e33a67548c355eac99eda13115.nq.gz
│   ├── 4df4ecaeb6f2fb04be06e4e408241d1c49c81a44.nq.gz
│   ├── 4feb2476a6b34f92e4a29b93183648d3d565a028.nq.gz
│   ├── 5b1ce01302fe8a367efd4c43ac9e8aefe50a3b90.nq.gz
│   ├── 61376ea6fd10c12f869d3bdf5b0f84532189e2ed.nq.gz
│   ├── 643fe7c354788a10439d2aff366cba51fe70160c.nq.gz
│   ├── 64f479cf41dda035d1bd3c52f66d59f7e8447cd2.nq.gz
│   ├── 675020002f865dc3b7f672be73c3c223f3afe8bc.nq.gz
│   ├── 68bb0d94386ffea955bab2c51c003594fa303fce.nq.gz
│   ├── 6e78260ea3002b80628f75d7718b334ddc32a2fe.nq.gz
│   ├── 6e9561c541cedf8203618de62b7d4331ad691ec0.nq.gz
│   ├── 6f86a75527eb25db9f58397289fa6340ba09958c.nq.gz
│   ├── 71b6c0413c1e65cc6f1cb5a1dddbb6f36b8fa8e1.nq.gz
│   ├── 7523a3939e76badb9078dfca907ee584adbe0232.nq.gz
│   ├── 771df7c7b1af8558f96ff5228b9c964956b50e7c.nq.gz
│   ├── 77644245e4b442849a997b5ffacb3c672700b5f1.nq.gz
│   ├── 79d8355ccb6491d88fd3cb81a2bd31d5e67e2d0e.nq.gz
│   ├── 7afc463039621c57562113b08f0e0333914acb16.nq.gz
│   ├── 8216bbcf2b6a20a0c3a3428d12c8a4616338c75d.nq.gz
│   ├── 82eeca81557ad6a73654e1a79f5d536eb6dad977.nq.gz
│   ├── 85b474fb3cd4efa9672a9b45ee06fc1f522949d8.nq.gz
│   ├── 86723965bb89b0994f59f755b5a0da4b99b6933f.nq.gz
│   ├── 8ab882dffc786366a053bec1c257121f0eb41f63.nq.gz
│   ├── 8daeb0339be12bb480beb754568959eee6b6707b.nq.gz
│   ├── 8e1589a7c53a2d3e2b1c5dc04b5708476650aab8.nq.gz
│   ├── 8e61dbc4cc0a1b5bcab1082069241c0729710951.nq.gz
│   ├── 94a42c625998f16cbaeca005e831bd32f800ef51.nq.gz
│   ├── 96647eab80f3f5b2712fcb917b941017fa0ccbfd.nq.gz
│   ├── 96c4063b8db557b9b2ee4c1760076c927c1e14ef.nq.gz
│   ├── 96fca00f399a178cac5725e014a962ab80731906.nq.gz
│   ├── 971e1b3da5f83d01115cf343760dd67998e1b35e.nq.gz
│   ├── 9728a8feb9a3f43a62fda5882b6968d769e6503d.nq.gz
│   ├── 990ef8ee17904bf96804d4024061cca2ec52d0a1.nq.gz
│   ├── 9a84254f8cb183382b88abde10a64c6c3f35f7ef.nq.gz
│   ├── 9ad7c2c461e080fd19b3a29e2edf98be33760419.nq.gz
│   ├── 9b19bf654de9ce8288f21eaa548b968b1c5b0f76.nq.gz
│   ├── a159e92a0ed9fa5de3b7f8e48fbf3e6db22039cd.nq.gz
│   ├── a23a071d2290189d5f02551c5066a53af34ae742.nq.gz
│   ├── a2f052df8627f5856f5b64cfdf4b0e3b763b7a4e.nq.gz
│   ├── a342749456e822c76f042b5417048ab3fca063d2.nq.gz
│   ├── b15c97c8d6b4fa0a4e12883ba4d184b630b180e9.nq.gz
│   ├── b37f164ca8cd3fc0f1a5826a417778c7f39d48d8.nq.gz
│   ├── b4f40d2966509676566516dfb8e2bcbdc17bfd2d.nq.gz
│   ├── bc98767c11f624596c6b8379cf84a75b49a197c2.nq.gz
│   ├── bd5035ad0d16349f3ce5f3a1bc689dd37811b32e.nq.gz
│   ├── bdb7155179904ece50ee1c246bd525105b66b04f.nq.gz
│   ├── be98e8e90d9d40fb3efad29fe969690d8e83c8f5.nq.gz
│   ├── c0271e65fff8923aac1d1f04aabf10ad2fc91156.nq.gz
│   ├── c063dfb6fc7575f456b398346d53f99337bbc1c6.nq.gz
│   ├── c16d6f4a944f83f2c8f49b68b6cae8b36e501f7c.nq.gz
│   ├── c17f5d9591406672d2a05b3f480d81a996a6816f.nq.gz
│   ├── c4ec2cea3d12776fc8ce9da1650323ca4f666710.nq.gz
│   ├── c7406d596383690e83b366720f14243a8e0f8f27.nq.gz
│   ├── c9cd1dc1c1e1d5a1bb83b8a5b079185d40de67ff.nq.gz
│   ├── ca6b1ba0d7ed7f591839988b28bb937154bca676.nq.gz
│   ├── cabefc2002dbdb0200e59011ce1987c79b800e9b.nq.gz
│   ├── cdf4bd401663f4b4afd525467f45d3d9fa455576.nq.gz
│   ├── ce70dee12cdd145370b82d42e0c2ab4f90428b7e.nq.gz
│   ├── d091a2acd4e12d85d5bd04fa2d936f8d999dc76f.nq.gz
│   ├── d197caeb23cbaf2b0c5ae5714969317c0e03e5d0.nq.gz
│   ├── d391df7361a358108875277a997e00c18d5e788e.nq.gz
│   ├── d4b0a9606312b25fc90318065723ce2455de9e38.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d606ad7928c8e461761f3f17b188577ec29284c3.nq.gz
│   ├── dbe2fc60917b350a9b088c8b70d16e32675592a9.nq.gz
│   ├── de2fd313df03a4b50b446ce096a002ffff30e86a.nq.gz
│   ├── e49091d449d267fa88e38073d7061ba6a199a315.nq.gz
│   ├── e5fcaeba39f4a646f7a6c23255997212863e2142.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7c29332d85b4e0a9c5fe29dea2569b77237703a.nq.gz
│   ├── e8c15e5b7dab41e2f94d243bc5670dbfe773b396.nq.gz
│   ├── ed0b99ef0be7fc2f0c7600550265d852c3bca70e.nq.gz
│   ├── ed4a0c4cbd54eeb9afa4ab12bd83e1f76c9f9573.nq.gz
│   ├── ed6fd7d40e6ca1e9994329a1f9db8506a86409c0.nq.gz
│   ├── eef817805e856fa5e0af4c159b0ec8de43e92546.nq.gz
│   ├── efd429c7f3cc08927669c4062b3b61c49d14716e.nq.gz
│   ├── f043aad02f702c31f7109f01ba64804a47f8c189.nq.gz
│   ├── f220c77f3c266f5a35980ebfd1b8b3bdde6a2c1a.nq.gz
│   ├── f43d946adabad02735007d2e08739e5c838bbe2a.nq.gz
│   ├── f8d14e663fd5fdde7e7d74f421413a339d8a3e4c.nq.gz
│   ├── fad238e21b5bf2f09d21931d1143e9634ce4f80a.nq.gz
│   ├── fda93f98458dfa8cfeb65f080b0716b6fec29692.nq.gz
│   ├── fed2739672ced181d1c96555f1d076b30639510c.nq.gz
│   └── ff39cd73840bac35382f682ec012dfa0f608b144.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6ffd8625ee4272dade063653bff615014bdc4734.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 138 files
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

[python-validators/validators](https://github.com/python-validators/validators)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
