# Repolex Knowledge Graph of ansible-collections/servicenow.itsm

RDF knowledge graph data for [ansible-collections/servicenow.itsm](https://github.com/ansible-collections/servicenow.itsm), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/servicenow.itsm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d7d387abbde446c765acc1110c712fcd5c248f4d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d7d387abbde446c765acc1110c712fcd5c248f4d
│           └── chunk-001.nq.gz
└── blob
    ├── 0102b0a974ec49314140d79ae6e34f30b6cb4def.nq.gz
    ├── 0189029c708604871407366a1fb8e7d8b37a57ac.nq.gz
    ├── 03456930ec91b909c7dbff953f9b78bc17e5c94c.nq.gz
    ├── 035329f36f43c1a92a202f078428cfcbee55c818.nq.gz
    ├── 072b4225a059e8c24228facd6255bceedea1b2b3.nq.gz
    ├── 08087d8b7c9b25f95c1195c0e2dfe81e8b4a51ed.nq.gz
    ├── 09576ae10234f6ed8a910ea81c56ccce3f7475af.nq.gz
    ├── 0996994d3662b1df234bd3dc8aa9470abca1f6cf.nq.gz
    ├── 09fb9209cd6401ebe2164cf7ff4fb8ead03ecf2d.nq.gz
    ├── 0a3f1f30339937213787298f715f16a30777597e.nq.gz
    ├── 0b4c829d8e07965c9d868abef8034be56434eb42.nq.gz
    ├── 0b75367a772ba34b1c154a2907fefd3114e2033c.nq.gz
    ├── 0bb6dadd6ae12f488dc3bc3cd4a21f02adfbd50a.nq.gz
    ├── 0c910445782c4d10f04caa2d2de2e1f66d4885f0.nq.gz
    ├── 0cb661dad46bc742672992ce4c7483ebb5b24136.nq.gz
    ├── 0f439897d1574cd290d06102b7c53e0c2f865667.nq.gz
    ├── 0f88d9a067dcefc3e33f2a66239de72b217bb3c9.nq.gz
    ├── 0ff3609872740681b503e27014c5e1858d1a1819.nq.gz
    ├── 10926e87f113fb026c366866d6fa466061562870.nq.gz
    ├── 1147e2c347d5e56552f9dd3e71b78756c8fcd47e.nq.gz
    ├── 120c3c8537497ab72374238ac3da9e9e159b7210.nq.gz
    ├── 12a64fa920561dfbbe3b69976c3e521d9d2e6017.nq.gz
    ├── 13de11e80c3de2f94c1b1339be06cc5933e70bdd.nq.gz
    ├── 14e1b85cd7b2b14e5f10049bec218f3a0fbd5954.nq.gz
    ├── 17c805d3bb05afc3c0be874061f81729b90ee969.nq.gz
    ├── 19377e3c8c9008ffce86d8063f0127d71e07e12e.nq.gz
    ├── 19fc7dd7d326b1261d5f8751946ae684e509b0f5.nq.gz
    ├── 1a143b69c8de9101d10941c623e629e63b990277.nq.gz
    ├── 1a2f16145b57070268ab1f1d77fd572049f2c500.nq.gz
    ├── 1ac8db71c90629365dcd3f419c206bdfb02e6c9e.nq.gz
    ├── 1b2d68173a5247c097d0dfe0fe044b52aac7d210.nq.gz
    ├── 1d8f464f993bbdadccd8024c8e5dfeee68e6d38a.nq.gz
    ├── 1dc8ee137e81fb14d1db847ba4835f263c3ea013.nq.gz
    ├── 1fad4a42604b45334f8789286443a0809457dfda.nq.gz
    ├── 1fea1d75fd32f8c649d4e4081c3268035d2206ec.nq.gz
    ├── 2041d021be3ada842530e513882fe0b66c7d4a53.nq.gz
    ├── 2130840f26b776bc2082f87e25947e5fe9e50760.nq.gz
    ├── 276eef8fbdd1aa90432e652411920612957283eb.nq.gz
    ├── 27b074ea536bac9fd1a9baea41bb76f8432920a6.nq.gz
    ├── 2a1a6b122ecc5dff99ca1d81340d4eba64478851.nq.gz
    ├── 2a2f8925e46c9579d032153beb9980be85e80ab2.nq.gz
    ├── 2a7b339c7b5abcdeaeb1a9a232ea83c16b3bfb5a.nq.gz
    ├── 2cdf72b28e4fa2dbf779a394c2e0bbc255168247.nq.gz
    ├── 2cfff883aa6e95a5ea75a7e65e661250da761773.nq.gz
    ├── 2d2705af3be82f0c9d21d40f5dbf96cdaa16b42f.nq.gz
    ├── 2d394e8fe1003dc78607b9a467cc9517daa119ab.nq.gz
    ├── 2d3d5caf6524dc82e374894337a85603e65d5c96.nq.gz
    ├── 2f3f4eb9d88407fbcdf19fb28bfa481095a5e59c.nq.gz
    ├── 2ffc7832f59adcb4b8ba5c9c35bb7e2f6bf15321.nq.gz
    ├── 31665730813967b958bc080696cbfe617d1cf152.nq.gz
    ├── 31d59ac806c4c6fdb0f317e448eb0694b07aacc2.nq.gz
    ├── 31d7885ccac987a7b0cc305eb1c3c5ddc9d2039d.nq.gz
    ├── 34416dff2bac5b421e1f6ac49ce4b0704c3080fb.nq.gz
    ├── 3561600acef2409c8f4164b3a487810e2c5427ed.nq.gz
    ├── 35b49b3a29a37fce8e848c435375dcca950c6709.nq.gz
    ├── 36a9a9eec751c924aa16c51466475af3a38e6663.nq.gz
    ├── 379dea90a09fcad34ee0db32df850eacabea4410.nq.gz
    ├── 38a4a78de0b1db321b81cd326c291b7330b86d32.nq.gz
    ├── 38dcf85aced4e7921c30041697982264b51eb4d6.nq.gz
    ├── 392dcc2d2096218c97d376288da06c5bb038c457.nq.gz
    ├── 39a36666b1bada0f038499ed68ae1a934aa91136.nq.gz
    ├── 3b10f5400ddc64fdeb4a1dc1bddf327bf2a56cb5.nq.gz
    ├── 3b803a545af808834818dc5d38aebe3e3fcb05a4.nq.gz
    ├── 3cc479c64f7395303053544980a64a81e1f0f5ed.nq.gz
    ├── 3d24fc80243814b9780877c7448af5a6d80b8a90.nq.gz
    ├── 3e7b29b897aa4b3884f71c91604ebf5923781773.nq.gz
    ├── 3ef14a3c8ccd1afd48277eb1f6361ed1bf1c199e.nq.gz
    ├── 403b2d575a42185faed294aa645ac61566c98297.nq.gz
    ├── 40be261ffc6488196c0f68f3643441941944b88d.nq.gz
    ├── 40e48c28c544d14776eb694679fc2aab213fe480.nq.gz
    ├── 448db0c8bdfd05efdabea9b53267317de915f61e.nq.gz
    ├── 456e2bd1ae680091ffe9494583f77d0945d31486.nq.gz
    ├── 4790f892a6f18bc8476419181da142fc786e7d3e.nq.gz
    ├── 480fe4834478ebb256c935d0e0c261a4156d4cd4.nq.gz
    ├── 4838eb56c26b762dcd30d8f35886af37d15e76c4.nq.gz
    ├── 4a6f0dd88a2af1aa93ccb27bd6c972b704bd9331.nq.gz
    ├── 4c3c6c5b34623c403c376df17828ab9bcb96452a.nq.gz
    ├── 4e39fb6a4e2f09eb85d88ed063e63e79c96ec85f.nq.gz
    ├── 4f3688c6b48b2bea2d44888600c778e05100e42f.nq.gz
    ├── 50501c523ab21cf3ad1c8db07cec560955092b1e.nq.gz
    ├── 5165b5e5447ff5c4cdcf3c7376cbdc2172c6f612.nq.gz
    ├── 51aca5a601d1da4bf3ebebe27f387da33917bdcc.nq.gz
    ├── 5250841c4d4bc7f12ca55cf8dc414af596ef957c.nq.gz
    ├── 5278f5cd4e9270c3f33f4b970dce8974953dfed4.nq.gz
    ├── 52a1b0e2e453730f27cf19a3e1060a6e1fb412f4.nq.gz
    ├── 5331e5c437735c56b9783bced7ba52b74d3eed60.nq.gz
    ├── 533bdcdf94115b142d4be1e05add762578ff75e4.nq.gz
    ├── 5365376d3b6d9e7d67b190bc941c5040174c42b1.nq.gz
    ├── 5569980d061ea1fb3bfe88119dd47372385619f7.nq.gz
    ├── 55e755f65f0c138df26c1be9e21c0dbe228238b0.nq.gz
    ├── 5773e69b3094166114a753fdb059a7dfcaab03e9.nq.gz
    ├── 577a60acfc647e614eba75a6f7fa175b413cb18b.nq.gz
    ├── 592b91ffec07caa305f7dc648452d3822928fdf5.nq.gz
    ├── 59aad52ecb75287a42948b67c1d6e7c021e95e42.nq.gz
    ├── 59eb77a220d7e269a88e9f57567ff629529f7e1e.nq.gz
    ├── 5c909eaaf08c34ef39a40e8b77210a10fccf6ad2.nq.gz
    ├── 5ed079d8d484c32312f0790cc5365bbc8d7a6a59.nq.gz
    ├── 5f2282a496602456e8346654442c3eb0c1eb70ae.nq.gz
    ├── 5f56a4d8266573fb3fe31c9ec822c08923fe852d.nq.gz
    ├── 5f6f0641ccf9a266a48510e7040f7eaef00deb21.nq.gz
    ├── 602e3eb305430b77b2c44857c7039e6b777fc2a0.nq.gz
    ├── 6063f9f6aebd6cd227deb9bf16d3c20efb0a699e.nq.gz
    ├── 60db285eb86eee82debc79bdcac023ea9ad2c471.nq.gz
    ├── 60ddf7f16459f2643a0b66a8abadbbc46d04b3d7.nq.gz
    ├── 611c74370c88f01d031ea309a2343a043091a967.nq.gz
    ├── 613f6abc41c382bb4428da454468e75dffe95ac8.nq.gz
    ├── 64cbe048faf9b6f9435bc245d065a6c622744aba.nq.gz
    ├── 64cde36ef58c3e069967f8bb2a94cd38ef2d6867.nq.gz
    ├── 66d216754f4cc2afa5dae9472a795c279af09324.nq.gz
    ├── 68e02747fa9fd4762c21bfc41b7259b68b3f9ed2.nq.gz
    ├── 6a070831344ca44952a0da02af0a5b7dc013027d.nq.gz
    ├── 6c30572c09774a353e05ee7f47a0493a606abbbc.nq.gz
    ├── 6d2bb4448c7ee520974c9f90ea2aac30339124f9.nq.gz
    ├── 6ea796f386bde8c83e5b7ffe5e9267f9e9eb97cd.nq.gz
    ├── 6ec40934c994c7177a766f5d64be576aca5e7209.nq.gz
    ├── 6f40b54d4d5de8af088eee545b002430896e63fa.nq.gz
    ├── 6fe58ee724499ea6ea92024639e9fee62eaad086.nq.gz
    ├── 713f0c78539544dd07e00b479a2a721920ea4eda.nq.gz
    ├── 71a898562b000f47fab643b47fcabf67ac213332.nq.gz
    ├── 75c503c7c79bc454be4d4c95b00726e2a809a8ce.nq.gz
    ├── 7a0353022f81ff3796cd6dec08a6a3d2fe0a277f.nq.gz
    ├── 7c25324b2d364a620064167b39a9cbd50ee902bd.nq.gz
    ├── 7c9eeadceeffb4bad211d6ed46e621c5c014d429.nq.gz
    ├── 7dcc2feb624a33f568ce936f49f4540331c72dc5.nq.gz
    ├── 7ed679ca866bb49c73c4940bdb07d7cb6c341179.nq.gz
    ├── 7f9581c291cf05468ddc098a5b72bad0b6517aa1.nq.gz
    ├── 809c2fee8f06a3c944b102ccbb8020e121322892.nq.gz
    ├── 83671bf4962cb294f36d4e46110379944626edf2.nq.gz
    ├── 83875e147779f2aa7f05e3c70efd990b2963ea60.nq.gz
    ├── 840948dc5a9f42cf1f122c5e383dffe27a430012.nq.gz
    ├── 850ad3e45ad0494eb89c8f17adaae6a6282cf437.nq.gz
    ├── 85f7e9b1ff78fa30f01c25309f0e764f9ee5e247.nq.gz
    ├── 86471afc9fb1067dde9cdb8bcba8db51f60c8221.nq.gz
    ├── 86a0329ae4536cf35ab6e4db9f4baa88c92e5109.nq.gz
    ├── 875c7452c5b2cba537b170e925a03ac98a39d832.nq.gz
    ├── 8782377a2917f7b84e438be40194e832fb3a5295.nq.gz
    ├── 89ab2ed7fe1191aa12d3c0e9649af7986c4b3601.nq.gz
    ├── 8af40672fe01efbf924b15a1515fc8e7fe71e41a.nq.gz
    ├── 8bce3d8ff1b371e9b6900f02affa75ced4696142.nq.gz
    ├── 8bf75364c2f7977a515fdaaf827c7c175288a346.nq.gz
    ├── 8cc5cea85a911056c3319986f9d8b22026a8e7f1.nq.gz
    ├── 8dc974abe53a4657eec4334a3f85ea5ac0bad8d4.nq.gz
    ├── 8e917eec2d0627855a90aaa3756bf876584f4c02.nq.gz
    ├── 900df3257fa3d465ab9382b3bfbf2f2e5829dedc.nq.gz
    ├── 9275b1d915078b8c4e31666dd14e5dc2657eefc3.nq.gz
    ├── 92ce53cf4e9bd04d77cdeb1ffe2bc6e2c721ecba.nq.gz
    ├── 936041ffee3d3435bf3bfa8c904985daa97edf59.nq.gz
    ├── 94f047d1e32a2d769ee77108113727178867e4b0.nq.gz
    ├── 958cdac96dbfc3207aa3eeaa95c5337ea0dfd67d.nq.gz
    ├── 96d95eea8ca47b9c58bb9d610e2e2111785f8f6c.nq.gz
    ├── 9738088974f5309d554ce59af795db2f1ca79b3b.nq.gz
    ├── 99e462d5df32bb709179009fbc65aced38585127.nq.gz
    ├── 9ae3ae44bc33913579d0f8b9bafb595329b5dbff.nq.gz
    ├── 9b8c8902124381215b778bb9d3ac31f530a5d86f.nq.gz
    ├── 9c0c183b71f0c12abe5c5bb0dcca1f8e265a3c2a.nq.gz
    ├── 9f111a63c65310213bd447de08712e2a38e5fdd7.nq.gz
    ├── a02b197f866dc15c831a868638d9623a126a97ba.nq.gz
    ├── a0f93d5ec8d2c5a83b3faacd19af7a3840f74526.nq.gz
    ├── a1ee978d9d01fed0b2582aca91e23c7fc308af19.nq.gz
    ├── a2162eb38caa1b1810ebc9d07986877d947dccf8.nq.gz
    ├── a3a316b014d79c4a64c8baa9669505f9ded7ad51.nq.gz
    ├── a4a3983e1560599d81bbb40ba2da84a587134608.nq.gz
    ├── a819d0529d97d486ce6bbe0272cd6322f12a84de.nq.gz
    ├── a8c4367f75f4a6635176edbc16fe5c249e3e0b02.nq.gz
    ├── a97b01f5ab8101111c13ab779629350bdf9c8b9a.nq.gz
    ├── a9bcea29e4f3db6bea0a257405d8ba0d19e0b37f.nq.gz
    ├── a9d58af85eed019406e78461f9463bb3c9bba965.nq.gz
    ├── ab14c4246b6f5f949ceff6af6e71d015a2ddfc8b.nq.gz
    ├── ae0be6a10a4aa942f98d08b29bfa794e7ff1ceac.nq.gz
    ├── ae59791cee36b3a1e2e824ec09aca14c176e96c4.nq.gz
    ├── ae8f111a2f00b4ea5d074883ccfdc4b4634f5c5a.nq.gz
    ├── aef192f6024ed5420abfeda9a84d51f21b3a0816.nq.gz
    ├── af8eb264af5f3091b67bf0e8b8f28fa3d77a91d3.nq.gz
    ├── afe02e124c494bdd9bda7bf799f20747eec7752f.nq.gz
    ├── b08768e28505846934d974d72e8ef94c0aa4003c.nq.gz
    ├── b2e9208118fa034254d6a09b0fd56092a9905939.nq.gz
    ├── b35464fcf117bc15ff9d34c5959ef7590673189c.nq.gz
    ├── b8560378d2525ec499da9cf72d1b46f9ad6e86b6.nq.gz
    ├── b86e0e170730351386381221fb2034572693a2a2.nq.gz
    ├── b8e33db1307330caa2472a763b4610ab3444ca2f.nq.gz
    ├── b9b9ba188dbdf33e12eae03d28969d1e3786e920.nq.gz
    ├── be728492b7f8d14d1c1d09892705b3c509349e0a.nq.gz
    ├── bfef8c06eda188d532c96e0c5799f70a95395bc3.nq.gz
    ├── c055601a3ded18573f2b82e67fb80b0a129dc4f5.nq.gz
    ├── c05a339b88378e1d2196e48a9de03b9327a41a0f.nq.gz
    ├── c075fae0b9cb611b269f712131b64e1542941511.nq.gz
    ├── c07aa67d3db6d41e7babdac54010bf94da9a925a.nq.gz
    ├── c097f1158415ef9f33ad4bf6abe3976f7f920917.nq.gz
    ├── c0c464c812f70f36505e85a24036e52e66af370e.nq.gz
    ├── c18ba857db24d6e03bebe1f36afd732420bb10d3.nq.gz
    ├── c2b9a51a3c8757748fb31fa9e73c72a726549082.nq.gz
    ├── c2e34288c557edb1534f5cc42a166ba26310517b.nq.gz
    ├── c3e2ce1b01d54cb9f2c86cbc19d90c25f98aaf9c.nq.gz
    ├── c46d14606c12d0899fe99eabef2bb1a7872773bb.nq.gz
    ├── c4be6200ce24ec2bfd54237a799594bcc9ae5512.nq.gz
    ├── c50dfcc2809c49f7e0b394a9e4c978152b7d78e4.nq.gz
    ├── c5c36da13ae8adf6368a5848f89b0a3f0c8ac37a.nq.gz
    └── c732f93a0e4f58d07034a45d2b0361c0dcb27f4d.nq.gz

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

[ansible-collections/servicenow.itsm](https://github.com/ansible-collections/servicenow.itsm)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
