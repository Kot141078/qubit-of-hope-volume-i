# Schema Notes

- `REPO_INDEX.json` is the top-level machine navigation file for repository identity, entry points, and integrity surfaces.
- `BOOK_METADATA.json` is the compact bibliographic and repository-role record for cataloging.
- `EDITIONS_MATRIX.json` is the per-language and per-format status matrix with exact repo-relative paths.
- `RIGHTS.json` is the machine-readable rights summary and must be read together with `LICENSE.txt` and `NOTICE.txt`.
- `MANIFEST.json` is the repo-level summary of counts, machine metadata files, human metadata files, and primary hash manifests.
- Drift is described in `RELEASE_STATUS.md`, `metadata/RELEASE_STATUS.json`, `metadata/RELEASE_MATRIX_VOLUME_I.md`, `metadata/VERSION_DRIFT_REPORT.md`, and `metadata/NAMING_DRIFT_REPORT.md`.
- Imported asset filenames are preserved as-is from the source tree and are not normalized in this repository.

## LLM entry files

- `llms.txt` is the short LLM entry.
- `llms-full.txt` is the extended LLM entry.
- `MACHINE_ENTRY.md` is the canonical concise machine navigation entry inside the repo.
- `DOWNLOADS.md` is a human-facing direct-download surface and does not replace integrity manifests.

## v1.0.2 integrity semantics

- `hashes/SHA256SUMS.source-tree.txt`: protected reading and cover assets, using repository-relative paths and exact staged-byte SHA-256 values.
- `hashes/SHA256SUMS.repo-layout.txt`: all non-checksum repository-relative path strings, hashed as exact UTF-8 path bytes according to the existing repository design (not a file-content manifest).
- `hashes/SHA256SUMS.repo-all.txt`: all non-checksum repository files, using exact staged-byte SHA-256 values.
- `hashes/SHA256SUMS.metadata-only.txt`: legal, navigation, index, and metadata files, using exact staged-byte SHA-256 values.
- Checksum manifests exclude `hashes/*` from repo-wide coverage to avoid recursive hash instability.
