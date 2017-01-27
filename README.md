AN OPEN-SOURCE SEMI-AUTOMATED PROCESSING CHAIN FOR URBAN OBIA CLASSIFICATION
============================================================================
You will find on this repository the jupyter notebook of the processing chain developed with the open-source software [GRASS GIS](https://grass.osgeo.org/).

[Reference article in MDPI Remote Sensing journal](http://www.mdpi.com/journal/remotesensing/special_issues/GEOBIA2016)

[GEOBIA2016 conference's Remote Sensing special issue webpage](http://www.mdpi.com/journal/remotesensing/special_issues/GEOBIA2016)

Keywords
--------
* Remote Sensing
* Object Based Image Analysis 
* Urban Area
* Land cover mapping

Abstract
--------
This study presents the development of a semi-automated processing chain for OBIA urban land-cover and land-use classification. The processing chain is implemented in Python and relies on existing the open-source software GRASS GIS and R. The complete tool chain is available in open-access and adaptable to specific user needs. For automation purpose, we developed two GRASS GIS add-ons allowing (1) to optimize segmentation parameters in an unsupervised manner and (2) to classify remote sensing data using several individual machine learning classifiers or their predictions combination through voting-schemes. We tested the performance and the transferability of the processing chain using sub-metric multispectral and height data on two very different urban environments: Ouagadougou, Burkina Faso in sub-Saharan Africa and Liège, Belgium in Western Europe. Using a hierarchical classification scheme, overall accuracy reached are about 0.80 at the second level (9 and 11 classes) and 0.93 at the first level (5 classes).


Acknowledgments
---------------
This work was funded by the Belgian Federal Science Policy Office (BELSPO) (Research Program for Earth Observation STEREO III, contract SR/00/304 - as part of the [MAUPP project](http://maupp.ulb.ac.be) and by Moerman research program of ISSeP [SmartPop project](http://www.issep.be/smartpop).
