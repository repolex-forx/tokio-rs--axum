# Repolex Knowledge Graph of tokio-rs/axum

RDF knowledge graph data for [tokio-rs/axum](https://github.com/tokio-rs/axum), parsed by [repolex](https://repolex.ai).

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
lexq download tokio-rs/axum
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c59208c86fded335cd85e388030ad59347b0e5ae
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── c59208c86fded335cd85e388030ad59347b0e5ae.nq.gz
│   └── repolex
│       └── c59208c86fded335cd85e388030ad59347b0e5ae
│           └── chunk-001.nq.gz
└── blob
    ├── 011ce899340e8edd6defa20373594343235e2a27.nq.gz
    ├── 049598c33910fcb3e7a92326d96953cfc0860ca4.nq.gz
    ├── 04de8223f0de2e5edfd610ff45d4a5031605907e.nq.gz
    ├── 058ca6f97404611a25ee117b0d5e6e200350b8d4.nq.gz
    ├── 0610a22a3b0acf98ba70613253e07876f1a6769c.nq.gz
    ├── 063eb72a462538a2c363d7754672cb958509036f.nq.gz
    ├── 0658dc02bf767db075bcf497c4c5ce614f497fca.nq.gz
    ├── 066520927ea7d5b053817407dcd127472db5e786.nq.gz
    ├── 06c073449f7ad9618b4fbd0681e64423c3f7187b.nq.gz
    ├── 06f9101c3f44bf8563c381a71d699f905cd0e0e1.nq.gz
    ├── 080bc3f2d3b8a9b95291190b8fee272fee96b618.nq.gz
    ├── 081de75d78acaa3f3469a8616869b14d813835c7.nq.gz
    ├── 088f21f9d468b8b6098ff7680a541d18cce21d03.nq.gz
    ├── 08c941ac1f8dcded25041bdf5be5dfb70d35fb23.nq.gz
    ├── 08fa9e53e47a70f009cfec2d674b7e54beaf6e0f.nq.gz
    ├── 096901d04d97243de50feacc46693dd3e9cea372.nq.gz
    ├── 09a25165e8e38786f4859733122b83ca338bda51.nq.gz
    ├── 09bd9dfbfdfb076ed06787a3e9e7865cfc195307.nq.gz
    ├── 0a0c43763081c4242b8387ea21297ac1465c058b.nq.gz
    ├── 0b299d2b9c3e97a6bb4f9ee5a31bfd040f246efd.nq.gz
    ├── 0b2afa168eda645ee3025bb086f70f81689e7c4d.nq.gz
    ├── 0c5852d20baa35437680fb0b3ced74fc26232d44.nq.gz
    ├── 0c85bae5eccdcaca7e86fd4bd618aa58e04c0ff8.nq.gz
    ├── 0cf1bc8782983fae5a66aa6c47d0f4dfa6a7eb0c.nq.gz
    ├── 0d65b2d38f7a8e0723da57f4c9b172163aab3e72.nq.gz
    ├── 0d9005b492ab7398e9c7bc46f3c419a170122502.nq.gz
    ├── 0e881ef2da476ff55f42eb7bf405fe9a709ded26.nq.gz
    ├── 0f234077d12cfabb4a762b76dc0f7204f52280b6.nq.gz
    ├── 0f4fd90ee4191f17daeb32349987e2500b13b9b5.nq.gz
    ├── 0ffd277f9bcc6f6f42a1cdbc010798307bf3904a.nq.gz
    ├── 105b1de46c51a28f448ef41b3551ebdedbf2e4f3.nq.gz
    ├── 108e2303b6288168b66401800f6be6416507af2c.nq.gz
    ├── 10a832be1872f59f79d8a1a93eb2a1d932b64891.nq.gz
    ├── 10de87088308d7bec52e83d8ccbc30fd040dd788.nq.gz
    ├── 1123fdd3d698be97463b6a97882a4a32358aa7c6.nq.gz
    ├── 1163afce743a135f16b3354ecf3ef4b992254446.nq.gz
    ├── 1168b3a11917e22ca1cb2b81e5dcc48a76815fad.nq.gz
    ├── 12092e857bcbe2e415da9b549a124d377a4abfdf.nq.gz
    ├── 12ca64c56cdaecdedb84f672a98dcb76ece187e2.nq.gz
    ├── 135891f7a316d22b23e688fa16ff0701a57ac3dc.nq.gz
    ├── 138820db167fd2503c2c9b5d4c23738b6ba45b0e.nq.gz
    ├── 13ab83ddc09b378057c6458fa68c406e4417ab17.nq.gz
    ├── 13db285d4f34dbd3c634c5c68946e4229945175e.nq.gz
    ├── 143154e89dbed57bae41eb4c723f4a7ea8b760bd.nq.gz
    ├── 148af57c04e53f2c09c9afd099056226804fd5c0.nq.gz
    ├── 14ed45275b47453cf68351dbf566f30a8b1a8b19.nq.gz
    ├── 151da867397097f21776996cb173086c8e9ef3d4.nq.gz
    ├── 157b55934dfb4c485e7ed25033197c857716aa87.nq.gz
    ├── 1649a9e4cf742ce1f726a513320e2d9cafedb6ba.nq.gz
    ├── 16737c21eb7a7bc0aefa88c8fd338bebc1df6324.nq.gz
    ├── 16f1962fc49f8d8143c82b8e298a7069021159a6.nq.gz
    ├── 175d0a2507476254d2acd1608571cb11d569eb09.nq.gz
    ├── 17669567da2cb1afbb946d13e79cd7ac2d06a9e1.nq.gz
    ├── 1768bb52221d7a2fd13f04ad90ae8d9f740fd220.nq.gz
    ├── 17c6ba80f32554d220309250e8f331ec3834d08b.nq.gz
    ├── 17d8967bb529e17b4445c224b5c5f47af383c29b.nq.gz
    ├── 184dfcc9987fefec7ea736a1877502ce3af67ca9.nq.gz
    ├── 18c0698f9fbe29ba7572b1ddfe3877723ea5fa4d.nq.gz
    ├── 18e107b1a8185621acf840ec6a0273ae252f7a69.nq.gz
    ├── 1916c36974e5fb4ce720b35015feca850132d627.nq.gz
    ├── 19a8d0d781fda2f8bd1d54447a0fcfca63e00d3f.nq.gz
    ├── 19e7307678c3eef0cbf76f36ad90dd91f2fb336d.nq.gz
    ├── 1aabfbb3b46352b1d14105aee31c496fcc14f7d9.nq.gz
    ├── 1ab45c0116eb3b76dfebaf7db93077eabd1d0687.nq.gz
    ├── 1b49f244b6e51d87c4dc2b4116875a4648bde164.nq.gz
    ├── 1bb7cadff8c7b0cfbf4d1b5d5c87df179e8637eb.nq.gz
    ├── 1c029c7ff4dbe26006733e05fd18abbab0639312.nq.gz
    ├── 1c07301ed8cd3f82a7da051e32853527c870d983.nq.gz
    ├── 1c0ef9b58a0cec19b6f3132c70991d89c0d03fed.nq.gz
    ├── 1ccbc6e01e6592345215021d0f9ff0530eaf3f05.nq.gz
    ├── 1d06dae69cde900ea147592d4add3f1017a0727d.nq.gz
    ├── 1d2a412ac43baf666918fa4da45242e6c53a90ca.nq.gz
    ├── 1d99e8f2aabc35d894a3f86b8049caf36e6c5864.nq.gz
    ├── 1dda92354c52a8d20be366ef84a0b54acc8dcf60.nq.gz
    ├── 1e13b8e4d9d2fe57c55effee511b387602412fd0.nq.gz
    ├── 1e4ad53e9463894c0ba75ec7e299a0d0675cc9fe.nq.gz
    ├── 1e4fc1ac43490bb5b923b2f90d146e286a0eea08.nq.gz
    ├── 1f2801b0a03012c44aed4013b9b5b82f58d80e49.nq.gz
    ├── 1fd4534710dac71ef500d083c3829f84fa495dde.nq.gz
    ├── 20194b68f2660b13d722137d87b0beb10267a5b1.nq.gz
    ├── 2053c1a56cadb0cceec0645589b58b78f97b3f96.nq.gz
    ├── 205c55fa8fe8bba796be92874aebd703bf05de62.nq.gz
    ├── 206eb8e9bcc1a90e460b3e0b5b9a66b25a86d2ad.nq.gz
    ├── 20900519787b81612102da75f4c4207bae6079a6.nq.gz
    ├── 20b01c1d5791a6388b748904e216bc17cf49d24a.nq.gz
    ├── 21feffff1be87a37811de90d4a4ed648da144978.nq.gz
    ├── 22905cd941c0609964db1cb02a8d559d60ea5cb9.nq.gz
    ├── 22a237e5a4cea6d1ff1d2cd8aba74e24eecb7cb6.nq.gz
    ├── 238316bb7e52ef857a001a6fad44e54718c83ce8.nq.gz
    ├── 23a8cb7f2db00cfcc67f10e989872d6cf02cffa1.nq.gz
    ├── 2407a16643fc60a7d030f04d8f6d037b9ca62157.nq.gz
    ├── 2474a4ebb47ea0b452c77276c03b202d60b4f177.nq.gz
    ├── 267f81fdd620d5f6c2176cbec72dad1435d0dbcb.nq.gz
    ├── 26ad198070015e7d112c7d9cd8246c7271b8a294.nq.gz
    ├── 28226993795405e15801866d4b33087bfd97961b.nq.gz
    ├── 287dae22e31ef5633e3d2800af978aa9b4081d74.nq.gz
    ├── 2903b824bf9324d830720078e8c7c91785e85417.nq.gz
    ├── 29cb4765c3625a6872116dd95616bf716fe7a984.nq.gz
    ├── 29cb4c6dd34debec2a755776a633c2f197a794f3.nq.gz
    ├── 2a85e749389fc75d6624af37deef550da771f7d2.nq.gz
    ├── 2a8bba1d7c5b344554d341362f13b6b2e55b25f5.nq.gz
    ├── 2b4cd6d586b1a59fb1d0ef0bcafbeed9c2a17a75.nq.gz
    ├── 2b66d4064dcb3c04d09cf95913dc92f7092e35b2.nq.gz
    ├── 2beb99cf85fa89c3fcc4e2d981e825d9a952845d.nq.gz
    ├── 2c7866f9f6bb0a3ebae8714748c1e86f7f7ce1e9.nq.gz
    ├── 2cf25f4f31f946a38acb80468f8dbf355be4fe6a.nq.gz
    ├── 2cf6486b12da26da12a64d17a1941391ab26ee02.nq.gz
    ├── 2d231db34bb54c6d2d78c71cf88c9bd7b371cb24.nq.gz
    ├── 2dfd7f4443da90bd1009ced1a83120350b77c680.nq.gz
    ├── 2f9c9d71b129d26841ca604138783fc43fff73f2.nq.gz
    ├── 2f9f2bb84421b1136153cdf9842cc169d7f15068.nq.gz
    ├── 2fb5f089fa92ec766fec1e1eb6961814e4dcf8f2.nq.gz
    ├── 30c16f19627363da8c06b37881e21cf4348762bc.nq.gz
    ├── 30fcfc70a9e98883d482a07a23808f5d378331b2.nq.gz
    ├── 3209da3b126f22f7b8b9c2172c2a7225528ef689.nq.gz
    ├── 3239d6ac6d3c26fd91563b406912e3f0dfc7a61e.nq.gz
    ├── 35364281bab2cb5708118416903dfba9f044261f.nq.gz
    ├── 35ffcc31f043f343f487a963c6444783281b8e2f.nq.gz
    ├── 366fc38e7ef9c8e27b15de9750edbf59a6c84c56.nq.gz
    ├── 36da73a21e729046f3125ff0fa087dbd19eb1881.nq.gz
    ├── 37b8fc3b26d1cc916fd7ff204930f5bbf3e9c3da.nq.gz
    ├── 37e4546c5ff159f6de6066f5c9807583b58db6c8.nq.gz
    ├── 3838636597c8a198078c8e4d2e02ae98d14cb826.nq.gz
    ├── 389c5f48f04ec9f5bf5cc5cda772658f1f164ac7.nq.gz
    ├── 38fe0964c0e3bd9cdc78672a3776eb63cd21b77b.nq.gz
    ├── 39966b7c9be35874c78bde291a5b6c5a4abbf2df.nq.gz
    ├── 3a1f6de585f7090e7a002ef92906486514f9af98.nq.gz
    ├── 3b62287ed85bbe22274bec51eb33bdbe83802e52.nq.gz
    ├── 3c8755bb856b400f9cba25a525621113612f65b6.nq.gz
    ├── 3cbcd47c833fa7972325fac480cd2b95ba9403f5.nq.gz
    ├── 3d1204723db334d2ba8fb522a3558edd8e17662d.nq.gz
    ├── 3de14eb32f65d3c7febe0a74373a7e8853e961d2.nq.gz
    ├── 3ea740e3cba7219ba8b5f27b36de68535f887b0d.nq.gz
    ├── 3eb57c9e239cf2f7c899650a2710ce3be8586197.nq.gz
    ├── 3f0ed94da75d97e9a3d200bd3e99e65bc03c75c8.nq.gz
    ├── 3f2a39fa7d36a4acb8ea624c183a64045e016896.nq.gz
    ├── 3fbcc4e03b755875d13b16d3fe0261712485861e.nq.gz
    ├── 418b5a05c09123380c713fdfadf6d6255509f24e.nq.gz
    ├── 41b7671cd2e6c7d227980de018b36bcf1ccd7b66.nq.gz
    ├── 4342895d2fc8743b0440a25b8ddbea69d8c393a7.nq.gz
    ├── 43e66dbdc40856293e010c56313c5cc378bb9d78.nq.gz
    ├── 440f20fe58cf243027ae430ce7dbfdcb5cd8ace8.nq.gz
    ├── 44da20dbf03e701bffba2fd1abca71d310fe5557.nq.gz
    ├── 44fbb54643fd4c26f002d0a59ff09e1a2c629ab8.nq.gz
    ├── 452406a3659aec3e414f11f7b87b8d6adecdcab9.nq.gz
    ├── 452fa21d2ee58c9e1d13e6ce858f5a4e8d19e44c.nq.gz
    ├── 4534b19eb3a56c56a45f0088241b80c59e765330.nq.gz
    ├── 455d240548981b5ac4ff396b28a813e9b07fcd20.nq.gz
    ├── 45a93777a9cce79b55337f4eb2b9322250a31b1b.nq.gz
    ├── 48188352e507bed8b1f003e6d4dcecdf1d276b85.nq.gz
    ├── 4990ee97bb665fe16c6460b4cb20d71abf235038.nq.gz
    ├── 49fce13d8b7ad78705d812d1cfe9d8ff721bb254.nq.gz
    ├── 4a5fea45462c27b4a2441e5adcfe7b81ce6fd10a.nq.gz
    ├── 4b30908d48081c7dffb18e3cdb5d6282b4d59b1c.nq.gz
    ├── 4b42d4204e68a35d893e51b49353658b26e5264f.nq.gz
    ├── 4bce0ec19d8983321d1ef3c449c3f3f33ee00cd1.nq.gz
    ├── 4e15f55a2a62eb9feb41e581d4d8dc292440bebf.nq.gz
    ├── 4f75fb440de45460c34d9aa86c340e807dd5291b.nq.gz
    ├── 4fc7c90fd66a031b93d436bce66f0a2d5047ce13.nq.gz
    ├── 50721e700aa28b2886349a1e576b3934c53cf3d8.nq.gz
    ├── 5098cfe3034066812592dcb2fa886bb2a43d208d.nq.gz
    ├── 5159c49b8887dcc13378440f3976d016cac9ee52.nq.gz
    ├── 517e5a38c379b62f3a703da51fefad40e8260788.nq.gz
    ├── 51f0c3f540abc572d6edfa553715b8a376b4666f.nq.gz
    ├── 52c9f592748efc312a18eaeb1c052b249b08a5a0.nq.gz
    ├── 53d1c4e4776fbb228ceefc776f7861b4ea4bc507.nq.gz
    ├── 552d8d4a81e7d674a2e76d682ea487678cf71b47.nq.gz
    ├── 55830fdf32ffe0305ea09e7e2f3c9eaf0f92390c.nq.gz
    ├── 565c1796d6e092d5d90c423fe399deeddb15ffbd.nq.gz
    ├── 56c8fd0f12448ea1ecadb9e97615e8ece75dac6e.nq.gz
    ├── 56ccdd05b0b1680f631cecadc7fe02dd89bf9294.nq.gz
    ├── 596f55817fb741e5a1b5c7e0e2da8cebe10521fe.nq.gz
    ├── 59f2c85953efdd88774c931c353f16a15ae9b2f2.nq.gz
    ├── 5c05bd3bfdf630e035717f1ae2fa7c077f62bd75.nq.gz
    ├── 5decd89c89f6b4566aa3494fb907b1ce570c0899.nq.gz
    ├── 5e399c1bf08c09c971c5656bda73fbfbf74dbe57.nq.gz
    ├── 5e773d698e6bba072926a7c4ee738b435dee8e5e.nq.gz
    ├── 5ed0ddef93a0abd16e1f11a0a5b980210fb10615.nq.gz
    ├── 5f40623257d4f1996f642a1c65bea0c804d37253.nq.gz
    ├── 5f90019daf57c5cc28b9101b7dee471449cac9b1.nq.gz
    ├── 60012d33eb7d5a033ef541f164ea3f01310eccae.nq.gz
    ├── 600ec3379121e534322604cb3c2f59c3de44e616.nq.gz
    ├── 601e0e2c1358ac77fa3b4296a0434354b87b27d1.nq.gz
    ├── 60cb3fa8efc715fda2055160b0035c7f83f20379.nq.gz
    ├── 629023aa0349d97726956b7e7d75b22850fda5ba.nq.gz
    ├── 63af28f5d0ee14515ae939e920734d9764de8962.nq.gz
    ├── 654538fa22d99b351b2cd561961bead4a7bd718f.nq.gz
    ├── 656aa8805522ca5724e5053bf334fe7317e40432.nq.gz
    ├── 6687898e2a0fe2da282efab6b5f7f38b7f788f56.nq.gz
    ├── 668858858270ebdadc00bb1b343a832971ba11c1.nq.gz
    ├── 685ff1c7fed2202eaadbeafa06ff3dc9f441a2d1.nq.gz
    ├── 692ea0ca12c3faef06d3b4fd02ae7244d8fb9296.nq.gz
    ├── 69942e4476cb8efe87f5f1c5cd91187d0a3b7fa5.nq.gz
    ├── 6a503e92e2a66e78a28d362b22a190f3f31c56c6.nq.gz
    ├── 6a7556438b557f5fd84f052d451630c21694d7ed.nq.gz
    ├── 6aa80e1eaadcd00d8a29476941a000132cdd7c90.nq.gz
    └── 6aaa1a31cbf306d1062e9548731a174cc18a77cb.nq.gz

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

[tokio-rs/axum](https://github.com/tokio-rs/axum)

---
*Parsed on 2026-09-07 by [repolex](https://repolex.ai)*
