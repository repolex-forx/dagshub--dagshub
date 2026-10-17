# Repolex Knowledge Graph of dagshub/dagshub

RDF knowledge graph data for [dagshub/dagshub](https://github.com/dagshub/dagshub), parsed by [repolex](https://repolex.ai).

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
rlex download dagshub/dagshub
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4f7d78a828ad11013582c2653dbffb1da70b65f4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4f7d78a828ad11013582c2653dbffb1da70b65f4
│           └── chunk-001.nq.gz
├── blob
│   ├── 02ee833147c11994d0f1b78f74300ddfeba058e5.nq.gz
│   ├── 04f995f006e3fb22324c3e90e6080e068ceab50f.nq.gz
│   ├── 0938e81771c1a6fa9fdd1609405ed3b0ce55e44f.nq.gz
│   ├── 09642157ee5438ed8104484773a1c8ff298bc0d6.nq.gz
│   ├── 0db9cf8fe6113594c05c9ca64b4b8e6973879f9d.nq.gz
│   ├── 0e857ef4c83d46a13bfd260592e4441fd11578f4.nq.gz
│   ├── 106af313466e6820b2d905a75e786603baefbaa1.nq.gz
│   ├── 11dff8632432887efb91d34bb69eebfb857c0d38.nq.gz
│   ├── 123a429c293d1b2f5a42bbcc70b41f342c4d9c3e.nq.gz
│   ├── 131cdb97b599ce2b8092bc1969d687abe096ed6c.nq.gz
│   ├── 14e4cbd1f53c20fdffd4c2fcc1bfb06a1f2c17f3.nq.gz
│   ├── 16985a9a98ceaac54dee8a854fef72e2cbd0e7a8.nq.gz
│   ├── 182b4e4e94997cf1d0e37af5938431151cf1de7d.nq.gz
│   ├── 18ec25a648b6375cc8a3110837f7b6ce11a0b5b0.nq.gz
│   ├── 19b10ca2351e807877c1b730dc081693b077003a.nq.gz
│   ├── 1a430876c4a9c93cd2fcf076c9a708bc71533316.nq.gz
│   ├── 1bd0e7c1d049e5023dc6703d3ba8c9de8e3629e3.nq.gz
│   ├── 1bee40d2b98ab00812f37e6a7fb73c48b739706a.nq.gz
│   ├── 1c15cc5d8ae1ec77e8dca98afc6982311dbb1374.nq.gz
│   ├── 1d2c99436810f8a8e4daf4c6215c5a2d470d5a63.nq.gz
│   ├── 1d779e3a3b4413008e2d986bee143da983aecb43.nq.gz
│   ├── 1f6b3e36879a92a48d668f17a0fbd5c0e9ea5607.nq.gz
│   ├── 1f9294cbe6b31a88f18bf3db4793ed4cb7c417c0.nq.gz
│   ├── 22687edde088286de63b6e35e423524fccec483f.nq.gz
│   ├── 226d9a71dff4bc088ac2d876449048d40932acb5.nq.gz
│   ├── 22b6c94c2060cc0ec7f9ee3034f5f67167112931.nq.gz
│   ├── 234f8c99e6a2bcb0401a923478c2a5c2a9f3f217.nq.gz
│   ├── 23619dd08349bd43b46ec628832a8ec2e7042f8d.nq.gz
│   ├── 26357aa6a3e07bc0db1ea8ebfed581db6c710e7f.nq.gz
│   ├── 2b0a99174472112127d230568066e10c04fa6771.nq.gz
│   ├── 2b5dafa72f0840a143164e59548956c756b9f043.nq.gz
│   ├── 2cbc78921c2567a3e8d6b7ade64abd422f501b32.nq.gz
│   ├── 2d912649d6bed98e0e9e116a68e55ca5b1bdea62.nq.gz
│   ├── 2dfee24c2a85874eb7790512f1c95e0d35fe982a.nq.gz
│   ├── 2ea9c5a02ad3e309644100ef305088d3940e512f.nq.gz
│   ├── 2efb6a2147619056bd021b03db37207d2ee19858.nq.gz
│   ├── 301e30a6ee39ccd989bb5305cf6ba142c11c724b.nq.gz
│   ├── 329d2acd191c1903dc23ab1aa851d7f8f7726b44.nq.gz
│   ├── 33223263e156f28d3b2e41e6c23fd598dff3339f.nq.gz
│   ├── 350b9f0cb617a4504b423652684b9a4076917360.nq.gz
│   ├── 35331fe63e6c473693b7e0ed6647f2b9cd012adb.nq.gz
│   ├── 3877e8d1503dc570d7dbdd331edd3a54aabcd615.nq.gz
│   ├── 39e5ad75bebbe1517dc727a4250b6c1ed4a2dd0f.nq.gz
│   ├── 39fb6c303c803e4fd594644eeaa7a53597853726.nq.gz
│   ├── 3b6167d2ec836344e6b45645d57a9ea2eff1dffa.nq.gz
│   ├── 3c1519121c1b21e651d77aa0d8bf44328e58875e.nq.gz
│   ├── 3dac1c791300f3d9b5494c197832e990a08b88de.nq.gz
│   ├── 419407868f32b88bfb4bb934abd4f384a2d4761c.nq.gz
│   ├── 4b6f613c921d0fb2ab5d8922a02bafa626d11258.nq.gz
│   ├── 4bbc639db80d98f4e6fbbc2e358ac9abe8731e17.nq.gz
│   ├── 4c6fc8a895e6f5d18613a30954653b6a77259a76.nq.gz
│   ├── 4cc1a48e3c5b8778db7d68f15069aa42a25aa9e7.nq.gz
│   ├── 4f72851035acbe1f854cf5353b301edf9949e362.nq.gz
│   ├── 501e8e445c5714ba13135128ea71c16514fce723.nq.gz
│   ├── 502aa60efa3a66a4af5da2635034c85e0548d8da.nq.gz
│   ├── 516bbb506e643050a4f2a16a5fb46d09da20a189.nq.gz
│   ├── 55c3737fbb175030fdd25fd54853e4e453028c8e.nq.gz
│   ├── 55ec8d784c3cfc688c31cb32a4225e5f551937b8.nq.gz
│   ├── 5702d4425ee301652397774751f68ab80eea6201.nq.gz
│   ├── 57ac67fb060e0c3a8a443c0061fe819110b09d89.nq.gz
│   ├── 58a3e8a7a21afca3c20ff79a9f5ed436a122cd2b.nq.gz
│   ├── 5b78034f6625962f4fe752d1c309dbc00871c2a1.nq.gz
│   ├── 5b8f00956ab7d4f85e836c87a78f029abd79905b.nq.gz
│   ├── 5cb6bb1662d463aa4cb9073969f87677fe9e4014.nq.gz
│   ├── 5ee691678a41dffcad2ebe049ea7e77f8246a795.nq.gz
│   ├── 5f7cd477e07873a11c2b4baa097a50a1279dab8c.nq.gz
│   ├── 60074a1a3577f1ae21bdbb294e92d414c9f237d8.nq.gz
│   ├── 607a668ddd3cb1aa4ee68d8a188fd3d68836495f.nq.gz
│   ├── 62132b7e01e05e12e87ed3769c40821f733a679e.nq.gz
│   ├── 636d81c3245d753efcd4f006000c45bb42fe6bb7.nq.gz
│   ├── 63b4a37d38e2484cf443ac94128c6ee8ff3fbec4.nq.gz
│   ├── 63dcbd9c482697be7c315c54e9aaa7c4f8a29059.nq.gz
│   ├── 65fb5b717106a55229710e2d9cfa81f11e1e1ad8.nq.gz
│   ├── 681bf76e1d909657ffd6efa979d6009edc0634c9.nq.gz
│   ├── 68afc61ba99c58d4d20475a5528a4476ea759572.nq.gz
│   ├── 6906892f2c779b230c464bef974033abeebd8eb2.nq.gz
│   ├── 6a2c2aa2e16bdd7019caabfdf7dc69879aa607f8.nq.gz
│   ├── 6a6e52edda01776fe0001041880e11c89da3cad9.nq.gz
│   ├── 6d7054cbac0b1630336c0ac57ae6da7da5c6d341.nq.gz
│   ├── 6e2ba369e17c30674522cbc14d643ecdecbc7c6b.nq.gz
│   ├── 6ed32867a130285d7d3eab14c8998c8ac502a8d5.nq.gz
│   ├── 6f7721757d92e870c0a94b7503004edde067fc0b.nq.gz
│   ├── 72587b6d13d85a4d12f937055217e9232314e53a.nq.gz
│   ├── 73810512eb26dbc90a17c0d1e4f191a1f6091e2f.nq.gz
│   ├── 74699aebc92af1e93409f6043d7da6cd6fecb985.nq.gz
│   ├── 747ffb7b3033659bdd2d1e6eae41ecb00358a45e.nq.gz
│   ├── 75ea415dcc2b1ead125a891b5b87c0593a0a0c52.nq.gz
│   ├── 793e0bb8b76b4448f8eed8e7ca5d29a0f2165c98.nq.gz
│   ├── 7ba36d3239878e273d56013136d908be928f294d.nq.gz
│   ├── 7ba3a70a4ec0c5ce3a76faeb86a0a89b8ee1507a.nq.gz
│   ├── 7bb08974885eba9a408bb57cb53643aa7f8a3392.nq.gz
│   ├── 7e526dbefc4398b8cbfb1a2ebbc65d8e53f5da73.nq.gz
│   ├── 7e687262ec5c35f2c405816019fb8ef74dca577c.nq.gz
│   ├── 7e7802237c5a0c4d76994137f95cbc62860b21f6.nq.gz
│   ├── 7efd03fd334146bdb75007c85a1f61648b4e482f.nq.gz
│   ├── 807686d9d6f2c81789b54236e0fcdf8e7ee45981.nq.gz
│   ├── 81775c19ae5a3f2e7aa84547052d53396d15b849.nq.gz
│   ├── 82cbaa87fad014d24bb882d2d2415e712bc74753.nq.gz
│   ├── 82e2cb04143e90b497fe088b80210c67a44c2769.nq.gz
│   ├── 835052dd189bfa80fa3a69341fe3ebb09a412bb8.nq.gz
│   ├── 84fd10c4b9747709a7c42a1794a3abaa8123c923.nq.gz
│   ├── 86fad2d4bfc133d28af4f739823d589d99633454.nq.gz
│   ├── 87477716f8fbad05c1d72a8fd68b87335f40b5a2.nq.gz
│   ├── 87c0fbd14128451404d24ecc5200def9219ead76.nq.gz
│   ├── 8a5f34edbed3494ac0a794ad379473bd4f98667c.nq.gz
│   ├── 8c9ae0f649e96c20492aef1da14b400b2f525dfe.nq.gz
│   ├── 8d069f6e91eb0193211905d6fe32ca717bd433f0.nq.gz
│   ├── 8de30655138ffc9bd7c92e6809e6ad52f2791004.nq.gz
│   ├── 91334a743185c857cde6211a0cefb605c577e82b.nq.gz
│   ├── 9160895fa2caf6ec43caf15e08247352b78d4414.nq.gz
│   ├── 9245b3170e1033c6526f5f53ecf644974891a0b1.nq.gz
│   ├── 92de6c3f6ebedf900fcb77ec498a9787397a2b5e.nq.gz
│   ├── 93961c8fd58d94e0d3ebe06688a118e124859026.nq.gz
│   ├── 93fc956a8105f530d52d1e34471397921a31f6e5.nq.gz
│   ├── 94b9ab702ce36883037c61d95ed163a8d161f3a3.nq.gz
│   ├── 960ae7011550d0ac3c5e34cae72d87d2723cb57e.nq.gz
│   ├── 97920d44c9c1bf5713de06709ce9ea1cde888111.nq.gz
│   ├── 97e6579d72ce98ff66f7fa40e0010932ef092dac.nq.gz
│   ├── 98a12bf6790ae95bfed6c83a18a78b586780be4c.nq.gz
│   ├── 98da9d728d1b95bf6f7665bc0c2c478431488a41.nq.gz
│   ├── 99dfe9ce6b138b28db17ff3209ab20a49afe9570.nq.gz
│   ├── 9b798a413c262526a84fbf9b03070f191d8774d4.nq.gz
│   ├── 9be3350fd9e1e54e68a82e862783cccc40998ec1.nq.gz
│   ├── 9f46feae1703b058c215793c174ae0c6cb9b69b9.nq.gz
│   ├── 9fd512141df533efc4a54dc10fe4702a4599eac1.nq.gz
│   ├── a3e9638c68083e6b9c81b1d7d8d83b9959539f56.nq.gz
│   ├── a4a6b0fb211de1af1db592deffa9cebd39321bf9.nq.gz
│   ├── a4af2cbf9c97ff088b13bc997fccff1f6a15bfc0.nq.gz
│   ├── a593372533755d16042643b777510dfa7fa6d265.nq.gz
│   ├── a617986ac682d37074d6df6f598faa72f6c0492e.nq.gz
│   ├── a62bf96c60e92b547d005202b8326f2b98736a5d.nq.gz
│   ├── a7ba6111f043f30f28f0e981873e9b3b37b0e810.nq.gz
│   ├── aaf9e6023882d07f8fb576a9e3ec0cb3afc54225.nq.gz
│   ├── ab1013461d745b17ab0eb2324a7f1f0fc4f03ba9.nq.gz
│   ├── abc4d40a4e0061f946d3c704aa3952365d81addf.nq.gz
│   ├── adc356e2eaab462a579b574e7ea5cd257f6403ed.nq.gz
│   ├── aea1b2e3c03aca6714358338c0aa662e66bbe6ab.nq.gz
│   ├── b3424f55e4f5d2900c3b5674dbbea5685ed9ad08.nq.gz
│   ├── b5a86d7058f1e494db246733865cc481b5040355.nq.gz
│   ├── b779cbfa8b094599a45929fb030add337c4a3096.nq.gz
│   ├── b9e1182ab95027314e6be0a4bc2f64bf52e220ae.nq.gz
│   ├── bbfc773b104a8f6dd29b928c02a1f2f226a89be1.nq.gz
│   ├── bf041b17bbee2efcee50da69bc7d62f04d6849a9.nq.gz
│   ├── c0fcac31f7feb2674267489fa607b317ffc0a025.nq.gz
│   ├── c16da8aa28c933ba3f48ed23d456274ad0e229e0.nq.gz
│   ├── c1938a6f2fc9c6c91ee832c7152caa20a1885280.nq.gz
│   ├── c24bb23b343ea398a0be3d5842713f558d6ca39a.nq.gz
│   ├── c268a8554b8061a8fe5dbbaa11bbf206af6af29a.nq.gz
│   ├── c32d2c9f2eeccb3b9749a4cbc9de9eb3d1bb9b27.nq.gz
│   ├── c3a677599d984f6491b7beacd365a21f7d8b5c57.nq.gz
│   ├── c3bfd8625c5b3070b29c4e6b4f3a8be19530f6fa.nq.gz
│   ├── c3fe9beabe44d6aad3be732616d4a97f38c7d095.nq.gz
│   ├── c6e98cfb7a80133994fc376fd2d9796b5f87bec4.nq.gz
│   ├── c75799190a50b2b50306e36c1a80072baea52b56.nq.gz
│   ├── c7642d015145dbc4e67f0622e5c3e61530743a14.nq.gz
│   ├── c7ab856e26364510200b63fbfbf437eedea00235.nq.gz
│   ├── c9f206ea811688f970621d0882e9527352eb474d.nq.gz
│   ├── cb1914220a33ed572b167e62ed58d0f0aa244253.nq.gz
│   ├── d25ad4789675b253e5202eb1e9c412815f9b102e.nq.gz
│   ├── d30e997837125d6afa3d9872e60281133e1d6549.nq.gz
│   ├── d5da7171dc7fae2fa35f09862245de0dcf041dbc.nq.gz
│   ├── d69ea03d860a6d5de8ad98e1f59f420caac1d56d.nq.gz
│   ├── d7646f405357f91cd08dbf75e73bc7ed9fa23884.nq.gz
│   ├── d9a81285f36c458fc012ac831950b71e0230d73b.nq.gz
│   ├── db2d128f1c8e9b9acd0a9e872fd84bb16c702ad8.nq.gz
│   ├── dd0a24f6ef860f1da15c33250e74402deb2cb32f.nq.gz
│   ├── df816e82e869889d15fd26faa2b9533b100a1e93.nq.gz
│   ├── dfdf0cc3c595dc0afbabd1e8565f35fb899f2313.nq.gz
│   ├── e031ec806ddbe033ba2d0848813e2b34b2705013.nq.gz
│   ├── e0b79caf7c3ccd08c4efc8fa1221b5cb912d2d1e.nq.gz
│   ├── e17adb6cf5d77311d8ffc1a2951b2a4983d37068.nq.gz
│   ├── e1c205336a3c30c7fadc6d29dffb7bdd0a059483.nq.gz
│   ├── e22cfad531a3ff214f7bd5744c9f6a3c58098196.nq.gz
│   ├── e37f814ab1618635168559e949033a881751607e.nq.gz
│   ├── e3b56b917bf1989cedfcb15afffb792641a3047a.nq.gz
│   ├── e4410e94f90cef606e5cef1f766dddc14d113a1e.nq.gz
│   ├── e45eca3c70f6f47e0a12f00b489aabc526c86e8b.nq.gz
│   ├── e5bafe6782aa1382e9acf78c45c2bf8682aa80fd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e87da114d03cfa4483b0fcb2379ab3fc7cec9a5b.nq.gz
│   ├── eb625643b8dcccbc736c23ef48ca7b9651ef9dc0.nq.gz
│   ├── ec4bd8715d8e539150b329b7e478957dee7ffb13.nq.gz
│   ├── ed464368953a26f9842c61499bc71bf9e75b05ad.nq.gz
│   ├── ed4e9d89f20656ad38a789f24e774585816177cd.nq.gz
│   ├── efc82e74fec8213418e4e0a8cde9fdd998c0fa9d.nq.gz
│   ├── f0c31925d8bd5351f2b28943f35f454311e00367.nq.gz
│   ├── f120b222cff25d25e1908016f785974602b99b46.nq.gz
│   ├── f123d195fb0281a87b263eb9ba1afdba7af3f712.nq.gz
│   ├── f1a294960130fc8678054db2cc186e110a06a794.nq.gz
│   ├── f34a065752b46eb0cd1f8a3748eb2df1698a1c06.nq.gz
│   ├── f6d5cbf6f05dd11754d0f2d4f766ed9c24dde7aa.nq.gz
│   ├── fb9e8cf2847c23608e2f1795185e14d6cf17956f.nq.gz
│   ├── fc34167c2361431c903cd0423c8e1f112ba5f586.nq.gz
│   ├── fc64e71af4339328d29a2f80e8e9a2653f8c3e70.nq.gz
│   ├── ff19b9b86433092c20f75c932d0326395f004008.nq.gz
│   └── ff5e5b0d3fd0d902eca4741ec6bce7b7bb9c1a32.nq.gz
├── branch
│   └── branch.nq.gz
└── commit
    └── commit.nq.gz

9 directories, 200 files
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

[dagshub/dagshub](https://github.com/dagshub/dagshub)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
