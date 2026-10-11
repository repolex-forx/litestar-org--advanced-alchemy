# Repolex Knowledge Graph of litestar-org/advanced-alchemy

RDF knowledge graph data for [litestar-org/advanced-alchemy](https://github.com/litestar-org/advanced-alchemy), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/advanced-alchemy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e051a5de1a008b70f2d67b416e236a8c59e69433
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e051a5de1a008b70f2d67b416e236a8c59e69433
│           └── chunk-001.nq.gz
└── blob
    ├── 00bd739528bef575a9a0da40dd7e62230ad5a8ff.nq.gz
    ├── 0191501cd3391ace6226b74277b223b5df5fa64d.nq.gz
    ├── 02026ba233f43a542104d9f9ea46d9dcee4545ef.nq.gz
    ├── 022da1131cfcde22b9d9af9ac0bbca226d4c78a9.nq.gz
    ├── 022e55b1fd01a13796d9732b9233b2d5cc38cf64.nq.gz
    ├── 032e7b5a3d9a750ac649e13539aa97aacb5415d7.nq.gz
    ├── 0395282f83e1e9bdb41f3d22743a4b859880699a.nq.gz
    ├── 03a3269645d4fa7445834f7014db0bc65b17995e.nq.gz
    ├── 046d64b2932f658c4d1b3e5a44f5c1cbf05171e8.nq.gz
    ├── 056ae0b06bc4d875cf18965f406568631db6ce16.nq.gz
    ├── 09533f683a0cbb8e1e68de757af1f67434bab783.nq.gz
    ├── 09aac0f8f55101a2fbb7768a50bb6fb631c6643d.nq.gz
    ├── 0a2f4eb4063af6c120d6735c1e1e071ac73d55f5.nq.gz
    ├── 0a9b048145cb9fcef700c202e4bb9fabf845341e.nq.gz
    ├── 0ad46ba330ac83f1505f76b3cbcdd67fe9976c7e.nq.gz
    ├── 0ae68295497418b3377eb7fc785142f7f8d0e615.nq.gz
    ├── 0af03364ede358b0a8a509f135f2320338934566.nq.gz
    ├── 0c3e402926ca867b57e7d6d3d677b5d81d4247bc.nq.gz
    ├── 0c6d84e8134874b5104bb7f42cefe2d651a904c6.nq.gz
    ├── 0e7be0638f89a816bc866e07fd9fb693cb9ea702.nq.gz
    ├── 0f41607ef041364a6574e68bff8fd20cd0ac17fb.nq.gz
    ├── 0f9221f6f5ec45534279d4d4a5ee24c565e5355a.nq.gz
    ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
    ├── 124294ea579cdf0d4970a9dad7846ed1b81192bf.nq.gz
    ├── 129fd5d535623e8bbd7ae3c40a5cf837b30ad6fa.nq.gz
    ├── 13b37be5bdbb39d662b10b35fbc568ea62d2582c.nq.gz
    ├── 14b5bcb98cc5dda3c67bf2f033f341db4e5b8f0a.nq.gz
    ├── 14dc9bd29083201fd864b31e25c4a3e2b766e7af.nq.gz
    ├── 155789d560fb8359a154a7fe57d4a94675370d8c.nq.gz
    ├── 15bc6c43ed00672377ef2eeef1ddeb54f3816258.nq.gz
    ├── 15fdc730a4807a82571805cb534c82baadaff3a2.nq.gz
    ├── 1651f22f889f0c2ed75bdc666ea519f2398bb017.nq.gz
    ├── 16b8d622a1141db66c8a10263f7248cd8c675d38.nq.gz
    ├── 16df8798591024cb14eea8db482a2c26a0de9d86.nq.gz
    ├── 172e417a7740dbc24debebac3877efa0c36d09bf.nq.gz
    ├── 17ea96bdfccc606955e898963b2867f336be2dec.nq.gz
    ├── 180ae3047dca6f9976e4fd1bbc70a74684195c3c.nq.gz
    ├── 19dc1eccebaec8a6748501fa907d0771cc5651fe.nq.gz
    ├── 1abaacaa24e4bdf4398b1101d811c6dc973c8ca7.nq.gz
    ├── 1d1dab25fa61d1ebd0666760901d8f19543f1d25.nq.gz
    ├── 201da8be9c9457fabc34e987b679d226c239358c.nq.gz
    ├── 201dd1c36d001d79ac8eb5bbd4c0e2422edd608e.nq.gz
    ├── 21118d9addefbbbf51c6cb719fc67f251e48a5ca.nq.gz
    ├── 21ce07cc6a375a9e4c2cced935f82bfdf944baa2.nq.gz
    ├── 21f0b03b8833412068717b8df92ba7b61b8c9c77.nq.gz
    ├── 2452b88f987af2694f0b8b7937ccd4c27a962f05.nq.gz
    ├── 2513d306f5c7c159429695a618dbeb1f6aefd9b0.nq.gz
    ├── 2612281cc8895557421b63d820ff908df6ff685d.nq.gz
    ├── 264c905601f858cf6025798a69ec2c3dd7a8567e.nq.gz
    ├── 27345630660864d56f704c0f47fad7aa15088c5a.nq.gz
    ├── 283a9fea53d4317d44e41aac1d49587202b41941.nq.gz
    ├── 28538a5824aa8f44de188e4e095e98ee7cc7587c.nq.gz
    ├── 28959cc84f7c1498cec4bebee5f17982fe4c5a39.nq.gz
    ├── 29a2d1e2c6833ff6dc0a38ebaa45e28a1c718997.nq.gz
    ├── 2c879bc5c98bd49429dc71547971b9ae27c67ecf.nq.gz
    ├── 2cd6d555c6c1425ea0fe814ed76d955de63de331.nq.gz
    ├── 2d2a9935aa7110a615e3d4ed1a1501fc4317ee99.nq.gz
    ├── 2de4179b95aaf77fa2f62b186e576edc37f06346.nq.gz
    ├── 2f3ea912f3cfdc10e6e36ec1f926d6d49ea34ad3.nq.gz
    ├── 2f6d5c30abf5c4b3a806c03b4a1b1d6c89f4c65b.nq.gz
    ├── 2f72bbfb6d935973591b6f14e8c8fe545d3539a5.nq.gz
    ├── 2f8e1d6870c063e965c70bb1d7ef41fc111904dc.nq.gz
    ├── 30467778f956ad5530aa0521ae2d3f676823b8a7.nq.gz
    ├── 306915f690020321181b841300af86d3489d8c0d.nq.gz
    ├── 3104c1b11d3dbdadb0c472850e58cc443830299c.nq.gz
    ├── 319fe73f5538317ffd0329ff0db343ebbf3e5cb6.nq.gz
    ├── 322be17a1ae652886cb9ca9c825ea21a61e3085d.nq.gz
    ├── 32c2d23fa933fc9ba9b792ec8ad52c124df77f05.nq.gz
    ├── 32f52b023ec5c2e7368419f5218e8b54c2226583.nq.gz
    ├── 32fefe3d6e0b77669b6d12b6794af64e7d9c259b.nq.gz
    ├── 33650ec93d42957413f9d7ae0d58d467250fb812.nq.gz
    ├── 344f03690c6cce7fc4f38143e24c453df97368da.nq.gz
    ├── 355305f42e360e91e84b0fde6c6539a7d879e5a6.nq.gz
    ├── 36041a188fa18b3d362a4478e57529750d7e8a29.nq.gz
    ├── 360ff6ce0fd9983caee79e246fd6943593585196.nq.gz
    ├── 37e659ca7ebf92ab96c2f06db38348982d67a51c.nq.gz
    ├── 381eca79e0e24c5c24057c9353b8693c977766f5.nq.gz
    ├── 3836e9990d578ad1c3c26bc9e71c8e4af057f8f2.nq.gz
    ├── 3901f4472ce0c0d63ea96f07a0aee2928f139df4.nq.gz
    ├── 3c01cbeec60c56db95b110f1e1a19f37cc25293a.nq.gz
    ├── 3c222b5c7e4a41e918edd5ea797b2efb2d694299.nq.gz
    ├── 3d140c411e002bd0b6f0469eb485870dbe5d5f9a.nq.gz
    ├── 3dbc8a50ddcdbf5c68211890990c7b3e441f6998.nq.gz
    ├── 3deba8ce051df7c1822f14037ab39962726e7f6e.nq.gz
    ├── 3df0a896b761fb71abcda6b0a82f22a7708eaf92.nq.gz
    ├── 3e34fc1b7090cc2624338f1b6f64ea22080da083.nq.gz
    ├── 3e94781b8a6326c7a8fddb751aed4da860cc2af4.nq.gz
    ├── 406f3885afc67308dcf58a0343ad44d1c321e10c.nq.gz
    ├── 40ec7dfbf08376b6f10e8d62d71be6c0961fbe77.nq.gz
    ├── 41107ac9287b508ff5591eb456485f9a44d44364.nq.gz
    ├── 442a29056b75953b43e1122d8c83e326305a32a2.nq.gz
    ├── 4584e5bc8de9a79e20e9b4c2720cbb719c74df70.nq.gz
    ├── 45edd806f1c5d5ac4e79a2787de6085f49a39a4c.nq.gz
    ├── 46c2fc658b79787542f112b3c8889f41bcb6b458.nq.gz
    ├── 46f087d2e4ed96d679b1a5250fd0fa47f05b7265.nq.gz
    ├── 4759b2ad6b501ff9b764893da31402cf969ead60.nq.gz
    ├── 489c49485d82e69b92614787454896b589988ee7.nq.gz
    ├── 49bc2b8b6501ee5fe1cb496f159c18ceafc61ef6.nq.gz
    ├── 4a62970a5e549530ea92ac6cc13c68ec15046512.nq.gz
    ├── 4ae6b3744f935532038a3b9a8b17bacad4676598.nq.gz
    ├── 4b34e3efe36f8655086246dbe6dbe1e6f8d53f02.nq.gz
    ├── 4c0305ad8af3d7a06fbb01a0c41f93c29dfe7042.nq.gz
    ├── 4c56f7d0e263b9ecdf02f5b8921cb7dac9b6ef2b.nq.gz
    ├── 4d68332de1f0f608f8e66c56e9dba8060b6f3c72.nq.gz
    ├── 4e28a93121826a1ec7236049d1a4b90d028e6345.nq.gz
    ├── 4e996dae5b85f572230ada0ccfd96da158e39110.nq.gz
    ├── 4f17f48708f60c658ac1768c6e258aeb6f0bc956.nq.gz
    ├── 4fc0823e1c62fd660341c91fb28a1580c3f9c2e8.nq.gz
    ├── 501b0f26c79e2de20e48182a143b1c3b63b7877c.nq.gz
    ├── 50f00f1062a97e4c82a3950a9e9837fe8382d711.nq.gz
    ├── 54b2483596277cf07385d12af763f16f2572ea15.nq.gz
    ├── 565ab816da2c9e22b43071f76f742cda1d54676e.nq.gz
    ├── 56cf9a7b1380a650e24041b2082b86e3373a9ba6.nq.gz
    ├── 586cbc25096495940eec5638c455fc438039b4ee.nq.gz
    ├── 58d6b73647b70476fbf0635f42de510c6269a73a.nq.gz
    ├── 59625c39490087ccb73a759385f34f75b4bbe060.nq.gz
    ├── 5a8808c58fdb6892f0463a9b16dbb691f878bcb9.nq.gz
    ├── 5c50c749e5310f6405d7125a4c6e139d290f90a2.nq.gz
    ├── 5c62320dc8bb86c1523ee2825ef84078384b3869.nq.gz
    ├── 5cbce249106b0ada997f3ca24825032e24ce5c8e.nq.gz
    ├── 5dd2a36c74270e665bb8a011e788815e092e770b.nq.gz
    ├── 5dd64956f4483973837c885bdcb0e0b5da4893d2.nq.gz
    ├── 5ef476b8a392043e7bd66324b245e6e34608f48a.nq.gz
    ├── 5f400aead94c73b090194c40d4fe475413e88625.nq.gz
    ├── 602524ce7b1de70aa6c37ac126de6625e5bd62e8.nq.gz
    ├── 6075e3c0eb551d5b474ac93406b12090b9bf8f84.nq.gz
    ├── 60ba20c43955d00eaefb3522582bb90f8840d288.nq.gz
    ├── 60d321fa5c731ecd062473c64ae3198ba2b38570.nq.gz
    ├── 60ea73a9fa2a491a81d5a8d0955e06520a332a83.nq.gz
    ├── 61015d27d9244031154ada42b7efc29a07d3db7c.nq.gz
    ├── 6152bc6e2a5481265d109d8be24b8883bb96071b.nq.gz
    ├── 61899cd410631f603beae63094bdb84cad872dcb.nq.gz
    ├── 63f93a3e4a0db2f6cc051ec64d8c63482697b47a.nq.gz
    ├── 64d223e81f55484c4511c4182c9ab2d308ff66a6.nq.gz
    ├── 65f64dc0c397d3cf24c7c50414b6b2587daaab8d.nq.gz
    ├── 665b04cdb23305008aafc80d5b2eafb31d49775b.nq.gz
    ├── 6684b3f1d05d9eec3d270a9da4e5a5e5e82baacf.nq.gz
    ├── 679e918876d745aa8a23ad02951b9881b811c424.nq.gz
    ├── 69247975b8de20a5a6ef6bb1e356267c04e0fe07.nq.gz
    ├── 695aa965d18876acfd4cca2513edc03c82d3d001.nq.gz
    ├── 697db1fc7a6197dc6f52af488767a83e6e3047f1.nq.gz
    ├── 6a1923203fc1a0787fc67f5959d1b01075187d16.nq.gz
    ├── 6b82a27abf8532ee4cf2f4a37a7d7818bb3c4eae.nq.gz
    ├── 6bf306215d8d87d83d08c88b286c83bd51e3472b.nq.gz
    ├── 6c45112779e64f9ac4599b7810d8b464a630b21a.nq.gz
    ├── 6c4f6fa92dd5845b3ee2d543667ce002601d5df7.nq.gz
    ├── 6c621196e8c375bdf33a8e89add8c6e9f6149e0d.nq.gz
    ├── 6cc3af9efb5cdb0b93fd823146ada95f253af2bc.nq.gz
    ├── 6d0ac73a841b7925e29c3f7377d53105a87e3899.nq.gz
    ├── 6da757051d2296dad4c940659ce580ea014cfb18.nq.gz
    ├── 6e53448144a587ec3804a253511ca6090f01cc17.nq.gz
    ├── 6f3b3582aae92209ba8affbe3156cd2c620a55c5.nq.gz
    ├── 6f59c84b581184bd0b3709c5c201d17f6ecf449f.nq.gz
    ├── 7029fd314d68464d4875d49550f9dcf5e8d6a019.nq.gz
    ├── 706d073ca5f70a04f837864f43e16277b8dfd156.nq.gz
    ├── 709c6ba27d300c6a46608cbf30cd35cedb8134ae.nq.gz
    ├── 7199e854da2711f3f5de5075f421b3d3316392e9.nq.gz
    ├── 72cc98902c96607c328e86a1cd21ae36fb9ce7bd.nq.gz
    ├── 73140be46b453257078a69c9f8fce1555f3a27c4.nq.gz
    ├── 73986942f488bae8c27d8399b93c06fcb4816916.nq.gz
    ├── 739886c4bd68cfdcc185b93d7bc3b6aa4c8af351.nq.gz
    ├── 740ac5ec4f57377991760c24b74d6cac9bb2cd76.nq.gz
    ├── 74c3be32e2124d462f22a5a6e83523d9eacf963e.nq.gz
    ├── 75019a52257a18d4df35546d0ccfb816be8cfbaa.nq.gz
    ├── 751d361abe650fef10cc5a3c12865d596a5b8c3a.nq.gz
    ├── 7707228bfc9b4ea516a79e259da0d1bbbf64968e.nq.gz
    ├── 7816c42c385324907b806e83d0d4c0acc920d082.nq.gz
    ├── 783b113676d6c1c1a82c028f2f6190d0d0dcf9b5.nq.gz
    ├── 7843ec8c12f8bdf3243e193d2bcba65bc245190d.nq.gz
    ├── 7850afcbe447b1e01f5de987d73438f1a6b7eaa0.nq.gz
    ├── 79336c1acaee77e54a681e5fd6d29348f57e6f26.nq.gz
    ├── 79c466f088683ba8aa46dda1e21de75d2fa0c359.nq.gz
    ├── 7b5afd30ba7680e65e181f63fae1383c49067827.nq.gz
    ├── 7bec51c06b979df8440e34c6b6dc6d15674b466e.nq.gz
    ├── 7c83725fc803ab33e7eb3d08026d21a8409e814c.nq.gz
    ├── 7cf5a0bdddb493cca437fe3c668b171dc7839b20.nq.gz
    ├── 7e94e6c138342862458740749d45c2cc51a45d37.nq.gz
    ├── 80581e02104f5eeca077015762f89ab65e6f3d11.nq.gz
    ├── 8072fe2f3a399daa39a089e31f69017cd74f294a.nq.gz
    ├── 8146d0daeceb245daf90fee17c64fe6ae4a92681.nq.gz
    ├── 816fa6881adf1e77ad2eb94e5bbd25cb048d7eda.nq.gz
    ├── 85f6b863097bc945a3d9215ab66800fd86a53484.nq.gz
    ├── 8636aaf2c98ed44880c8b82ee26a612eb104c572.nq.gz
    ├── 88732a9d94c189d4ecf6b4cdfe1b4f2b254eedd7.nq.gz
    ├── 88b308cb89c44d4209f1633c712418bead160b9f.nq.gz
    ├── 8929163f3e1b39ff2395e18d7b36e76fb7b764c9.nq.gz
    ├── 8a1f21ca50b417dbb2ef632308a8c11e85c5b5ec.nq.gz
    ├── 8ab2ee615f48136699f90d93d59083c191d38d11.nq.gz
    ├── 8ac2cf8ea220406caa4732905847427dd53d70d8.nq.gz
    ├── 8ade399537f64dfe62df3975212395b7bf853551.nq.gz
    ├── 8b6f60d6313d606e6bb24c37446850249c14a3e9.nq.gz
    ├── 8eb60806a4dccb86c68dbb94efa47c8e6d4afd17.nq.gz
    ├── 8ecbf53e440931edbb2ea5700a2d8996aa76c58b.nq.gz
    ├── 91437edaab8959be1027e7b9947a87d97cd18e28.nq.gz
    ├── 91ae196b708592415246208fa4b5038f10c38f43.nq.gz
    ├── 9201ef4c614eadac037863fc018f6fb3c7b802e6.nq.gz
    ├── 9259190e87214b387f75ea94a69857fe608c51d0.nq.gz
    └── 92dccb8d8d0ea20631412898eb936d62efd826fc.nq.gz

7 directories, 200 files
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

[litestar-org/advanced-alchemy](https://github.com/litestar-org/advanced-alchemy)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
