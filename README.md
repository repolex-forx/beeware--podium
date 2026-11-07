# Repolex Knowledge Graph of beeware/podium

RDF knowledge graph data for [beeware/podium](https://github.com/beeware/podium), parsed by [repolex](https://repolex.ai).

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
rlex download beeware/podium
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d41d4d9ea4f59a6e274fb2b0977b73b1cc06968b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d41d4d9ea4f59a6e274fb2b0977b73b1cc06968b
│           └── chunk-001.nq.gz
├── blob
│   ├── 04a45720221866ee1bef7065d78853c802a0169f.nq.gz
│   ├── 04b4603c9f90a65a2f18a2533262b8e4592fa334.nq.gz
│   ├── 0a06527951d18a36730ded8eb5ad7f4b41c4519a.nq.gz
│   ├── 0ac7e7e5e27682fb5d1492294bd083af6404eda6.nq.gz
│   ├── 0c12efa9db066c4fbbbfcc9188f3b2719ace7b4e.nq.gz
│   ├── 146b398ab7ab3a984a8bbaef614cf53abceaeb0e.nq.gz
│   ├── 19cd52e2c5bd2778bbfa1d8d2b1de61fee9a74f0.nq.gz
│   ├── 1bca2d42d265cfce2d88097653904caa0b82c81c.nq.gz
│   ├── 20d65a3dc0109ff9845e1b34d729f59f158e5174.nq.gz
│   ├── 216107e99c72db0dd8fe55c77b83101892d3557d.nq.gz
│   ├── 21e682d6bdfbb1ee2f8374028460a5889b68ac6b.nq.gz
│   ├── 22718a3f36fe0cec5a84589cc434518ad0e4799b.nq.gz
│   ├── 23a4d96f768f3076402cdedf766417e9e87252d1.nq.gz
│   ├── 260ae8939294cf7b1d67248711ee1460f7910ece.nq.gz
│   ├── 27ac1fa32d50ad498daa986c373a9bd8b887a23f.nq.gz
│   ├── 29cc96a16d13780d513884ed82f97e43ecd411db.nq.gz
│   ├── 2bb80720c81dd93f6211e872a4c1d1619fafae17.nq.gz
│   ├── 2f0a8767d7bfa50c99dd6d96a5534bd78b45d0e9.nq.gz
│   ├── 2f2e1067ddea64b29891f5dd4b1b6a6c1c1bc1be.nq.gz
│   ├── 30e8d2faf66511a389a0b8f84ad2503c989cb152.nq.gz
│   ├── 30f3f0c0ba447d071035ebac4492e5d586f1735b.nq.gz
│   ├── 35f7843a23ecd016b93e5b99bfcfda8fc7d4273e.nq.gz
│   ├── 3ae006facb317ff6e8f05ca49495b248b82d85aa.nq.gz
│   ├── 3be56fede1b1e58e79e0c89b7fe0000eef4d86c4.nq.gz
│   ├── 3c178d36b49c29b7ed456dd1280e1dbd2c122a62.nq.gz
│   ├── 3c4c6e2cf879e5eb10ffd02893bfc89cd72a6c53.nq.gz
│   ├── 3e9364b251b9d710e35afab14bcc409d4246df4e.nq.gz
│   ├── 42b34f3a4bf2f703fc799da95f1731a57d1a0260.nq.gz
│   ├── 43f8d1f70a796390a1e3d6c42010b4a2d84d3274.nq.gz
│   ├── 44243c0be92aef81c3958f236551a5a892e57b1e.nq.gz
│   ├── 44a7772c7d582790ce580367a74b00454bd6a0f8.nq.gz
│   ├── 4822e506dc397b680968682389d2e0d7ba8c6010.nq.gz
│   ├── 48d70f1ae2c4e4c5b431c337fdefe50d7fdb2314.nq.gz
│   ├── 4a09c81e23ca735b7d235c71f9ed7feca8081af3.nq.gz
│   ├── 5164a0a1d28d2ce47bd42185e6484361522e2b05.nq.gz
│   ├── 57b3aa993d48fdcfae7c85a5b7373aa3bab50599.nq.gz
│   ├── 5937a49d051639b7de6489697100a46fa4be5545.nq.gz
│   ├── 59bd65e5d0af0313973d0cffde3106fdd7676f97.nq.gz
│   ├── 5b98e215b0cda31122f60d9c2a814cf3d9a41c46.nq.gz
│   ├── 5c32a834cbd0183323e2b64f3a5d53073ffdc2d4.nq.gz
│   ├── 5d3076dc36f03d1886ae1aa72e228a14f6b88237.nq.gz
│   ├── 5ddbd91fff15beeb51ef5638b9d4791de7fccdb0.nq.gz
│   ├── 6092317a660aff1c51e6936bb19882540c5a1227.nq.gz
│   ├── 6127796176416643bce065f76c9e88ef2465c478.nq.gz
│   ├── 62b4c3af8f31641e41983ad48367261afb0ec8fb.nq.gz
│   ├── 65107eb9c56d938156e90436b741d50e2e0752ed.nq.gz
│   ├── 65cfdfc7e0ff8957244718df803d16f8822cff7b.nq.gz
│   ├── 6a6d5adefabfc22cbd36e5b3a9b54013b98ef93b.nq.gz
│   ├── 6ae85718cefbbdafe7eb85685e8a554eeafd3376.nq.gz
│   ├── 6b04e15302a94f855b58c1bf625c4613a0e19b49.nq.gz
│   ├── 6c4c99c7234d720005af77df91e5ad5e81fb0cfc.nq.gz
│   ├── 6cc919800888e9d445420dbe88f22761ed690b03.nq.gz
│   ├── 7289e2903c2a6c73f11b138a0a82844626726d88.nq.gz
│   ├── 7755ef9798e18acb1d0287b106bfecd9e48937a2.nq.gz
│   ├── 7e2eaa5c5eee361be766307a8697763ccbbcbcd8.nq.gz
│   ├── 7e453da3010ceb3457f857cbf95bf6198dde7d05.nq.gz
│   ├── 85b9269631ae91558dedfb932f9cdf7702efa180.nq.gz
│   ├── 88d2da3ce8fc8e42e3a460408b89cf51b2f5ec39.nq.gz
│   ├── 8cdb8bf1de07a068cd8ac5efb45312ffea972324.nq.gz
│   ├── 8f4b8e63133389facbb5b5059a6c32b7d379f89a.nq.gz
│   ├── 90595b35929f93272ff88df1b2117c773fed4dd9.nq.gz
│   ├── 98c60afebeadfa82c330a698f0983fc063c164bc.nq.gz
│   ├── 9c4b9f800c1474ac38b054e1a1411dfdcba1a5e9.nq.gz
│   ├── 9d97b945b3cfb057cf01849c8ae69892f8247fa8.nq.gz
│   ├── 9fb69b65d504e5e99858231aea45b0c153e85a34.nq.gz
│   ├── a167a69c819828ce48ed7ebc0dca1d636db19d57.nq.gz
│   ├── a2de22133debcdab5fccd322d67ed3c4e5878445.nq.gz
│   ├── a8d88a9e6d331e317b35a341cd7fef5053698ef5.nq.gz
│   ├── a91b7cee2a620d9e9759af21cdb1824a648d2501.nq.gz
│   ├── aafa977fe5764bbdcf79f8ed6d346c13ff0aa76b.nq.gz
│   ├── ab9461f7a50d5387e686890f72185328a48e1f4c.nq.gz
│   ├── adc3bd57bdd89a37ac08f8c3efbb2806107f1031.nq.gz
│   ├── ae99ed68bca7d21eea969c5994bb6b37a21013f2.nq.gz
│   ├── b1ca550341bd2fb194e1fa60714243b20104cf98.nq.gz
│   ├── b242a41e2526739fed4306f10e6cf02060148f65.nq.gz
│   ├── b4a621e400eb0708bcf306009faa9a4f74d7d5b5.nq.gz
│   ├── b834affdddcf5014398ca9c16aafe3ea7f2d0422.nq.gz
│   ├── b88cf17523dfc8b400264493a95f082d7460eb3f.nq.gz
│   ├── bbfe2c05ce8874cddfe5f59676aa96b5006d3180.nq.gz
│   ├── be7cba683aa63b89209ada8ec95b88326adc98ec.nq.gz
│   ├── c02e441e356358fdd7c216be9b7b3801451004ad.nq.gz
│   ├── c1cef816cd97048171bc8846fadaf711ed00bbf6.nq.gz
│   ├── c1ecd287d16f581935ddc68d7c7da3a5ee1811a9.nq.gz
│   ├── c720c3dd5f72e20c38af441172d048254367405c.nq.gz
│   ├── c815205597dae8a4c86419d2e39fc2e987c91410.nq.gz
│   ├── c8dba3af546d5e4f8e23400779e7e43822c2f88e.nq.gz
│   ├── cb4d037eda6824bbacc19ff030f2d9dd14ef219e.nq.gz
│   ├── cc77532673be56f855e19675a72bc439bc45d3b1.nq.gz
│   ├── cd274895eeadd0e6d8eae878fdf11c90a837141c.nq.gz
│   ├── cd8c8a0404a86fbeefc11c105de2bac23d6b9bcd.nq.gz
│   ├── ce5569fe206b81326073e83dc7b4e7d349b70433.nq.gz
│   ├── d050ad5465ed93f5c3bb9d09029aabbdfe8767ac.nq.gz
│   ├── d38445e56bb10ab7a9757d91ddc0a0ea5c31c300.nq.gz
│   ├── d43533051ac21ee1e719fc7ebdf52086a0a43b7e.nq.gz
│   ├── da8c18d04614caa10ea8afda5d93b8cb7be6c483.nq.gz
│   ├── dd0d1f163dd3327853665dc0802d63a1c53c7f2d.nq.gz
│   ├── dfa473de49bd96bbe0a5fcf8bf52c461442b256e.nq.gz
│   ├── e423ec117f01a0dcf6922da42dadd5c67f5cba05.nq.gz
│   ├── e532e0f0a95dffa96d3d1d331d626037810d7e35.nq.gz
│   ├── e68cc5dae093ed173a52f1d262ebe5128d718a1e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e765196c8b56e5e12d78bc9a30e9cc26990fe390.nq.gz
│   ├── e828b1f1a19365a2dfff348555c2c69fb5274476.nq.gz
│   ├── e889ffaa5c56bd56681e56b9858b3cc2ff67258d.nq.gz
│   ├── e89b2da3f615201cd0610e602c449d0820e2500d.nq.gz
│   ├── ea8889950fbe41caf56ff9c48a135d4df2f42e72.nq.gz
│   ├── ead5509d0cd58c79c8a392365b9869161d088115.nq.gz
│   ├── ec794826255483bed5b1d2c3210bf1e99977a606.nq.gz
│   ├── f183b78cd65f6631f1efeef931a89f9598cbd894.nq.gz
│   ├── f1c7097166262d2ddb62c56226d514bd0170946f.nq.gz
│   ├── f2168031a0547705d59c4babf9abd90e9d2fcfd1.nq.gz
│   ├── f3178246659c97ac826e0d4690f24f8ed528591f.nq.gz
│   ├── f33e5f214607aef4233eaa07747f34b38418750c.nq.gz
│   ├── f499d90d6478bc595774af954ea0ec5f8bf81449.nq.gz
│   ├── f77d388916de620f3b331cede2bcd38c4fa0d442.nq.gz
│   └── fdc2f910930cd70e528daabcefd0d708b608194f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d41d4d9ea4f59a6e274fb2b0977b73b1cc06968b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 124 files
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

[beeware/podium](https://github.com/beeware/podium)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
