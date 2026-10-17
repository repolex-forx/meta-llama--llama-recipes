# Repolex Knowledge Graph of meta-llama/llama-recipes

RDF knowledge graph data for [meta-llama/llama-recipes](https://github.com/meta-llama/llama-recipes), parsed by [repolex](https://repolex.ai).

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
rlex download meta-llama/llama-recipes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2f22a9eb030f92d0e99227e57e9a1123af1f9532
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2f22a9eb030f92d0e99227e57e9a1123af1f9532
│           └── chunk-001.nq.gz
└── blob
    ├── 000106f6071fe7e5fb10f97b722592cfa774dff5.nq.gz
    ├── 000fa0ffb8b0779a1d967c5ce777a0706006ac59.nq.gz
    ├── 00a0dcb730249218f52875e79981c3313e473bfa.nq.gz
    ├── 0132fb9b0d9195d20dc2bb1b32fc680162e6f9bc.nq.gz
    ├── 021a1c00af9ab5d56bc636843a150607f04f7499.nq.gz
    ├── 0258719cf64b15080c26ba08cd1db261fc4b9089.nq.gz
    ├── 026eb4c2b31a15e5e55cbad939def310e459f231.nq.gz
    ├── 026efa11384f6d3240a7a593575efb6f54a7d94e.nq.gz
    ├── 0297d53c9434ae639c47306fd604cbd3874f1bf3.nq.gz
    ├── 02fadcc5aa39d364f93b2493e02dbe52fdb1ef67.nq.gz
    ├── 0323a1c9d37d5559e9dbbd3159bc759a54b996f4.nq.gz
    ├── 03b2674a7595bb8bee4f1a784086597a03a29a02.nq.gz
    ├── 04f6c7fd6d11e3fcc3fe2ee1f9ee1ffcfa28fcfe.nq.gz
    ├── 05d5babc9204d5453986f7ec438c55545ddc4083.nq.gz
    ├── 0600ed5e4551c2c3d58ebf9ed4ce2a5925b3fb4c.nq.gz
    ├── 069727f3eb4e74e936980158c7d3a4aa74a8129b.nq.gz
    ├── 06ac0eca7ea8ebefcbc8a88f970d7abde67bafa0.nq.gz
    ├── 079cc8aec3db2fa3beed7eb6f47f439fca515b22.nq.gz
    ├── 07b18e5f187d8c1171f5eab9d484d802a003e566.nq.gz
    ├── 07d5da9cbf141911847041df5d7b87f0dd5ef9d4.nq.gz
    ├── 086162b9582af57c2c01849af7c904395ce83364.nq.gz
    ├── 0868ffffa6ffa2c33b0f79d089758884922ff370.nq.gz
    ├── 08b500a221857ec3f451338e80b4a9ab1173a1af.nq.gz
    ├── 097e56d6a9b7bb36cd1bb35e66f4a69eade6001e.nq.gz
    ├── 0a4f32622ad45f8ecb3392d1c407fa2650c2910e.nq.gz
    ├── 0a7a71f07007f42c12b3d34fff48eb38c8da9282.nq.gz
    ├── 0aa2d059bc2da8562dc191e74630e9a5fc26e2d0.nq.gz
    ├── 0ad8a956e0ddfed402b2a1785978c5c99f77cf73.nq.gz
    ├── 0aeedf8463a12d6a1a6592c3859eabd2eb55614e.nq.gz
    ├── 0c4f95cab912665e8bfd0f0856471908c4d10d5b.nq.gz
    ├── 0c98dec1a4603c771ffe4ad6a2f61767060ef497.nq.gz
    ├── 0fa4b65f410e9a3b7de9788a7a150773f20bdb9a.nq.gz
    ├── 0fedc8ed498400ffd9670b1a41cb5178dcce7628.nq.gz
    ├── 0fedfffeaa37b06c2d045223b3131d21c43504a8.nq.gz
    ├── 1017bae34c29b3660a75dc9f1522bca764f4c51a.nq.gz
    ├── 10721113ac42c1bc34966262b40ee01fa010ec41.nq.gz
    ├── 10ad93068fcf650ce5996d6d7135c06ed60cdb8e.nq.gz
    ├── 1166db156d720d0a54ae9831cd4d62849473be86.nq.gz
    ├── 1198a2d884f12fdb80da1c54bd363f923ccb4f8b.nq.gz
    ├── 11be4786204dc2de57d2bfc660052311c0de8ab7.nq.gz
    ├── 11df4759a203e7fd0342c868e23f4e01a180f039.nq.gz
    ├── 124c49778090bd5718cf0b3c43d1cb7f33185f33.nq.gz
    ├── 129760580b929b85b02e6390734639630a0b530b.nq.gz
    ├── 13b8755558827d58f6401946cd8f80ec892e7df3.nq.gz
    ├── 14b96a9a1fe46251462ca74768baa65f6f9d402e.nq.gz
    ├── 14f215468805b92e224e06ed0c44572bec9e9af1.nq.gz
    ├── 164c521c18ee9cedab23a52841b9a348e02d33c0.nq.gz
    ├── 16633e2d417901fe6c72497582777dad3dd9541a.nq.gz
    ├── 1702a3fab6d6a162ae45ebe7b577eb83721a6390.nq.gz
    ├── 180e1514c7f2281907bdc49d4ed8adba2fd09eb2.nq.gz
    ├── 19a2d94e77acbed69486738b72fae9d6ec45509d.nq.gz
    ├── 1a3d07f981e7f22261aa1ee815d40f7f283409e0.nq.gz
    ├── 1a7ca795f426679ecbe67f19c46117e9cf3deda9.nq.gz
    ├── 1b21dd1abed1370cebfaa92469cc41ffbff26966.nq.gz
    ├── 1b87f9857a28bd15f486cf041dc0d835f8960932.nq.gz
    ├── 1e2b3d53d0103f9c860cbb438c2f0913c0f45e28.nq.gz
    ├── 1e2b775a185644c6d6b7adeb1b0ac687b09c28f3.nq.gz
    ├── 1e31b447f6fab6d463c0cbf795bdf3871c5de886.nq.gz
    ├── 1e4b9424dfc9bd3374c6d34a404a9e4909f83d4c.nq.gz
    ├── 1ec3c107d8a4ec487792f21cd858708427798ea7.nq.gz
    ├── 1eed438870632d9aacbf1111fc2f9f9bb66a21e4.nq.gz
    ├── 1ef932b49fe421137f4c969c310cd3f700a43960.nq.gz
    ├── 1fd66af9be4563dd3093cef5ef8c564a8015cef6.nq.gz
    ├── 211f0a8814a2b168aa9d8f232123e25b84609604.nq.gz
    ├── 213c8a47fac324e09b3f9da139d8184a3bafe233.nq.gz
    ├── 23cc54abf2b91cf7fde9d0268ecf01db5997bb28.nq.gz
    ├── 25a4029a1196d30d6c4309624cdced2bc8f3efd0.nq.gz
    ├── 25cbdc4cea146c0999cdcb7f7a7e3eba4bfb3a21.nq.gz
    ├── 25d16aa76a759d19c6730e95fc5ac4e33e7e4d90.nq.gz
    ├── 2637a3cbd3dc5ec5a59b721166c8b27f01883d34.nq.gz
    ├── 278fcfe54134c763ae6a8a9b6c6ef37cf5f71c72.nq.gz
    ├── 2793199db6173abc5446ea02024bf6fb70736ef6.nq.gz
    ├── 27ee07b34ff1e1fa08ea68032b70860d669bba35.nq.gz
    ├── 28d4b77f9f036a47549d47db79c16788749dca10.nq.gz
    ├── 29924e0f7ecb24ea4daa7d4d7c575199dda74b8b.nq.gz
    ├── 2ae27b8409e02025788f98f0ead68e6103e6fecb.nq.gz
    ├── 2ae40c7a3263f79841e4f53c767cc419adfceaf3.nq.gz
    ├── 2b3cbb0659737d353ecc7df0b1b7487ad8daf6a6.nq.gz
    ├── 2b55f529d16c1af2d9a11c77b66c1ad020df8279.nq.gz
    ├── 2b787a30d1604e64a02642dbbd8c6245f499158b.nq.gz
    ├── 2ca160600211e50d63a80bdd089dccf0640151f9.nq.gz
    ├── 2ca8931a46106048fc5684cadb7f0d247211553c.nq.gz
    ├── 2cbd6d19d3371dc85f6925e34a75c5c73bc3b187.nq.gz
    ├── 2cf5d38d31b2a7c35b9786df775d810bb2480237.nq.gz
    ├── 2d292f6cd3a8d18b7d9c51a6d74379ccfd464181.nq.gz
    ├── 2de1f642089df197468990da8e4bbcfce855f905.nq.gz
    ├── 2de8e9b49ad3be81a45ee947462599d5479b695f.nq.gz
    ├── 2e2c426b4257e32677844b3b5af80d5a541b518f.nq.gz
    ├── 2eb6a33732026c0fccda3e05c40f6f99a13dc36d.nq.gz
    ├── 2f42d6310df37f1416aee4c7351c032fd505b38b.nq.gz
    ├── 2f5f706b14c8a51805b0a74f741a7fd1625207f8.nq.gz
    ├── 2f69da56dfa67d47417ba918e0d03d706493eccf.nq.gz
    ├── 300632f112f564ad6252a56b18b6887d8d3b588f.nq.gz
    ├── 30c80fddfe5c12689c0965736e6700eacb4bc021.nq.gz
    ├── 30d7aaa9f278c4ae8d5c7bea7d1abdb4dbbf22cc.nq.gz
    ├── 312a4c8911f6f5c4c79c6fcf1f2641f6794b6d54.nq.gz
    ├── 31c49ffb5a7e9d817d60116509c9f57256f6d8b2.nq.gz
    ├── 31eaae2551f87caba066b02c307f6b545e79ca5d.nq.gz
    ├── 32fa3edcbed9df03e81adeab7896c66a02aa4f50.nq.gz
    ├── 337c822f677382315173dc1bf2730d6d2c13968b.nq.gz
    ├── 339f1da6e879d36c4547394bc495df0944316ddc.nq.gz
    ├── 340dcafcb4b85c3a107b31dbd47d413fde160303.nq.gz
    ├── 342949e92c86f7a1e3b4c3bdae744e47a551f83a.nq.gz
    ├── 3493cf180851fe47187853feeff3f7ee6c702f26.nq.gz
    ├── 3494a9ad943cbe274a7ca2de9436337c9305c929.nq.gz
    ├── 3530c60d4aaaec3f9505e39c1cbc5b0bbb93b6ce.nq.gz
    ├── 356e4a4b9aa2f09bcdbef09b6ed57318bf8012db.nq.gz
    ├── 35767434b49288a8c5a3ae948b2380325e81ced4.nq.gz
    ├── 35c778a437d726605244c29bc7e42cec997486de.nq.gz
    ├── 35dce29fcb8f03b0c8e275777aad513c299e45da.nq.gz
    ├── 35f7e5a0374b63fa292ce6215993f16f759de3df.nq.gz
    ├── 362540adb68db1e2c2cfdab34434d8bfb2d14a51.nq.gz
    ├── 3724164d6a9fdaf93d29a81cafa59585825d9cba.nq.gz
    ├── 387804aa1cc8a29a5467cc3a3d08e4d4609b4878.nq.gz
    ├── 393d2ae1f5d97fc7df2a36487215707db2211a9b.nq.gz
    ├── 39c7e75cdb5a36d66e155b89b2fdca66e8b331fd.nq.gz
    ├── 39ea05f5daa54ddbc76df4e18c55bfe29a3f218c.nq.gz
    ├── 3a3170571efb53081ad4c31e883c4640319a36e0.nq.gz
    ├── 3a46c796fa0fcb27a4ab289935bb97c94d097c87.nq.gz
    ├── 3a7561813f2e9f48e91506c53d439cf4f1aa9d37.nq.gz
    ├── 3b595ccfae6ac8dcc79ee3d139d2d9b821626c01.nq.gz
    ├── 3d24dae56469e086554e41b794fbc66e809f6804.nq.gz
    ├── 3d9ea01d9401b558360eb42f942b133bac5f5c0a.nq.gz
    ├── 3f11cd949ed41733c45b7d471093b17847aa907d.nq.gz
    ├── 3f6f0d6cd7f3cedc7420cc825d94609f154be371.nq.gz
    ├── 3f80f58db6a1ccfb7e671082f111ed5c624ccb5e.nq.gz
    ├── 3fe050ba05602c810c7e9545c16d2c71d4a3d0e9.nq.gz
    ├── 4035e37c6e7f99693ff86c0216d5e4b9c7d8013e.nq.gz
    ├── 404ebf53658d0e98a81a16db4e7b19fecf8beaa5.nq.gz
    ├── 4061392de4b3305c5d08ee9037a0d7d34756db6f.nq.gz
    ├── 406de742db9b1457ed645591b4bd9a8a097250ed.nq.gz
    ├── 41ab54f3b60912efe51590e616c25fcb542b8a80.nq.gz
    ├── 41dbc02701a0100ae066509dd96d1113699892bf.nq.gz
    ├── 425d40e77eeb9772c5ac9a081bae80718c68dcb1.nq.gz
    ├── 42bbf6ec0e0b51b29f25b89505d7aac398d8206f.nq.gz
    ├── 43b5972f18538bf9546d401f0f69c2f5f572d835.nq.gz
    ├── 440f7ab52dbf72cb31aed04db0678dab865117fd.nq.gz
    ├── 4470d2047abd0156e88a79ec50cafe0236c96e7a.nq.gz
    ├── 44ad0ef0ae3a6a791ac59fa476a817cc58ff3f56.nq.gz
    ├── 45474cea33c4154add769e62deace805696a8752.nq.gz
    ├── 45bb60420f55d42aad65641b5a9643424e129860.nq.gz
    ├── 4680bc6629e050e3b025314dbe35ffb306043953.nq.gz
    ├── 48b63b32842e2d933aa54b73ff605775cfe67598.nq.gz
    ├── 48c1d84400d9b629eab5cf530d94c2a7ed0ef9c0.nq.gz
    ├── 4909e8804bd45db7d2571b7fcc4808143c1db050.nq.gz
    ├── 49454ca0c945d4a9787d75c5f72c3e50ea8913e0.nq.gz
    ├── 49862dc262e7b9d801883566bb2aa5be17bb87bf.nq.gz
    ├── 49a42e58b0eec271e4aa2d6b1562671d174d90b7.nq.gz
    ├── 49c563fd8f24fbbcee21be07dfa6ff3f88825fad.nq.gz
    ├── 49ec6d8172e2817076717f278f0b006e27269c5a.nq.gz
    ├── 4af7b0328c92ce2fa173032e002ec6ffbe3cd4c1.nq.gz
    ├── 4ca75c9eda2a7f02f283dad3bfd5f444386f2b2c.nq.gz
    ├── 4cb1c44ba6b90d9eaffd77ba32453c13fcd2852a.nq.gz
    ├── 4d29575de80483b005c29bfcac5061cd2f45313e.nq.gz
    ├── 4d3f1f44c26351f283148c13d440cef239327702.nq.gz
    ├── 4d66912c4a142cd965684da4722b69a9af340dd0.nq.gz
    ├── 4e01111e90af81b0c8c8f30e0608ee7861c0a159.nq.gz
    ├── 4e38e07a2e5b979c2b1c3db1bd8fda03151ea718.nq.gz
    ├── 4ea6cd9ce584eca754be572649bb3a46997c33fa.nq.gz
    ├── 4eea2074998d59900d431210a97d4a42d33a1497.nq.gz
    ├── 4f0f1d64e58ba64d180ce43ee13bf9a17835fbca.nq.gz
    ├── 4f906e0c811fc9e230eb44819f509cd0627f2600.nq.gz
    ├── 4fb30bfe0fa8cbda7354549e14e138cbc5674a7f.nq.gz
    ├── 5136c4afe74918b12c1dc101caf3ed1497c358a5.nq.gz
    ├── 518b5d32ccd4a0fd297e34834ee5a12739c559d6.nq.gz
    ├── 5253d3ad9e6be6690549cb255f5952337b02401d.nq.gz
    ├── 52945497bac2684e93f64cf0c2d48e5331ef445b.nq.gz
    ├── 53fa5739b095046ddf30ce3cdfa66a11c3fc56d6.nq.gz
    ├── 54ed04d3b2c219160e383d50c2fe407c9d417426.nq.gz
    ├── 55bb233d6a7cdf6b6e419b8dca36771f414c2690.nq.gz
    ├── 568efa2815ba8425c77931a833b3182bc3e5554d.nq.gz
    ├── 56b8e792e2219e557cd8ae8530803e5af94933ad.nq.gz
    ├── 57d836d62fd82761bc1fae4a845afe10c5a9cb32.nq.gz
    ├── 57da20f546da5d149ec7b59b341f11cee1642449.nq.gz
    ├── 596a64ad28d847b48ea808e1e98c749c72973c47.nq.gz
    ├── 599940bdf333117b6357c051e14c994a5bb2d178.nq.gz
    ├── 59a3cdf48e98a197ccf749e68f0bcacfdea8c4d0.nq.gz
    ├── 5a5074c6974b3abc98127f1b18a6d853da71c1dd.nq.gz
    ├── 5c335d7e07fae854ba48bd499affad7a52e9e6ca.nq.gz
    ├── 5c8239a1896794f74243345785714cb3a3a3d816.nq.gz
    ├── 5d2c135bed12c14fc7147fc3f6840e367a0778e1.nq.gz
    ├── 5d41f492944b4d6c58a3aefa2cd1824430d8f129.nq.gz
    ├── 5d8b8355736af76d37f9547941961d39b7427f37.nq.gz
    ├── 5da59a3543517ca6fdb40811b62b5e129c28ff02.nq.gz
    ├── 5dbb6cf22a01cdcafb8a52a4ec394888039f3c5a.nq.gz
    ├── 5dd40bad5578fd3f90c1c6370b5e576a9507dd49.nq.gz
    ├── 5e8b53dd52fcbdd7ba54a0c52a4e0b9d25d502f5.nq.gz
    ├── 5f81396e38251425af11f14882ed2603e819b5ca.nq.gz
    ├── 60152f40f3ecf0c487a4028d7c6f1a899661ccae.nq.gz
    ├── 605d4a00706142d5ebc1b7c1bc1eac65b85fc497.nq.gz
    ├── 612b54f8e029794152531ec1e004501379e6c299.nq.gz
    ├── 627c828e71e31f20aa786824b81afc007436933a.nq.gz
    ├── 62b611da081676d42f6c3f78a2c91e7bcedddedb.nq.gz
    ├── 6329bc0a76ce92e21e6a9149c921e6c6fd6915ac.nq.gz
    ├── 662f7c50b9edb83ad786dc61b2f7392dfa443bb1.nq.gz
    ├── 666407c142174b49f3906b138602c521cc3e4de2.nq.gz
    ├── 66b5cbea28c65b799957949d98748d23bdf4fb78.nq.gz
    └── 69612ae4f4f54d8b14ed52a8513f546ef956177d.nq.gz

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

[meta-llama/llama-recipes](https://github.com/meta-llama/llama-recipes)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
