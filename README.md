# Repolex Knowledge Graph of ros-infrastructure/rosdistro-reviewer

RDF knowledge graph data for [ros-infrastructure/rosdistro-reviewer](https://github.com/ros-infrastructure/rosdistro-reviewer), parsed by [repolex](https://repolex.ai).

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
rlex download ros-infrastructure/rosdistro-reviewer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 15f4131c6e854dda1f08a9748ed6c660c78da055
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 15f4131c6e854dda1f08a9748ed6c660c78da055
│           └── chunk-001.nq.gz
├── blob
│   ├── 056d9ce7166509335b0986fa4d42daee9c0cf0be.nq.gz
│   ├── 059223decf0fbd3547cea37b04d7a26289d84dc6.nq.gz
│   ├── 0aec02422ae8212633b4ced5e0ff5b319ad73581.nq.gz
│   ├── 1001f32510b169657e63e8911a65d5a947f6fc63.nq.gz
│   ├── 119d51c03748293f138b3e3264fb8602db6ca3f2.nq.gz
│   ├── 16f3e99b9fb75b3b7f7801907a263c3f39b95928.nq.gz
│   ├── 20f896fb65bb724a5518401a2d466163ba6b19ab.nq.gz
│   ├── 2384133c047999a6eb50517da8b6ca1ab4390418.nq.gz
│   ├── 23c4cb3b50919fe9d0ee76c19ecfdc907a84636a.nq.gz
│   ├── 23cf272f6e8168956e327d323010aba3b714e13d.nq.gz
│   ├── 2421e0367cecea989605f3e77624faabeb88dee7.nq.gz
│   ├── 24609c991b00e99827d4da85aab47f3d7c51f9fa.nq.gz
│   ├── 2a48511de59ea31a649f15914a7c5cada2deca09.nq.gz
│   ├── 323d01b7086f741da34826481f66d9433b656d2f.nq.gz
│   ├── 34c0545b25b7b0414022082bba508cc51e04ad98.nq.gz
│   ├── 374b3cd52d71bd4e637522ad903a49627c2580da.nq.gz
│   ├── 37d2f30551eb851ad3cf4ccec5180c78ecfee3b4.nq.gz
│   ├── 38faf5941b593b2930c67efee16e347e21a9ea4f.nq.gz
│   ├── 46e020615285e96398188d66a86fe002904b118b.nq.gz
│   ├── 4d168796a48e7e02eba281db7098e2cabd3bc786.nq.gz
│   ├── 4fb183d5f4edd6b381307f178c8576b8da0c13c6.nq.gz
│   ├── 538cb1e8437d5fb819ab86c5fa5f49e7d6a8d8e8.nq.gz
│   ├── 55c6e593d03bdc3a6f32383e881344e81c99a9d7.nq.gz
│   ├── 56fb47bc81a28ecc328870c144341a865d534e55.nq.gz
│   ├── 67744a2624f7baeab5c05151adea4db9ae38f320.nq.gz
│   ├── 691ce5dacbe485a367ddd0fe5144b2a159c509c9.nq.gz
│   ├── 6fd78d1e2d656e279869616b042aed721dd4ceb5.nq.gz
│   ├── 70c8ea8c296d3fcf5128245b377d11fbe224b15f.nq.gz
│   ├── 7ee305ad96697d00466968a58d919d1d1be701be.nq.gz
│   ├── 850c304129545a9b73443084ba3e9947c69ab301.nq.gz
│   ├── 8793c93d46839cff501c058a29fd184efb1c1640.nq.gz
│   ├── 87c736c276f05981d4bc7509250a7e2b09eaf0ef.nq.gz
│   ├── 87feeed7ee11d1973ab767ac54097dfb98fbf5bd.nq.gz
│   ├── 89d3db5d0f79dcc4c526f76c35a7db52287d2981.nq.gz
│   ├── 8bba33260b3e6786937c7d4612f84af46d9dc3be.nq.gz
│   ├── 8d315d51e4f6e4f533a08823b5cc3627e9540cc2.nq.gz
│   ├── 8fef3823dea17906272525331f38834b4bb7019d.nq.gz
│   ├── 91ea2e3c9e49dccc3abe298d4446734f467c504d.nq.gz
│   ├── a846db10880c25bc21828366a609f05da46d4ad2.nq.gz
│   ├── aa3aaf50d14b7bc2bac4223240184ac6a612460c.nq.gz
│   ├── aad7119d14495d486cce2965cea183c7a4c687d8.nq.gz
│   ├── b69c7eabff9f101092ebb0010eb14324a5ed73dc.nq.gz
│   ├── b762ee1a70536ef2490be7b71dbd440dbccb835b.nq.gz
│   ├── ce8d6f136097ba496cc79b8f62e1800371b4dcfb.nq.gz
│   ├── cea5d6d60b569b7f17e7aeea53a447ab2e4c1adf.nq.gz
│   ├── d048a7b913447ed422d05c0d94028aef493f2866.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d84983ca2b72e8fb2f0e47fe4254ca3d88f93442.nq.gz
│   ├── dd9a9970493345d408a890a7cdb88be10bc012e5.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── eee5fe63e9668e7c3f93c1ddd9f68d885ae1198e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 15f4131c6e854dda1f08a9748ed6c660c78da055.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
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

[ros-infrastructure/rosdistro-reviewer](https://github.com/ros-infrastructure/rosdistro-reviewer)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
