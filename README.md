# Repolex Knowledge Graph of sqlalchemy/dogpile.cache

RDF knowledge graph data for [sqlalchemy/dogpile.cache](https://github.com/sqlalchemy/dogpile.cache), parsed by [repolex](https://repolex.ai).

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
rlex download sqlalchemy/dogpile.cache
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 185db4fb6cd844cddac17cc3dcbbd51a876891da
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 185db4fb6cd844cddac17cc3dcbbd51a876891da
│           └── chunk-001.nq.gz
├── blob
│   ├── 05de1130666775f5111d041cdb47ab20e4c57c79.nq.gz
│   ├── 06047aef1dbae769217c3f6a544bf96432098a63.nq.gz
│   ├── 0a18302466b89b0deba569d5e0dcdbf28cde297f.nq.gz
│   ├── 0ace10bd210bf7006b9a882d0abb0dcfd3f77a9f.nq.gz
│   ├── 0ba7c06a346062a168616077e5bac6fece12a40e.nq.gz
│   ├── 0d569a6e291fc131cd6239eb1e354c8601361ef6.nq.gz
│   ├── 0e8c491ba006349ddf1d422f64969ced70a3d0e2.nq.gz
│   ├── 0e9b4f6b1d40c36e76aafbce4534a307b0d59481.nq.gz
│   ├── 16ea325ae5c4899ae54e691964c2a11e9929f4f0.nq.gz
│   ├── 1ee0a7773e779496dda72f24f762bd97618d3095.nq.gz
│   ├── 24fa2354464d85180c404c2d09e42987a653bd29.nq.gz
│   ├── 295627a49c638dbc753c4c155f2a6a3f5b1b155d.nq.gz
│   ├── 2a649628c6fc4f38439b0680b6b48c4c5cff95ad.nq.gz
│   ├── 338010ece1cf1d453af9301ff301014131ea33f1.nq.gz
│   ├── 3392a10068fafbb26bf3eac949b4e0b7c6581cec.nq.gz
│   ├── 3a9988968f6231529843f23c73e03d31eba58920.nq.gz
│   ├── 3f3751034968aa79a1167e736500b1423cb8aaf4.nq.gz
│   ├── 407194171e4a45332d5cf6bb2842d959d735fcbe.nq.gz
│   ├── 40ab275e1d7c32a1d7bb257a015c9c2c9ba30189.nq.gz
│   ├── 414cd81e11453949a4edbe67b7c53d3460eb8ee5.nq.gz
│   ├── 465cd90db693d93d67f488bad1e3fc36a12e0e50.nq.gz
│   ├── 4acea460ebb5e43f9115260df830347f9da9c613.nq.gz
│   ├── 4aec9fab0217883508e6069edce70d61b4b8caeb.nq.gz
│   ├── 4dff69fd5ba90e5080bcc51d373823ea032976eb.nq.gz
│   ├── 4fc63d162e1f2189214cfccccac02be6dbfbdc4f.nq.gz
│   ├── 4fd9dda9efd0bf805a24d163c9288df2cd96c4eb.nq.gz
│   ├── 53c9d5747c3878848617a29a5bc3adcd0ff6f1a4.nq.gz
│   ├── 57798ad1fadcfe9f5c8f279143ddf4f931044808.nq.gz
│   ├── 5c42bd1c64f8606a25c18198baff73432986182e.nq.gz
│   ├── 5cc6b38e6d6893bd0b97f6408168fc24e1b12b63.nq.gz
│   ├── 5ced01a8efde6a5aacca65750ec8c8369712598c.nq.gz
│   ├── 5e56a92164b55135982a6f8fc51cdb7466852334.nq.gz
│   ├── 5edba513fdbba57670d6931766e6a2b97c539456.nq.gz
│   ├── 6f8120ef29b08712dfeea84320d6f067497d5b51.nq.gz
│   ├── 76ac3a1ad83df7ca5349a15c681c9fa6ef74d508.nq.gz
│   ├── 7ca54d66b45a12dcfa372fecaad929627065c123.nq.gz
│   ├── 83ad911f742839894bd5693db15d2a050048eba7.nq.gz
│   ├── 8503b82a7b18f7ea3dc465b239bf2b0da79d8a9a.nq.gz
│   ├── 85e4e85f4fef15707e7b4924fc3f96ee93f45f36.nq.gz
│   ├── 87f67fbd8501629c0ef9d3036cdc74877407adb6.nq.gz
│   ├── 87ff50828645dce8e65ecd8b8cc603e282619b3a.nq.gz
│   ├── 896a2acbcc8bdea71d083c75c185b64118492965.nq.gz
│   ├── 9277a6ff1291916045869f01ce59120ec8e167a4.nq.gz
│   ├── 935c42b8f2a583872760fc916903439fb648800a.nq.gz
│   ├── 96b4016ddf19df92f023bf4e707c94f327bb41dc.nq.gz
│   ├── 9d1ac4d1945e1cc9f21de455f993b2002992ba0c.nq.gz
│   ├── a09214bbb9b2104315e86ab782092a95e1550e92.nq.gz
│   ├── a3b2e3e6e3d8f1d59439722489f503fb5433160a.nq.gz
│   ├── a4530b8928e4e9897474f4ba742986b320c3f9f2.nq.gz
│   ├── aa85a143463bd7446ae4b5fcb7614bc283b9ba9b.nq.gz
│   ├── ac1e87e8ba83d17530a7db3993ac12169f4fd453.nq.gz
│   ├── ac411aac00b09b3142f89d69e27386934819aefb.nq.gz
│   ├── adeb1b4a3d348a5cc5fbfd577c3b0a16e6dcf8ef.nq.gz
│   ├── afec67cd8a7e8d4015039fefc80653c408d685ba.nq.gz
│   ├── b024da80e9c1c8c800cc1b46e90c1e783cb446cc.nq.gz
│   ├── b1dd0f976e490e86bf00033c9e113a9afc6c5002.nq.gz
│   ├── b4ad0fb35c787f55bc88f06512246585f382f53e.nq.gz
│   ├── b5317052c687230900a6da89dec12af91f4c5d7c.nq.gz
│   ├── bb30e7aafc1a059956e96c269d1dbe2d9c1d5d6a.nq.gz
│   ├── bbe029fc645b86516a06453102c632bb89fd2e16.nq.gz
│   ├── bd1695d8a8e0f52f79739e7c1c6745f2286aea98.nq.gz
│   ├── bed284d6ab39bd670bd3da0f80da86d8ca0224a4.nq.gz
│   ├── c05718115a5a66b1a34557018082992362175f77.nq.gz
│   ├── c334174ed08f3c23545cd8987f6c3c16df0bd936.nq.gz
│   ├── c6ecc8cb9e0bb8001cdc6a6bf268b3ad90b11c9a.nq.gz
│   ├── c7536974bf3d25681e24945114b14ee3a00af67e.nq.gz
│   ├── c79b6b751f5409e1515c299bce81e4805d01f93a.nq.gz
│   ├── c9c9ba88735164d76edfa207380961268af47bab.nq.gz
│   ├── ca5dd76b795344a9ed7c91b8704f83c639814797.nq.gz
│   ├── ca96833fab4ee47ea2b4fad569774f90be987915.nq.gz
│   ├── cc0093fc3f22e8bf0975df38f0927953e91d7025.nq.gz
│   ├── ccf6517395f5008271e91ed7076e55224cb25b8c.nq.gz
│   ├── ce1476126cc3ee7cf4a7321e4c8b617ab32631af.nq.gz
│   ├── d376cce8e650cf8ae3532dc1d8298eabde667d07.nq.gz
│   ├── d463c375154556966c3f5db7b54444347489bc73.nq.gz
│   ├── dc5f408ca1b5658a2110d68b3caa527d35d4d5ef.nq.gz
│   ├── e10ba4d14d6e065d097680e7d863dde671228043.nq.gz
│   ├── e2b5c41aa39af35a79edb19c16fdd4e562f60972.nq.gz
│   ├── e361d67764670fa8535b50ca3bc7eac9792b3e1c.nq.gz
│   ├── e48b05767d6df1ac08ccca7cc64626617fef7562.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6f096beb32a0c891bf26642bcd163041466a0f0.nq.gz
│   ├── e76f1df3642dcd01ecb0896f94c586305b8e548e.nq.gz
│   ├── e8bac01a8dfe941c7b33c85cd6d980a310aa0de2.nq.gz
│   ├── eab01fc42a0629163ed36f87dbd5230af0d94909.nq.gz
│   ├── eb77c603f0cfdc85090e83ffc60e3ddef80a87b7.nq.gz
│   ├── ef6debdba7163853083e801763b05f315bf09135.nq.gz
│   └── f49b3691871a5c683a48fdab5cb0a55bb63da2a8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 185db4fb6cd844cddac17cc3dcbbd51a876891da.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 96 files
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

[sqlalchemy/dogpile.cache](https://github.com/sqlalchemy/dogpile.cache)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
