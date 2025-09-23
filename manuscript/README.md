# /manuscript

## - manuscript.md
Markdown template file, will contain all manuscript.
It will be easily converted to the format requested by the publication joiurnal (LaTex, .docx,...), using Pandoc.

Example:
```bash
# convert Markdown to Word using Pandoc
pandoc paper.md --csl=vancouver.csl --bibliography=references.bib -o paper.docx
```

## -refs.bib
Example reference file.

