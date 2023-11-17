## Steps

- panorma - create a panorama of the images

- split - split the panorama into small images

- filter - filter images that are not gonna work

- augment - augment images randomly to create larger dataset

- annotate - manually annotate images by clicking on a berry or leaf

- segment - pass the annotations through FastSAM to get the segmentation

- validate - validate the segmentation and get the contours

- classify - classify the berry by lifecycle stage (unripe, ripe, overripe, spoiled)

- format - format the dataset and create a yolo compatible dataset

- train - train the model!


## Models For Transfer Learning
 
https://www.kaggle.com/models/rishitdagli/plant-disease
https://www.kaggle.com/models/agripredict/disease-classification