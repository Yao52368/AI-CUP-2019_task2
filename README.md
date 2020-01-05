# AICUP-2019-task2-Abstract_Classification
## Competition Description
從arXiv的電腦科學相關論文摘要，預測出摘要所屬的類別(Theoretical Paper, Engineering Paper, Empirical Paper, Others)。
## Introduction
　Team Name : NCKUDM_UrbanComputing  
  
　Public Score : 0.714503  
  
　Private Score : 0.741327 	
## File Description
　Source code：AI-CUP-2019_task2.ipynb  
   
　Train Dataset：data/trainset.csv  
    
　Valid Dataset：data/validset.csv  
   
　Public Dataset：data/testset.csv  
   
　Private Dataset：data/task2_private_testset.csv  
   
　Pretrained Scibert：Scibert/  
## How to run?
　Step 1. Install requirement package  
   
　　●  [keras-bert](https://github.com/CyberZHG/keras-bert)  
    
　　●  keras：2.2.4  
    
　　●  tensorflow：1.12.0  
    
　Step 2. Run AI-CUP-2019_task2.ipynb  
   
　　●  You can run the file in order and train the model by yourself.  
    
　Step 3. Run with our model
    
　　●  Download [our model](https://drive.google.com/open?id=1_IoF1hW-55WtoukyAsfNefeY5tHI4szW), create folder named "save" and put it in save/  
  
　　●  Run load_model line in "Load and Save model" block in source code
