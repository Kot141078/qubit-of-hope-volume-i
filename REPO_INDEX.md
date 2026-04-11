# Repository Index

## Repository purpose

This repository preserves the currently available multilingual reading editions of **Qubit of Hope — Volume I** by **Ivan Kotov**.
It is a public reading and preservation repository with transparent documentation of edition drift.

## Rights

This repository is public for reading and preservation only.
**All Rights Reserved.**

Authoritative rights files:
- `LICENSE.txt`
- `NOTICE.txt`
- `RIGHTS.json`

## Directory tree

```text
/
|-- covers/
|-- editions/
|-- hashes/
|-- metadata/
|-- BOOK_METADATA.json
|-- CITATION.cff
|-- DOWNLOADS.md
|-- EDITIONS_MATRIX.json
|-- LICENSE.txt
|-- MANIFEST.json
|-- MACHINE_ENTRY.md
|-- llms-full.txt
|-- llms.txt
|-- NOTICE.txt
|-- README.md
|-- RELEASE_STATUS.md
|-- REPO_INDEX.json
|-- REPO_INDEX.md
`-- RIGHTS.json
```

## Language editions summary

| language | status | notes |
|---|---|---|
| ru | provisional | master/source and some exports remain at v1.0 while fb2 is v1.1; Kubit family |
| fr | aligned | v1.1 across currently available assets |
| es | provisional | master/source is v1.0 while exports are v1.1 |
| de | aligned | v1.1 across currently available assets |
| en | provisional | master/source is v1.0 while exports are v1.1; PDF has copy suffix |
| nl | aligned | v1.1 across currently available assets |
| zh-CN | provisional | master/source is v1.0 while exports are v1.1; master naming family differs from export family |

## Metadata files summary

| file | role |
|---|---|
| `CITATION.cff` | citation metadata |
| `BOOK_METADATA.json` | core bibliographic and repository metadata |
| `EDITIONS_MATRIX.json` | per-language and per-format status matrix |
| `RIGHTS.json` | machine-readable rights summary |
| `MANIFEST.json` | repo-level manifest summary |
| `metadata/ASSET_MAP.md` | human-readable asset map |
| `metadata/ASSET_MAP.json` | machine-readable asset map |
| `metadata/RELEASE_STATUS.json` | machine-readable release status |
| `metadata/SCHEMA_NOTES.md` | schema and file-role notes |
| `metadata/SOURCE_PROVENANCE.md` | import provenance and hardening note |
| `metadata/HUMAN_ENTRY.md` | short reader landing page |
| `llms.txt` | short LLM entry surface |
| `llms-full.txt` | extended LLM entry surface |

## Integrity files summary

| file | role |
|---|---|
| `hashes/SHA256SUMS.source-tree.txt` | hashes for the imported source-tree asset set |
| `hashes/SHA256SUMS.repo-layout.txt` | hashes for the imported asset set as placed in this repo |
| `hashes/SHA256SUMS.repo-all.txt` | hashes for the full repository contents excluding `.git` |
| `hashes/SHA256SUMS.metadata-only.txt` | hashes for metadata and legal/index files only |

## Canonical reading path

Start here:
- `README.md`
- `DOWNLOADS.md`
- `RELEASE_STATUS.md`
- `metadata/HUMAN_ENTRY.md`

For the cleanest currently aligned reading bundles, begin with:
- `editions/fr/`
- `editions/de/`
- `editions/nl/`

For provisional bundles with documented drift:
- `editions/ru/`
- `editions/es/`
- `editions/en/`
- `editions/zh-CN/`

## Machine-readable companions

- `MACHINE_ENTRY.md`
- `REPO_INDEX.json`
- `BOOK_METADATA.json`
- `EDITIONS_MATRIX.json`
- `RIGHTS.json`
- `MANIFEST.json`
- `metadata/ASSET_MAP.json`
- `metadata/RELEASE_STATUS.json`
- `llms.txt`
- `llms-full.txt`
