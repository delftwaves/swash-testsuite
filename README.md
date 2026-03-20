# SWASH test suite

[![release](https://img.shields.io/badge/release%20-%20v11.01%20-%20brightgreen?color=success)]()
[![site](https://img.shields.io/badge/sourceforge%20-%20site%20-%20blue?logo=sourceforge&color=informational)](https://swash.sourceforge.io)
[![repo](https://img.shields.io/badge/gitlab%20-%20repo%20-%20blue?logo=gitlab&color=informational)](https://gitlab.tudelft.nl/citg/wavemodels/swash)
[![image](https://img.shields.io/badge/delftwaves%2Fswash%20-%20image%20-%20blue?logo=docker&color=informational)](https://hub.docker.com/r/delftwaves/swash)
[![license](https://img.shields.io/badge/license%20-%20GPL_v3%20-%20orange?color=important)](/LICENSE)

SWASH is a general-purpose numerical tool for simulating unsteady, non-hydrostatic, free-surface, rotational flow and transport phenomena in coastal waters as driven by waves, tides, buoyancy and wind forces.
It provides a general framework for describing wave transformations from deep water to a beach, port or harbour, complex changes to rapidly varied flows, and density driven flows in coastal seas, estuaries, lakes and rivers.

This repository contains a collection of test cases for [SWASH](https://gitlab.tudelft.nl/citg/wavemodels/swash).

The aim of the SWASH test suite is twofold.

* To test the SWASH model for regression testing due to feature updates and code changes.
* To familiarize (new) users with setting up and running the SWASH model.

In the `testcases` folder, you will find a variety of test cases. Each test case contains input files as well as output files for verification. Run instructions are also provided.

For the installation of SWASH on your own computer, HPC cluster, or in the cloud, click [here](https://delftwaves.github.io/swash-docs/getting_started/install.html).
