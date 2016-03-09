# DUNE Computing Model

## Editor's notes
The layout of the document was changed in late December 2015: significant parts of it such as the "Requirements" and sections on computing for the DUNE prototypes were all moved to the appendix with the purpose to make it more readable.

The "head" latex source is now "dune-computing-model". Previously
used "new-layout" designation for a few files has been removed in early March 2016, and obsoleted files (before the "new layout came to be) were renamed to "-old" for clarity.

As of Spring 2016, major updates are being done to the prototype sections of the document (NP02 and NP04).

## Overview
This repository contains materials of the DUNE Computing Model. The Computing Model
document serves the following needs:
* It fulfills the old mandate of LBNE for such document to be created
* It serves as a point of reference for resource and other requirements for DUNE Computing

Historically, it is continuation of the previous planning and documentation effort undertaken by LBNE,
which produced two document of interest:
* Software and Computing Plan (LBNE DocDB 7818)
* The "Requirements" which were meant to ensure agreement among the collaborators regarding policies and technology choices to be adapted (LBNE DocDB 8546)

## Drivers
* Challnges in DAQ and its interface to offline
* Scalability of computing resources
* Potential reliance on HPC for difficult reconstruction cases

## Computing Model as a "Living Document"
The initial draft of the Computing Model was completed in the Fall of 2015. It is meant to be a "living document" which will change as DUNE goes through the R&D, prototyping and other stages in its evolution.

## Known Unknowns
The work on DAQ and other DUNE online systems is just starting in 2015. While there is valuable understanding being gained already, it is not feasible at this point to produce reliable estimates for data reduction factors to be achieved in DAQ. This situation is likely to persist for quite some time as progress is made in R&D. In the meantime, it is helpful to consider the DUNE Computing Model under two sets of assumptions, i.e. assuming a significant (an order of magnitude) data reduction factor in one case and a "bad case" scenario where there is only a factor of two achieved over nominal values.

## DAQ
DAQ in DUNE is an advanced and deep subject, and as such it's best described in a separate section.

## Timeline
DUNE will go through a few distinct periods of development and operation in the period of time preceding its commissioning in mid-2020s and beyond, during its operation. To best reflect the evolving nature of the project, the Computing Model will be specified for two time periods - prototype and R&D work (2015-2020) and the workup to actual experiment (2020-).



