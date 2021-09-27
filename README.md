# U.S.-Census-Counts-Data

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

A Brief Introduction
=====================

The U.S. Census data that I pulled together to make the population density and pyramid animations. The package is called uscenpops and it’s available to install with install.packages() if you set up drat first. The instructions are on the package homepage.

The uscenpops details:
========================

1.Installation using drat

While using install_github() works just fine, it would be nicer to be able to just type install.packages("uscenpops") or update.packages("uscenpops") in the ordinary way. We can do this using Dirk Eddelbuettel’s drat package. Drat provides a convenient way to make R aware of package repositories other than CRAN.

First, install drat:

if (!require("drat")) {
    install.packages("drat")
    library("drat")
}

Then use drat to tell R about the repository where uscenpops is hosted:

drat::addRepo("kjhealy")

You can now install uscenpops:

install.packages("uscenpops")
