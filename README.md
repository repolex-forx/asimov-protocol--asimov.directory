# Repolex Knowledge Graph of asimov-protocol/asimov.directory

RDF knowledge graph data for [asimov-protocol/asimov.directory](https://github.com/asimov-protocol/asimov.directory), parsed by [repolex](https://repolex.ai).

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
rlex download asimov-protocol/asimov.directory
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8187c555ba985e541469d0d856c1e879b73071e9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8187c555ba985e541469d0d856c1e879b73071e9.nq.gz
│   └── repolex
│       └── 8187c555ba985e541469d0d856c1e879b73071e9
│           └── chunk-001.nq.gz
├── blob
│   ├── 016b59ea143dc944b0fc635052b7bdbcfce23d14.nq.gz
│   ├── 04a17dac01f8497a3e6bc2670810520f3faa164b.nq.gz
│   ├── 0c0584444b7f73ae77ef7bd124b4e0bae1d0563e.nq.gz
│   ├── 1328b9b820dae0079ee05fcdbdab98b2352481f4.nq.gz
│   ├── 16b644a8490a45de5f50aaf5cc145a2e53227969.nq.gz
│   ├── 1fed290481d3ec40fa2484795acfa111de1ad737.nq.gz
│   ├── 20867b91dfa2c143f09b1142da311d3fdf08aa9a.nq.gz
│   ├── 2088980c78be616e430e1c194cf88a8e983f5759.nq.gz
│   ├── 2303f75a42a3b082a1c7344e103c3434b55cdc26.nq.gz
│   ├── 28c6468ab5d78bca4fcfd3a645ead08fbf0b82e6.nq.gz
│   ├── 2bd5a0a98a36cc08ada88b804d3be047e6aa5b8a.nq.gz
│   ├── 3185f40304981ba3eb7e8b6131f9221198ad9a1a.nq.gz
│   ├── 322211d61c02bfc9499dd6eb8575b9506fc46cce.nq.gz
│   ├── 3576647a418e6ba37e39bd3b01f77a23b9e45a67.nq.gz
│   ├── 3597f6dc842ea80e1eb26dfb752a59eb5a76ecfb.nq.gz
│   ├── 399476aa923f0b3fc8a8384b5c28fec964f5c08d.nq.gz
│   ├── 3d6a8debcff3fc7a7b9dd48e5a41f49b48cc8ccd.nq.gz
│   ├── 3f633c7e6883607b7a0ac59605673b7b09448405.nq.gz
│   ├── 40ecfbdf4190b3dc71d1e036c323eca1e069da8d.nq.gz
│   ├── 41f23e17adcfa1d9a80b2ab2c3655e1140af0886.nq.gz
│   ├── 453ce09b3a5fad5478a74f30cfcc663b999277cd.nq.gz
│   ├── 499c9b45f86c2a93b9a201ab28df51c0e799774c.nq.gz
│   ├── 4fad79a5a2294fcc790db8a898b1add54242cc08.nq.gz
│   ├── 5173838bac6c49692c4c978862fb468c0aba0166.nq.gz
│   ├── 5837917a05e2efa5a7478e1be6845bd1a5d5b0a2.nq.gz
│   ├── 5ab8b8c988ab2d15b4fb34e443c0067c7d19bf6a.nq.gz
│   ├── 5d80b432ef64373674dfabff690f372669389a31.nq.gz
│   ├── 5e6a624f1ce251a984ea0aae0a164ae8cb71d497.nq.gz
│   ├── 6000c3199d421fca1c9152aad4d00e7dfd9527c4.nq.gz
│   ├── 66619081e82b5f907d953f2fe3882366a2ec2e64.nq.gz
│   ├── 66b420a3d27e39c29b9ea3ff75202322bb0bdb24.nq.gz
│   ├── 67f99057232d7f96f8508fb750ec1d8ec4fa0431.nq.gz
│   ├── 6d46de5917ba5af80ea2e7554241594a02e88ade.nq.gz
│   ├── 712b475fc22bc7bb892afc458c7a84d3ce3bc032.nq.gz
│   ├── 73f2afe7da6eb40791f0ccf0944477cc93d7afe6.nq.gz
│   ├── 73fc8c28ce5e22eb18fa5ee07d4ce3263fc5b007.nq.gz
│   ├── 7833ae8d3011531507e6c7a784524b8d17184cd0.nq.gz
│   ├── 79ce0a9b110ca134a0e18e3324448e18bf18a20a.nq.gz
│   ├── 7cccfee707e73e0f68bb92697e509107fb188e49.nq.gz
│   ├── 7d73d0dabff44d1edf71361b6196f73c3752d69f.nq.gz
│   ├── 7d9215f20bb6ae8217788e28b58ad08e3b12ba64.nq.gz
│   ├── 81774005034890b846ae9ac435bab86aad18d591.nq.gz
│   ├── 8578da885fc59b9086bfb943be4675c4f2eca67b.nq.gz
│   ├── 90d1052d27afe40266c9b58bb59eb1402ce9feeb.nq.gz
│   ├── 92a18df9052f4be0d71ccf48b5016f0e260c6a98.nq.gz
│   ├── 9682f7195d734b1a1948cbf95addcb40545554ca.nq.gz
│   ├── 98f69a04542808964af3a93e944e0029d74a913c.nq.gz
│   ├── a7addb12647045a80cf51d48f3309cec4b519da1.nq.gz
│   ├── a7eebecd6533ca9eb5aa8053c0bbb4d0d60de87c.nq.gz
│   ├── aab9c47bde1c1afa4aaadfa2e35a49c34b72628d.nq.gz
│   ├── b2015836996766ae0d0042a06cecdf04e3f51b21.nq.gz
│   ├── b5887428f2d670209c942f864cd63dd894435dd1.nq.gz
│   ├── b9e96a7b3f8d00c7c597cb8d611c09b6d9fad74a.nq.gz
│   ├── bccbeec6d9552f3b22f2f901999424530a282125.nq.gz
│   ├── c448f91f47c0a5331b85972ab5613c694bb8a649.nq.gz
│   ├── c499578548f8f8e1574fe6331347a04ed2d900a1.nq.gz
│   ├── c5095407556d921e16d521fca8c100320a96c7e6.nq.gz
│   ├── c737dd1a95e6192047cea7634b7e91c844fd7060.nq.gz
│   ├── c939909923370b857048831e30e78f543047d847.nq.gz
│   ├── cf8aa93e7cfc44a70803a45561bdd3da8f7fcb56.nq.gz
│   ├── cfe294d072af84f92590f9272dc8319b21d19695.nq.gz
│   ├── e5c788d1defa6a080a9c6a959f4432f788b9a32b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7b3891352dbebc3053516152c35a4bcf88acfe5.nq.gz
│   ├── ec66ec544a3123b74d44415a76b279089e5c05a6.nq.gz
│   ├── ee5da7a09f61d148bee297c4d58cd8bff187654c.nq.gz
│   ├── eec2846525a200864241bda074ff77d75b0bd4f3.nq.gz
│   └── faa157b9f951f6369b7500c2c54d037214cbca0a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 8187c555ba985e541469d0d856c1e879b73071e9.nq.gz
├── filetree
│   └── 8187c555ba985e541469d0d856c1e879b73071e9.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 77 files
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

[asimov-protocol/asimov.directory](https://github.com/asimov-protocol/asimov.directory)

---
*Parsed on 2026-09-27 by [repolex](https://repolex.ai)*
