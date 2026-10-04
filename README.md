# Linux Systems Lab

A historical collection of systems-programming exercises and related coursework.

## Navigation

Start with `legacy/myshell/`, `legacy/process/`, `legacy/fifo/`, `legacy/ProcessPool/`, and the server/client source files. Other language, RP2040, numerical, and coursework files are retained with their original names. Linux-specific system calls generally require Linux; macOS is not a substitute for that environment.

```text
legacy/          Original source, notes, images, data, and project files
docs/catalog.md  Original-to-current file mapping and cleanup record
```

See the [complete source index](docs/catalog.md). Generated compiler outputs and editor caches are excluded from the current tree; original commits remain intact.

## Working with this archive

This collection is not one application and has no unified build. Select an exercise, inspect its dependencies and entry point, and build it in a separate project. Several files use Visual Studio, Windows APIs, GBK-encoded comments, or missing course-specific headers. Preserve the original encoding when editing.

Visual Studio project files are historical references after relocation and may need their source paths updated before reuse. Source names and internal relative paths are retained within `legacy/`, apart from documented filename conflict handling.

## Validation

The cleanup verifies preservation of retained file bytes, filename compatibility, and document links. It does not assert that all historical exercises compile or that their comments and algorithms are correct. See [validation record](docs/validation.md).
