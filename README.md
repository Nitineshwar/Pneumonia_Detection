# Pneumonia_Detection
## Project Proposal
#### We have all atleast heard about pneumonia and its affect on the lungs ever since COVID-19. COVID presented danger to us because of its affect on our lungs ,the infection might be different from  the bacterial and viral forms of pneumonia but still this project serves as a first step to identifying pneumonia.
#### Although this model is used to just detect if pneumonia is present or not,this base model could be used to detect areas of lungs so that we can classify between bacterial(focal) and viral(interstitial) pneumonia by implementing further computer vision techniques such as image segementation.
#### The dataset that I used is a slightly modified version from [here](https://data.mendeley.com/datasets/rscbjbr9sj/2). The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).I modified it to get 100 validation images for each class.The dataset size was around 1-1.2GB
## Usage
#### The DATA folder contains the Chest X-ray images , the Pneumonia Detection notebook contains the source code of the CNN model and predictions notebook contains final predictions on our trained model.
#### This Blog [post](https://www.kaggle.com/grayphantom/cnn-pneumonia-detection/notebook) gives the detailed walk through of model building and training.
## Similar apps
####
