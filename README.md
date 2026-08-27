# Subpath

**Shape every point.**

Subpath is a local-first SVG path editor for the browser and desktop. You edit anchors and bezier
handles directly, import existing artwork, and export to SVG, React, Vue, Svelte, CSS, data URIs,
and sprite sheets. The full editor runs without an account and keeps working offline.

[Open the editor](https://subpath.dev) · [Desktop app](https://subpath.dev/desktop) · [Changelog](https://subpath.dev/changelog)

## What this repo is for

This is the public tracker for Subpath. Use it to report bugs, request features, and ask questions.
The application source is closed, so you will not find code here. Everything else about the product
gets discussed in the open:

- **[Issues](../../issues)** for bugs and feature requests.
- **[Discussions](../../discussions)** for questions, ideas that are not yet a concrete request, and
  showing off what you made.

Before filing, search existing issues. A comment and a 👍 on an open report tells me more about
priority than a duplicate does.

## Reporting a bug

Open a [bug report](../../issues/new?template=bug_report.yml). The two things that make a bug
fixable are the steps that trigger it and the document it happens in.

Subpath stores your work locally, so I cannot look it up. If the bug depends on a specific document,
use **Share** in the editor to generate a link and paste it into the issue. The link encodes the
document in the URL itself. Skip this if the artwork is private, and describe the shapes instead.

## Requesting a feature

Open a [feature request](../../issues/new?template=feature_request.yml). Describe what you are
trying to make and where the current tools stop you. Concrete workflows get built. Abstract
capabilities usually sit.

Some things are already ruled out. Subpath is a path editor, not a full design suite, and it will
not grow raster editing, page layout, or a plugin runtime.

## Security

Do not open an issue for a security vulnerability. Email **support@subpath.dev** instead. See
[SECURITY.md](SECURITY.md).

## Privacy

Local documents stay in your browser or on your disk. Cloud sync is opt-in per document and
currently limited to invited accounts. The [privacy policy](https://subpath.dev/privacy) and
[terms](https://subpath.dev/terms) cover what the hosted service stores.
