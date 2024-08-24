# ReefNet Dataset Repository

Welcome to the ReefNet dataset repository. This repository hosts all the code, data, and results related to the ReefNet project. Currently, the primary resource available here is the ReefNet dataset.

## Dataset

The ReefNet dataset is a comprehensive collection of annotated coral images designed for training and evaluating machine learning models in coral classification. The dataset includes annotations and images that support the study of coral species across different geographic regions.

### Download the Dataset

The dataset is hosted on HuggingFace. You can access and download the dataset using the following links:

- [ReefNet Dataset on Hugging Face](https://huggingface.co/datasets/ReefNet/ReefNet-1.0)


### Dataset Structure

The dataset is organized as follows:

- **`All_ReefNet_annotations.csv` (2.98 GB)**  
  Contains all annotations available in the main ReefNet dataset, along with the associated metadata.

- **`Metadata_All_ReefNet_annotations.xlsx` (11 KB)**  
  Contains metadata for the `All_ReefNet_annotations.csv` file, describing the meaning of the column names.

- **`ReefNet_RSG-TestDataset_annotations.csv` (2.42 MB)**  
  Contains the annotations of the Red Sea Global (RSG) test dataset, used in Experiment 2 of the main paper. This dataset was collected by Red Sea Global (RSG) in the Al-Wajh lagoon in the Red Sea (26.4°N, 36.4°E) in 2022 and was previously stored as a private source within CoralNet.

- **`ReefNet_RSG-TestDataset_images.zip` (1.21 GB)**  
  Contains the images from the Red Sea Global (RSG) test dataset. This dataset is used in Experiment 2 of the main paper and was collected by Red Sea Global (RSG) in the Al-Wajh lagoon in the Red Sea.

- **`Metadata_ReefNet_by_CoralNet_sources.xlsx` (33 KB)**  
  Provides an overview of the CoralNet sources from which the ReefNet dataset was compiled, including attribution to the original creators and metadata such as geographic location and average image resolution. The first sheet explains the content and column names of the other sheets.

- **`ReefNet_labelmapping.xlsx` (79 KB)**  
  Provides an overview of the label set mapping performed to consolidate the ReefNet dataset from the separate CoralNet sources. The first sheet provides metadata explaining the meaning of the content and column names of the other sheets.

- **`ReefNet_RSG-TestDataset_labelmapping.xlsx` (33 KB)**  
  Details the label set mapping performed for Experiment 2 in the main paper, merging labels from the main ReefNet dataset with the RSG-TestDataset. The first sheet explains the meaning of the content and column names of the other sheets.

- **`sources_data.csv` (12.8 KB)**  
  This file provides detailed information about all the sources used in the ReefNet dataset, including key metadata and URLs. The columns in this file include:
  
  - **Source**: The name of the source from CoralNet.
  - **URL**: The direct link to the source on CoralNet.
  - **ImagesURL**: The base URL structure for accessing the images associated with each source.
  - **ImagesNumber**: The total number of images with confirmed annotations available for that source.
  - **FirstImageNumber**: The starting index or identifier for the first image in the source.

  This file is crucial for users who wish to download images directly from CoralNet using their own methods or with the provided script, ensuring that all images are correctly linked to their respective annotations.

### Downloading Images and Annotations

To download the full set of images from CoralNet and the associated annotations, please use the download script provided in our GitHub repository. This script is designed to handle the specific structure of image storage on CoralNet and will automate the process for you.

You can find the script and detailed instructions in our GitHub repository here:

- **[ReefNet Image Download Script on GitHub](https://github.com/ReefNet-Project/coralnet_crawler)**

Follow the instructions in the repository to download the images and annotations efficiently. The script ensures that all images are correctly organized and matched with the provided annotations.

## Contact

For any questions or issues regarding the dataset, please contact:

- Yahia Battach
- yahia.battach@kaust.edu.sa

We hope this dataset aids in your research and contributes to the advancement of marine biology and machine learning applications.

---

More updates, including code and results, will be added to this repository soon. Stay tuned!
