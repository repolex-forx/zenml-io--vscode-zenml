# Repolex Knowledge Graph of zenml-io/vscode-zenml

RDF knowledge graph data for [zenml-io/vscode-zenml](https://github.com/zenml-io/vscode-zenml), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/vscode-zenml
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e43dcca1a0a3870cf1b821e13b6bbda1114df498
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e43dcca1a0a3870cf1b821e13b6bbda1114df498
│           └── chunk-001.nq.gz
├── blob
│   ├── 00918f1041db26fa8a04f0010e155efc38f09a9b.nq.gz
│   ├── 02044f7689829b53bea63f20372205966185e714.nq.gz
│   ├── 0287fa918455ab6188c542882517f462b97319d1.nq.gz
│   ├── 02f56789571d5b9c0fdd441ab83ee88056ab6d29.nq.gz
│   ├── 03f23e706f4f58006d072f34dbcb8b9bd719b3d4.nq.gz
│   ├── 0455e912e4454c7749c581b6c97d98a0b6f7f817.nq.gz
│   ├── 06058afef91deae3abc110bb8f279949e49779da.nq.gz
│   ├── 08498be46abbf83a2e36f5efd1412958822afe56.nq.gz
│   ├── 09a16ec7a3ac3b63bcd064b286f858d9b6c4fd88.nq.gz
│   ├── 0cfb0e23a77831f085fa96a5dad2ed44b5cc9387.nq.gz
│   ├── 0db72e6e0217ca67df3e7f714f89c2439ffd1c79.nq.gz
│   ├── 0dc07df0bdac1e9187c30c8025cedf6aff2b2256.nq.gz
│   ├── 0eca0fe48659ec779e244e860c5fa666e71a6f7f.nq.gz
│   ├── 10a76b206f18c66a8954d983d1d34069c550768f.nq.gz
│   ├── 10dc5c51e75007a693fdb7bcdcd548d7e297b11b.nq.gz
│   ├── 11485da6d54899c2dc8745bf32699cead98418c2.nq.gz
│   ├── 12380f38f03c5cd024093fb70b105e6c6c70acba.nq.gz
│   ├── 12eebd705b7105d0053e1c72a2f5fbe212c806c2.nq.gz
│   ├── 135f32f32ca04f1f0e7b943608d3ca0a3a5afde0.nq.gz
│   ├── 141ae28bdf3b8dd4de62773fdd0e74b56815eb3c.nq.gz
│   ├── 1466595f2c44bfaa0606513b28f6693355da7071.nq.gz
│   ├── 1689c30cdf98d386ba69525a508886116062e97c.nq.gz
│   ├── 16ae5f3968445e7195087bec9c879f89a1f9e21a.nq.gz
│   ├── 1931076f21316700e4e31b1f27ccf1f9ea5f3a96.nq.gz
│   ├── 19bd8ab25968a852fcb5a533a4475256c9c816a8.nq.gz
│   ├── 1bd53da7a10e39aad34a4f2eb92ff1a5e26fa801.nq.gz
│   ├── 1d412fe7789bc968d15c6b0bcc1731af94ff5f14.nq.gz
│   ├── 1e77a71e8480a1dbb6974ef801ce6a328a130708.nq.gz
│   ├── 207d1369a759dba7d83cf52d1e30bbdedd1c292c.nq.gz
│   ├── 2377f48a23963c0bd8b73c8496354b2cbedc180a.nq.gz
│   ├── 261cb5428fab84356277ce1670aaf626c15c5176.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 27217957f8c852dbdebc51a1ab43ec98a836371f.nq.gz
│   ├── 27ec282dd4711760bcc707e3b668fdbc447358f6.nq.gz
│   ├── 283b4fc2d75ee9fa39a1e1737e3ef5e3b0e804cf.nq.gz
│   ├── 2b56cdeeb373893bf0ad50cf5f58ca5e09ab31f4.nq.gz
│   ├── 2d7bb7a92ea30509fa8ba47af9f077974e2c25aa.nq.gz
│   ├── 2dd8d0b3c86016d4226f59ce6f923ff6943c1a0a.nq.gz
│   ├── 2dfb80d7e874ac17b6353c6e158c8a7d4fa0cd2e.nq.gz
│   ├── 2f6d03a4e64f2cf093711ac08c7de95fd349be25.nq.gz
│   ├── 3014e42df081f3ba2e1b907c6c6665aa560e4391.nq.gz
│   ├── 3027ffbdc50bf9262eb0c08b8bbf32c47160f47d.nq.gz
│   ├── 30ef8bbdb3b61963cb5b150c4ccef1f09c3f7811.nq.gz
│   ├── 321a5a363aacc29748051cecf71aeb1e7dbfb787.nq.gz
│   ├── 32f1586c6d0eb82506b5ff572cb3a0c304070791.nq.gz
│   ├── 379880974d40e6b2b037d9683c37cfbc16d26f9b.nq.gz
│   ├── 3bc6150e1293f83393f92eeb4b593600fb37814b.nq.gz
│   ├── 3c99500500de8901230ad0e1a6f16eea69ee1693.nq.gz
│   ├── 3cd5825c7386e634f8cc04daf35216218a38feed.nq.gz
│   ├── 3d750c36c8f19a631da978c13e4797b784898d5e.nq.gz
│   ├── 3e2eef803ea3c30da0a3cf2027a3a3a258e6ad18.nq.gz
│   ├── 3e966211da4a1d06eada5f4114359a061cfb1ce0.nq.gz
│   ├── 42a1c98ac5a1125154adc313f67569191af37a1d.nq.gz
│   ├── 42fd52cc922193a8ddce32eeeefc6ef1430b9fce.nq.gz
│   ├── 484b67e40d8dc40f8dc0ca027246a00b91d8cb37.nq.gz
│   ├── 48854831a54ea375f3f9f18ecbf6789a9dbe354d.nq.gz
│   ├── 4894209ebb08c601f243192ef9de91ed1963aace.nq.gz
│   ├── 4b3c649fd42052ac65343c6ac77c9133b4d2b7a3.nq.gz
│   ├── 4c53142d99b97c895b6240d05c4ccc8cacecfbd9.nq.gz
│   ├── 4d3ff6f7889df898188717973e4598abeb2943cc.nq.gz
│   ├── 4dcd302aae4892890ee082df55483f86461afb81.nq.gz
│   ├── 4efbfdf393c2074729b870eca7f136c9c6b5043b.nq.gz
│   ├── 4f68bbffa9903f308aba56c79d5fa270568908d2.nq.gz
│   ├── 5052fa546f285d76239a5348fe8820edf2e121be.nq.gz
│   ├── 50b12f09228da713bff4036a4764879a11f026fd.nq.gz
│   ├── 517bd26a04acbff1951d77a238fafcecf7287739.nq.gz
│   ├── 52079c6e3fed611783d80ed5dccf8fac25e511e8.nq.gz
│   ├── 545dc472ce298b12e8566593e2046ba74b7fc54b.nq.gz
│   ├── 54a15036f03af23170426cdf65ee7b1d321ab506.nq.gz
│   ├── 55faf60231f02810b38fd1dfeb01b65e3360c53c.nq.gz
│   ├── 583129918df49e90d16e6be7155e461d03b7e62a.nq.gz
│   ├── 5847eda914e53d09deba152942e13375ae166755.nq.gz
│   ├── 585c6b8bebfb7a59fd6456f091b2f876e3c4cb32.nq.gz
│   ├── 5920956ce7e03ccee265fccdc852ace6a4daa4dd.nq.gz
│   ├── 59f6f90abae5715ae4734c709f22af84add0abbc.nq.gz
│   ├── 5a3d2b9e04325d16a40cc88c1be05b72a106a8b9.nq.gz
│   ├── 5acdf568e29b1f8ac46b807d13d5286be91490d7.nq.gz
│   ├── 5b9cb75537364118e8d4f6828c13e6b2b14446ea.nq.gz
│   ├── 5ca11c4e6aee45d685e91f612d8dc45204bc6957.nq.gz
│   ├── 5cd4be391196befcc6eab795f70fc2d8a6778c47.nq.gz
│   ├── 62a3905c6ce2afb45a4904c3b2f1d5efbc20bc78.nq.gz
│   ├── 62b616700b75ad5697525becec1782c1337d2414.nq.gz
│   ├── 62b9cedda590ca673c07ef92081569322497823d.nq.gz
│   ├── 64adfd9773de882d3c184205702a0e8859179b82.nq.gz
│   ├── 677fe10797784184dd77bcd7c157888a56d4722f.nq.gz
│   ├── 6999fcfd4ca67b6c2c74fa3a5c4f8a0a1dea61f7.nq.gz
│   ├── 6b6e2399e30e2ea4fc7bdbbb862ad712bc54e04f.nq.gz
│   ├── 6badd146727ba7c4ba8787ad6c03da0b3a79c540.nq.gz
│   ├── 6bc872731a2afedc964b4609bbd179c7411e49f1.nq.gz
│   ├── 6c8771b95e09bd8452ae3c5f2d1a0d075f138c36.nq.gz
│   ├── 7253a5ceee98e9a69d5e36d9d2e02969757bf239.nq.gz
│   ├── 73368e7d04ac33a633744a956614989fb9ba59cb.nq.gz
│   ├── 74d939c865f69937a0c4e510d29c7a61c5fd5991.nq.gz
│   ├── 758bf18f5d781a7482a7badc165d9be6095cd482.nq.gz
│   ├── 76c725faa04d98d5583bfbd791418ddc91dbe69b.nq.gz
│   ├── 7739b5ac59884ec3dd1a7056a335f7a0e900adc1.nq.gz
│   ├── 786c935f28834a05966bae77a37a965cc3119069.nq.gz
│   ├── 7bd5f0bf64eb69d3e7fcecfe1ce80c04408ac76c.nq.gz
│   ├── 7c0d8fa85f1f06bd175d97fabf449f70beb94b9f.nq.gz
│   ├── 7ea491624f31f95ab4bf58b3fcac1e97e2304d61.nq.gz
│   ├── 80b85957430bd93a2453fba71c8e854e61b9a238.nq.gz
│   ├── 8192b174bc6f5212067fc2d2db007de5585417e8.nq.gz
│   ├── 8462ac363cbbb588b1ce456ae3d4640489807ea0.nq.gz
│   ├── 84635253b44d6a5fe11e946a0eb6b3f550132d5e.nq.gz
│   ├── 857fb341a87d9837d9d1d78731f1c53149efc2cb.nq.gz
│   ├── 8749d63ac562834613b96d4ace7599791aa0feb6.nq.gz
│   ├── 87e93f8d0249c298c7085e6868d1145d5ce9eb10.nq.gz
│   ├── 8844892c24b67e6e9cdffded6cc326ead10e00bb.nq.gz
│   ├── 8851c9016b32571a4af61f367e7a1b52a0de555d.nq.gz
│   ├── 88cf28d086327e6395ba1b75c1627836fbb4ac20.nq.gz
│   ├── 89f02f2c8c4e6b520b9e7c9dc5dbf37b266fa757.nq.gz
│   ├── 8bfbadf2704683e8d1ac5df03219646dd3e9e54b.nq.gz
│   ├── 8ca166fc562b8fe9405ee79e436b2a6b64032d5c.nq.gz
│   ├── 8e788a6617bc30ae3c0b35d08f966e236202f287.nq.gz
│   ├── 8e81ceb04e69aa60c9d7cee2c79682c5144b56fb.nq.gz
│   ├── 900ba9831ba13ee135ba1bf214b07f72ece41c42.nq.gz
│   ├── 901eb7ca6ef366e02a2e40b855281dde593fc9b1.nq.gz
│   ├── 908214109d031987ca6adc7598eea18aec3d88be.nq.gz
│   ├── 957ad47b098d7e3414f036a993b46c8122c227a5.nq.gz
│   ├── 95c2d69796a7659de73f0402bb849b2460171fd3.nq.gz
│   ├── 9632fcbf68ac20f1c0a0f5b8a82a2745e7def9ba.nq.gz
│   ├── 9649147fecb71281a37f29d1c95982bb21fe8781.nq.gz
│   ├── 969e56e457767eca322ae1331f20a2fcd1d199a6.nq.gz
│   ├── 9702acc9212540913a19fa9d5a503bbcf2773425.nq.gz
│   ├── 973fa955d1817d1563fef32fd43af6a38c333cde.nq.gz
│   ├── 97a6e208f82bc7b0535a216dbc57f4f2fdb335aa.nq.gz
│   ├── 9a4c55c63c4281604a9ddbd09d24d52ea4e617c6.nq.gz
│   ├── 9a55d856f9d409280a3bf2dbbfbc053877916061.nq.gz
│   ├── 9b1676281a7c1282389d6b55195989ebd374932e.nq.gz
│   ├── 9b7acf30a5c0cde46fda66d63b3c688ab12bcad2.nq.gz
│   ├── 9b7cbfa5e6280233a94545decb3215d040182202.nq.gz
│   ├── 9bea70550124603d7e06676a6ac82449dcba24d6.nq.gz
│   ├── 9d992d55ceef6a09cbc2fd901190ce0c33937cf8.nq.gz
│   ├── 9e05257735499149fc4beef4d5198cd29365777f.nq.gz
│   ├── a1a7fca0b08f51aa13c446ffd243c44c5356509f.nq.gz
│   ├── a37d98e3c15a19c5a3dae7fddcae61c86efba8b0.nq.gz
│   ├── a41114dca7d4c0d267d65d3bb2c23f45082dc2ae.nq.gz
│   ├── a5073c4ad18ae4cba40f073ff32d4ebc7563a9b6.nq.gz
│   ├── a522eade1c500a921b4cbc07ac453aadb08b5f4a.nq.gz
│   ├── aa1fce63ecaeb1909f625ff89d30478e86742bf9.nq.gz
│   ├── ab286d03ca7f938936dc89b221b9bf98186497af.nq.gz
│   ├── ac377b49eb8dbfdd29fcc906534688a1cd6631d5.nq.gz
│   ├── ac8c30133c499ad7ab147a3677a79cb2f1c27a32.nq.gz
│   ├── b1589f4a41386c466f26414ec6e6e57a579f2bc0.nq.gz
│   ├── b321042f4ac67cb28d70cacc8e6bdf363790a1ee.nq.gz
│   ├── b3d29f0c2dd36c34eb8f980062e9f2b6b4f5e3b8.nq.gz
│   ├── b52dfe76ca66d8c409ec743760d2c0314b2e0d94.nq.gz
│   ├── b62ba25f015a10788b8e1693a5678dd90ec5511a.nq.gz
│   ├── b6d27332edff7432e35f4275aeacf3fc73cf3d5c.nq.gz
│   ├── b8c844f79502e3d3af2c3e423960d034f0e5cb27.nq.gz
│   ├── b8f5e27ac9306aa7018900dbe7cb62a04d8bde4b.nq.gz
│   ├── b9301452855ced519b74e982a9f7714ee414b24d.nq.gz
│   ├── ba59e5e0d72b8e061459764177caff23c3ed584d.nq.gz
│   ├── bcc72cdd1f2664849b0b0882b4598e64287742a8.nq.gz
│   ├── be7be19bf4e8fe3c26d82362f5cad656ff693d8f.nq.gz
│   ├── bf68dd047b54a2ee665e131713bb94a6b4e81fb3.nq.gz
│   ├── c242decfd4c61f4678cef0a02df6f9b7af0145de.nq.gz
│   ├── c83a99037e6cb1a0003e6ae5227780de5f294fa3.nq.gz
│   ├── c97df4ccfcde065a01479d322ff48c7cf308e313.nq.gz
│   ├── ce3fab246c5a63b1db3c31711efdf402bc3c7a97.nq.gz
│   ├── d24a74618b2060611c44f6751bf364a3a70a2ae1.nq.gz
│   ├── d2b2420c94d114452c45a874cc76f857ca3455d7.nq.gz
│   ├── d2b80b948619364b6cdbf8e95dce628b16538b6d.nq.gz
│   ├── d450cc3897581941e4ff49de6fc32aa26ce9d640.nq.gz
│   ├── d83bd1ae59952d16a240096762ea63b4b9e19b0c.nq.gz
│   ├── db15df687c9e2254cb75329674e0d73473fbdcd7.nq.gz
│   ├── db22fde25e0979c40438ca95abc90caf39092ad3.nq.gz
│   ├── dba672623f421d433e18fbca7182bf8d36eaae15.nq.gz
│   ├── dbdd83af9e3cf233d95117b4d6de1fe3475a55a1.nq.gz
│   ├── dc7859fe9ece26cc3f4d45e723749d9a85085348.nq.gz
│   ├── de1a61c679743ea48b363e511afbb363123872b9.nq.gz
│   ├── df7c5471f62df5b38b9cf0ff913223fb3644f2f8.nq.gz
│   ├── df8a9f6ec449fb1e863362e6abfd0ac6e7aad10c.nq.gz
│   ├── e02d928d68a3264c602cd02c429faaf0c7e446f4.nq.gz
│   ├── e0cce1a8df40ef1f859342d62f860b4cee767e5f.nq.gz
│   ├── e409ef652cc0fb27cd0b147a126b3a4f388aa8d8.nq.gz
│   ├── e459c03e9ae0682f4b4d9ddb93aaed61713b2f92.nq.gz
│   ├── e45d6f6f5c80bd4252e1879aac0be97a34b9bfbc.nq.gz
│   ├── e626cb86b13e7c5a21367838307052d1b77ab528.nq.gz
│   ├── e77428b806f6308fa036f784eaa1fca6f6acb7f6.nq.gz
│   ├── e86677a7dbcd3345d43eb72b902489e9dd13086b.nq.gz
│   ├── ee00f1e6386dc3ad974517aea2bc3f8ee08f5a1a.nq.gz
│   ├── eea342d8d17fd340c511f4a3923998b15f31a645.nq.gz
│   ├── f0a4052db1174d811c67af1785cd6011a8553926.nq.gz
│   ├── f20e9eab649f4abccdcc617fb94160b6f753b471.nq.gz
│   ├── f3c3073940b58357a2f2145f5e8da0fbd042b389.nq.gz
│   ├── f6309696771475c09a556ceee82b100c6941efb9.nq.gz
│   ├── f700344e43cfe080c0aef863c659dcfd8186070d.nq.gz
│   ├── f9566cf5227d5fa1a3ebebe74b35bdf9896b6705.nq.gz
│   ├── fb33f1185a62592baaf2ea2b9244cf663fd5f675.nq.gz
│   ├── fbe6ca4fbc81aa788eb2c487b24f9f74283a136b.nq.gz
│   ├── fcec292082ad57895cc00fccd52dba1b022b906c.nq.gz
│   ├── fe3625e7e2e78324760987d6e14dfbd3d46e3b95.nq.gz
│   └── fffac9e15ff4a91ea3920e0dcc59b5a23389cf32.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e43dcca1a0a3870cf1b821e13b6bbda1114df498.nq.gz
└── issue
    └── issue.nq.gz

11 directories, 200 files
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

[zenml-io/vscode-zenml](https://github.com/zenml-io/vscode-zenml)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
