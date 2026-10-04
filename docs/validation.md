# Validation record

Date: 2026-10-04. Cleanup baseline commit: `fd8465c40ddc4a8ce536cba5051edd8d2d650680`.

## Preservation and structure

- 302 retained blobs are unchanged at their current paths.
- 35 generated build/cache/executable entries are omitted from the current tree; the baseline history remains available.
- New documents and required configuration/path adaptations are recorded in the cleanup pull request. No existing source history is rewritten.
- Current filenames have no case-insensitive collisions. Markdown file links and generated-output ignore rules are checked before publication.

## Checks and limits

- Retained source, image, experiment-data, note, and historical project blobs match the originals.
- No unified build is provided or asserted. Individual files may depend on Linux/Windows APIs, external headers, original encodings, or unfinished exercise text.
- The cleanup does not claim complete solution correctness, comprehensive testing, or portable execution of all files.

