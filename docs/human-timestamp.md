<!-- Derived from Eugene F. Barker (github.com/genebarker/standards) MIT -->
# Human Timestamp

Prefer the use of a human friendly timestamp like so:

    2022-03-25-1503

Where the form is `YYYY-MM-DD-HHMM`. The `HHMM` uses military time. So
in this example, `1503` is 3:03 PM.

## Thinking

- The form is easily recognized and understood.
- The form is friendly for digital use (has no spaces and sorts well).
- Seconds and timezone are left out because (1) they are harder to read;
  and (2) they are unnecessary in most cases.

*Adapted from [shrikenet][1] by the same author.*

[1]: https://github.com/genebarker/shrikenet
