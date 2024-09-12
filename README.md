# BeehoneySegmentation
BeehoneySegmentation is a collection of images of honeycombs of apis mellifera bees containing capped honey. This repository not only contains images, but also contains the training results of different deep learning algorithms to solve automatic segmentation in capped honey in bee panels. More information can be found in the paper titled: "Capped honey segmentation in honey combs based on deep learning approach".

## How to cite this
More information about the aim of our work can be found in our paper. If you use this dataset, make sure you cite this work as:
Latex:
```latex
@article{Rodriguez_Lozano_2024,
	doi = {},
	url = {},
	year = 2024,
	month = {},
	publisher = {}},
	author = {},
	title = {},
	journal = {}
}
```
IEEE format: .

APA format: .

## Dataset link
The dataset requires approximately 12 GB of free disk space, and it is available at the following web [Link](https://drive.google.com/file/d/1X-zKIDUBxo5zZ5cbTbMBxr97cCm5nnH-/view?usp=drive_link).

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
