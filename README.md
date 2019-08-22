# Google Summer Of Code 2019

#### Project completed by: Lizabeth Katsnelson
---

This repository holds the scripts used to reformat CPTAC datasets for compatability with cBio portal standards. The project outline is as follows: 

* Recieve datasets from CPTAC
* Reformat using R and bash scripts
* Validate on local computer using the cBio Portal circleci validator
* Push the reformatted data to cBio Portals public datahub (https://github.com/cBioPortal/datahub/tree/master/public)
* Data validated via circleci in datahub
* Data passes validation and internal tests - ready for publishing on the private internal portal
* Test the data visualiztion tools within the internal private portal
* Data passes internal portal tests - published to public portal for use

**Note:** unpublished datasets will not be uploaded to the portal until CPTAC collaborators successfully publish their work. Unpublished datasets or embargo'd datasets are stored in the private portal.

*As of 08/2019, the only dataset that was allowed to be public was the COAD (colon adenocarcinoma) dataset. Here is the link to that dataset in the public datahub: https://github.com/cBioPortal/datahub/tree/master/public/coad_cptac_2019* 

**Acknowledgments**

Thank you to the Google Summer of Code internship for funding this project. Thank you to the wonderful mentorship of everyone at cBio Portal, specifically Jianjiong Gao (MSKCC), Ritika Kundra (MSKCC), and Priti Kumari (Dana-Farber Cancer Institute). Thank you to the CPTAC consortium for allowing us to use this data, specifcally David Fenyo (NYU). 


For more information on cBio Portal for Cancer Genomics, visit their website: https://www.cbioportal.org/
