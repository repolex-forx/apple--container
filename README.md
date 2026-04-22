# Repolex Knowledge Graph of apple/container

RDF knowledge graph data for [apple/container](https://github.com/apple/container), parsed by [repolex](https://repolex.ai).

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
lexq download apple/container
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d9b8a8d197c076a373ece871f3953de0d2a385a8
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d9b8a8d197c076a373ece871f3953de0d2a385a8.nq.gz
│   └── repolex
│       └── d9b8a8d197c076a373ece871f3953de0d2a385a8
│           └── chunk-001.nq.gz
└── blob
    ├── 00b273dd86700c5030b0dc67c215a414a60c7f40.nq.gz
    ├── 016ab6d62654dd9e884fe2962335e291c719f02d.nq.gz
    ├── 0219335b5c02f738664900688f4b221aeb309d3e.nq.gz
    ├── 031f31322d82955d959791e89138f7573f5e4eb0.nq.gz
    ├── 038b76d7de308cf488491f508052e457aec789c2.nq.gz
    ├── 0495982966014f806a92551de045ae323b43c873.nq.gz
    ├── 05789d2add5f0b11bafbe79c42f991e83755e1f5.nq.gz
    ├── 08ea752bfd79bc64845c8acb5fe965c67b8a7517.nq.gz
    ├── 09063d9afdac883e4a79b176f92789fada0f5c92.nq.gz
    ├── 09d886ca3675e581ba0e90a7ffd0904b260fad8d.nq.gz
    ├── 0c156a5a069f975d59835855894d936067c2f02a.nq.gz
    ├── 0d017e4c167b0f912eb6178e795cccec3bb5b360.nq.gz
    ├── 0d5aac9e2e59b830d1c0e7d88c22d3ad49310c15.nq.gz
    ├── 0e561c19feeea399a363a5b68f72feadc76a10ab.nq.gz
    ├── 0e86411bb72dd237f96705cf20720aae1ca60aff.nq.gz
    ├── 0f9646f058823492f971142b943f629544cb3ad6.nq.gz
    ├── 108e28d439006d03ce447d31f44f9c769eeebcbb.nq.gz
    ├── 10b77caeff3857c6fe2f0ec4cee77aba5c06ec05.nq.gz
    ├── 118772b39c12209c76e653f4ff322a6134299c6b.nq.gz
    ├── 12a46cbc078776633dfc49f72678879c387b8ae0.nq.gz
    ├── 1371906d62d74c7a3351c7364fd974a7856bf219.nq.gz
    ├── 15835b2796f1768346754d549d36011bdabe6d30.nq.gz
    ├── 160a395a8b0fed3393dd546260306e9cde5259d3.nq.gz
    ├── 1a5856bf60f3a6bf81b90a3546185449d24c1a35.nq.gz
    ├── 1ba312b8ce484b455a385108284ec9f18811ff24.nq.gz
    ├── 1cc844a6cb2fdc63f242fb6c61d8dd6d7bc5ba63.nq.gz
    ├── 1d1e32282c0ea366a6d24ecebe5f21c605ae2607.nq.gz
    ├── 1e4e1a3e2aec06cfb3e6af207ec376413ff304ff.nq.gz
    ├── 1edb1e83aded955fb92c2e42790a95a4bd415ba4.nq.gz
    ├── 1f3da08d1629a31c974e8a57925127f7120739f1.nq.gz
    ├── 1f87ba99357d3027b70e41842af1ea6571839f6c.nq.gz
    ├── 1fae0a7837775b80c9c9085d9550d61ea2bc49df.nq.gz
    ├── 211b27fe0fb6f9818426e7e47ad70c8794276f72.nq.gz
    ├── 2122c1159aa4ed164b62dcf75b5ba51bf8c8093b.nq.gz
    ├── 217531b8ce99995d9827ac8831b1b9fb48d7efe2.nq.gz
    ├── 21851c28af0304040520d08579fe9753393a915d.nq.gz
    ├── 2201f24294b1b81d9aba50bae88cef2a72b39f69.nq.gz
    ├── 220e5267c9622cf69fb3d5bc91ac66005191c5e5.nq.gz
    ├── 227e35e03bf42723fe1617d2494fc29fe14f7b86.nq.gz
    ├── 23c4e05a1cf1fce91e3f42e31564869f297a0847.nq.gz
    ├── 24b255c2a9f45f0b35225da03dbb0166b0de487a.nq.gz
    ├── 2550a887baddb21e20730e6ef9672ced015fd2a2.nq.gz
    ├── 258eb2f0bb8401a1be91f09988ae40c0b5950518.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2624f4bc7dbd71ae3902edf81731bf5d90bc0571.nq.gz
    ├── 262a900d299deb6dd3f996df2bd52296aabc86b8.nq.gz
    ├── 27264c1589fe4aeed2ca5997c540e7ac0e0c977f.nq.gz
    ├── 272af8fd1d8080ede534c078fa20a381df4b2531.nq.gz
    ├── 2879523892046a9778b9fdbc37de047358c7ac77.nq.gz
    ├── 290e66ba6f2788ce5bd0d41732e7f3fa18d28277.nq.gz
    ├── 2933f2917cf502d37052b6b2a3e66acbab5e1771.nq.gz
    ├── 29c299b1e683d3c632c8ae100e1647c20a61cc55.nq.gz
    ├── 2ae284d8befb59dcb044219aa0c3a3fd4b36d4a2.nq.gz
    ├── 2b25aa48fe9e1277384f550039af8c5e5ad333b7.nq.gz
    ├── 2b9068260f4797101b17c73bbcef7b4f8924562d.nq.gz
    ├── 2c219ea0d15b065d2ffdca1d9a5778f0528064de.nq.gz
    ├── 2c6b7943c01d2169875dc446c888554face3b778.nq.gz
    ├── 2f0716d2e9d017e96732ec253f4f10562b9d5639.nq.gz
    ├── 2f5a2432b1826c257e102e1c3f97940c55558310.nq.gz
    ├── 2fa7749f3efe080be62f8b68d5ac32e9c4727d22.nq.gz
    ├── 2fb06ed1c8534565fd7d0ff2ca65ea5edd4ab95a.nq.gz
    ├── 2fb9916d2558fb2836a0e776050b3eeadcf4aa2e.nq.gz
    ├── 2fd111e24e6abecea5eed04095260eff76bd9a84.nq.gz
    ├── 322798c4f8e71036939ed92ba913b508f1b4b307.nq.gz
    ├── 32d277a33f80467e70c5655cbfbc79a9601e814c.nq.gz
    ├── 3442cca4052efbd81567756454e2a2d7da41b703.nq.gz
    ├── 3603d81f9ac2214e50e827499a39856abc7a93d2.nq.gz
    ├── 3727f9eb3d276f19fafae48e9d426ad0130f316d.nq.gz
    ├── 378d37980f0a88960762a575d7cc164650053a07.nq.gz
    ├── 37df99a6ccd6925b4f63ec8f2fdeb8273181e55c.nq.gz
    ├── 3807f40a3727f395d6f5b11d8328d8167c1cc062.nq.gz
    ├── 395dc7b909ad13b76f727e25891128c75209694c.nq.gz
    ├── 39d43b8d02c8da3177b149ba23cada127e1ae144.nq.gz
    ├── 3b29d5751ee5120893fff2188cfb46cf176da010.nq.gz
    ├── 3c6a3dca851f29523d323490bb0cb54c7731cc2d.nq.gz
    ├── 3cac4693c09b555ac1d290f51dea2204c448eb09.nq.gz
    ├── 3e01f7deb91460536f8f5de3930e86fd3eb4bcfe.nq.gz
    ├── 4067df8cffaf5fd812874556a6360a607b4d2f1c.nq.gz
    ├── 406b552f023b1ba79fb951c0b11b7953201525f2.nq.gz
    ├── 41a6796772a461d1b5bee134ffbbcc7ce9358b25.nq.gz
    ├── 4214a7d9d950043f2e7dacc6955f678c67b7484f.nq.gz
    ├── 42694b86b67be58a1bf5578805ff1b26cb258b93.nq.gz
    ├── 42b242c8b4f66ba4d92422e2f18a22f70a14be73.nq.gz
    ├── 42c3df717490ecb22c89a757dc3dee9f93c3517c.nq.gz
    ├── 432a1e637a98d885bbb09e02291696245d8e448f.nq.gz
    ├── 43b2fd258d99ef5f97f3d213101a62683ae25ea8.nq.gz
    ├── 446fa33083d34b1860716e1ae5de3d6a36e0c347.nq.gz
    ├── 44a84a228aaeb47c523ad4026f7ebd542eeeae73.nq.gz
    ├── 455e719a7d7a9fa4ed2d7d043073cd9f5122a870.nq.gz
    ├── 458e318ed95d4b4568a0d8be821e9907d8e2cfbe.nq.gz
    ├── 45dd41aef6f78c7e1dcd9e7134f0c19e13ec8683.nq.gz
    ├── 4652efcdbb476f6c24312609e8e16fa01df38c93.nq.gz
    ├── 4737cb67a1a5c4403c4c5abbd1561545051def65.nq.gz
    ├── 4820b9e881fea9485a07c0ba8e16f7caca3d1f91.nq.gz
    ├── 48a7cebdd256ab8a34937ca6b87487894f4ad241.nq.gz
    ├── 48b085ea1f80ca6de04ba6d3eceb2e561dea3854.nq.gz
    ├── 491ffa59722b273c10dabb638815b907ef233e4c.nq.gz
    ├── 495a227fd007acab4f8981c4f85dc715ccbf5bc9.nq.gz
    ├── 49fbcd70c7d559160f937da018e44487eada260f.nq.gz
    ├── 4a234366b2b68ba103c656bdeafeb0167188cc1b.nq.gz
    ├── 4a3a318ea851fe7fa47aec895461fe43cb67174a.nq.gz
    ├── 4a5008c6265a6458917527af70d8c0ece24a2369.nq.gz
    ├── 4a685e659fa7175446ea3bf3c5e9895c0bd6f258.nq.gz
    ├── 4abc7a90973ec48b251d3fd4a8b146522f827214.nq.gz
    ├── 4ae98d6a4105391041582714a4fd0a2c57e38ea4.nq.gz
    ├── 4b0b8178320d8845f586410ee2d2577f6566b31e.nq.gz
    ├── 4c605c41a4dc82d659451fdc82cb51ade43bdaea.nq.gz
    ├── 4d2c36246f2b9a4d9f611e48553b5545261f781b.nq.gz
    ├── 4e4e5d68fcd84e00336e9e125c47fac4e6e76606.nq.gz
    ├── 4f0bd7ec14e848b8ffe1b78b1652e0f9a5967feb.nq.gz
    ├── 5028897e1b985a16f755a2cdb4078fd0fe6d200f.nq.gz
    ├── 503b97ee70ad32844e99816107e41b2bd39d625d.nq.gz
    ├── 5390f85b63604860ea5ef6e00cb6a90af073ef12.nq.gz
    ├── 53b110bfa7d26f15d09898697b307207628dcada.nq.gz
    ├── 54d472e1f4da9e2134a99a521b6355fe2be32b56.nq.gz
    ├── 563482d1aee40afbe44219dc518fb3e793eceefa.nq.gz
    ├── 565fba3aaa8bdec0315fba2f2cf870ba908588bf.nq.gz
    ├── 5663eeb41dce3521e5c47624569bba4f737b6986.nq.gz
    ├── 5699d7518539d6262f53d05903f19ed35298e596.nq.gz
    ├── 56d7986b860eb2b4ab4955753622c446291a57a5.nq.gz
    ├── 575f67fd50ffe2d14c7f45b286cfbd8c30ccad3e.nq.gz
    ├── 58c96269d4a8b38f0533ab5c88f53a7fb19395bb.nq.gz
    ├── 59953974f49923e5f17d983d5fdf27bbb72cd110.nq.gz
    ├── 5a2f836a61443acd5e7e95dc36c224ed64d7d99b.nq.gz
    ├── 5a5f8543eb80f39dc822f5769519f7ee5a02e257.nq.gz
    ├── 5a960902776114adccabf34136fd343d87bce916.nq.gz
    ├── 5aab382a41dd04bc7f9da715b9a0101eb5c485a6.nq.gz
    ├── 5c39eff2667c1856fb97a56a05bac32d31d7a540.nq.gz
    ├── 5d34025612f6b9f0d356db3b5ffa982c5762c678.nq.gz
    ├── 5d9c6c7b9022b41903323de4cfa224249a2f8ef4.nq.gz
    ├── 5de62b2e91ca1c4643b898214dec912569826008.nq.gz
    ├── 5e5fb3b74f92c6bed5f1d5c096db675fd91aa5a0.nq.gz
    ├── 5f80a713ca25cc7da269fbcee1b2347f29abc767.nq.gz
    ├── 5f98e805b6f38454e7cc9adaacd19642144a16d1.nq.gz
    ├── 60a86f3f88b25f5a752dba075acd1d54bb98b813.nq.gz
    ├── 60e8bf80333546dd3d3179713b571627f779cf26.nq.gz
    ├── 6433a36a52ba9b95fedc4022fc3c0d49007b0540.nq.gz
    ├── 662b04e20f50f8f20545527ff23b9f5d626f342f.nq.gz
    ├── 66a04d8615d2d609b4e01a66542805afb9d517c9.nq.gz
    ├── 67dd27c25046d293656006d010e2550ca7b91917.nq.gz
    ├── 6895a924c31241f8120a52f48724ea7906f9ede4.nq.gz
    ├── 69251edc231f14e30f5f04b9ff83cc42b074fde2.nq.gz
    ├── 69541979461a6580da63c51d36576e3f85739409.nq.gz
    ├── 6954a85328bb47491b286d11febe1994d72b7856.nq.gz
    ├── 6a9c86c0260f5a2ffc93a31dc5a79bb194e60660.nq.gz
    ├── 6aa39a59a1dd68d1d56a2188d22204aea12601fc.nq.gz
    ├── 6ac2fa9e6fd507880786f47b03cd44bd6d0a1631.nq.gz
    ├── 6b99d30e82ea36a473fd202c485f42278678a83d.nq.gz
    ├── 6f1cdd2d8ef461eb6de48976e4e43d4132186c62.nq.gz
    ├── 6f30b1f3e63a22b21b502c9496fbd812327ed0d1.nq.gz
    ├── 7052ff2ffdcc23339cf72fe4dfcac01427a7e79c.nq.gz
    ├── 71e7726dac6ac942f7ac64f69faecf28d7ddb842.nq.gz
    ├── 72cc27d8472bac9bc5eb31b88710312a93e7b6f6.nq.gz
    ├── 752009535115eb84a03743f803932b152dedb26f.nq.gz
    ├── 7522a515faf29118a3c1582805d41c5ca569bb68.nq.gz
    ├── 76326cc628fec353c0c979cbd49178022c98e091.nq.gz
    ├── 77d103af2eaafc13f42a9a97ddb4534b1623a2e9.nq.gz
    ├── 78a2074671f35e065425ec48997ef1aeb96c3e55.nq.gz
    ├── 793ad9da116dc4ff814f040d9bf5790671c394e3.nq.gz
    ├── 796d61911c856d318b7f83b283714edb06bc9f87.nq.gz
    ├── 79af080f9dca31843cf16623505380e51f5253b4.nq.gz
    ├── 7ace24299761751bafdb4236b11fc3940271a329.nq.gz
    ├── 7aea2a3291de5ea4624196a3e716c71b8e1beec2.nq.gz
    ├── 7b31ea0c387718b8a87c7d850a5be017af1040d7.nq.gz
    ├── 7b46fac762a00866d2574362d0413a990d94b8ad.nq.gz
    ├── 7d1f6ad0cf92a7587d3c7fb7237829d3ab654218.nq.gz
    ├── 7dc5b20cd2102a2823a485c7497db8c6d82e01ad.nq.gz
    ├── 7e03b583ec603a420a97d57d48cab7b7aa5489c1.nq.gz
    ├── 7f5b4f478658f8cbd661b92240278f063d93f5e1.nq.gz
    ├── 80f7391fccecaaea6458b024d30123fde4491259.nq.gz
    ├── 8100c4120d8510fdc11312bb6e59deda2ab9c655.nq.gz
    ├── 81d330a02e32d929dcca7ae99b5a0c95b04175ee.nq.gz
    ├── 81d63a26aafda47d59f251302e76f11a5f56c955.nq.gz
    ├── 82cb9f6d8a0e6840d968c58ed5bd055affb33051.nq.gz
    ├── 83890a24c3eea9ecd3e531664d6cb6f6607292f3.nq.gz
    ├── 83aabfc51392215771bc872ca2b82df2bae84e30.nq.gz
    ├── 84c55a532091d8c4a4c33f611db613c741eea556.nq.gz
    ├── 856b0dbaa9d2498ae8130be0b28293a9ddbd90e8.nq.gz
    ├── 863d4de6686bb94349c4d50dbe7ad28d6ef7882e.nq.gz
    ├── 868344fb9ec3f38858f9832de969e32cc3b3b91a.nq.gz
    ├── 87d710b631520f33ebfac094470d50c5cef62839.nq.gz
    ├── 88900735ffa0845fbd6b9d749e73b923bc4c5aa9.nq.gz
    ├── 88cc73a7bbec843334243dc7b753b75518078349.nq.gz
    ├── 88de209f9c79dbacdbf437ffb271141a70f80749.nq.gz
    ├── 8bf21511904d6d307de0f18ca4960bbc345b3f7d.nq.gz
    ├── 8ce9086bece38a3dd8919c0d262df3a6c337e311.nq.gz
    ├── 8dd020d252cda2794e111942ca46ce59555daaf1.nq.gz
    ├── 8df54ba70ec833eb0277d269507f284ff5d283ed.nq.gz
    ├── 8f377d6bfbc978e2daee361eee62f9da3c3b14ed.nq.gz
    ├── 8f39c790b1b96fd773dfe32584ff73e2b91cf81a.nq.gz
    ├── 8f600e50e9343853a939e98e4e398cc7e6bd2b39.nq.gz
    ├── 8f80dd11da11ef80f10346daccd02fa8cbb2a30f.nq.gz
    ├── 8fa9c05b459216dc073e29cbaf0117ad08e036f9.nq.gz
    ├── 901c15a617a1162b08758cb81a21ef369510274c.nq.gz
    ├── 9031359a7581f9180d91945e36b969641b8ede5e.nq.gz
    ├── 9332428b9fc8781a10bd5f95cccc127192ec627d.nq.gz
    └── 94db22c38fc9f96d4498c526c0430dcf1dcf78c0.nq.gz

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

[apple/container](https://github.com/apple/container)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
