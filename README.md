
<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- badges: start -->

[![License](https://img.shields.io/github/license/archmetalDBM/GlobaLID-database.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Release](https://img.shields.io/github/v/release/archmetalDBM/GlobaLID-database.svg)](https://github.com/archmetalDBM/GlobaLID-database)
[![DOI](https://img.shields.io/badge/doi-10.5880%2Ffidgeo.2021.031-blue)](https://doi.org/10.5880/fidgeo.2021.031)
<!-- badges: end -->

# GlobaLID database <img src="logo.svg" align="right" width="120" />

Here you can find the most recent version of the GlobaLID database and
the R-scripts we use to calculate any lead isotope ratios missing in the
original publications and the age model parameters. What you see here is
work in progress, there might still be some errors or blanks in the
data. Database versions with only correct and complete data (to the best
of our knowledge) are regularly archived at the [GFZ data
repository](https://doi.org/10.5880/fidgeo.2021.031). These are the
versions that should be used.

# What is GlobaLID?

GlobaLID is a Global Lead Isotope Database and aims to facilitate the
reconstruction of raw material provenances with lead isotopes,
especially in archaeology. The app provides direct access to and
convenient interaction with the [GlobaLID
database](https://doi.org/10.5880/fidgeo.2021.031). You can filter the
database according to your research question, upload own data to compare
it with GlobaLID, and produce and download publication ready plots.

# How to cite

If you use the GlobaLID database, please cite it as  
Westner, Katrin J.; Rose, Thomas; Klein, Sabine; Hsu, Yiu-Kang (2021):
GlobaLID – Global Lead Isotope Database. V. 1.0. GFZ Data Services.
<https://doi.org/10.5880/fidgeo.2021.031>

    @misc{Westner.2021,
     author = {Westner, Katrin J. and Rose, Thomas and Klein, Sabine and Hsu, Yiu-Kang},
     year = {2021},
     title = {{GlobaLID -- Global Lead Isotope Database V. 1.0}},
     publisher = {{GFZ Data Services}},
     doi = {10.5880/fidgeo.2021.031}, 
     url = {https://doi.org/10.5880/fidgeo.2021.031}
    }

# Become a contributor!

GlobaLID needs your help to grow and to provide high quality datasets!
The core team is permanently reviewing and adding new and old data from
the literature to keep GlobaLID growing. However, we are neither
proficient enough with the geology and geography of all parts of the
world nor do we know all publications with lead isotope data from ores
and minerals. Hence we are happy about any support from our community.
Interested? Write us!

# GlobaLID core team

-   Coordinator: [Sabine
    Klein](https://www.bergbaumuseum.de/en/museum/mitarbeitende/kontakt-detailseite/prof-dr-sabine-klein)
    [<svg viewBox="0 0 512 512" style="height:1em;position:relative;display:inline-block;top:.1em;fill:#A6CE39;" xmlns="http://www.w3.org/2000/svg">
    <g label="icon" id="layer6" groupmode="layer">
    <path id="path2" d="m 336.6206,194.53756 c -7.12991,-3.32734 -13.8671,-5.55949 -20.25334,-6.61343 -6.36534,-1.09517 -16.57451,-1.61223 -30.71059,-1.61223 h -36.70409 v 152.74712 h 37.63425 c 14.6735,0 26.08126,-1.01267 34.22385,-3.01709 8.14259,-2.00442 14.92159,-4.52592 20.35674,-7.62608 5.43519,-3.07925 10.416,-6.8615 14.94192,-11.38742 14.4876,-14.71475 21.74129,-33.27334 21.74129,-55.7176 0,-22.05151 -7.44016,-40.05177 -22.34085,-53.98159 -5.49732,-5.16674 -11.82143,-9.44459 -18.88918,-12.79281 z M 255.99999,8.0000031 C 119.02153,8.0000031 8.0000034,119.04185 8.0000034,255.99998 8.0000034,392.95812 119.02153,504 255.99999,504 392.97849,504 504,392.95812 504,255.99998 504,119.04185 392.97849,8.0000031 255.99999,8.0000031 Z M 173.66372,365.51268 H 144.27546 V 160.1481 h 29.38826 z M 158.94954,138.69619 c -11.13935,0 -20.21208,-9.01056 -20.21208,-20.21208 0,-11.11841 9.05183,-20.191181 20.21208,-20.191181 11.18058,0 20.23244,9.051831 20.23244,20.191181 -0.0219,11.22184 -9.05186,20.21208 -20.23244,20.21208 z m 241.3866,163.59715 c -5.29051,12.54475 -12.83407,23.58066 -22.65053,33.08742 -9.98203,9.83734 -21.59659,17.19443 -34.84378,22.19616 -7.74983,3.01709 -14.83852,5.06335 -21.30725,6.11726 -6.4891,1.01267 -18.82759,1.50883 -37.07593,1.50883 H 219.5033 V 160.1481 h 69.23318 c 27.96195,0 50.03378,4.1541 66.31951,12.54476 16.26485,8.36977 29.18144,20.72859 38.79164,36.97254 9.61013,16.26483 14.4254,34.01757 14.4254,53.19607 0.0227,13.76426 -2.66619,26.90802 -7.93576,39.43187 z" style="stroke-width:0.07717"></path>
    </g> </svg>](https://orcid.org/0000-0002-3939-4428)
    (Forschungsbereich Archäometallurgie, Leibniz-Forschungsmuseum für
    Georessourcen/Deutsches Bergbau-Museum Bochum, Bochum, Germany;
    Institut für Archäologische Wissenschaften, Ruhr-Universität Bochum,
    Bochum, Germany; FIERCE, Frankfurt Isotope & Element Research
    Centre, Goethe Universität, Frankfurt am Main, Germany)
-   Database: [Katrin J.
    Westner](http://lgltpe.ens-lyon.fr/annuaire/westner-katrin)
    [<svg viewBox="0 0 512 512" style="height:1em;position:relative;display:inline-block;top:.1em;fill:#A6CE39;" xmlns="http://www.w3.org/2000/svg">
    <g label="icon" id="layer6" groupmode="layer">
    <path id="path2" d="m 336.6206,194.53756 c -7.12991,-3.32734 -13.8671,-5.55949 -20.25334,-6.61343 -6.36534,-1.09517 -16.57451,-1.61223 -30.71059,-1.61223 h -36.70409 v 152.74712 h 37.63425 c 14.6735,0 26.08126,-1.01267 34.22385,-3.01709 8.14259,-2.00442 14.92159,-4.52592 20.35674,-7.62608 5.43519,-3.07925 10.416,-6.8615 14.94192,-11.38742 14.4876,-14.71475 21.74129,-33.27334 21.74129,-55.7176 0,-22.05151 -7.44016,-40.05177 -22.34085,-53.98159 -5.49732,-5.16674 -11.82143,-9.44459 -18.88918,-12.79281 z M 255.99999,8.0000031 C 119.02153,8.0000031 8.0000034,119.04185 8.0000034,255.99998 8.0000034,392.95812 119.02153,504 255.99999,504 392.97849,504 504,392.95812 504,255.99998 504,119.04185 392.97849,8.0000031 255.99999,8.0000031 Z M 173.66372,365.51268 H 144.27546 V 160.1481 h 29.38826 z M 158.94954,138.69619 c -11.13935,0 -20.21208,-9.01056 -20.21208,-20.21208 0,-11.11841 9.05183,-20.191181 20.21208,-20.191181 11.18058,0 20.23244,9.051831 20.23244,20.191181 -0.0219,11.22184 -9.05186,20.21208 -20.23244,20.21208 z m 241.3866,163.59715 c -5.29051,12.54475 -12.83407,23.58066 -22.65053,33.08742 -9.98203,9.83734 -21.59659,17.19443 -34.84378,22.19616 -7.74983,3.01709 -14.83852,5.06335 -21.30725,6.11726 -6.4891,1.01267 -18.82759,1.50883 -37.07593,1.50883 H 219.5033 V 160.1481 h 69.23318 c 27.96195,0 50.03378,4.1541 66.31951,12.54476 16.26485,8.36977 29.18144,20.72859 38.79164,36.97254 9.61013,16.26483 14.4254,34.01757 14.4254,53.19607 0.0227,13.76426 -2.66619,26.90802 -7.93576,39.43187 z" style="stroke-width:0.07717"></path>
    </g> </svg>](https://orcid.org/0000-0001-5529-1165) (Ecole Normale
    Supérieure de Lyon, CNRS, Université de Lyon, Lyon, France)
-   Programming: Thomas Rose
    [<svg viewBox="0 0 512 512" style="height:1em;position:relative;display:inline-block;top:.1em;fill:#A6CE39;" xmlns="http://www.w3.org/2000/svg">
    <g label="icon" id="layer6" groupmode="layer">
    <path id="path2" d="m 336.6206,194.53756 c -7.12991,-3.32734 -13.8671,-5.55949 -20.25334,-6.61343 -6.36534,-1.09517 -16.57451,-1.61223 -30.71059,-1.61223 h -36.70409 v 152.74712 h 37.63425 c 14.6735,0 26.08126,-1.01267 34.22385,-3.01709 8.14259,-2.00442 14.92159,-4.52592 20.35674,-7.62608 5.43519,-3.07925 10.416,-6.8615 14.94192,-11.38742 14.4876,-14.71475 21.74129,-33.27334 21.74129,-55.7176 0,-22.05151 -7.44016,-40.05177 -22.34085,-53.98159 -5.49732,-5.16674 -11.82143,-9.44459 -18.88918,-12.79281 z M 255.99999,8.0000031 C 119.02153,8.0000031 8.0000034,119.04185 8.0000034,255.99998 8.0000034,392.95812 119.02153,504 255.99999,504 392.97849,504 504,392.95812 504,255.99998 504,119.04185 392.97849,8.0000031 255.99999,8.0000031 Z M 173.66372,365.51268 H 144.27546 V 160.1481 h 29.38826 z M 158.94954,138.69619 c -11.13935,0 -20.21208,-9.01056 -20.21208,-20.21208 0,-11.11841 9.05183,-20.191181 20.21208,-20.191181 11.18058,0 20.23244,9.051831 20.23244,20.191181 -0.0219,11.22184 -9.05186,20.21208 -20.23244,20.21208 z m 241.3866,163.59715 c -5.29051,12.54475 -12.83407,23.58066 -22.65053,33.08742 -9.98203,9.83734 -21.59659,17.19443 -34.84378,22.19616 -7.74983,3.01709 -14.83852,5.06335 -21.30725,6.11726 -6.4891,1.01267 -18.82759,1.50883 -37.07593,1.50883 H 219.5033 V 160.1481 h 69.23318 c 27.96195,0 50.03378,4.1541 66.31951,12.54476 16.26485,8.36977 29.18144,20.72859 38.79164,36.97254 9.61013,16.26483 14.4254,34.01757 14.4254,53.19607 0.0227,13.76426 -2.66619,26.90802 -7.93576,39.43187 z" style="stroke-width:0.07717"></path>
    </g> </svg>](https://orcid.org/0000-0002-8186-3566) (Department of
    Archaeology, Ben-Gurion University of the Negev, Be’er Sheva,
    Israel; Department of Antiquity, Sapienza University of Rome, Rome,
    Italy)
-   East Asia: [Yiu-Kang
    Hsu](https://www.bergbaumuseum.de/en/museum/mitarbeitende/kontakt-detailseite/yiu-kang-hsu)
    [<svg viewBox="0 0 512 512" style="height:1em;position:relative;display:inline-block;top:.1em;fill:#A6CE39;" xmlns="http://www.w3.org/2000/svg">
    <g label="icon" id="layer6" groupmode="layer">
    <path id="path2" d="m 336.6206,194.53756 c -7.12991,-3.32734 -13.8671,-5.55949 -20.25334,-6.61343 -6.36534,-1.09517 -16.57451,-1.61223 -30.71059,-1.61223 h -36.70409 v 152.74712 h 37.63425 c 14.6735,0 26.08126,-1.01267 34.22385,-3.01709 8.14259,-2.00442 14.92159,-4.52592 20.35674,-7.62608 5.43519,-3.07925 10.416,-6.8615 14.94192,-11.38742 14.4876,-14.71475 21.74129,-33.27334 21.74129,-55.7176 0,-22.05151 -7.44016,-40.05177 -22.34085,-53.98159 -5.49732,-5.16674 -11.82143,-9.44459 -18.88918,-12.79281 z M 255.99999,8.0000031 C 119.02153,8.0000031 8.0000034,119.04185 8.0000034,255.99998 8.0000034,392.95812 119.02153,504 255.99999,504 392.97849,504 504,392.95812 504,255.99998 504,119.04185 392.97849,8.0000031 255.99999,8.0000031 Z M 173.66372,365.51268 H 144.27546 V 160.1481 h 29.38826 z M 158.94954,138.69619 c -11.13935,0 -20.21208,-9.01056 -20.21208,-20.21208 0,-11.11841 9.05183,-20.191181 20.21208,-20.191181 11.18058,0 20.23244,9.051831 20.23244,20.191181 -0.0219,11.22184 -9.05186,20.21208 -20.23244,20.21208 z m 241.3866,163.59715 c -5.29051,12.54475 -12.83407,23.58066 -22.65053,33.08742 -9.98203,9.83734 -21.59659,17.19443 -34.84378,22.19616 -7.74983,3.01709 -14.83852,5.06335 -21.30725,6.11726 -6.4891,1.01267 -18.82759,1.50883 -37.07593,1.50883 H 219.5033 V 160.1481 h 69.23318 c 27.96195,0 50.03378,4.1541 66.31951,12.54476 16.26485,8.36977 29.18144,20.72859 38.79164,36.97254 9.61013,16.26483 14.4254,34.01757 14.4254,53.19607 0.0227,13.76426 -2.66619,26.90802 -7.93576,39.43187 z" style="stroke-width:0.07717"></path>
    </g> </svg>](https://orcid.org/0000-0002-2439-4863)
    (Forschungsbereich Archäometallurgie, Leibniz-Forschungsmuseum für
    Georessourcen/Deutsches Bergbau-Museum Bochum, Bochum, Germany)

# Contributors

-   [Nima
    Nezafati](https://www.bergbaumuseum.de/en/museum/mitarbeitende/kontakt-detailseite/dr-nima-nezafati)
    [<svg viewBox="0 0 512 512" style="height:1em;position:relative;display:inline-block;top:.1em;fill:#A6CE39;" xmlns="http://www.w3.org/2000/svg">
    <g label="icon" id="layer6" groupmode="layer">
    <path id="path2" d="m 336.6206,194.53756 c -7.12991,-3.32734 -13.8671,-5.55949 -20.25334,-6.61343 -6.36534,-1.09517 -16.57451,-1.61223 -30.71059,-1.61223 h -36.70409 v 152.74712 h 37.63425 c 14.6735,0 26.08126,-1.01267 34.22385,-3.01709 8.14259,-2.00442 14.92159,-4.52592 20.35674,-7.62608 5.43519,-3.07925 10.416,-6.8615 14.94192,-11.38742 14.4876,-14.71475 21.74129,-33.27334 21.74129,-55.7176 0,-22.05151 -7.44016,-40.05177 -22.34085,-53.98159 -5.49732,-5.16674 -11.82143,-9.44459 -18.88918,-12.79281 z M 255.99999,8.0000031 C 119.02153,8.0000031 8.0000034,119.04185 8.0000034,255.99998 8.0000034,392.95812 119.02153,504 255.99999,504 392.97849,504 504,392.95812 504,255.99998 504,119.04185 392.97849,8.0000031 255.99999,8.0000031 Z M 173.66372,365.51268 H 144.27546 V 160.1481 h 29.38826 z M 158.94954,138.69619 c -11.13935,0 -20.21208,-9.01056 -20.21208,-20.21208 0,-11.11841 9.05183,-20.191181 20.21208,-20.191181 11.18058,0 20.23244,9.051831 20.23244,20.191181 -0.0219,11.22184 -9.05186,20.21208 -20.23244,20.21208 z m 241.3866,163.59715 c -5.29051,12.54475 -12.83407,23.58066 -22.65053,33.08742 -9.98203,9.83734 -21.59659,17.19443 -34.84378,22.19616 -7.74983,3.01709 -14.83852,5.06335 -21.30725,6.11726 -6.4891,1.01267 -18.82759,1.50883 -37.07593,1.50883 H 219.5033 V 160.1481 h 69.23318 c 27.96195,0 50.03378,4.1541 66.31951,12.54476 16.26485,8.36977 29.18144,20.72859 38.79164,36.97254 9.61013,16.26483 14.4254,34.01757 14.4254,53.19607 0.0227,13.76426 -2.66619,26.90802 -7.93576,39.43187 z" style="stroke-width:0.07717"></path>
    </g> </svg>](https://orcid.org/0000-0002-5806-343X)
    (Forschungsbereich Archäometallurgie, Leibniz-Forschungsmuseum für
    Georessourcen/Deutsches Bergbau-Museum Bochum, Bochum, Germany)

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

-   [dplyr](https://dplyr.tidyverse.org/)
-   [readr](https://readr.tidyverse.org/)
-   [rootSolve](https://cran.r-project.org/web/packages/rootSolve/index.html)
-   [stringr](https://stringr.tidyverse.org/)
-   [tidygeocoder](https://github.com/jessecambon/tidygeocoder)
-   [tidyr](https://tidyr.tidyverse.org/)
