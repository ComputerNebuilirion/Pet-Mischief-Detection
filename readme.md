# **COMP4423 – Computer Vision** 
### **Project - The Pet Mischief Detector**
LI Jianxi 24109859d 

Zhang Xulu 24113522d 

CHENG Keyan 24110027d 

## **Task 1: Problem Definition & Data Curation**

#### **1.1 Define Classes and Rules**

**Pets (2 classes):**
- **cat**
- **dog**

**Objects (5 classes):**
- **cup**: Easy target for cats to push
- **laptop**: Dogs might chew, cats might sit on keyboard
- **potted_plant**: Cats love digging in soil
- **vase**: Fragile, cats love knocking over
- **couch**: Added this for "safe scenario" detection

**Total: 7 classes**

#### **1.2 Curate the Dataset**

Curate dataset from COCO 2017. We mix the original train and val together.

## **Task 2: Dataset Splitting & Formatting**

- **Split the Data**: Programmatically split the curated dataset into training, validation, and test sets (e.g., 80%/10%/10%). Ensure this split is reproducible by using a fixed random seed **RANDOM_SEED = 42**. 

- **Format for Training**: Convert the dataset into the format required by the chosen detection framework (Here is YOLOv8n). Document this process and provide any conversion scripts.  

## **Task 3: Training/Fine-tuning a Vision Model**

- **Select and Train a Model**: Choose a vision model and train it on your custom dataset. Here we choose YOLOv8n.

## **Task 4: Mischief System Implementation & Evaluation**

#### **Part A: Quantitative Detector Evaluation**

#### **Part B: Qualitative System Evaluation**

The code source file folder of our project in onedrive:  [Project_Code_Group_23.zip](https://connectpolyu-my.sharepoint.com/my?id=%2Fpersonal%2F24109859d%5Fconnect%5Fpolyu%5Fhk%2FDocuments%2FProject%5FCode%5FGroup%5F23%2Ezip&parent=%2Fpersonal%2F24109859d%5Fconnect%5Fpolyu%5Fhk%2FDocuments&ga=1) 