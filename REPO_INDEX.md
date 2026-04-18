# Repository Index

## Repository purpose

This repository preserves the currently available multilingual reading editions of **Qubit of Hope — Volume I** by **Ivan Kotov**.
It is a public reading and preservation repository with transparent documentation of edition drift.

## Corpus role

Role:
human-facing narrative companion / perception bridge for `c` as a new class of AI beyond purely instrumental framing.

This repository is the human-facing narrative companion in the same public corpus as:

- `Kot141078/advanced-global-intelligence`
- `Kot141078/ester-reality-bound`
- `Kot141078/sovereign-entity-recursion`
- `Kot141078/ester-clean-code`

Canonical context file:
- `CORPUS_CONTEXT.md`

Corpus-level references:
- `https://raw.githubusercontent.com/Kot141078/advanced-global-intelligence/main/CORPUS_PRIMER.json`
- `https://raw.githubusercontent.com/Kot141078/advanced-global-intelligence/main/STACK_LOCK_2026-04-12.json`
- `https://raw.githubusercontent.com/Kot141078/advanced-global-intelligence/main/CANONICAL_DISTINCTIONS.md`
- `https://raw.githubusercontent.com/Kot141078/advanced-global-intelligence/main/OBJECTIONS_AND_REPLIES.md`
- `https://raw.githubusercontent.com/Kot141078/advanced-global-intelligence/main/CITATION_AND_VERIFICATION.md`
- `https://raw.githubusercontent.com/Kot141078/advanced-global-intelligence/main/CLAIMS_AND_EVIDENCE_MAP.md`
- `https://raw.githubusercontent.com/Kot141078/advanced-global-intelligence/main/STATUS_AND_MATURITY_MAP.md`

Read this repo in two ways:
- standalone reading surface: `DOWNLOADS.md` -> `RELEASE_STATUS.md`
- narrative companion in corpus: `CORPUS_CONTEXT.md` -> AGI `CORPUS_PRIMER.json`

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
|-- CORPUS_CONTEXT.md
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
- `CORPUS_CONTEXT.md`
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
