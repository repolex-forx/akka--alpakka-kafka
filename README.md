# Repolex Knowledge Graph of akka/alpakka-kafka

RDF knowledge graph data for [akka/alpakka-kafka](https://github.com/akka/alpakka-kafka), parsed by [repolex](https://repolex.ai).

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
rlex download akka/alpakka-kafka
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4e1e9fb11cb125a331031d8631f1232938421098
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4e1e9fb11cb125a331031d8631f1232938421098
│           └── chunk-001.nq.gz
└── blob
    ├── 02b7ad9235aa4f7a83906b861a8cc3eb8d721e43.nq.gz
    ├── 02f10c2261faa78eb8ff704756e26b5e12a1c2db.nq.gz
    ├── 033482d697f7154c970986dd964bd30decd44ffa.nq.gz
    ├── 045c25618c7f2c750f97e402db1d2fc43648e97b.nq.gz
    ├── 04ba541217457d820ef93b1194d99e260da5f921.nq.gz
    ├── 064c6235797901d817488d7483dffc46634c9ba0.nq.gz
    ├── 06c64410d4ba45895665d98f2c0617bd7da9e38e.nq.gz
    ├── 06e912866bc35f35f4bb4ea94d6c29b0fc4ba41d.nq.gz
    ├── 07bce943e40b45fbeaa57187ad10c8a8759751bf.nq.gz
    ├── 08e9e0b020bd2af561b44d73413f645c5da64bae.nq.gz
    ├── 0ad2f6e8c4e0880ca3aed2f78469813bc1361550.nq.gz
    ├── 0ae6506992ea83c0c5edc07fb22d2ca2b48c3abc.nq.gz
    ├── 0b2a1a3e9a5b6a1c7cd2d1b996170c2e3344ba68.nq.gz
    ├── 0b440321df850d76ce57fe22b6bebe8814d1037e.nq.gz
    ├── 0c8eedc2cec67cd185813f8fac7a79ea855e7cda.nq.gz
    ├── 0d25981901e3ebcb3a01204251443ca2d3789aeb.nq.gz
    ├── 0e884afbfdeb024d2c530d013a0d4ff82bf2eeed.nq.gz
    ├── 0f38b162fdc0b8d1be8059c3108f476b52266e38.nq.gz
    ├── 0f54f34241bf3a142f6686c4dcbc67338ef16b23.nq.gz
    ├── 10009ca641047c227792e3b101f5a3db9cff9499.nq.gz
    ├── 108fd9a800e4b8a8e39a222aca89832f4fa16ef2.nq.gz
    ├── 13c73da68492bf1b9d91e45cb9b09ea2c19e61b4.nq.gz
    ├── 1604e736a462b26ff7c73bea5c73e11ce241fefd.nq.gz
    ├── 16a5f81fef7d1d61d0febb8aa042ef83d0847d7b.nq.gz
    ├── 16d65d029b82f9db6d86a677b72bd71282875116.nq.gz
    ├── 18c7c0cd2d2629c43288284483e44f7dc59013a8.nq.gz
    ├── 18d8a8708b449a465a62a29f1563823df7e58d65.nq.gz
    ├── 19048f7aa1c8baaa1417db928ec8dd25c311a6bf.nq.gz
    ├── 1aaa8ad2d11bc69e42c5a65f90a1ddd31a538857.nq.gz
    ├── 1aacf00532bc8cd2d253fabb50a0d880717f0310.nq.gz
    ├── 1b27495b0865b64192d6cf0bbc9f2717bd8f0196.nq.gz
    ├── 1b49851ffa9c3e5bacd232c452b4d4cb03b645b4.nq.gz
    ├── 1c36c7f4e007b00e14f77cab82661639a38bc09a.nq.gz
    ├── 1cc9152eb337dc95f8eebbcfb47824e04c36b099.nq.gz
    ├── 1db31bfb238ecd29d5881b450fd420b28f406111.nq.gz
    ├── 1e6ed63ce68c126147e47d560a3141a8e3ef18e9.nq.gz
    ├── 2075ea1b515fe4763b9ac4c2be082b9c1aab1d1b.nq.gz
    ├── 20b29f4331ebc22d822d7eabf05b6234cc37c55c.nq.gz
    ├── 21e3b7477795d9751ed3f13e46a23f60d31548a2.nq.gz
    ├── 22a84ea08fe2c1f5efd9e764358174c646bd7eef.nq.gz
    ├── 22c5f5527959cc5cb35f542cff7325bb2cb96eb6.nq.gz
    ├── 243ffe2b4f11a90e4f01791ad188516b90bb1e00.nq.gz
    ├── 268a3cded7c958f89bee5134f5c914ab9dfc8001.nq.gz
    ├── 28dbb22127cf454cdb8164a6df8b7d65364eb42e.nq.gz
    ├── 293a2805b87c18e3bf79b85ac14dd754ddd8709b.nq.gz
    ├── 295cdf61059bc139880a487debc388c3903cb322.nq.gz
    ├── 29c4982ebc2c54525e2dbef4568fb57753be221c.nq.gz
    ├── 29cda21a8e1d677c71a79069879313d28c29aef8.nq.gz
    ├── 29d01f4abb6fe5f488bf24b9714ad0b786d199e3.nq.gz
    ├── 2a10f89c729d055049af651ef8d80634ca2b2d9c.nq.gz
    ├── 2bb6e854eecdad001e93fa483541a7616f18ba9f.nq.gz
    ├── 2c48a005a5da9b4deee5e46c594be9cb6f5e7dff.nq.gz
    ├── 2c6440d5d88ad21ff5a325cd0c0e3c8d4f3cff33.nq.gz
    ├── 2d153c54929fbb56fb913d2d0636698b7c54c3d0.nq.gz
    ├── 2dd07e8bed7139b49434cc7bc020560314d74037.nq.gz
    ├── 2e2b3ad40d7f7ec2f547aef29c4c867b1a4e79ae.nq.gz
    ├── 2ffae4bfcaf6dc28e07fa94e10bffc8bf684aeff.nq.gz
    ├── 314a8dc3682c8732cae4ad7c6165785061229427.nq.gz
    ├── 3187375912d136e1f10c7d640526b6b849c7f65d.nq.gz
    ├── 32454579930b215e30794ab90bbe11fa4382c961.nq.gz
    ├── 33f1ba2821f05c28572ea1082087c644e6f277ba.nq.gz
    ├── 34c2763f8b16238c6ec2f16d4dc73d9733207991.nq.gz
    ├── 354ad43e753c8556e2d481897a43f2aaf9ff4266.nq.gz
    ├── 36170f47dd056f4e55b6faeffb475e9891c745af.nq.gz
    ├── 37a8c152a1223802434685fcc5777e9d875170a1.nq.gz
    ├── 3838e58e7ab7141a8c9665ebdd2130cf8cc16317.nq.gz
    ├── 39dde16312542c69a5304b3f3b43825fee4a4c94.nq.gz
    ├── 3a847fe6aad3e2f5caebe2fd8591eaf6a23c3054.nq.gz
    ├── 3ba1e933b993c10cb0348834522214ab430d72fc.nq.gz
    ├── 3f766b9f20970595da502889ad4d28ac8c3eb265.nq.gz
    ├── 40a824d911baf8b30fc8ff65f3c0b8f4cfb8bee8.nq.gz
    ├── 40fb71891e888e93a9ef8572286328e6fe772feb.nq.gz
    ├── 411da63436991a58070ba84724f45cf654b9f06b.nq.gz
    ├── 41c0417f65cfab98fa60e2ceed862151ebe1cacc.nq.gz
    ├── 41d7657ac884719e10c8ab54dd07e803a3430f9f.nq.gz
    ├── 43b286d9ff566607a4652a51e771c7f89e356e94.nq.gz
    ├── 44189860031ea4378d4c5c1b8a0792438a611422.nq.gz
    ├── 44ceb195ffc9dac636b6e2b6c08ee9eb33e0c4f9.nq.gz
    ├── 453b1fac1cb555fb138ce5b99de96e40339eb38a.nq.gz
    ├── 45523b750b322494dc046b333f0b726290fd7909.nq.gz
    ├── 46c860852d4e610fbbab85e564c73af9313ef186.nq.gz
    ├── 4731a438a9655654438129654e4571f28776b437.nq.gz
    ├── 4764e88f709fef48a35fe99142c772d403d93355.nq.gz
    ├── 4854ed575438631342395740fe28e3d6ae4f0490.nq.gz
    ├── 49529c599abbf656406f806338a8f086efdaa30d.nq.gz
    ├── 498cc6b3fd7a1a6f2d1c2282a894821cb7327b05.nq.gz
    ├── 49c5a6a8aae8fa9ed6e07be4ff5c44dfa17d3be1.nq.gz
    ├── 4a419902bc42a7f4c9f42e217bc2385077500500.nq.gz
    ├── 4c2e9e7619365f689af780a1f8a9f9b4a68b4ffb.nq.gz
    ├── 4cd0e035a62d2208f7769b12b6458f16d0545378.nq.gz
    ├── 4d119fc7888026924dd9538dcfb426e9b55cb6c6.nq.gz
    ├── 4d20ce34319e7de55498c771a07ca28c47bcc550.nq.gz
    ├── 4e2f6e46cf01ca2b01b559c0fc90400b48dabc08.nq.gz
    ├── 4eafff65b1cc46ec6b1193c8fa306e4eec9b6335.nq.gz
    ├── 4eea18a67a487f411b110f7f083007088435a629.nq.gz
    ├── 505d113443c4302876ccdf28411929fcef55413c.nq.gz
    ├── 5103bbf43eefa45425f5419faa4bba345307641f.nq.gz
    ├── 5142a8557d3765fc719cfc37a5a6b13922c25bf3.nq.gz
    ├── 529705558f5cd5a9a26bdd9b4b4869523b0301d4.nq.gz
    ├── 52bedc870fdce44551a5f1a8b621abe5988eb45a.nq.gz
    ├── 52dbdef04674489bd9fab19bd451a0f564cabe1b.nq.gz
    ├── 53e89e81a56a9b1fb04218924f8e9151765c9ea7.nq.gz
    ├── 548378b2811d66baa49cf951f58fcf4d521e83e5.nq.gz
    ├── 550c30534de6f86d176364b38f4feb3e2decfa82.nq.gz
    ├── 55ec2d2a6e76b27f0b5f4b9c0c1dc8c360f5cea9.nq.gz
    ├── 56c48f3f8ca831d8fae458899cd18f9263b17b0b.nq.gz
    ├── 58938853d3fb8e62f62710d7978a237c213ceb3d.nq.gz
    ├── 58b4823547a395d6a679d002f64205de6bf6b405.nq.gz
    ├── 594f20a6ad39d1bcc1c4232888d998a51b4744b6.nq.gz
    ├── 59ce7a36e48cb1a403d13de9901d84b28a828e53.nq.gz
    ├── 5a0eb0c7139386c2ca12dec476528c839ad88252.nq.gz
    ├── 5b2af770412d0614c8f6b6b6d08c8c6b8338d9ec.nq.gz
    ├── 5bb789c307defdebd43c7c313b5258e5349d9bef.nq.gz
    ├── 5df3e2de50cf5e43e05b92bd990800af224bacb8.nq.gz
    ├── 6252dee0b550c3527802951968ae03d16d1f53f9.nq.gz
    ├── 62628b350096e9f9b50b51169bb5c01c3d9d0e92.nq.gz
    ├── 6280832e2e27d7ef4dece8bf77e1eb4e6d3dcaa4.nq.gz
    ├── 647f9e45ba50e0e7f27ca9dae13cfce03fbdd56c.nq.gz
    ├── 64aa398a0ba585e84f1d9bae8be6cf994d81f8c5.nq.gz
    ├── 670c640c67d4c70ac943790c7794898898e03d32.nq.gz
    ├── 67266b76ab27e526168f8f2e346398b70043c321.nq.gz
    ├── 673845970f2d6e43425057d88f67db5e82b1a787.nq.gz
    ├── 69a22579dc559dab938449e062129533ec1fd35d.nq.gz
    ├── 69cae66c7dad58c45847f1505aeb842df122e8b7.nq.gz
    ├── 6a868962cab831c5b3532f1f1d874e5d23937bc2.nq.gz
    ├── 6ab2af06ee6adbfa02a307a8ea1f9354c7c2acfd.nq.gz
    ├── 6ca6b3ba71d1d10bef3370b7f237b7a7d3025ba2.nq.gz
    ├── 6d176114161d43a390b262a30e2d7bd52f086129.nq.gz
    ├── 6e36ebaf8512844da259d2e1bfcdb38cd187f27c.nq.gz
    ├── 709ce3faced831cdcbc68403f4a11881ea392e50.nq.gz
    ├── 720093a23d002945bb9070720e9809846583727d.nq.gz
    ├── 73a1ac7829101d6408d7871a9b65b7cc38c03598.nq.gz
    ├── 740b9338fb68246e1396c2205ea7a6fb6fe9ce45.nq.gz
    ├── 769f4735c1d2f6d09c6a643d02ab61f867591fde.nq.gz
    ├── 7779a7ebedb398666ccb5a6e2e52b032d2e22c94.nq.gz
    ├── 78b530bc0758997ef0d57aed15c7b23d4c854705.nq.gz
    ├── 791d1ff232167466efe96092103ce3b50496b997.nq.gz
    ├── 7b8a9b7270b400c09a96d54f90da2dd7c8a97ec4.nq.gz
    ├── 7bba7ea2bc9bffcd0bef4cfbd3b8340578984e97.nq.gz
    ├── 7c60d5d439de3993cbc0b7ea830552839f9348bb.nq.gz
    ├── 7c86567d995dcf7c33ff42ff73a784b86da0e419.nq.gz
    ├── 7c88af29d3860c89f9554c78d7a17d483c9cfc5d.nq.gz
    ├── 7d1fcc2e26385a15c77e74df718a6ecd62fbfe86.nq.gz
    ├── 7d278e38abd14a958dc10da6accfc5a8fe0f1248.nq.gz
    ├── 7efe2a330bb297c25e2e574b3d9d4b7af5496b5f.nq.gz
    ├── 8050c25ed4266c892b35b4caf768e339fc31edf6.nq.gz
    ├── 81b5b1a83535b1ad95ba68eddb5e221b60b897d4.nq.gz
    ├── 83029b6f188fc137f1d4f4390f2a1b33d7756559.nq.gz
    ├── 8331bdc9d5ec8391e3a9f745c9042947b3df872b.nq.gz
    ├── 85084e0a8a02d8b5004e36c6a977c7070ef76825.nq.gz
    ├── 86b057e0f97fd90e782eeb7d3f06367dc63103c8.nq.gz
    ├── 86bbc3ef4f2d3b245c707d57c800e6312bc1d8a6.nq.gz
    ├── 872118c0225ff94a8b80e3abb6f5a271a7f940fe.nq.gz
    ├── 872d9f118e6af20914226d589820e32ebed6df29.nq.gz
    ├── 875342083f7f7587e85440dab1836cd9c485a797.nq.gz
    ├── 88ab438c38e27cf39e8d55832af0ae57351fb72a.nq.gz
    ├── 894585aa60d004a73b3a57c09ff7a264274fec48.nq.gz
    ├── 8a4499c037766fb1737730115b06d80f52e58f04.nq.gz
    ├── 8c2917e35944889bfe80d3a00abb727d3bb5c428.nq.gz
    ├── 8cb970d87d3c04247e929340cc6fd2d0d7ebe30e.nq.gz
    ├── 8ceeeed8b028f17cdc13246d07039c06f64759f8.nq.gz
    ├── 8d23d8f3ed6459b6249f0b55a4101ce0ce9a0edd.nq.gz
    ├── 8d334648dae2da0fb28fb0d003d4f01e8e774687.nq.gz
    ├── 8e13b5d75e4304082d61622b225b806e7e2640bf.nq.gz
    ├── 8e3212b974af85c9460d43708c3a65140e11ac13.nq.gz
    ├── 90dd912a9dfa9b56027b07e758384ef00c66d91b.nq.gz
    ├── 9270cce91b2fc98fddb4a8f62d8120db97d498f0.nq.gz
    ├── 9297894c5428cfdffe86965ba46ea20401a206ca.nq.gz
    ├── 93724f22065461d1bdc5a13213e6f265c84b6246.nq.gz
    ├── 937ba6f84b0dab28f9947b3c00c17aed21e06105.nq.gz
    ├── 938022e18eb60b67ae32cadf1373bcc4e9320a5c.nq.gz
    ├── 938ec18dbad98f4322cc972eb15f12cc135fae25.nq.gz
    ├── 93dc1e7cc9096372b84fcfef43980bef1abbd528.nq.gz
    ├── 9720b934173ec4c414aa4016b9f1997f4fc9ce16.nq.gz
    ├── 973ecfa6d9451829a4312ebd7d5566ee175230ae.nq.gz
    ├── 9762288f19b032f7d433260a62ba205937eee886.nq.gz
    ├── 97832f72fd884c79545aa311b39399a213c0438e.nq.gz
    ├── 99010958beb48fb59e8820f81f25b3868d171fab.nq.gz
    ├── 9aebfed3f8088dd0bf33c21bdd6af865ff3df344.nq.gz
    ├── 9cdf9b1cbbb7cfd2c1abdefd8328d7922819a0ae.nq.gz
    ├── 9dd5c97de4f7cbf34500fcd7fdf85b6264df6151.nq.gz
    ├── 9ee6a18d5f9da2aa66d39db02a41bafbca70e754.nq.gz
    ├── 9ff3bfc945da0e5fc8c35354d5b87a503e6d8716.nq.gz
    ├── 9ff72973738b37ff8c5c2e9f917340dd42c43a71.nq.gz
    ├── a026881828dfdc45628d565afd8ebb4809c4f261.nq.gz
    ├── a03c8338190e6f65d41bebdbf76418d37d06d98b.nq.gz
    ├── a1d870230da7ba68ced00e8ae7e7d08b45ac507b.nq.gz
    ├── a4c643b6642d4de24938d130dbbd5204e8addfd3.nq.gz
    ├── a552fd73032e0f15d09e7d0e859014d89056a15e.nq.gz
    ├── a65a9188e090ec77bebb0e53224a334ed5d1595f.nq.gz
    ├── a6dc088c2477ec41ecdd1f15b8ea36f861cbacdd.nq.gz
    ├── a76c507beb14d2d5acb2901bfb27ee2b63891a20.nq.gz
    ├── a895f3c1fd86095a4d8eefcf14bddeef0980ffa3.nq.gz
    ├── a970db42e37b64ed59287572da4c60e06023725c.nq.gz
    ├── a9cf1876631408e0521933ed55ee915e8ea8c295.nq.gz
    ├── a9f140834a61aa0d9d2adcede4ad752ba797d9af.nq.gz
    ├── aa5e04fcd7477e32b8ab972b6c0d097c1c77b158.nq.gz
    └── ada0e7eec2abde29ce2ad332bd402fc61286bb3b.nq.gz

7 directories, 200 files
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

[akka/alpakka-kafka](https://github.com/akka/alpakka-kafka)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
