
<!-- README.md is generated from README.Rmd. Please edit that file -->

<!-- badges: start -->

[![License](https://img.shields.io/github/license/archmetalDBM/GlobaLID-database.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Release](https://img.shields.io/github/v/release/archmetalDBM/GlobaLID-database.svg)](https://github.com/archmetalDBM/GlobaLID-database)
[![DOI](https://img.shields.io/badge/doi-10.5880%2Ffidgeo.2025.080-blue)](https://doi.org/10.5880/fidgeo.2025.080)
<!-- badges: end -->

# GlobaLID database <img src="logo.svg" align="right" width="120" />

Here you can find the most recent version of the GlobaLID database and
the R-scripts we use to calculate any lead isotope ratios missing in the
original publications and the age model parameters. What you see here is
work in progress, there might still be some errors or blanks in the
data. Database versions with only correct and complete data (to the best
of our knowledge) are regularly archived at the [GFZ data
repository](https://doi.org/10.5880/fidgeo.2025.080). These are the
versions that should be used.

# What is GlobaLID?

GlobaLID is a Global Lead Isotope Database and aims to facilitate the
reconstruction of raw material provenances with lead isotopes,
especially in archaeology. The app provides direct access to and
convenient interaction with the [GlobaLID
database](https://doi.org/10.5880/fidgeo.2025.080). You can filter the
database according to your research question, upload own data to compare
it with GlobaLID, and produce and download publication ready plots.
Visit [our webpage](https://archmetaldbm.github.io/Globalid/) to learn
more about the GlobaLID project and to get the latest news.

The current version of the GlobaLID database includes data from these
locations: <img src="man/figures/README-map-1.png" width="100%" />

# How to cite

If you use the GlobaLID database, please cite it as

- Westner, Katrin J.; Rose, Thomas; Klein, Sabine; Hsu, Yiu-Kang;
  Becerra, María Florencia; Nezafati, Nima; Renson, Virginie & Stephens,
  Jay (2023): GlobaLID – Global Lead Isotope Database (Version 08/2025).
  GFZ Data Services. <https://doi.org/10.5880/fidgeo.2025.080>
- Klein, S., Rose, T., Westner, K. J., & Hsu, Y.-K. (2022). From OXALID
  to GlobaLID: Introducing a modern and FAIR lead isotope database with
  an interactive application. Archaeometry 64(4), 935–950.
  <https://doi.org/10.1111/arcm.12762>

<!-- -->

    @misc{Westner.2023,
     author = {Westner, Katrin J. and Rose, Thomas and Klein, Sabine and Hsu, Yiu-Kang and Becerra, María Florencia and Nezafati, Nima and Renson, Virginie and Stephens, Jay},
     year = {2023},
     title = {{GlobaLID – Global Lead Isotope Database (Version 08/2025)}},
     publisher = {{GFZ Data Services}},
     doi = {https://doi.org/10.5880/fidgeo.2025.080}
    }

    @article{Klein.2022,
    author = {Klein, Sabine and Rose, Thomas and Westner, Katrin J. and Hsu, Yiu-Kang},
    title = {From OXALID to GlobaLID: Introducing a modern and FAIR lead isotope database with an interactive application},
    journal = {Archaeometry},
    volume = {64},
    number = {4},
    pages = {935-950},
    doi = {https://doi.org/10.1111/arcm.12762},
    }

# Become a contributor!

GlobaLID needs your help to grow and to provide high quality datasets!
The core team is permanently reviewing and adding new and old data from
the literature to keep GlobaLID growing. However, we are neither
proficient enough with the geology and geography of all parts of the
world nor do we know all publications with lead isotope data from ores
and minerals. Hence we are happy about any support from our community.
Interested? Write us!

# Join the team!

GlobaLID needs your help to grow and to provide high quality datasets!
The core team is permanently reviewing and adding new and old data from
the literature to keep GlobaLID growing. However, we are neither
proficient enough with the geology and geography of all parts of the
world nor do we know all publications with lead isotope data from ores
and minerals. Hence we are happy about any support from our community.
Interested? Write us!

# Team

Please find the up-to-date list of team members on the [TerraLID
webpage](https://terralid.org/team.html), where development of GlobaLID
continues.

# Funding

<table width="100%" cellspacing="0" cellpadding="0" border="0">

<tbody>

<tr>

<td>

<img src="man/dfg_logo.gif">
</td>

<td halign="left">

This work has received funding from the German Research Foundation (DFG)
through the grants KL 1259/17-1 and WI 5923/2-1 (project number:
524790825).
</td>

</tr>

</tbody>

</table>

# Acknowledgements

The initial GlobaLID database was compiled during years of own research
and profited from the generous sharing of published lead isotope
datasets by many colleagues. The creative and collective work of
compiling the database and application was initiated when all members of
the Core Team and E. Salzmann were members of the Archaeometallurgy
group at the Deutsches Bergbau-Museum (DBM). H. Zietsch (DBM) compiled
the initial literature references.

The Core Team feels deeply grateful for the support of the contributors.
Without their efforts, GlobaLID would grow much slower and less
accurate.

We are indebted to the R Core Team for providing and maintaining
[R](https://cran.r-project.org/), the authors of the fantastic packages
we use, and the R community on
[stackoverflow](https://stackoverflow.com/) and many other webpages.
Last but definitely not least we are grateful to the [OpenStreetMap
contributors](https://www.openstreetmap.org) from whose Nominatim
database we obtain most of the the geographical meta-information.

The following R packages are used on a regular basis:

- [dplyr](https://dplyr.tidyverse.org/)
- [readr](https://readr.tidyverse.org/)
- [rootSolve](https://cran.r-project.org/web/packages/rootSolve/index.html)
- [stringr](https://stringr.tidyverse.org/)
- [tidygeocoder](https://github.com/jessecambon/tidygeocoder)
- [tidyr](https://tidyr.tidyverse.org/)
