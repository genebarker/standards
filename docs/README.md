<!-- Derived from Eugene F. Barker (github.com/genebarker/standards) MIT -->
# Project Documentation

This folder contains the project's documentation. The documentation is
written in plain text, then supplemented as-needed with pictures, diagrams,
and models:

Type       | Format
---------- | ----------------------------------------------
Plain text | [Markdown (GitHub Flavored)][a]
Pictures   | [PNG Files][b]
Diagrams   | [draw.io][c] (context, box, ERD, object model)

## Markdown Guidelines

In general, the files should be written so that they display well using an
(80) column terminal window. Accordingly:

- think **elegant plain text** designed for the terminal
- limit line length to (76) characters; this makes it easy to edit well on
  terminal editors with line numbering
- markup lightly using [GitHub Flavored Markdown][a]; this provides a little
  structure and as a bonus it renders well with most markdown tools
- use [reference links][d] to keep the body text clean and easy to read
  - when the link targets another numbered doc (a usecase or decision), name
    the label after that doc's number - e.g. `[017]` for
    `017-review-name-request.md` - so the target is visible without
    following it
  - for anything else, a bare number is easy to mistake for a doc
    reference; use a letter (`[a]`) or a keyword instead - whichever
    reads better - so a bracketed number always means "jump to a
    numbered doc"
- use [footnotes][e] to move side-notes out of the main flow of the text
- use `.md` for the file extension

These guidelines cover the files in this folder. Text written for other
destinations - GitHub issues, email, word processor documents - follows
the convention of that destination.

## Directory Structure

- [decisions][f]: Architecture Decision Records (ADRs). Use
  `decision-template.md` to author new decisions, and log them in
  `decision-list.md`.
- [usecases][g]: System usecases. Use `usecase-template.md` to author new
  usecases, log them in `usecase-index.md`, and, if applicable,
  `live-usecases.md`.
- [examples][h]: Practical reference examples showing formatting,
  extensions, and list syntax.

These are the standard homes. Projects are free to add their own
folders when project artifacts need one - e.g. `models/` for design
models, or `graphics/` for the source artwork behind app resources.


[a]: https://github.github.com/gfm/
[b]: https://en.wikipedia.org/wiki/Portable_Network_Graphics
[c]: https://www.drawio.com
[d]: https://www.markdownguide.org/basic-syntax/#reference-style-links
[e]: https://www.markdownguide.org/extended-syntax/#footnotes
[f]: decisions/
[g]: usecases/
[h]: examples/
