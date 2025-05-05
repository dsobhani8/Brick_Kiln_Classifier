# Brick Kiln Classifier

We can not upload our actual dataset because it is confidential; however, in this repo we share our code for preprocessing and training. In the ResNet and VGG code we include synthetic data to demonstrate that the code runs.

The satellite patch we download from the Copernicus browswer had the following attributes:

To acquire the satellite imagery visit the \href{https://browser.dataspace.copernicus.eu/}{\underline{Copernicus Browser}},apply the filters described Section \ref{sec:data}, click search, and select the file called \texttt{S2B\_MSIL2A\_20250405T042659\_N0511\_R133\_T46QBM\_20250405T063356.SAFE}. The full file summary follows:

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
