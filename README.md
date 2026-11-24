# RPACT Cheat Sheets

[Download the rpact Cheat Sheet (PDF)](https://cheatsheets.rpact.org/pdf/rpact-cheatsheet.pdf)

## Help improve the rpact Cheat Sheet

Which rpact command do you use regularly but still find yourself looking up? Maybe it's a function name, an argument you keep forgetting, or a short sequence of calls you use to get a result. If you look it up, chances are someone else does too.

Whether you're new to rpact or use it every day, we'd like to hear what you'd find useful on the cheat sheet.

- **Share a command or workflow.** [Open an issue](https://github.com/rpact-com/cheatsheets/issues/new) with the R code and a sentence about when you use it. A single line of R is enough.
- **Add it yourself.** Edit the [Quarto source](cheatsheets/rpact/rpact-cheatsheet.qmd) and submit a pull request. A short, runnable example helps others see how to use the command.

Corrections and suggestions for making existing examples clearer are welcome too.

## Build locally

The Quarto source contains runnable examples for design, planning, analysis and reporting. To build the PDF locally, use Quarto 1.8.26 and R with rpact 5.0.0, knitr and rmarkdown installed.

```sh
quarto render cheatsheets/rpact/rpact-cheatsheet.qmd --to typst
```

GitHub Actions builds the PDF for pull requests. Updates to `main` publish the latest version to the download URL above.
