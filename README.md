# detection_on_GroceryDataset
FMCG (Fast-Moving Consumer Goods) brands require insights into retail shelves to help them improve their sales. One such insight comes from determining how many products of their brands’ are present versus how many products of competing brands are present on a retail store shelf. 

Problem Statement: ​

​1. Given a grocery store shelf image, detect all products present in the shelf image (detection only at product or no-product level) ​

​2. Accuracy of at least 0.8 the mAP on the test set. (More the better) ​

**Dataset**: 
https://github.com/gulvarol/grocerydataset

https://storage.googleapis.com/open_source_datasets/ShelfImages.tar.gz

Step 1: Data Preparation​

* prepared the Grocery Dataset to train an object detection model to detect products from a store shelf image.​

* Gather the datasource from the given links​

* Understand the structure of the dataset and the annotations,​

Step 2: Organize the data into training and testing splits.​

​Created two different dataframes from train and test sets.​

​I have implemented functions to prepare pairs of images and corresponding annotation files (.txt) for object detection.​


Step3: Building the Detection Model and Evaluation:​

​I Have selected Pytourch as deep learning framework.​

​YOLO v4 Implimentation:​

​YOLOv4 (You Only Look Once version 4) is an object detection algorithm that improves speed and accuracy. It's used in computer vision tasks to efficiently detect and classify objects within images or videos. YOLOv4 is known for its real-time processing capabilities, making it suitable for applications like surveillance, autonomous vehicles, and object recognition in various domains.​
