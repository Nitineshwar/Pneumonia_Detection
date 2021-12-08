# Pneumonia_Detection
## Project Proposal
#### This Blog [post](https://www.kaggle.com/grayphantom/cnn-pneumonia-detection/notebook) gives the detailed walk through of model building and training.
#### We have all atleast heard about pneumonia and its affect on the lungs ever since COVID-19. COVID presented danger to us because of its affect on our lungs ,the infection might be different from  the bacterial and viral forms of pneumonia but still this project serves as a first step to identifying pneumonia.
#### Although this model is used to just detect if pneumonia is present or not,this base model could be used to detect areas of lungs so that we can classify between bacterial(focal) and viral(interstitial) pneumonia by implementing further computer vision techniques such as image segementation.
#### The dataset that I used is a slightly modified version from [here](https://data.mendeley.com/datasets/rscbjbr9sj/2). The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).I modified it to get 100 validation images for each class.The dataset size was around 1-1.2GB
## Usage
#### The `DATA` folder contains the Chest X-ray images , the `Pneumonia Detection` notebook contains the source code of the CNN model building and training, `final_cnn_model` is our final saved model for predictions,`predictions` notebook contains final predictions on our final model.
![image](https://user-images.githubusercontent.com/39852450/145150778-8613306a-3b3a-4574-8a37-a82ab64c3c0a.png) ![image](https://user-images.githubusercontent.com/39852450/145150905-bedec617-abb8-4c1f-b8db-2be6e8f79581.png)![image](https://user-images.githubusercontent.com/39852450/145151045-18ee3305-208e-451a-b582-0beded243137.png)



## Similar apps
- Ali Zamani's [one](https://www.kaggle.com/alizmn/pneumonia-detection-with-cnn-acc-91-7-recall-95-6)
- Cinni Patel's [one](https://www.kaggle.com/cinnipatel/97-accuracy-on-xray-precision-recall-f1-score)
- Koh's [one](https://www.kaggle.com/minfa1207/cnn-pytorch-loss-0-9991-acc-87-6)
