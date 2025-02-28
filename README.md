## README

Jasper
2025-02-28

This is a repository for the 2025 UCT Biological Sciences Honours class to demonstrate various aspects of reproducibility and GIS with R as covered in the [course notes](www.plantecolo.gy/teaching).

Firstly, the badge below provides a link to the Binder environment for this repository. Clicking on the badge will open this repository in an interactive environment where you can run the code and explore the data. To set your own git repository up to work with Binder, go to www.mybinder.org and follow the instructions.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jslingsby/bogusrepo/HEAD)

Secondly, the repository contains the following files that help set up Binder for use with R:
- `runtime.txt` - which gives the R version for Binder to use
- `install.R` - which specifies the R packages for Binder to install
- `apt.txt` - which specifies the system dependencies for Binder to install. I have included several linux libraries required to run spatial R libraries like `sf` or `terra`. See the `InteractiveMap.Rmd` file for an example.

Lastly, if you want someone to be able to view HTML files that you have generated in your repository, you can do so by appending the link to the .html file in your Git repo to `http://htmlpreview.github.io/?` For example, the link to the `InteractiveMap.html` file in this repository is: [`https://htmlpreview.github.io/?https://github.com/jslingsby/bogusrepo/blob/main/InteractiveMap.html`](https://htmlpreview.github.io/?https://github.com/jslingsby/bogusrepo/blob/main/InteractiveMap.html)?
