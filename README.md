# Exporting the ATLAS GeoModel geometry to USD

## Introduction

The [ATLAS experiment](https://atlas.cern/) at [CERN](https://www.home.cern/) stores the information about the detector geometry in a custom format based on the [GeoModel toolkit](https://gitlab.cern.ch/GeoModelDev/GeoModel).

The GeoModel tree is composed of nodes which are largely inspired by the nodes belonging to the [Open Inventor/Coin](https://github.com/coin3d/coin/wiki) scenegraph-based 3D graphics framework.

The geometry is built by defining a set of GeoModel nodes (Materials, Shapes, Physical Volumes, ...) and placing them in a scenegraph-based tree structure. 

The resulting GeoModel tree is then persistified into an [SQLite file](https://www.sqlite.org/index.html) by the use of a custom DB schema.

## Aim of this project

This repository hosts the tool to export the GeoModel tree representation stored in the ATLAS-specific SQLite file into the representation used in the [USD 3D format](https://openusd.org/).

This lets reaserchers to visualize and inspect the ATLAS detector geometry with industry-standard tools. 
It also lets researches leverage the power of GPU cards to handle geometry data.  Lastly, but not less important, it lets researchers build virtual reality app to interactively explore the detector, as well as for outreach and educational purpose.


## Team

* ...
* Ilija Vukotic, University of Chicago, CERN/ATLAS Experiment
* Riccardo Maria BIANCHI, University of Pittsburgh, CERN/ATLAS Experiment
* ...



