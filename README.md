# AN OPEN-SOURCE SEMI-AUTOMATED PROCESSING CHAIN FOR URBAN OBIA CLASSIFICATION


You will find on this repository the jupyter notebook of the processing chain developed with the open-source software [GRASS GIS](https://grass.osgeo.org/).

![alt tag](http://www.mdpi.com/remotesensing/remotesensing-09-00358/article_deploy/html/images/remotesensing-09-00358-ag.png)

[Reference article in MDPI Remote Sensing journal](http://www.mdpi.com/2072-4292/9/4/358)

[Remote Sensing special issue](http://www.mdpi.com/journal/remotesensing/special_issues/GEOBIA2016)

Keywords
--------
* Remote Sensing
* Object Based Image Analysis 
* Urban Area
* Land cover mapping
* Supervised classification
* Segmentation
* Optimization
* GRASS GIS

Abstract
--------
This study presents the development of a semi-automated processing chain for urban object-based land-cover and land-use classification. The processing chain is implemented in Python and relies on existing open-source software GRASS GIS and R. The complete tool chain is available in open access and is adaptable to specific user needs. For automation purposes, we developed two GRASS GIS add-ons enabling users (1) to optimize segmentation parameters in an unsupervised manner and (2) to classify remote sensing data using several individual machine learning classifiers or their prediction combinations through voting-schemes. We tested the performance of the processing chain using sub-metric multispectral and height data on two very different urban environments: Ouagadougou, Burkina Faso in sub-Saharan Africa and Liège, Belgium in Western Europe. Using a hierarchical classification scheme, the overall accuracy reached 93% at the first level (5 classes) and about 80% at the second level (11 and 9 classes, respectively).

Acknowledgments
---------------
This work was funded by the Belgian Federal Science Policy Office (BELSPO) (Research Program for Earth Observation STEREO III, contract SR/00/304 - as part of the [MAUPP project](http://maupp.ulb.ac.be) and by Moerman research program of ISSeP [SmartPop project](http://www.issep.be/smartpop).

Cite this code
---------------
Please use the following DOI for citing this code [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1290492.svg)](https://doi.org/10.5281/zenodo.1290492)

Recent developments
---------------
The processing chain evolved throught more advanced segmentation optimization strategy (called SPUSPO [1][2]) that allow for unsupervised optimization on mutliple partitions of the scene (local approach instead of global approach implemented here [3]). The most recent version of our processing chain is available here: [https://github.com/tgrippa/Semi_automated_OBIA_processing_with_local_USPO](https://github.com/tgrippa/Semi_automated_OBIA_processing_with_local_USPO) 

[1] Georganos, Stefanos, Tais Grippa, Moritz Lennert, Sabine Vanhuysse, Brian Johnson, and Eléonore Wolff. “Scale Matters: Spatially Partitioned Unsupervised Segmentation Parameter Optimization for Large and Heterogeneous Satellite Images.” Remote Sensing 10, no. 9 (September 9, 2018): 1440. [https://doi.org/10.3390/rs10091440](https://doi.org/10.3390/rs10091440).

[2] Georganos, Stefanos, Taïs Grippa, Moritz Lennert, Sabine Vanhuysse, and Eleonore Wolff. “SPUSPO: Spatially Partitioned Unsupervised Segmentation Parameter Optimization for Efficiently Segmenting Large Heterogeneous Areas.” In Proceedings of the 2017 Conference on Big Data from Space (BiDS’17), 2017. [https://goo.gl/yRBwPQ](https://goo.gl/yRBwPQ).

[3] Grippa, Tais, Stefanos Georganos, Sabine Vanhuysse, Moritz Lennert, and Eléonore Wolff. “A Local Segmentation Parameter Optimization Approach for Mapping Heterogeneous Urban Environments Using VHR Imagery.” In Proceedings Volume 10431, Remote Sensing Technologies and Applications in Urban Environments II. IEEE, 2017. [https://doi.org/10.1117/12.2278422](https://doi.org/10.1117/12.2278422).
