<!-- Derived from Eugene F. Barker (github.com/genebarker/standards) -->
# Project Standards

*Personal reference only.*

My go-to doc standards - centralized so any project can adopt them and stay
current as they evolve. Each standard is either a **design rule** or a
**document template**.

When I fight through a great design rule or refine a format, I capture it
here - so it's available across all my projects.

## How to Use

To adopt these standards in your own project repository:

1. **Copy**: Copy the `docs` folder into your project.
2. **Go**: Start writing your own design rules[^1], usecases, and decisions.
3. **Sync**: Run `docs/docsync` to stay in sync.

## Lineage Header

Keep this header at the top of the design rules and example files to stay
in sync with the latest improvements:

```html
<!-- Derived from Eugene F. Barker (github.com/genebarker/standards) -->
```

## Template Header

Template files like `usecase-template.md` and `live-usecases.md` carry this
header so docsync can alert you when their structure has improved upstream.
The template provides structure only - your content is your own:

```html
<!-- Template: usecase-template v1.0 -->
```

When docsync flags outdated templates, the upstream clone is at
`temp/docsync/`. Ask your AI agent: "grep for Template headers, compare
versions against `temp/docsync/`, adapt any outdated files to the new
structure preserving all content, and bump each file's Template version
stamp to match."

[^1]: Design rules are open form - see existing ones like
    `human-timestamp.md` for reference.
