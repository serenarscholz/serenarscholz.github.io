---
layout: page
title: Software
permalink: /software/
---

## AR identifiation algorithm

Most AR detection algorithms are based on IVT and IWV, and they apply some sort of arbitrary threshold to detect features (e.g. water vapor transport over a certain absolute value, or over a certain percentile, etc.). Our new method is based instead on the moisture-weighted wind field, and it performs consistently across a variety of warm and cold climate states without tuning or arbitrary threshold decisions. Code and documentation will be made available on GitHub when the associated paper is published. AR tags will also be included in the [Atmospheric River Tracking Method Intercomparison Project (ARTMIP)](https://ncar.github.io/ARTMIP/intro.html).

<div style="text-align: center; margin: 1em 0;">
  <img src="/assets/ar_ids_quo.png" alt="AR identification" style="width: 70%; display: inline-block;">
</div>

## Island

Island is a modification to the hierarchical modeling framework [Isca](https://execlim.github.io/IscaWebsite/) that allows highly-customizable land surfaces, including a simple representation of the effect of plants on surface evaporation. Users can create and input custom maps of albedo, surface roughness, and stomatal conductance. Once the modifications are integrated into the Isca codebase, code and documentation will be made available on GitHub.
