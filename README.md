# Repolex Knowledge Graph of deepmind/optax

RDF knowledge graph data for [deepmind/optax](https://github.com/deepmind/optax), parsed by [repolex](https://repolex.ai).

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
rlex download deepmind/optax
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8589d974e565fbf1bfa1cdf8d94f5ecdf8ebe93c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8589d974e565fbf1bfa1cdf8d94f5ecdf8ebe93c
│           └── chunk-001.nq.gz
└── blob
    ├── 00e7758322a2327b2904bd7d3612078fe9cf2875.nq.gz
    ├── 012dc44862be8bc0b4bc0fb2944c56505ff5c20f.nq.gz
    ├── 0153d35bf1a2e8b5a8770252cda7cdec474ef331.nq.gz
    ├── 070ad2e003174aee1fc3eb4647853a7650ce56b3.nq.gz
    ├── 09c84bca4d332d8de507bc307f72025906189d21.nq.gz
    ├── 0a87b87225846838de5cdc2b4afde4fcf790f655.nq.gz
    ├── 0adfeaa10e5fc95a56827f093b2e7b85d72e69dc.nq.gz
    ├── 0bc21f7949b7f5d433b035d81a90afa31eb58692.nq.gz
    ├── 0ceec03c1a1930def06e9a7189c367d496e82875.nq.gz
    ├── 0d9645bfbd08284e834eab397ece09f233574676.nq.gz
    ├── 1182820affab5544424ac438e2953c266dff023b.nq.gz
    ├── 12877a196ae10316367e87ed373e6e9b3fcf7f81.nq.gz
    ├── 12aabb6271db1e766c6fe3e90f655ea27da26011.nq.gz
    ├── 132298043b2880d8fb904cc29c0a3ce18f41a97f.nq.gz
    ├── 1480d8a00e84c72c7325583254a8f05131c41aca.nq.gz
    ├── 15834ce0d1937f450ecec19f7e438bcb144c95b6.nq.gz
    ├── 166ed95a64d7cf685afafaf2dcc1799345c5236b.nq.gz
    ├── 18eed54866a23c52656e5bd996dcde2f61451e70.nq.gz
    ├── 1b24f88e839cf60244d832252ee07548e5b4fedf.nq.gz
    ├── 1c462c58dface0e13c37759f0c8116fda33991e5.nq.gz
    ├── 1ceed50acde6edb016bc4bd7b00cc6bf6e7f489b.nq.gz
    ├── 1e6de5f245df20dcfe79359bb41cdfa3a08970f2.nq.gz
    ├── 1ebc2580824128b3436cfbca34276248c8496871.nq.gz
    ├── 1ffab6a5efe94da33c4cdeb344485afeeb4ba26b.nq.gz
    ├── 21e00b6f49d6c24ab5526e17155b2c90cbf6cfd8.nq.gz
    ├── 245d9d58ea79e153ecc966d875257cf9c22500de.nq.gz
    ├── 2708f6d55c0a54bf39699950b6f440cc66fd5466.nq.gz
    ├── 296809cb893c6c21e68024358089c52d84f70b2d.nq.gz
    ├── 29eeced718db2245363e4245e568c95a3f05c643.nq.gz
    ├── 2e225661b8151e69902dfa6b7b8edba5a7c21ce6.nq.gz
    ├── 301636abd28f5f8a7e60ed10a66850a6d5fd0fd0.nq.gz
    ├── 3087beb07046ffc77fe8d437034504225284b71f.nq.gz
    ├── 31a642704529e5e85e54e1bb028a41389f57d135.nq.gz
    ├── 329607112a52ca84932b4384140bec054f4eea14.nq.gz
    ├── 3304de430e40b36b3f756c7f7aa55234b7d6f4a9.nq.gz
    ├── 343c6b0f50ddb43e6ad518c025ec23a8c00a319f.nq.gz
    ├── 359327b5fe8e282817e6ad4af8130e2d6bfef097.nq.gz
    ├── 35c032ef0741e8d827a4cca537c488c6c8f524fa.nq.gz
    ├── 36c878f1edcd08db6238c56afb1eae01e7115df3.nq.gz
    ├── 37b50ec5e74f04f2b900b2ada18cc49f42b88b04.nq.gz
    ├── 39e0f9880b3ccff07b5e389bc7d232892655828a.nq.gz
    ├── 3bb23203787ca6d51c6739b367ec67dfeb968c7c.nq.gz
    ├── 3c556385bf5a2d027b3ac5f6a5eb59d46b0f1a87.nq.gz
    ├── 40835036343d3d03487ea494f8e5d3dd370112c7.nq.gz
    ├── 41f247dcaef0af7f6d7fb4734494a42a6de6cee7.nq.gz
    ├── 42dcd5de98fc46cf7710ab2ac58ae2ccb35e3ae4.nq.gz
    ├── 4314122a14a623fca476de2fa24468441648d269.nq.gz
    ├── 43264f4b9f4ee3ffc097133e269547d3862ef835.nq.gz
    ├── 450bcf370e880ad8b25861f129951e1c50abf4c3.nq.gz
    ├── 45b94319c8daadc56a3e1eafac90afbc8727e384.nq.gz
    ├── 45fab244be75ac82736f63e497ec6f82a9eb1ec2.nq.gz
    ├── 49392e37598a985272ed43fc41ed602757c2a9cd.nq.gz
    ├── 49c5f4703873daddb875248198672bffe7fa26e7.nq.gz
    ├── 4bb179047669b111e41435c5e99fa4023550f7e0.nq.gz
    ├── 4cda0d2e005f8e86550eeb43cf9a07d807ae4253.nq.gz
    ├── 4daa7edb21696dd24de368ff3afc7b2f7db6ef89.nq.gz
    ├── 4fb7c4937e27ef9c8b22719785affd8079456500.nq.gz
    ├── 501ca72820678a1648af18971096d54467117f0b.nq.gz
    ├── 50c8bf7b931b8529b2d4492c3ab7dd22aa9e93cf.nq.gz
    ├── 525d6451b2c5eb6cff1e4bb90fd5ab34fc48a5b8.nq.gz
    ├── 54c380b84ba5874deb3bd92da3061f5d88bcf2e8.nq.gz
    ├── 5a3ed77345357e5edff2df5d7c8d2116fc5eab9d.nq.gz
    ├── 5a693fbd9fd1c82dfd19023b73e3aaeeb571890d.nq.gz
    ├── 5ab28c63523f436e066916a8a2d1c0ee63a6c812.nq.gz
    ├── 5b15b59915b70e4015ea868d8fb8b64acdc2a84e.nq.gz
    ├── 5c32bb04b3042f08e9b5b5b3a6c437219becfb0d.nq.gz
    ├── 5c6281bf988d59838b50e00aa3412c2513377785.nq.gz
    ├── 5db48fed8e39f4f27b3b4a83b8873594391ada07.nq.gz
    ├── 5e227d29a15b74f7c1778c606220773f80166b87.nq.gz
    ├── 5f47c430022e95c0f1f35cf05bba46656df10050.nq.gz
    ├── 60ba330cca9dd68a00523b2553172dc0d0a13121.nq.gz
    ├── 6103b2e0e07cbc44c1f8ad14c9c834978ead7ac8.nq.gz
    ├── 62e9571bac2363cc6b5bd363e9f99838459f265b.nq.gz
    ├── 62edbb23674b1b91b1be48109d1998dcd1a37af1.nq.gz
    ├── 632fcdd94181f730fccc0767bf3d5b4c44e778be.nq.gz
    ├── 66a3746b9d51554ad0d92a035ff3f0033eef036b.nq.gz
    ├── 66a604009318909928376fb7ff97b7bee8c05d6c.nq.gz
    ├── 66d9e285b8666279646766c97d39b5c167a57633.nq.gz
    ├── 68b36cb4c131f2f56eefda5d4b4841c39b65c8ad.nq.gz
    ├── 69c055a7bd1c6dfc3e102364681c56a6e4312b3d.nq.gz
    ├── 6a0be26f8e649bbd9cb9f6b4e085db54a7588277.nq.gz
    ├── 6a231289e75d0162628c17600c6985c737917ec0.nq.gz
    ├── 6b14eb10368ab57278ee0b5b42eb8ddf6061ffbd.nq.gz
    ├── 6c5b501d6e8d7cd348d8463643f5a72b90f87da7.nq.gz
    ├── 6cd1cfe5efc12f80fccae8ecad9b3b4f8c6de2d1.nq.gz
    ├── 6dabd2d829b2e52fa7f15110a5be64462c4011b9.nq.gz
    ├── 6e2c158dde9082dafe7d0d414d43589088c69892.nq.gz
    ├── 6e38839b0ed35bccd8ff6922940f61d6522350f3.nq.gz
    ├── 6f2b4827f94e8e216835bcb76bb4359a083acc2d.nq.gz
    ├── 713bf3224abfa9dec2689b7c0e18ba400f801afc.nq.gz
    ├── 716b960c91b7cdc42af99799f20651d27e5f10ac.nq.gz
    ├── 74f4bc748375853ae2ada85f93ac4afeab749ce3.nq.gz
    ├── 774f68ff01817e47dfa716d91c11c1db35690ada.nq.gz
    ├── 793a8cae0e1669936fff192857328b743a9b8847.nq.gz
    ├── 79818e5a651d5912b7bb7d835fad09dbe689a75a.nq.gz
    ├── 7a9f77452b7d3356a21736bb781fb53708c98b42.nq.gz
    ├── 7f3117896aa9f5b1830c98710e20f42d028e1638.nq.gz
    ├── 7f9b45bdab796026e3b3c34016c2ce26ea257275.nq.gz
    ├── 7fb919b634342ee80ff92177ca8087de3a2584a6.nq.gz
    ├── 81d9dda6e64e1e2798b3d8fe78d0fe71673b215a.nq.gz
    ├── 828ee268af40d2e7ea248eb6e4d20933cd1db8af.nq.gz
    ├── 834f17b82f22d5a06ab70e69c094d27cd24ca760.nq.gz
    ├── 83d35036b87b365ae02ed52f48b45dc20c048c73.nq.gz
    ├── 861283780ae02e6ba90e59d17d239f4096b8100a.nq.gz
    ├── 873eb128aa6485e88348cead1cdf6928925d6dee.nq.gz
    ├── 8998cd643dbea52493b4abe6fdb2d014c37463d3.nq.gz
    ├── 8bae8931915b8c8be426c5a6c42eddc33ada6070.nq.gz
    ├── 8c3c2cc8bec5213325627e86332ad9a13a2cd2d8.nq.gz
    ├── 8cc26eec269b0b92033e2dabb5f996d86f2cfb9a.nq.gz
    ├── 8d459ecd8055decbdbb37f7ce7c35ba26591c8c6.nq.gz
    ├── 8e017d89d2dc1365b2527623ef3b8457e06618f5.nq.gz
    ├── 8e493789d9026b70d0fcab556a9f39288f4be564.nq.gz
    ├── 905a6dc6df2fee4201bf208d441aef4ed3ca581a.nq.gz
    ├── 9220923fa8092ef0460b3dcc8d38e92b5ffe6a61.nq.gz
    ├── 92f82451f98de759d2cbdd3e905fd0ec0afe1886.nq.gz
    ├── 940457150d7a295d297fa9d18e26ee69c7cf3ce3.nq.gz
    ├── 94bfdca75bcf17d71949fccb827f1b747a57eff8.nq.gz
    ├── 95ec5bd54ddddd493ea523700b54d44f2189e9e4.nq.gz
    ├── 9608ca5f1f0b0f4b0c82c832319027a7f9559e78.nq.gz
    ├── 963974ed46fc09f0912018655f3a584c883f646d.nq.gz
    ├── 980d129fbc60ec01f81d93510086d8b81f631f9b.nq.gz
    ├── 983706cc7827b0f2b7228f6350adec02e76e139a.nq.gz
    ├── 9875c153f230988737a11a1bc407298fbac5d749.nq.gz
    ├── 98afce3449895e06c59eaa235b47e7ec4c5ee2da.nq.gz
    ├── 990c5f266c2e7840ffdc0531b1b34cb3902c7dcf.nq.gz
    ├── 9a8ea00d486fcf696163d12037eda9323eb3a1cc.nq.gz
    ├── 9c76f5e23954820a72da43418874856136070e6a.nq.gz
    ├── 9f9d9d5c8e5c144abe490c56e1e50627a3a7c5e6.nq.gz
    ├── a05f54234d4e632afb57ce92d417453f0384f529.nq.gz
    ├── a06b3a9a4ea43cf56f26ae4f9c02c82e6eca7f7a.nq.gz
    ├── a2cebadd1106add28b4788e1230d160975afb883.nq.gz
    ├── a4238d5276fb43460f5d3dc67f2e9e72a7b297a8.nq.gz
    ├── a4b35bc7ff8789e1290d438f2f2f8209ae6039fd.nq.gz
    ├── a5b47ec40a3715bab3b8b2b26e974bb41c6eec47.nq.gz
    ├── a5bd5baffef0cbc474fa3042811685b2a0dd85a5.nq.gz
    ├── a706cce4794bdadbc24c3d1d626cae5ffc1c9c05.nq.gz
    ├── a75a8b0081e4e369ea185d0a6a384fdcab86f27b.nq.gz
    ├── a89f2f95b00de0e9a62c33993943eabcbe4f3e50.nq.gz
    ├── aa3bb8ba97b99c91e23cdd1fc259f657fb904048.nq.gz
    ├── b0cfff9874f9d1f4d566f717921665a295ba36b3.nq.gz
    ├── b124b5f103551381af9b414d36f88d557bff323a.nq.gz
    ├── b1729e7f68204ab08109b66fd78903578078c311.nq.gz
    ├── b31e1781cb29c3a50d35b0c53fb104fc5b763e01.nq.gz
    ├── b3ca14a5e841c42037cd7e59d16b55dbbdcf7535.nq.gz
    ├── b4aa63e9d160e9fdce464ee1972e01ea7765b7b4.nq.gz
    ├── b774f392ef2098950e04e4c99c6c692f6ddda33c.nq.gz
    ├── b7f96ae7afb9abf060606e88e424490e121de5a2.nq.gz
    ├── b96c37ea623a55f27aac283a6fc9507615ef1008.nq.gz
    ├── bbe490bdcd967a933d2735f1327ec7be7ae00a67.nq.gz
    ├── bc2477718123d21988bae12d664f152b4668f7b6.nq.gz
    ├── bce9853f41737493c24eeca3331bfcf98559979d.nq.gz
    ├── bdc7fda0e284ce14056cbbe3603f34a560d75992.nq.gz
    ├── bfaf17ed86ce706e3ebb03e50f5ee1d962cec66c.nq.gz
    ├── c001312dd0f169a8438c7d2008a0d8956d10c68c.nq.gz
    ├── c30e3143ef905da45733a32d87ae4d07fed65878.nq.gz
    ├── c3c0ed5e32db114d65ee0e223fdc4cb2e87555da.nq.gz
    ├── c4f7cd01eb28f5407529e5f695c8c7b8ec35bb87.nq.gz
    ├── c6634734aa8a549ef1a1f56219a130152226203e.nq.gz
    ├── c71ea128104f59d9547b0f6b6f3506b8e54448e4.nq.gz
    ├── c8a736b8a8395afb5434ac1ec24b82b323072c48.nq.gz
    ├── c8a780f59a2b93f5f2cb269951cfca5d278fac28.nq.gz
    ├── caa3a7d24cfffdaea5f7dcb8f988d0d5086a697c.nq.gz
    ├── caeb20812903a54b79e1840052e63196b208ed41.nq.gz
    ├── cb48d89e1b96dae81af1bd4f4de38437d55e68ad.nq.gz
    ├── cb639038821ad03e884a6ed8655adaa93783edcd.nq.gz
    ├── cb6abb5344868b5f0d7bb9e13aede51ed9e32e00.nq.gz
    ├── ce4952f2dbf690e5c74ab666bef19ee96063781b.nq.gz
    ├── cf1682c729ebf9c138137789a0a92831755c56ae.nq.gz
    ├── d2178304a4536f4a84bd7ec9d7fa24d1192b1a6b.nq.gz
    ├── d4c92cbc1f2b7a9621e1d1981b1f1190cc55edb8.nq.gz
    ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
    ├── d7fcdb45edc4859dccde200b1c50a01283b509e5.nq.gz
    ├── d8521cee52ea1fecb03d07eb2236d293437c021f.nq.gz
    ├── d942a575cb181ec067bab74a09867d17f706cc16.nq.gz
    ├── db9205f1c33d3a9c7eb53fa557df98649ca58c53.nq.gz
    ├── dcb9d2b1fccb0879319fa2694729d00034465306.nq.gz
    ├── dd7d0a778d64eef69624654a2f94a28a811d6647.nq.gz
    ├── dfdeee521d9578659171de68438f78d820f8542e.nq.gz
    ├── e143e4d03c30943136690ba14f0007cf26e6cba3.nq.gz
    ├── e26aab7afca15e0b6248f8e6d7585f89983fba3a.nq.gz
    ├── e35d8850c9688b1ce82711694692cc574a799396.nq.gz
    ├── e46b072a84a80f18d2fe35fc037813f2495926b3.nq.gz
    ├── e49c6af0ebcf87fb080b3c9bfd6d89c2da4a6429.nq.gz
    ├── e626232c75f8a45341370d148465af497335e985.nq.gz
    ├── e78ac7d58ab248133bbd8a8b4524ab14e58c5786.nq.gz
    ├── e7bbe7a695d3f927796e1bec7f17b10f068274e4.nq.gz
    ├── e867b33e365181d81e8b77ba85b83d0f1c6f2699.nq.gz
    ├── e878933f1921ba888647abac0b9a62be31fc2241.nq.gz
    ├── ec8b6f922621d6d10fa7b295acd038e4d21285ec.nq.gz
    ├── ecf011a4f1460dfe08ec2e9f198dbb245f953137.nq.gz
    ├── ed9a8d0fb1a996cf03eaf5eb71ede06354b02feb.nq.gz
    ├── ef7d82752912f4033d8bee762d3d15c4790a2e7e.nq.gz
    ├── f177021dca98245519c7061f79eb104823619625.nq.gz
    ├── f1a17854590811c812917ad04eec1145a63f74cb.nq.gz
    ├── f29a902bfd68a241571c78ed321649cf0786bd0e.nq.gz
    ├── f2b28fb9aa843aa9c82b4debb81013c24bc4fbd8.nq.gz
    ├── f45d6e7ac1e0c0729d1b57133cdc4d889b488515.nq.gz
    └── f4d955442e005cc05cf3879821de34274a781ed0.nq.gz

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

[deepmind/optax](https://github.com/deepmind/optax)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
