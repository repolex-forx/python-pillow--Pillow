# Repolex Knowledge Graph of python-pillow/Pillow

RDF knowledge graph data for [python-pillow/Pillow](https://github.com/python-pillow/Pillow), parsed by [repolex](https://repolex.ai).

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
rlex download python-pillow/Pillow
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 204aae6682fc936f5350b3fe70335776f81480a7
│   │   │   └── chunk-001.nq.gz
│   │   ├── 339bc5db93bd95decf65a59fab273f300db6594d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3c41c095064200a02672d89cc5ff629eaf4b0d4f
│   │   │   └── chunk-001.nq.gz
│   │   ├── 46f45f674d47b5d8bc54230dda8fe9e214598b87
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4c1aed801e43c6b307e7135279ca1dbc02bbf052
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5158d98c807e719c5938aa3886913ef0ea6814e9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5c89d88eee199ba53f64581ea39b6a1bc52feb1a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 693df7b42c666f88c719f9973be0ad71607328e0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6956d0b2853f5c7ec5f6ec4c60725c5a7ee73aeb
│   │   │   └── chunk-001.nq.gz
│   │   ├── 89f1f4626a2aaf5f3d5ca6437f41def2998fbe09
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9b4fae77178e827ab17118fbc89c739ffd6a0fab
│   │   │   └── chunk-001.nq.gz
│   │   ├── da59ad000d1405eaecd557175e29083a87d19f7c
│   │   │   └── chunk-001.nq.gz
│   │   └── e34d346f10c0b1c814661e662a3e0c1ef084cf1c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 204aae6682fc936f5350b3fe70335776f81480a7.nq.gz
│   │   ├── 339bc5db93bd95decf65a59fab273f300db6594d.nq.gz
│   │   ├── 3c41c095064200a02672d89cc5ff629eaf4b0d4f.nq.gz
│   │   ├── 46f45f674d47b5d8bc54230dda8fe9e214598b87.nq.gz
│   │   ├── 4c1aed801e43c6b307e7135279ca1dbc02bbf052.nq.gz
│   │   ├── 5158d98c807e719c5938aa3886913ef0ea6814e9.nq.gz
│   │   ├── 5c89d88eee199ba53f64581ea39b6a1bc52feb1a.nq.gz
│   │   ├── 693df7b42c666f88c719f9973be0ad71607328e0.nq.gz
│   │   ├── 6956d0b2853f5c7ec5f6ec4c60725c5a7ee73aeb.nq.gz
│   │   ├── 89f1f4626a2aaf5f3d5ca6437f41def2998fbe09.nq.gz
│   │   ├── 9b4fae77178e827ab17118fbc89c739ffd6a0fab.nq.gz
│   │   ├── da59ad000d1405eaecd557175e29083a87d19f7c.nq.gz
│   │   └── e34d346f10c0b1c814661e662a3e0c1ef084cf1c.nq.gz
│   └── repolex
│       ├── 204aae6682fc936f5350b3fe70335776f81480a7
│       │   └── chunk-001.nq.gz
│       ├── 339bc5db93bd95decf65a59fab273f300db6594d
│       │   └── chunk-001.nq.gz
│       ├── 3c41c095064200a02672d89cc5ff629eaf4b0d4f
│       │   └── chunk-001.nq.gz
│       ├── 46f45f674d47b5d8bc54230dda8fe9e214598b87
│       │   └── chunk-001.nq.gz
│       ├── 4c1aed801e43c6b307e7135279ca1dbc02bbf052
│       │   └── chunk-001.nq.gz
│       ├── 5158d98c807e719c5938aa3886913ef0ea6814e9
│       │   └── chunk-001.nq.gz
│       ├── 5c89d88eee199ba53f64581ea39b6a1bc52feb1a
│       │   └── chunk-001.nq.gz
│       ├── 693df7b42c666f88c719f9973be0ad71607328e0
│       │   └── chunk-001.nq.gz
│       ├── 6956d0b2853f5c7ec5f6ec4c60725c5a7ee73aeb
│       │   └── chunk-001.nq.gz
│       ├── 89f1f4626a2aaf5f3d5ca6437f41def2998fbe09
│       │   └── chunk-001.nq.gz
│       ├── 9b4fae77178e827ab17118fbc89c739ffd6a0fab
│       │   └── chunk-001.nq.gz
│       ├── da59ad000d1405eaecd557175e29083a87d19f7c
│       │   └── chunk-001.nq.gz
│       └── e34d346f10c0b1c814661e662a3e0c1ef084cf1c
│           └── chunk-001.nq.gz
└── blob
    ├── 000377b6c7b1e05688fc17d5da09d163a18c5b4b.nq.gz
    ├── 0003cf33f8c74a2e173a6eaf578e8252bb1cd702.nq.gz
    ├── 0004b5521536c4f695088951b71cec7d99575aa8.nq.gz
    ├── 0006ccd1297a379811b28f9d69e12c80c262811d.nq.gz
    ├── 002497c326453b1d41602a7d57bf09905d980b8f.nq.gz
    ├── 002a44a4f4d8f220159e4b2989cff2195c61c7ff.nq.gz
    ├── 0035296a45c14576988720407e11c6a06f857ce9.nq.gz
    ├── 004217210df508cec7e17a13672cc16e68f61fbf.nq.gz
    ├── 0069eb5bcecfa4854430a0423c7a53aafa3c6c6c.nq.gz
    ├── 006d574f3fba71e73e3406dcfd055ee0814eaf1b.nq.gz
    ├── 006ee952d439ecb72667d0d5d4c6e34437ef0281.nq.gz
    ├── 008d20d38e11fe7f6d615f3f0f603f994a822a9f.nq.gz
    ├── 009280a79a648be15d6064c96f931e71ce9fde8e.nq.gz
    ├── 00c691a74591ce8755d8a61e903666baa8b7876c.nq.gz
    ├── 00c8995b08d7f3a6cd80a77dfd40d2d1d5307bc1.nq.gz
    ├── 00dec41d165fb3b414376cf90fbed980e62ee3d1.nq.gz
    ├── 00f3d5f74db75879cea73dd0b574ae9ba9e2b5ab.nq.gz
    ├── 00f6bd2f30541c65db4a1d2792cd1197661bb9f0.nq.gz
    ├── 01016355ae0403c2266226f1affb2ff042f031a4.nq.gz
    ├── 010d3f941e13f8c349fe17ef6b8f92ce1ce71474.nq.gz
    ├── 01247f97ed3efc6d98280e16bd88d9df8ec71ae7.nq.gz
    ├── 0144600066ff3b8690ce93f2fa9480d4246417d9.nq.gz
    ├── 01471189693b0e157fd311ab93e1fcd268d47121.nq.gz
    ├── 016257d3dd29e83ed8d68f89363965dc39b93811.nq.gz
    ├── 01717d980da1ce09c7d3202b276a47cecec37704.nq.gz
    ├── 017da499d2c111e821b9b674ff3339deedbfefcc.nq.gz
    ├── 0181b088cec5012953258419b42cbc90ea44b948.nq.gz
    ├── 018cc1cbfb1772b07438a152bd53230ade7fe03c.nq.gz
    ├── 01981aa4fbe2bde03969c38f6226553bffbfc728.nq.gz
    ├── 01a05606c0a6f98b25587945b74a5f80d1567837.nq.gz
    ├── 01a182cf158f36e0d4aaf1d34955c2c8fcf68ddf.nq.gz
    ├── 01bd4b1d76b335a4d38b620a6fa821a3abf0d36d.nq.gz
    ├── 01bfd1750a40c2584cf4c52ec027849d6e1a7631.nq.gz
    ├── 01cb880cb31c91223db6d9d02d001c23d2797e99.nq.gz
    ├── 01cc868b21616ef3634205e2c4283d39bdb4f2d9.nq.gz
    ├── 01d48fa3f48ee75744ca75acf8cc7ef5f414007c.nq.gz
    ├── 01dca594f53e22fda9b11ed5b704326680af1b8c.nq.gz
    ├── 01ec77a58cc706d06588f2d10da90a234716b77f.nq.gz
    ├── 01f40ee7b062b58c8039297918484b5dc0b1767d.nq.gz
    ├── 01fa090dc3ac1394d2031f2a44b31c328625553d.nq.gz
    ├── 02067a32c106de3d765128685d67b1f4b39df7b1.nq.gz
    ├── 0207d27c74b61b0b02e78eea3e38fc8431214337.nq.gz
    ├── 020fbf7df7d44df35f9d85e33025dad0e7f6710f.nq.gz
    ├── 0210505f5fe0edbf932a4728e9b3f40a98449e45.nq.gz
    ├── 02189d51405eecfd9258531959da7713561f69a0.nq.gz
    ├── 021a5fa633bf9989b728018e58f6c950a604370a.nq.gz
    ├── 0229dbbc1ccad2322a4d4ab6456f8ea8ceea4ddc.nq.gz
    ├── 022daa0003fd844f0cf716b9f58a88e418cad37e.nq.gz
    ├── 02454ba039654aa128239411a86e96f994464f60.nq.gz
    ├── 024634ad8f9dc7fc7f49cc4d94c72e52f2006d8b.nq.gz
    ├── 0247527f5b206f7110b9d1f73b7d0106957b6cf3.nq.gz
    ├── 024be9e80cf02efa80f763bf7fdaa7de945ff6d9.nq.gz
    ├── 02622e72138ddefc7980851983d95705a85ac13d.nq.gz
    ├── 02634163e1cd1e40aa0791ddd2b8deb148b19f43.nq.gz
    ├── 026bfd9a01be093084c4a1a4880e3d88a61d98ba.nq.gz
    ├── 027e5338b7a621cd6eef3a8c239345e4077757e9.nq.gz
    ├── 0283fa2fd42cd96e99d02b99a275af7d7c6860c9.nq.gz
    ├── 02939d26b5f33d03b17ec3fc3594847f02d8a8a3.nq.gz
    ├── 02a4a5c7668e22b43b0ab7f34115eacaa4d91e39.nq.gz
    ├── 02b4f392e6f52d3b987d6e4f3d630ca87253d62b.nq.gz
    ├── 02da702a799b60a53a41ecce45d889c7b6f7955d.nq.gz
    ├── 02e1bfe6a99443f83f72e522d6440e82bc17f03b.nq.gz
    ├── 02e464ff190ac6cf003042fac858d63e65174169.nq.gz
    ├── 0302ea476a17942eb3f4a10d347533af4f57a667.nq.gz
    ├── 03137c8b6037b9a9da81c5e14a1eae4b9c2dfdd5.nq.gz
    ├── 031bdcfce10dc119f4479085810427cccd925671.nq.gz
    ├── 031fceda3fa596457276a1ac8e16e9e0b8f4e8e7.nq.gz
    ├── 032c1c6d2634f229f068f8f4af6950694552d109.nq.gz
    ├── 03359de31cd9201a1ae73dacf98c5528c2a49ef6.nq.gz
    ├── 035b83c4d77288e2ef08f78268cc98be92cd838a.nq.gz
    ├── 035fbc4bb84d6b67ee99cd6bbb5e8996059dd142.nq.gz
    ├── 036521b0e5e94294cdf671f729dd08f1dae300dc.nq.gz
    ├── 036965bf5d8068323df2c14f4fed7fd5d4fb981b.nq.gz
    ├── 037479f9fbbf28c43ca7f1c24e0ab28cef4b1fb5.nq.gz
    ├── 0376e90a7be5f9da5b5882aa5e54af41de695128.nq.gz
    ├── 0379443241918d6ebf3e7d6e6ea6745861dd1794.nq.gz
    ├── 037d6f492ce775c53c7df02403530f7a5673b7a8.nq.gz
    ├── 03829c133f5b4590644d33aba62e22a265306d84.nq.gz
    ├── 0388b6b8a1cf16628ad2270f07518dc2cfbe19a4.nq.gz
    ├── 03960d4939938541ca3f8efee4bf13ffdecbb2f5.nq.gz
    ├── 03a6eba44ffe9104130c8263bfabc3bc30f736e2.nq.gz
    ├── 03afa2d2ef2c6fc71a08f54aaae8acc5ee84a4ff.nq.gz
    ├── 03bbd4b43362900338480cf23dbf65dc9ffbd58b.nq.gz
    ├── 03c436435d6d18bcb407d39374f34afd22be7ff1.nq.gz
    ├── 03c797e537c7868b9ecb4d48961c52f88251e5f1.nq.gz
    ├── 03db1ce35165157ec2a85becf80827cefea7a56e.nq.gz
    ├── 03dcab81d0d3c0b53227930815216ddbc4d22223.nq.gz
    ├── 03e92b5b91311a8249b5401989f66d1deb316b86.nq.gz
    ├── 03ee96c0f00c952e798cd054dcf6bad5a8c435f2.nq.gz
    ├── 03f18c195e4127bfac021171d10e21f568ccf334.nq.gz
    ├── 040301433f94dbf090d59d4fbc8dcf9b8bf2720d.nq.gz
    ├── 040472d69e3884378eb121210c1f555d847659bd.nq.gz
    ├── 0411779535bb6d13283b8d5897cbba51880924f3.nq.gz
    ├── 0425bbd750eacf884ca1fc0ba8aa893a71ccdfc6.nq.gz
    ├── 0429eb99d83d4ed519f64c235281768a0df4bccd.nq.gz
    ├── 043156e892dadc4fb1222b33f5eda33251cd15aa.nq.gz
    ├── 04325ad868f09dd510fe0499b1cb42eb1c506fe1.nq.gz
    ├── 0432ebcb61c30a77eb385b323a0bd6c8d8577ef3.nq.gz
    ├── 043559352ab19376892afb7c8bdeb5ed5674497a.nq.gz
    ├── 043cba6af8bbfe6d7386ac7ca247c5235c0dc387.nq.gz
    ├── 0445a2ab22f52f549409bc6c74caf49993560bb2.nq.gz
    ├── 044aede626434e93f32cd5800ba205066ec9a206.nq.gz
    ├── 04545f81742ea9a1a5d03a28cd57adf1894d3a4a.nq.gz
    ├── 0456bbaba3c8202752863738198a3a9bc434d0fd.nq.gz
    ├── 0462cfd49680e9cb55138e56db3c5b5921e7a7dc.nq.gz
    ├── 0465e48c2046a9e453f002aad318b4dc7bb165eb.nq.gz
    ├── 046e9e45cd6b54befa51b8d108e2e0cb303c7914.nq.gz
    ├── 047990f1c2a3ab2bb44ec1763bd1c48af3019cc2.nq.gz
    ├── 047be16c5f5ca9c4e23ebd7164ed4912aea23cd2.nq.gz
    ├── 0491a22a11ca017319ea4f3d30bf08f792ce09ee.nq.gz
    ├── 04a3121d24d04cc8e6917691ff9408e0f5c27e49.nq.gz
    ├── 04b2a47eed329f5d79a8f922d02df295c80fc200.nq.gz
    ├── 04bfbc7556b848eef51e33ff636a8e7008553583.nq.gz
    ├── 04c9ae8abd88adddea7b3251d35a98a403b08140.nq.gz
    ├── 04d3dadf8d17ac6a8abb0339a63ee33ae8145654.nq.gz
    ├── 04d6f5dcd588f79c97472d1e985f0812b336f92a.nq.gz
    ├── 04df163d7fed0433ac4dadaf0d0e5a42ca1c28bb.nq.gz
    ├── 04fcf61e0ef476aed6a41327ecf621c5d924d714.nq.gz
    ├── 051623ed4480b4bf07e1c49f3eee0321d5530117.nq.gz
    ├── 0516b760c61f21cf4da96a8f151dd55d186f6738.nq.gz
    ├── 051fdcfc9871fe1545fb8ba73ba194b4882e4388.nq.gz
    ├── 051ff23589d1c5fc0f25f8fcddcc549b07cf364d.nq.gz
    ├── 0521f5cf176fd6c774b7e58a7f450dbc369644a9.nq.gz
    ├── 0526233c0f5282687e1efb57dd7ce6d8f20929fc.nq.gz
    ├── 0526f550ef6ace9a1119f02a182776e6dd61a1ce.nq.gz
    ├── 05279ddfbe65e0b91d7ce07306db92133f9e638b.nq.gz
    ├── 053e4e4e952ca9a0139f6d7a2b726c64b305fdc1.nq.gz
    ├── 054b82df5ba930779dfa3e8bad304d171bb74e6b.nq.gz
    ├── 057d0acf0cee4645f3b6360dabbf9f7b421ff428.nq.gz
    ├── 05828a72fdf90dbe434cebf06f968ef7e91189b3.nq.gz
    ├── 058861d67e511324de620f283d62fd5c1f2dbfeb.nq.gz
    ├── 05925d50202e9bf9a37dd392f60f89cf9c53abcb.nq.gz
    ├── 05948d44aeddd75798f11b596ff11c6020588957.nq.gz
    ├── 059d7b72aca31525f2ae86da71d7139b0fb4e4a2.nq.gz
    ├── 05b2d34d54cdddbdda419fb622fa4914a5081cf6.nq.gz
    ├── 05b5d471691abc7b61b63c04a0cff0d496a02e48.nq.gz
    ├── 05cb37554b32409736dd5a58de235627ff8587c6.nq.gz
    ├── 05f209351d2b164eac6a0ee5083e633471b825c3.nq.gz
    ├── 0605821e0ad7a168ed4387d1e7291bd63310fcb3.nq.gz
    ├── 060fc497ea7af0b31acafa4bd18342aa04e87252.nq.gz
    ├── 0617291d152975acfb63c18e742398bca34e7afd.nq.gz
    ├── 063046d8c223a2aa5114ab798f72332fd6360b48.nq.gz
    ├── 06334d666bd6bc6e08d88f08dfc198f404793b9a.nq.gz
    ├── 063833b3a35c36480a888f136da69464c9ba7c11.nq.gz
    ├── 0674a9a152891da8d9bfca7124126851ade460a0.nq.gz
    ├── 067c165b24811ad7dd230d48b0c4fc19554d1342.nq.gz
    ├── 067f42f62de41dcff95a93da1633747bc8f12ad6.nq.gz
    ├── 068cd5c33dbc80ed211928023b232ac2ed99aec6.nq.gz
    ├── 06965ead3f07721bdc3be6159c9a8a518b3cf46c.nq.gz
    ├── 06acfc7afd2409f0e57f5cb4f9f0b416dad2120f.nq.gz
    ├── 06e4a089380d59de2e81b3d5a87d09591d75f8f8.nq.gz
    ├── 06e6d99748431592e7a3fd72b0415e526b24624a.nq.gz
    ├── 06e95d7cc2cf98c16d8b1228bae78b7480902f06.nq.gz
    ├── 06ea0359c45b8fe49bb8d8ab2899533bb5f42b27.nq.gz
    ├── 06ed2ed2f607d890d4ea25d763d758f39440b521.nq.gz
    ├── 06efed7443f9bf50e6b208b1fe5e35d58663cd97.nq.gz
    ├── 0706af4c07dd1d507286dab3153cdb735aaf09b0.nq.gz
    ├── 070ba23a178cb622b4f298794a607bace3a982cd.nq.gz
    ├── 07191892506868d269fc7ba7e9a4f8b6510cd933.nq.gz
    ├── 07239887f9f98692b632388d897970e8399b6b12.nq.gz
    └── 0730936feb02979540f21be7b5690949462b7bef.nq.gz

32 directories, 200 files
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

[python-pillow/Pillow](https://github.com/python-pillow/Pillow)

---
*Parsed on 2026-09-25 by [repolex](https://repolex.ai)*
