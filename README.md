# Repolex Knowledge Graph of executablebooks/sphinx-proof

RDF knowledge graph data for [executablebooks/sphinx-proof](https://github.com/executablebooks/sphinx-proof), parsed by [repolex](https://repolex.ai).

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
rlex download executablebooks/sphinx-proof
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d1113a8299fc9ec4abbf8e032d8097642d96fb65
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d1113a8299fc9ec4abbf8e032d8097642d96fb65
│           └── chunk-001.nq.gz
├── blob
│   ├── 009ac9e51597150c43e7018bdffebe064fc9aa0d.nq.gz
│   ├── 01a5521af349c6cecbccb81740e4ea42eeac48d3.nq.gz
│   ├── 0469b723dbcedb09ef4d4a0a804dadcb56d682ed.nq.gz
│   ├── 0cfc40c5db5fef5f68e6b22a68d4c0345e0a3919.nq.gz
│   ├── 0d1e76b0b845e9d20680e162099f95c39eb6b86b.nq.gz
│   ├── 0e240004c52338f8ebc558f1ff06881cb4afae35.nq.gz
│   ├── 107c9ac231e5f9217244b148fe4d1f727963e11b.nq.gz
│   ├── 1357de195a57ba9b0152fceb6320cefa67b48175.nq.gz
│   ├── 169d3ae526bf256fda68549212469aaa39b05b40.nq.gz
│   ├── 1803d61367b754d77f56cf179023e7f5dbfca0b2.nq.gz
│   ├── 1820cb2e842a1c66b0ab38e972acfdd85b12c096.nq.gz
│   ├── 19ef4b34e19211cc1003b2cf52ce12adc96e7b28.nq.gz
│   ├── 19f308aeda4b57aa3af10151f6b9730e88069065.nq.gz
│   ├── 19ff116bfe9b68452920849161e5b4269c3a3b75.nq.gz
│   ├── 1d89a4f50e28b453e5d68467b48e18103d0ed8ae.nq.gz
│   ├── 1df893421106c789da835aee64e68432f1a634dd.nq.gz
│   ├── 1f0ec5891754427f3b711d328ee92aaa0f563c3e.nq.gz
│   ├── 21bca9972533f9b4a394d9505ae2ae7fe44d642c.nq.gz
│   ├── 2c0764f4deaefa281b0316aeff4b3c9b98693531.nq.gz
│   ├── 2c317004d99e493db8e892e43ac0cdd3cb4ed732.nq.gz
│   ├── 2e755b1c2e5afaf714696c0cb0fdf9e92c2ccf7c.nq.gz
│   ├── 2e9158d78a3aa0bf0df3ea62c392d0a34df784f9.nq.gz
│   ├── 2f2054cbb12312db497b72f79a8fc17f64a7c853.nq.gz
│   ├── 314a12112cb04c1b246dc3799eef70818adc99a5.nq.gz
│   ├── 320f6b22dc8fa1d6bf8073ead47e2710a30acedd.nq.gz
│   ├── 326892d3612fc34607bad45d7bdbf182ccbcc5f7.nq.gz
│   ├── 352552225263ce65f69d328f85fb2e05ad21b6f4.nq.gz
│   ├── 3abe6237dff993d0e3c4933c7173c1926f147e00.nq.gz
│   ├── 3b739e0d193d91d080502b1a9491ec5369374785.nq.gz
│   ├── 3c17b4e154e6035995288a1d6eaab335b7042448.nq.gz
│   ├── 3c82183aa6451cf4e165659c666ff19c6936951f.nq.gz
│   ├── 41c4df18626af335798162f16d2ccc4cf9580f3a.nq.gz
│   ├── 44963ec35c3a24da5d276171cef7bcbc3d19e6b1.nq.gz
│   ├── 475ba515c04b5b7cf67a1517430691febc39a32e.nq.gz
│   ├── 4aea147b77a63cad222682c0df0b0d8676da5c9b.nq.gz
│   ├── 5083cf7a55b5823bcfd6d9a43f87702fff3a6adc.nq.gz
│   ├── 50c04b5f593b8b2b9842e3b9c90396ce53931384.nq.gz
│   ├── 51aa875dc6ea036dbab032c479fd7eb805bf7d65.nq.gz
│   ├── 5a079aa820ec00add2013943b557c7d7b8672618.nq.gz
│   ├── 5b259a34387805318d3547e9c454832ced19c7a6.nq.gz
│   ├── 5b5475a658e26a051e206e949a68b288bec408f8.nq.gz
│   ├── 5c6e61695ba5a6414cf5c1ba780ca82a472dd580.nq.gz
│   ├── 5d48ab18fbc0856e39c54d65d1c3a54af899070f.nq.gz
│   ├── 5e8ab90c6bf62ac27d44a07a106ca39181935186.nq.gz
│   ├── 5f037c0e717aed0e510757d97c2cd8409b79b132.nq.gz
│   ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
│   ├── 639abd216652bf97c06d6526edbf4cd99c27b108.nq.gz
│   ├── 6ca58ef58a15b462ab325eefb85f22290965d925.nq.gz
│   ├── 6cbbf970ffbdab8365bb736b79146349e41b3614.nq.gz
│   ├── 706514099af72a566da2150f712a4a25007739d1.nq.gz
│   ├── 716133a30486204c9e289faab207b356629f3c87.nq.gz
│   ├── 7462ec8d71e28b3c5695cdcfc86aae1ff2fc264f.nq.gz
│   ├── 7558a0f3b4ba8f5a8fb91f7839f1fd3df3422564.nq.gz
│   ├── 75d07293d72a20714bd70801ddf78a3475bc2977.nq.gz
│   ├── 7809c2a9732860cb8d40e0d3a9de56c0576f1813.nq.gz
│   ├── 7a567d5482a715ecd8dec9f4afef31ca9bb483bb.nq.gz
│   ├── 7e1281c340a5aed819e95a1ecc903ef20aa662d3.nq.gz
│   ├── 7edac4d3c5c9009b01f2096ecfc3e426ce69eb54.nq.gz
│   ├── 8005accbb8d9589b3468c80e3d79574ca2298f6a.nq.gz
│   ├── 83eaa92c90ceb92d38b680f9bf243ebf28052f72.nq.gz
│   ├── 8563616cb63fe95a30831cd526d5461156a5df39.nq.gz
│   ├── 86324c5d31f9ad28d6c3fab221e5d1c16c2aa386.nq.gz
│   ├── 89ace3c9b10d944fc4121f517c5495456bedb2ff.nq.gz
│   ├── 8a7c9c1dee36b4e1419ab4775c5fac3e082ad453.nq.gz
│   ├── 923c04840a455d869d8fa7947dbb90559588a5d3.nq.gz
│   ├── 93a3f634459990867797e0d90863a939f97997d6.nq.gz
│   ├── 987ee960846bb5f573fc2dbda4759cb3d109258f.nq.gz
│   ├── 9c04856944ea4b5494282d6ce637c452bf2d6947.nq.gz
│   ├── 9eb3bbaf5f5ee60a3ef4329f12b98bd72be28bc4.nq.gz
│   ├── a2f8fec49fa414902bbe3d88602aecb0ae81db43.nq.gz
│   ├── a3ada2e0dac8a491a6b3c711f45dc07e3ba6b71f.nq.gz
│   ├── b66b0fd1a0d824d3b699736f1194a8e337bb631c.nq.gz
│   ├── b7b97b34be51dbcca0cb3bc8442e92c1ad6e7c6f.nq.gz
│   ├── b9eb2e860c79d3cb3ebc70882bf8e519ab81d14b.nq.gz
│   ├── bbaa55dace20e22a70010af69258b000f204b0ec.nq.gz
│   ├── bbe9ee1c744183a3a3c5264dd1107df081331227.nq.gz
│   ├── beb2069e9ce64667441706106247404e54ec8213.nq.gz
│   ├── c18ad3be0db4295956ebbbfcdf880a9666e4ac7e.nq.gz
│   ├── c3ed84ca4007a1fa3a117ba15d9abcb232412f48.nq.gz
│   ├── c51938cca8aa9ae7d9fcfea272c7a4605519c442.nq.gz
│   ├── c687ef36cf80de8c25897a5573061bc7da6f67e1.nq.gz
│   ├── c751e148f7bf40d54d76e6f339462dc3ae6a0203.nq.gz
│   ├── cbf414c7851fc430128af8410f1a68044bdb386e.nq.gz
│   ├── ce71699dd351c0e942897ad96a892828869bb326.nq.gz
│   ├── d12d737092ee3857ab3e89827ba5e149b3b597ed.nq.gz
│   ├── d2c6942be7dfb7fced25b277ded5b2939303ed33.nq.gz
│   ├── d77b2577a700490e07cc595127c201c40ba9f0cf.nq.gz
│   ├── db9016ac4cf949624c9a369ecf12fc4f6b5b9508.nq.gz
│   ├── dda9865ad01e8f6ecebfc69f0889c81050a594f0.nq.gz
│   ├── ddd18b7b6be1ab4333eaefc0fce03554f551f3e0.nq.gz
│   ├── de9a71e0ecc70b093ba5c69f2e09084f86e6fefd.nq.gz
│   ├── dfe4463dfef17d9224069c72763e836ee89a5c3f.nq.gz
│   ├── e0e4a3f1859a49cfb44e4ade21c226db48354eea.nq.gz
│   ├── e5f2f355c4f1185b8ef9c6eadeef31365d75ef4f.nq.gz
│   ├── e62f5e0937ab2650e06da146f76623cf9943ee30.nq.gz
│   ├── e63f478d6552306ad64c496384739a9d9ff28b2c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6e6f24acf04df403ea3d6ec5d93085667ea15d3.nq.gz
│   ├── ebfc601d8365d8fa9b829f55af8d458e1980567e.nq.gz
│   ├── ebff1074684838c43f8aa2496a316d99214e8c78.nq.gz
│   ├── ed88099027f775942fa65dce2314f1ae9675cb36.nq.gz
│   ├── f6cabd97497da02836c3233c89ad5de522ef40dd.nq.gz
│   ├── f6dd01214886a8d731c88f4cd38c36499487f201.nq.gz
│   ├── f91b49a8090bcda7fedd74835a3164f61f8ff05e.nq.gz
│   ├── faf976735c2abea364b25202ddb20236231e86ff.nq.gz
│   ├── fbb6197888b27eb9f45694cfd75d572877b2bd0b.nq.gz
│   ├── fcda601ecca7177cbfeb396df490b156136f0b26.nq.gz
│   └── fceb3588a4449480298f821d058b915e4120e609.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d1113a8299fc9ec4abbf8e032d8097642d96fb65.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 116 files
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

[executablebooks/sphinx-proof](https://github.com/executablebooks/sphinx-proof)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
