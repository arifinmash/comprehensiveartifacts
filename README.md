## About the Project
This artifact aimed to build a machine learning and deep learning based malware detector using CICMalmem datasets, which will be able to catch the memory obsfacted malwares. Later on, we also aimed to perform evasion attacks on the best-performing model and evaluated their performance in terms of robustness. We collected the datasets named CIC-Malmem2022 for the open-access website of the Canadian Institute of Cybersecurity. This dataset was created for the memory obsfucated malwares and the research goal is to laverage the machine learning and deep learning techniques for detect the new unknown malwares which the model has not trained. Once the model is built and revealed their performance is revealed, we perform the adversarial attack to that model and observed its robustness.

# Methodology
## Data Generation 
The reason for generating data is to observe the model's performance with the unknown data. We have observed the original dataset that we obtained from the CIC website was built was for trojanhorse, spyware and ransomware. We collected malwares of more genres other than the mentioned types of the malware i.e botnet, apt (advanced persistent threat), keylogger etc. We build our virtual environment and run each malware samples there and collected the memory dump by the FTK imager software. Later on, we have used that image to analysis by a tool name volmemlyzer to extract the fratures and correspondinfg data. 
![Screenshot width="10" height="10"](datasetgeneration.png)

## Training & Test Dataset creation
We have followed the below architecture to create our datasets. We have created two test datasets for testing our best performing model. 
<img src="dataset.png" width="100" height="100">

## Model Building and Evasion Attack

## Trained Models 

## References
