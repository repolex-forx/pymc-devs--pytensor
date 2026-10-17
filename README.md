# Repolex Knowledge Graph of pymc-devs/pytensor

RDF knowledge graph data for [pymc-devs/pytensor](https://github.com/pymc-devs/pytensor), parsed by [repolex](https://repolex.ai).

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
rlex download pymc-devs/pytensor
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ce6df07fd243c5d372d84e30078fe2abd03f81d2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ce6df07fd243c5d372d84e30078fe2abd03f81d2
│           └── chunk-001.nq.gz
└── blob
    ├── 007329401267f8d14d9d6937637693954e6ea8dc.nq.gz
    ├── 0096063d7c92a8a5ff4be8861f93a35b9cb9781e.nq.gz
    ├── 01804b21a2e2e710b47f5ae2e10b825a126079b1.nq.gz
    ├── 0251f73c13623598930d475375213e65bc7ff30b.nq.gz
    ├── 028c85485413d65e0abfe656b0845576adcc9f90.nq.gz
    ├── 02b357eaa2cbbad135842478d9be619abe610dd1.nq.gz
    ├── 02f305b06b9a62fbe47ceb3c5a53d6ac288180e9.nq.gz
    ├── 0301eb181a710520d3ffe28df6114e3a493c11ce.nq.gz
    ├── 03488d4b140019895e282b46b99354ce6b68346b.nq.gz
    ├── 038989686c6b6bfede0dd9b7a3ed6219a9a65415.nq.gz
    ├── 03c461ee7fe74139bc68254b0fe8ec58c0d01e7e.nq.gz
    ├── 0669c4fdd37bfdae2fd106d77ae7d75841e0a6db.nq.gz
    ├── 0681d32a8eb8979f632afa3b47cde4e26ed263e4.nq.gz
    ├── 06aaeb5ae93c084d3d665fee3687e9dff8c5150e.nq.gz
    ├── 06b49db0b7a5b31fe544ab046922d981f204ff8a.nq.gz
    ├── 073c6f2818019c77e13d9acfa9570923e040a16c.nq.gz
    ├── 078f35c102a86239cb74a41eef42bf0068da82d4.nq.gz
    ├── 0849fba5cbb1d4373be41bbf47fe03614334b140.nq.gz
    ├── 088c5d73a2f2b7020b4aec783ceb8337816e298e.nq.gz
    ├── 08aeff776668c690ee704f247246c8b9d5f95cbe.nq.gz
    ├── 09e0a4ae52468e4155260e6a83ea5a403a986003.nq.gz
    ├── 0b8c33e040ea6bd1743024550d2be778c2a7960d.nq.gz
    ├── 0c51f8eb41a199d0ae825a189173df6ccab3f0f8.nq.gz
    ├── 0da32429e2b3eabbe0d37bb39cabf53635d42db1.nq.gz
    ├── 0e3bf98481828f8f5b716cb7d38259e853100ec1.nq.gz
    ├── 0f622e73a1ec349cca0e65cfac12725cd25fb37a.nq.gz
    ├── 0f73a090d4cf35481ede32c847cfc0466eb5b975.nq.gz
    ├── 0fbc9d3219ebb905d94d48bb9a32e8c9a54193f6.nq.gz
    ├── 10b05c498d975b8046265a1af042192600806a77.nq.gz
    ├── 124ea857384cbe13e0f148f4764b75830240d413.nq.gz
    ├── 127b971b2e5c34b6392f40f813918053e765b729.nq.gz
    ├── 1305211b0c865d0179661989ee1a7260f0647f76.nq.gz
    ├── 131f9d0dc99cb8d2ab96692af8286f38bc87b199.nq.gz
    ├── 135d8ecd832c2cf5612a8a800e2bdf04923d6ccb.nq.gz
    ├── 13ae08eafb8068b603fbdb1d67c7485e646a9f5b.nq.gz
    ├── 15a1ddc5428396c3b99f20803253164e5f830855.nq.gz
    ├── 15dfced32b18633aba5774111f63f5e393be441f.nq.gz
    ├── 1686cf8a80495d8af687ad4ce56844ab85676870.nq.gz
    ├── 16bcb6de911c4d94bb2ad669c8926b0c48ae705c.nq.gz
    ├── 16e93635a82b4d25e8c2a3754ab09d31832b97bf.nq.gz
    ├── 175bbb788bbb37a7a8d2b0e4ab77d29814b7890c.nq.gz
    ├── 17f472fac0da273bebb3a35af746ae52598b8bff.nq.gz
    ├── 180842f084567a7ddb506af913e193c29ea17c77.nq.gz
    ├── 18b7c080533bafb3cd0bed863b49cf776c382dd4.nq.gz
    ├── 18d57b29c0b8f1d68b38d335866c6d8712c10f78.nq.gz
    ├── 18fce217beca740603291a3298bdd425c6a0aa99.nq.gz
    ├── 190f6fea756a123011981dee06d9dea546571016.nq.gz
    ├── 1954c6cbb62df23674aabae17b8aae347518d1b5.nq.gz
    ├── 1961a10ab67002364401c6daa0cb75a7a3f27753.nq.gz
    ├── 19880ff05f5bb8b5e01b3cc98fb833ad2e776174.nq.gz
    ├── 19af6f22c7473b88be46b8fcc41bd27f1278b388.nq.gz
    ├── 1a3a2c3ff85bcb959cb8e9559d15db5cb6a91125.nq.gz
    ├── 1bf6d5489653e85324b69dc0849b99e7627f76dc.nq.gz
    ├── 1c7789926c89f6bbb5bb5b82ed7a2f5c0d25bbda.nq.gz
    ├── 1da24584a2b69bc673d6d02e348792d54d50ebcd.nq.gz
    ├── 1dd5bb43bb3ea90375d31edf24fca91e6b473e37.nq.gz
    ├── 1eaec9f0f28c4de024ed8de154a6197b8863d3e1.nq.gz
    ├── 1eb559c6ca5ce82a7cdfa95df42b0202215efbcf.nq.gz
    ├── 1f0658a7a5a84c1aa2ee66e620d854d347028727.nq.gz
    ├── 1f651c1969ffac77549096a53c8bdd7c94b27b93.nq.gz
    ├── 1f7a5fdc73973c765d9e731589bf31ff979c14f4.nq.gz
    ├── 1fd3c50f330b8bad194cbe6dd72014286d0cd80b.nq.gz
    ├── 200078133ab2ce4a0f7d4f12474566bfe2d874bc.nq.gz
    ├── 204711d5461d5c22dd3936eea7d59c3bf8a75e2b.nq.gz
    ├── 206fb1ad53bdefec625e4ad9a56e98438e86e101.nq.gz
    ├── 21ec9800e2c2fff4a6617a3898d5da5888b4ab38.nq.gz
    ├── 222191415c8adced8686f102103158b382fc81be.nq.gz
    ├── 22de7642f175458d0b47e16277a87e45b9998a78.nq.gz
    ├── 23150d33d002343e7bc3db9ea2ebb895600bd7f2.nq.gz
    ├── 2341b27a5b4fea6c91dab53ba552c3b77050ee8f.nq.gz
    ├── 236ad7afe23a3d9f3d3ea65a6af9d4f760b8b7c8.nq.gz
    ├── 239533ff7b48232d8e3297d5f67ffea25189befb.nq.gz
    ├── 239f73df806cd475cb1e84c5a3cc65cfba958cf0.nq.gz
    ├── 23b9f31a2077d6f8d4235f4bb9015d9e1b95f3f6.nq.gz
    ├── 23fcff91fc24582aff859a1f1b59e906082e9ebc.nq.gz
    ├── 240ec3fedf26af10703e4b56ef5a58e63f25ff54.nq.gz
    ├── 241c73583a4eca94f300aed577e26210a0d4d6f9.nq.gz
    ├── 25584e3a53c4ac42fdf4f8815e7615ee11ba3688.nq.gz
    ├── 25fb9d2e67cd7454b373a7d13d280bed8974229a.nq.gz
    ├── 262a04f330a162d554f2539c25cb6875698b9ca5.nq.gz
    ├── 26401da59628936012b2779f200bfca7e67032ed.nq.gz
    ├── 26477a9602f38bb69e9d2df5f6f5601e6a161448.nq.gz
    ├── 26f1a07f5362772f9e1ec03d6b6686fb3d6efdad.nq.gz
    ├── 27a25d4155b7c39cf7711b274033e004c96f621c.nq.gz
    ├── 2805f09226bccd838904f0b3c108f89da470d4f5.nq.gz
    ├── 2952f36282bf073b3d676c88e3aa881b9a36f595.nq.gz
    ├── 2aca41626384d1da0382d58ee28e50f1662ff4c5.nq.gz
    ├── 2b96ef9ef5e90de4af3cdac6a5784a2c897bf8c9.nq.gz
    ├── 2bc607b37671e47877c415158a393823c43fa3a4.nq.gz
    ├── 2d0911b24963461ce8e60abc668966ab7d409ea0.nq.gz
    ├── 2d7adc7f10ffe3e1671df6f05dd9ef9a0db9649a.nq.gz
    ├── 2e2081d3b401af6474d98b80a1ba60135108eefc.nq.gz
    ├── 2ebc0004d5f1d44d275a1fcb82441da8384f3171.nq.gz
    ├── 2ed8515ceebd426906c4bc62f15af0b13f19529b.nq.gz
    ├── 2f857e6775ecdc9e54e1423a7c7d1a6f2dcc96be.nq.gz
    ├── 2fb47fac34ee010dd38d8189ddcdcf4adb18de07.nq.gz
    ├── 301e448fded0dd035f2e5fab02e8f3f4f267c72b.nq.gz
    ├── 304676e994a99c000b5ba4bd6971cb503c51763d.nq.gz
    ├── 305c4cc4afc961cc219f19b5cf123efa6f43dc06.nq.gz
    ├── 30ba1131e04f604e30d76471e44f4a80a1241c31.nq.gz
    ├── 30c2f0a5c078441653b9fc24f5d7e1bfaabb7bf3.nq.gz
    ├── 30fc55ed99fdfa00f3e03ddec719fe53aa78dd6d.nq.gz
    ├── 317d27a79c509ea2e99cd924b57e5f55e78cf4fb.nq.gz
    ├── 31d45fe6617e85c86541d2a0e2f1ee3c6c3ad75b.nq.gz
    ├── 324a486adb9feba34e96ba208ff1b5337023a21b.nq.gz
    ├── 325ccb7f5c4edf64f35e3c2aef415a6e3f4fe351.nq.gz
    ├── 327f6b639a9c4dc4d7701e46ca736e6841e6bf8b.nq.gz
    ├── 32a85c4b1900817103a0e6e6338fb70d896060aa.nq.gz
    ├── 332876643d1ad31ab7833376b2eddaa34af0c47a.nq.gz
    ├── 334220d417db36e9593cb17278ab2285c65169cd.nq.gz
    ├── 3424a6c68f73aeefdc79ac49440826f42974a012.nq.gz
    ├── 3517acbb553a12c29e3d92796abe95d5248f6c5d.nq.gz
    ├── 35bbdc69b92038707188f34cad92b4175c3d04db.nq.gz
    ├── 361b5cdd346746bdf7bf0104eb24347694b920ea.nq.gz
    ├── 365c8c1c248165c622861c76ca535a347280d9d7.nq.gz
    ├── 36eeea4b3dd1756f1ad50d32dd1bff5de8c96427.nq.gz
    ├── 36ef00de7f8ef386909f3b1c959175c724b8c44c.nq.gz
    ├── 373b0b22e454d702c2c34c1386b16a86447b6c38.nq.gz
    ├── 37802b129f79a485697733dc15bec713440eaec3.nq.gz
    ├── 37c082896f87f545c538c9bf75843345019015c2.nq.gz
    ├── 3a2e152a4b88f6aea3943330c2a1a398b0906a60.nq.gz
    ├── 3a3b93d8f729b4e8a5e3aeea53659f868ca3bd68.nq.gz
    ├── 3a3cce12d57ea864b75d4dd03e305a1e1999508b.nq.gz
    ├── 3a7a8b7287e54aab0bc202f459883b78d2b51963.nq.gz
    ├── 3a9e5dcfc81279d4a2494d425aba419f3c88c019.nq.gz
    ├── 3ac2357c13eecb9ca4c786ec8bbea645d7af604d.nq.gz
    ├── 3bf809fb3ae02ebd3e914dc8c3cfa21ced2dbedf.nq.gz
    ├── 3c07a4dd719624c862bdf1312a74c132fba8c235.nq.gz
    ├── 3cc2ef8908d8bba9b64d290a5c49c2e9abca1f1a.nq.gz
    ├── 3ce38ae45a66db5841f61d15d7b71a7bb3556fef.nq.gz
    ├── 3da86c98741baf2fe393c1816f3c7d0cace61efa.nq.gz
    ├── 3de6b4e305121e89b021674fd1c7076e0d5e7648.nq.gz
    ├── 3f822a839865646cd07b281f0e022ba7afd3fa05.nq.gz
    ├── 3fddc7220425fec594fd692effeb5fdca755555c.nq.gz
    ├── 4033671f529170c8be291988a7eafef1c7766b6b.nq.gz
    ├── 405d3ea79a299cf270c221712e4055637259cb6e.nq.gz
    ├── 40aff4d02c036aee19a396eb64b4e30bcdcea19f.nq.gz
    ├── 41a5f09a3443e4adb9b619d4959d217a81e2c385.nq.gz
    ├── 428e9bd7e9be7b6d002a134829157b5eebc7fe3e.nq.gz
    ├── 43058a26c5086e84af8cfbc4f9e8d875dcb8b5bd.nq.gz
    ├── 463d0581552e1b708c88bf50c1a84a1c75c9d217.nq.gz
    ├── 4695263ba743927b4e666d042fa91adbc2e95516.nq.gz
    ├── 46e186dd8fbe6d0a5baaa558ca8175c2b74c27c2.nq.gz
    ├── 481457d4dac17b6bad4cd183e76075172ea04de1.nq.gz
    ├── 4816d79bb39d666a0dd5ff84f4bd1e2ef1704b2a.nq.gz
    ├── 484f20e97d83bd6e645546d4019f9300094329b9.nq.gz
    ├── 4910f527397d5fc7de9d1a89492e70be4ae543be.nq.gz
    ├── 4a3a64e7ce53f8e7dd3a1cb5f3022634a6830eb8.nq.gz
    ├── 4a5d387e2aeac0af0418b3b601ae8fff57727b5a.nq.gz
    ├── 4a67a54e7a420b1660cd7600f5f3bdacb4d1366b.nq.gz
    ├── 4b3cf8095a466eaa7a72486e6646048e2717b62f.nq.gz
    ├── 4b43d1aefe3df271ca89d3760edc3ff02c507174.nq.gz
    ├── 4b941b2051dfb6b47fd523158cee93c1353912d7.nq.gz
    ├── 4c030d170081a2cee9eb369e56eae78721326c39.nq.gz
    ├── 4c06b28d4ac327e4855e9589d4709a415f39a97c.nq.gz
    ├── 4c2659032526d83e4a1afccbdd947d5aa809f3dd.nq.gz
    ├── 4c496653150a0c8b51e32f98e0ef177564a836f2.nq.gz
    ├── 4d4b03cc62937604cc95973d6f1abcf00e12322c.nq.gz
    ├── 4d5b9f296bcfcd266fff8167d42ee29e98c462cf.nq.gz
    ├── 4e28fe7b917bb45585b32bdbc2af9a798991b904.nq.gz
    ├── 4e36a0e42b29acc8797eb2ec58dd0e825010ef78.nq.gz
    ├── 4ec14bf01a75280633cdcc6f8010d98f6e434e23.nq.gz
    ├── 4ee068449a90dcfc691e5b2fb34c936b9527cf6d.nq.gz
    ├── 4f351947dfa9e046a8e6173ae90e2d74114c3842.nq.gz
    ├── 4f3cc3f73871e54c4bbe7f78376befdcee909b97.nq.gz
    ├── 4faeb3c150fd76203023e9d36a23b95057868653.nq.gz
    ├── 51037e499b2a466e4cfe3a624baad97eeeeef247.nq.gz
    ├── 5264813bf7507e6a68ca4bc5cb7673901851b2be.nq.gz
    ├── 5264d1881e006ce8f0c39688074d962cfd27567c.nq.gz
    ├── 53f91d9d347b62443aea04d089d3131a9187bc51.nq.gz
    ├── 542b174c4cba619ee8f322a7d80cd929405632c9.nq.gz
    ├── 543c678dda3b73fd6958443149b994086e51f876.nq.gz
    ├── 54518e682af9b9969995871f5a924c26e63e9b34.nq.gz
    ├── 55476ecb34d958f9fb5250fa5eb502257cb7ae17.nq.gz
    ├── 55bdab6c9667436fee5ac0727621e2c4b0fe2a05.nq.gz
    ├── 56827a552f7665118c2f21b186920b8509175705.nq.gz
    ├── 57d55ffb95c1c88c1cdaea7d27adfd83b09b4c12.nq.gz
    ├── 57fac1b44391568708814259ac4b37b6c57fb1ca.nq.gz
    ├── 59cd5ed5d3d865297309657d29f5f1d7a008bf06.nq.gz
    ├── 59dcc4c6c864cf61734f0faf346b09ead10ff652.nq.gz
    ├── 5b098cfac5fb3f1ce78dd11fbf48c74c45cf3768.nq.gz
    ├── 5b11b845fe5a4ac98decf294fd10393fb4cc5a20.nq.gz
    ├── 5b3da5cff92993e486cdb295d12f7265aa2f8b61.nq.gz
    ├── 5b7bbe165b912ea790055db3f2420510758f464b.nq.gz
    ├── 5bde6bde2774e6e41ff65590387c17396cbb3c69.nq.gz
    ├── 5be607f6b25babe7b4302dcce2ea15c6ddf96d11.nq.gz
    ├── 5c9bff756a2407dc4312fb7496ccae17f70ccc45.nq.gz
    ├── 5cb5fb83faef3bf21084ccfff9845046b441f903.nq.gz
    ├── 5d45db19a149637630f6b49cab60b22c230a2d8a.nq.gz
    ├── 5d60fff5dbf3b96ca09d3e461ef35b2342b6a8d0.nq.gz
    ├── 5e1bca569ac5acc248106a7fecdebbd5460db4e3.nq.gz
    ├── 5e8b2da0ddff0f3ec4fe697ac96b979dd06c72be.nq.gz
    ├── 5f0c723c3f6b29247c4fe6d3d57ff2bdbf0737d1.nq.gz
    ├── 5ff5354d31baec5e13658deb2449b1fb5d74aef9.nq.gz
    ├── 621479b769ed4f5e680a9fc1b37779cde64433a0.nq.gz
    ├── 623efe4236d6a13b8203c728cf707808bcffc014.nq.gz
    ├── 62477be13b868abea6b1df463a2a6ca901d32334.nq.gz
    └── 628e54be5f6727bfe8731abbba5490e2f03b1003.nq.gz

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

[pymc-devs/pytensor](https://github.com/pymc-devs/pytensor)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
