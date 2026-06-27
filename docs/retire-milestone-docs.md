<!-- Derived from Eugene F. Barker (github.com/genebarker/standards) MIT -->
# Retire Milestone Documents

A **milestone document** is one that helped the team reach a design decision
or architectural outcome, but whose subject matter becomes self-documenting
once that outcome is in place. User interface sketches and design notes are
common examples.

Retire these aggressively - every document the project must actively
maintain has a carrying cost.

Once the artifact it describes is complete and self-documenting, move the
document to a `RETIRED/` subfolder within its home directory and add the
retirement date and reason at the top of the file:

    Retired: 2026-06-27
    Reason: Replaced by database schema.

## Thinking

- Leaving stale docs in-place with no signal misleads future readers.
- Deleting them loses the reasoning trail that led to the outcome.
- The retired date and reason tell future readers exactly when and why the
  document was retired.
