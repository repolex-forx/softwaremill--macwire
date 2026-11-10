# Repolex Knowledge Graph of softwaremill/macwire

RDF knowledge graph data for [softwaremill/macwire](https://github.com/softwaremill/macwire), parsed by [repolex](https://repolex.ai).

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
rlex download softwaremill/macwire
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 10571d5991cd17e7d38194be7bb79f978fd90119
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 10571d5991cd17e7d38194be7bb79f978fd90119
│           └── chunk-001.nq.gz
└── blob
    ├── 00179f5acebf25bb1139d233093999d7a7bb572e.nq.gz
    ├── 0194c9f7650766e30a524183b3870590dd1e430e.nq.gz
    ├── 01b88725d7692078420f3334fb15550ab1941ef9.nq.gz
    ├── 0204384537a3a231b35a089f4c866a400b66ab01.nq.gz
    ├── 0205aea444732961b2ce30ce64a880032d0b6ae6.nq.gz
    ├── 027eaa4fc266d18883449de5e9a5860c3988020f.nq.gz
    ├── 02f9ef8a4b1543c5ac84c997e428feed5222b2cb.nq.gz
    ├── 030baeedf85a26a879f608aed8c4f6fd82e33078.nq.gz
    ├── 0377a63a729c0c09ac42b00438a0a26afab9c02a.nq.gz
    ├── 046705b9fdc1f619be19e97672fddcca1985d3db.nq.gz
    ├── 049dd5c2443f6040c50babf12d566fcf6b07139c.nq.gz
    ├── 04d9adf082334a3d771017563d76b9a1fb80c1ea.nq.gz
    ├── 063858d5766b09cdd55b86de47455f71fab8fff1.nq.gz
    ├── 07b5ae08fab5cc64c43bff72e9139692bf514384.nq.gz
    ├── 07cf8544fa73907cd3de393603dd684c5b3c69d3.nq.gz
    ├── 08e2266cd5957d612d2d58b27089ac6aead55dfc.nq.gz
    ├── 08efd88be380857cd75c64d7fdbb448bc26006ae.nq.gz
    ├── 093afe43510f89d042bb48adf55dd9d70078ff67.nq.gz
    ├── 09b8dd16bbc139f6ad8d6d29b13bc2f59242c889.nq.gz
    ├── 0a353b4c032690d67cbf37e85c6698d1f20d89e3.nq.gz
    ├── 0a4944534770df98db75e5dd44ffc5e9ffd7aa49.nq.gz
    ├── 0ad7d248e1fb82a9bcc3e40598d9329c37766e56.nq.gz
    ├── 0ad9374d51fb4a027bcef51a21a8b6f7f253abf5.nq.gz
    ├── 0bc9ac01af6d9c87b567014446aeb02f3a451eb5.nq.gz
    ├── 0c7e2b5f258ac28ef3a83a2b98738ae60305561b.nq.gz
    ├── 0d7c2773ebd2ebcc1b035cc6af6b3a3eb2bb93a6.nq.gz
    ├── 0dbfb65bc3ca42727771c814cf7b94087426cc49.nq.gz
    ├── 0de5b44eb4bc2ec295469901bedfff4d4e6e704d.nq.gz
    ├── 0e8a5a8d997b9f705de601500e778a15d8dcc0bb.nq.gz
    ├── 0f83ac7c12f5607634e04559e0e80286dbd020bc.nq.gz
    ├── 103464b842b6b1ef10d5f55743ad7517d358d50a.nq.gz
    ├── 10450a50c83562e99c75750e5936016df6c23728.nq.gz
    ├── 10513c1b98198bb52d5c502b35e3859ae4f4bb53.nq.gz
    ├── 110cf8126ca986a62bb7693f8e4133b7282d629b.nq.gz
    ├── 1170fecc99b94c0ba1898983456a017c2e5523be.nq.gz
    ├── 11749dbc0923a18ae47b2c3e186c4098fc1e8e79.nq.gz
    ├── 12a328f2c2fc1a8f3cde661f1311ecfa08d431d1.nq.gz
    ├── 13b965cd149da7781a41bec1bd1e08ec7952be68.nq.gz
    ├── 141eccd658e1bd0417334d3bba86c6ab229e3bbe.nq.gz
    ├── 14c8a57d729c9946b1efe174b12a0a7b187700fe.nq.gz
    ├── 150bfa04d1783ae195c5c4dc9030a691a02b15fd.nq.gz
    ├── 158f2fc77fddc947a908ecf37c2a6c029c8fbd8f.nq.gz
    ├── 166e03151d4e01425fa19b27c125728ca11b982e.nq.gz
    ├── 17572a14f245500dca3c26b778c30f03629d1f1b.nq.gz
    ├── 176a863a56213fba12d1d96f9dc5e315f006813d.nq.gz
    ├── 17ce148664585abffbb418911fbc5112ad24ad57.nq.gz
    ├── 18b08dbdb4536cb8ede24d36cf56097d7eed4a77.nq.gz
    ├── 19036a282d68d757c78b0e7871adec698d2b8d5d.nq.gz
    ├── 19955a5a482fdb0f66f98766c9926c174fcce247.nq.gz
    ├── 199e87f5b18456bb09abf7a7f3d86ac8c49912b4.nq.gz
    ├── 1a80b481c9a95f8ba17aa0e7d49628a6d53a6baa.nq.gz
    ├── 1b0617a484265d68b0a2ab244cc7bccc56e95e07.nq.gz
    ├── 1b294fc1f95ee3a3015c8f0d839d3c13085c5620.nq.gz
    ├── 1b3a6773942b7c6e5c4f26ea8ec72b3d448fb46f.nq.gz
    ├── 1c410ceef50ea9d3b60cc742b5cbc0cf5a578c68.nq.gz
    ├── 1d3f16c5a8df94e1025784c7d9f0ab95b8b5b838.nq.gz
    ├── 1efbc79e71f766efdf060e0ae3e95a0159ddd7b0.nq.gz
    ├── 1f843f146e32828ebc3ef3d5f12482aa53ce377c.nq.gz
    ├── 1fcb7c4ccc6a90508a9cf6d1955db3b038e3bf23.nq.gz
    ├── 215eaeb364720583c1b09a477d2c3878944790ac.nq.gz
    ├── 21743563774b2439465299057ef615de89b2b25f.nq.gz
    ├── 21855ed403ce80b535282f5dc7addb031dc564ad.nq.gz
    ├── 2265a2bd35cbfcc125be55e74357fea7c631f429.nq.gz
    ├── 235223a2ecd6bbce334c0bdaf95228543a53f60f.nq.gz
    ├── 2402818d91c7c994d046483163dd578784a4a596.nq.gz
    ├── 25d970efaebe80c9c9bf69b73ac24758756c436a.nq.gz
    ├── 26f22da7d3e53c2ddc5924c8f952800415b58fda.nq.gz
    ├── 279281fa61abac1020cc2cafe47282195b041ed3.nq.gz
    ├── 27f6b9892417b754a3cdd2c1bdf9e8f7c8023c7d.nq.gz
    ├── 286df37d00f3f79f8d528a44b0cf847af0f3899c.nq.gz
    ├── 299a92dac8f9d6cfd24178c525106b0a78c8ab12.nq.gz
    ├── 29b0fdc415860af4c52d06cbbacfb85fcd255bc3.nq.gz
    ├── 29c9b40862eb8fc832559c860ebeaf93776eed2e.nq.gz
    ├── 2a417e4532898034ff8c8a703741227be5a2e24a.nq.gz
    ├── 2a6cd9905d8b0201ee4fc21bd0d32bafa5634930.nq.gz
    ├── 2a857cbf9d3bb6c717aa8d7b573cfe31df3137e1.nq.gz
    ├── 2aa303e4ec6f9be789edbfaefda9a696a96e22d7.nq.gz
    ├── 2b39dd4c845fcabc63a21c915446421095cf6eb6.nq.gz
    ├── 2b95c041de8a06bd82cb06a187cafc5d000cfaad.nq.gz
    ├── 2c3e9b6ae37e7ca0d183fa7c8a7b0d4cc1299a5f.nq.gz
    ├── 2c74367fa7d5850e038324fc1617cb2e44022653.nq.gz
    ├── 2cb024db66993019285d1a0fb5ec6a3760564ab2.nq.gz
    ├── 2cd402f796eb3ee8032502e77808eb4db9eeb76d.nq.gz
    ├── 2cfeddf9816e9de1d26698a36c22102db9bcc88c.nq.gz
    ├── 2d0be807f41934d2eea5aac80d013e657823e2b5.nq.gz
    ├── 2ef1327d0a79b871a28928d66d6d65ab8a782180.nq.gz
    ├── 30556b86382a759afe3f5e399710c74f4bc8165b.nq.gz
    ├── 30c9ae0a73dba64ed5c557552d88f7587847cb9e.nq.gz
    ├── 30ecf336e00e21e6ce23547cac9722afb15dcefb.nq.gz
    ├── 312c494cedafbaf1305c2d0cb3fabe7f0bb4ced5.nq.gz
    ├── 31c4c9ae4935cc29ed72b5d58fa351b9b96ca533.nq.gz
    ├── 3269c321d65c1741d7e5883cd57929446f5815da.nq.gz
    ├── 3425e9adc01812b8eaba3e7c1680d80cd5fc04fc.nq.gz
    ├── 3531c00ea8e811597cce712bf109bcb52ab735e9.nq.gz
    ├── 357a53762b0e7140c6ce863d93d065a3288e9f49.nq.gz
    ├── 361919fb9bc6b9b564fc89f9d4c0e75cc6285d42.nq.gz
    ├── 3621bc3d3134ee5bf60fd6b38ee94996ba36aaa6.nq.gz
    ├── 362cf04e222a6169fa4d502c75ee6cf9a6690d55.nq.gz
    ├── 36658d34101e93f5b94f6a766dc6323100204147.nq.gz
    ├── 366a3e4d469397e1a904ef3ac6da6746f7680c50.nq.gz
    ├── 3703ef046c4b42bbf1ba19ebcab702ee89609350.nq.gz
    ├── 374f8133d34525ede46a84abcf9b843c1d04e875.nq.gz
    ├── 382096892486f3a5f575dbfc00c0e52c512b13c5.nq.gz
    ├── 382482174fee772dcc448299c4a069ce102e7412.nq.gz
    ├── 38f2f3f1dbe321cd7e526986084c9911519bb073.nq.gz
    ├── 396ba2d7b3056c5ca2531d98061404abc955d46d.nq.gz
    ├── 3989693a02c5b7970f0a173c37e5413608233da1.nq.gz
    ├── 3a9418148f48c1891e2d955583bbf4d71dd1e7ca.nq.gz
    ├── 3b6288228333bee4f66c45dd2d4c579f16087189.nq.gz
    ├── 3be37b08bf989863abb8511c48f886691546ed58.nq.gz
    ├── 3d3b2c1b02ec1aa6fd7be87ee7662afa5a7e2c84.nq.gz
    ├── 3ecc478438af4cb4bc2badc8aec591f593b06495.nq.gz
    ├── 3f0e4eb49286f7c59787ff578480fe7497b09cd2.nq.gz
    ├── 419f21bd0f1eca4ac4e379a5778be28f029e6343.nq.gz
    ├── 425a33c063310b353838be2055c8c02e101e1e35.nq.gz
    ├── 42c1de2a9634ab2103c8b323d451ed5d0a92f70c.nq.gz
    ├── 435645af9c11228048be8f64012e33c8a03f9d07.nq.gz
    ├── 435dab630c9b6f174cffc09833a4279fd4ae1943.nq.gz
    ├── 439213f4138bd39eada16bacffbc364ae2946922.nq.gz
    ├── 43c6483092d362c06a15630cb0f43a2f80625700.nq.gz
    ├── 44a481cc97f8b5af6d91ae04002383d10896f48f.nq.gz
    ├── 44c503bc1c01ddd69c9559e5cc6d82dd9dc65d9b.nq.gz
    ├── 451ce710bfde2d14b44bfa7558ba7c864662bf90.nq.gz
    ├── 4694672ceac304e1d7890f856e3970ffb9ab42e5.nq.gz
    ├── 47a75b5df06abfae8270b5cb3cd1f98b29b3560b.nq.gz
    ├── 490cad515027d3f867abb064e75ad1cf4fda039f.nq.gz
    ├── 49db9f2560d6475dc460aeea1a039815480579f1.nq.gz
    ├── 4a598872ee871389a7ee700ed5a608b94c26423b.nq.gz
    ├── 4aef91b3b83ba8156082b0ea5cb56d99f5db0227.nq.gz
    ├── 4bfa1e3f620e47d2679f83b150a49fb06ea1e645.nq.gz
    ├── 4d21b51f218799222cab1fc78af8cc739485abf8.nq.gz
    ├── 4e4f50c74c5da296f98741fb5677c2fa855fe2b3.nq.gz
    ├── 4ebff72140d1ac34b031968ba3ddb9570a23742f.nq.gz
    ├── 4f5df706c16cf3853a4afee9338819f4ffbed402.nq.gz
    ├── 4f6ed4d8800901df84ce9aaba910447632dee892.nq.gz
    ├── 4fce1923dd50405f4670a4278d1dfbaca8010204.nq.gz
    ├── 50007cb9b5202d4901a3822f442543117b88f003.nq.gz
    ├── 521a54bc4cc924042c95e8f236f9b485bb684352.nq.gz
    ├── 522474a520bacf952e43dbcf81830634fc253d8e.nq.gz
    ├── 522b4de1e894fe7f2f275b778fd6040ee1c8739c.nq.gz
    ├── 52af946f3ae0bf695da60d66bb6e7c084ddb22a5.nq.gz
    ├── 52d264bf0130ca2185f246f12d0ad6efed6231f0.nq.gz
    ├── 52de1f3b30e53828db9cf165c71da9725615315e.nq.gz
    ├── 53b95cce60302591e375d52427e23c18e7ccb41c.nq.gz
    ├── 54050317593b2c816514ee40a34afb2b63e8c7c9.nq.gz
    ├── 5496ae561c977eab31d04e6110b7aeefe9da63db.nq.gz
    ├── 54d639ebc53c92f027ad3613a8a808dafca7b32c.nq.gz
    ├── 54d6e452a6962606f949574c98598c43252ab8d2.nq.gz
    ├── 554faed30af0f2f2456681ab2975684fc6dd64fb.nq.gz
    ├── 5565ec533fbf4953e2c77fdb25214ef6774b90b6.nq.gz
    ├── 55d98971c1f2e711286185d24c5f19fdcf5a08ed.nq.gz
    ├── 5629c1083e35efcf4874fcf352a5c8d6f4d161e0.nq.gz
    ├── 56cd6720026dc6f2d990bed9de846fe06d2fb64b.nq.gz
    ├── 570910f1cdf5f5bf299f1afddd92a5ced8da71e8.nq.gz
    ├── 57902b59f0a0fe15e0a2114a9c1b3d10d9082dbb.nq.gz
    ├── 592b567a2d33b63146a38865d46579caee3d14d1.nq.gz
    ├── 5967a32656bf95fb142d55553b6fd485d930472a.nq.gz
    ├── 59c35f0d2f1e5ba215ba8c04e14c90d7ee40ffa5.nq.gz
    ├── 5a70e3146d2e04ce86443f108baef22d206c2d96.nq.gz
    ├── 5b197769779ede04643be21b45f7890fafe505c9.nq.gz
    ├── 5b20c7ce77003dabd9b8edda964bfd776eb57c30.nq.gz
    ├── 5bdb1bc29103afb496d109cacd8a01bc51dd0e1b.nq.gz
    ├── 5c2fdbc57eb000ab6ec1d6f2e61e3a4b05f9e83a.nq.gz
    ├── 5c8342866f557b3d57ecd09088ac51cd31dd1d55.nq.gz
    ├── 5dd10871a459568c3c09a0f8e23d73d3d76987f5.nq.gz
    ├── 5ec4e732fcbb869b2a477ea0c2688bd6818d3432.nq.gz
    ├── 600d36a7190a8f72356ba6ee9318005d4bad3b65.nq.gz
    ├── 60453633f83389113bb254081d7fe68accdf8907.nq.gz
    ├── 60fe82555ab7e6f1be951ae9b109a22fccea11c3.nq.gz
    ├── 6164b6a366ca1282c824acf7d94154bee748649b.nq.gz
    ├── 619ccdb41b8e3f35a69ebd4648ea5628e44824bb.nq.gz
    ├── 62fa3b08590009fccb2d67e49ae851c6a6c00d85.nq.gz
    ├── 63594dafb30b621388f78073b975d0c9b51222f7.nq.gz
    ├── 6388c860f5841a55c97645e2ceec26f538ccd129.nq.gz
    ├── 648a8f7cdf4907491755de9169c4ff7164d695f2.nq.gz
    ├── 6503ad3474d8aaf3f3b599864237473cd923200b.nq.gz
    ├── 66affb7797163130edfe9619fbfd5032982b56f5.nq.gz
    ├── 6753d9f61060343d6cf95c061e25717352467107.nq.gz
    ├── 683f09d00f9d8dd6b6d698fae1e719b55fd051ba.nq.gz
    ├── 68b9f76436f11f6860a2ac4e6aa5ca6a9782f51a.nq.gz
    ├── 6931ec671f86fcc91c7963e64dcafe681e082e71.nq.gz
    ├── 6b48fb7bca3d6641fe71430488b7c180c6f6a614.nq.gz
    ├── 6cc03bc4ad00ee10921e00b6a0acd777087b11ce.nq.gz
    ├── 6ccc0fe38d97a0fb0351345d11265ccb4dc84b0b.nq.gz
    ├── 6cce575b8e7fe17f14141c626f7e951a040a183b.nq.gz
    ├── 6dd96b8cdc4152ea62a807fb3cbf2c64dc1456cc.nq.gz
    ├── 6e55091ff51071fcc1bc541576b1e238cdfe6edc.nq.gz
    ├── 6e99280f0466011a5aacfc2447c49e8916aa420a.nq.gz
    ├── 700afa00d87322aaf4d23d0e74295458db91ef3e.nq.gz
    ├── 701adebc0783fce82c9410655ef335e61de39888.nq.gz
    ├── 7076b7141b204e02bba3d7a847f672dffcf191de.nq.gz
    ├── 70b5a68d092b386d14a60a1cdeb3340ca91172a5.nq.gz
    ├── 70d11f4fd3e843571c4ce8d7bfcb04367e085370.nq.gz
    ├── 70e3d15137828d0c06177dcb4bb14c5921db3f6c.nq.gz
    ├── 719e3b9b8ec75d8dade87a93e228af5603bc6914.nq.gz
    ├── 71a82fab280b0ec727123783455d74d1de4688a7.nq.gz
    ├── 71cc72ad1e906c40857bd5e44189b57f518582f4.nq.gz
    └── 722015f3279b6cd96d2deecbff5efe13564f8d7d.nq.gz

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

[softwaremill/macwire](https://github.com/softwaremill/macwire)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
