# Repolex Knowledge Graph of json4s/json4s

RDF knowledge graph data for [json4s/json4s](https://github.com/json4s/json4s), parsed by [repolex](https://repolex.ai).

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
rlex download json4s/json4s
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f31d2fbc1e63ae2ed04f6150aec5b85e7de6c64a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f31d2fbc1e63ae2ed04f6150aec5b85e7de6c64a
│           └── chunk-001.nq.gz
└── blob
    ├── 00f461951b36a60fab25dc2417bd4b9f61024358.nq.gz
    ├── 01d8ac7e0c937000613454138eb7c451f77199ba.nq.gz
    ├── 020b17167319fea72cf6d338475f166965bfc2a0.nq.gz
    ├── 031522a3ffee91f58dd2dc4ff3786d5992e7d555.nq.gz
    ├── 0464a741d23394f92d64d563ce3bbed9f968ae98.nq.gz
    ├── 06902f57268b86cb6ab99b2403f2aa8a25d19428.nq.gz
    ├── 083ef18daef9e292032c08d1da39a5daa8c43210.nq.gz
    ├── 089427030a127b9553f86d00a8751fb1a1797576.nq.gz
    ├── 0a1087231e6f81b7a96bdb1446225f432f8e6360.nq.gz
    ├── 0a1c452e8c13acb6e63284b86d432f086288a14c.nq.gz
    ├── 0cd817a92e9d24e0bd753646c6d4c9e7bb3a91a7.nq.gz
    ├── 0d9e56d46c6d3b9979b1dc5f76b14a1ae83c87c7.nq.gz
    ├── 0db96bc565ff48abddc534e769e7a8594f7ff453.nq.gz
    ├── 0dc3405ecbd136a5ee33bb963a4ea5f0d9796924.nq.gz
    ├── 0e1e0e172bd5b2666bcdc21020411257687388d5.nq.gz
    ├── 0e26f9639d6711a5510699f7994bc960fe3e27c1.nq.gz
    ├── 0f0816987327ad47aa2684d37e5a75a8d50ce335.nq.gz
    ├── 107169aeef1f70f4866d6652601e102aae960bca.nq.gz
    ├── 108e5bbec084fcf4fb689dd2efcf82580d54c29a.nq.gz
    ├── 10cd11700b950a63d7b4f7e1518f9eba99ff4184.nq.gz
    ├── 11af3538e26a59d3ee545fbf86522df74251d712.nq.gz
    ├── 1235d6e7624f4f35008d2b8782122126131b2c5f.nq.gz
    ├── 12e451c5bcaa170d099daeb6d9e01ec1dae4667d.nq.gz
    ├── 15e2604fbee4dc7b594a61401767621a165a2cd8.nq.gz
    ├── 16adb396bd341f8a9d616bf9d58a71d7d8e41eda.nq.gz
    ├── 175b60c8406bf1bbfe6c9a420b9fb30aacaa0cf4.nq.gz
    ├── 177e88dabefee8174b2fe779e9ae62966fac7ade.nq.gz
    ├── 17d4e94255f3cdf16eebb14a42b65e989c5072de.nq.gz
    ├── 17e1a6c9d7d00af43f72c44bb52e42a3e435522d.nq.gz
    ├── 1be81b42db62c83385ed965cfc0316da844a50a4.nq.gz
    ├── 1e6c186b6bcc7398c990f1dcfc39a561d3810632.nq.gz
    ├── 20438f1c4eb0bb522f88d6d0c57c0f80720a301d.nq.gz
    ├── 2043ae31d036d37ec85081541ed1f61d9ba005bf.nq.gz
    ├── 206b9cd8d2b50e640ad103f9fbb38fdc9fb17c85.nq.gz
    ├── 214857e3aa5737af3cd69685f161bcd6b8553e47.nq.gz
    ├── 225fe1d73fb8bb90c8c1552e8f9c4296d39ff533.nq.gz
    ├── 22a0a1c2fe439c8f399be72777d0ce09aaeb21f6.nq.gz
    ├── 24201983966ad885be6acb5c92507ae413b3b4a1.nq.gz
    ├── 25524a66f2cc491e5f97ef8a27d6e2cce3aab841.nq.gz
    ├── 260149c1dc260502933a0480bde7f2a5e3be55cd.nq.gz
    ├── 277480ffdf02c72762644010d0676d440689dc8c.nq.gz
    ├── 27798bfb9b24cc57169d9b65d94b0ec29885cd1c.nq.gz
    ├── 29955ef2b1593697d5ee940fde75efe108ae6156.nq.gz
    ├── 299e1dfb68eb9f28fb1ce5a31b862276d4d772ef.nq.gz
    ├── 2a5922ff59a680184bec8a2749ce75523c9968d5.nq.gz
    ├── 2bafce88d9206345f21a759f10236b4dfbc84cec.nq.gz
    ├── 2d0b48b4aca5c40f817483d4bb5e74704b8ecfb9.nq.gz
    ├── 2ea0e18403664456c5cb8a0ef5e5e75cc7652133.nq.gz
    ├── 2f47ac5ce3d7145367085583ef63a60d662522f5.nq.gz
    ├── 30291cba2230c12b0d038717f8b0502836e4dd28.nq.gz
    ├── 30c4200299d48bd5d556582555f6e68098bff243.nq.gz
    ├── 3231a3b6d073175e23238ed365b6b39a573bee2a.nq.gz
    ├── 349669d4a9722e2a69b41e52e07b432d5ad28c50.nq.gz
    ├── 3623324673637561d434a802bf454e07a381ada5.nq.gz
    ├── 36b848b72fb7510c1d66987dd8a9d01f8487b508.nq.gz
    ├── 37c1edb082632bee9355fa7fbe31eb87bb7ba670.nq.gz
    ├── 37f33d327537fca00a9f6b27004432ec36aee8e8.nq.gz
    ├── 3868537e1568b639d2764cf7d391d853d84b9af5.nq.gz
    ├── 3869479d650c9e47237f649abc868ff5a20dba4f.nq.gz
    ├── 388c688725d958db73b61366699184a727cd30e1.nq.gz
    ├── 39bd26179547cf3747ecdd9d68e8365267891339.nq.gz
    ├── 3be483527f9bc08634ec25fe2e230aa2dd3745fc.nq.gz
    ├── 3e04fe3f7db8a2694d8905aeb474bcddd3ed8636.nq.gz
    ├── 3f66d55674425b2e913aebcf6eefd58eb5d527a2.nq.gz
    ├── 40a4915ac3e7d105505f8043db7048e3caa2db05.nq.gz
    ├── 41758ca9f5fe27400dd124b2e5a1b28aec65e84c.nq.gz
    ├── 42afe50fb678352983eb385c698ce82fe4a52c59.nq.gz
    ├── 42f6c9e48d74bc2e5125e10508046478e1912460.nq.gz
    ├── 45076b51e57f1f5cbdf836d16e30179967a178c7.nq.gz
    ├── 454767ce34b3616960a4034e8dd4000aa011b8ec.nq.gz
    ├── 459b78e951f22e878bd681835e612e7a16614869.nq.gz
    ├── 47a2df88922ca1a01838e9ba05d960bda5011dbc.nq.gz
    ├── 48a3f9ccc3a5ec997992686d065b1dc2c013d8b2.nq.gz
    ├── 48f7bb136341dd29c21bdc76a3587a00eceede05.nq.gz
    ├── 4909afd04fffa2413fb5ae911d24eb69ce3037d2.nq.gz
    ├── 492e913c0b5f872fa3fdca3701c2a8b448c1d921.nq.gz
    ├── 49e5702377e887a6beb552cd70654e5963039f8a.nq.gz
    ├── 4b2800200b4f64ca4c6a6405363afcf5b3d80872.nq.gz
    ├── 4c3814286a5f6c24551eebefdfdedde8732402e7.nq.gz
    ├── 4c4986843db1955066b89039ee1ce90d56e05a19.nq.gz
    ├── 4c71b6714b67423bf57e860550df829e71628673.nq.gz
    ├── 5322b2190e80f84e07ea8e3ce5df06a34e9a8d3b.nq.gz
    ├── 535bc4b24ccb9047aee7216a415f95e76445a2e7.nq.gz
    ├── 55f08dbe3ed47fc523eb920a0f30e68e9e2d2b4d.nq.gz
    ├── 5847a63f049086a09d21d77d7ffc3bd1c61203b4.nq.gz
    ├── 59133d137d56d8bf333558fafe5b6725653b6e89.nq.gz
    ├── 5b6d21c2790b27d2ec76d8217f76ede3b7f7d11b.nq.gz
    ├── 5e4ddac3234fb711f31d952cb1b41c7c0e0088c0.nq.gz
    ├── 5ea09154728ff6697e3f583a6d55bb294cc824a8.nq.gz
    ├── 6068e1f8228029fb63aead92992d3ac013c436e8.nq.gz
    ├── 611dbb539a1267fbd38fab8b177d1cad57e728fc.nq.gz
    ├── 616432840e4bb68906cab0d95af65de33c254332.nq.gz
    ├── 62368712adf682f14bbba7be812882172e3796a3.nq.gz
    ├── 62e739e825da604513c7f325c78aa073eb0a83e4.nq.gz
    ├── 651cb0223362fcda7fc956f48d55bf611651b44b.nq.gz
    ├── 665d28ade20146dba872b81a78763ae12de12925.nq.gz
    ├── 66906084a5240e45f87782f25871ce83bc57e65f.nq.gz
    ├── 66a58b2cdeab06e1682001dc9fac97219f85b747.nq.gz
    ├── 67422d6904c0de2aed4d9b3ef86ca8bcb5b4b470.nq.gz
    ├── 67848088729aafb98e2f5289b414df82b7006e74.nq.gz
    ├── 689629ad0261da4ccd4808346db129293da94611.nq.gz
    ├── 6af0166477e71c94b2bc22480a7a8a1b377c1d00.nq.gz
    ├── 6b8cd5606603ce36702f1666cbe21bf0b7e1d8d0.nq.gz
    ├── 6ccf1e62705de33d73c9c1f11033d944a36a4cf9.nq.gz
    ├── 6da6d8bca48064e86fa92fec9fa07c7c56ea69f3.nq.gz
    ├── 6f1ae49ba7d0dbffb2b0e3b38afd9d12eca37ee4.nq.gz
    ├── 712ca27cd25218d433c1ac842c89935b2555c0ff.nq.gz
    ├── 7218c76430465b4681add85508b16e8c8d994f0e.nq.gz
    ├── 73edb50553935fb2721a0e7c52acb9b14275b322.nq.gz
    ├── 752f27c73dd1630fe83d43df140fa754a9492b84.nq.gz
    ├── 77d03b58f3371a8996575dfc6711601b8b4f1dea.nq.gz
    ├── 791df3d87e00144ed600202f0f4fe766d2a7f728.nq.gz
    ├── 79ff5b3d4b63ea6dce54b756857f28a5fa00d34d.nq.gz
    ├── 7a5d22222af0b51a6f3066663544de87740aed81.nq.gz
    ├── 7b14393e4b5b4c0a9fe47150ff17b10fd61ca967.nq.gz
    ├── 7bc5bdc04c523adf57efd5d4da45959b627436da.nq.gz
    ├── 7fdf78184d1144bef26219742aae617bac25f7e5.nq.gz
    ├── 7fdfd0d560f57ec02c46f14caed80ce11f73a6e8.nq.gz
    ├── 80027cf013949489148bb21a48c73bd2c78956dc.nq.gz
    ├── 808a6d7e3d60cf81352172d23fea33f59777e984.nq.gz
    ├── 82777df776d308999bf47e7be0d04054d0df4ca0.nq.gz
    ├── 8484be546b436d94b3842c5995c387f1e583e2bc.nq.gz
    ├── 86f913dd2df15cb3ef801695ee1729031ee0b381.nq.gz
    ├── 877e5e9e16b58acdb72dd244238bfdc7abe3640c.nq.gz
    ├── 8872cd5ac937d2575de332952495a0a67b91694f.nq.gz
    ├── 89c56c7b262097d7b4b2235c985280c7667ce0d7.nq.gz
    ├── 8a061cbc69c57491d9cd13953e1a41bcd0329158.nq.gz
    ├── 8a5b3af69846ff525789e405378a7e034817ef4d.nq.gz
    ├── 8ab87b1589a0dc3f538a8b6bbb537201818dfafa.nq.gz
    ├── 8be2c170c829fe07ad7c69130ad8e3f137331287.nq.gz
    ├── 8c3faeebb2f5c6f448d8043d058a90783f2abee5.nq.gz
    ├── 8d82bdf733261f11d4fbdfef38e47b7c41e8cf02.nq.gz
    ├── 8e3f75d1b393b18dea488584d4bb887ce4176dfa.nq.gz
    ├── 8eb9ee2d8c450f55c834d138b1368aa656dc2584.nq.gz
    ├── 9211926b39c316b517fb3c9f6034bc51c391205c.nq.gz
    ├── 9262c6b7237021ab4b03b45cc65c3d3a0d829ab1.nq.gz
    ├── 9298b2bc0c917b4e3f6942cc38fe6e84ba3d0a01.nq.gz
    ├── 93436bf92dabf79b39c49d6658890d207a69afad.nq.gz
    ├── 93a252408b318bc71ede34903a43ff3e1ede891d.nq.gz
    ├── 93f62278b3ea2612883ef5df451949ac7b91be95.nq.gz
    ├── 94fbabb4b897da9ceb72ca4981cee34f99bbcc2d.nq.gz
    ├── 95723e0d755b361d4f91622b179b1ce2b6d484d6.nq.gz
    ├── 97d93f9e99608033c758d83ddeccae7372bb281a.nq.gz
    ├── 98263c7dfcedabedfcefa90b572446782f790d6f.nq.gz
    ├── 99dc7b3d331cf0883351693a01babc38c21000c7.nq.gz
    ├── 9a88e1d87c1d4219b80366f00ffad4473977383d.nq.gz
    ├── 9bb3321472b2c3fdd13d0fe3e83ecb8492fda871.nq.gz
    ├── 9cb7f4ee31bf006eb969068ae4b198e93e457028.nq.gz
    ├── 9cf841a1b08227e329eba550ec5b98c0352ba25f.nq.gz
    ├── 9d429e5f57d978dfb83b8405765ffa2e2f2e6c54.nq.gz
    ├── 9db7b4f6d83e0b8991be2b8b49474854758828f2.nq.gz
    ├── 9ef06fef2a9047a3cf74681fbea34983400aaff4.nq.gz
    ├── 9f05284ba1e34f7a58aaef71d3843637b1006fe5.nq.gz
    ├── 9f14085cd6d6a8694a1022b0675eaf1305fb5085.nq.gz
    ├── 9f523048bba844b772bffd306eecb14be1e38480.nq.gz
    ├── a0761e07a903327820e727226f776d4cca147b5f.nq.gz
    ├── a0a7a07d0207a45477037180c52d18eb7fc859c6.nq.gz
    ├── a27fa6563cee2ca532f858e834fe50435902df89.nq.gz
    ├── a373e2f0e810699d13e10e41bfadc7fac8beb0e6.nq.gz
    ├── a40a7eebd3d2c3e981e7477cae09ed3b0e1669be.nq.gz
    ├── a4fd58b018809ea0bc632157f4b76de27bb9ea4b.nq.gz
    ├── a6eb5c3d96584bf926f2df1e1458ce20ff22ae9b.nq.gz
    ├── a77257c3e6b0c198b069a368d76868375e4b1479.nq.gz
    ├── a885d92f0b14e7954da89705cc42508093254dad.nq.gz
    ├── ab02b2809b17767848767a00817839bf7645f345.nq.gz
    ├── abcbc037a4e8e412b778f5873251ef3079c9a813.nq.gz
    ├── ac064c788ecc801c00a3efbc6f9bf8ae19fa7b02.nq.gz
    ├── ac32010873706f89ded716f3d784ecc073a5d9ff.nq.gz
    ├── ac752981d7dd3157c9840b26df332d3e25769e1c.nq.gz
    ├── ad144cd7b15131535b38758e152ee78e1426f739.nq.gz
    ├── afb3f09823c70654c2ff5e3aa707e51885bd8850.nq.gz
    ├── b0f853c10458be4c96d23e651a55cd9167949603.nq.gz
    ├── b1ca926376792aad2aba8cddb91b0f9c499b8f8f.nq.gz
    ├── b29bb641bc4a5aafdbd10f9d2fd347bb4a7a8d41.nq.gz
    ├── b3087e2a1756c0b1e621c7b97517ec67750ef2bf.nq.gz
    ├── b42039e70bea31967c85dd25c28878bbf52b2ac0.nq.gz
    ├── b4a68cbf9633b5b6afdbab05962252b59a0b1ccb.nq.gz
    ├── b57713a26d3044872ba0672feef1ce2b7350ad27.nq.gz
    ├── b57ceca518bd3822584392dc342fadab6606dbda.nq.gz
    ├── b68cd52ce0a5852363e95665f03b56709c942cbd.nq.gz
    ├── b7c9845ad22a19c8aff90f9c205364bf90865b9e.nq.gz
    ├── b85c4e22400d5ccb89ed3aec1a16a86eb0cc9c70.nq.gz
    ├── b8c7eb446bd51520e1d9d09f8b733c238a0fdb36.nq.gz
    ├── b9b68caae75812ee83dbcc23eb468506560edfb3.nq.gz
    ├── bab2576fb8a524959b8218281d3d4972e7c6a0c0.nq.gz
    ├── bc99c4df2a5fea9eff0bb7473956cb1202d1296f.nq.gz
    ├── bcebe39d5b90676ae23859e39b9b0d6044378b31.nq.gz
    ├── bcebfdf76d5daca6cd90f8953e98e9107b3cac35.nq.gz
    ├── bd67e059b7a5958037c4cf87dd7abd52d042867d.nq.gz
    ├── c04a929324bb902c1e29d1198a272356de338553.nq.gz
    ├── c0981a9140fdc2423aa2feff339e8f16e4456e68.nq.gz
    ├── c0d3ecfc2f4f975c9ea8bc649b1054026802fcfc.nq.gz
    ├── c1b2c0f6dedadc2e4eebf95761193bf59ff36be8.nq.gz
    ├── c2200b1002346c75e19df6493eebe19232adacd6.nq.gz
    ├── c230bb9c086065f39d51eebe415deeef881b7dbf.nq.gz
    ├── c28f8f1fac5759e8933d9fddc0eb51d6f9e88f35.nq.gz
    ├── c4f09506912856fb60cfb835b31b1dfed2e5c1d7.nq.gz
    └── c6d97da2a1968c78bb274b6da58c46129571e73b.nq.gz

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

[json4s/json4s](https://github.com/json4s/json4s)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
