# Repolex Knowledge Graph of allenai/olmo-eval

RDF knowledge graph data for [allenai/olmo-eval](https://github.com/allenai/olmo-eval), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/olmo-eval
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ef703a1ec8d860546357eb908c6b9dc9af92946b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ef703a1ec8d860546357eb908c6b9dc9af92946b
│           └── chunk-001.nq.gz
└── blob
    ├── 0102f22e97cc6688953e3305c182e18de83e541d.nq.gz
    ├── 02c23d5ba1e0077c8c8df60b71206d4fac06e2c7.nq.gz
    ├── 02d02842c410b5503469d0ecbcae7c7ff0998989.nq.gz
    ├── 0521738074e473401f72250b5725347dd98fe0af.nq.gz
    ├── 06602c6c6d894cbf84c402c39fd3e4dc88da909e.nq.gz
    ├── 069c114d23c14ddd8473e14ce73282e0138e7be2.nq.gz
    ├── 0770c70e5ed02ee485ee617f88639e88ca6acc38.nq.gz
    ├── 07ed25b8516ccc7b94d12c2aabc5f016556fc8e7.nq.gz
    ├── 081c6b003a2fdcf15970c2c4aea68d24804d18c4.nq.gz
    ├── 08281a163ae86b05a51f59aaf8d19a97a4271698.nq.gz
    ├── 083391e5f5f06156e043fd1cd25974a94f0795da.nq.gz
    ├── 08a5fcd55386388a0f2cec675bca45eacc0dff05.nq.gz
    ├── 08ffca09888e47428af2b2cc77089c609a414a8d.nq.gz
    ├── 09a50f4048bc8341f1f8a082547d06ca5e910b26.nq.gz
    ├── 09a97a611d935bd7382309a662edf0636e0432df.nq.gz
    ├── 09ec1945ff2f999df8330948045d1a0ff24890e0.nq.gz
    ├── 09f07ea8a8986caf45cba71cc2e40c91be31a9f2.nq.gz
    ├── 0a1751aa2aadf27d574232c79d33dfa8fd1561f8.nq.gz
    ├── 0a22750412ec98a5c08476b81be9509e54897480.nq.gz
    ├── 0ade4afefc9447d8c48a08558cb1dee9e4bbab0b.nq.gz
    ├── 0aef5e5138f82d71582554adc7da50330b416fd2.nq.gz
    ├── 0cd3190fa6a95fb0a260afda1f5a3120fb6698e9.nq.gz
    ├── 0d4d60b8465878aa14fe8257757c80928ae9ebc3.nq.gz
    ├── 0dfa0b8af581f5bfecac5c85b8317fde24d43aee.nq.gz
    ├── 0e03a40bb1bcfbcb1d5fc29083583797eb22e3b2.nq.gz
    ├── 0e8aaa90a79d245f09d26b764376034ed65cbfaa.nq.gz
    ├── 10271ce16226a2bc558f2c09f63f7a7a216df48b.nq.gz
    ├── 106eb18bb1d407e6373cf1bf260897d5c7691a36.nq.gz
    ├── 111ce49a7ce903d005a939eb9c96efd86429ed7f.nq.gz
    ├── 118983982015789cdecf8aeff7bf7195ecc96c7f.nq.gz
    ├── 119edc8e42b21347e1b3fea4e57cc861de68aafd.nq.gz
    ├── 1203822c85d331ecbc1b890c5dd7acfb7f25a565.nq.gz
    ├── 12044e67dae1df2a40ba6c507304e9f3c5a83ace.nq.gz
    ├── 12e3c6a1b1104c6f23ebff2e657a4b62369c390b.nq.gz
    ├── 1393d48a4caa02b1af281690f1a87f287e9cd69a.nq.gz
    ├── 144df38b01136e26b30da5bef19e1b7bfb552bf5.nq.gz
    ├── 14e0f25fd055c32465c32e9e2263162759078ef3.nq.gz
    ├── 1532b7a68779c1fe19f9bf62191ec30dcd2dae04.nq.gz
    ├── 1677d98aba4ceeaac3780749e6ca0e6fb95a3b25.nq.gz
    ├── 16a61abb660bd03cbda35bc893928a0fdbf0183f.nq.gz
    ├── 1708f37b8c2af7e81ae794bba942db4b7ff940b1.nq.gz
    ├── 17ac57dbe12ed314e9645542a1ffa7899258fbdd.nq.gz
    ├── 185a3972f1261c047427e467131b466059b815fc.nq.gz
    ├── 1a28db87a6e2885acbaa9374edee850bcc142c2d.nq.gz
    ├── 1a4905cd8c1d055f050c6e53d6246d97956e68df.nq.gz
    ├── 1c3ffab43459eeb00c8dd15ab1ab824676da7e07.nq.gz
    ├── 1d059f04dfff931a9371a372b0627d601d624dae.nq.gz
    ├── 1d8ac5e6b3a8e7a820bfe886636c96e178ce8625.nq.gz
    ├── 1e25c3c9a0da8cd810d3b640c136e4eea0914c3c.nq.gz
    ├── 1e34669c4d327ba170ab7452c9629efab54ed20d.nq.gz
    ├── 1f13b0c4fa880fbdaca78956d599480767141391.nq.gz
    ├── 1f18ebde0d2e65a194c97427700f87051f796169.nq.gz
    ├── 1f767688ef226a9915d278bb63ae242df90bc946.nq.gz
    ├── 1fba247c4caa00bfc8c5003c8e3e232bc8f65c53.nq.gz
    ├── 21f6b6bc8056e2fa7587460c23155f3d08dea718.nq.gz
    ├── 228a406d272ec09a153867da5fda9a9d8d338ff2.nq.gz
    ├── 22b201d1880f1f7c6ed4d4e331df23be386bc3a6.nq.gz
    ├── 22e681438a8efc0d6e57cbc2ede3b557b2e34452.nq.gz
    ├── 24ce00db0d62ed720140768221dd3c5f84ab048c.nq.gz
    ├── 24f8d89ad0f9be91354059d98b54da80e7ea69b7.nq.gz
    ├── 2523e1704c34b6c21699b619d248b5b0a49f3746.nq.gz
    ├── 253e857138548c6af65126ac0f148c0b4353d839.nq.gz
    ├── 26bc3f3096be18169f43d9cd6cc4dd8262f583de.nq.gz
    ├── 270f88851fdf9150c5eb80c0b374b5e5a6bfd5ad.nq.gz
    ├── 275dd611800fa263829e7862270c790a2a56238f.nq.gz
    ├── 2769f49d6a48408453e7c0c6d7eedf3ff1052aa5.nq.gz
    ├── 28f7e8b1376f634b4be0095ce23f734f934e8161.nq.gz
    ├── 29042374d4e94e45b49cfeadc513238c8aa99300.nq.gz
    ├── 2925b28e126427745b08148e10f63eaa5d8a0bf5.nq.gz
    ├── 2969a60f029085bc4a4c28f7ddefd7984ef6a1b0.nq.gz
    ├── 298be139c49b725203228d9bf4db976ba8be3079.nq.gz
    ├── 2a6e01413bca2ba5d8cbe75bf5f5109264ad4fa9.nq.gz
    ├── 2b49cd79fce3d52410a272fdf3d0f5b23cff5998.nq.gz
    ├── 2c8bd6495adb9170916962d1e342c6aa3bbcf1ed.nq.gz
    ├── 2cc6dbc0c08ec89c76ff7339c5acf2d70173a7b9.nq.gz
    ├── 2d3a6517a8530b2b0f063a757ac38bec823c97f4.nq.gz
    ├── 2d98f0cb7e1eb49b481ab6faa5f202e24a06a3e2.nq.gz
    ├── 2dd9a7e97045f4cfafa98fa9dd8e848e09f2eb80.nq.gz
    ├── 2fafa6446dd4bfa68f60648cd71b259fbf2d3149.nq.gz
    ├── 2fb62d37ec725d5a988bdbcca3f21d46f8055ce3.nq.gz
    ├── 304cf62a728105907a6f5b5d88c9b039803fa546.nq.gz
    ├── 307b351e8317889342691c21504737819ea9e845.nq.gz
    ├── 30ddecbdd31396ebce5a21abd2d641e6960af737.nq.gz
    ├── 32492359a31de41fa259310456ca6a05e574d574.nq.gz
    ├── 327c1de9c96dc6495e6fe5237ead69698a744dd7.nq.gz
    ├── 33383a28c65764c34c17d28194a221ef5b0e5462.nq.gz
    ├── 3339297e26ef7887c527444d665153fcd50f9f21.nq.gz
    ├── 346fe9d6fbf7b4720754cd2a8936914100ab1e82.nq.gz
    ├── 3576bcfcf607088615a376ab820cfcaae27e483b.nq.gz
    ├── 3594dffa1a9692b4804cdcb1c97abf56d632779b.nq.gz
    ├── 35ca6909fa6fc65ceda9398498906b62ecf7b4f3.nq.gz
    ├── 35ff35073f7971312e36bc6799531cb67e9ad0c3.nq.gz
    ├── 364c72c6cc418f9bf7ed94643672b68ad9f63797.nq.gz
    ├── 3675c98e075378be5e64ba2a0ced8637e44a8c10.nq.gz
    ├── 3687f8d6fc0dd902df84c58afdd71e7e447f0244.nq.gz
    ├── 375e5d24b7ab8f7b7956277929f9d81cdbdbb4a7.nq.gz
    ├── 37c081c92cfb44ec8a0cffd92c3508e3ae861d0b.nq.gz
    ├── 37d78bb11b064fc263276abcf29881ddd07d21fa.nq.gz
    ├── 381659af18c94d427a468320b0aa9a8eb94a8327.nq.gz
    ├── 382ce242482013b0ed49269153327fbdedbefa31.nq.gz
    ├── 3841f169ead21e408292c8458d7c7952a1622864.nq.gz
    ├── 389171624014972878241c5fe10355247a399473.nq.gz
    ├── 393096305c636690bab45b838040d05317ea0f2d.nq.gz
    ├── 3996f16fd4b727a67ccd0a722d5bb2dfc17b6318.nq.gz
    ├── 39f6cb831de9975c298928b12859171a03f4a65e.nq.gz
    ├── 39fe15a85df93ecdae2524504afdf19df5ba91a7.nq.gz
    ├── 3afe4554064ec38802dd23f2687892e8e602ad18.nq.gz
    ├── 3be65ff0027367164b6a37cf4fde6121fb350f23.nq.gz
    ├── 3d51bc492852f03767d7ce83e42edae31999ff28.nq.gz
    ├── 3d991eb619b92545faa1d065359eab43587a5270.nq.gz
    ├── 3dc1f76bc69e3f559bee6253b24fc93acee9e1f9.nq.gz
    ├── 3ddf9f5fde5b73b6505217de51737b1c083c546b.nq.gz
    ├── 3e6d9dee8b327ad8133ce136fa44de4918a44671.nq.gz
    ├── 4060aa208c7416e40966582a89c233a2759b6e3c.nq.gz
    ├── 40b2e272db0264eac0ecc3b8b154a4ccdf9fd7b4.nq.gz
    ├── 41e0b46a210e7f76dfa1f0bb420fb9833dc0474c.nq.gz
    ├── 42d997cd58b7abcd48839a19628c593e1e966e62.nq.gz
    ├── 43b630dd16a0296e63ad9548d2659ec907c5f2ed.nq.gz
    ├── 43b74fb4bcf8e2bdf659f340784fee441691c3cf.nq.gz
    ├── 43c2a912beff6526355706a534fc4fc13b81ff5e.nq.gz
    ├── 45b6d1d963d3bd620c14f8dbc4ec12c878e30b4d.nq.gz
    ├── 4617e61d4538305475e173e476969110623c0382.nq.gz
    ├── 467d20f402e25cc4c7a8853c23af7b8a4fac3fd6.nq.gz
    ├── 46899da8a0e21b03398919256edee8cc066c9b43.nq.gz
    ├── 47eab30beabb282ac594ab322d1ff6b400b98e1b.nq.gz
    ├── 488bfe3025bd3790045ae8ad79e675da0b683e57.nq.gz
    ├── 489388b971310762c52b76377fe2a7d7df69365f.nq.gz
    ├── 48974385e8775bb34012dc953ff55539644990b2.nq.gz
    ├── 492f117f842629e71476d5bc639b2964ceccf46e.nq.gz
    ├── 49650d44ecf692febe2c7bdc0107419576fa27ea.nq.gz
    ├── 49b080cfc86cc4c7e7ff3215e5d9739b05ce6519.nq.gz
    ├── 4b33eeb46092785dff02f868d73dfacbe584efdc.nq.gz
    ├── 4bdb90e792391a3942ebff10c1dfe07415dc834a.nq.gz
    ├── 4c1aad64576a19461f890a1201fe2b052d0dce16.nq.gz
    ├── 4c7bee694297a453023edf66dda138fa806009c7.nq.gz
    ├── 4c7d58b959df5c1c7889e04caa630c5efdd7bc6a.nq.gz
    ├── 4f5e48e5f74dc1f79ca29fcf65aa3cb836ee53c0.nq.gz
    ├── 516bc70b2409d7e9c0f3ade0b17684e697358496.nq.gz
    ├── 519f80f5facbd16848f7191672ab96d86ab6777b.nq.gz
    ├── 51fc714cda16152ac07b893d0d4de781a4fdd00e.nq.gz
    ├── 54c4f30c9c4c54d6d34c74641bd44fe9fd4ccb07.nq.gz
    ├── 54fe84208f61b62c82476a3f8ad0e596f3b439e4.nq.gz
    ├── 55077abaac9220508cb3fef59798b61e300b4872.nq.gz
    ├── 553a94062f302cdea94345e98e5b563fa3493505.nq.gz
    ├── 5557fbea5ec7da3a2c81ad33f75bc131708f697e.nq.gz
    ├── 562359a280fb8dd166b8ea7221f27a6900d5f043.nq.gz
    ├── 56a5143850fbdd707c9f1b494d03e790c707807e.nq.gz
    ├── 574d59256cbb5844cb6400fdcd29dc98ce5cfadf.nq.gz
    ├── 5779a6e01263ac0a883656d64ed75952faf0f245.nq.gz
    ├── 57bf1c79315732317bde40108c1ef7dc283493a4.nq.gz
    ├── 5887b11b3b60625f37a7e61e3feeab06b71b9a23.nq.gz
    ├── 58b985f5ca5ec4cc7cde16a4aec181c4b1a53c30.nq.gz
    ├── 597030b9fca2e923af1af323a0129096c47947e3.nq.gz
    ├── 5a129e7c597b9578bb7f55185b74dbc788f139a4.nq.gz
    ├── 5a49268a9566842153e54663952493f92ba98924.nq.gz
    ├── 5a5ecea4686d3b2e6e8394422ad34538432823c4.nq.gz
    ├── 5aa9fa6ad7eb676c11b97e7837537e9b5c803687.nq.gz
    ├── 5ad0a6248784b46c211ce52af6220632d0222c85.nq.gz
    ├── 5b1c8acd182bfa307d24cf2c2d8c4aa4c0a1e245.nq.gz
    ├── 5c0bc06d11a1fac6773c71fb23ed76948a8a0968.nq.gz
    ├── 5c126be9e45818351706b8f6362adfbea9e1267d.nq.gz
    ├── 5ddbbc99ed88aca320f2a94f6f3fe2aacee91341.nq.gz
    ├── 5e0d276d0def2d74b7919057b921f432fcb56332.nq.gz
    ├── 5e7bfe75e94eb9808cc7d0cea4f179e39eca856c.nq.gz
    ├── 5f745a70cc1ce150a00ac40950122f0dfdb86859.nq.gz
    ├── 5f882b242532b4701f3e56df16186a9f9802373b.nq.gz
    ├── 5fca1553b0b41d1d555ac91145800debb3e62d28.nq.gz
    ├── 5fe8870cf2472d7eba1dd034b932e8c0d8658a66.nq.gz
    ├── 6015ea1b69148b8cc152eeef14745af98b7d205d.nq.gz
    ├── 602e7c4faec3e29d505a615d6bba73cf073989b6.nq.gz
    ├── 602f6789153e5ad9b015721b1f9794425d011b7b.nq.gz
    ├── 61082614508407a939bf5c5186061d8fdbe2861c.nq.gz
    ├── 613cd475e488824576b996717f2d657a81a87d4e.nq.gz
    ├── 61ab0e850bff8a04672230570b3bc3405ac8e045.nq.gz
    ├── 6337d0d8e9ea645c19fa0a20c5d6271eec6f80c9.nq.gz
    ├── 634357b52242faa356af5cf8e4c5980a468df5ec.nq.gz
    ├── 63bac1d5b1eff234624429f7c2e22e55297d35df.nq.gz
    ├── 640f1de9670000dd6b4fce635df87bc648e21ccc.nq.gz
    ├── 669290dc91d725cc235b1aef7b9dbd810f873d9c.nq.gz
    ├── 66f3feccd7aba50c190762e774dd9705ee4d38ea.nq.gz
    ├── 671e9842195d84bbfdd54e604fc956e2e63261ab.nq.gz
    ├── 68a76656cb1d2dcbabec05d6ba830351653164f0.nq.gz
    ├── 68ce86d9402e4773ccb1df8f8ce8d60b55eb92c3.nq.gz
    ├── 69930d8e5ef7d8244c05ef756ff32fece12a42b4.nq.gz
    ├── 6a3239212ed367d6415e140a5cf989639fe6e925.nq.gz
    ├── 6a4c874b6933dc2640ab4cafa0f77437578feecd.nq.gz
    ├── 6a80f2e4c8413f43eb62529befa22fd9db17fdf1.nq.gz
    ├── 6ad1729ac2af3b2b18f7b5b8d0b522c0badb03de.nq.gz
    ├── 6ad70a476fb2efeeea9bcd843ac1cd0436bb6cdb.nq.gz
    ├── 6af28cf3bf8010b2821b8e066ab97a3553024f74.nq.gz
    ├── 6b01aa7b72be4406c3ca9e15b50fe5c10a47376f.nq.gz
    ├── 6b49135ea958181cce705a6da1e5ef80f187fb8d.nq.gz
    ├── 6b91b2b98c8b22c4c812ca35700bf5f6ffccb517.nq.gz
    ├── 6d66176e70f7eaa451076b01d1b2f2449c338020.nq.gz
    ├── 6d8227c2780450559636831589b8a526dbbf555f.nq.gz
    ├── 6ee20f6827ead357819d0e9b4cd5e96a90486dd1.nq.gz
    ├── 6ee8c7614a3399bdcbc174dcb0a4787e5377a31b.nq.gz
    └── 6f1047e48b65cdbf9ad6d195f19548a0466d5d60.nq.gz

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

[allenai/olmo-eval](https://github.com/allenai/olmo-eval)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
