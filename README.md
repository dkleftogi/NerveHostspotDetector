# Development of a computational framework to detect and quantify nerve hotspots

The utility of this code is to process data from mass cytometry imaging technologies and identify areas in the images that represent possible nerve elements. 

To do so we will utilise pixel based information and the elements we will find will be called "hotspots". They represent proxies of nerves and their presence is supported by the expression of nerve specific antibodies in panel.

Here we provide codes and datasets required to reproduce the framework.

## Publication

Title: NOT YET

Journal: NOT YET

Published: work in progress...

## Code Description

The framework is presented using an R Markdown that implement all parts of the analysis we have implemented so far. 

It is mainly used to load the data from two different segmentations, process the data at the pixel level and combined them with the nuclei-based segmentation data that represent single-cells.


Important note for users

Please modify all paths found in the R markdowns and change them to your computer's file system. 

## Data Sources

For illustration purposes we provide data from 3 breast cancer patients without any other clinical information that is sensitive. 

This is purely done for educational and research purposes only.

The full cohort of breast cancer patients is courtesy of CCBIO, the data are not published yet and the contact person is Dr Kenneth Finne (kenneth.finne@uib.no) 


#### Releases

5-Jul-2024 : Git initialisation and first release of the pipeline


## Contact

Comments and bug reports are welcome, please email: Dimitrios Kleftogiannis (dimitrios.kleftogiannis@uib.no)

We are also interested to know about how you have used our source code, including any improvements that you have implemented.
 
You are free to modify, extend or distribute our source code, as long as our copyright notice remains unchanged and included in its entirety. 

## License

This project is licensed under the MIT License.

Copyright 2024, NeuroSysMed centre of clinical treatment research, University of Bergen (UiB), Norway

You may only use the source code in this repository in compliance with the license provided in this repository. For more details, please refer to the file named "LICENSE.md".
