# Google Summer Of Code 2019

This repository holds the scripts used to reformat CPTAC datasets for compatability with cBio portal standards. The project outline is as follows: 

* Recieve datasets from CPTAC
* Reformat using R and bash scripts
* Validate on local computer using the cBio Portal circleci validator
* Push the reformatted data to cBio Portals public datahub (https://github.com/cBioPortal/datahub/tree/master/public)
* Data validated via circleci in datahub
* Data passes validation and internal tests - ready for publishing on the private internal portal
* Test the data visualiztion tools within the internal private portal
* Data passes internal portal tests - published to public portal for use

** Note: ** unpublished datasets will not be uploaded to the portal until CPTAC collaborators successfully publish their work. Unpublished datasets or embargo'd datasets are stored in the private portal.
