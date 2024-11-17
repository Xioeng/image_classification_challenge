This project contains the base code for the challenge https://www.kaggle.com/competitions/fiu-cap5610-spring22/overview.
A deep learning model was built to classify objects in images into 4 classes 'Apparel', 'Accessories', 'Personal Care', 'Footwear'
The data structure is given as the files:

-`train.csv` - the training set.
- `test.csv` - the test set
- `sample_submission.csv` - a sample submission file in the correct format-
- `images` - folder containing all the train and test images

The best-performing model was built using a pre-trained DeseNet201 architecture plus a 4-layer fully connected network, achieving the highest challenge accuracy: 99.51%. 
