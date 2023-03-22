# Rice-Disease
##Domain Analysis
This dataset contains 120 jpg images of disease-infected rice leaves.It is a multi class classification task. The images are grouped into 3 classes based on the type of disease. There are 40 images in each class. Classes ● Leaf smut ● Brown spot ● Bacterial leaf blight

Classes

1.Leaf smut :-It is caused by the Gram-negative bacterium Xanthomonas oryzae pv.It causes wilting of seedlings and yellowing and drying of leaves.

2.Brown spot :- Brown spot is a fungal disease that infects the coleoptile, leaves, leaf sheath, panicle branches, glumes, and spikelets. Its most observable damage is the numerous big spots on the leaves which can kill the whole leaf. 

3.Bacterial leaf blight :- Leaf smut, caused by the fungus Entyloma oryzae, is a widely distributed, but somewhat minor, disease of rice. The fungus produces slightly raised, angular, black spots (sori) on both sides of the leaves 

## Pre-Proccessing steps:

Splitting the  Data

Training: Dataset to be used while training.

Validation: Dataset to be tested against while training.

Test: Dataset to be tested against after we trained a model.   

Prefetching solves the inefficiencies from naive approach as it aims to overlap the preprocessing and model execution of the training step. In other words, when the model is executing training step n, the input pipeline will be reading the data for step n+1.

You can use prefetch transformation to overlap the work done by pipeline (producer) and the model (consumer), interleave transformation to parallelise data reading, map transformation to parallelise data transformation, cache transformation to cache data in memory or local storage and also vectorising your map transformations with the batch transformation.

Data augmentation in data analysis are techniques used to increase the amount of data by adding slightly modified copies of already existing data or newly created synthetic data from existing data. It acts as a regularizer and helps reduce overfitting when training a machine learning model.

## Result :
#### Model accuracy is 90% which is pretty good score.




