# test

A user-created system catalogue.

Version: 1.0.0
Model: Fictional

## Objects

Name | Type | Parent | Radius (km) | Mass (kg)
--- | --- | --- | ---: | ---:
51 Pegasi | Star | System center | 827883 | 2.16743e+30
51 Pegasi b | Planet | 51 Pegasi | 136000 | 8.89e+26

### 51 Pegasi

Main sequence yellow dwarf hosting exoplanet 51 Pegasi b (Hot Jupiter). Spectral class G2V+.

### 51 Pegasi b

First hot Jupiter discovered (1995). Tidally locked.

## Install

From this folder: `sol-sim -m "./solar-mod.json"`
Then open `/mod test` inside the app. `/mod exit` returns.

After publishing: `sol-sim -m "YOUR-NAME/YOUR-REPOSITORY"`

## Model

Author-supplied parent-relative Keplerian ellipses, not a live ephemeris.
Starter mass/radius values are estimates unless edited and marked otherwise.
