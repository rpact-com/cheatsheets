# RPACT Cheatsheets

[Download the rpact Cheatsheet (PDF)](https://cheatsheets.rpact.org/pdf/rpact-cheatsheet.pdf)

The [Quarto source](cheatsheets/rpact/rpact-cheatsheet.qmd) contains runnable examples for design, planning, analysis and reporting.

Build locally with Quarto 1.8.26 and R with rpact 5.0.0, knitr and rmarkdown installed.

```sh
quarto render cheatsheets/rpact/rpact-cheatsheet.qmd --to typst
```

Report corrections in Issues or propose changes to the source in a pull request. Pull requests build the PDF for validation. Pushes to main also publish it to GitHub Pages at the stable download URL above.
