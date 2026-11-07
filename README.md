# Repolex Knowledge Graph of huggingface/relore

RDF knowledge graph data for [huggingface/relore](https://github.com/huggingface/relore), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/relore
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 06a1c99c4653e9db899a18e96d8ff0ee6b419815
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 06a1c99c4653e9db899a18e96d8ff0ee6b419815
│           └── chunk-001.nq.gz
├── blob
│   ├── 02d658ee33e799aa44041a67bbef755463439a7c.nq.gz
│   ├── 04dbe40113ce84c9a26e6a6995039ee141315c50.nq.gz
│   ├── 07e2f6ee62c0ae733463ff8c14badde792582d9c.nq.gz
│   ├── 08e18965409639a9d146261864c7f8f03eadc333.nq.gz
│   ├── 0a031d553f20099bab40aec3d1ffe5392bf0d3f3.nq.gz
│   ├── 0ada8bf8fbf6e452a8827e909c7e0156abee6109.nq.gz
│   ├── 0cd941102bc774308325cc75da66fb5421393a82.nq.gz
│   ├── 0da148aedbb703f6b5ad6f8355fd47f26dc0c8ce.nq.gz
│   ├── 0e0c20f3d523209c29dfebd871394e6d52d2e589.nq.gz
│   ├── 1198ef22909ed277e4316f70179bb519610940a3.nq.gz
│   ├── 135bde65a3efa17a243fd8835372136f50dbbe70.nq.gz
│   ├── 1558e2ab1839c60742ceb258bcb50f2f6294a9ca.nq.gz
│   ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
│   ├── 1602d46ef4b1684a850ed74d55489c0cce6bdfbb.nq.gz
│   ├── 16153690e6aad10fab6b42c8ef43d3d9debd74fe.nq.gz
│   ├── 176f56ce3951c49a864cdef4826fdf56965ce466.nq.gz
│   ├── 17f5d12b5b0f7c73a05fdfbcfeba7a5eec864f38.nq.gz
│   ├── 1922637152d1635c583433d8aa16c47f8c2ba56a.nq.gz
│   ├── 1b42d0e52844b22a15db8e23117faca25d49d6e7.nq.gz
│   ├── 1cc6f997b632ea988213d1f885f4c5005c034a20.nq.gz
│   ├── 2120a84bf7f7ef338f098c65e235bcb1a2299a94.nq.gz
│   ├── 235b015bdcb480487b4948e356f3634a4cc474d2.nq.gz
│   ├── 23cb80104a5079ffe0ad38da8b6a02c8d2176e39.nq.gz
│   ├── 2815a2c65cff0bcec4f2b7ea1512654d80f4884e.nq.gz
│   ├── 296d2adf48337751977a468b40b908caf2f0e660.nq.gz
│   ├── 2a263370f6231593aa56f884336b62ac82a2d96b.nq.gz
│   ├── 2b1a3634acff0862f8cb5c1a0163de375a99362d.nq.gz
│   ├── 2bf9f17e71385d9511456e64cb35f3db629932d1.nq.gz
│   ├── 2e510aff5855ba46f96cbcd10991d9d588f77e6c.nq.gz
│   ├── 2ebfac5ec54b53282c068874737f8e5084c2e562.nq.gz
│   ├── 2f7c90343801e2eb5300c884fd341c7cec718cf2.nq.gz
│   ├── 31cdb5f64eb2290cd91f607aa4d621ed35237a09.nq.gz
│   ├── 323a32f4e15da8be2b80024e24d35bef6db7c805.nq.gz
│   ├── 33d2fcc2f84fb3a16b1ef803badbb1100ef4f65c.nq.gz
│   ├── 3483fa4d0ab77700f84ea2ebccdc379db0ac36d1.nq.gz
│   ├── 34e7dc752dd89936bc70786c4432036c8b69bcd3.nq.gz
│   ├── 34ef49dfb50ae88d8b85fa6cb0038d72206e507a.nq.gz
│   ├── 3592cbd9c071fde47a904a4abd92e420c29f7aef.nq.gz
│   ├── 366ca149cb7c930a074f77c75ccda35f8e0510b5.nq.gz
│   ├── 375c6a716a16be10b14403b90466da0bb3d7b751.nq.gz
│   ├── 3810ab1a698d78fe39e021b3a3ed65f37be02f84.nq.gz
│   ├── 3839a05b48fe1d6ee8a3f2406e1b3b15fc8d6e40.nq.gz
│   ├── 3b760225635026cd0621a7816be2f4105fdcaf09.nq.gz
│   ├── 3b955d5cea5bb02f1b6b9701727fd0f20561209f.nq.gz
│   ├── 3c1d19fa7f948a76d4057f4d15cee290c92e788f.nq.gz
│   ├── 3cf7e9fee7eec6896b110b82cf0474fd4ac09c7f.nq.gz
│   ├── 3e4f17b19d36dc33a6a806517c20d3e481f4cf27.nq.gz
│   ├── 3f6af2f0481ae81971dcd714c065f66629c3609f.nq.gz
│   ├── 40a7ad5d2e29aa340477487a115e2f6a026fa612.nq.gz
│   ├── 42f525fc2727e19ae8eef3e85aee66101336349e.nq.gz
│   ├── 4527d4902748fa8d85f21336032b7a856023a8f6.nq.gz
│   ├── 45c4d8d9fac8c885c94dace7963843f200692456.nq.gz
│   ├── 46bbc5d8b464156a45c4b0c94e47e10e16ad42db.nq.gz
│   ├── 4a0e5ca2db87098b9c59f88cedd2be6359b9bba6.nq.gz
│   ├── 4b113eb11328631ed6032242d60d8166e8a808db.nq.gz
│   ├── 4b9d7febdb145d243c33b4db64a2e1f0783a912a.nq.gz
│   ├── 4c61d5fb0aadb806836d35acb829c4c7ce741a7b.nq.gz
│   ├── 4e1e0dc4079753b10e91d7cb88d06f6f83643430.nq.gz
│   ├── 51aa9a32ff77b2580d7bf7546210489c33fe8fff.nq.gz
│   ├── 51ef43cfc53e2ba4f5ea9759bb21ebb43fdf114b.nq.gz
│   ├── 52b0ab91ed98cd58c56909ff31cc5eee655490e0.nq.gz
│   ├── 5404d419c17bd69b3a2848316b454cb98080560a.nq.gz
│   ├── 550d96cf08574d8b9e44d98d27935f06afd455b0.nq.gz
│   ├── 551ada7c0ae75feb29fb0d874ff8b6ebd785c562.nq.gz
│   ├── 55ca53e2907852383c140c87407b4be92a3e5e65.nq.gz
│   ├── 57bb8c1f56127f163ea1561bb82a9898253427cf.nq.gz
│   ├── 5866ce89a173bf04c8b1cdd58f56366d12de09f9.nq.gz
│   ├── 59829ea5d312fccabb125cc5b5d108137344f71a.nq.gz
│   ├── 5d4456006ab5ce44a68be69c3354f1c934043654.nq.gz
│   ├── 5d8417166257ea2a48fd717fdce9f4602e3911c8.nq.gz
│   ├── 64f096324d5cb7b4b4d145236d307cf455d7c1a0.nq.gz
│   ├── 653f417e547058a28d876a33af420ae667233022.nq.gz
│   ├── 66164b7db3a1bf520ccb64f909d7152b426c70a4.nq.gz
│   ├── 66aa6dd4ac7cd5ea91d4b4cdc1158c8df3247fae.nq.gz
│   ├── 68a30499d24524a0a64a9882f8754fc0fdfc60d6.nq.gz
│   ├── 6a5a9fa452c205824f0252c770a90e7a87ca85bb.nq.gz
│   ├── 6addc64359064ac8e77c88786d0a4c08554eeee7.nq.gz
│   ├── 6b3cdcddf85a3e38d7df4761ec017121ee20ed6b.nq.gz
│   ├── 6c4a8f29dfc46f6ca362cb58981302810f256829.nq.gz
│   ├── 6cda06c1307dd87d455a1da550462d11898e798f.nq.gz
│   ├── 6e01a8dad6c77d8c61dd3372ac37a9ff5af29a17.nq.gz
│   ├── 6f86069b99eb774fdcc25cce5075927f56a88d58.nq.gz
│   ├── 701fc49b5efa9cf1a75a41614d3ebed6713c884a.nq.gz
│   ├── 704104dc8415cc0a1a653244379af0d0b6622475.nq.gz
│   ├── 70ec141703eec0a92955c744c7dca94e3d85072e.nq.gz
│   ├── 717779f03c572f69131a3a95b20e79c14d115771.nq.gz
│   ├── 71d804d5fb3b5acf8b58c7abad65569ff3d844eb.nq.gz
│   ├── 7608ce70a9e074929c007a5b9f339d88b7ff0e90.nq.gz
│   ├── 785a1a43d7491e22bb89ec36a9b602d4e56ce483.nq.gz
│   ├── 79b13cd4182a5b329aee60ab54a8f2ea2ca253ca.nq.gz
│   ├── 7b9004ff5cc4f679708324c1eec1a58f6af37bf0.nq.gz
│   ├── 7e5f3a3e086328e583cf78c835bba1644e4e5765.nq.gz
│   ├── 7e6fa128a15071269a7af6332f667fd9d7dfcd65.nq.gz
│   ├── 8026dd31cc7540be05b414649cec8f8c9ca0e51d.nq.gz
│   ├── 80608abdba9b6f8f9342ad5e51b4e3720ed5808e.nq.gz
│   ├── 80bbbf22eedac6c0bab8fa22cba54ec47cdffc92.nq.gz
│   ├── 80d8599f479a3db2f23129a79ad78650e97bf2aa.nq.gz
│   ├── 80ee75f90650fc647d063f4f79a7c3578a8ee312.nq.gz
│   ├── 81355a37056e825c02c3f7df4e10a90a5a5c0a3f.nq.gz
│   ├── 8193cf72c3b25caf3982afc4070c0c2586762d83.nq.gz
│   ├── 8411f696334a43054bf9a2426a962a5a1b3b80af.nq.gz
│   ├── 860adeae1fe8c2d136b8b89fa1b4f88170e27778.nq.gz
│   ├── 8a6b65b2ded45df60ea7c234ddc80d8b2f8c6b24.nq.gz
│   ├── 8b529d660b19a93d4bf97e550932a43c0f933b37.nq.gz
│   ├── 8b69c2b42aa5653c69b10c7dc9a0dce1a2225f78.nq.gz
│   ├── 8da7dde665463fa2a23b2e3f75e2cb49e119ddbe.nq.gz
│   ├── 9032887649861ed2a71d3357b6e032ec520c48c5.nq.gz
│   ├── 909cc429ef5e52fdb453e07218c73d095641155c.nq.gz
│   ├── 927db815f3a79727cacaa04332d89d84663020e2.nq.gz
│   ├── 95571670d8fc217ef63268aaf5b039e84303bc89.nq.gz
│   ├── 962411379b550a5a530d79eaf6f3f0f6132c36e5.nq.gz
│   ├── 99c686f7c72227e0860ea3c6fa796cc07597c5ca.nq.gz
│   ├── 9bc4149120bd766c9600e299e4cfaff3101ea2f8.nq.gz
│   ├── 9d2564b0b8bdbef7e9af647a8bee4a5a45c0a7a2.nq.gz
│   ├── a1af5ca71484f1fe9560eaad71700f6a32ba5565.nq.gz
│   ├── a852f7271244a74d91ff63033d9ebde3d0c90604.nq.gz
│   ├── abe64c22e5d9e21808f8d1cea8a3bd1749a1c26b.nq.gz
│   ├── ae6f2706574146311e61186deaff4b68e51de376.nq.gz
│   ├── b29800aa30f89e6afc1aa68f8467f964b320d681.nq.gz
│   ├── b2a90381393f43231eef00ebd6d971bda56a15e3.nq.gz
│   ├── b3d84fadbfbf0eff922be745949bb02afb5bc454.nq.gz
│   ├── b43db927ea72b77d294fd6c96ad0471c13393f19.nq.gz
│   ├── b5ada733f81d2185e7ad63371e0ddb1c9ea9cd46.nq.gz
│   ├── b7b38087a1265b69cbd90681bedbe6878344e379.nq.gz
│   ├── baa8b01706f8bbbff223a3a5de37e2dbb777b824.nq.gz
│   ├── bcbde80515cafca162b631987fd6cd58931b134d.nq.gz
│   ├── beac34edfe648f9b9397d93a454cdb9970d98789.nq.gz
│   ├── beb280ff3b1b72790d73ec62a39a3c7ef2c0a6a5.nq.gz
│   ├── c0c3c359c5319b0037f951d69d6800b3b982a4d5.nq.gz
│   ├── c5107949c5f391b63321d6dd5e78d0f3a2d09e9a.nq.gz
│   ├── c677ca5e9177f87ab313df63fc411500cd4013bb.nq.gz
│   ├── c882e738986685081ec9d7efce502151561cf2ad.nq.gz
│   ├── c91ab882b3e0c7b017f2312245b9c6123d538915.nq.gz
│   ├── c9629c9bc5690c0c32b0d9930cd91f99823c773f.nq.gz
│   ├── c986ed478bed64f46c2d84d5af6f90b73d42d4c4.nq.gz
│   ├── cb7a028ebe5926a927433bb801e366b7031cc3d3.nq.gz
│   ├── ce74a64dbcf8e3c9775ce4999eb991965d57000b.nq.gz
│   ├── cec2a2f0da28afc0aeff672cbf9d534ebe8eee03.nq.gz
│   ├── cf09bc285ebc8707e5f7c020bfde291ad047ab6b.nq.gz
│   ├── d18ac6f02ef6652b15347a2c8d16d262ab52b992.nq.gz
│   ├── d583f677ce837a59703f017f916f18c448aee334.nq.gz
│   ├── d7d214f09fc51f06d88e48c74ab667cd00a35f30.nq.gz
│   ├── d9b263aec300421e2f8992967f33511e8988fe8e.nq.gz
│   ├── dadb1e44720ba61c09d69035656f4e998769eefc.nq.gz
│   ├── db895917af235916a5d473d4fee44a59c80f55d0.nq.gz
│   ├── dc0143e4a8e3d275451a4618451a444ae4efe724.nq.gz
│   ├── dcb6a6eb722f368d62f20dcf1fd60daa9bc6eeb7.nq.gz
│   ├── dd4cf6cf33131c4c369ea8900bb3ddd46c0813b5.nq.gz
│   ├── de67a36f9bd64b16e8e4d6203f905d62f353f438.nq.gz
│   ├── dee059147ab23369435ca5bf04756c213351cc18.nq.gz
│   ├── e27816da0c2167da91e51f5dcf9a4c4d35190e0d.nq.gz
│   ├── e572e6e81cdfdb106a8767999711ade8cb32d51b.nq.gz
│   ├── e67de0a8c6de8692efb6ea5930835b87613d390e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e72392b59060783316bd2485f7dcabe97013e3c5.nq.gz
│   ├── ea52be9837e69ea913be27b15118ea540ea51323.nq.gz
│   ├── ef80647e481bb5a6d02b9d95494c00a17c3b7522.nq.gz
│   ├── f0086fceda78b924c00753a245a857abe056aa64.nq.gz
│   ├── f1142ef9eee21366c69a48477818a7185b26dbf2.nq.gz
│   ├── f67f9084e515598af9a80f1606841302db315046.nq.gz
│   ├── f7491d087ecfd06b1c620f4786ec0f68ceb74b23.nq.gz
│   ├── f7cd625d307309526dad2c02d8e066baa76f884e.nq.gz
│   ├── f8a48b84f3fc1bad23fedc267a3959792c9d0e5b.nq.gz
│   ├── fc71eea1e56c577eb7743153d59e45fdb6161bc7.nq.gz
│   ├── fd0363216aa68a138544557ab765d499a3d9a224.nq.gz
│   ├── fddf3f8d6766f5290e6cb99e493a4efe0108f65d.nq.gz
│   ├── feff18ea45bfe892ec7adb3831e8f16101b7dfab.nq.gz
│   └── ff1743b64e8a71bc6e85890d934632e6090e08c4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 06a1c99c4653e9db899a18e96d8ff0ee6b419815.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 176 files
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

[huggingface/relore](https://github.com/huggingface/relore)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
