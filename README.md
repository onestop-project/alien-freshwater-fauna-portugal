# Checklist of non-native freshwater fauna in Portugal

## Rationale

This repository contains the functionality to standardize the data of [Non-native freshwater fauna in Portugal: A review](https://doi.org/10.1016/j.scitotenv.2018.09.251) to a [Darwin Core Archive](https://www.gbif.org/darwin-core) that can be harvested by [GBIF](https://www.gbif.org/).

## Workflow

[source data](data/raw) → Darwin Core [mapping script](src/dwc_mapping.Rmd) → generated [Darwin Core files](data/processed)

## Published dataset

* [Dataset on the IPT](<!-- Add the URL of the dataset on the IPT here -->) (not published yet)
* [Dataset on GBIF](<!-- Add the DOI of the dataset on GBIF here -->) (not published yet)

## Repo structure

The repository structure is based on [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/) and the [Checklist recipe](https://github.com/trias-project/checklist-recipe). Files and directories indicated with `GENERATED` should not be edited manually.

```
├── README.md              : Description of this repository
├── LICENSE                : Repository license
├── alien-freshwater-fauna-portugal.Rproj : RStudio project file
├── .gitignore             : Files and directories to be ignored by git
│
├── src
│   ├── dwc_mapping.Rmd    : Darwin Core mapping script
│   ├── _site.yml          : Settings to build website in docs/
│   └── index.Rmd          : Template for website homepage
│
├── docs                   : Repository website GENERATED
│
└── data
    ├── raw                : Source data, input for mapping script
    └── processed          : Darwin Core output of mapping script GENERATED
```

## Installation

1. Clone this repository to your computer
2. Open the RStudio project file
3. Open the `dwc_mapping.Rmd` [R Markdown file](https://rmarkdown.rstudio.com/) in RStudio and complete it for your project
4. Install any required packages
5. Click `Run > Run All` to generate the processed data
6. Alternatively, click `Build > Build website` to generate the processed data and build the website in `docs/` (advanced)

## Contributors

<!-- This section lists everyone who contributed to this repository. You can maintain a manual list here or reference the contributors on GitHub. -->

[List of contributors](<!-- Add the URL to the GitHub contributors of your repository here, e.g. https://github.com/trias-project/checklist-recipe/contributors -->)

## License

<!-- The license is the open source license for the code and documentation in this repository, not the checklist data (that you can define in dwc_mapping.Rmd). As your repository is based on https://github.com/trias-project/checklist-recipe, we'd like it if you kept the open and permissive MIT license. You're welcome to add your name as a copyright holder (because your are for your own code contributions), which you can do in the LICENSE file. If you want to release your repository under a different license, please indicate somehow that it was based on https://github.com/trias-project/checklist-recipe. We know, licenses are complicated. See https://choosealicense.com/ for more information. -->

[MIT License](LICENSE) for the code and documentation in this repository. The included data is released under another license.
