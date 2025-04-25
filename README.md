Brain Tumor Segmentation Using U-Net Attention
Brain tumors are one of the greatest dangers and life-threatening cancers, with early and accurate diagnosis is very important for patient prognosis. Magnetic Resonance Imaging (MRI) MRI is increasingly becoming the common imaging technique for the detection and assessment of brain tumors. However, still, most of the time, MRI scans are interpreted manually and face the problem of being time-consuming and requiring expert radiologists along with fallibility because the anatomy of brain tissues and tumor types is very complex. Therefore, "good precision" has created considerable demand in this field for automated solutions capable of detecting and segmenting brain tumors.

The relevance of this project stems from the fact that it is attempting to solve these problems with the use of CNNs for brain tumor segmentation. The model learns complex patterns directly from the imaging data and thus brings about reliable and consistent results owing to the deep learning approach. This not only aids radiologists in making quicker decisions but also paves the way for improved diagnosis, treatment planning, and patient monitoring.

Magnetic Resonance Imaging (MRI)
MRI is a non-invasive imaging method extensively applied in medical diagnostics, especially for brain imaging. MRI yields high-resolution images of soft tissues, which is why it is crucial for detecting abnormalities such as tumors. Various MRI modalities (e.g., T1, T2, FLAIR) image different tissue properties, enabling differentiation between tumor core, edema, and normal tissue. MRI is used as the input imaging modality for tumor segmentation in this project.

Brain Tumor Segmentation
Segmentation is the act of cutting an image into different meaningful areas. In the case of the brain tumor, it would refer to the exercise of separating the tumor areas from the healthy brain tissue. Accurate segmentation is important for treatment planning, surgical navigation, and the monitoring of disease progression. Manual segmentation is tedious and subjective, hence the need for automated methods.

Deep Learning Considering Medical Imaging
Deep learning, especially the Convolutional Neural Networks, has changed the face of medical image analysis. Hierarchical features are automatically extracted from raw data by CNNs so that it can be used for input to data-driven precise segmentation. They proved their ability over the old techniques which depend on handcrafted features, thus giving themselves a niche for application in fairly complicated tasks like tumor segmentation.

Convolutional Neural Networks (CNNs)
Therefore, CNNs are special networks used for deep learning to analyze grid-like data like images. They include convolutional layers that include filters to extract spatial features from the image. These are followed by pooling layers that reduce their dimensionality without compromising significant information. With this feature, a CNN learns patterns such as edges, shapes, and textures, all of which are critical in recognizing tumor areas in MRI scans.

Dataset: BraTS 2020
The Brain Tumor Segmentation (BraTS) dataset is a benchmark dataset for training and evaluating tumor segmentation models. The 2020 edition includes multimodal MRI scans from glioma patients with corresponding ground truth masks for tumor regions. It thus provides a diverse and complex dataset mimicking the real-world heterogeneity of tumors in the size, shape, or location aspect.

HDF5 File Format
HDF5 is a file format commonly used for storing such large numerical datasets. It is especially useful in deep learning applications due to the amount of huge training data that it handles efficiently. Thus, in this study, HDF5 is predefined to append both MRI images and segmentation masks so that fast reading and preprocessing could be done while training these images.

Evaluation Metrics
Model performance will mainly be assessed using metrics like the Dice Similarity Coefficient (DSC) and Intersection over Union (IoU), which are used to measure the overlap of predicted and ground truth masks. Dice score is one measuring unit that is highly preferred for medical segmentation because it considers both false positives and false negatives.

Flowchart
<img width="268" alt="image" src="https://github.com/user-attachments/assets/7a8ac12d-580f-489a-8fae-5ae2bc9ead1b" />
