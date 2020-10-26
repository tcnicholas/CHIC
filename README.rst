CHIC-1
=============================

Supporting dataset and example plotting script for:
"Understanding the geometric diversity of inorganic and hybrid frameworks through structural coarse-graining"
Thomas C. Nicholas, Andrew L. Goodwin, Volker L. Deringer
DOI: '10.1039/d0sc03287e'_

Structure files
------------

* XYZ format
* CIF format

Structures are separated into material families as described in the journal publication.  All A(B)-sites have been reported as Arseninc (Boron).  This facilitates compatability with standard programs that require "real" chemical species input.

Data from publication
------------

Contained within the data_from_publication folder, separated into material families are the following data values for each structure:

* compound reference (e.g. the CSD/ICSD reference code, where available);
* compound name;
* MDS coordinate 1;
* MDS coordinate 2;
* Tetrahedral (T) density (defined as metal atoms per unit volume (nm-3) for the coarse-grained and scaled structures);
* A-site heterogeneity (defined in the journal publication).

Additionally, the relative distributions of each material family is included in the file "relative_distributions.csv".  We define the relative distribution as:
The standard deviation of the SOAP distance in MDS (2-dim) space of all points in a given material class from their respective centre of mass, normalised such that the silica polymorphs have a relative distribution of 1.0.

Plotting script
------------

An example plotting script used to generate the publication figures is given in the Juypter Notebook file (also given here as an HTML file).

.. _DOI: http://doi.org/10.1039/d0sc03287e

