# Repolex Knowledge Graph of python-pillow/Pillow

RDF knowledge graph data for [python-pillow/Pillow](https://github.com/python-pillow/Pillow), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download python-pillow/Pillow
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3c41c095064200a02672d89cc5ff629eaf4b0d4f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 3c41c095064200a02672d89cc5ff629eaf4b0d4f.nq.gz
│   └── repolex
│       └── 3c41c095064200a02672d89cc5ff629eaf4b0d4f
│           └── chunk-001.nq.gz
└── blob
    ├── 000377b6c7b1e05688fc17d5da09d163a18c5b4b.nq.gz
    ├── 0003cf33f8c74a2e173a6eaf578e8252bb1cd702.nq.gz
    ├── 0004b5521536c4f695088951b71cec7d99575aa8.nq.gz
    ├── 002497c326453b1d41602a7d57bf09905d980b8f.nq.gz
    ├── 004217210df508cec7e17a13672cc16e68f61fbf.nq.gz
    ├── 006ee952d439ecb72667d0d5d4c6e34437ef0281.nq.gz
    ├── 008d20d38e11fe7f6d615f3f0f603f994a822a9f.nq.gz
    ├── 00f6bd2f30541c65db4a1d2792cd1197661bb9f0.nq.gz
    ├── 01016355ae0403c2266226f1affb2ff042f031a4.nq.gz
    ├── 01247f97ed3efc6d98280e16bd88d9df8ec71ae7.nq.gz
    ├── 01471189693b0e157fd311ab93e1fcd268d47121.nq.gz
    ├── 016257d3dd29e83ed8d68f89363965dc39b93811.nq.gz
    ├── 01717d980da1ce09c7d3202b276a47cecec37704.nq.gz
    ├── 0181b088cec5012953258419b42cbc90ea44b948.nq.gz
    ├── 01a05606c0a6f98b25587945b74a5f80d1567837.nq.gz
    ├── 01bfd1750a40c2584cf4c52ec027849d6e1a7631.nq.gz
    ├── 01d48fa3f48ee75744ca75acf8cc7ef5f414007c.nq.gz
    ├── 01dca594f53e22fda9b11ed5b704326680af1b8c.nq.gz
    ├── 01ec77a58cc706d06588f2d10da90a234716b77f.nq.gz
    ├── 02067a32c106de3d765128685d67b1f4b39df7b1.nq.gz
    ├── 0207d27c74b61b0b02e78eea3e38fc8431214337.nq.gz
    ├── 020fbf7df7d44df35f9d85e33025dad0e7f6710f.nq.gz
    ├── 021a5fa633bf9989b728018e58f6c950a604370a.nq.gz
    ├── 02634163e1cd1e40aa0791ddd2b8deb148b19f43.nq.gz
    ├── 02b4f392e6f52d3b987d6e4f3d630ca87253d62b.nq.gz
    ├── 02e1bfe6a99443f83f72e522d6440e82bc17f03b.nq.gz
    ├── 0302ea476a17942eb3f4a10d347533af4f57a667.nq.gz
    ├── 031bdcfce10dc119f4479085810427cccd925671.nq.gz
    ├── 035fbc4bb84d6b67ee99cd6bbb5e8996059dd142.nq.gz
    ├── 0376e90a7be5f9da5b5882aa5e54af41de695128.nq.gz
    ├── 0379443241918d6ebf3e7d6e6ea6745861dd1794.nq.gz
    ├── 0388b6b8a1cf16628ad2270f07518dc2cfbe19a4.nq.gz
    ├── 03960d4939938541ca3f8efee4bf13ffdecbb2f5.nq.gz
    ├── 03bbd4b43362900338480cf23dbf65dc9ffbd58b.nq.gz
    ├── 03c436435d6d18bcb407d39374f34afd22be7ff1.nq.gz
    ├── 03c797e537c7868b9ecb4d48961c52f88251e5f1.nq.gz
    ├── 03dcab81d0d3c0b53227930815216ddbc4d22223.nq.gz
    ├── 03f18c195e4127bfac021171d10e21f568ccf334.nq.gz
    ├── 043156e892dadc4fb1222b33f5eda33251cd15aa.nq.gz
    ├── 0432ebcb61c30a77eb385b323a0bd6c8d8577ef3.nq.gz
    ├── 043cba6af8bbfe6d7386ac7ca247c5235c0dc387.nq.gz
    ├── 04545f81742ea9a1a5d03a28cd57adf1894d3a4a.nq.gz
    ├── 046e9e45cd6b54befa51b8d108e2e0cb303c7914.nq.gz
    ├── 047be16c5f5ca9c4e23ebd7164ed4912aea23cd2.nq.gz
    ├── 0491a22a11ca017319ea4f3d30bf08f792ce09ee.nq.gz
    ├── 04a3121d24d04cc8e6917691ff9408e0f5c27e49.nq.gz
    ├── 04c9ae8abd88adddea7b3251d35a98a403b08140.nq.gz
    ├── 04d3dadf8d17ac6a8abb0339a63ee33ae8145654.nq.gz
    ├── 04df163d7fed0433ac4dadaf0d0e5a42ca1c28bb.nq.gz
    ├── 04fcf61e0ef476aed6a41327ecf621c5d924d714.nq.gz
    ├── 051ff23589d1c5fc0f25f8fcddcc549b07cf364d.nq.gz
    ├── 0521f5cf176fd6c774b7e58a7f450dbc369644a9.nq.gz
    ├── 0526233c0f5282687e1efb57dd7ce6d8f20929fc.nq.gz
    ├── 05279ddfbe65e0b91d7ce07306db92133f9e638b.nq.gz
    ├── 053e4e4e952ca9a0139f6d7a2b726c64b305fdc1.nq.gz
    ├── 054b82df5ba930779dfa3e8bad304d171bb74e6b.nq.gz
    ├── 05925d50202e9bf9a37dd392f60f89cf9c53abcb.nq.gz
    ├── 05948d44aeddd75798f11b596ff11c6020588957.nq.gz
    ├── 05b2d34d54cdddbdda419fb622fa4914a5081cf6.nq.gz
    ├── 05cb37554b32409736dd5a58de235627ff8587c6.nq.gz
    ├── 0617291d152975acfb63c18e742398bca34e7afd.nq.gz
    ├── 06334d666bd6bc6e08d88f08dfc198f404793b9a.nq.gz
    ├── 063833b3a35c36480a888f136da69464c9ba7c11.nq.gz
    ├── 06e6d99748431592e7a3fd72b0415e526b24624a.nq.gz
    ├── 06ea0359c45b8fe49bb8d8ab2899533bb5f42b27.nq.gz
    ├── 06efed7443f9bf50e6b208b1fe5e35d58663cd97.nq.gz
    ├── 0706af4c07dd1d507286dab3153cdb735aaf09b0.nq.gz
    ├── 07612e5872e00989ec76fbd29b9587ca28fec2bf.nq.gz
    ├── 0768729793340d8c2f0d69a954b98c16c6346150.nq.gz
    ├── 079271fc6d86762bf99e838c7c24c7fbb3f4648d.nq.gz
    ├── 07964487f3cb9ae2a801dfaf63a01f0ab570cf09.nq.gz
    ├── 07a1ff4e4dd41f919c482cecdb455526b4354418.nq.gz
    ├── 07a74a104cd5bc71779be6fe61d614ae7d30c09e.nq.gz
    ├── 07bbf747155607a3ada3f4b752f990099c1e711a.nq.gz
    ├── 07cb69719d9d965f5e237152522b4446d3e0a018.nq.gz
    ├── 07d339e7c51774b7754365832003f868a494847d.nq.gz
    ├── 07e62db8ced49ed476b26dc35d0ad8f881bdfa41.nq.gz
    ├── 08226738e11c97884e441dc36aa223c72496a914.nq.gz
    ├── 084d0f2880d4fb1b561241dbc3375a8b3b437c1f.nq.gz
    ├── 08862113b153a19024a6e7db3b8737a0e7621682.nq.gz
    ├── 08e14f0e3a150d24a3ceee5da271cacca441778d.nq.gz
    ├── 08ea7002849ebe3489e350619e8e0a0ebddc94fc.nq.gz
    ├── 08f8c4681a90908a2ca3d7695d19f150a5787816.nq.gz
    ├── 094c3057c867a1d678b1683937df5ff70e7b3c96.nq.gz
    ├── 098e431fca031c8e53c3a0982205d8f1a15f5de5.nq.gz
    ├── 0a3fdb809ed719ab2619185dbb07d76eb16ddf2a.nq.gz
    ├── 0a99a605afcbfb2e8cb2e60e041cd44562648873.nq.gz
    ├── 0aa8de04cb4cb1f0726e0d16bd90ba288bd22773.nq.gz
    ├── 0ab63ef42e02a5408d79beba6ea393c4d5fe47c0.nq.gz
    ├── 0b06aac965ff9208bef778ca100e623092d67125.nq.gz
    ├── 0b1f060438aef10d8f0d4cc67628ca75572793db.nq.gz
    ├── 0b285fe8053fb2853ada1ab0af301d1d950efd87.nq.gz
    ├── 0b547c7e2ec3d3941829b7cd7da5ec0933256715.nq.gz
    ├── 0b60190d26cac6445ca646baa769bc09297535a8.nq.gz
    ├── 0b999eed32005a4095bd23316396a594b02fd572.nq.gz
    ├── 0baab7ce21e685c9133dbbc6eaf05fd155d93737.nq.gz
    ├── 0babc91083fa17d380aa945763fbf8ab38db74d7.nq.gz
    ├── 0bf7752300e0a27f83cf2e8ab08000f0a46a60e0.nq.gz
    ├── 0c11e70f210dec640117d9bc468aabb7a1abbf60.nq.gz
    ├── 0c7c7620fd47355a40e72b01b10b601a1230b323.nq.gz
    ├── 0cb7ea36e3e338376493f0a9d2cf95388528afcd.nq.gz
    ├── 0cc27b69cd9f7f73eea4b13a1b315c9ca3179215.nq.gz
    ├── 0cd5bea856b6ed89d5a57d2bef5daaa02e59f3df.nq.gz
    ├── 0cdf4d26e3ec7804048b402db4966230ebddf197.nq.gz
    ├── 0d28069f00031ef8076f3a2d4841ef2f7dbccea9.nq.gz
    ├── 0d43cbc730e91c03491caf2c5387e1e88af4f900.nq.gz
    ├── 0d4ea602fc3522c314bb74355aa82239a0cbfb06.nq.gz
    ├── 0d5ff03f525904d4bc29e3b22f70b45eb1c2cba7.nq.gz
    ├── 0d6f394dd6f13d599b44a117c860cbff21835ff4.nq.gz
    ├── 0d9a1c8f81677324ae1e29610df9727fa69cf5e3.nq.gz
    ├── 0de1d33941e6150fd3b44d017f940cb0b2c1b370.nq.gz
    ├── 0de7760e98e27e622490a8221b7f4074d6853fc8.nq.gz
    ├── 0e60b59f5d25201eb29ad8addd157b3231279adb.nq.gz
    ├── 0e7e6dd8ae631ad3577bda1d3e823bd2a3227536.nq.gz
    ├── 0e9edfd403182dd3ca815935cc85f33ec5dbd746.nq.gz
    ├── 0e9f3b412c23ef5c92aed7a7d00b3aef154f3dd4.nq.gz
    ├── 0ea3de39906b931401630b9354061e4780a5ecac.nq.gz
    ├── 0ede05917a40b7b777e1ff2e6d8a0aca927a1897.nq.gz
    ├── 0ee49b150088f6630ad4d76ba2c087a4fba7c97e.nq.gz
    ├── 0f290fd7fdbab8db7e78ae0d2a1183048e04cb0b.nq.gz
    ├── 0f3996e95eb284db22889658455e5fa15363ddb8.nq.gz
    ├── 0f6685a462f5f1f5abfaf2ce4d141baba4c0da54.nq.gz
    ├── 0f93442678d649818d1cde598a3a1c7362ebb8cc.nq.gz
    ├── 0fa209c5cb1fd03603a44fc5d4c0dfeb997e2c16.nq.gz
    ├── 0faf96760bd07e176449d278325fc3e2feeb2a63.nq.gz
    ├── 0fff4a0d43d4e44dd4df3f6eb2f94d047d74efcc.nq.gz
    ├── 10002656245beff2de91b93edc930c4d1d367e92.nq.gz
    ├── 101e0b49437ddcdfdf8d2c94d0644cd767d18d83.nq.gz
    ├── 102e971dd320eeaf54fbe4811bc76c95c1a1c05a.nq.gz
    ├── 1097f4be59eefd9ed1332e15f063c323ce04f5f0.nq.gz
    ├── 10f0f44009ae9237c1a5712ae8b0c7269b527711.nq.gz
    ├── 1102c69ca3b0cd47c1c9763168605a54b799c2c9.nq.gz
    ├── 1109b4ee670b5b0f642aee70773c32768ec0e07e.nq.gz
    ├── 1123d7bc915c896297ad380a7b29123692a6744f.nq.gz
    ├── 112aa9fe67feaaa39ceb6bb9bbec6a37a13a6d02.nq.gz
    ├── 113d3075532d82b404f5230eb4ed682cd439a45e.nq.gz
    ├── 1149e29649e397696507d9766c048cee992ab1cb.nq.gz
    ├── 115141273f59544f3a0990ce33371d8faba266a2.nq.gz
    ├── 1169ab02f4fca8ccdc7cad9647ab3825dd8928e9.nq.gz
    ├── 1175616e1472c8f5a255b563edafef5f730e0ed6.nq.gz
    ├── 11ccfb6cba02b18bf51522560f32ee14e258124e.nq.gz
    ├── 11d90699d10a143dec559004e42f8ab580a322b4.nq.gz
    ├── 12058480a4469be242fb7b4587538b1f55d10356.nq.gz
    ├── 1210e3737978e5b6b8d0d94817c31ecc5eedd389.nq.gz
    ├── 12633284f49bfa8ff7270fd8791780ffa8a1387b.nq.gz
    ├── 1278ba3a6d6ffa38f527688c76ea5c7224e7ddcb.nq.gz
    ├── 12a05ec18b17445b2977b984fbc7575ac22907fa.nq.gz
    ├── 12bafa8ce90bf0166d205eb8fa7002ae20260372.nq.gz
    ├── 12c15b43ea70984dcf2a95b4479e50c250f630b9.nq.gz
    ├── 12c8741cee2f5f2ce8d3d11307c0d4135db23302.nq.gz
    ├── 12dca6cf2c9313d13a900188a21834287c1fe75a.nq.gz
    ├── 1324a40d00a417649e67f2c4eb8f23f9f7ee1c3d.nq.gz
    ├── 13b540d600b5057ecef4e7e4c3c452dd87362b5f.nq.gz
    ├── 13c6a43239beebabf0585993f2824133434a595a.nq.gz
    ├── 13da711bd13d456406188b445a9668c40fc8604e.nq.gz
    ├── 14168da8992ee8bed51ce4e33348f2a84175c128.nq.gz
    ├── 14222db1094c1e537dd2310a98075c08b5e3cc36.nq.gz
    ├── 145130c8ec7d0e0034f583ac57f67e543aba7413.nq.gz
    ├── 145b8b074a203e1070b17ffc8a9ecab612b3d4cf.nq.gz
    ├── 148cc206a5d0ada68925359fdf0ed8e70698278d.nq.gz
    ├── 14901b3882cea0679832e4f45a49f6b10034d3ce.nq.gz
    ├── 14a76d9d6181e1c279a249cce6869bfe4f831772.nq.gz
    ├── 14d6e8be7b22735358669388ed719cc2aeb8ea10.nq.gz
    ├── 1503168ab9caff1c119c51a3d79ecd17d456c81a.nq.gz
    ├── 1527cbf91a05aaa0b23726a8f4fb70f7fa55ac61.nq.gz
    ├── 15339ea9ccdd3bc54b25dfe54800f1c3bb730d26.nq.gz
    ├── 154f3dcc061a76f85c95d16ce460d1fe91ff2632.nq.gz
    ├── 156c9a091ec1e758906761dd85071cba04770a41.nq.gz
    ├── 1571cbc4e917d9c3bfcc88bb810819985b89eb47.nq.gz
    ├── 1576a549b58ae83da286c7481c1b8f7f797ad4fd.nq.gz
    ├── 15a7c980914a4789c9f4b4a64481a9acbd525bee.nq.gz
    ├── 15dd7f116dbfd6fb2f8218f7e3ff7803d199755f.nq.gz
    ├── 161d82f2e5fa051c08dd9d17fdc77a262069359f.nq.gz
    ├── 162037184e8871bc47b8366160c430375da27e9c.nq.gz
    ├── 162b0521ba0838422de4f1de884a341b93904b3b.nq.gz
    ├── 1655b8f60159a12d85347c34b92c43374e7b0714.nq.gz
    ├── 166381fb73f0e0dba385f9f39893be35f89bbdb1.nq.gz
    ├── 16e4bfa52e6c870feba0582df6812b668edf2ed3.nq.gz
    ├── 1727fe338fc0bb705f6d340c969567c76e618fe9.nq.gz
    ├── 174f565fc64f2791a9b4aef3cc09240b402ddafe.nq.gz
    ├── 18197c15f1a23322cbedfb798a1ad9daf385fdb5.nq.gz
    ├── 18215f1aff7d85bf066a4f12cb16542c48ad18c2.nq.gz
    ├── 1852f9e47868f2c181a70005771572f052815c96.nq.gz
    ├── 186d6ee843b43b96b5bca831353fbf7141e399c7.nq.gz
    ├── 1871d1f7a7b89a63e31c9679416c1e0b2369383f.nq.gz
    ├── 188bb0499e67f93af7be88c3dc8e4c855605835b.nq.gz
    ├── 189758944d933d5d503ecc6ae3da72da3c605bdd.nq.gz
    ├── 18c5a4990cdcaf8b31f71ee20f88c85d291de263.nq.gz
    ├── 18c6f657925f79c5ac46e27687d422fe797f1684.nq.gz
    ├── 18fd1e1723de3237802ecf53839ac530d5321822.nq.gz
    ├── 1907d5d3d474b41f091b714ab3bcbf3190404f38.nq.gz
    ├── 19180638efa88ebf827c78a7ed5e4a112815e10b.nq.gz
    ├── 191cc0b3a6710a68be803020711d080a1010efb0.nq.gz
    ├── 192c041d94edd900be6520be120df67d88eb7863.nq.gz
    ├── 19423e51afe522e040077129aff84af82b2746d2.nq.gz
    ├── 194c85784c51ac3e30ea62381102eeca429fe63e.nq.gz
    └── 194d24540e1a67bbe9f0b402df6e4ebe684eafad.nq.gz

8 directories, 200 files
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

## Source repository

[python-pillow/Pillow](https://github.com/python-pillow/Pillow)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
