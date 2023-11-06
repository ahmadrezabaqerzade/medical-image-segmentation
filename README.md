<div align="center">
  <a href="https://www.kaggle.com/competitions/uw-madison-gi-tract-image-segmentation">
    <img src="https://github.com/ahmadrezabaqerzade/medical-image-segmentation/blob/main/images/cover.png" alt="Logo" width="" height="200">
  </a>

<h1 align="center">Medica Image Segmentation</h1>
</div>

This repository serves as the template , focusing on medical image segmentation. Explore and utilize this template to kickstart your own medical image segmentation projects, leverage best practices, and accelerate your journey into the world of precise medical diagnostics through deep learning.

## 1. Problem Statement
Segmentation in artificial intelligence is one of the very important areas that aims to determine the precise boundaries of one or multiple targets, requiring each pixel of the image to be labeled. Segmentation has various types, with three commonly used ones being semantic segmentation, instance segmentation, and panoptic segmentation (instance segmentation + semantic segmentation). Segmentation can be used in various fields such as medical image segmentation for disease diagnosis and urban image segmentation for self-driving cars, and so on.

 <img src="https://github.com/ahmadrezabaqerzade/medical-image-segmentation/blob/main/images/spacenet_aerial_hero.jpg" width="500" height="300">  <img src="https://github.com/ahmadrezabaqerzade/medical-image-segmentation/blob/main/images/city%20scape.png" width="500" height="300">  <img src="https://github.com/ahmadrezabaqerzade/medical-image-segmentation/blob/main/images/535342_1_En_16_Fig1_HTML.png" width="300" height="300"> 

Segmentation is also one of the most commonly used areas in the medical field for disease diagnosis. In medical imaging, segmentation includes:

1. Segmentation of brain MRI images for detecting brain tumors and studying neurological diseases.
2. Segmentation of lung images for lung cancer diagnosis and prognosis.
3. Segmentation of breast MRI images for detecting normal breast tissue and breast cancer, among others.

Segmentation of gastrointestinal images obtained with integrated magnetic resonance imaging (MRI) and MR-Linacs also aids in the detection of gastrointestinal tumors. Diagnosing gastrointestinal tumors is one of the challenges faced by doctors in treating patients. Approximately half of the patients are eligible for radiation therapy, and this procedure should be performed in a way that does not harm the intestines and stomach. By using artificial intelligence (specifically in the field of segmentation), these areas can be identified, helping doctors to expedite patient treatment. Treating patients using this method can reduce daily treatment time from one hour (which can be difficult for patients) to 15 minutes.

### <code style="color : red">Challenges</code>:

* **Complexity of images:** Medical images related to the gastrointestinal system have complex structures that can make the analysis and accurate diagnosis of cancerous masses difficult.

* **Size and shape variations of tumors:** Gastrointestinal tumors can have different sizes and shapes, which can make their accurate and reliable diagnosis challenging for physicians.

* **Natural variations in the gastrointestinal system:** The presence of natural variables such as bowel movements, digestion, and gastric motility can make the diagnosis of gastrointestinal tumors more difficult and lead to errors and incorrect results in segmentation.
### <code style="color : green">AI targets</code>:

* **Accurate identification of cancerous masses:** As mentioned, for high doses of X-ray radiation, they should be directed towards the tumor and should not cause any harm to the stomach and intestines. Therefore, tumor segmentation needs to be done with high accuracy.

* **Reduction of errors caused by different dimensions of masses:** Cancerous masses can have various dimensions, and their type should be detected in all dimensions.Misdiagnosing any type of these masses with different dimensions has a detrimental effect on the treatment of patients.

### <code style="color : green">Medical targets</code>:

* **Faster detection of masses and quicker treatment process:** According to studies conducted by Carbone universities, in normal conditions and manually, it takes approximately 1 hour to identify the precise area of these masses for daily treatment and deliver radiation to the masses. This time can be reduced to 15 minutes using artificial intelligence.

* **Early detection of masses:** Early detection improves the treatment process and helps physicians diagnose these masses earlier and initiate treatment before the patient's condition worsens. Artificial intelligence can increase the chances of patients' survival.

* **Accurate and more reliable diagnosis:** Although manually determining the area of masses by physicians is somewhat accurate, in some cases, it may introduce human errors and jeopardize the patient's health. Using artificial intelligence helps make this process more reliable.


## 2. Related Works
This section explores existing research and solutions related to medical image segmentation. 

## 3. The Proposed Method
Here, the proposed approach for solving the problem is detailed. It covers the algorithms, techniques, or deep learning models to be applied, explaining how they address the problem and why they were chosen.

## 4. Implementation
This section delves into the practical aspects of the project's implementation.

### 4.1. Dataset
Under this subsection, you'll find information about the dataset used for the medical image segmentation task. It includes details about the dataset source, size, composition, preprocessing, and loading applied to it.
[Dataset](https://drive.google.com/file/d/1-2ggesSU3agSBKpH-9siKyyCYfbo3Ixm/view?usp=sharing)

### 4.2. Model
In this subsection, the architecture and specifics of the deep learning model employed for the segmentation task are presented. It describes the model's layers, components, libraries, and any modifications made to it.

### 4.3. Configurations
This part outlines the configuration settings used for training and evaluation. It includes information on hyperparameters, optimization algorithms, loss function, metric, and any other settings that are crucial to the model's performance.

### 4.4. Train
Here, you'll find instructions and code related to the training of the segmentation model. This section covers the process of training the model on the provided dataset.

### 4.5. Evaluate
In the evaluation section, the methods and metrics used to assess the model's performance are detailed. It explains how the model's segmentation results are quantified and provides insights into the model's effectiveness.

