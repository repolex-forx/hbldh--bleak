# Repolex Knowledge Graph of hbldh/bleak

RDF knowledge graph data for [hbldh/bleak](https://github.com/hbldh/bleak), parsed by [repolex](https://repolex.ai).

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
rlex download hbldh/bleak
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c7ca1b04b00b0bda5f98ccf9493e24784cfe869d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c7ca1b04b00b0bda5f98ccf9493e24784cfe869d
│           └── chunk-001.nq.gz
├── blob
│   ├── 001c9714c726aabe4e66e43f25bfbd0177a1a94b.nq.gz
│   ├── 0157c8c506de5b0e49c120aff5caf7b45ce1d168.nq.gz
│   ├── 01be044afb6f593a91d11e137dcdfa8977d8c3c2.nq.gz
│   ├── 03b97e6c7dbdf4d7909e4063e078e7b18c04c2dd.nq.gz
│   ├── 064e552b1b51810a09f9ecfee4c1e8f0e58e6305.nq.gz
│   ├── 06ac7c3f6b344d186a82faa74d9e91f43bdccc6c.nq.gz
│   ├── 0850acda8119020deb06f3ab1d4fce8c5c382aaa.nq.gz
│   ├── 0adcfafb2c692c9760862c06f44b4c586601ef7e.nq.gz
│   ├── 0c48665ba74f7159fa9e63075e833ad3195357ab.nq.gz
│   ├── 0cf5b175dc6778906998476ef8eea703105bb1f2.nq.gz
│   ├── 0e6dd7b41adee45ddf08dc5dfa230640fc793458.nq.gz
│   ├── 0fea12734d739dd5d5c33c84df03ecdf61f707af.nq.gz
│   ├── 10b87e83ac5af8609159e5654d6e6687e56af762.nq.gz
│   ├── 12c2945a62bb3db1d95ba4b337ea629aed37f875.nq.gz
│   ├── 142371eb7dc669e6317a97fd7243782de34b98e4.nq.gz
│   ├── 1758e765f9945bc6b547b2b6ad3276c4b3e1758b.nq.gz
│   ├── 1a363c71a0fffea47b8625df2aa1e97e1e6dea66.nq.gz
│   ├── 1ea8b6c842fae2175d4b8616c521eb5b7c2f4986.nq.gz
│   ├── 1f23badf99768ba40ef1dfe2e4f1dfead201de52.nq.gz
│   ├── 20193a041567bd9c53ed7e2f773b6ada2e38f29c.nq.gz
│   ├── 2829716de30214dc0370ef15c8043c486fe380f9.nq.gz
│   ├── 2c8579ef423fd0858d197db8119e4b3906905db0.nq.gz
│   ├── 2cf032093909619618a2d05616347e34293a9133.nq.gz
│   ├── 2e44ded73c07e930627ea7cd36343e8b9f5119ce.nq.gz
│   ├── 30b4292a7da612a5d1f67b626c807ee100a70569.nq.gz
│   ├── 3162c8b44b7444d1849d5f99625f1ed1f1a9a295.nq.gz
│   ├── 331efb0d1346950d850239c0e9ce2928746ab778.nq.gz
│   ├── 34c0f3ea9cfb0a92e5e9d76d7f85744c2df14f54.nq.gz
│   ├── 3634b6612b6f232e09292ed40e45002e73829105.nq.gz
│   ├── 38315e6d74918164b0db30c2319aa3134bc49d68.nq.gz
│   ├── 3b375d64d7a97d8ff5823bd3259de08a91a819b7.nq.gz
│   ├── 3b7ffa12006d785832ca4dcb82c1f7bf5cdfaf97.nq.gz
│   ├── 40974e2964b471c7a96820f03741a5aa68a3e48f.nq.gz
│   ├── 40e6bd660f8ae339fce9d4e77972d45367a938f0.nq.gz
│   ├── 435db91d8f79d1e07c63a188c6884a80db029b13.nq.gz
│   ├── 43a06c67dc7a960652063e125c0e9a14e6b0e759.nq.gz
│   ├── 440690349f6d5bd11dc44b722954e4e0b187cc79.nq.gz
│   ├── 446bbb7c6d6d9324b17159ed4e797d03ac421c18.nq.gz
│   ├── 46afe54f3ecbaf858f991c321b6e763ab2735fa4.nq.gz
│   ├── 47e0916a09e5fecbdaba2dc60e888150d841b5d0.nq.gz
│   ├── 4850a957459de48433f04a52e040b7e14affd1ae.nq.gz
│   ├── 48c1eac286ad4e71bfd474e631d280f4ca2b2a2f.nq.gz
│   ├── 4a16beee133acb7ab138d995a268a5128522b4ea.nq.gz
│   ├── 4b47c9d34f16209c5a726f5f32f29e457f5992dd.nq.gz
│   ├── 53ce6673a25b4083bfb9a3ef1ff16608302b0f4d.nq.gz
│   ├── 549c66e13f6932c95910df7a7d929beb0d02d9a8.nq.gz
│   ├── 54b1c5fef8110188228974d0fb57dc41e0d72b39.nq.gz
│   ├── 54fd1beeb364ae39756453677e87c4fde34c1a8f.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 57e72bad3de4496e7c37e08e7c5aa6e02531738e.nq.gz
│   ├── 58291f2569efdc3c507aa9ba763d653e7315c7e1.nq.gz
│   ├── 5961279f86fdb9b826f04824986a5ad653fc1adb.nq.gz
│   ├── 5c10397f23e6fe3f4d95c17846771a84d6c249d7.nq.gz
│   ├── 5c73cb6515751b9036cd9461037fe2386ed1a791.nq.gz
│   ├── 625c179681b81b78633c3f7321fa9c90623f6dc5.nq.gz
│   ├── 63b426aaa8789a0586da2473a5626fb80d0e97f7.nq.gz
│   ├── 63d9ca2ff2b22871d5fa1af8b9d72352b3f2a57a.nq.gz
│   ├── 66479be1723bcbfc97ac7417b6f537c96f4d9a2b.nq.gz
│   ├── 666075762b15114239e9056e9661d4487117290f.nq.gz
│   ├── 66b36fc209012e1153763bcc8a767646c5aed8ff.nq.gz
│   ├── 688734a5745997f2febbf23a0994539e275923ed.nq.gz
│   ├── 688b9dfdbbfd4de454e88056a0a6d5d26ad78aaa.nq.gz
│   ├── 6a6515e71d02b47fc443acc65ba179b17597589b.nq.gz
│   ├── 6d93c254d7bf950b864969b29fc8fd4df7cf8b2d.nq.gz
│   ├── 7152c837a2e04a0f382862a1439a73fc1887d2ac.nq.gz
│   ├── 7180b3d2dec5e755d157977f39c17386ca577b6b.nq.gz
│   ├── 748ad6e921ae990773b4ec7cc50afd66bb7531c7.nq.gz
│   ├── 76434ea9f63b20d87caa5b3783691d55035de137.nq.gz
│   ├── 77c515f49c7899277bbdfdf57fdb9e96594a5890.nq.gz
│   ├── 7de87462b5b1b6ec0ea459b1c74f61255d51c44c.nq.gz
│   ├── 7e8744c54715492e894bd7e0606177297707ec20.nq.gz
│   ├── 7fdb472bc8e4a23449ee5576068cce39c77c0757.nq.gz
│   ├── 84703515ec254324474bbffbcad424fa546d67db.nq.gz
│   ├── 856d9f0af89acf0c455fbd1a7296e997b0e9fac9.nq.gz
│   ├── 8887c4d6cbd29c224cadf5b0675e08199dd2eb53.nq.gz
│   ├── 8a81534ba7fbf04812871f396ea1c9784e5f853a.nq.gz
│   ├── 8b033310dbb565447da549b158a8f2da4b15cb9a.nq.gz
│   ├── 8b18fd34770d25e9e13697de1f5412f44f2e1708.nq.gz
│   ├── 8b873b2b2c3d350bd432d4cf26fe6e8959354e2e.nq.gz
│   ├── 8f9ca5f86ac6a6f522abfdfe0b957ea2acc2f8aa.nq.gz
│   ├── 9273aa4441b1bad946303f1d6e6a69357d29bf90.nq.gz
│   ├── 92a26edb6c277c78820c693554cd1e8082da9fe7.nq.gz
│   ├── 937e6fe4e255c0769b27c8347cca840204e01301.nq.gz
│   ├── 96628062020f0012304641d8332876695163ac79.nq.gz
│   ├── 97a95011927f9ec451c968e1a96bfaf9715f83fa.nq.gz
│   ├── 98c0cf6b4304289427b08ad77edcfbcfce09ce3d.nq.gz
│   ├── 9a76880b95c4bdad00b1fc7314ca3dd50b059316.nq.gz
│   ├── 9bf949611f519d37b9e396222dae031afd73a04f.nq.gz
│   ├── 9ff68163071134dc2a5a2339096aa8c28ac831c6.nq.gz
│   ├── a02cf9129a53cc711e82c7f425e04d7e41d4c5e8.nq.gz
│   ├── a13ac95409b0eafa484d3bf6013b482a2cecb567.nq.gz
│   ├── a16445645b49cacd982d342cb874b8f837682e17.nq.gz
│   ├── a205aa7afcaa8a04e392e1af93acdbf6e95f3c23.nq.gz
│   ├── a46bd16db0a1e0f6aed9875bd2820ac4d07ff047.nq.gz
│   ├── a6152678c0445bf0af612d47df22e2008e9682a6.nq.gz
│   ├── a62873ed2a9665c6a7af99ea3632e101858f5d67.nq.gz
│   ├── a66daf378fe8e250f854d0e51aa972975b90efdd.nq.gz
│   ├── a6c2e654cf678f2e223fb46bf93d1f5957aa5b4a.nq.gz
│   ├── a83eb356f891ca7880dea3d840a17ed91462ea15.nq.gz
│   ├── a90aee8f156fe20bb1c1bb63c1d4d7bf1c7cd124.nq.gz
│   ├── ab5669a9f63ef643d5e74f208b536d84c0a8f030.nq.gz
│   ├── ac6b48aa912b9153fcda26c07cd3e712b9eaa5ff.nq.gz
│   ├── adaf01b4315555e24d5c01a2636b4cc7e57c8335.nq.gz
│   ├── aeaceee83b8a66cb8146434d728bb781ac427d84.nq.gz
│   ├── aee042ee940f3823c231bbadeb7d9d94c30f11a5.nq.gz
│   ├── b10e311956da5de8de98ba343697735894e1f28c.nq.gz
│   ├── b3132715a07f0b3d263279a9c56b6a2005e23922.nq.gz
│   ├── b43d2c137208122d9353df47ce6d27118a536ddb.nq.gz
│   ├── b55df53e92f817b5c0a1b76080fc46ec9c14e976.nq.gz
│   ├── b792bd72fd8e1c290c70b2b5d7d6cb76d8ed84a3.nq.gz
│   ├── b7e82e831f23fac42b69a9125f85e86568e56823.nq.gz
│   ├── b9b7cd434920cd41e4afc35a266841984e656632.nq.gz
│   ├── ba230ce317ff14e27fe6f041d64f0d0ec7f5cc34.nq.gz
│   ├── ba4a2e6521a4abf522f3c53b15cfc467e880d8d4.nq.gz
│   ├── bd236d914e4ed310abc2cb377ebcc773c4a810e6.nq.gz
│   ├── be22e6f96d5ff65cba85fded2ef965b1df4a8833.nq.gz
│   ├── bffba6245a3c8d6abf41ac4c0b488e50da4b1846.nq.gz
│   ├── c169d6bc1a15d127b73723d26adce08a0a3135fb.nq.gz
│   ├── c1b4018c04adac9bd539eab06d171c830f7dbb22.nq.gz
│   ├── c45bcc669247d3dfc850da221754544b9f94a330.nq.gz
│   ├── c464d16cc923886cc9f6999a68522a21407b8328.nq.gz
│   ├── c4bdb30646dd2d52386153bdb6ca9097f6e33209.nq.gz
│   ├── c58781d30e838e79df06102f4c17ac02b6daf016.nq.gz
│   ├── c5a408251f8065c3ac0f3127d665d57aea7c7655.nq.gz
│   ├── c67745e2d4aee91a5a27dfea642dccec0eb52ffe.nq.gz
│   ├── c7d28f287d17058c2de8dbd9f3cf1877aeb0166b.nq.gz
│   ├── c848ec2cb63a2129a8d7cb63795edcd772711187.nq.gz
│   ├── c9942d1bd2e0b20dd82970945f71d7bd9c62d384.nq.gz
│   ├── caf3be0bc928e47724c6df2a3a74ca52d121b78b.nq.gz
│   ├── cc5652abc3898d1d24230497de560ea421f5c0b4.nq.gz
│   ├── cfa80bbd7a66328a5ec31066b2ce5964ade88765.nq.gz
│   ├── cfa9c7ddf52d7e4bf926cd4deb037b0b054a91ff.nq.gz
│   ├── d28a6e11d8b87d08624a8dd898e4095c5b5d63db.nq.gz
│   ├── d3ca0913fe3e585434b2566da01571830324c682.nq.gz
│   ├── d3d33a128133b7b6a99f01c4a6042a6924f48871.nq.gz
│   ├── d58c3343641784a2d4cdec1723567beb8520173f.nq.gz
│   ├── d5b9b9393f6a6ee0dff7d3a45f7cddc31e309902.nq.gz
│   ├── d6bbd253fd19d92fc3180be002950b4679a3ba5d.nq.gz
│   ├── d6f100150711fba29f1feb2dce465f99fec9a5b9.nq.gz
│   ├── d78f940112bed0b6fbcb9f774cea8e7694594803.nq.gz
│   ├── d8b91ed797db1159e13932a410d2042910f645a2.nq.gz
│   ├── d8cc346e446cd6c7a3f05afa35554b6869fae1f2.nq.gz
│   ├── d9001ef40fafca19b86fc6293efd15c5bb93e7cb.nq.gz
│   ├── da63e9e387e04d2df40b9c887a1511d91172d8d8.nq.gz
│   ├── daec885fd0fa9258f2ebe776d2bcb09ae5c0a2cc.nq.gz
│   ├── dcc5597795d6a9cd550da8478bfd57374706b525.nq.gz
│   ├── dd00812d6cf4116a6630c6bd1c092d0635d3a53c.nq.gz
│   ├── dd965d3bb533b316e0cc3c5cb52ffad996aaa2ad.nq.gz
│   ├── de753cf28ddbf9c3876f4d6c5124a3787f1fce45.nq.gz
│   ├── df1bf6bb57e37dc88a25b3b1ca414d92c48084ac.nq.gz
│   ├── df7fe5774e016e27cf0ac3bdaac3a9ad490a4fe5.nq.gz
│   ├── dfcd0fc5ae462a408a5b4188d8d92afb73299e0d.nq.gz
│   ├── e0a4c7a69a2af686781517aa9994edc0474eb004.nq.gz
│   ├── e0fdb8bebd95b0f60bf7b01fd269c52c154fc8a9.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e4144149ab9546add5c4808f46827e07e57d7365.nq.gz
│   ├── e5696eb8f5a531e110a8d9ab78b9de27e7a5f4de.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e60ea101084916e751a5de128592c69e6c3861f9.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea4fbc1bfed3a7b4e8a00a99e45fd30a1faec123.nq.gz
│   ├── ea8bb0f07108221138def203cf2c1cea6112514f.nq.gz
│   ├── ead4442b920a3f20e4726517cabbe0190b78d914.nq.gz
│   ├── ed6e177d682cd70bba070b179e51265b11b2bbc1.nq.gz
│   ├── ef9e2014395a795bb5ec1b5260a273da68999bf5.nq.gz
│   ├── f351ca8ae2f72675d9cc3bcd4b2ee57442e878f2.nq.gz
│   ├── f4080636b2304f7d64853eb6a6895266c2708400.nq.gz
│   ├── f47fe668a01f72213246d077ae90e0a87844c2ad.nq.gz
│   ├── f4a0461a013df8b51b084e80d3e850ba58e94538.nq.gz
│   ├── f595284041be1fd35c07f9f8db7b22b4c5f84f2f.nq.gz
│   ├── f760885423271ac6f39f6fb19a8f8bada7789072.nq.gz
│   ├── f9c0c02c3d280a3e6f352bbd868f851304ed749d.nq.gz
│   ├── fb619d8430b5e59548416d5d03167ba257125a91.nq.gz
│   └── fb694b536c32d720e1baaf349d519f54e86a3836.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c7ca1b04b00b0bda5f98ccf9493e24784cfe869d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 182 files
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

[hbldh/bleak](https://github.com/hbldh/bleak)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
