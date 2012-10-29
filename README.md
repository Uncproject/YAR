CAGEO Benchmark Case studies 2012.  Watt Field for history matching different geological scenarios/interpretations.
=================

OVERVIEW

This case study was developed to test techniques that deal with many different geological scenarios that are hard in practice to parameterise between for problems like history matching and uncertainty quantification.  As such a set of 81 realisations of a simulation model are developed which along with a set of uncertain relative permeability measurements create many possible models of the reservoir which can all be calibrated to the production data.  The task was to choose only one or many of these models (and which ones) for making predictions.
In this folder find the following files and folders: -

MODEL SCENARIOS
PRODUCTION DATA
RAW DATA
REL_PERM_DATA
Appendix.pdf

For more information on the field and the field study please read appendix.pdf.  The model data is contained in the other 4 folders.  Each of the 81 scenarios is found inside the MODEL SCENARIOS folder.  The labelling convention is explained in appendix.pdf Table 1.  Choose whichever scenario you wish from within this section.

For each of the 81 scenarios there is an option to either use your own model grid, developed from the provided data or use a predefined grid model we have provided. There is an object and pixel model option provided in the INCLUDE directory of each scenario.  When running the simulation model you must direct the relevant part of the data deck for the porosity and permeability fields to the relevant modelling approach choice. 

(e.g. INCLUDE  'INCLUDE\OBJECT\G1_CO1_object_Perm.inc')

Production data to match to is provided in the PRODUCTION DATA folder including some estimates of noise in the data generated by a 10% noise assumption.  People studying this problem are encouraged to evaluate the noise level themselves if they see fit.

The REL_PERM_DATA folder contains a number of measured relative permeability curves measured for the 2 key facies (Channel sand and overbank/fine sand).  Any or all of these curves can be used in the study.

The final folder is the RAW DATA folder which contains all the raw data required to (a) regenerate the geomodel of the reservoir should you want to create your own models and (b) the simulation grid files ordered and listed as in Table 1 of the appendix.

QUESTIONS

If you have any questions about the field please contact heriot-watt university or dan.arnold@pet.hw.ac.uk.

