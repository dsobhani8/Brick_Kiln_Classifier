# Brick Kiln Classifier

We can not upload our actual labels for kiln location because it is confidential; however, in this repo we share our code for preprocessing and training. In the ResNet and VGG code we include synthetic data to demonstrate that the code runs.

We use the Sentinel-2 Level-2A data collection. Sentinel-2 images were acquired between January 1, 2025 and April 13, 2025 with cloud pixel percentage lower than 10\%. The period of January to April was chosen because brick kilns operate during these dry months. We focus solely on the Dhaka metropolitan area which has over 23 million people, is the largest city in Bangladesh and has the most brick kilns. 



**The descriptions of each file follow:**

CNNDataset Builder.ipynb: Building the dataset to train both CNNs

Git_VGG_Kiln_Classifier.ipynb: VGG-16 linear-probe training and fine-tuning.

Git_VGG_Kiln_Classifier.ipynb: ResNet linear-probe training and fine-tuning.

faster_r_cnn.ipynb: Faster-R CNN training,

Faster_R_CNN_dataset.ipynb: Building the dataset to train the Faster-R CNN
