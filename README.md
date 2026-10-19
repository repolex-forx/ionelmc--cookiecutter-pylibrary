# Repolex Knowledge Graph of ionelmc/cookiecutter-pylibrary

RDF knowledge graph data for [ionelmc/cookiecutter-pylibrary](https://github.com/ionelmc/cookiecutter-pylibrary), parsed by [repolex](https://repolex.ai).

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
rlex download ionelmc/cookiecutter-pylibrary
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 24da906dfb9f250b31ed2ee595d6f05d07b357db
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 24da906dfb9f250b31ed2ee595d6f05d07b357db
│           └── chunk-001.nq.gz
├── blob
│   ├── 05fd44bc74e5f383784bceddf4c04649b89a38db.nq.gz
│   ├── 08936d99094e1b728f76a1a13bc81ce1cdbe0cb7.nq.gz
│   ├── 096b2b66533ddd287dd5650e59313f27f2b0a3b9.nq.gz
│   ├── 0ffc1b53f5851f6deddff48bec8cb5e1909eb5b4.nq.gz
│   ├── 14f1fd2b12048de976ee549ca20170be34b65799.nq.gz
│   ├── 1b25de12c331361f31f671a3e172760ae2245624.nq.gz
│   ├── 21334ea5d1b86500f6f6196018942b62ab4e23dc.nq.gz
│   ├── 258e7a92e4ba37288efdd43eae56fdd111aee9f9.nq.gz
│   ├── 3277ff6c864a1a6f03ac8348615cb10cdc428639.nq.gz
│   ├── 32d21197efa1467ebfa4a6cefb29a915113714c2.nq.gz
│   ├── 37f99888b6f1174f4e8c3ab4e7f479d409ea7841.nq.gz
│   ├── 3b337823837608eaae1eca6e8314cd4ae1e27c80.nq.gz
│   ├── 3cbfb4d9df861edd725362e1385d3906f0b345cd.nq.gz
│   ├── 3e9b37c2197cec7426979fefbe3e6adadf61ab83.nq.gz
│   ├── 3fb33cb8510a6c7209e212a16d918e000e43cda7.nq.gz
│   ├── 444499c83dcb368cbf52cd50fa23b4ecd8386e52.nq.gz
│   ├── 4763cc63e4757af39608e6a58042fb28673778d8.nq.gz
│   ├── 53cff19c438725af96fc85a24caac85436d5a346.nq.gz
│   ├── 5514016393971466293aee44a3ad653ca2f2efbc.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 5c6d0dceeed527c1e42da189d30cc413926accbe.nq.gz
│   ├── 6983a7282a363940ae5b074a5874a0b223065e73.nq.gz
│   ├── 728c62949bfcc578b4978fce2b474dc4edd785cd.nq.gz
│   ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
│   ├── 7c8cd07407127cd9008d77b34dcd845c75235c39.nq.gz
│   ├── 8c161e4eb0da4c08655af0ddff3d89cedfdfb4e2.nq.gz
│   ├── 95739be1817e89f83fb43522711dd12ca5d3414e.nq.gz
│   ├── a113a4c8402d5d67fb90f6522d738a0199450b72.nq.gz
│   ├── a2d480bb79405d1371da3c20e8fe0f3999995624.nq.gz
│   ├── a6c56447eca5512e3aa5d95c9191f9b0d768f48d.nq.gz
│   ├── ad842d51d97d389707466a2f855e895fa0b9f6d6.nq.gz
│   ├── ae1fa8d23bd6c0e3a84497ab36d0cf0d01214561.nq.gz
│   ├── ae464b9037f48007b3303b55dd7790a4cd3dea98.nq.gz
│   ├── ae8344155cdb49be70fcbd8cb71a98c183e3a136.nq.gz
│   ├── bc13b80cb7b9ba7e698fa8a66d39e58a7349e81d.nq.gz
│   ├── c1a280731498687c7c31c989352de02af0ada697.nq.gz
│   ├── c1f798cd614afc153d0ea0ecc65040eae5ce93f3.nq.gz
│   ├── c643e5ef9fdda46e437a46a5a13538c526472f9b.nq.gz
│   ├── ca4324508800c63a1798bfda9893233852f2150e.nq.gz
│   ├── cd1831404a1ad5a3cc1820ad68ad7cdf91a91e40.nq.gz
│   ├── cfeca4f93871af922b9338e6bc93e542411875b2.nq.gz
│   ├── d3c939336f968a179a3c027d282de64a134830ca.nq.gz
│   ├── dce5f91b48555f29dfb7d935646ef1282559916a.nq.gz
│   ├── dcfb0356dcb087f380c5554421ff8c996448fded.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb610e0aea641f77e4e93c498ba2ca5947f2b38d.nq.gz
│   ├── ed2ef5589d26cae90d0875b15d7f41628c91279e.nq.gz
│   ├── f0427cc98dbecb6144864b9706ed42d8e0589139.nq.gz
│   ├── f11c7011f63592baa95c6841b197fb16a457ba83.nq.gz
│   ├── f2750d61870820726cff8e2622ace4ef18636cef.nq.gz
│   ├── f95eb78d8a603b0fe5d17560d0dd04877d55c71c.nq.gz
│   └── fccd768d955005aa3283ae0b05460b47b94d795e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 24da906dfb9f250b31ed2ee595d6f05d07b357db.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 62 files
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

[ionelmc/cookiecutter-pylibrary](https://github.com/ionelmc/cookiecutter-pylibrary)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
