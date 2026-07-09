<!-- Derived from Eugene F. Barker (github.com/genebarker/standards) MIT -->
# Summary Usecases

A **summary usecase** describes how several usecases work together to
achieve a larger outcome, rather than a single interaction. Cockburn calls
this a "cloud" or "kite" level usecase, above the normal "sea level" one.

Mark one by suffixing both the filename and title with `-summary` /
`(Summary)`:

    045-renew-company-summary.md
    # 045 - Renew Company (Summary)

Do not also add an inline marker (e.g. an HTML comment declaring the
level). The filename and title already identify it unambiguously.

## Thinking

- The suffix shows up in directory listings, git diffs, and rendered
  titles alike - one signal, three places, for free.
- An inline marker duplicates that signal without adding a capability.
  Add one back only if a second altitude tier (beyond summary vs. normal)
  earns its keep - not before.
