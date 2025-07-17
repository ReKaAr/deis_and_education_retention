# deis_and_education_retention
Code to replicate analysis of the DEIS programme in Ireland and its impact on educational retention levels.

The code is broken into three sections. The first two are focused on data preparation, and the third is the analyses themselves.

Part 1 is to prepare the SPA data and is conducted through Python.
Part 2 is to prepare the different methods of clustering schools and is conducted in R.
Part 3 contains the difference-in-difference analyses and is conducted through R.

The dataset used for the analysis is included as a csv file. The sources used to compile the dataset were as follows:

The school-level data required can be sourced from annual csv files released by the Department of Education from this link: https://www.gov.ie/en/department-of-education/collections/data-on-individual-schools/#:~:text=Reports%20showing%20enrolment%20figures%20in%20individual%20post-primary%20schools%2C,international%20statistical%20reports%20are%20available%20at%20Education%20Statistics

Data for the Pobal HP scores was sourced from the Trutz-Hasse longitudinal study of area-level deprivation in Ireland for the years 1999-2006 from the following link: http://trutzhaase.eu/services/hp_deprivation_index/ For the years 2011-2022 the Pobal HP scores were sourced from Pobal's online database: https://www.pobal.ie/pobal-hp-deprivation-index/
