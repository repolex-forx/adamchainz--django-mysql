# Repolex Knowledge Graph of adamchainz/django-mysql

RDF knowledge graph data for [adamchainz/django-mysql](https://github.com/adamchainz/django-mysql), parsed by [repolex](https://repolex.ai).

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
rlex download adamchainz/django-mysql
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bb19ecea2dee440c8e81f9364d60a5829813198b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bb19ecea2dee440c8e81f9364d60a5829813198b
│           └── chunk-001.nq.gz
├── blob
│   ├── 004f349da56e3625150d7213f40a28dc0615f6f0.nq.gz
│   ├── 00745736cb8c09418fd80cb770dc324a21207cd5.nq.gz
│   ├── 05f089912a556d345a17d33e707119837efa41b3.nq.gz
│   ├── 072259cf7ba24783244ac2cfe1e93d2914167187.nq.gz
│   ├── 0895f45488001621e0a77c32dd4d343375bb4261.nq.gz
│   ├── 09434275e9ca098652506c086bb63d8f98ee12ee.nq.gz
│   ├── 0e6214ab2dabe7281b80fb4c15577a828347f9fd.nq.gz
│   ├── 0e86d38710dc02f18837088dc5c1558272a78e04.nq.gz
│   ├── 0eb250ad4a7a90f38e3988020d5b19b95a164dc4.nq.gz
│   ├── 155325d989909c22fa00c13c3759010ff5fb0f55.nq.gz
│   ├── 187372f0775038be99ecd34b964e0c85815c77f9.nq.gz
│   ├── 1912eeb248594ef0d4d024813d29a75540d38013.nq.gz
│   ├── 1cdbc5b5e809e7a86ceef4f129e29a3b7b20714e.nq.gz
│   ├── 205ab9ad9df4ab629d1b7b8d8a72b41f44d8824c.nq.gz
│   ├── 2114d4e4d6457dd9323957883c517c11a974592b.nq.gz
│   ├── 22ddbb118475b52ce8ecba56d9ec45009923da58.nq.gz
│   ├── 24027bcd4e706022fdb7921a13e2810f106501d7.nq.gz
│   ├── 248187a59861b2fd140403d6372af4d0d07bbb1e.nq.gz
│   ├── 248468a02eb34a934fcc4c3a34372d64e52a1f16.nq.gz
│   ├── 24f5ee2c2727c463f0e5b863f8f3b501023d870e.nq.gz
│   ├── 2610fbf9ac5e613ae61f801d17bc75202e4d3833.nq.gz
│   ├── 268a9afb2c744c90ea59b1a435f42f1a17d17117.nq.gz
│   ├── 2718635853904f38b16332dda49af31b87b89369.nq.gz
│   ├── 2984b66ca4cdc8eea60a1e7ddb3993e27e2867dc.nq.gz
│   ├── 2a7f84f54867d02714727f82eef95d3be939d666.nq.gz
│   ├── 2cfd601d09bb3f953640cff773703136b6fb7697.nq.gz
│   ├── 2e59bc9c2394e5232de9c73a44659f3ae898ed0a.nq.gz
│   ├── 2e85218dd1e97a2057ee9e98b494d016d2d80154.nq.gz
│   ├── 3133c24e3ea42b270ac2353f33376f3795ee8df8.nq.gz
│   ├── 319ecade20b7f31be9450d10bc746f8bff558486.nq.gz
│   ├── 322877b4d4e3f54e74175ac8e71eae821f134f77.nq.gz
│   ├── 33b4f5886b13db3e41df05ccfa4a0e1001fb7699.nq.gz
│   ├── 366b05f9f8d9789d84e4e87d4d77cc5ae705b039.nq.gz
│   ├── 39250d4175d970a19eb9c0ca7de17c77270669d7.nq.gz
│   ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
│   ├── 3bb11d64544d558d7870938dbf76616171433f2a.nq.gz
│   ├── 3e042d198471a5221663f7f08cb73719ee1d1a87.nq.gz
│   ├── 3e24c60a266d9241157137c29680462378ea2158.nq.gz
│   ├── 3f37514f570a3bfe0100eba854bca4a02694e19e.nq.gz
│   ├── 40f4ac757715bb1a8c355eda9124141fdda3aeff.nq.gz
│   ├── 452c63d8cc9a8e72cc341b0c98ecb82448eba910.nq.gz
│   ├── 468c041dd9a8fec1b564f8e72d1cfd18ef98a721.nq.gz
│   ├── 47c1a11beae46f7ec858a00dad4141a922e5d462.nq.gz
│   ├── 4b231308890196a2174c814c4d1e28fce0573f78.nq.gz
│   ├── 4bf333d9b97e56d18d873bdc05ab405a5e4151e3.nq.gz
│   ├── 4c418417bcfc1af03e7c03660de1ec85e5032a5e.nq.gz
│   ├── 4d0f33401126cb14f94a381192241c5b67423258.nq.gz
│   ├── 4f47dc29759414634f2a64c1cd35b4cb78ef0d90.nq.gz
│   ├── 507dec32a4ac834b9cb6179127845482276811da.nq.gz
│   ├── 50fee9464d7606cd3192a09c000952bf246e0ef9.nq.gz
│   ├── 51c33ba6a3d6ffe50e9683b17aeb460b81ecfa81.nq.gz
│   ├── 52e128e501cd2cd1530197e73a7afdce6ffc367c.nq.gz
│   ├── 56ea46b111c8c4c807fa74f8dce75b4d06a020c8.nq.gz
│   ├── 571d6ba86ad17b8e6f06baf3dba824f36d227316.nq.gz
│   ├── 580c5812fadd4ff2e6f8c67f70e1ff7d590030d0.nq.gz
│   ├── 59d41792215cc9b7c9e131393e0c889230d4f9f1.nq.gz
│   ├── 5c788cad40d2f5d0199867cf0154a54a98c68d3f.nq.gz
│   ├── 5f475623df682b1125287231a37817f31504ef57.nq.gz
│   ├── 6939afce26dd3c3391eeb0104e6d73c64dc2cd57.nq.gz
│   ├── 695daf90a78a9b2d38fa44facab67f7093b861cb.nq.gz
│   ├── 6a554f53670c5ae84d35f1fa42592d6747b0361f.nq.gz
│   ├── 6b4c28931af76716d2154d78f849b4cc867f8062.nq.gz
│   ├── 6d7e94444034606cab0ed1416c0f4ff5dc369620.nq.gz
│   ├── 6d84da5216fd01dee7f362b609905434321128ac.nq.gz
│   ├── 70583ab57cbc3235b68b5ef6e8485b3335486313.nq.gz
│   ├── 70cb4d918e16cacb2e473e704c729e8ea2028039.nq.gz
│   ├── 72436a56911377a91ed915dc0d5cf5c0c7548eaa.nq.gz
│   ├── 729605e28b258ad99705208c520b1eb7a9352fcc.nq.gz
│   ├── 7561b584b6056551bbdf30e01a52e0ed51007d47.nq.gz
│   ├── 7582c4f0b899c82289625dcf853fc75bcc3de3f0.nq.gz
│   ├── 75eb32952d3280c111f96f57ebc4be240209036a.nq.gz
│   ├── 774cd0e571415866bc41519624c7bb63343e70c0.nq.gz
│   ├── 787a0c774623b31ae3c992f4a7810f7f5902f784.nq.gz
│   ├── 7f1d007c01048570d774e58f46203d3e92056c39.nq.gz
│   ├── 83287eb72dc5fbfbe3fa2946cb903c87a334fb61.nq.gz
│   ├── 8525ba2344b077c7de56172af6ac17501ad7215f.nq.gz
│   ├── 893ef836b5f53650f5af602599ddb67f2aa9d8da.nq.gz
│   ├── 894dd26f9e3dbdd0dce9f8847f22c376f414b785.nq.gz
│   ├── 8bd6628ae93c0fafb028ca52e9eb618853f4abff.nq.gz
│   ├── 8fd71efbe02c42d2ec287932ef5b607d5aa9eec6.nq.gz
│   ├── 939817c166e12e686b3c4e5dfad896e451a908d1.nq.gz
│   ├── 9628ae981534e26bce110914a4fc61148dffdff6.nq.gz
│   ├── 98819c779f2850ecee2520839d04bfe7fb3c685b.nq.gz
│   ├── 9892e3f9a23caccccbdfe15430236743621faa3e.nq.gz
│   ├── 9bf290e626bc7d84603a8fef96a51232528e6448.nq.gz
│   ├── 9c08950b4771af2a3d097fd94438d2ee83be40fd.nq.gz
│   ├── a0ba0abacd11b26b99a657a7ff50eb6e94ae63b9.nq.gz
│   ├── a2284fd0e8e460ccebf6de318e2591c567b63afd.nq.gz
│   ├── a28d2c3ef31d83252cde9646f301a584a43508e7.nq.gz
│   ├── a39253fb48561915d8e7630c2fef2688b0406250.nq.gz
│   ├── a3a887dca882670c0815062872d6244e749b971d.nq.gz
│   ├── a4b3841f233064eae1693b7fb3248b6cef3b6cc9.nq.gz
│   ├── ab6f22a0831d912b8de0d99666230065097e68db.nq.gz
│   ├── ac260a758eae507f49f9815492fb72f47904b0de.nq.gz
│   ├── ac4755dc4a7c855b7c50f94f44c8665b792f5b85.nq.gz
│   ├── adeac1877561c0171aea40b3267785fa3bb9902b.nq.gz
│   ├── b20b8bce1cc3b73b384e75285123af358eea2571.nq.gz
│   ├── b6305336dc07dfb3b2b70887b03c07cc52714589.nq.gz
│   ├── b63eb684caeeaee32280d2d46e093cff3bdfc665.nq.gz
│   ├── b68fb7b192c60f886aa863f20c1577cd8a40b65a.nq.gz
│   ├── be2b6e8921ec45f1bd8a5f13f853077d2bcdc79f.nq.gz
│   ├── c15e668109726ecfec4d91670f1455b864d09396.nq.gz
│   ├── c2694d1d303b13c5680cdef819a44f9f756e159f.nq.gz
│   ├── c3d1bb850a2fce5d711dd00246deb46622b2292a.nq.gz
│   ├── c55b674c2d3069d99ac893e3480b95cc83d00636.nq.gz
│   ├── cfc27e411418fa848c05c4bfa7c0d066131dce08.nq.gz
│   ├── d3c3ea9ee42b21d5e12d89892f59685114728ec8.nq.gz
│   ├── d585da546d507a65ebe123c67945245f0a3a01cd.nq.gz
│   ├── d5ca2227e9edcd880e9832d8b9e2966c6ce91bfa.nq.gz
│   ├── d7cd714a2e8514aed210af4394ddea319279bed4.nq.gz
│   ├── d97c2187cf85d761a67b6920d6bb01a09270cea3.nq.gz
│   ├── db7069990d0f8a973bd7dd3c77af95dbc2093354.nq.gz
│   ├── dbd7940e07a17778ba388fcc77b40c4003fe01d8.nq.gz
│   ├── de6a8cf1e8ebc10ac3096998d27d090861a0a76e.nq.gz
│   ├── e06b835ab82ccc73063daa30e8264d08d609ea3c.nq.gz
│   ├── e2594c4a457a3186c69e79d6c4d15b3c752aea09.nq.gz
│   ├── e28ae7182fbee999979629a2eda437362adb53c3.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e63d78ae14a9036bd5318e35460cde966dde3827.nq.gz
│   ├── e69c9f89af85acb44c0f435460cd3b7604ed921a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73b3b85dddb6b106f4674d79a55214cb9c255dd.nq.gz
│   ├── ea11fc528909eefb38d05226e7a1c07b2a04769f.nq.gz
│   ├── ed36c5270109ef7b464646a97947a9d538988770.nq.gz
│   ├── ed552a34f78b176e6f4b969c7f6c18b581d1de4e.nq.gz
│   ├── ed63a80d1a04e503643c05c9d192036195f90572.nq.gz
│   ├── f0b600b40bee7222fbf1853feae54de775348dc5.nq.gz
│   ├── f1027b2379da1d229e886bd1c202067eb63c40b8.nq.gz
│   ├── f48fb96b6d9e016a72bb387cf2442bd1e2a22b8e.nq.gz
│   ├── f52cdb0242a3e3b1bef8e8f1dc87ae9b308dd11e.nq.gz
│   ├── f85bf8705162bb98d6d98bde0dc6bb8800ea17be.nq.gz
│   ├── fa2d6e2f2561c446ef1eacadbeadc79419d7f863.nq.gz
│   ├── fb342f968285309c52a6948b751e01f2ab3a8d20.nq.gz
│   └── fd97a509db57edd5f85f157490743015bb98ae7d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bb19ecea2dee440c8e81f9364d60a5829813198b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 142 files
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

[adamchainz/django-mysql](https://github.com/adamchainz/django-mysql)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
