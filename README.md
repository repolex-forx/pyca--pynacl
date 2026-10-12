# Repolex Knowledge Graph of pyca/pynacl

RDF knowledge graph data for [pyca/pynacl](https://github.com/pyca/pynacl), parsed by [repolex](https://repolex.ai).

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
rlex download pyca/pynacl
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d869c687681685c759f11142ec789b89fc62b56e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d869c687681685c759f11142ec789b89fc62b56e
│           └── chunk-001.nq.gz
└── blob
    ├── 010352bae1f498c9e2ab29e14111ebc002582c1b.nq.gz
    ├── 01cf5cdb24a74d38d33099431da3555cfbb211dd.nq.gz
    ├── 02292938c5650678bbde43228c389fb359ba9bdc.nq.gz
    ├── 0240f036c45496f74a62650d727cb57f5651b019.nq.gz
    ├── 02b0fd9a9f112f69f6e122aef00ba4ba126d7144.nq.gz
    ├── 02ff093c33c755cd36ae69a501bbebafe4f483b1.nq.gz
    ├── 03a80790002172bc21d6a3cf3ec9a56cacd65f93.nq.gz
    ├── 03b57d6318b6e0e2dff76d8713a80b0fc0638161.nq.gz
    ├── 046ab09a7a81061f109d48734cd864337cf8bcb2.nq.gz
    ├── 05957591ca75a36920e8a8d18f8c8f190a3ef473.nq.gz
    ├── 05cb099f4274cba2fd157d60fa0276d8bf7baeb9.nq.gz
    ├── 061061f14e87a05358c900f450107568feab517d.nq.gz
    ├── 068a9c6bbd3c7c840e13fd68dc62b73769ad35b3.nq.gz
    ├── 06a1ab0907f0a16522ffcc03c6dae0ebc33e5a58.nq.gz
    ├── 06af181b9d5465d1d879a372e0d14670829edfe9.nq.gz
    ├── 06e54036e8d826a3e31f4051e1d156cd5d2eb989.nq.gz
    ├── 06f9908a11d1286b2ea828664433fd89e9c23bc9.nq.gz
    ├── 07e3655731df4962d9d740605de35b3c3af3f541.nq.gz
    ├── 07eafcc55bb134dc6228585a8f532cc6877c5a21.nq.gz
    ├── 08a5b09613bc26a8e9ee15d77217c65d0f79c6a3.nq.gz
    ├── 08ca411c7f5912c0c608a7639b625095d63aac7e.nq.gz
    ├── 0924e9baff2f662f2643796959cd0a0662d5f300.nq.gz
    ├── 09f2473b42019bf35d031e09f4abe47eba74e334.nq.gz
    ├── 0a4994673793af92ebb13a49a0ebbd189681cdd3.nq.gz
    ├── 0ae1cf2f71ed2721b8e761db4efe1680a6d0ece8.nq.gz
    ├── 0c129e67ccc65b917c85009fb57e409f43c7189a.nq.gz
    ├── 0cf32ac3b45f2f1e0e27c84b4d183599e3b99376.nq.gz
    ├── 0d247c466f2abea59a66fff082f4288bd7daf250.nq.gz
    ├── 0d3d8e949d60012953ec782e9effe10dec732390.nq.gz
    ├── 0ed205dfb8c7e6c26e938674b984b9bc02084f42.nq.gz
    ├── 0f193a1af458415559c933feabfb88429f6b1c06.nq.gz
    ├── 0f3f73069541b013ae6fadf2db072ecce611dc62.nq.gz
    ├── 0f9c8acae95a1dc0a6d946834cf84a3d2b299fbb.nq.gz
    ├── 0fd368a9c50a3368e2ac82f91770998c99be9cad.nq.gz
    ├── 0fdac42d3539059f516fd7f52c4ce32012f104d2.nq.gz
    ├── 10702b8cf9325e042b7ccbaf80258752446a1e7d.nq.gz
    ├── 113ae84e9005b0a08975b68dad23502c500049d1.nq.gz
    ├── 12059b6e4fc0bad223c82d8d8187665f4f4886ef.nq.gz
    ├── 1224c0f132def9450f04545f54d405d7d88e4da3.nq.gz
    ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
    ├── 12a5d1890c326884cc9ad68c49d5969f157dd264.nq.gz
    ├── 12b86542c3b38e803daebf4d5141a995f50f184f.nq.gz
    ├── 149e5058ae1400d3e0b1e4f79e04bec613c4b50e.nq.gz
    ├── 14c2a74bcb1f280fc68fac1734772ffa21dc44ab.nq.gz
    ├── 14e412d2bcc851a5674973fa6a42e89bab9697ea.nq.gz
    ├── 14f5248b18c81e735da25e49c31a7c70076b43cb.nq.gz
    ├── 1565d37aba84a13f20a6e4b64b9c1b54081d2d0d.nq.gz
    ├── 16532a32697acbe644ee8f98274d561b7d4d4bb9.nq.gz
    ├── 174a389329feb67f0119fc728730b4c2c83e6881.nq.gz
    ├── 17b42843f96dcfe85391599de845c074a28ccdfc.nq.gz
    ├── 1814c6f3d649dc13d905b82d1cfc6c6804b21385.nq.gz
    ├── 18a98fb7ccbae805fa93084a50cbd13986cd0126.nq.gz
    ├── 1900f7a4b974b731ef792d93d23e4b56a9f091d8.nq.gz
    ├── 1930bc35f30b1aa35773a6ed1dc5a55e48e4d2c8.nq.gz
    ├── 1949d381130555ef93d287428f2b973bc2cf48a3.nq.gz
    ├── 1ac33732219d7ee42e56d3290893400f7166193f.nq.gz
    ├── 1acd12169f358df9094cc85bd4cb251829c17072.nq.gz
    ├── 1bc0cf984dee02f3c2a2d7584854b5de07381154.nq.gz
    ├── 1c4285f5f24f1bf7d10a8fb6ef9d4cfd605b5a42.nq.gz
    ├── 1c6131ff7033520e0c585bc81e7bd62432a4d160.nq.gz
    ├── 1c6858537833282d555da4143be8553c72748970.nq.gz
    ├── 1d1220fee237f94a0a4f49b93af1ddf3ef7a625d.nq.gz
    ├── 1d3709db128f81048933d84030874f2401344477.nq.gz
    ├── 1dc1340028ada114ae84ba74cf8082327bd251ab.nq.gz
    ├── 1de77a05c7beddbf273731de2d4410144848fbb7.nq.gz
    ├── 1e178a478bff7788a643991ee5c7e3cde2b456f5.nq.gz
    ├── 1e6f72a620e52688bd4eebd1945f8d7cd5fd0a73.nq.gz
    ├── 1fceb26d435ca7a28a257785b3da88faa99b6495.nq.gz
    ├── 2071b33f62e5b2780c2fe2040f32ef155ad84667.nq.gz
    ├── 20902807470047def31e659047f9c5142df9fed1.nq.gz
    ├── 20e6806f90f0cda79511f90250bbf942dc193ade.nq.gz
    ├── 214ef5f8ee7c509260d6b08a45e57ad2886ca7b1.nq.gz
    ├── 228aca7b6bb2dde59ebe83d8ba5ff888bba8dfa5.nq.gz
    ├── 228df3f39bf9c93c809285500486def24c2febac.nq.gz
    ├── 229972f29247e15494c79a12deea84f9950c78df.nq.gz
    ├── 23054b754428ee96f9879010ae92c8a5506a4295.nq.gz
    ├── 23ac927713aac1d327811346a9c6f9adae5680d3.nq.gz
    ├── 24417577676fd6324aa0b6b8fc26bec5edaff02a.nq.gz
    ├── 24b3072aa1113a38c4de818dbe44a37ae68c0bb7.nq.gz
    ├── 25a541dd20ed7a4be264e35b5f44a5ea7927e5b3.nq.gz
    ├── 25caa890298a4e53619ff628fd7cd64d772a2afc.nq.gz
    ├── 25db669b76eb4ccfae0d829ad9f02c3f2c3ba482.nq.gz
    ├── 2679d0a09233341122b9474dd31476c90226aad4.nq.gz
    ├── 26a3d31efa93bc34fa62526e53f42a88696d792e.nq.gz
    ├── 26bd18ace1a4c6e5e33ca86dc901b2e86f725ae1.nq.gz
    ├── 2745d3ede5fbde7685549e060121a1af7799fbd3.nq.gz
    ├── 2754a91c92ecca9ae9601a09a30461e1504dc8f4.nq.gz
    ├── 27cc007e576c098344a1f17fc99bfb223d47d0bb.nq.gz
    ├── 2922942dd2620d705693f96dd05a5bf03345cfd4.nq.gz
    ├── 29292c1ca947b1446fbbbff0e816558a5945ab43.nq.gz
    ├── 2946ba873bd811cf5ad0131439b3fa275fc5f42e.nq.gz
    ├── 29e7b1cb88307aee7733ee9ed13ce05ecd069f9c.nq.gz
    ├── 29f45a8544eb308510399e775108cfd4b869a573.nq.gz
    ├── 2a594e2939f8519b9e0e212fd3ba6faeec16da9c.nq.gz
    ├── 2a690c9ac8c2091c52536f611e3d63832064f80c.nq.gz
    ├── 2a8fddbd1ff976617da0bd3b8f8d645ec5c88ed5.nq.gz
    ├── 2b250d57959d910467373ab15ddd1024d352db9a.nq.gz
    ├── 2b2b7d6edc11a2fef58bd731663058fe4cb7855e.nq.gz
    ├── 2bc527d0a1e8874f05f060d2ce176ee83376b2c9.nq.gz
    ├── 2c94e483710018ee33f9a68104566371b1ecf2aa.nq.gz
    ├── 2cfec49bd7335ae451cf31a9664a133d0e8b835e.nq.gz
    ├── 2d2e0302ad6e6c4c802641e937dbfd6e7d874d13.nq.gz
    ├── 2d487dbb6fa401659cc33a4ef40d230d7f9e6dfa.nq.gz
    ├── 2da877d21b9a8717895a8dd887388c798a1bacc4.nq.gz
    ├── 2dc6e2f668043265950766fceea7a6ad81186f9c.nq.gz
    ├── 2e6a20f98ba4c394c6979d5632b64a85fbf37dc3.nq.gz
    ├── 2f5600a0683ea5e8ae1edee8cbca13d0059a3aef.nq.gz
    ├── 2fae2744c020231f59635e9a254def904247fa3d.nq.gz
    ├── 2fbecde8d3c7f249ad9f88f13972528d5037e896.nq.gz
    ├── 30484db823be1efc08d4b9459e34258b7a8b6f2e.nq.gz
    ├── 30a2882b11aac1ddbbac407a32e4750b963116c3.nq.gz
    ├── 3152e286a1e5b0a8ec1af8b7918f6b8c55af674c.nq.gz
    ├── 316c5e94a3b9ef91c20c5589f8f1be488763b922.nq.gz
    ├── 31745fc139d21010a214729b1b7f904df4a5e469.nq.gz
    ├── 322b6742b2697f7bf7ee8450764f689c7414f05a.nq.gz
    ├── 33484825f0d411b27ef00c0abdba561dfcdf2ce4.nq.gz
    ├── 347132c320e0d22e9725b6b9dd4633dc73fabefe.nq.gz
    ├── 354906458aeca5b18f9aa124bcb21077298b1c58.nq.gz
    ├── 357b26f4d5578830210c68b4909964bf4c703274.nq.gz
    ├── 35bacf30a30ccfbf85ba51420aeb9f05672d30ce.nq.gz
    ├── 3611f6ca65eb92fd50c6d751e66ea4b016a93023.nq.gz
    ├── 3691a4947267b9e740f09ae16e40ac6d485cf521.nq.gz
    ├── 3697e3ac5e638bec3faed0f3d8046c3545023cef.nq.gz
    ├── 36a6de87d43db6b438c9dcd4af69c3f7d7fb30e5.nq.gz
    ├── 37e114f84fd22f85a538a6408d2158bc3e6acf43.nq.gz
    ├── 38024d17ad4eff8868c34d93e88a2f2f4ee30abc.nq.gz
    ├── 3835777cf453eff38255ef136da360c8f34366b3.nq.gz
    ├── 389943d2118ef401eeac6b6008bec356e67387f5.nq.gz
    ├── 394c3914107c1217bd2a6ff6d8ac72c71f85cef4.nq.gz
    ├── 3a2414c69d21eee18b247d9479ea89e3610b2a2c.nq.gz
    ├── 3cffae866235471d01dae609647504e93af09244.nq.gz
    ├── 3d35cde174de9cd9788e4bff9b5391c1b06a2fbe.nq.gz
    ├── 3d6d77552195ee22a80a9b0ab136a15572b90d8d.nq.gz
    ├── 3da864c7d27051531391281e7ad460839354c1c5.nq.gz
    ├── 3e46fda85e20b4687bfa3b55e76bc8ad40cfb7cb.nq.gz
    ├── 3f4c45caf0eb7c4177ca9575b563d198f2bae1e4.nq.gz
    ├── 3f9a38b51006ff583fb156329ef4466f4c92aec3.nq.gz
    ├── 40a45ccef02fad07a67374341ff55e9ae963c1a5.nq.gz
    ├── 40f782f418c5ade3f0d20c3320dc40e3b9f5f0b3.nq.gz
    ├── 422818143f62421257c8de41d3e5b54533bbdc60.nq.gz
    ├── 4267174c24f7c56bfd0eb90e62e6e99a779e118d.nq.gz
    ├── 427c3fb08992fd8510d0220962b61c0af53ca7d3.nq.gz
    ├── 43170b5d775a64129c1abeb5b6cae9c031a6440b.nq.gz
    ├── 43296cb063ede8ab2ef52b28e4a9dde0ba568aef.nq.gz
    ├── 432970090820791e5e605938542bbd532b800df0.nq.gz
    ├── 432d6dbee5693605298907fe4973030f24345458.nq.gz
    ├── 433a9a26dc6157e94255faa9e12807254dff4661.nq.gz
    ├── 43e189ed0ebdf120f31d60898a565185cfce4eba.nq.gz
    ├── 4428c97f326f9f6edc51d3073eef87bfa6ae1aad.nq.gz
    ├── 45298501364bec029e75d2a1144bd81f77c474cf.nq.gz
    ├── 45eb98d7970379b60915d09f5b2f9179fb7e08c7.nq.gz
    ├── 45f678ecdf8f19913d7ad1a0bded083ee7210d1b.nq.gz
    ├── 4652f0db526dbadacb91e7ec8bfe0c522387a791.nq.gz
    ├── 474f486002d8c616faa9ebf54ac205eec0f1b9b4.nq.gz
    ├── 489c7c20fc803cf6a39ff08204ab92027c3acb67.nq.gz
    ├── 48a684601bd23221a41c43c16890dd3034c5b7cc.nq.gz
    ├── 48bc9344a4d661e116be1483d5520753875b2bd1.nq.gz
    ├── 492876cface62b89166050e72141c110b0a346b3.nq.gz
    ├── 4a17f13424f807e65cd0b08f05daa7e582d8329c.nq.gz
    ├── 4aa769462a94f8e85b0760e370d9439be8fa6143.nq.gz
    ├── 4ab295d7a3fb0e7e1fbbb915c5d2a181c3022bae.nq.gz
    ├── 4b46264a6acbdeb6b80040d7f7c411d34581d76c.nq.gz
    ├── 4bcdb33e3f8560f69555e475d359a816f92bd6a6.nq.gz
    ├── 4c1d62ed430e5b501faab5c5151b0201fe04af0d.nq.gz
    ├── 4d10017f0e93029292568b836e21390e20ab77f6.nq.gz
    ├── 4d27f335f3a2b6c737a2f7062700b111503c24a1.nq.gz
    ├── 4d69f11776e729e938adcc2ddbcb163177b9267a.nq.gz
    ├── 4da52447b5ccd7769d33ea62d14924ae6df59ced.nq.gz
    ├── 4e756591ec8712536b342172b20097d87654770b.nq.gz
    ├── 5134b67c6f6c79089ac4059ec404fed6b27976b8.nq.gz
    ├── 51ac26ab9033a45a3edd8d0ec5cccc372e523de0.nq.gz
    ├── 51deccd9b31606c8dd9e71bebd61a4d1a9a15135.nq.gz
    ├── 53833d6493e6ca99025d5950e2a644187b0c2855.nq.gz
    ├── 54ceeed9f1856149517be07cafeeadfca064c3b3.nq.gz
    ├── 54f64c2684134503a2dd492c1eb35520abd2ef0d.nq.gz
    ├── 562cf717e9f89c54c8240e749ed6f74a1a3d6b83.nq.gz
    ├── 5657b65a788b0781b41c686f9c9729b6c3fbef03.nq.gz
    ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
    ├── 573541ac9702dd3969c9bc859d2b91ec1f7e6e56.nq.gz
    ├── 57bd5713c354778bdf7dda206d1df67077c1708b.nq.gz
    ├── 583a2d44827ebf560e209e5cf1c84a0755f2921c.nq.gz
    ├── 585804fb1ce338b6b665c8c11ca0d4e8d75aaf45.nq.gz
    ├── 58de56cf85a7cec5834120733803a5947efebdbb.nq.gz
    ├── 5976c455dd4da7e8e0b2bcdb2aec62ff5faa32b4.nq.gz
    ├── 597b2c6d0e56b1b9b4868bd876778200105655d9.nq.gz
    ├── 59895bc24492a7e91b1c900595ba2d62da5cdcfa.nq.gz
    ├── 5a23903c4aabb5745a43330b282c50b93299106d.nq.gz
    ├── 5aaf832183fd361056158e0f3e0e9e39c935afd3.nq.gz
    ├── 5afe963f9a353973461cc0cfc9cddea9b8c7dadd.nq.gz
    ├── 5b255e5e0ebefc4d12e8a47cb043099ce1f5ebbb.nq.gz
    ├── 5c2e5de8116f4519da0f62008dcbbbda21d6e08b.nq.gz
    ├── 5c7956632b20250a7a3e344e5fed45184d6c8ba8.nq.gz
    ├── 5d671df142da5d16ecc35dc74ad25ebc7d8cc885.nq.gz
    ├── 5db821d2e2f3e36719fc4f7a5d4da77d4c6bbc92.nq.gz
    ├── 5e450bab3cdf4808973786e8f51d0a820b5afafe.nq.gz
    ├── 5e6c2f9dd230077236f9bd784b713b4772b20d01.nq.gz
    ├── 5e7c35209295237260ac6832572d8017982a4a63.nq.gz
    └── 5ee6f605257b303e82e0c247c5db45a8febd1fb6.nq.gz

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

[pyca/pynacl](https://github.com/pyca/pynacl)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
