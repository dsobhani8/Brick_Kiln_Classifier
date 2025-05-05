# Brick Kiln Classifier

We can not upload our actual dataset because it is confidential; however, in this repo we share our code for preprocessing and training. In the ResNet and VGG code we include synthetic data to demonstrate that the code runs.

We use the Sentinel-2 Level-2A data collection. Sentinel-2 images were acquired between January 1, 2025 and April 13, 2025 with cloud pixel percentage lower than 10\%. The period of January to April was chosen because brick kilns operate during these dry months. We focus solely on the Dhaka metropolitan area which has over 23 million people, is the largest city in Bangladesh and has the most brick kilns. 

The satellite image we download from the Copernicus browswer had the following attributes:

\begin{description}
  \item[Name:] \texttt{S2B\_MSIL2A\_20250405T042659\_N0511\_R133\_T46QBM\_20250405T063356.SAFE}
  \item[Size:] 1170\,MB
  \item[Sensing time:] 2025-04-05T04:26:59.024000Z
  \item[Platform short name:] SENTINEL-2
  \item[Instrument short name:] MSI
\end{description}

**The descriptions of each file follow:**

CNNDataset Builder.ipynb: Building the dataset to train both CNNs

Git_VGG_Kiln_Classifier.ipynb: VGG-16 linear-probe training and fine-tuning.

Git_VGG_Kiln_Classifier.ipynb: ResNet linear-probe training and fine-tuning.

faster_r_cnn.ipynb: Faster-R CNN training,

Faster_R_CNN_dataset.ipynb: Building the dataset to train the Faster-R CNN
