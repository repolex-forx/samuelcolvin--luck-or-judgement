# Repolex Knowledge Graph of samuelcolvin/luck-or-judgement

RDF knowledge graph data for [samuelcolvin/luck-or-judgement](https://github.com/samuelcolvin/luck-or-judgement), parsed by [repolex](https://repolex.ai).

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
rlex download samuelcolvin/luck-or-judgement
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ecc7c9e5a6cf271fcffab26e511c2ac79a578127
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ecc7c9e5a6cf271fcffab26e511c2ac79a578127
│           └── chunk-001.nq.gz
├── blob
│   ├── 04be076b6d0f9245d8db71f9f6829a3709cc0182.nq.gz
│   ├── 055c675ec43b3dd4e41ac1ef0d039c8b11d0f754.nq.gz
│   ├── 058f0a01705d719f8e0fd7aae5ab0a73a0ec66c8.nq.gz
│   ├── 083b92381cf1e0fb145e6485e459f2e0b49029ec.nq.gz
│   ├── 0f8241d33121867f3ed4535a88ec3f28539ad7ad.nq.gz
│   ├── 1035ae837b05ef7f3780d615388d8c5216033906.nq.gz
│   ├── 10fc0ae37e6827439e6f5c519ceef7224e7e04a0.nq.gz
│   ├── 13266a0d5b3840d266bb718c4797dec6ed4c1386.nq.gz
│   ├── 171d06cee168d5a9cae57b4b1f62cecbd71f293d.nq.gz
│   ├── 1aae3d0e821262dc6257e22a0a78d58c6694277a.nq.gz
│   ├── 1ab37c85bdd6b2a756101186bba73da32931f434.nq.gz
│   ├── 1cd0f516bdabd611c29ea81e2995df487f672d9b.nq.gz
│   ├── 1d3c40392b6c7687237abf76ec173f6d52d0773b.nq.gz
│   ├── 1fd37f4ff3b37a0b16b14d7fb2d57402ec223166.nq.gz
│   ├── 1fdbd74933f3b75b94c8eb9b1a9d5e0592f006ae.nq.gz
│   ├── 220d4d4872cf789cbc33d1fa4dcff664e4bb9cdb.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 25e0c2f71de909fea3c4226fa182fcf9274a4790.nq.gz
│   ├── 26c69a4f88557341aa46d012ed40da829ccf0805.nq.gz
│   ├── 28789764ef9f709eb69e4e0d0c81af9ac0e53706.nq.gz
│   ├── 2a38e00a8c55d3e47d36393fdf6fa5fe520455cb.nq.gz
│   ├── 2a551fb79cc04b2d91706ddc9e0619818dbe9dbf.nq.gz
│   ├── 2ea18ba6bf4e6dc9c45363fba5834b14bd2a7dc0.nq.gz
│   ├── 34ac463727420d5cd138685065a809ca2db926ad.nq.gz
│   ├── 34bb2c3edcdcd69be0c2514a098a1d5335369b14.nq.gz
│   ├── 353fb58e975c4f33f2c397668bc84123c0cc7292.nq.gz
│   ├── 36846ff99991b7504b19d433dc131bda40a2d66f.nq.gz
│   ├── 391f13b0d0ae36c1211b50ae5da53d3423cf7d74.nq.gz
│   ├── 3af7dc6fcad6bf617230c77b46e9ff89d992f3d4.nq.gz
│   ├── 3c5ff55a985057a198a1aed0031c2cb5790d83f1.nq.gz
│   ├── 3e4488fb44fe0667995c8f17ca02a02b82d170c6.nq.gz
│   ├── 3f08e1572a6a06b05511ce0169d21b6d41d2483b.nq.gz
│   ├── 3f71d8a7e5d8847d2da180c98fecf59df6f0707d.nq.gz
│   ├── 40c449a31e5da6a331a5bd6681a1f1b21ca81de1.nq.gz
│   ├── 429ed7876cdaf97903fd291b04a479c638a1fc5a.nq.gz
│   ├── 45decd43443e0566e067b6c480075d786cedf5dc.nq.gz
│   ├── 467e3dd677a4ff7c267395f81b46cb6f7ba311f5.nq.gz
│   ├── 4864b935252ad7f1fac9ef72f30c10cd2251fc49.nq.gz
│   ├── 4a71dd6b8eb8faee855b2455cb5c47f564911bca.nq.gz
│   ├── 4aa47594677e49c69e3f074118de70479abbcdd1.nq.gz
│   ├── 4b37587fe8c76a39558a1c74c3b1bdcbb8c6e9ff.nq.gz
│   ├── 4ef856bf8e67d5cee0636ad26054261fbeffe22f.nq.gz
│   ├── 4ff1bb0c630b3ce0b73825f50a7627c28b858a43.nq.gz
│   ├── 503dd624933479ca5507c50afb84be1ef5e81397.nq.gz
│   ├── 51c044bf23d5cf1401e44e07efa94468bfc7b18c.nq.gz
│   ├── 51d30ef8d02aec3c6424a465e2793b1fe2c27c7d.nq.gz
│   ├── 5412f817ccaf902098af759d19d560458ca5f771.nq.gz
│   ├── 57ff9aad7b3bf7952f3c8bd2f75e30d5aba882df.nq.gz
│   ├── 5ad7117829214a32bc09548e632052ad760d1f6b.nq.gz
│   ├── 5b2335720ea6f0fc7dbe9387c33a55b863516818.nq.gz
│   ├── 5b82729ca20a7897c95b50c5bad5790d51758ea5.nq.gz
│   ├── 5c670499fc91383e49f045f902c835f956d62201.nq.gz
│   ├── 5c949462b3f6987dd098fcc7449cc0fc2d61c991.nq.gz
│   ├── 5d2ab35c0cd587725bab5f6eb7a789c718cbdf8d.nq.gz
│   ├── 5d4756a6409a5cdcf6483e071df5c93f544731dc.nq.gz
│   ├── 5dac0dc25fa5e743002c6ede682de4d82c906403.nq.gz
│   ├── 5f764b7c0aadf648dc6ca420f4a9522fb9e915c4.nq.gz
│   ├── 6163380260de19db68af81d8fb1e482c0456e629.nq.gz
│   ├── 6197dfa3bed3d106a86021ff18bed42a9744405b.nq.gz
│   ├── 61a8a095a298faf9bbdcf9db2ad92544a3d62f22.nq.gz
│   ├── 62dc78d81c919f163cccee188be6c4306afa7461.nq.gz
│   ├── 639bf1cf6ce1c86d5130b0d0f008f084c3829132.nq.gz
│   ├── 6576a60269f628bfa5e34620e6b1a74339ad8b74.nq.gz
│   ├── 65930428ae444b6ae16c2f5cebd2c582872a6757.nq.gz
│   ├── 68b15a46884bb9d36cb604acf4669cd1b4a70dc1.nq.gz
│   ├── 692aa394e82b9fd0931a78caa19c21d4ce3a043a.nq.gz
│   ├── 6d87bfa2d84f1e426efbedbe084c6e72426d8605.nq.gz
│   ├── 6f74ed4c57d755eeaa4a15444ca94e50930d8a66.nq.gz
│   ├── 71c885be9486dc4ac99871b596a5ab9028d5ff01.nq.gz
│   ├── 750dba6e053e5c472d3e9c5813552ebd52478c7a.nq.gz
│   ├── 76e197ba8e321612d57491d37ad5a6fcc6b44aec.nq.gz
│   ├── 771bf425d4921c9ede6a1d13f55e3ea135df6aed.nq.gz
│   ├── 783b5adb238245c1965f01278e4e2ab355f2532e.nq.gz
│   ├── 822d9153965d704979d7f0a6a7060d2bef74e4f9.nq.gz
│   ├── 82c22b193c866b5f5f62da386c028134c74abf27.nq.gz
│   ├── 8342ddf4463cb59244c3c7f6ea253522fd90f774.nq.gz
│   ├── 8915de455b569a5579a909b92c59f24021ffb89d.nq.gz
│   ├── 8a8192b439a0c8c6ffab6357788489dd80b081b6.nq.gz
│   ├── 8a9b2e2d2a70d459421c9b2e534cb708951664b6.nq.gz
│   ├── 8b2b98c0f640db7b436099c15df808f73fbfe058.nq.gz
│   ├── 8dee25975b870c3ff987a4a37830f41eb572060b.nq.gz
│   ├── 8eb99235291841b18a00fd8051b1f21f56510cb5.nq.gz
│   ├── 92b76138dfadcb3740eb227ac336ed610131f421.nq.gz
│   ├── 94739bc422916db1890d3bfc316d21aa6e42cf70.nq.gz
│   ├── 9828e877f0a4b00fcd73b5c173741e4db0a2cad0.nq.gz
│   ├── 9f991220f75e23e270ff153e8dcdc2959ec78ffb.nq.gz
│   ├── a0347c235b2c1040c335e0b4a220e38f1cf0c18f.nq.gz
│   ├── a03a05abad81273deef624e4a5fababefc1e5861.nq.gz
│   ├── a1a062ca5ac5a7aceb92b4ad3a3673d601dd005e.nq.gz
│   ├── a330df49f184a6edf0a9dc2eb4587355658699b5.nq.gz
│   ├── a4891af8493890fb85065a0b7a9fcca097d97419.nq.gz
│   ├── ab4a8c7b35af37e9cb67c135cc1b539cd64a7f4f.nq.gz
│   ├── ac09d0f0a7b291420e4a1952700897b03e1c3259.nq.gz
│   ├── aefa681eee9e6752055af900a625578af4973349.nq.gz
│   ├── b03a467a0848b5b5e889297b1460df59cbe9c796.nq.gz
│   ├── b0a5cd0aa6bb18b4e605bdbff8908f414b9e15aa.nq.gz
│   ├── b1ce39004dc1a0582494e842510a70d260ac1c2a.nq.gz
│   ├── b447293554c22d9e59af5592cb73781aa6580fb7.nq.gz
│   ├── b4edd013b5707d15d0428700b3d9dc885d5a66d2.nq.gz
│   ├── b658d13d32b84619fceff57ceab8527d102bfbf4.nq.gz
│   ├── b76132c2e5f0e31852be4f5542a4d604eb441680.nq.gz
│   ├── b8bc228fad12669629fa9b5d27fbe0d006fb5d92.nq.gz
│   ├── beda5496cbc564fdf2b054e3767b1c41b24401d2.nq.gz
│   ├── bff8047a23e928ea00f05fb4781906eba3ad0b0f.nq.gz
│   ├── c082f778457490537d2922b1c1b30aa0ebc34bea.nq.gz
│   ├── c08b8cf03ce264754f3eb6ac92fb105509150fee.nq.gz
│   ├── c14c635b71a6fb44ebd48db1dc7b36e7b6291b54.nq.gz
│   ├── c29f4e7ac09ac4aca4b615e6d4344796ea22e840.nq.gz
│   ├── c594e97f05286343b483dc83e65b59e887cae748.nq.gz
│   ├── c8cd0f4be29a337bd0f90f4bec18c194127d4336.nq.gz
│   ├── c9d94659757684aca1ba1e664d10205ebf373a22.nq.gz
│   ├── c9f53c6b4a3235cecdfdd53a5c5fe04d8e08bd5f.nq.gz
│   ├── cb7f529ba2d472301bc8647beb42d45cecd9b72c.nq.gz
│   ├── cfedd39940b8ba9ea7b5768e7f0653eb16330e4d.nq.gz
│   ├── d01554414951d7a6560548a2d855f71b21bfa73d.nq.gz
│   ├── d09fcac44a6317b61022ee6306c497069eb7e2ed.nq.gz
│   ├── d1a3725a17cc2588e49a966934355435d2a964dc.nq.gz
│   ├── d20bb16a995bcd839f8b63d931264e7555800b25.nq.gz
│   ├── d2f3712218455da3ebaecc9e210485f0f58f4a56.nq.gz
│   ├── d750817073b792ab164d177fb9a7bf087ea7ee75.nq.gz
│   ├── d7a16f8b375509e1d39f8e35b3f5ccc95112806f.nq.gz
│   ├── d9deeae3eff91c9187b67b7188149bd82ae117cf.nq.gz
│   ├── d9ea0d47866b9c39a56997bdde9d572fd2318851.nq.gz
│   ├── da5601f17e174af2b22aea0e4da4ff9f4766d8cb.nq.gz
│   ├── dce2b3687268c5fc232d4248298476681163eda8.nq.gz
│   ├── dd57705a7ac1c5fb81a72a3cf6a97f5a984510fb.nq.gz
│   ├── dee2e0d07c1c42af766f510766d4f58ab51923cd.nq.gz
│   ├── e0e47a30658d12149ca2ccb572fd2a856068c259.nq.gz
│   ├── e250ced830d396a9264a51ea8a9dae6b8a7fc713.nq.gz
│   ├── e675942eb2d3cfef9b46adc3afabd956664a79ae.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7f20ba3a61e02599fc1ee6fbd53ea58dca52904.nq.gz
│   ├── e93b74b457ee4130343d07ce5f0a1b590d82d0b2.nq.gz
│   ├── ea3c80060a3164b0c28e76abab177f6133c71894.nq.gz
│   ├── f7f0a28f842457acef4666b1561554a5c0db1248.nq.gz
│   ├── f8738e7608d9c2d05701572427c15227cf6972f3.nq.gz
│   ├── fa3868b78d55108f453b7d5722b9ca7f13387abb.nq.gz
│   ├── fbcd8cd00f45486d86b65b2a2913ceb05d632660.nq.gz
│   ├── fd3ae856f4f3c0c9077bde3e714408c840f6604f.nq.gz
│   ├── fe7107f8e7479ea89b02fd71e300f9275fab9bbc.nq.gz
│   ├── ff022496ec6ec232b68ad7bc1d50bda406997f99.nq.gz
│   └── ff4fe30a512646430f4beb51f09036e4db3c210d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ecc7c9e5a6cf271fcffab26e511c2ac79a578127.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 148 files
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

[samuelcolvin/luck-or-judgement](https://github.com/samuelcolvin/luck-or-judgement)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
