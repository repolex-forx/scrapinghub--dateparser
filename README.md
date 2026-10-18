# Repolex Knowledge Graph of scrapinghub/dateparser

RDF knowledge graph data for [scrapinghub/dateparser](https://github.com/scrapinghub/dateparser), parsed by [repolex](https://repolex.ai).

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
rlex download scrapinghub/dateparser
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 07b40b2f01773d830321538ac9d2d6219edbe10e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 07b40b2f01773d830321538ac9d2d6219edbe10e
│           └── chunk-001.nq.gz
└── blob
    ├── 0109483fcccd96fb3f6aacf47b51504df2cfc1bf.nq.gz
    ├── 0168175d8d4aa45cd894559d1c8182c3d7855378.nq.gz
    ├── 017edb2187e11fe1b2c8ca475fe47df9434e69d5.nq.gz
    ├── 0200c7c820b026475b919f45bb53636ed8de25b3.nq.gz
    ├── 02712b9d7a534616e8bf4f0ab0ca67fccf42c8de.nq.gz
    ├── 02e7bac1b9d9e4a89922da3066a991994e9edeba.nq.gz
    ├── 036e88d6389837f43f5211edf4615cb331cc5788.nq.gz
    ├── 03981c4c35f06a5a22600d7d3fb33441385ca404.nq.gz
    ├── 048ebdf1caea45a6d63c356bd9306ff5a8e6704e.nq.gz
    ├── 0570f229a948cd07c3b434fd957d17eda83502da.nq.gz
    ├── 059676b19c1d38f88b9304c9c947ab8de3b9209e.nq.gz
    ├── 05fe9d802274d04374b9180469acb143891ec7da.nq.gz
    ├── 0686375f712bb490838ae66b9411b1558cd802ac.nq.gz
    ├── 06d9a0d9bfe3a1a2955ac7c991941e1ba132a026.nq.gz
    ├── 06f6eae56d3e366adb96fc39421a085be467d4c2.nq.gz
    ├── 0711ced38607544d31bafade9b0c8a93bcd79225.nq.gz
    ├── 075372e31e658a163edf3e78b1bb7780731d23b5.nq.gz
    ├── 0780bb89a0ead9253e8ff475e7cbf47e03f77553.nq.gz
    ├── 07e936e1e04becbeb008e0da6d24f84a1d451fab.nq.gz
    ├── 08e7da7eb0b9000f3839a6a1a33e790d6f93d030.nq.gz
    ├── 0a0b444f248ead0850a9442e7d87d456c2989548.nq.gz
    ├── 0a42aa5472115783f3f402068cda8fc8c1a66e80.nq.gz
    ├── 0ac4382b11afe13ee6336d501d12caedff4e99b5.nq.gz
    ├── 0b088074c98b2bb95958b6ac02cbae57eaf52061.nq.gz
    ├── 0bd3ce8857775921d8f88463ae5b88d30df92d12.nq.gz
    ├── 0c20320e5785dd75749b9c008b69a92414508984.nq.gz
    ├── 0cc577ad4f509375311c9ba6b3604871996f9e3d.nq.gz
    ├── 0cc83110b3db668fbf5ae943b9cfd00c31b3e963.nq.gz
    ├── 0cdd83ea6cbca380ce1177410e9ee7f5ebb3e1fe.nq.gz
    ├── 0d4a3f8ecbefc4404ccae51b33e1b2b685e368c9.nq.gz
    ├── 0d75f6002da710f0057cd5a1159ca5f1f049c511.nq.gz
    ├── 0d928e042b255c8d6aac57fad164be765d531063.nq.gz
    ├── 0de1da24c29dfb60b16b46a341c7ba80c974ab4f.nq.gz
    ├── 0e219da76156cd2e99139da5f12467301599a358.nq.gz
    ├── 0e24761428c589a9b43e713722c18ed85cda9ab0.nq.gz
    ├── 0e5e50c261ec7717833f03a62009dc9425541aad.nq.gz
    ├── 0e8775658b5589883a063f9ad601670dc611a881.nq.gz
    ├── 0f1c379edbbf98c9768dd6f4352357e251ab44e7.nq.gz
    ├── 0f5684f4505bc723f09ccc555b17442534291e46.nq.gz
    ├── 0f5b0c95a288895976263053f8ff9261617c89e2.nq.gz
    ├── 0f76d2ab427bdc547fc2d5dc59b6222424eeef6e.nq.gz
    ├── 1151f5581e8fe529d04745b379b28e6ee96b36be.nq.gz
    ├── 1261bedd91965f6bd9b380a0aebb6d365fcec483.nq.gz
    ├── 12f9d59d29b21375f70205aab8d4eae4158b1429.nq.gz
    ├── 13a5d2d91af66c851cce5df4934d8a34bdf32be2.nq.gz
    ├── 13d342bd444611e6d44ae18916a3d53661403656.nq.gz
    ├── 13dad6b68d0d0a30fbbbb16b89c2efce64bbf21f.nq.gz
    ├── 14609027012444b3b8f7a16095791a015d0b39aa.nq.gz
    ├── 146e63fd128413ec5d20754efef644f62ed1e6b6.nq.gz
    ├── 14e9e35d2e106f2064253ab6e529372302cd1865.nq.gz
    ├── 154253925037765c26193ba2301c84f572e2a88f.nq.gz
    ├── 162b39c3407877f485969d88414b34b12d669f3d.nq.gz
    ├── 166db09729adc4c9d135fe353b2196a42962cc2b.nq.gz
    ├── 1749baffdcc4d720e8496f7b4613a0e0c80753d6.nq.gz
    ├── 18853f7031e3082735787218da4e539c57e5b40d.nq.gz
    ├── 18bc30ababd335506733c144ff9445cc6e0ab2b8.nq.gz
    ├── 190f2fcec1f7adadd850e94536a9dbce481d29d3.nq.gz
    ├── 1967b29e3a8d1b88720d4832773ee4117860ef05.nq.gz
    ├── 19693202f8ca9e8224e1e6aea964bd97ad45850d.nq.gz
    ├── 199d014b4b429dbb4acb7fd4b71e4eef49dc4fed.nq.gz
    ├── 19c735ab03c60e63eabd4543bf6ff7612ae87c99.nq.gz
    ├── 1a36dc2b802ae8fdb410dc4b081229f8958eb722.nq.gz
    ├── 1a5a33d9409fce896f9fd9921159e2db4414d28b.nq.gz
    ├── 1b5d9b9a2f77468496de1df159d032a71cdaacb5.nq.gz
    ├── 1d671cb1040fe1f3b9316ef506011a37bb3893fc.nq.gz
    ├── 1e863593eb7d24cfdf0d31327860c68d7e6a9ef3.nq.gz
    ├── 1e947e76b47a079bcf891b3f0d9e6a2614b55f34.nq.gz
    ├── 1ec35ef54b2e639ca9941102d0c53d26c457f976.nq.gz
    ├── 1fbc67e4464ba208f63cd884b7a77d24b1166090.nq.gz
    ├── 20857e8923da878f13bd89720b5f682ecb8a2007.nq.gz
    ├── 214f782415db8b49371cb93be5f18d847751babd.nq.gz
    ├── 21f055e044fd9fcf4b06e7accbfb2b458c7d32f6.nq.gz
    ├── 222cef83d002d1f07ea6fa786328a1144858f979.nq.gz
    ├── 2448417b4bb28a199178f775d5df0a834c495e73.nq.gz
    ├── 249c31c6f35d582abe2e69c69575ed3c7666a82f.nq.gz
    ├── 24a7a5244d5d8768f424d48269383ee22314ab40.nq.gz
    ├── 24b76d278ae08057121019fc90b7c35a2a946af3.nq.gz
    ├── 250649964bbc36f4bec2942f69238aa6f7c02c1a.nq.gz
    ├── 252d94593a493de1473725cb1112d0eee9585ae3.nq.gz
    ├── 25b3b3940d44dc8139a167c61437c0d53b61fa91.nq.gz
    ├── 25df6ec5f1110d2878ad570532a76b041ddfc6ef.nq.gz
    ├── 26076d8fe8910110a3c154cd6126e769185de4a8.nq.gz
    ├── 2706fccd6b368cb18443b0b58c31dbb9e228144b.nq.gz
    ├── 279e71bab843174a2e7f21c10b3684925d678125.nq.gz
    ├── 285f97fc0f3dfd9d2c7622f1a6c6ae85c5542adf.nq.gz
    ├── 28a5480b0951f6b58feece4f82f6f5c2ab0f6765.nq.gz
    ├── 28b5f402ffe02db42e333baa8a15c9e49f0696ec.nq.gz
    ├── 28c9cbb1b7c883d86e28e2e8b5fcb80ebbdd7bf0.nq.gz
    ├── 2964812fa7b8d3017f2f15a8abc1a02f8c9900df.nq.gz
    ├── 297b4e716b2ff9ae2ad822d680f2767cc7df809f.nq.gz
    ├── 29c8c3e93cc731e1d86490c323772f848bda391d.nq.gz
    ├── 2a58d0d41ca43c9644ffbc520318259c113d7d13.nq.gz
    ├── 2b4b31f15a1ee0c98115491092d6dd03aaacf0ca.nq.gz
    ├── 2ba4b37ffb1210033c378a652797ab7af8a39e37.nq.gz
    ├── 2c36202c4fa9b25d86fc2a0e70f6de3e270cbaa0.nq.gz
    ├── 2caed4da1c0e5d4643f2828105b274789ee8d3ab.nq.gz
    ├── 2d2878fc0a4f4f7f978a679af4adb7b1e6a0a212.nq.gz
    ├── 2db342a5c2ec32009dbf1400f4083fb09368554d.nq.gz
    ├── 2e47c258f98ccac525fa3c389fc467977180060f.nq.gz
    ├── 2e4db64218e5ba73a093bba0e62c2c46bab3161b.nq.gz
    ├── 2ec82c64b74594d398c1582c0abf518410299fe8.nq.gz
    ├── 2f14a878d9975b45ee16df6fc29837cfd8262cef.nq.gz
    ├── 2f30883f6c82bc3879d368c2156d49db03abfb06.nq.gz
    ├── 2f4dfc4a216fd34919d2ae7f5bc572dd99632cd2.nq.gz
    ├── 30127d11d42ac614b089ccf50388a49751c5fb9e.nq.gz
    ├── 30a6bd1a379ab0a08b0a942e51e06d6a826c4449.nq.gz
    ├── 3162d529a85c1b5f7b2cad6f999882dccdf906ff.nq.gz
    ├── 31c4b8e48d6fab3f7eaa2eb9f35be4723a120344.nq.gz
    ├── 31ec227781d90ccbf89da88d3d1710c05d31d2b2.nq.gz
    ├── 320fcbb8f95a52ce1320ee69d736cd8bcb262af5.nq.gz
    ├── 32224356130fbc6311445fe11ee74b39e33ee0ba.nq.gz
    ├── 3259a790c5f62860e6eda5a9e7290774ef0729f9.nq.gz
    ├── 3386398fba8ff66884f75031eedb2cf6d0dc250a.nq.gz
    ├── 33de25c4ae77f42febb4761bb679dd6b381be279.nq.gz
    ├── 33e7f345d0b9dbec4b1632608d289f15f649b909.nq.gz
    ├── 34238284a610ec98a43973e763a9f50e3914d140.nq.gz
    ├── 347c280b8e085aa4f7a8f6a2f853bd617182c87e.nq.gz
    ├── 34c3228c889d70f8456a7a5ba1e0048c5d6c4819.nq.gz
    ├── 34de7131a0a9ae5c01561d4b39bd30624fd8310a.nq.gz
    ├── 350e4b9992a4aeff8a0ddf069fa99d3a39fdc3e1.nq.gz
    ├── 35402b266e520ec98d78e5dcbf1509ce01ef99e2.nq.gz
    ├── 358105e2db27db9ce17f30c1418af7f6bc9e29a6.nq.gz
    ├── 358d0974efd8a10dec368caa4bf839f0eed3fda7.nq.gz
    ├── 36d465c4e130ea7832a135e9024dca1d7ad278dd.nq.gz
    ├── 377aeef9741b58d0d510e76a38338caf5ef9ae1e.nq.gz
    ├── 396377dbce473a416358f30b5c8e6b616947e7d2.nq.gz
    ├── 3a4c9855b1b6df6d8e2eae155febe368250bccda.nq.gz
    ├── 3b5a3106011ef1972d283adfaa8f5255d517cff0.nq.gz
    ├── 3bef6b588d0f79caab18908ce49375baee6d26ae.nq.gz
    ├── 3d3159cc4b029e86fc77445ffc331d2ab421aeb1.nq.gz
    ├── 3d61d332128606d0b60d305691826909a0057507.nq.gz
    ├── 3e49ebcc2d96924973322ce29884f25ce9125580.nq.gz
    ├── 3f051df39b0dead23db8705d85c1f12a7c3e6b91.nq.gz
    ├── 3f9f4469c4f323ea63f76154827d5eee020c9189.nq.gz
    ├── 3ff3cb380607fc516fd0b5cf18803c438b9f4985.nq.gz
    ├── 4020e6d23efb098c5583518e63120d63eacc139f.nq.gz
    ├── 402c83d697cbf9e3c1c48bc3bbaa683416be8ef9.nq.gz
    ├── 40d7bc7bd62b85951b2be62fc661602b5c01e4fb.nq.gz
    ├── 40f4cb9a20d962ea727596bceed45210395ab462.nq.gz
    ├── 4187fc37acb816e24ae5a7ef24fafadca5cb1df2.nq.gz
    ├── 4242f07fa76615f15335199a7118a8af9a186ea8.nq.gz
    ├── 43f0301b14a2bec490084580ef6f59e4f0a00fa3.nq.gz
    ├── 44a4766e766392d6f062bf78fe46ed4473e1d903.nq.gz
    ├── 46321b6e164c0c8ef99d4fc7eaf8d0f3aca83396.nq.gz
    ├── 463c59f65bc540ce7208848e1ba20c2f30dec2fd.nq.gz
    ├── 464ca9d0b6fd1139cf9720d758b26c09998dbfc9.nq.gz
    ├── 465e829c66b913bf2357d39e4c79024782aa8387.nq.gz
    ├── 46c3c7668dec8f8bc2d8734091dc216cc7b9e2ac.nq.gz
    ├── 47490ed60a97b80c23921f184dfec522d1b5301b.nq.gz
    ├── 4753f02d95f9d1d070166fd97b8bd29918527ce6.nq.gz
    ├── 484977e9b4396c061fa1f52a773557068db193dc.nq.gz
    ├── 48a79201a813175a0941aa1938dca4919bdf7b67.nq.gz
    ├── 48eb125760880105308400273039071a35878df9.nq.gz
    ├── 48fca68dc13e1b2f2b00cf3a83736e859506c4cb.nq.gz
    ├── 4958ccbaa8c8e8a52f877d9b1cf1c683b64101d4.nq.gz
    ├── 4981f20bf751bd1d39f47888bb5748f4a5459c61.nq.gz
    ├── 49b8503cfca5498389985bc34190ac2226e0c948.nq.gz
    ├── 49c4879482f3f69b5c4eaab8f8e39d086504f186.nq.gz
    ├── 4acf16db6e14612dde2d23d0510a88fdd4b616e4.nq.gz
    ├── 4c664539d7d71e18cd19b8636af5ffdef50f1f04.nq.gz
    ├── 4c77e3e1cb386976067795885f6cf89b1f1c9074.nq.gz
    ├── 4ce6bcb5d3cff918770be5fa224ae2a34d01583e.nq.gz
    ├── 4f8a00e5bc154de0863695e80cabb501a1dd0ea3.nq.gz
    ├── 4fec9f64ef5a26adc7fd10d38c903af638584ff4.nq.gz
    ├── 501338c415c0681b91c1597fbc87046038642af8.nq.gz
    ├── 504ebb46243d0c164d44d89cfab2cfddf933e0d4.nq.gz
    ├── 50e14ee8928e37b7c041baf51e31adc624628be3.nq.gz
    ├── 5154d79b248e492067fc2104cdd6d3bbd11a8c97.nq.gz
    ├── 519408bdc47268a4aad72ceb0d1b70ea372a9ca5.nq.gz
    ├── 52cc3bbce259cc7fd16db1a173968b326669f5ff.nq.gz
    ├── 5351a1b2be82c2b49e1d18ba76efd37eaabf5b51.nq.gz
    ├── 54936ca514a133f881994a14fa5f4a3c035f86ec.nq.gz
    ├── 54a0defce99d075ad81b3c1a0e8c65fe87691945.nq.gz
    ├── 55ea8260a35acec173380d8c022f8d5e6f9d4c6e.nq.gz
    ├── 573fc3b7a7ae113aed2dde94ddccaea55090da69.nq.gz
    ├── 5762d8afbd2826679f45c5132e4a10a97d5e3dcd.nq.gz
    ├── 57b80e6c3173ba9f291f9e70cf56362baeb8e24d.nq.gz
    ├── 59395dc3492961627c1d0857a16da5d930705132.nq.gz
    ├── 59a971ceb0b6cd7cb04bc982c7b97a0d1baa2b91.nq.gz
    ├── 5a1daccc4ce85cd93df3cb3d7b35223a023b7576.nq.gz
    ├── 5b4fdcc86827efc6c662b6ebddc9b54f1876d5ea.nq.gz
    ├── 5c9bea17eea970d1a09237f93f90543f0e76f121.nq.gz
    ├── 5cd1835a694c1f93597be3d11ae931fe512729f2.nq.gz
    ├── 5dae996cc8869970963cb6ba62949e8701fa1cde.nq.gz
    ├── 5dbeb4b275503f2fdba3807fa86d13e44965da51.nq.gz
    ├── 5fad8d1a014bd081bfce563338c2ae155a3ba7e9.nq.gz
    ├── 604b29163f6332a7992c705ac55b6411f4da87cb.nq.gz
    ├── 60ae84c032a897c66975d4297d3bd77582e4dbd7.nq.gz
    ├── 60d94a1d8134db4093223bfc2ec7eb32ddacacf6.nq.gz
    ├── 614eb62c5f93c16b4550b7c7e6d9813d2da34f6b.nq.gz
    ├── 6164d1d16db33330a5fa37a2fb793a4303184c40.nq.gz
    ├── 617f649ab63dbcc55f3fbbc24755d477f7a98b19.nq.gz
    ├── 61b2c0a053d01053726c09e2de65252381d96873.nq.gz
    ├── 623d48cfa6b6f2ba551dde2435254ed5a1b63862.nq.gz
    ├── 624128e0477508f1c510354784e91617a547a375.nq.gz
    ├── 62a2cd01cb97ae9836d48e60bd23d315a17d4890.nq.gz
    ├── 62abaed2c6cc00de90ccf91b484b5ecc92abfdff.nq.gz
    └── 6320af78f8b91d232b5dd120328b72b7dddf04fb.nq.gz

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

[scrapinghub/dateparser](https://github.com/scrapinghub/dateparser)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
