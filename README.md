## About the Project
The primary objective of this project was to construct a malware detection system using machine learning and deep learning techniques, employing the CICMalmem datasets to effectively identify memory-obfuscated malwares. Additionally, we sought to assess the resilience of the top-performing model against evasion attacks and gauge its robustness. The datasets, referred to as CIC-Malmem2022, were sourced from the Canadian Institute of Cybersecurity's open-access website. These datasets were specifically curated for memory-obfuscated malwares, with the overarching research objective being to leverage machine learning and deep learning methodologies for the detection of previously unseen, unknown malwares that the model has not been trained on. Following the development and performance assessment of the model, adversarial attacks were executed to evaluate its robustness.

# Methodology
## Data Generation 
The purpose of generating additional data is to assess the performance of the model when exposed to unfamiliar data. The original dataset, sourced from the CIC website, was primarily focused on trojans, spyware, and ransomware. To expand the diversity of malware types in our dataset, we gathered samples from various other categories, such as botnets, advanced persistent threats (APTs), keyloggers, and more. We then established a virtual environment and executed each malware sample within it, capturing memory dumps using FTK Imager software. Subsequently, we employed a tool called "volmemlyzer" to analyze these memory dump images, extracting relevant features and associated data for further examination.
![Screenshot width="10" height="10"](datasetgeneration.png)

## Training & Test Dataset creation
We have followed the below architecture to create our datasets. We have created two test datasets for testing our best performing model. 
<img src="dataset.png" width="80" height="80">

## Model Building and Evasion Attack

## Trained Models 

## References
