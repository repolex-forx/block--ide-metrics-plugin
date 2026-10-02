# Repolex Knowledge Graph of block/ide-metrics-plugin

RDF knowledge graph data for [block/ide-metrics-plugin](https://github.com/block/ide-metrics-plugin), parsed by [repolex](https://repolex.ai).

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
rlex download block/ide-metrics-plugin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d05bc24b7f0e06513236e598e4e8fea669887531
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d05bc24b7f0e06513236e598e4e8fea669887531.nq.gz
│   └── repolex
│       └── d05bc24b7f0e06513236e598e4e8fea669887531
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a760e54d26b347f7b2cee03bcf199d699ef764.nq.gz
│   ├── 0382f7c8a0e3d82629a297751ad4e2ae55b968ef.nq.gz
│   ├── 086a62808c31b5a6539ad31b56b2827d2cc9488c.nq.gz
│   ├── 0932d4d9ede3c64714e34036088e664b31806fb8.nq.gz
│   ├── 0a4efcd988959b37e6cfb0e0e4814fb2f17540a6.nq.gz
│   ├── 0d21941ee7adc973b83a128704f4cb6b718d1c3d.nq.gz
│   ├── 0e9bc050a90ca757fc18feafda811b19bf016168.nq.gz
│   ├── 10a301d6fdf0c54e337901a871c55c0531f2ea2c.nq.gz
│   ├── 144f7e88632124a95da082e86c725fdd1d2da75d.nq.gz
│   ├── 15f15846659f5fee111cf6c20472c2ea6f03d92f.nq.gz
│   ├── 185b37b5756d1d68f1fa970103306b3714da1f55.nq.gz
│   ├── 1b527ee0b1423c66340b243d38cd8505f8187627.nq.gz
│   ├── 22da1933733e12e6090921adf4a9f2c9fc65ae87.nq.gz
│   ├── 23c016e3c7103bbff8f5a8fd2a7d58055911f377.nq.gz
│   ├── 2a84e188b85a31f9b4c2aa930ce9288fb6dc6936.nq.gz
│   ├── 32783f572bb080a2251421a0c35e7e4ce91ac0a7.nq.gz
│   ├── 33c9c354529fc881c65af02fbb92aba9f8a009c1.nq.gz
│   ├── 3cb7bc3f96a6f3dd5aa0b1cdf5152ddd978af309.nq.gz
│   ├── 403fcfdda6ada5695c4892c223d4eb1c58d41589.nq.gz
│   ├── 4119e9bfb9055741abf20827e76822b12ce78290.nq.gz
│   ├── 41fc763a89faec031353fee533ef44efe5ced4c5.nq.gz
│   ├── 427a3895e686d26697bf972fbb62c271f1ceb2df.nq.gz
│   ├── 447cf9d305471915c162c52f8f0fb30b7f1ac070.nq.gz
│   ├── 49022f7943817a9c8025785a846eda60f518d593.nq.gz
│   ├── 5353b311d306107a000031f0bd8836e3377a4012.nq.gz
│   ├── 5622ece21a0136fea5e01a7afdd4ecb2b85d9d23.nq.gz
│   ├── 5bbbb3fe73d61590eb5f480631b3b70b8e8b27ed.nq.gz
│   ├── 5eed7ee8452842305a18a4eb967442683808226a.nq.gz
│   ├── 5fab61ceb76ce52ae91a5f113b4f0a4ba0b7eb39.nq.gz
│   ├── 61e1f1ac617691a41ba458dbb919a8430501fa99.nq.gz
│   ├── 62c92dbfd4eee7708b2b8c561a58f30bc509fffd.nq.gz
│   ├── 672190d2912b9d59fee0e2eb2cab0fe19d212d91.nq.gz
│   ├── 6b70c0914716db35878aedbf0df8e83f97315b71.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6c08ad9b6e0cdc346c1c03660fee492a9762d12f.nq.gz
│   ├── 6e43859c847aed61e3b89ca832b92ca0b8d166aa.nq.gz
│   ├── 71a876a05af795097548c518dcfcc708e59f325d.nq.gz
│   ├── 71fa905ec4b58858774a848f1055826582fca620.nq.gz
│   ├── 7410f4f689066a8b9ce8b3638ec4760f21878d86.nq.gz
│   ├── 74a9de908e7f0cfc8eb5c9d39cfb35449bf7ff64.nq.gz
│   ├── 761d1770c6063873bbf01b65a306194aa9be418e.nq.gz
│   ├── 7c54a309ffb14b1a66ceddf0d23d39481f7615df.nq.gz
│   ├── 7d6640f80887c2576d84190a5735ef294002e4ec.nq.gz
│   ├── 80dd7498a4f1bf97d3d19457e2b19735176530e8.nq.gz
│   ├── 84e4b75899cfc76852088365bff9925866e92357.nq.gz
│   ├── 8bdaf60c75ab801e22807dde59e12a8735a34077.nq.gz
│   ├── 8cfedb9e4295e689c7f70a08434d7c3ae13774e6.nq.gz
│   ├── 8ec77b4d979bf9a53cc59ec307c03364e964e48a.nq.gz
│   ├── 8f55e203c19e1c50c941eca5ac14f65add74b4d3.nq.gz
│   ├── 9008d0b7d1f898c79d92ebe721934efe369f5615.nq.gz
│   ├── 90ee70de0ee94f9bcd239ab08f695faddc6c6a83.nq.gz
│   ├── 9bd98905e694b14e9fce5d16a521d83c4556e187.nq.gz
│   ├── 9c402ee4b0cd4e08858bfbb124249398b887b79f.nq.gz
│   ├── a08cfcda8d81520c23197078b64a1d3a099debfd.nq.gz
│   ├── a2ef7eb635c1a4d898a75743d6d29d86e89d68ce.nq.gz
│   ├── a360757d633fdb040a1c99d5b5a75a252d41e347.nq.gz
│   ├── a5024279acb344e7dfbe6efc535520b3dbf09497.nq.gz
│   ├── aa854b5c3c27b6d8939aa10a3ddf18392b1c3842.nq.gz
│   ├── adeda9f42c4b2d6f670738c0b38fca078c961e0b.nq.gz
│   ├── b3308111d29c3666586777fdaafcfcae30f00ded.nq.gz
│   ├── b3ed831dc582b83f616baa59d9a167979a16370f.nq.gz
│   ├── b6a5c651ceb99d1cc7d47f0335829008d40c8fed.nq.gz
│   ├── be7b25d53a98098eb75f83e388d16046581dbc9c.nq.gz
│   ├── c065c145fdfeee77840c9f81caa7f37aa21fb5c3.nq.gz
│   ├── c074c2d19d4b61b40337e8b240b5af3b5f6fb7f8.nq.gz
│   ├── c11069595ca187946eecc4b17de69c7d335b0fd2.nq.gz
│   ├── c4161289a89da65a757c855dab60f0669cc34b1f.nq.gz
│   ├── c58d9eed9807af6fa3680a39ef78e3230409e7ec.nq.gz
│   ├── cbb3b1d72dd809097ff6ed7fda4596f07d2f17a5.nq.gz
│   ├── ce9dadbf1d38d64e929628c5ce521621392ff9e9.nq.gz
│   ├── e4638c7b6c4c9f363fd23c1c613207e32a516809.nq.gz
│   ├── e559ef8fa16d644d954d879d88e43b1d32fc2a16.nq.gz
│   ├── e5ab97601506207b9cf14704625545de6cde821d.nq.gz
│   ├── e7064254f8bbe86eec8d8f7ba6e8ebd8848a3443.nq.gz
│   ├── e9b6c2ecfab1fdca849bb57ce02bc82633028a10.nq.gz
│   ├── ecb84ce5058441243ec006c5fe1a6af6d6a835ce.nq.gz
│   ├── ef07e0162b183eb9d19a2c9ba7035c283af9f8dd.nq.gz
│   ├── f281bdc83e4c6e9d6b1d0c5857fb1c9cfcfc1745.nq.gz
│   ├── f327332ecee26ed48ae437585826a394d9aecbc0.nq.gz
│   ├── f4daada8834af0db661e3b99bc5863fed0c777b1.nq.gz
│   ├── f61c58024bac5d61a84839da9b2fb99afd6ea3cf.nq.gz
│   ├── f6ec427e63dbb0a9d34b03aeb78f40ec1d87e4b0.nq.gz
│   ├── f8fb537e32cf8707d814d3f531b20d6c894ffd46.nq.gz
│   └── fabecf8373559018723c0a050fa50b6679a4abf1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d05bc24b7f0e06513236e598e4e8fea669887531.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 92 files
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

[block/ide-metrics-plugin](https://github.com/block/ide-metrics-plugin)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
