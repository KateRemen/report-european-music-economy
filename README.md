# Report on the European Music Economy

This repo is created two deliverable. This deliverable is preceded by [Music Economy: Methods & Indicators](https://github.com/dataobservatory-eu/music_economy_methods_indicators/).

1. [Report on the European Music Economy](https://zenodo.org/record/6464782#.Ylq7JNpBzIU) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6464782.svg)](https://doi.org/10.5281/zenodo.6464782)

2. [Economy of music in Europe: Novel data collection methods and indicators](https://doi.org/10.5281/zenodo.6464990) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6464990.svg)](https://doi.org/10.5281/zenodo.6464990)



Both follow the [Open Policy Analysis Guidelines](http://www.bitss.org/wp-content/uploads/2019/03/OPA-Guidelines.pdf) and the best practices of the European Union's Knowledge For Policy and the [European Open Science Cloud](https://eosc-portal.eu/) portal.

## Folders

**root** - The two articles, `.bib` bibliography files, and `yml` files for markdown conversions, plus reproducbile `docx`, `pdf`, `epub` versions. Work in the `Rmd` markdown files. If you do not write R code, just ignore the R code chunks, and use it as a clean markdown text.

**bib** - please save here individual BibTex entries.  The consolidated entries will should be placed in one of the main `.bib` files in the root folder. The pandoc / knitr / RStudio workflow can have hickuups with bib files, so try to save individual files first in `bib/xyz.bib`

**not_included** - user's scrap directory, excluded by `.gitignore`.  Please put your non-synchronized scaps and code doodles here.

**data-raw** - data as downloaded, received, as a starting point of our reproducible work. You will find here 5 CAP surveys.

**R** - R code written for the publications.  It is better to write stand-alone R codes, and put final 'chunks' into the `.Rmd` files.

**Py** - You can use optionally Python files.  Posit (formerly RStudio) can weave R, C++ and Python elements into the documents.

**data** - Final data outputs that will be placed in the articles.

`_book`: Research output in PDF/EPub/Docx files.  For each output, start a new repository. All our deliverable are delivered in a version-controlled repository. 
`png`: Portable Network Graphics visualizations.
`jpg`:
`R`: R language code that produces the spreadsheets or visualizations or tables.

## OPA Open Materials

- Label and document each input, including data, research, and guesswork: see contents of documents.

- Standardize the file structure so that materials are organized in a way that is accessible to an informed reader: see below folder documentation.

- Ensure that code/spreadsheets are reproducible. 

- All research and innovation team members use version control software and track changes in a shared project repository. It is clear who contributed to the research, when, and who approved or rejected the contribution.

## Citations, assets, bibliography

The bibliography files (.bib files) can be found in the open repository of the [Report on the European Music Economy](https://github.com/dataobservatory-eu/european_music_economy) (main folder.)

The used references are at the end of the report.


## Links

See the deliverable legal description [here](https://openmuse.dataobservatory.eu/resources/music-economy/) and the results on the [music.dataobservatory.eu](https://music.dataobservatory.eu/) website.
