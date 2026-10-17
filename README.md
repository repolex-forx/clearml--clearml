# Repolex Knowledge Graph of clearml/clearml

RDF knowledge graph data for [clearml/clearml](https://github.com/clearml/clearml), parsed by [repolex](https://repolex.ai).

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
rlex download clearml/clearml
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8738571cdce186ec43d1ab14de385f03ec1999f3
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 8738571cdce186ec43d1ab14de385f03ec1999f3
│           └── chunk-001.nq.gz
└── blob
    ├── 004f747ea3fa2c57fe477a701daa1d47ae27b6dc.nq.gz
    ├── 00c5424c821c40be3b9a01f18f7f5ed42cb1bfbb.nq.gz
    ├── 01582b241a46bf814bf3d95209c265a56d05760a.nq.gz
    ├── 025ab8fb5ab95b576ae3cd08e7339bd9fa777099.nq.gz
    ├── 026c4de5ef6ab63a8b8874bdb17600275ec331c8.nq.gz
    ├── 02eccd678fb0e7794ba289384394a0996a7a8656.nq.gz
    ├── 03403b383fab5709fc4a1b75e78737221c206043.nq.gz
    ├── 036a90dd540aadd0169ff8cc016aee9abb677ff3.nq.gz
    ├── 039c00b76ce28cae26709fb7302261be34670851.nq.gz
    ├── 0489e1381e61d22228f3f722f7b533268f04d056.nq.gz
    ├── 05566ff34455293f3cfba257ddff64b779660ad8.nq.gz
    ├── 05c2fbcb402d7a2ad644dc6c58111671d9c97d2f.nq.gz
    ├── 06d9ec80f5c14d030b5f9f741ac476ea769e593b.nq.gz
    ├── 0768a79c7a91af8643bdf7faf61ae15c9e5b4f5d.nq.gz
    ├── 07bc089997af394c6055534f329e1a9694fd4c47.nq.gz
    ├── 0852aaebe19ccc8a7d114427c0e33739de5a1d36.nq.gz
    ├── 088b377c78e0df1e1912ca9b307ce8564d09c240.nq.gz
    ├── 08e385e0621a169fbe79975ffae959d058464573.nq.gz
    ├── 09f7f5034523636937483293a3645fa635ae07eb.nq.gz
    ├── 0a305c46ce89ee6fa86d4acfaae592ebe68b392d.nq.gz
    ├── 0a51676de791414c864a4366ff734f7233068b63.nq.gz
    ├── 0a6b37f94e8b539c5a3bd945a8d9b5456a12669b.nq.gz
    ├── 0b0653b07e188d337cd29f4500581379d75a518c.nq.gz
    ├── 0cb0e5854d4be391d39cac52d61a43c60f514aa0.nq.gz
    ├── 0d7fb2e2bb694b1836b525193e8949d853ddbf34.nq.gz
    ├── 0eeca2db3644200e8dffdba86a41fb74c7699a32.nq.gz
    ├── 10a9a5eaf123ef384a58fe6337f9538ed6535d7b.nq.gz
    ├── 10be830ee07db069fd59916f45712e5a0e57b294.nq.gz
    ├── 11ff5639956b7ab46c3b4614340c98d7ece7a6b9.nq.gz
    ├── 13274659a7b48f0f9e87a2628d06a479f61fcb2a.nq.gz
    ├── 13a992caa52ba708ed4c9098639a2c16d6f70cfb.nq.gz
    ├── 13b353fd7f9fc12cad09c2fb579735b2462988d7.nq.gz
    ├── 13c87789a80c86d07a57ff3660d23d787fc593b3.nq.gz
    ├── 1458ff5085c0dc90243b4211afb6d41803d7dbec.nq.gz
    ├── 15136fe1429ac4c8b517be1b6de0666ce89a5f5b.nq.gz
    ├── 163080ebd8e32bbbd22edbdc521ff61da9d64806.nq.gz
    ├── 1698d2931ff06bedd50d62a3cd524f833518ffa5.nq.gz
    ├── 1783bde8792f299888f29eed72fc3f2c59cba757.nq.gz
    ├── 17963607fe81d7a2550f00512468465354d9e1cd.nq.gz
    ├── 17bb3ce47c6cea3fb7302eed3dab948dcc24b48a.nq.gz
    ├── 17fc270f14470c21e8ba1d42c2f28f81ea905769.nq.gz
    ├── 181a2ba31a6ea533ec36783770951b57d73e5662.nq.gz
    ├── 187db785ac080ca87617923a75f3ae45080a154f.nq.gz
    ├── 18d23aa412e11380a3836c19b29391a1535915f4.nq.gz
    ├── 18d8800997b961b74801902f6d89c3883f045153.nq.gz
    ├── 18dae872ec8aff1f4c93e7f78ecd8d07cf2079f3.nq.gz
    ├── 193a5a9e62dbca89ce4e722068a6f240f7c335e9.nq.gz
    ├── 19b418d531d1631a08e5c18ae727bd7b87c9dd9a.nq.gz
    ├── 1c12acd441c0a2e227e150e0892f81c4f1fc856c.nq.gz
    ├── 1c920d157aa1def36bfd8c9f0862512180c2bc79.nq.gz
    ├── 1c990e00e62b1003c98f1b78f0881252752068d4.nq.gz
    ├── 1cca137483f8e4d39aa1266e8ebe6d5d77e9b8cb.nq.gz
    ├── 1cd570714684af56923a21cc39ab2b2ab50646af.nq.gz
    ├── 1d15aae5b50dc47bbc10daaeaad9290008cb9208.nq.gz
    ├── 1d317f8d0541d3c5990a6453426a96256a8f8625.nq.gz
    ├── 1d51f663bdb0da938956121c2b7326c915c25afe.nq.gz
    ├── 1d944898ab7cc3150ba5b41e674552ff7db2d9c1.nq.gz
    ├── 1e06be6ba1734aa9c434b7f3b391acf4ee5e65bf.nq.gz
    ├── 1e2be48cc095a5daab9c0db7832597c49f2fe6ed.nq.gz
    ├── 1e4f1a2ae9eab71fd0f0085444a9e2af7a36e95a.nq.gz
    ├── 1e8d751928284f1df0df841a807e1b1e8839affe.nq.gz
    ├── 1f1512e468e5af58819460ad86b1af78a129d25a.nq.gz
    ├── 1fb6918f0f9fc6decf471f21fbcdd19cd1e0ff25.nq.gz
    ├── 2000caab4d735c2d6a39ecfec9f17df163991c9c.nq.gz
    ├── 20143be98ddff1e9e749f244f36a25c5e879a3ef.nq.gz
    ├── 209988ce1598fb8b81083364e126b4319e3a8fcf.nq.gz
    ├── 21896433b4cf2ee13ea6a06dea6cdc28d964288f.nq.gz
    ├── 22ef1de8a1aaf0986157b3f277d5242ae09d5c19.nq.gz
    ├── 239610f96b1a0d7aa7ec2fd39e0765cf7bb37e8f.nq.gz
    ├── 247b7e1c7f78e84f0a409b28c215265330bb2921.nq.gz
    ├── 24da5c5b45c0596c353665936345904c17923496.nq.gz
    ├── 2577c5358c7b9e4426f19f280bb61d0512ea07a8.nq.gz
    ├── 257b48944e6827610c2e580d35e3d8d75e1f9a30.nq.gz
    ├── 25cc12dcd36949f4fe5833be078e3b4a31c4141a.nq.gz
    ├── 25ecb239ea5c7714769ff7ec54cbd0b780ab474b.nq.gz
    ├── 26218bce48832b15017598ad64af0d024393d1dc.nq.gz
    ├── 2652067a8f1c98c5765d99092c42d1279be8a17d.nq.gz
    ├── 26cc84a473ccd25d7149e63db283129686e066c3.nq.gz
    ├── 26d5227e89cf736e655b8ffd86e8bec8c3033dfd.nq.gz
    ├── 270fd2339be9c3729baa41d59a22263d25c27575.nq.gz
    ├── 2890aa070bc1a52ba1fb312af23b89172094c471.nq.gz
    ├── 28e83826812d620a2e0ba356bb8d19a26a4b3d9f.nq.gz
    ├── 29bbaf46181c4ef2e2ffba2bcbb0247ba7f63d07.nq.gz
    ├── 29d44c7ec809015fbab68876fc11fe33722ae1c9.nq.gz
    ├── 2a0d1c46d7bb47c262a6cb30b100f7300512dbb0.nq.gz
    ├── 2a8a836daf26876dbe6b85a7f903d6f253af8c05.nq.gz
    ├── 2c28dd3e7aa81564cd9fbb04e34dfdc826ce7e2e.nq.gz
    ├── 2c49ecdd3d83e898aa955282f0221f3b99cb1514.nq.gz
    ├── 2ceb085b1f650b18e7b306cbf607a8aab73489ce.nq.gz
    ├── 2e1c9e8212ee4ed359e62af2cc181a7ab67466ff.nq.gz
    ├── 2f2734c14ad0f83ae2f8647e513e1405362bcc68.nq.gz
    ├── 2f88d79c2116879fadf8aa0a4b65e6296b41aaee.nq.gz
    ├── 2facdbbbfb5f1182b5f74d33ab10dfce34694b58.nq.gz
    ├── 2fc4c9fc972404a2a873720e4196b77b8a86b81f.nq.gz
    ├── 306e66136432ff154c86a25482e7c4003f5943be.nq.gz
    ├── 3092afeccf57cff6ffbc13e89160a244786004a6.nq.gz
    ├── 31142b6efa9260fe2603b477f78ceb62d3e2aa75.nq.gz
    ├── 3177a89d2343c75abdc87409f560c6437469a7a9.nq.gz
    ├── 31fe6050312369297789f08382bbc84cf8e75404.nq.gz
    ├── 320745cbc16e869ae2e9e166ef5e4fc535b125d2.nq.gz
    ├── 3320a97720a970450011834dfca4d1cac9b76484.nq.gz
    ├── 33932d22a7e9e939b960c7ac8149d8b639632ae7.nq.gz
    ├── 343346a29686c23fd085af2c49af870077325f0f.nq.gz
    ├── 34bb35d320d2be99111fb61a0c1adc3b74526f5b.nq.gz
    ├── 35c6bf010fd45abfc99b80908641c9ab68124672.nq.gz
    ├── 35ded08213c03c421c20e6c550d479fd392adcc5.nq.gz
    ├── 35f15f062ddca0bc96fe2fcfe2cb94d0734fc98b.nq.gz
    ├── 385981434965ab90079c1fc68d9cb35cc0425f4b.nq.gz
    ├── 3923a1e1dd23274ae82b923524a873bf5088b00c.nq.gz
    ├── 3aeab809e48279a19de7bbcaa3210e422e5c7880.nq.gz
    ├── 3afe34d5a469aaf50a237102d038c75468ce8477.nq.gz
    ├── 3b1cf5bd81907449825ed9a8f855f63c61bfc100.nq.gz
    ├── 3b2213e3c5de7129461c5fba0764c9366d7fb136.nq.gz
    ├── 3c3ef0cec9681b4a267d5734a9168749cc0dd510.nq.gz
    ├── 3c6e79cf31da1c0433d2fa666bf50b53f6359f26.nq.gz
    ├── 3d8a11dbe2b322c2bb5938bab862f4b544770cee.nq.gz
    ├── 3dc77c27b404c781d7aa2ee4eb5694ea415e1128.nq.gz
    ├── 3dca0dcd09a09597d2f4f124e269e22141e71634.nq.gz
    ├── 3e0cbf7f6dab088a9a1bb4e223ac5176803e5784.nq.gz
    ├── 3e4628ec5ca68f12794f99637a729ac5a7f5744a.nq.gz
    ├── 3e4f1dbcdd2b8de4fb43bfb73dd6b88feaa9c193.nq.gz
    ├── 3eea0741e3a9d22b520273c696f24b7537063f5f.nq.gz
    ├── 3f741f2e3814112caea5a45532fd45afc27b542e.nq.gz
    ├── 3f814eb4a9ee64990a28a4c96c373480cd52143d.nq.gz
    ├── 40a96afc6ff09d58a702b76e3f7dd412fe975e26.nq.gz
    ├── 4254d8ac84a4045b32217cc464d59b41c947a5eb.nq.gz
    ├── 4391a4a2e008ec403c258661be3a4f59039c0354.nq.gz
    ├── 43c6b0b9dd2d769b6e9719c26602f56df911b79b.nq.gz
    ├── 45580a053d37ce0c60a3b9684c60c20a658dcf1f.nq.gz
    ├── 45aed1663796e01e9217b7e59db2fb5b0d35011f.nq.gz
    ├── 46178fa279c17abe66d6fd96713ed1fa07b663a2.nq.gz
    ├── 462cb04bafca0a6fc1f2997fb7e1826265797e42.nq.gz
    ├── 4682a0e30d1eb9a97380fc3ea5ae216873f92d3f.nq.gz
    ├── 4745c9c8b642057c91a678763b5454fbd4acc078.nq.gz
    ├── 47cd8eabc6fcb45f2d0fa8fc4728a84d1ddaf536.nq.gz
    ├── 47fc59d5898397cb1590d40d5acf94f812f801b5.nq.gz
    ├── 48677093c8811344ad41368aaaaef30ef84728c9.nq.gz
    ├── 494f01669521d94422f414c04d33c24b54fd7a38.nq.gz
    ├── 4bb9da7e26a3702c7da783540c84c813ea743a10.nq.gz
    ├── 4c26dc63bcf7330dcdaf1c174ae1f6daf02c3ad5.nq.gz
    ├── 4c8c2e70323dd3be65274e0df5e8ce6d093d8b13.nq.gz
    ├── 4d34fd86b76fc90cc31587924a5468220476d4ec.nq.gz
    ├── 4e57e0e61db846cf9e6a9daab78a31982dfc8d17.nq.gz
    ├── 4f1b1df197c9b434261349615c860518f419c585.nq.gz
    ├── 4f63e8873a7247aedf78884b29dfc1e8e968d009.nq.gz
    ├── 4fccc6db688c62a033c76fdc279211ebadb0f03d.nq.gz
    ├── 500ffc216f89c44bec524112dc93e88f7dcf1468.nq.gz
    ├── 5035609b04960336648b7ebaae2f481b2f000957.nq.gz
    ├── 5066e3427fe86c14758b9754af9911347de48a4b.nq.gz
    ├── 50dfeb3909d9652130ada912d66d56bbce0e8a37.nq.gz
    ├── 51567212ed31925316f0b4b3c4abe833424f673d.nq.gz
    ├── 51f9f7e8395133124b10f7537c1dc91970b6b853.nq.gz
    ├── 5220d0a245c579cc81ea7e96803b755dde50d0aa.nq.gz
    ├── 52de4877d9b0ebd1008ef26b5c1b9914359a0082.nq.gz
    ├── 52df038b20e4ca54154bc48fb01cd885b26b2ad7.nq.gz
    ├── 536e2368a1a4c7aefd88867c8efe3a430dfc2b64.nq.gz
    ├── 53870ec344760411fdffb70cd5cfe694748541e8.nq.gz
    ├── 53b722a8801bf16f427a5118c2e99739b294bea6.nq.gz
    ├── 541d49c44fea06254529b1637c87215f50cd3eda.nq.gz
    ├── 54224faa31baf26d9fde209a1dda2b414be13ae4.nq.gz
    ├── 54c6af795be7fcea2c25399c2d5a2cbe4f057206.nq.gz
    ├── 54cb7615a37f3d8d79b5cde3a416a9c0df79dc9f.nq.gz
    ├── 5521493dcad326487c3f347e33d029cc606471a4.nq.gz
    ├── 5578c08e54d6ddf26e4731d13e42896bc9e45b0b.nq.gz
    ├── 55e6f352c2a189ba3faaf2c37ce5bd86490bd038.nq.gz
    ├── 5632ea770d4bb2b1eb6105018688edfed5509e21.nq.gz
    ├── 5660b926077f42ed4eba9a892954aa51f1f50681.nq.gz
    ├── 56bf1ae35b84a9ce37f7c92d3c5a3d786a157684.nq.gz
    ├── 56eb7ff2c7f937a0228aa3b4627cb5d6129b2fe9.nq.gz
    ├── 570179c850455a0fbcc7932bf6ea41c7cbd96130.nq.gz
    ├── 5727f12354a46093e5ed98edfd3e3611e0b7b346.nq.gz
    ├── 5834fdc5c4116cb6f2f55a72a620169f2751c478.nq.gz
    ├── 599d60c3b8d4d479decccd7c25372a320db61fab.nq.gz
    ├── 5a3551e5212e9e327b09dd668e11870cc058b51b.nq.gz
    ├── 5aa6dab5968d47fcfb4d309151cf944380d5e60d.nq.gz
    ├── 5acefbb939b1d9a775af41f2d3e21b4f6225901d.nq.gz
    ├── 5aec21a2cc748d79e6761946dfd58af205aa9702.nq.gz
    ├── 5b305a34e7576f278b30c7d6ba9444eb7bc4b100.nq.gz
    ├── 5b3324e9fc9686f9a64d47ed01fa872befa90d1b.nq.gz
    ├── 5b34ccbda4b65b0fd697a537534d18731d3b3013.nq.gz
    ├── 5b4194f2e5ac241a22b4907f7b6d05bd20ecb2cc.nq.gz
    ├── 5b6178b08b2517317460c9727e0127a71bfbc71f.nq.gz
    ├── 5ba12672ba3b997638c6ca2ee5324ae03197309d.nq.gz
    ├── 5c3d693fda70b14dd8e92cf68029e255b864d824.nq.gz
    ├── 5c502681dc9f4517749679d04570f3c8c0199bde.nq.gz
    ├── 5c7f7b56f177687285811573ad92061a7559797c.nq.gz
    ├── 5d0eafe3619c558505dc83bffed4af79abdc4d82.nq.gz
    ├── 5e4a112fe5149e716b05d2fb26c808c2310a0d97.nq.gz
    ├── 5f1100ebaf1369d211c0f9f07d033244f0b0de23.nq.gz
    ├── 5f24564013bacf9daf9de5dd1d960701436c4228.nq.gz
    ├── 5fe15cd9fd5e28bcfa17d071a5faa81bc842b6e7.nq.gz
    ├── 6034668828fa3a81833145dcf4b529df75927eb7.nq.gz
    ├── 6134f74a25469e6587a6f469fa39668e3cde2a47.nq.gz
    ├── 614e65ea14217a68726185146b8b3b372239b43b.nq.gz
    ├── 619f06e0ba5824d9127b026517194616fbfa2641.nq.gz
    ├── 623efd403bea61f1b99271bb5d48fd006d3f370c.nq.gz
    └── 62ad5d2a2f6c404257bf4060641044fde8aea215.nq.gz

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

[clearml/clearml](https://github.com/clearml/clearml)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
