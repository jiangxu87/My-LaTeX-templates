# My-LaTeX-templates
My personal LaTeX templates

## markdown_report_pandoc

Usage:

```
pandoc --template=template.tex -s DSASPOC20164-3_Min_Report.md -o  DSASPOC20164-3_Min_Report.tex --latex-engine=xelatex
```

## markdown_beamer_pandoc

Usage:

```
pandoc --to=beamer --output=slides.tex talk.md --latex-engine=xelatex --template=template.tex --natbib --biblio=ref.bib
```

