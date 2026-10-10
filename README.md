# Repolex Knowledge Graph of pola-rs/polars-benchmark

RDF knowledge graph data for [pola-rs/polars-benchmark](https://github.com/pola-rs/polars-benchmark), parsed by [repolex](https://repolex.ai).

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
rlex download pola-rs/polars-benchmark
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 401908a307f133a2dffbe3f5e0e0fb2b50ea310b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 401908a307f133a2dffbe3f5e0e0fb2b50ea310b
│           └── chunk-001.nq.gz
└── blob
    ├── 00abce1db175dbb870836fbf6f78f9aab294c5f4.nq.gz
    ├── 019c04a24ba2840062687e24211fd6637cd0c1fd.nq.gz
    ├── 02ba1109551b2c2ecc4eaea25c5ca8275df6ab1b.nq.gz
    ├── 037b4598982f114b6279b60d5af2c020f26a2a73.nq.gz
    ├── 03bddb7a477ec2f97db3686e5d4ec6ca0fa72f57.nq.gz
    ├── 03f379c37e80918659aa94a2a86f365f9fe54627.nq.gz
    ├── 04080a229a05ec0b8b24bc67ee7da761fb286498.nq.gz
    ├── 06abe4363addd548efe328c7fbe860ffbe68b31c.nq.gz
    ├── 06e8d33aa8c7b85bb8288f07ec03812abbf1b669.nq.gz
    ├── 08bfaa91f47b11be2e8c55a8a956992cc7d0a1b7.nq.gz
    ├── 0a4aab25845ba43a35de3e63cf64ceb5ea32db9e.nq.gz
    ├── 0bd138c2913f1f2852f23c26b4dc5ef0254682dd.nq.gz
    ├── 0cf84113719a3848c261c2eb0d89004b3c9ab999.nq.gz
    ├── 0dabfb5af4baa4df1804c87b3762e36b8e70df73.nq.gz
    ├── 0e6571a1db4a18522f14727b971ef7beb56679f0.nq.gz
    ├── 0eb4aec4e803699bec37a25f2d8972dd0cb4ef5d.nq.gz
    ├── 0fc97f50d64a0571f1a28f6945037b2544208757.nq.gz
    ├── 10a5ea942a8bdfec3410af47c2cba56b514537e9.nq.gz
    ├── 11c52a93ec0bdcd22a2c23c0c507ef33748fe263.nq.gz
    ├── 1200bd969c05c56849cbaf37ee14fd70962a1f63.nq.gz
    ├── 12f830cd7835cd59fef9107e70416e825390ffa6.nq.gz
    ├── 16ab17f1391ea89141d2467811cb3a06b53c0ce4.nq.gz
    ├── 16d1f97633ab0225ac04bca03b575f9f6e382bce.nq.gz
    ├── 180f7b6d71f2d5cdc68080636bd5972c10758ff8.nq.gz
    ├── 1959e35b6b2afec3c7f66330b0823c6b2ce8a963.nq.gz
    ├── 1960bb29fc1c6c7d0c1b2d0ef35b9dde5466f51e.nq.gz
    ├── 1b636c108dac09db6ebb8ec4b57f213c80002c3d.nq.gz
    ├── 1c23635ee61454852694bfbd63d5e2bf967ee293.nq.gz
    ├── 1c26fe9bca23842ad57e98ee9ce9a19b9fe750c3.nq.gz
    ├── 1c72c5a83ac85f4a2e9cf2a7d6ecf03071cccd05.nq.gz
    ├── 1d358bf0fac2087cdf6fc1ed6714622ede28df84.nq.gz
    ├── 1e44bb1ccbedc11699fa812d7dbf17d43e0ca0ae.nq.gz
    ├── 1edb0a8ff0134881681f7a68f386ab5eace644e8.nq.gz
    ├── 200d47ec1a8b01e9e7524eb5a090b3c27154b3d8.nq.gz
    ├── 201a4f3594667c5f46a154b666f74afb4d8c0eb0.nq.gz
    ├── 222014c2f7dd8b7360c5d9fbc360472ce4b447b1.nq.gz
    ├── 2220af9f187f531cc241126ed98a41ca03150588.nq.gz
    ├── 230831896cb942ef493f32e2d555eaa0b2a532b3.nq.gz
    ├── 23a060ad58fcad16fea9815587e4f4fca0c898ae.nq.gz
    ├── 259ff83d7eb2c8a69d9f9c12c075c02a28f065a1.nq.gz
    ├── 26566cb85af6bfb1076836e4421e1fd2b6b59f5a.nq.gz
    ├── 2687e19204ccd008990de9cc07b716515aa71ea7.nq.gz
    ├── 26eafadf150a53b6038887931acede7c1ed5f395.nq.gz
    ├── 270fae867861c701405b1ab65a49dea2bf87c7f9.nq.gz
    ├── 2728f7e90527a6db8366c3dec4ebd8ecd027daa0.nq.gz
    ├── 274a1b8c42bedb3c97390fedb17a20e38943c994.nq.gz
    ├── 28d0b9c823645b2f4211756794818eee6093555b.nq.gz
    ├── 2916d202f0d779880bd61aca3fc661fe838e1259.nq.gz
    ├── 2956a737d2dd7eabe1253579ee80cab5c5362a93.nq.gz
    ├── 2a0016b5e8c17f7725b6028b4fd0808a024e689a.nq.gz
    ├── 2a50a5442608072f644bd7d8a83b6fff5d75a4ae.nq.gz
    ├── 2a77377cf669dc6ff1ee48c8d0ce3ecb3f6ac282.nq.gz
    ├── 2b6a663aff566994d3ae3cfa586cc27994fd0a6c.nq.gz
    ├── 2c875987aacbc396f17ee3fa141d4105743f6943.nq.gz
    ├── 2c8810c0365193aeec20cbc3c200b0326c1f94d3.nq.gz
    ├── 2d734a5eea1b366995d2e48ff74f2cb2a12cfdd9.nq.gz
    ├── 31b9cffabb78c9cfdf10013f49cb2bb8d3db71af.nq.gz
    ├── 31e7b364b0735d92e9d4258a75e8b125c5c05ac9.nq.gz
    ├── 327e5de4b256456e8f5e6e5cbf32b342258045bc.nq.gz
    ├── 331f573c63e5a056ab0394d2acf05ddd132bdc72.nq.gz
    ├── 3334698e42a4cfdd6a838d9eb503d63434c1819e.nq.gz
    ├── 3385626d16fdeb8c0787465686f770ff7935a469.nq.gz
    ├── 33bdf870640c547f590662800c71f3a88f82a912.nq.gz
    ├── 353368438bc4c7766692d65d725088ffbf9e1b7d.nq.gz
    ├── 353dc99be93f92af91e0fc9e2f73c3690db4981e.nq.gz
    ├── 3711427de1c1d78a3588e56e8add2768950a8061.nq.gz
    ├── 37bf30b076191da9c5f9e85ab0cc1b2007cad7b2.nq.gz
    ├── 38187dcf19444bd09902839a06d0f27d88bf8c89.nq.gz
    ├── 38f82e5d84ca0694a9c2b3ad190fd234b75d171e.nq.gz
    ├── 394de4487ed6c95281bf423bd6fec6f2c97d2542.nq.gz
    ├── 3968f54f27af88d98d57e3bb97762cb83a45707e.nq.gz
    ├── 3b29a61a980b6f513f891b8f98e6aefbc9c2c5c4.nq.gz
    ├── 3c3554043e339ca2f4a675ac8a0bb2a12174d1a8.nq.gz
    ├── 3c4f64d291835c3529d13bf3c7fb79f25532fb3a.nq.gz
    ├── 407417ee1369960d52591eab1a9d02ef8d3716b7.nq.gz
    ├── 414d3abee33cb98f825edb6235ef199ceda6f987.nq.gz
    ├── 416686eefe9bf4c6587e14fd1c0894390826962f.nq.gz
    ├── 41e0dbc4cd8fe87086d04d71005486c2adab0ab0.nq.gz
    ├── 45110e62b62c2a2db3c66eb0ff53fea1737b9e91.nq.gz
    ├── 4655f4c65e2d867ea2a07ae5b5657c791cbc0f26.nq.gz
    ├── 481a0204a9216dcbccb7389672707d6aa2cf15b4.nq.gz
    ├── 483ef1e236d69c7143bbc55456c75d2f7d196705.nq.gz
    ├── 487b9fbb90b88431c06b03d1d65f08da2b9b788d.nq.gz
    ├── 492b1a908b0516d9fcfdcb7c76d230317304f500.nq.gz
    ├── 4ae301742b075a21d8e7bf77dfca4d47c8c8d613.nq.gz
    ├── 4ba6a1a051245c013af641fe814db6f0cf136a47.nq.gz
    ├── 4e74b2cea6b5d426165047032efb66338e68e18d.nq.gz
    ├── 4ff2e0d0f8cab09f0df62ec7f0028a34dc8503e0.nq.gz
    ├── 5098bfaed67c7b8687c1a2801664ade33284b99e.nq.gz
    ├── 51297a17840233c9c4b410bdd8b8da076b365f42.nq.gz
    ├── 519a0b177fd9b200fda4aa0ca273e3c0a9476382.nq.gz
    ├── 51b9e02599a1b701363fbff1933d6e526f897e2d.nq.gz
    ├── 5214e66b7d80eb0bfaf488aab4ef6eecc7c84c6a.nq.gz
    ├── 522557e47e0c2ed623affa24b104ee44a6559429.nq.gz
    ├── 524f23e661dd93fcf769e593de26befae8fb8789.nq.gz
    ├── 54de8d75f3bbd66c28ac6902603ea01a805f763f.nq.gz
    ├── 550519878d5f6c105699007886f539b98d76a7f6.nq.gz
    ├── 5539d0d26e93e1a60dc4d79be2ece64169244e5f.nq.gz
    ├── 55a9c45f7dff4ad8858e03cea72dc3b928ed5252.nq.gz
    ├── 576af9a28224fab50a16d6b0d8a3c5e2cba81a5f.nq.gz
    ├── 58794bf901d14865f1bea39ec1ee7a91c61a65a2.nq.gz
    ├── 59a68838c77f0880b8a214990cf82484c65b7aa5.nq.gz
    ├── 59c0d7b1ebcb2e851a28ee8d705f05d33307598b.nq.gz
    ├── 5a92497748d3a86cea6574cd31ad84e94ec41f73.nq.gz
    ├── 5c657ab7696eab62c299766e6b32fbee2044525a.nq.gz
    ├── 5dac463df3458187cb832a184c96b8b7d1683607.nq.gz
    ├── 5dc7a3366c16f25a4a4955b5d47b9952106eb287.nq.gz
    ├── 5fa00496dcc88aeb9f229d0d25d46e4f97588bd9.nq.gz
    ├── 61098c948c7aea60129695373683ed9c803bf469.nq.gz
    ├── 618439d1af69be30e5529151037f84f23f463855.nq.gz
    ├── 625120d9f23f9404a474b8dd25b1e3bc390012ab.nq.gz
    ├── 630a9a3f7b2fe5c97f107986504f8e43a76625bd.nq.gz
    ├── 655257aae8de5d1f7129126110a6586b15688164.nq.gz
    ├── 65645bc48d927b2fe16dc66e8c811e8138843543.nq.gz
    ├── 6581b56a2c70722e2f3f3aa051c257a5671b82db.nq.gz
    ├── 6689d8f9ab02191dda1d0985e19cbb99eeff9de3.nq.gz
    ├── 67fd3d9f72914748eba86e56cf2382d187b46a35.nq.gz
    ├── 682c6257df4c83903dece1c1e15dee4632332482.nq.gz
    ├── 6893ac2a5b5ed7593e1e00e3163d65bc21799ea5.nq.gz
    ├── 68a818eba71f6a2341b7f3a4e8db062b4fb9c447.nq.gz
    ├── 68f6b3678e49e35cb72fd6e18f12113a53ecc964.nq.gz
    ├── 6968ec4d7ea3ec1cf880a364735a8499d31ad240.nq.gz
    ├── 6ab1ebffa70e3c7c678b08dd7838dd41d6198953.nq.gz
    ├── 6b00966312a91c03f034bc9df4ae40c1cceb4bf3.nq.gz
    ├── 6d4d647507f2681f83fdd4114952525a94645680.nq.gz
    ├── 6da1fef307ee446e4927caec2d4796316ffe77e8.nq.gz
    ├── 6f18d70a73175c8d2051a3776dfddc6d15fe64d1.nq.gz
    ├── 6f484b52f105e570e48fe9900634687678497f84.nq.gz
    ├── 703a8084c0915d4c155f673754568749161255d6.nq.gz
    ├── 7164bfac2b66811bd192ed957129399822c8901d.nq.gz
    ├── 72735ed1744a9e6f2d833fd9681024e5550212a2.nq.gz
    ├── 7300d416fd133e8d65613943c98ee9c4b15eca67.nq.gz
    ├── 745f0b37d30f668ce32a022a434944f8586d06e5.nq.gz
    ├── 752fbae057f1f39585796aed66a72f412ec1f45c.nq.gz
    ├── 75353535c66e2a67bdd6c30cbc9d20e1016a0258.nq.gz
    ├── 75ccc6f45bb178deac643b070be73b0f76920bec.nq.gz
    ├── 76356b3892aded65dc1d2418d94575f5c90848c6.nq.gz
    ├── 77dc699ebe6482ce864cd668b2f55cae6e675343.nq.gz
    ├── 78b2279a76a4b3475e18019b5af90bcdda3528f1.nq.gz
    ├── 7dde9b70dbcaf7d9e4975e840b556c799257e7c0.nq.gz
    ├── 7e4cda828ba9d891d6350ddb7ab6aea628a1f544.nq.gz
    ├── 8047d820bf86e51eee26013c7d4d45fe0acfccf9.nq.gz
    ├── 806f52de38be5d5a4f0e97e604102d6ba8ec3032.nq.gz
    ├── 80abc14c8ae40d807172f89b6ea86ec310b6c6ae.nq.gz
    ├── 80b0f5ff60cd91d8fa7989599c1c5333c03b98b5.nq.gz
    ├── 818594bb99e5c13b0434b89ec47a6ea016999245.nq.gz
    ├── 81ad38c667dfcbcf8945e965c3f6884357b7860d.nq.gz
    ├── 8258af8660c936af5bcb8e9e45995e59e1126edb.nq.gz
    ├── 83178b259145e3e13fff8b06e0f5deeede69ceb0.nq.gz
    ├── 84300bbbfa7bdd3bf4f29621125ca00445e4160f.nq.gz
    ├── 854a168b7ef601a32fcf00936e97c17f0b8f03f7.nq.gz
    ├── 85fa5f818eef7864348998a70ec73c59f846eb4f.nq.gz
    ├── 86871c5b91cfe4403d436ddc8667b6e77ebc868f.nq.gz
    ├── 86d188bebd0c33d1ea6181c72bbcf141f33e51e1.nq.gz
    ├── 885185cf3df83a0196e2fffa15220268fc08446e.nq.gz
    ├── 88b5895fc0b02e9e84ef3af8151efa0457e906ab.nq.gz
    ├── 892cec762df1ba97c3ff0dcab5c666653bdee639.nq.gz
    ├── 89efe56a5c0f81726822520bb5b570e68b14b1ed.nq.gz
    ├── 8a319c6fe6db5d8bd261c632a9a737a547a89f63.nq.gz
    ├── 8a32c3e8aedbb62c97112686f9971bd5ffbcbd8b.nq.gz
    ├── 8a36fe2a8575ebcc662de0f49489c63f0cfdd094.nq.gz
    ├── 8b7b91556b9a39f3cf8626ca74d13b1029578132.nq.gz
    ├── 8e225e82cbaf2ba8d5296c89f73a50956171ec19.nq.gz
    ├── 8e455fdde8fbef11f9bf21d6a028df23b7ba59b6.nq.gz
    ├── 8e7e974bb9290ecec67b1109e3f31233420a2723.nq.gz
    ├── 8f66ee37a67f0881cbe825052bc888b4bed589ac.nq.gz
    ├── 8feebece79f70206162fcee5440775ea0972dc4b.nq.gz
    ├── 90580ebc70b957c8e6e127d6288de73e9b09b296.nq.gz
    ├── 90d0750ce973f39d9f77961bb384a6d74b30ba09.nq.gz
    ├── 9154dc1b194c02264839548c0ab049b2b26d9614.nq.gz
    ├── 91bc1da24e4f0c7ee3d8b703214994d4bde37bce.nq.gz
    ├── 9253260c44ffe31b760e58d103bb839d5c56e48c.nq.gz
    ├── 92af24a54f553a73364a825b2ca9ce52baca95a0.nq.gz
    ├── 92b1ef55162617968900794b78a549a950bb24bb.nq.gz
    ├── 937e53acfb590d8e53a7db761b17f0b83d96e697.nq.gz
    ├── 947a9530e2074a89d0b141b63dad0503e4d7ea4d.nq.gz
    ├── 9490e868a2df1175047ef7b0e9966a09d6e7cb44.nq.gz
    ├── 95f303907307ba250d6bbaf1a3683594ea079a27.nq.gz
    ├── 960adf70156fd4424cd12b539354c6c46dcc199b.nq.gz
    ├── 96d9c08d15b97ee5f8ab008f36b024946a91bff1.nq.gz
    ├── 977d24ec922c57f5d94ca847320b1701bf62a721.nq.gz
    ├── 97ee92c961852aa39181d6af785c417cb811aa66.nq.gz
    ├── 9911300c09ad45c5627442f4670822978a5cedca.nq.gz
    ├── 9922bc2dced677381cf7cd152c07aba924e3fbdb.nq.gz
    ├── 998913db3f472ed7f833f871363f6b5758422a79.nq.gz
    ├── 99bdae92244126a66d3156b1b618c03968a46970.nq.gz
    ├── 9a2aeb7a6696be4431b986ce574f0d9dee3dcb4d.nq.gz
    ├── 9b26de010054dd58f6f768e9219bf4868ea21317.nq.gz
    ├── 9bb51d91f69d7b8ecc0f8909f95ed548f0c40821.nq.gz
    ├── 9c9eb9e3e3a5c9f3570e170a42606f507a8ac43f.nq.gz
    ├── 9dfed50d530e2cf718bdc211ac7568b898b320a1.nq.gz
    ├── 9e036c6b112ec83e03f73caf281cad4fd1674c7b.nq.gz
    ├── 9ee03ce5b3c33cb5ffe040379e1de05eb91c82c9.nq.gz
    ├── 9fac3aba38f9158e50fa25e2d1a3f67cd3a616c5.nq.gz
    ├── 9ff4d258b8758efce4dc46c8ab8ac3e8de31d29c.nq.gz
    ├── a029d3a53a875a2ee2a2585cb08c6311324fc13d.nq.gz
    ├── a17c87d59e3e508f1b4a970cf07f028a6557f84b.nq.gz
    └── a3121c4ec39b976195aa773ca07f704054dd6b09.nq.gz

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

[pola-rs/polars-benchmark](https://github.com/pola-rs/polars-benchmark)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
