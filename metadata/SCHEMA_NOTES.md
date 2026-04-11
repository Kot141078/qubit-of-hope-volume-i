# Schema Notes

- `REPO_INDEX.json` is the top-level machine navigation file for repository identity, entry points, and integrity surfaces.
- `BOOK_METADATA.json` is the compact bibliographic and repository-role record for cataloging.
- `EDITIONS_MATRIX.json` is the per-language and per-format status matrix with exact repo-relative paths.
- `RIGHTS.json` is the machine-readable rights summary and must be read together with `LICENSE.txt` and `NOTICE.txt`.
- `MANIFEST.json` is the repo-level summary of counts, machine metadata files, human metadata files, and primary hash manifests.
- Hash manifests mean:
  - `hashes/SHA256SUMS.source-tree.txt` = imported asset set in source-tree layout
  - `hashes/SHA256SUMS.repo-layout.txt` = imported asset set in repo layout
  - `hashes/SHA256SUMS.repo-all.txt` = full repository contents excluding `.git`
  - `hashes/SHA256SUMS.metadata-only.txt` = legal, index, and metadata files only
- Drift is described in `RELEASE_STATUS.md`, `metadata/RELEASE_STATUS.json`, `metadata/RELEASE_MATRIX_VOLUME_I.md`, `metadata/VERSION_DRIFT_REPORT.md`, and `metadata/NAMING_DRIFT_REPORT.md`.
- Imported asset filenames are preserved as-is from the source tree and are not normalized in this repository.
