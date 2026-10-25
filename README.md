# fromSpreadSheetToR

Yanina Bellini Saibene, Paola Corrales y Elio Campitelli

This course is intended for [people](personas.qmd) who use spreadsheets for data manipulation and analysis but would like to learn how to work with R and have never programmed. The first version of this course was developed for the [Research Software Camp: Beyond the spreadsheet](https://www.software.ac.uk/RSCamp-beyond-spreadsheet).

## Building the website

The website is a [Quarto](https://quarto.org/) project. To preview it locally, open `quarto-course.Rproj` in RStudio and click **Render** on the index.qmd page (or go to the **Build** tab and click **Render Website**). From a terminal you can run:

```bash
quarto preview
```

You'll need the `rmarkdown`, `knitr`, `tidyverse` and `readxl` R packages installed.

## Publishing

The workflow in `.github/workflows/publish.yml` renders the site and publishes it to the `gh-pages` branch on every push to `main`. Before the first run:

1. Run `quarto publish gh-pages` once from your computer (it creates the `gh-pages` branch), or create an empty `gh-pages` branch by hand.
2. In the repository settings, go to **Pages** and select the `gh-pages` branch as the source.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Licencia Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Esta obra está bajo una <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Licencia Creative Commons Atribución-CompartirIgual 4.0 Internacional</a>.
