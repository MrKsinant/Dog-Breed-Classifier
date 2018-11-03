# Dog Breed Classifier

This study corresponds to the second project of Nanodegree *Deep Learning* schooled by **Udacity, Inc.** (https://eu.udacity.com), a for-profit educational organization offering massive open online courses.

Its goal is to build a "very special" **dog breed classifier**: If a dog image is submitted to the algorithm, the classifier has to detect that the image corresponds to a dog and predict the dog breed, but if a human is submitted... the classifier must detect that the image corresponds to a human and indicate the most resembling dog breed! In the case of the image corresponds to no dog nor human, the classifier only has to relate that no prediction will be done.

Building a dog breed classifier is a difficult task, and to do it, here, we have used a deep learning approach.

In this repository, the following files and folders can be found:
* The file ***dog-breed-classifier.ipynb***, the Jupyter Notebook which contains all the detailed and explained study;
* The folder *images*, which contains all the images used in the Jupyter Notebook;
* The folder *trainings*, which contains the various logs generated during the training phase of the two models built in the Jupyter Notebook, and the corresponding graphs;
* The folder *haarcascades*, which contains specific **OpenCV** (https://opencv.org) implementation of Haar feature-based cascade classifiers to detect human faces in images.

Due to the fact of the generated models weights (more than 100 Mo for each), the folder *models*, which is used in the study to store the two generated models, is not provided. The folders *lfw* and *dog_images*, which contain the complete datasets used to build our deep learning models, are not provided neither, but can be found at the location specified at the beginning of the Jupyter Notebook.

Finally, to conclude, respectively to the requirements, it can be said that the deep learning models built within this study have been constructed thanks to **PyTorch** (https://pytorch.org), the deep learning framework mainly supported and developed by **Facebook** and its **FAIR** (Facebook AI Research) team (https://research.fb.com/category/facebook-ai-research/).
