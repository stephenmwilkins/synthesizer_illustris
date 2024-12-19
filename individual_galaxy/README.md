## Individual Illustris galaxy

This demonstrates using `synthesizer` to produce synthestic observations of a single galaxy extracted from the [https://www.tng-project.org/data/](Illustris project). 

This folder contains notebooks showing how to generate spectral energy distributions (`make_tng50_sed`), emission lines (`make_tng50_lines`), and images (`make_tng50_image`). However, it is first necessary to download the galaxy data and create a `Galaxy` object. This is acheived via `make_tng50_galaxy`. This allows you to specify a single galaxy of your choice and download the relevant quantities. This requires the use of an `api_key` which can be obtained from the Illustris website (**DO NOT USE MINE**).

`make_tng50_galaxy` can also calculate the line-of-sight dust attenuation using the surface density of metals (in gas particles). However, for the default galaxy (around 300,000 star particles) this can take about 20 minutes. 

