# ZotHero

Rapidly search your Zotero database and copy citations.

https://github.com/deanishe/zothero

## Features

- Perform full-text search across your Zotero database, including only searching specific fields
- Copy citations using any CSL style you have installed in Zotero
- Copy citations either in citation/note style or bibliography style
- Copy citations in any locale supported by CSL
- Citations are copied in multiple formats, so the right data are automatically pasted into the application you're using
- Trigger search while you type using the Snippet Trigger (you must assign the snippet keyword yourself in Alfred Preferences)

## Download & installation

Download the `ZotHero-XYZ.alfredworkflow` file from [GitHub releases](https://github.com/deanishe/zothero/releases), and double-click the downloaded file to install.

## Basic usage

These are the workflow's default keywords:

- `zot <query>` — Search your Zotero database (common fields).
- `zot:[<query>]` — Search a specific field.
- `zotconf [<query>]` — View and edit workflow configuration.

See the [README](https://github.com/deanishe/zothero/blob/master/README.md) on GitHub for full instructions.

### Pasting citations

When you copy a citation, ZotHero puts both HTML and rich text (RTF) representations on the pasteboard. That way, when you paste a citation into an application like Word, the formatted text will be pasted, but when you paste into a text/Markdown document, the HTML will be pasted.

## Licence & thanks

The workflow is released under the [MIT licence](https://github.com/deanishe/zothero/blob/master/LICENCE).

The Zorro icon was created by [Dan Lowenstein](https://thenounproject.com/danny_mustache).

Citations are generated by [citeproc-js](https://github.com/Juris-M/citeproc-js) ([AGPLv3](https://github.com/Juris-M/citeproc-js/blob/master/AGPLv3)).

Workflow stuff is taken care of by [Alfred-Workflow](http://www.deanishe.net/alfred-workflow/) (also MIT licence).
