# GRE Verbal

This repository is for creating GRE verbal study materials using the Oxford dictionary API and Google's text-to-speech API from R. It is recommended you find a word list such as Barron's 3500 in Excel form.

**Add Definitions.Rmd** will scan a spreadsheet of words and use the Oxford dictionary API to retrieve additional definitions.

**Text to Speech.Rmd** takes a list of words and definitions, generating a text string to be read by Google's Text to Speech API. You *will* need a free Google Cloud Platform account and create an API key to use this.

### Prerequisites

These notebooks will not run as-is because you will need a word list and API-enabled accounts.

Run these notebooks using R in R Studio. You will need a good working understanding of R and the `tidyverse` as these notebooks make extensive use of programming, and you will likely want to customise this for your own purposes.

## Authors

* **Logan Wu** - [Github](https://github.com/loganbwu)

