# BeehoneySegmentation
BeehoneySegmentation is a collection of images of honeycombs of apis mellifera bees containing capped honey. This repository not only contains images, but also contains the training results of different deep learning algorithms to solve automatic segmentation in capped honey in bee panels. More information can be found in the paper titled: "Capped honey segmentation in honey combs based on deep learning approach".

## How to cite this
More information about the aim of our work can be found in our paper. If you use this dataset, make sure you cite this work as:
Latex:
```latex
@article{RODRIGUEZLOZANO2024109573,
title = {Capped honey segmentation in honey combs based on deep learning approach},
journal = {Computers and Electronics in Agriculture},
volume = {227},
pages = {109573},
year = {2024},
issn = {0168-1699},
doi = {https://doi.org/10.1016/j.compag.2024.109573},
url = {https://www.sciencedirect.com/science/article/pii/S0168169924009645},
author = {Francisco J. Rodriguez-Lozano and Sergio R. Geninatti and José M. Flores and Francisco J. Quiles-Latorre and Manuel Ortiz-Lopez},
keywords = {Deep learning, Image segmentation, Beekeeping, Precision apiculture, Apiculture},
abstract = {Honey is the food stored by honey bees for periods when it is scarce in the field as well as being a product that is consumed worldwide by humans. Each hive generates different amounts of honey depending on the population of the bee hive, health state or environmental factors. In fact, the reserves of honey provide beekeepers with a double function: to predict the amount of honey that can be obtained and to analyze the state of the bee colonies. The assessment of honey reserves is commonplace in scientific research related to the health of bee colonies, genetic improvement or environmental issues, and emerging technologies can provide useful tools to evaluate honey stored in hives. In this context, this work proposes a methodology to detect the honey areas in high resolution photographs automatically using methods based on deep learning. Specifically, the methodology follows a “divide and conquer” approach where the images are separated into tiles with overlapping areas that are used by a semantic segmentation algorithm based on Feature Pyramid Network (FPN), detecting the honey in each tile to finally merge the tiles back into the complete image. The proposal has been compared with different feature extractors (backbones) and other semantic segmentation models, obtaining on average accurate results above 90% and 87% in the Dice score and IOU metrics respectively.}
}
```
IEEE format: F. J. Rodriguez-Lozano, S. R. Geninatti, J. M. Flores, F. J. Quiles-Latorre, and M. Ortiz-Lopez, “Capped honey segmentation in honey combs based on deep learning approach,” Computers and Electronics in Agriculture, vol. 227, p. 109573, Dec. 2024, doi: 10.1016/j.compag.2024.109573.

APA format: Rodriguez-Lozano, F. J., Geninatti, S. R., Flores, J. M., Quiles-Latorre, F. J., & Ortiz-Lopez, M. (2024). Capped honey segmentation in honey combs based on deep learning approach. Computers and Electronics in Agriculture, 227, 109573. https://doi.org/10.1016/j.compag.2024.109573.

## Dataset link
The dataset requires approximately 12 GB of free disk space, and it is available at the following web [Link](https://drive.google.com/file/d/1-JG66yVVnm9SZIfpIGLrMdevm55-lVg1/view?usp=sharing).

## Dataset folders description
After downloading and unzipping the zip file from the previous link, you can find the following folders:

***- Test_images:*** Set of images used to test the performance of the methods tested in the paper with data that have not been used for training.

***- Test_predictions:*** Prediction results of all methods tested in the paper for the test set.

***- Trained_models:*** Models trained with the training and validation set for use and comparison.

***- Train_images:*** Set of images used to train the models.

***- Training_loss_evolution:*** Binary cross-entropy loss values evolution per epoch for training stage for all tested methods in the paper.

***- Train_predictions:*** Prediction results of all methods tested in the paper for the training set.

***- Validation_images:*** Set of images used to test the performance in the training stage.

***- Validation_predictions:*** Prediction results of all methods tested in the paper for the validation set.
