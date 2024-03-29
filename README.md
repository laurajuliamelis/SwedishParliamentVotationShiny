# Lab5Shiny: A shiny application

A simple Shiny application about Swedish Parliament Votation data. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

The application require a basic installation of R. In addition `devtools`, `shiny` and `rSwedishParliamentVotations` packages, [GitHub repository](https://github.com/laurajuliamelis/SwedishParliamentVotationAPI).

```
install.packages("shiny")
install.packages("devtools")
devtools::install_github("laurajuliamelis/SwedishParliamentVotationAPI", subdir="rSwedishParliamentVotations")
```

### Installing

Run the following in R to run the shiny app:

```
runGitHub("laurajuliamelis/SwedishParliamentVotationShiny", subdir="ShinySwedishParliamentVotations")
```


### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Friends and family for making this possible.