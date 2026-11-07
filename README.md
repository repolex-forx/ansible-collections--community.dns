# Repolex Knowledge Graph of ansible-collections/community.dns

RDF knowledge graph data for [ansible-collections/community.dns](https://github.com/ansible-collections/community.dns), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.dns
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 81b2f7d9ef881ca09bc5df26f1c3abda7c959665
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 81b2f7d9ef881ca09bc5df26f1c3abda7c959665
│           └── chunk-001.nq.gz
└── blob
    ├── 012065c8539f2bd3e61eecc74acf5a046956de40.nq.gz
    ├── 0291ae66ae9473fec94daeb0bbaba1333a416a23.nq.gz
    ├── 04574128be4d716b8967f49b80d012a238b952b9.nq.gz
    ├── 068768fb51d69200a742f059d80bf8ec065b218a.nq.gz
    ├── 06e6fe6bed9197fad56c1480f844379a0ec0c76f.nq.gz
    ├── 07579b3ec3099ce000319ac6ef7aea7eefb09faf.nq.gz
    ├── 084f266cb923e14ca87b34b327cabecf4b949c11.nq.gz
    ├── 0895763cac64276a295c2446fd33acdaba9a2a63.nq.gz
    ├── 098e078aa44af361ce2d6231ed624d9e9b33caa3.nq.gz
    ├── 09c2c7a44c9839a266a8e391904ee972f4d5e7d4.nq.gz
    ├── 0b61be1680b13e9c19e425b9e482d80d4c865d06.nq.gz
    ├── 0ecde6d5886dec7e3ddb1342bc3c85d22e741cb3.nq.gz
    ├── 0f0ca440cef4b5b8995aae6b6d319fdc37eec148.nq.gz
    ├── 0fc1a5554a463809a146b096d9548fbbc4e6a7b0.nq.gz
    ├── 10143c4f006b14c60eec08690feb57619b99e411.nq.gz
    ├── 107fe125698754beed8efddf473a003bdc2a80d7.nq.gz
    ├── 11f58fddcadad91b8517d81ba9fd0059a383dbad.nq.gz
    ├── 12cfd7e739b4cc43f9c4d4dfd885a59a26b00204.nq.gz
    ├── 12f1ace7364621f7a2928c7564f834f442c1f818.nq.gz
    ├── 17250ecea539259b64d6a4e3477b6ff886fd3f69.nq.gz
    ├── 1af3f87226c91520671a4e1d00a0babace14c317.nq.gz
    ├── 1b641c44745b880ebf617a3ced234118193a0201.nq.gz
    ├── 1d6cf8554ada641c9a963a6f986822bf4be2da9d.nq.gz
    ├── 1d86ed3568d55d6ee54c0867db20482ff94bf21c.nq.gz
    ├── 1db997043fc0f4581fdee842905f4d4721c42606.nq.gz
    ├── 1e20ec09f56cebd9f33501b4a4e2398ec23e6622.nq.gz
    ├── 1f30a5c8583c2f61b0a2cdc8b9358e9893b3aadf.nq.gz
    ├── 1fc6d29a809c304f49bc061a218e6fdabc51b4c6.nq.gz
    ├── 1ff1d4e274505f8b9c496c83d4a9f2cd44402269.nq.gz
    ├── 20fd75046a5556dbc0cd2a7d9ca4196e7bfb79fe.nq.gz
    ├── 22582d06d474a62da9c9a475918317440782a18a.nq.gz
    ├── 2345e5bf97ac9332c1a61a251c197c83a198bf14.nq.gz
    ├── 23c38dd88a31c77caace3e20a798aff13c3174ad.nq.gz
    ├── 2508a500dcd38eb54521bc5759603e8f56ca2843.nq.gz
    ├── 256f6cfb0f36aa2d04c15906824c2d115a1bdd6b.nq.gz
    ├── 26a320da5236c81aee51e037e9ed413d0c9aaad2.nq.gz
    ├── 26b92747221e4640b9f94454a0dafdfe54fba3ec.nq.gz
    ├── 27f27b5b13575eb478c70f89593a39602b45ae9e.nq.gz
    ├── 29474a8ef50f898bbf9c1ff3eebf4cf6daa185cb.nq.gz
    ├── 2a6105486ae2c4e39ff7e236575185fc06c21a2a.nq.gz
    ├── 2dcea86a8f036e77a30860b2279502ba2448ad9a.nq.gz
    ├── 2ec644a7adc0a4c6e6ea93b2f5f9da7411670103.nq.gz
    ├── 3175674dc1e0ef160ae323e1e6c9fbf051b8e29f.nq.gz
    ├── 33054ccfae6003c13a1dc037f787b605e779375c.nq.gz
    ├── 330b734dca1a6692ecf76943f6d4c0aafd4149a0.nq.gz
    ├── 33f2835b4cc3a6e0b7e8ff5e35c5310ed94d8ab0.nq.gz
    ├── 343879b242b3341c9e89933ef78ccd7842fa167a.nq.gz
    ├── 350c6bcedc7a6f769f3f8047c9c5077e08937cf7.nq.gz
    ├── 355754023b8debff24f5a463355a16bb06f002b6.nq.gz
    ├── 35aa690a6d96539b2c94e4789df5ddf04e83c53f.nq.gz
    ├── 36183fe176e0c97f192927e1faaa55c9113942ce.nq.gz
    ├── 38590f2e4ec486212f404e5f1405e69f7ec27db8.nq.gz
    ├── 39f93e91bf4b3f65c0c100e817427825d55c71aa.nq.gz
    ├── 3b4d074a837ea970b073c173ed28666972a2ca2e.nq.gz
    ├── 3c62eab04c62304f63f471c6ebd4adf223ac6fe6.nq.gz
    ├── 3d0a4def7a91de1ada5fe1dc7655084b6e12c0b5.nq.gz
    ├── 3e12a50f3dc9fa83b8a15bd3b6d6104f8350c8a0.nq.gz
    ├── 3e469b26ccf55a9107754f22c07f472edbfaa6a3.nq.gz
    ├── 3eeb82e99d6c2fa75f3f1c1f4507edd4fb0e1291.nq.gz
    ├── 409168b44a85c3b63162a357e5e353d294809f53.nq.gz
    ├── 40d4f05133af2d41842dc2bc61ff7b088cb8ffa8.nq.gz
    ├── 41fd60638832f7d9b8aac98e1c4116a630f59514.nq.gz
    ├── 433856e955a97f343d7ebfee6e76afbb37f62103.nq.gz
    ├── 4487a1d958f5266054d6f76e9776a0004d452758.nq.gz
    ├── 46e535b522c5ccd902990381d7447984d091120e.nq.gz
    ├── 4709d57633832d7484353219efacf8f47cc7c6e3.nq.gz
    ├── 480d388be732d3cd0de4e3b9328a02ff81c4431c.nq.gz
    ├── 49410695e0c47e69e5e8d929d0fc3486b8ff4236.nq.gz
    ├── 497dec43ba19ea875434bd3781e284c1f6d40aff.nq.gz
    ├── 49c7e96f645577fb82b85e8df40f1d0c62d017b6.nq.gz
    ├── 49ebf22001d5f82c8a4e352cd84b71ecc3d2861a.nq.gz
    ├── 4bf85002f99656eff787191428872d5858804906.nq.gz
    ├── 4c819340d827220b63679ba23f8e67575f2dbe2c.nq.gz
    ├── 500eaf0ff5c70ea72c3552901ca0fc521d2e78e4.nq.gz
    ├── 503c2997b5096cc137d9d11bb2b574bb43f386a5.nq.gz
    ├── 5216afbac5a12d22c60ac03dcf8c807d4945f69d.nq.gz
    ├── 539f8adeb49b92b0d8032b9d7f227d82828c3d10.nq.gz
    ├── 53f1c72a43218c31ef401d08d7ec89ccfc76454f.nq.gz
    ├── 5477808fe8ff621a6be96415d3a0250cbbc9d8ec.nq.gz
    ├── 54bb0429764d1c4c51d4f91b4ef4f862cefa0b18.nq.gz
    ├── 54d4159302c15d6c9fc5f54528a51e0d66025201.nq.gz
    ├── 56c8cfbcab8e5a2fcf85921a2bb5ad9cde5ecee7.nq.gz
    ├── 59c8a9955c0733b54129667c9ca77f3c6801f859.nq.gz
    ├── 5b79a61294b0e109c526b3dcf9d5547ed99e8a0c.nq.gz
    ├── 5db0a79a745b950db2bbc5bf0ac2b649fc255d6c.nq.gz
    ├── 5df3b81ce1e10150d9b0d68453446faefd49c53a.nq.gz
    ├── 5e6d0a32e582ccf97ab06733f5deaaf4721d8292.nq.gz
    ├── 5ee7812edbb236187b2434d8d01342f71c10b922.nq.gz
    ├── 5f7f23331e3ba21d001e88e0f8b9bd71c2368a1a.nq.gz
    ├── 60287d54c16d08d01e5e21113dceb171253a4f98.nq.gz
    ├── 60318f105e6c17912277418a195d30a935724348.nq.gz
    ├── 60ee1e72067625d467333cc6b78ad28766882c8b.nq.gz
    ├── 632b35c770b32c30886ad6753ccc7f376e2bce83.nq.gz
    ├── 639cd2390b34d750f3fca05caa6155eae13b40d8.nq.gz
    ├── 63b6bc8a3682394fbf352e5675a6dc0e06a5db35.nq.gz
    ├── 63cba8a31ba0aaa349b04e00ce4f1381c8071317.nq.gz
    ├── 6457c1341bc1910ffb91b2566015fe6d9abecfc8.nq.gz
    ├── 6664deecd1f885a11bb78a31aaeff9fea5193bdc.nq.gz
    ├── 67017cb147735ce14638e3e493391b9d8199bf8a.nq.gz
    ├── 673404a652e9c26319ed0e3137fd5ec720c6c58d.nq.gz
    ├── 6c794df2a393b04cb4dab4a095afb4566a08c55a.nq.gz
    ├── 6c97f750e37b976abcff81ffea1815fddf33bd36.nq.gz
    ├── 6dbd405887c3735268e9e562479b658970eb6eda.nq.gz
    ├── 6dd02704e0020891948b94a726e4a422f118fb59.nq.gz
    ├── 6f549566b06461204f6994228b0aab787e6f132a.nq.gz
    ├── 70926b878558b8dc0e0b257aee180ec5fc7e6861.nq.gz
    ├── 7371d04656c8461a833f139d461785a383ea45e4.nq.gz
    ├── 73c5a1824768b2bcedb9b598c7024b3793ebff41.nq.gz
    ├── 748bdaed2dd02f30800322107b82f215de30eadb.nq.gz
    ├── 74fe1d580941f76d5d6d91e9194583150c57cf47.nq.gz
    ├── 760129f97aef9ff51896c4b8d4bb308f69ccd52a.nq.gz
    ├── 7664c26f93de8303933d15b5997734bc650d7e08.nq.gz
    ├── 76d63c340c64d0d1d5e1a0de824f99bc0850a0e4.nq.gz
    ├── 7a9c3f06b18a030275680eed55787e15f46dbb03.nq.gz
    ├── 7b22ce344d9da146684968c13d8d49b8cbd17dae.nq.gz
    ├── 7b8471d4722a78203dce74b007aa3b98009168f9.nq.gz
    ├── 7d0a13531100cc6c1915206dde1b69aee60ada3b.nq.gz
    ├── 7de635a3d0fdce8cf50d50f3f34a2d82db66abcd.nq.gz
    ├── 7f750ccad13903079035d57338407b1eaab965f7.nq.gz
    ├── 81c361019bbc1bfee052564e7a9f0610f1734a58.nq.gz
    ├── 83292039ded1eaccf755b47da6f75dae8ee1518f.nq.gz
    ├── 839e723f8ae91ec4faaabf7c5f50b95dc1fc5fb9.nq.gz
    ├── 86174aab9e4ef1ef8613bc2e1b9849db7488b1ea.nq.gz
    ├── 86fea8ff541f1f11c9d8271e050da74af788b806.nq.gz
    ├── 8c2aef4445b21d8aadc40a53bb8f750b12da2d7d.nq.gz
    ├── 8c6d654735cfe9f098bcb5d54c2507da0554b5e0.nq.gz
    ├── 8c7e2964555fb6e00cb3208cf9e8181f6a135b2f.nq.gz
    ├── 8cd10312f619e50ad6e6aa7f06197131a26f1a26.nq.gz
    ├── 8e121712f9077dfe3c2e3ddd92c1ed5453790bb8.nq.gz
    ├── 8f42db74fe41df111390a0dbe0f9f5ef933bb714.nq.gz
    ├── 908636d5193fb5e6fdd8d85560afa867adc80516.nq.gz
    ├── 93ade4823453cf92603a68f639d82799b13334d7.nq.gz
    ├── 93effa6f0c3db148f6a8bc3f073c7c34c7e7611d.nq.gz
    ├── 94e5343d7431dba4e9bf402552176941bb5a565f.nq.gz
    ├── 9509a291dcd23535d0e9bdb90dacc42765211488.nq.gz
    ├── 955a9bcf1811717e3a2cc0ffd288a1c01d1f8b61.nq.gz
    ├── 95dbdc8b2fd4baa31565598926b47df1bfd30fc6.nq.gz
    ├── 98c6c5063a51fdc6eab87b83e9f1c84ee890d33a.nq.gz
    ├── 9953028267caac44505eac0a8332da67034b2136.nq.gz
    ├── 9ac6164069322a7882bf1b98408b7bbc0de8c3bf.nq.gz
    ├── 9bba87ac88a490f4cc9d41e579e47f7b2ed27c08.nq.gz
    ├── 9c8e600ca60a43f876b80f2331742cc2cd23aa84.nq.gz
    ├── 9cb6c0fd4dd1cc60a9104cbd01f195cc83d3ca58.nq.gz
    ├── 9d54cd9925e8380fff69702bd33c6de60e07a60a.nq.gz
    ├── 9ddffff90fa7eae12b39dccd16e61c9e1e37817b.nq.gz
    ├── 9e26b90a8e0aff67095aafcb5dad5efd3871c3d9.nq.gz
    ├── 9ea5ee74ac23868b32f4848ad7ab162cfe56a7dc.nq.gz
    ├── 9efa2991e72f777527327344d2720f1f2ae5ee01.nq.gz
    ├── a1483ecbc053aaed91a59d7677648ae33b177c19.nq.gz
    ├── a530adb6193a03e45c8ce1e8ecaf33a53235d97c.nq.gz
    ├── a612ad9813b006ce81d1ee438dd784da99a54007.nq.gz
    ├── a68d7512a4844a4c816d41506ee4ab1426656a7e.nq.gz
    ├── a6a6f35dce68f88bae6f53af25829cec507f682b.nq.gz
    ├── a6d4a7ec35245bd8315d4a96f6c6a6d6a6a0b53e.nq.gz
    ├── a975922583783266821cb0528cfc7e86af255fbd.nq.gz
    ├── abc0d5476d7f9c84ed912c06a36589470b32a219.nq.gz
    ├── ac1a2fb6adcb426cc28b1c168bf97e97e8557d20.nq.gz
    ├── ac7ebac8af95dbb36c9bbee8cbf20c9d14ad197a.nq.gz
    ├── ada9b7463812f38c32c19bd720e51e6fc8c4f1d3.nq.gz
    ├── ae6ad3e127248eb3af4e07189713da67ea6b529b.nq.gz
    ├── b03778111f709467577b8e0ba8d15324ad63cbe9.nq.gz
    ├── b27f907da06bd32d607fe7f5aeacd2611a859441.nq.gz
    ├── b4cc1560cc8cc04eeeacbbf090773a93af1f4d0f.nq.gz
    ├── b57f5e9e964c5a112dc89d4d90fe8053aebc8e2d.nq.gz
    ├── b7a791a911b26139feeb585fb35f85e0fc1f3f03.nq.gz
    ├── b8b6be348162ddbfc5be63f39aaf865fa30ac440.nq.gz
    ├── b94dfff7acef4df0ccb51330ef2ee36757c17d0d.nq.gz
    ├── b96d5a24ed688987a77245ed5dc4c9952cf82843.nq.gz
    ├── ba1c375f3efa918ca035adeca8ba5ed69f05d43a.nq.gz
    ├── bb14e11cd0e551753d106ebee2b7db0f217a668c.nq.gz
    ├── bc1605bff69822b03a12070f15b0f252d91320d6.nq.gz
    ├── bd1f02444157711d0f84148e3ea7d7981aeb5736.nq.gz
    ├── bd3f33ab32b0af1b5c8ccb1d2d7ad9858ea888d4.nq.gz
    ├── be94c497139b143b168217d8c0650645f924007e.nq.gz
    ├── c02915a7cae025a3c6c9da0ff2d1a9dc71272dbb.nq.gz
    ├── c0e3334807db97fa1003906a9883b7d692b02d03.nq.gz
    ├── c247d43afacda093ad6d1a01f3ecf12b902a26b3.nq.gz
    ├── c35c02055cca1e2a083d8ffcdab904922b017bf3.nq.gz
    ├── c3a52f5d1b7d516d14f587351045b6a0f77736c7.nq.gz
    ├── c42274718f69e15660e198a83c035f2b1b52104b.nq.gz
    ├── c48e8440ecae786c42fe84758955b5788c7a9473.nq.gz
    ├── c68c4f3f07c47f909da905babe9d0fd89dec6e34.nq.gz
    ├── c7dbcfec4477f3ebd924010346f7a38592b0cc11.nq.gz
    ├── c9247883b779e62ec2c1de94a74adce91dc9c9fb.nq.gz
    ├── c9712afd6cc5d288d184ad9a3e1d497735b74111.nq.gz
    ├── c9af5ca28314fbe0d5c8eea2c873eb2d3f867baa.nq.gz
    ├── ca642f527fed3141cdd9edf2928544b0d0e1b726.nq.gz
    ├── cb6632c8f53d595311bfcf9ae0d5fe64f2c016ab.nq.gz
    ├── d1d98e1f6fd5490979d0ee7a4b61644dcb5bdc55.nq.gz
    ├── d21ec747c081c84e09289cd258f002676ecb062c.nq.gz
    ├── d225e0ac036f19b000dfa0af7ab026d292f1f07d.nq.gz
    ├── d23d6f7e2ae46d282959325e0f144ea71d012104.nq.gz
    ├── d38952ead04b8ef44837fa12e9111b74ffdc4912.nq.gz
    ├── d82ea1412646ee974035652b520b69e820730900.nq.gz
    ├── d9391e51a03eb8501e8935c87fb0d8a7daaef34e.nq.gz
    ├── d960564579e3f9b384d9a7ad766407fa3851123d.nq.gz
    ├── da2ec3e5cebf24fb9a4ab4b384f3c28fbb253ab8.nq.gz
    └── dbbcb46c22bfcec41d98fe888d5ec586ffa46cea.nq.gz

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

[ansible-collections/community.dns](https://github.com/ansible-collections/community.dns)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
