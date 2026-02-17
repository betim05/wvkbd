# GPL-3.0 Compliance Notes (Fork Maintainer Guide)

This file is a practical checklist for distributing this fork while preserving
GPL-3.0 obligations.

## Project License Layout

- Main code license: GPL-3.0 (`LICENSE`, `COPYING`)
- Included MIT/X code: `os-compatibility.c`, `os-compatibility.h`
  (see `COPYING_WESTON` and `COPYING`)

## If You Distribute Source Code

1. Keep `LICENSE`, `COPYING`, and `COPYING_WESTON` in distributed copies.
2. Preserve existing copyright and license notices.
3. Mark your modifications clearly (date + author + summary).
   This repository uses git history plus `NOTICE` for this purpose.
4. Do not add extra legal restrictions beyond GPL permissions.

## If You Distribute Binaries/Object Code

In addition to the source rules above, provide Corresponding Source under GPL-3.0
terms (for example by publishing the full source repository for the exact build
revision, including build scripts and interface definitions required to build).

Recommended minimum for binary releases:

1. Publish the exact source commit used for each binary.
2. Publish reproducible build instructions and dependencies.
3. Include `LICENSE`, `COPYING`, `COPYING_WESTON`, and `NOTICE` with artifacts.
4. Ensure users can obtain the complete corresponding source for the same
   binary version.

## Warranty and Liability

GPL-3.0 is distributed without warranty unless explicitly stated otherwise.
Do not remove or contradict warranty disclaimers from license texts.

## Practical Fork Policy Used Here

- Upstream attribution is preserved.
- License files are kept intact.
- Modifications are declared in `NOTICE`.
- No upstream repository history was rewritten.
