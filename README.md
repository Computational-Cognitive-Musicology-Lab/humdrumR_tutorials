# HumdrumR tutorials

This repository contains tutorial materials for [humdrumR](https://www.humdrumR.org): an R-package for computational musicology research.

![](Slides/images/humdrumR_light.svg)

+ Nat Condit-Schultz
+ [Computational and Cognitive Musicology Lab](https://ccml.gtcmt.gatech.edu)
+ Georgia Tech, [School of Music](https://music.gatech.edu)

This repo can be accessed and played with in [this]() posit cloud "sandbox" environment.

## Data

Several [humdrum](humdrum.org)-formatted datasets are included in the repo:

+ `**kern` encodings of 371 Chorales by J.S. Bach.
+ The [CoCoPops](https://github.com/Computational-Cognitive-Musicology-Lab/CoCoPops) dataset of 20th-century rock/pop transcriptions.
+ A simple humdrum version of the [Saraga](https://mtg.github.io/saraga/) dataset of Indian art music.
  + Specifically, the estimated fundamental frequency (F0) contour from 12 vocal performances from Saraga.


## Content

This repo contains three subdirectories:

+ `Data`, which contains two sets of humdrum data.
+ `Slides`, which contains `.Rmd`-based reveal-js presentations.
+ `Tutorials`, which contains `.Rmd`-based code tutorials.

If you look at this repo via the [posit cloud workspace](https://posit.cloud/content/9786145), you can look at our slide-decks and/or try out tutorials right in your browser.
Simply open a `.Rmd` file from either the `Slides` or `Tutorials` directories, and click the "Run Document" or "Render" button.
