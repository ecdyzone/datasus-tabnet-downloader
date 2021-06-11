

# DataSUS Tabnet Downloader

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mumaral/alura-desafio-modulo-1/blob/main/projeto-modulo-1.ipynb) (notebook written in portuguese)

**Download data from DataSUS / [Tabnet](https://datasus.saude.gov.br/informacoes-de-saude-tabnet/) and rename it easily and automatically**

Inittiallly made by [silva-felipe](https://github.com/silva-felipe) (the code is [here](https://github.com/silva-felipe/BootCamp_Alura_DataScience/blob/main/notebooks/tabnet_automaition.ipynb)) using Python and [Selenium](https://www.selenium.dev/documentation/en/)

I just expanded it and created a dedicated repository for datasus scraping/downloading tools.

# Next steps

- Include other pages and options. For now it only works with immunization data.
- Parse tabnet page andcreate a dictionary of line/column labels. Therefore the user can choose the line/column in a more human-understandable way, instead of visiting the site and choosing numbers.

# Disclaimer

There are two almost identical pages of immunization data in tabnet. The data is slightly different and columns/lines labels are shown in different order. 

1. First one at http://tabnet.datasus.gov.br/cgi/tabcgi.exe?pni/cnv/cpniuf.def was last updated in 2019.
2. The second is at http://tabnet.datasus.gov.br/cgi/dhdat.exe?bd_pni/cpnibr.def and was last updated this month. It seems to be the current one.