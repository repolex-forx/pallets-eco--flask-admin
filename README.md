# Repolex Knowledge Graph of pallets-eco/flask-admin

RDF knowledge graph data for [pallets-eco/flask-admin](https://github.com/pallets-eco/flask-admin), parsed by [repolex](https://repolex.ai).

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
rlex download pallets-eco/flask-admin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9f0d23c03dcae17f6537667a4741cde85274d66e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9f0d23c03dcae17f6537667a4741cde85274d66e
│           └── chunk-001.nq.gz
└── blob
    ├── 0182ff2a0633f4d45f23f159aab52b574e138c38.nq.gz
    ├── 02a7af676a09b5c91a405e35d19c9c8da7b2639c.nq.gz
    ├── 037e3172e118f564fe0d6ddb2148f8435c975965.nq.gz
    ├── 03a0a5808b83898fc16bc6606764dc6cc1835c1a.nq.gz
    ├── 049772cc164b3dd8a1b4120fab012b89552d2627.nq.gz
    ├── 0552e7c1acb23f98c0ed5de1296fed589d15f444.nq.gz
    ├── 058de4509c20ffaf679039781819b52a6130557f.nq.gz
    ├── 059c73e9602cb01232827be367e93ec335399a57.nq.gz
    ├── 05bf88c5f95404c8b3e7a1ac9b55080adfd75a95.nq.gz
    ├── 0607b55faa39c5c4055cbde0ce1eec58da0eb34e.nq.gz
    ├── 0683a3b3b96223600a19e6407fa674bebd2ab51d.nq.gz
    ├── 07db793e0ef59b922a8b11e612da7b2250282e0c.nq.gz
    ├── 09e680cae498674e1a9bd628cbe73bae376e2934.nq.gz
    ├── 0a96ab961d3b0a3d9162a56fb7d8d6e738f459d8.nq.gz
    ├── 0b041893d2e4ceeec62c6b7de1762b094f39c06a.nq.gz
    ├── 0b4e58a1667b7a6f006a1b7d4f3fc1dca752ed66.nq.gz
    ├── 0c91b35fa66ba49ed519473a64a1c31a7f41560c.nq.gz
    ├── 0caefbc395b03bd4e4c1cde57556aa614305a95b.nq.gz
    ├── 0e5d055b05a87eff9e346042b6cf3da00cbd01ce.nq.gz
    ├── 0eb3d890bb91cf39b18a7b74d60ad9b6ab21d2c0.nq.gz
    ├── 0f8ee87304e9ab00c03ba815fbb8371e4c2a3bdc.nq.gz
    ├── 100787f7db190dbaa1f544e3f36a8be05a8690b3.nq.gz
    ├── 11066caa44cd9e3251aa9a3dbd37c135f2995184.nq.gz
    ├── 1150eb3fd03b07134759da4095d824a4c8ed72dd.nq.gz
    ├── 11fb8ca9bc501126ab2f9a75edf1ebda55e12239.nq.gz
    ├── 1263a6e8b368045889f3b902f39482f13cc65931.nq.gz
    ├── 128bb75b93f1abf73daf9b956b55abc928876c14.nq.gz
    ├── 12bc3521a7d6eacd0b8ebb69eaf6c0bb3557af41.nq.gz
    ├── 12eb6bd48c9317d37cd138bfb67a24f72cca12c7.nq.gz
    ├── 13477b410f75d29abba4b8873e3cda17e7d16227.nq.gz
    ├── 13939b54c3cf50e82ca150e21a695ac0aa3c77df.nq.gz
    ├── 13f817c7ae34978dbf29410f0cda6b488a7c1c61.nq.gz
    ├── 1440bd1a82b34789dbcae86f30d095014cd35b69.nq.gz
    ├── 1489b11e748d564da1ea7d291a17b62617b66ea1.nq.gz
    ├── 15721fe372e3e55cea64b6b510a954fc95c8d46e.nq.gz
    ├── 15aa602f5cacf593dee6e63361a759dc01e1419c.nq.gz
    ├── 164baecdcfdd8a933738c17a905abacefeb7277d.nq.gz
    ├── 16fd9114ba3493bb54ca5fb7b8cb12beecac4214.nq.gz
    ├── 176646a8b58db9b88a1d41f118c29a07e03d650c.nq.gz
    ├── 1789af3931adb29e6d4a94965eb0d96517187dc2.nq.gz
    ├── 17c99f6b43bfb5058c7f4683e14b5c8f282e4452.nq.gz
    ├── 184d9761be31f44fc08ac61df2cb1265cfbd498f.nq.gz
    ├── 19291210b8193a36bc38afcc5b04b0ca1ee33876.nq.gz
    ├── 19daed19e28d292d7b8058355d1c39e89f7da0a8.nq.gz
    ├── 1e943be4c65322d272b1dc87b44a82f1d96bb035.nq.gz
    ├── 21c19e52037438c2d09921dbc12f79e783bebf99.nq.gz
    ├── 225c6e47119a2be85bbbed415ac69c42603f558b.nq.gz
    ├── 226094e2563883c759f343cb56263d1b6397b8a5.nq.gz
    ├── 23283517f10621af2871451ec202ce4656681676.nq.gz
    ├── 238bdb526d796e2207bbe07b90d9d11788632bff.nq.gz
    ├── 248b7b65d08349cf4a0113eaba6c37b8d56c8765.nq.gz
    ├── 24a3b1da79be0dedc49fda7ae4d8d5517946f7f7.nq.gz
    ├── 24d78f370a005cc810931992fb00f2a751740f44.nq.gz
    ├── 25111f6be12054d9629733b96ea8fe457e808660.nq.gz
    ├── 2513b42e84f88edf2bd8d6b6ffa8670a4713f24c.nq.gz
    ├── 26888b55c253e25f1098ee255735f6a5592e9188.nq.gz
    ├── 26bfb16b8f8bb29bc6915f8ff8b04e93e8ddb4e2.nq.gz
    ├── 26cb4ae7bad4bd9b6929cfc113019a6e5c7ba186.nq.gz
    ├── 280c0aa8a056b77a2ec672c71269a65d7d4836e5.nq.gz
    ├── 287cb9910540f489b1b5a6c1697d158ee3780589.nq.gz
    ├── 28b7f426564b72e2519c4ea2a05d8bc0c17cbe5f.nq.gz
    ├── 28bd6a5be3558463d087a114784326eec1c8ba6f.nq.gz
    ├── 28d143095f8cacaa46e796d86034d90d49084abe.nq.gz
    ├── 28f2ce82375b2d60a34aa3b335dc1c1031c54b18.nq.gz
    ├── 295b8b4821ea8e165dd4a28c1f7c76f8d29d560d.nq.gz
    ├── 29ba662c7e6f6e1f36a10724672e02b2da92a2c3.nq.gz
    ├── 2a85b35ee74dcf7d402cf2caff49712f74cc2d72.nq.gz
    ├── 2ae08bc333efc1a3fc8b2b117ba5c64e62eb2c73.nq.gz
    ├── 2cc7a93391f971a84cc8c9e64471806e290d4438.nq.gz
    ├── 2d710962fbc7621f4bda9cecce84af68e31a28b1.nq.gz
    ├── 2e0764473e9cd16767d23099144667008b55755a.nq.gz
    ├── 2e6638e0281eb3c84d8b3782c7a2e8fa75c73adb.nq.gz
    ├── 2f3dcba10c5862af98100ed954e12da6a3482bdf.nq.gz
    ├── 2ff985a67af35fdfd1076354b771c425867cdab4.nq.gz
    ├── 31982e2810943a488ba6bc21a1b396a55ea23a75.nq.gz
    ├── 32ccf78d240c4d3d750e4ee0b31044a01f62441e.nq.gz
    ├── 33e4fef192f2d8fd77df809defdec6cdd0d5cd1c.nq.gz
    ├── 356a2cea053a0f8184e2c9d1ce024311792e8c21.nq.gz
    ├── 35acda2fa1196aad98c2adf4378a7611dd713aa3.nq.gz
    ├── 35ba7831824062e5a5333f0cce09a90f1d8e01e7.nq.gz
    ├── 36e0102c98ac723eab35faa570d102086ccd7c6b.nq.gz
    ├── 376de3f9f79fa43fca2523967364f2ba99ac3be8.nq.gz
    ├── 39073a1efa7a3ffc0b71a4711ba700b1d76e0316.nq.gz
    ├── 3933ad4c7743a26410c8477929b294d700612b38.nq.gz
    ├── 39797f7eab50407d54e55f1e0601d343c555f0ba.nq.gz
    ├── 3990dc184820f736294dfb1c617cc0411f54cf93.nq.gz
    ├── 39c8f08758e7346f67faf48bef7ab6e130254720.nq.gz
    ├── 3a3d4741f15aa9a8a18bd92eb0e770452c600462.nq.gz
    ├── 3ad54886dc3f876e6a759220e1fe6b83a1b33744.nq.gz
    ├── 3b0aedacd180603bd58c6c209dc41cddf9a8f7a5.nq.gz
    ├── 3b2fa5acf04c1b7331eec4b5db48df3a1e4b3711.nq.gz
    ├── 3b72e8bb52d3e9584e2b64bf10c5a8fd23977da5.nq.gz
    ├── 3b9a57673497c1d8d2ce44495a530eff634b4343.nq.gz
    ├── 3d293d34bd939549861fa7131e9dc6a854ada703.nq.gz
    ├── 3d43d83ffb53ec675d59310b714cdbb967221cf1.nq.gz
    ├── 400014a4b06eee3d0c0d54402a47ab2601b2862b.nq.gz
    ├── 401ec0f36e4f73b8efa40bd6f604fe80d286db70.nq.gz
    ├── 404fd0eba1df7d98e1a031effa6c35bb7983eec3.nq.gz
    ├── 4102bc9dec8c931d4d80841b18cb652da6fcf775.nq.gz
    ├── 41ca512626f5c37f9191eb626ba4ed8c2a92b838.nq.gz
    ├── 423b1a84a9c1c5b2fd870cbabd25d98565b79c98.nq.gz
    ├── 4397abe823523129ebbbe6829eedd514bfa2efcc.nq.gz
    ├── 488912dd654162ff2ab525665c98ea1eef8625e4.nq.gz
    ├── 49811b0fca6c93ff8eda02df3f54d3001b49492b.nq.gz
    ├── 4a1df3c65762ce6ed93867e22e5e0ad0f73588bf.nq.gz
    ├── 4b055de8fcac40f4b779568b867863c04eb690fa.nq.gz
    ├── 4b36e9a1d03c15b4117d27c5d25052407ef3973a.nq.gz
    ├── 4b8d7474fd2200e5398bc33ec254d64db6630a43.nq.gz
    ├── 4c430fc144fd6dd9c8e901d2294bd6a4184c0074.nq.gz
    ├── 4cb0a57ce75c4c59c262b9b8034ef27c1e07be55.nq.gz
    ├── 4d13fc60404b91e398a37200c4a77b645cfd9586.nq.gz
    ├── 4d8ef37527ca193eb9d032190f25fc3fd684d3e1.nq.gz
    ├── 4e5dd8a4a1a4ef2a141df1b4709f36e0d8b9ef7b.nq.gz
    ├── 4e64f3d224acc132555e55aafc0654ecccc82b73.nq.gz
    ├── 4eb4637915ea375f2437ce6d623f845d70e9afd2.nq.gz
    ├── 4fb25a6ef819a8646b727e5e5284c810aa6bcc3c.nq.gz
    ├── 51644eb8d4ad0c8433b019159cb85acd54f0230f.nq.gz
    ├── 51f9cc75fff5c40347026783c0d573659cd0a00b.nq.gz
    ├── 526309ec734b5f3f9510d68e621a5700a7b6386b.nq.gz
    ├── 53689c0ccd70dae032a6572b668bc73375cb1eae.nq.gz
    ├── 548b6c3f6404aa85d0200e42d34319919cbfad7f.nq.gz
    ├── 54c109828ca647c87ac11412460a6d034f1b008e.nq.gz
    ├── 56a537f4be634c8fb6c770ed16eb3a1f2ee73c24.nq.gz
    ├── 592f7aec6b01005c3e3f69aea456709a63bbab08.nq.gz
    ├── 5a74ede007f48b62e0b154f803a3343bbbfb1f35.nq.gz
    ├── 5b5e9e1916a6c03d1f198ccbccf6f03563f6cc1f.nq.gz
    ├── 5bf391f2bcc9cda2c5dd6208e12dd5066f94c5dd.nq.gz
    ├── 5c82d869643d011f2fa4e993ceba490d62a040da.nq.gz
    ├── 5cdd59d0cd40aae63291bdbd73ec73d8a62a9829.nq.gz
    ├── 5ce0ff255725b3e0ded0e13cee4559e04d0d5fb1.nq.gz
    ├── 5d3d13f5f985cba1190c49eac4ee145bb8d8516d.nq.gz
    ├── 5e39fc2b6216c153ec57ecb341509707161faa66.nq.gz
    ├── 5e6c4aae9f17f5fed85219a075e7f3f1af37c278.nq.gz
    ├── 5ed9f15780e9d01878d4640615b735b66be2f111.nq.gz
    ├── 5ef8b75493d580862c0448ca2ef2cda1c252b2c1.nq.gz
    ├── 5f3b1b765f00ee72556ea663f42dfb23c4e43749.nq.gz
    ├── 5f451dc51dbdd4ab25f65f7d31a8c76fe3a5e1e2.nq.gz
    ├── 5f7329600b62b202edf934d031046b913f599f6d.nq.gz
    ├── 602b0b1773dc3fdcb74192c97d26a1f78dad9251.nq.gz
    ├── 610056861f85b334fda9a170d89c7f2f93e5cc8d.nq.gz
    ├── 64e02a5005058298189f645eeb5ffa279d17c02f.nq.gz
    ├── 64ece2cdfea5400445a18c026b4446dcc5a8f3cd.nq.gz
    ├── 65ad77ab29e9a02e751cbe5b7b5fff3159a5385a.nq.gz
    ├── 667a3d1d53cb8054958b6963d7fe7030ee924c2f.nq.gz
    ├── 67d11c323bfc19224074c1bbf0e4359f15b6c71e.nq.gz
    ├── 68cfef9c651f0d353efffe0e04869f108fd16d85.nq.gz
    ├── 6938447bdc5cfd2b52282c2756eb8f654e66f791.nq.gz
    ├── 6acd053469c8d21c538be771ab086fcd28ddcdb2.nq.gz
    ├── 6b2e13fcd838cf66a5106b846074f7d82f796395.nq.gz
    ├── 6c70f0523a5f5112423593dbeb5c38ea13b86d9b.nq.gz
    ├── 6d0cf8f26659f0196497588554583c18c3c7f051.nq.gz
    ├── 6ee025227a08fcede8f837b21ee27ca9faa7efe0.nq.gz
    ├── 71004669ebc43c47e4e875ad638e312c31109308.nq.gz
    ├── 714ea897ccc8188cdac3c173095ce8b1f8ee424e.nq.gz
    ├── 719a077ff492c8e9b8b42f84352348b214e5440a.nq.gz
    ├── 720118c60df9c84dabb88e7e3898067be905b0a6.nq.gz
    ├── 72682e7c9d3bf86ebb7a4ca9a953707c1bb433e1.nq.gz
    ├── 728bce2d4bf68dffbbecddc98ec9e1d8288f3856.nq.gz
    ├── 737cc5cd34d9726d923065b751dd8e0240231a87.nq.gz
    ├── 749f7ef8dc691481e8d2fe2d77cc3d8bd0da09fd.nq.gz
    ├── 7578ca07b9bf79628b51d67b5d80309dc3b0f427.nq.gz
    ├── 7726b73ee1529a237234f4f7335799167ba4bf84.nq.gz
    ├── 7903c1d4b66e4e7c589e7efb5039135dfbb759d7.nq.gz
    ├── 790ddff3e9f3829061de4cb11fed29b7abecab18.nq.gz
    ├── 7990aad597107f8681d825515657be57c8673f37.nq.gz
    ├── 7a4bd5eef576a947c53587091933a9b8fbfc9f5e.nq.gz
    ├── 7a4e2e9db5702eea321ce81d852082a141a62787.nq.gz
    ├── 7a7d1ef81f0821ce71345eb9b3916856c8c5d9df.nq.gz
    ├── 7b894dd90372caab216525e5e284a093fa37a915.nq.gz
    ├── 7badcc6b4843ab42308af06b994a880d50375dad.nq.gz
    ├── 7be8f6c7ab1f9dfb30d97f29fe0bfe0eef74caa7.nq.gz
    ├── 7c1156bf33c1ff8f80bddd0892f2836323fd01f2.nq.gz
    ├── 7cc8f0150f0bc194d80938b2a3773f649ea7c015.nq.gz
    ├── 7d15817211c944c9a5e4252d574d47851421b0f3.nq.gz
    ├── 7d1c78a50bdeb12c4156ea72fcff4e4f907a1024.nq.gz
    ├── 7de22954272a0f24f59e7e0cc2ecf5b737238096.nq.gz
    ├── 7eb63209ac2279f697dd3fe0fd4d7af84dd9fa2f.nq.gz
    ├── 7f62d98bbb98aba7a0c5c5609d793d8c48c5372c.nq.gz
    ├── 80ba05faeb146a2e271210c3a9e2212f43511c41.nq.gz
    ├── 80d9169da1781076beb9a4f87004ffa3dce8c61a.nq.gz
    ├── 81129ecfdaacbfa36acf01fd2fe0fc5cfa9902b1.nq.gz
    ├── 8174d3ad929ce30473dd5ef8db593f7f68e0b7f3.nq.gz
    ├── 81d8be6c8ea65b52f8831ff3852b304ffcb21c4a.nq.gz
    ├── 82444d91f77207b8e63b38f6a101873011456d90.nq.gz
    ├── 825f40c4a75a6ac692d37b2d996aaefd27155250.nq.gz
    ├── 8379e69ab9c63ffaf23e4481b52ded0c8d044b6d.nq.gz
    ├── 83ad8254fa736f645337bf85177d94919e89d171.nq.gz
    ├── 83ade87b8f691a5b2361b6773b67b243fa56f0f2.nq.gz
    ├── 83bdb64c318722d5eed903284864c700507f5651.nq.gz
    ├── 8419864606799e8e7638b7e9196ef5f7ae41be3d.nq.gz
    ├── 84c4104fa9964bacfb1c1117547dee793abc22b0.nq.gz
    ├── 85545eac4317ba50db5fa8ae44e6d70c0422d53d.nq.gz
    ├── 855c845e538b65548118279537a04eab2ec6ef0d.nq.gz
    ├── 85f7c72fb8c68d5562ac03f21b5142e94fe90ab7.nq.gz
    ├── 862d13ed2b626207571bfdca7f8a6a8210c2d54e.nq.gz
    ├── 869147221ed1aa1a13c433e5f0257efdb72b4d62.nq.gz
    ├── 8700decf38476be86e41278d530603b29c6f7360.nq.gz
    └── 87be5446974b0ebf16fe7ee2f154b7de847339ee.nq.gz

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

[pallets-eco/flask-admin](https://github.com/pallets-eco/flask-admin)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
