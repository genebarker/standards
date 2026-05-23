<!-- Derived from Eugene F. Barker (github.com/genebarker/standards) MIT -->
# Project Documentation

This folder contains the project's documentation. The documentation is
written in plain text, then supplemented as-needed with pictures, diagrams,
and models:

Type        | Format
----------- | --------------------------------
Plain text  | [Markdown (GitHub Flavored)][1]
Pictures    | [PNG Files][2]
Diagrams    | [draw.io][3] (context, box)
Models      | [StarUML][4] (ERD, object model)

## Markdown Guidelines

In general, the files should be written so that they display well using an
(80) column terminal window. Accordingly:

- think **elegant plain text** designed for the terminal
- limit line length to (76) characters; this makes it easy to edit well on
  terminal editors with line numbering
- markup lightly using [GitHub Flavored Markdown][1]; this provides a little
  structure and as a bonus it renders well with most markdown tools
- use `.md` for the file extension

## Directory Structure

- [decisions][5]: Architecture Decision Records (ADRs). Use
  `decision-template.md` to author new decisions, and log them in
  `decision-list.md`.
- [usecases][6]: System use cases. Use `usecase-template.md` to author new
  use cases.
- [examples][7]: Practical reference examples showing formatting,
  extensions, and list syntax.


[1]: https://github.github.com/gfm/
[2]: https://en.wikipedia.org/wiki/Portable_Network_Graphics
[3]: https://www.drawio.com
[4]: http://staruml.io
[5]: decisions/
[6]: usecases/
[7]: examples/
