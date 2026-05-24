<!-- Derived from Eugene F. Barker (github.com/genebarker/standards) MIT -->
# 2 - Adopt Usecase as Single Word

## Status

Accepted

## Context

A usecase is typically spelled as 'use case'. This project places usecases
at the center of its requirements and consequently its code base. The
widespread usage of this two word term results in unwieldy references in
documentation, class paths, and attribute names. Some examples:

- Please see use case #4.
- `/usecases/base_use_case.py`
- `event.source_use_case_oid`

## Decision

Adopt usecase as a single word.

In this project, a usecase is a well-defined term. Collapsing this term into
a single word:

1. Is natural (doesn't confuse anyone).
2. Keeps its usage in the project clean.
3. Establishes 'usecase' as a distinct noun.

## Consequences

- Path, file, table, and attribute names are concise and clean.
- References to usecases in documentation may appear _wrong_ to new project
  contributors.
