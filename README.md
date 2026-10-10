# Repolex Knowledge Graph of jazzband/django-downloadview

RDF knowledge graph data for [jazzband/django-downloadview](https://github.com/jazzband/django-downloadview), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-downloadview
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ff0aeb909fc05d5419cf54b65ff9d01cb6b4189a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ff0aeb909fc05d5419cf54b65ff9d01cb6b4189a
│           └── chunk-001.nq.gz
├── blob
│   ├── 01364f1cd75577724cd8ad7a384c670556cc130d.nq.gz
│   ├── 04ad473407ecd32c479a709142e4105ec99ff8ab.nq.gz
│   ├── 0e5811b5881e6fdd747436477d3c9fb15c17f460.nq.gz
│   ├── 11e2cf154d2d2d2876a5a6afc9d99758b595af38.nq.gz
│   ├── 11fda2b0f393c29d17d8cde58fbc8f3a0457e5b5.nq.gz
│   ├── 1218bc829b005406427c3de0b77d077e3c9eeb7a.nq.gz
│   ├── 1422bdb18df92636c5442693d677b5791552f33f.nq.gz
│   ├── 171a88c1c3d475eca3fd42f03fbfff715f189e70.nq.gz
│   ├── 188d4e5397dfe83a8fead995b603ae32746502c5.nq.gz
│   ├── 18d27602cc941433d52261f7483f02944c389d31.nq.gz
│   ├── 1f346f47b755f497124ab97db8ed4153409d2cf3.nq.gz
│   ├── 1f5542ae7ddaf31f7553a9487055022b609ba673.nq.gz
│   ├── 20cca9a0bb30a8054a0aceda73c53b04e0def821.nq.gz
│   ├── 20df49f5ad7da4bc3b29b9b064e5e85005a58c78.nq.gz
│   ├── 22a3c55cbb6f0c2ac818f599bb6348648072c0a5.nq.gz
│   ├── 28e866cc0e5e8b0f3ef33aedd96c0efc358f7ee6.nq.gz
│   ├── 29b58e73b439aa30653130d9c42e8365751ba830.nq.gz
│   ├── 2b2d4ece12025bca15c47c20382836c10c2e9a82.nq.gz
│   ├── 2ce14642d78169ddc63c265d73ed185494287b0c.nq.gz
│   ├── 2dcc77c2adadae7d233a2724b39e7931343218ba.nq.gz
│   ├── 2f11e5ad31dfdffe5b2fa902de6301a21cfa59f5.nq.gz
│   ├── 30de8d6a9c78f23152597ac8d7edaa5d36332023.nq.gz
│   ├── 34a3aa41c7b6e3250d3e1dad28579ccc557802d7.nq.gz
│   ├── 34a92bcd6b7f6b30fb731cb4f93e8da2f234b359.nq.gz
│   ├── 35f7cd95cb82ecf3c8f96e2ae5239b99d2ebc5cb.nq.gz
│   ├── 363b0efbbfa32f6e6c916de416a8d49d4b7a1069.nq.gz
│   ├── 376e8e4e1e9ee6bcaae5a1d1ea953a243cc6c1cd.nq.gz
│   ├── 3a56643f81a2e285c4d5a30369aa3639140efbb3.nq.gz
│   ├── 3b9a946f7c304268187463c5376b480fd8f94554.nq.gz
│   ├── 3c5abb275187766145b2a7d1ac6fc78fe37ce7e7.nq.gz
│   ├── 3ee67992f93ba6e88edba94bee5dba58bb7334fe.nq.gz
│   ├── 3efd62899fa7311323a9146aee93ca82730643ef.nq.gz
│   ├── 406cfe99a912cae77764324121c57b8cb5ee0b22.nq.gz
│   ├── 43bd9f9607d1b4db09b2a55763d69b6e93a7a02d.nq.gz
│   ├── 442800cb5c7af85a634a0c3ff49282a6fb665bff.nq.gz
│   ├── 446dec65bccbed5727799baa06512dda32d78069.nq.gz
│   ├── 48e3fd1ae4b1368715fb8cfd013239f45f3f2163.nq.gz
│   ├── 4aed6ed431a0618b570cc537df67de13ec6a75da.nq.gz
│   ├── 4e5fe90c0518f5392352f2bad3bf4ec5b044fde7.nq.gz
│   ├── 4ed20557cd5c3efd4037cd5869b698db97d69e72.nq.gz
│   ├── 50781890eabc6df2a5eb05e21e15ee40b9ee80c6.nq.gz
│   ├── 51f35b36e7f80a14a6adf5858bad749722a4409b.nq.gz
│   ├── 573ea4a30f0a161da794f1bd1e64c1010c5310ac.nq.gz
│   ├── 5820b1dc37076ec94c7bb039532d35f964b5329d.nq.gz
│   ├── 587a8d9eabfbb5b8b3d494378fe693b0c5300552.nq.gz
│   ├── 5a39a42e51b0821017187ab9825485c64edd2bf8.nq.gz
│   ├── 5c1f07a097cf66098b0641696ba5b51a5773b062.nq.gz
│   ├── 63e1129635efa997ed363c774ff22818e570190a.nq.gz
│   ├── 64d56f50cb4e5fd1785acfe94d30e9bc18d3a9ca.nq.gz
│   ├── 6720443017cae67804a1d15e2f7fac3620132466.nq.gz
│   ├── 6b47e9ca0e2c8305eb42ef76f9475df9b0d24201.nq.gz
│   ├── 6d080c95ffa59ab70ab0b2ceb4ab6ee016aa171d.nq.gz
│   ├── 7139b5ca0ab5b733c57421aca9f285ae26a113f3.nq.gz
│   ├── 71955cc9c9784ba04809e760c8c30b32379de9b1.nq.gz
│   ├── 7590109810111798d4a16e35d756684522d43d1f.nq.gz
│   ├── 76f55443ec66503b9fc1e6fa544e386941fe718f.nq.gz
│   ├── 77dac3a00f33c33b900093544af952eeb0f58986.nq.gz
│   ├── 78afc728a7605594c4f1e820c3d8abdce6812a35.nq.gz
│   ├── 793a54664ad56bbdd10c2af6f1f43f1f9c6c8f7d.nq.gz
│   ├── 7a98199ac1e354a88519f34b0b2ab86806380d35.nq.gz
│   ├── 7b354c14f12429c9dab94c7294fb41eb14be960a.nq.gz
│   ├── 7b7b39cbfee8c9367b6fc37f413011d1d23ebfa5.nq.gz
│   ├── 7c32f4ecaca9458424bb6b2d6e7f2ea3b5a0e9c7.nq.gz
│   ├── 7c785bf7dc55eb14832d12a4ee6a16ad35a3564f.nq.gz
│   ├── 7d00ed097cc996fc223dbcc584f783130a00c220.nq.gz
│   ├── 7d776df4aa2f59eb8782f03b2eaf5568eb7e2ca8.nq.gz
│   ├── 7eb7b97c91ce0bb3ac89445cd1c70250de79a466.nq.gz
│   ├── 7fa96ef8df5decf617a912ded99f4f46aad37c7e.nq.gz
│   ├── 7fcb1ae4e44943d66ced6dcd50b3a0a238046c5f.nq.gz
│   ├── 822511e34523577eda64c873fcef4ab24b346a9d.nq.gz
│   ├── 83068629f02ee6627ccda0d6c54d7bf5046a6c16.nq.gz
│   ├── 8485df03daa284c870d23a0a65b792e3c7d0d477.nq.gz
│   ├── 8590ca5faa41a0230eaf470fbd8468e57c3db01f.nq.gz
│   ├── 875c9f32a1d9571aad82ec19e9778fa4824299c9.nq.gz
│   ├── 8b6d329eb66dc636e6e3213cdbc86cb83ca75859.nq.gz
│   ├── 8c69017c393d88754785f5e5a6667c9232c2933a.nq.gz
│   ├── 91742f25a6c2b2ee5c1c1c5421f823212f207c5e.nq.gz
│   ├── 97ab9ffe6840dd25140ea1f86a763d3d059289c2.nq.gz
│   ├── 98857f691d6420abe71daf7ec19906123b4c9999.nq.gz
│   ├── 9c90b249d0d680075df79369e16ff2882979deaf.nq.gz
│   ├── 9cb2a4ddd0152d215eb05efb7165ddf5681081ce.nq.gz
│   ├── 9fdd6d7641eaa22971f6a33d1103d89911611f54.nq.gz
│   ├── a0977ec104c94a6a8fe0a546a133601ba4260db8.nq.gz
│   ├── a7cdb39d3699f06e3cdc5816ee761319a35bb8df.nq.gz
│   ├── ab9b2e00b4263be772602a137e2f143d83a4c284.nq.gz
│   ├── ac46b9799fc2ec5fa023247d3fe6581bd256a962.nq.gz
│   ├── acd1eabf31be5f096855d1eff1456cdcc28025ac.nq.gz
│   ├── aef8d9ec707360b99dc9f337f585764e05c6bba2.nq.gz
│   ├── afceca30e0415dfc213a93f2e0b178b781420a0a.nq.gz
│   ├── b0c923462e6e55c9bfd4223d9057c540d92fc2b3.nq.gz
│   ├── b1d0f4a34c3c37953316d1d1d8a39fab331b142b.nq.gz
│   ├── b2aa87220ab6f2df4639d15cc8c6eef7a940da6f.nq.gz
│   ├── b565e95e0a21ff78304ea6c50bf9054be76af99a.nq.gz
│   ├── b71a4ddb49e4fce32a5676af4c609777d0da9006.nq.gz
│   ├── bb14d6b111019230a4a8275dd6bdf31e1dbedfd0.nq.gz
│   ├── bced5558975332a0d4ba96b470600a3bf82ff891.nq.gz
│   ├── becee9ae745b636c5f9baf850154592021f09927.nq.gz
│   ├── c5d84447afef7359e1ba7096454629fbc6e96c65.nq.gz
│   ├── cb2fac485557108647cbefa362c4301442f332a3.nq.gz
│   ├── cbbf48c88ebcaeb666441c558ef65c142c533dd4.nq.gz
│   ├── cbebf158c1bbbe749b2f743984deac482fd1075d.nq.gz
│   ├── cd0875583aabe89ee197ea133980a9085d08e497.nq.gz
│   ├── ce93f69a779269611075849eae1bbdcb33203fdc.nq.gz
│   ├── cedc3c714afddd716996e205009c0e2b54bb7e2e.nq.gz
│   ├── d09cc898fbe369d5e6741b6134f28a5a7ca95194.nq.gz
│   ├── d601a69a9f72498322a9d389d127e22e2ff5a131.nq.gz
│   ├── d7c06fba7602b47671952e94e187e7ceed6cc006.nq.gz
│   ├── d8b1270478a37827f1f8bd1c72dfb328ee68b65e.nq.gz
│   ├── daa43720ca6d874a7c2af944e0f37401d6c93957.nq.gz
│   ├── dc5809ee1fa0b7e30067f5cd9f643fa66bb27503.nq.gz
│   ├── dceaeeda48315bc3aef1b863976dce40b5b15f0f.nq.gz
│   ├── deea961e29516673390e62c41c48e2fe14ac7bfb.nq.gz
│   ├── df5079c06c9960a1aa830001e217eb92f342fccf.nq.gz
│   ├── dfa7a247737c8a6ace99141b09fe463add27ef3f.nq.gz
│   ├── e0223e1ad03c12c057deb001f7d2596390f5b8f2.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e1942a13093a428043ff3c2cad179760d492e909.nq.gz
│   ├── e272c5a7f09339e6e8da38e93b30c92ed14c562d.nq.gz
│   ├── e399dd90bc0ab83eabc79027e1fb1e5c1fefe79d.nq.gz
│   ├── e3ab4942faf0348025fd13bdf6e1178e4b776405.nq.gz
│   ├── e4858059f75e07fa9bce90e1c5eb8810f8d5e7ec.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e812ed20c50d34ea812b2ee5bf5c16446a4d8ea2.nq.gz
│   ├── e98f8967312ba83c782b857d194415dacc9a47d4.nq.gz
│   ├── ea11d76c6551b668d50791fb408a7f10170b4ea2.nq.gz
│   ├── eb64347eb83e65e912bd2fdd67cd5f907f22765b.nq.gz
│   ├── ecb5392119af6fb70558931055bbb1fdf936d182.nq.gz
│   ├── f14aba7e8476ec56bc37d4fb6b07e3fbe1167c10.nq.gz
│   ├── f1e863dc959953a73aecb7c4c1854355f86c8930.nq.gz
│   ├── f36913c6a892f0de722913b70be0ad5a26332c81.nq.gz
│   ├── f3ea739c087002d879bf051c53741c754fe49548.nq.gz
│   ├── f96c008ff40b0136e5e56e43cd72e367319851a1.nq.gz
│   ├── fa2446ea54ce74c63ec03c168266425010464f31.nq.gz
│   └── fedbae9edd9f39a13d36a53609ed1027ebdc53d2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ff0aeb909fc05d5419cf54b65ff9d01cb6b4189a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 143 files
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

[jazzband/django-downloadview](https://github.com/jazzband/django-downloadview)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
