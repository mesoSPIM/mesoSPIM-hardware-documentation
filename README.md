## mesoSPIM Version 5
![mesoSPIM V5](images/mesoSPIM-V5.jpg)

## What is the mesoSPIM project?
The mesoSPIM (mesoscale selective plane illumination microscopy) project
aims at creating open-hardware microscopy platforms for imaging in cleared tissue. Core features of the current generation mesoSPIM setups are:

* compatibilty with all major clearing techniques including CLARITY and iDISCO
* large field-of-views, ranging from 2 to 20 mm using an Olympus MVX-10 macroscope
* dual-sided excitation
* optimized for fast screening of whole mouse brain samples, yielding relatively small datasets (10-14 GB/brain/color)
* near-isotropic sampling (5-10 µm in X,Y & Z) due to an axially swept lightsheet which leads to uniform z-resolution across the field-of-view
* modular sample holders and quick sample exchange
* large travel range (45 x 45 x 100 mm) to allow imaging of very large samples

Inspired by the [openSPIM](http://www.openspim.org/) and [openSPIN](https://sites.google.com/site/openspinmicroscopy/) projects,
the documentation for building and extending your own mesoSPIM is available here.

## The mesoSPIM wiki
The [mesoSPIM wiki](https://github.com/mesoSPIM/mesoSPIM-hardware-documentation/wiki) provides documentation, setup, and usage instructions.

## Who is the mesoSPIM project for?
* You are looking for a versatile imaging platform for cleared tissue that can be tailored to your needs.
* Research groups and imaging facilities with experience in building and supporting custom microscopes.

## What are ideal imaging applications for a mesoSPIM?
* screening of large numbers of samples for clearing & labeling quality
* visualization of cell populations or other structures (blood vessels, plaques) in whole cleared organs

## What are the mesoSPIM instruments less well suited for?
* imaging live samples (this is the domain of classical light-sheet microscopes)
* high-resolution (<1 µm pixelsize) scans with large number of tiles across whole mouse brains (this is better done using light-sheet instruments not based on a zoom macroscopes such as the Zeiss Z.1., the COLM)
