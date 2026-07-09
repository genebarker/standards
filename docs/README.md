<!-- Derived from Eugene F. Barker (github.com/genebarker/standards) MIT -->
# Project Documentation

This folder contains the project's documentation. The documentation is
written in plain text, then supplemented as-needed with pictures, diagrams,
and models:

Type       | Format
---------- | ----------------------------------------------
Plain text | [Markdown (GitHub Flavored)][1]
Pictures   | [PNG Files][2]
Diagrams   | [draw.io][3] (context, box, ERD, object model)

## Markdown Guidelines

In general, the files should be written so that they display well using an
(80) column terminal window. Accordingly:

- think **elegant plain text** designed for the terminal
- limit line length to (76) characters; this makes it easy to edit well on
  terminal editors with line numbering
- markup lightly using [GitHub Flavored Markdown][1]; this provides a little
  structure and as a bonus it renders well with most markdown tools
- use [reference links][4] to keep the body text clean and easy to read
- use [footnotes][5] to move side-notes out of the main flow of the text
- use `.md` for the file extension

## Directory Structure

- [decisions][6]: Architecture Decision Records (ADRs). Use
  `decision-template.md` to author new decisions, and log them in
  `decision-list.md`.
- [usecases][7]: System usecases. Use `usecase-template.md` to author new
  usecases, log them in `usecase-index.md`, and, if applicable,
  `live-usecases.md`.
- [examples][8]: Practical reference examples showing formatting,
  extensions, and list syntax.

These are the standard homes. Projects are free to add their own
folders when project artifacts need one - e.g. `models/` for design
models, or `graphics/` for the source artwork behind app resources.


[1]: https://github.github.com/gfm/
[2]: https://en.wikipedia.org/wiki/Portable_Network_Graphics
[3]: https://www.drawio.com
[4]: https://www.markdownguide.org/basic-syntax/#reference-style-links
[5]: https://www.markdownguide.org/extended-syntax/#footnotes
[6]: decisions/
[7]: usecases/
[8]: examples/
