# Component Mappings
This repository contains name mappings to translate yocto dependencies to the equivalent openwrt packages.

## Opensource.csv
This file should contain all mappings for opensource (upstream) components.
One can find yocto names [here](https://layers.openembedded.org/layerindex/branch/master/recipes/). For openwrt packages the (compiletime) name of a package is typically the name of the directory of that package in the feed.

## Runtime.csv
This file contains all names for runtime packages, whenever they differ from the regular compile-time package name.
In openwrt compiletime name of a package and runtime name may differ.

## Gitlab.csv
This file contains mappings for components found on the prpl foundation Gitlab. Typically yocto and openwrt names are identical here.
