# Repolex Knowledge Graph of near/borsh-rs

RDF knowledge graph data for [near/borsh-rs](https://github.com/near/borsh-rs), parsed by [repolex](https://repolex.ai).

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
lexq download near/borsh-rs
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 28bb5fda9f285185a8c78c712d1e7e6ceba3be73
│   │   │   └── chunk-001.nq.gz
│   │   └── 79097e3c71ae469a101b4828457792bcf8be7f5f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 28bb5fda9f285185a8c78c712d1e7e6ceba3be73.nq.gz
│   │   └── 79097e3c71ae469a101b4828457792bcf8be7f5f.nq.gz
│   └── repolex
│       ├── 28bb5fda9f285185a8c78c712d1e7e6ceba3be73
│       │   └── chunk-001.nq.gz
│       └── 79097e3c71ae469a101b4828457792bcf8be7f5f
│           └── chunk-001.nq.gz
├── blob
│   ├── 01ef40749ad73406934efb7ae5acf181844f75c7.nq.gz
│   ├── 0a0b2e075e9cb08f27a8f483a657a4177f586579.nq.gz
│   ├── 0c62999440ba9ccf299c0be6df9006c0d9ae35be.nq.gz
│   ├── 141609adc8bc6286e1912c9a2519d43ba9415d1e.nq.gz
│   ├── 1855af6b19ee2a7be59fa10a0eea91fdbe57bede.nq.gz
│   ├── 1bce0dfa4410011b69cbe319aa33821fbffcc478.nq.gz
│   ├── 1ecb351ccf67293e322722e8f8bcbba3dcf69080.nq.gz
│   ├── 23c1bb89ad903d732ea01e0dc9841ecb9ed2980e.nq.gz
│   ├── 24e14c1fa975c940a9721e3484818ec95ad5f454.nq.gz
│   ├── 263ddc7741f1ba45dfd5cb83510afe4711a24231.nq.gz
│   ├── 2dbc8a0adc0f3d7350012f6fd1b745dd10770f75.nq.gz
│   ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
│   ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
│   ├── 37f2d34cb4c01777c81730b3d16de707147d7a8e.nq.gz
│   ├── 38fc7e3045c98ee7bf87d991dc3c7bc8b86506bb.nq.gz
│   ├── 3b99c47e33d01af59325601782aed328d765f4ac.nq.gz
│   ├── 3d802ad9a7c13e97418c1006386086d9d1d113eb.nq.gz
│   ├── 417ba7e6cd3d68f4ec481522350936722cb754a0.nq.gz
│   ├── 450bcda23b8d397585ac9d6975bb195c8a11fe6b.nq.gz
│   ├── 4a9963a4628fee8d9d72c667f4ac90494455c72c.nq.gz
│   ├── 4cf3fbd9560467a8984ebf18eb01c684ac3159ca.nq.gz
│   ├── 4f1b2f0dd684392a5fba8d403000aaa79d688bfa.nq.gz
│   ├── 53b14e527ef6c0537c34bd2b62803f1d774c8240.nq.gz
│   ├── 55f368b8678cf665a70a1186c545944a4b7d6819.nq.gz
│   ├── 56eb628ce20222869f3d6939952aa58c86c3c573.nq.gz
│   ├── 5ec6cd41850a3090e63bce512436265586dfa57b.nq.gz
│   ├── 692e959874fdfad91c45dfc6e5cb50564cfbf29e.nq.gz
│   ├── 768b84e13e21c56b4b15294ab3d429eee94a337a.nq.gz
│   ├── 78a2460fd958f3d2f578950903af6d30f99498af.nq.gz
│   ├── 7af550cef4781cfbdfeb0612edb2d569aa68c125.nq.gz
│   ├── 7b465479f9f4d09353609d2e0837eca84a99a1b0.nq.gz
│   ├── 84e0573aa2e83b038a41a83940b8b7688257e35c.nq.gz
│   ├── 8574b1929db58ffbb01598f4e172cc128a403935.nq.gz
│   ├── 862b1632e592719fcc790f810781ce1dd0f1b081.nq.gz
│   ├── 86ae04d5810e064fbbba1231519a13e88e4a5da7.nq.gz
│   ├── 8db27c42e190652ded93bbe9e6f4a939c08a0d3e.nq.gz
│   ├── 923059f8cc898cb9bfafa509677a22335b795abc.nq.gz
│   ├── 933d7c80ba964c413c18a676d953e8b1b118b79a.nq.gz
│   ├── 93f3a11f984de80df0a7265d03acee1f690c004d.nq.gz
│   ├── 9633e6c486b24d1b3c2f05389351e651ebade7da.nq.gz
│   ├── 9e3ce7c20e6251c4e9038d190367dd1b7c9a2272.nq.gz
│   ├── a0b0a4692196dc05382257689d208dae2ca62bf7.nq.gz
│   ├── a2e4f4f786618cddc1fb1a6dda78bb92cf4c73fe.nq.gz
│   ├── a625a984e90c68be5b67df56186733007058085a.nq.gz
│   ├── a776f3154683e6ba4bc0be626e675e86f3a4afcf.nq.gz
│   ├── a86a6dc392cf3a6676e6471b020edf87cfaa516f.nq.gz
│   ├── a955788da5e29678a74dcc3a8220e5af2268d5f8.nq.gz
│   ├── ae7975afb03fce63b0249aa5e5e5e48b539dc344.nq.gz
│   ├── b12bf63453bcd528d7826271012b460bdb781dab.nq.gz
│   ├── b2fc3dc31cd91bd8ae208a93389b48bd217a436d.nq.gz
│   ├── b47943d40932416378396cf9ae2e1e01c41e1575.nq.gz
│   ├── b75c1ee6aecfbd545e2d792d4f630e91d3301783.nq.gz
│   ├── bacaf1e646d8ef421c90f2e6f2386f7677c39dc5.nq.gz
│   ├── bb0bed9fc7e4a06082ae62986b9b9f2dcaff7a0f.nq.gz
│   ├── c42313a10f7eef6a31eb3ad109852fd245fc2ac8.nq.gz
│   ├── c5e6367a8c4f7f32285fb3ca98d4e3099126b237.nq.gz
│   ├── c629dcfc24cff1d0783bfbce4a4bcca8ad96d2e3.nq.gz
│   ├── c926c432816cfd6fb2e8342b21343d9b2ef52278.nq.gz
│   ├── cbe42f4b1897c308281f214a6996b75e11b7a52a.nq.gz
│   ├── ceb01f78398a3f8ac391202b707ee412df60f81d.nq.gz
│   ├── cf51b18a15ab4ef335d8166c922a6030c37cbf67.nq.gz
│   ├── d35274f341824620c94434dd17b4c1828a55f63c.nq.gz
│   ├── d88f98c96eadff449ae518758b8f23e684e845fd.nq.gz
│   ├── deb749850f388486d350005195a2f5f97fa2588b.nq.gz
│   ├── df3dd2748dceefdd0684c410c304b2128331871c.nq.gz
│   ├── df7025e499dee5d080a4df9345a203940711ae7b.nq.gz
│   ├── e01b99c8524d931765a6fff2d9c31567eeea137f.nq.gz
│   ├── ea258563c9468160cb481206c24910e6995af9cc.nq.gz
│   ├── ea2f181a679d47c9531d7050da52a4bdede9a4f5.nq.gz
│   ├── ea3ab955bd32d282f39b9fe8a031ffcef578085a.nq.gz
│   ├── eb9b73fa8b43e9f05c4ad7aa4bed4678e48700f8.nq.gz
│   ├── ed0fcac92bb0e79d84ca138b82b7cc1e3c01b9e9.nq.gz
│   ├── f228ae5b9a702501cd1291d0b408a0b37d27b162.nq.gz
│   ├── f3a5547a125ffb1e8019e963a115e9a41c4623ba.nq.gz
│   ├── f48056e1d7d9fea699237b8aeceebc072e31270f.nq.gz
│   ├── f5a5c4c41d837ebfc9b5d4148611c3f53d272630.nq.gz
│   └── f93bdb327413559c6cfd121607b8dfd1c8c7510f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 28bb5fda9f285185a8c78c712d1e7e6ceba3be73.nq.gz
│   └── 79097e3c71ae469a101b4828457792bcf8be7f5f.nq.gz
├── filetree
│   ├── 28bb5fda9f285185a8c78c712d1e7e6ceba3be73.nq.gz
│   └── 79097e3c71ae469a101b4828457792bcf8be7f5f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 92 files
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

[near/borsh-rs](https://github.com/near/borsh-rs)

---
*Parsed on 2026-05-10 by [repolex](https://repolex.ai)*
