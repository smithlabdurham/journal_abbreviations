# Using this repo

To abbreviate journal titles using pandoc, add:

```
--citation-abbreviations https://raw.githubusercontent.com/smithlabdurham/journal_abbreviations/main/abbreviations.json
```

to your `pandoc --citeproc` command, or add
`citation-abbreviations: https://raw.githubusercontent.com/smithlabdurham/journal_abbreviations/main/abbreviations.json` to the document's YAML metadata.

# Source
[`abbreviations.json`](https://github.com/zotero/zotero/blob/master/resource/schema/abbreviations.json)
is extracted from Zotero 6.0.7 and licensed under the AGPL.
