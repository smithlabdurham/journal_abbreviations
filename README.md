# Using this repo

To abbreviate journal titles using pandoc, add:

```
--citation-abbreviations=https://raw.githubusercontent.com/smithlabdurham/journal_abbreviations/main/abbreviations.json
```

to your `pandoc --citeproc` command, or add
`citation-abbreviations: https://raw.githubusercontent.com/smithlabdurham/journal_abbreviations/main/abbreviations.json` to the document's YAML metadata.

# Source
`abbreviations.json` is extracted from Zotero 6.0.7 and licensed under the AGPL.


On a Windows installation, the source file can be found in:
`C:\Program Files (x86)\Zotero\zotero.jar\resource\schema\abbreviations.json`
