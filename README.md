# Repolex Knowledge Graph of webpack/copy-webpack-plugin

RDF knowledge graph data for [webpack/copy-webpack-plugin](https://github.com/webpack/copy-webpack-plugin), parsed by [repolex](https://repolex.ai).

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
rlex download webpack/copy-webpack-plugin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 18eb9d9fd4d01bfb886ae60ead7df184d75ba265
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 18eb9d9fd4d01bfb886ae60ead7df184d75ba265.nq.gz
│   └── repolex
│       └── 18eb9d9fd4d01bfb886ae60ead7df184d75ba265
│           └── chunk-001.nq.gz
├── blob
│   ├── 01536f5a66c9d5d59232d073cb14e09b7a750d6a.nq.gz
│   ├── 02cbac003051f36a6dab37936140f28bbe700015.nq.gz
│   ├── 039eeeb2ad9f9f4c9df43cc139fbbf4b74ee865c.nq.gz
│   ├── 09713a2b23a0b338aeb6b48be300a4b9a14adc0a.nq.gz
│   ├── 097fc7901bd78052b41e30c471269718bea9e764.nq.gz
│   ├── 0b98a29ef81900823d7781e3f1b46fcac45b0ffa.nq.gz
│   ├── 0d03fd9419ca6e1c2b156ff577f68ac556986cc5.nq.gz
│   ├── 1269488f7fb1f4b56a8c0e5eb48cecbfadfa9219.nq.gz
│   ├── 15dec380749dfd43eeb12975b237e3f0ccea7ac8.nq.gz
│   ├── 18a6684470c114db5ef9df2852eb9f45d59aef4e.nq.gz
│   ├── 21aaefe0ac033b37c8714bd19692c37b24ba9b53.nq.gz
│   ├── 27f3f0dc031aef77960b3e7f0202970d4f53df96.nq.gz
│   ├── 295c8626a8763c0cbf041803ec8b6d17255e1597.nq.gz
│   ├── 3010843382c225130f37f367ecf3e3b76e3de587.nq.gz
│   ├── 334ca7239f6cf91e92c584967d2eb6c16f66d991.nq.gz
│   ├── 3762a52183fadc78bff2688305296db66f0bfdc6.nq.gz
│   ├── 39057291dec441f434be59838c247f8f2ba85720.nq.gz
│   ├── 397e0d294718277d4de26f4746a52657bb85f4ef.nq.gz
│   ├── 39f4a79845cc240f84aa8408f4faf5c681513bdf.nq.gz
│   ├── 3e4e0c1ead5696bb3b68760878078bb24dfc4e50.nq.gz
│   ├── 3e5126c4e761fd09582fc517918a1601b218dff0.nq.gz
│   ├── 408f1bf626b361831f31150176f45cf2d296c48c.nq.gz
│   ├── 458a3a557cade17b412d276dab833bc574dbcb7d.nq.gz
│   ├── 4c330738cc959751fb6760a91a50d9e58cfe5cb9.nq.gz
│   ├── 4de0432b22804cb04435b384ef371beb0cee3c1b.nq.gz
│   ├── 4f41809c68541a4d81d8221cdb9b270d0a50789b.nq.gz
│   ├── 56c8344ea98bede94f24f0788700ea24a0563742.nq.gz
│   ├── 5c77abe784e0ee00b588349e40626dba28d54549.nq.gz
│   ├── 5ebe8e191e8065ac1d35fa83863a617fc2c8e6a1.nq.gz
│   ├── 5f7952820781fd0eb6556e4bfd7a00ffcab1656c.nq.gz
│   ├── 622c2f54db3e1ea1f43c35442199ccf72c07517f.nq.gz
│   ├── 639058d3801761bd0d0578ebb7fb8694275a738c.nq.gz
│   ├── 646c5d2bf399f37ba94c63fef23dedb030bc587a.nq.gz
│   ├── 6b055f35ffdd0c0daf52b890ef941e1c9378a305.nq.gz
│   ├── 6cdfa8ac7e601939fb095c8bb55a8355619866c6.nq.gz
│   ├── 73f3cf9e85b6ef6bea075b9b916b7ff6dc77e73c.nq.gz
│   ├── 7f84562177b6559e644318976c890d91a9994490.nq.gz
│   ├── 86a8e2dfa89e6abcce655fcf9a6f65b285229e15.nq.gz
│   ├── 87c7dc088d6dfef360dadb05ae1862bd1b6f673d.nq.gz
│   ├── 8bd6bf54dd10de45b279428c78acaac80ec7d083.nq.gz
│   ├── 8c11fc7289b75463fe07534fcc8224e333feb7ff.nq.gz
│   ├── 8e1cf3fd947ca4983836195114a9c9634492c4fa.nq.gz
│   ├── 9303096e7517890d8a5743f6a77980284aa480e3.nq.gz
│   ├── 954b38b2f464bfbeb8e8634fbc934e46201d3b77.nq.gz
│   ├── 9b917393631c645a5c581e25757ca805c5c583b7.nq.gz
│   ├── 9ed5e1dea8fcaf000846cea9b73966ea99fe5e05.nq.gz
│   ├── a2373c722dedbf05f6669eba1ea044484213d03d.nq.gz
│   ├── a72566517117347d875ec9909fd19c4d6f74358a.nq.gz
│   ├── aa62c71529b31b5823efdb60104ec61b9368fe1c.nq.gz
│   ├── b8e1f20033100212b556aec230bc09ab3814f845.nq.gz
│   ├── b9ac6581b79f6c6b0a10f968e38abd79d5f85624.nq.gz
│   ├── c1c31e5d0d6f19ab327579fc6fb58fb74bf69532.nq.gz
│   ├── c27d8893a99490cc432461db991faf1b276e005f.nq.gz
│   ├── c82c171defdac551177d75232b41b48738200dad.nq.gz
│   ├── d0398f0d296e5e8242c2d97f10fbec4c2d6a10b5.nq.gz
│   ├── da08ba6c595f24df0f6b55ff86f4cfb480a7a65b.nq.gz
│   ├── dbce4f4cf4b518c5c7c82f69a8b17d18ee6b526e.nq.gz
│   ├── dc0ba0e773dba4a53c4a90db50b3bd958bb11947.nq.gz
│   ├── e01f1ecd994b92f499dcb755d326beed57fe7b1a.nq.gz
│   ├── e0fc213e6401065506088ffd0497786e7a497d7b.nq.gz
│   ├── e3ad9381854abbece27010e5d25e1bd748ac894c.nq.gz
│   ├── e484db3ae353ead40039362b998c0800dba63ff3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── e94452b353478198d61e690dcc36c90daf8c11a0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 18eb9d9fd4d01bfb886ae60ead7df184d75ba265.nq.gz
├── filetree
│   └── 18eb9d9fd4d01bfb886ae60ead7df184d75ba265.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 74 files
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

[webpack/copy-webpack-plugin](https://github.com/webpack/copy-webpack-plugin)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
