# Gene Attribution for Cancer Classification 



## Code
To view the code please see the following Colab notebooks:

1. https://colab.research.google.com/drive/15PrVBlBhFGzlQZ_Fd4bFvU29HjXqIEo8?usp=sharing
   <br/>This notebook contains the recreation of the model by Lyu et al and the code to generate vanilla gradients. 
2. https://colab.research.google.com/drive/1Il4zZ1hjjL4eDOpADxHYvk61EfiBxxow?usp=sharing
  <br/>This notebook contains the code to generate integrated gradients. Beware it takes a long time to run. 
3. https://colab.research.google.com/drive/1yT-FcjERHNadM0r-jD6dO6PUROy_0gJV?usp=sharing
  <br/>This notebook contains the code to train the model on the top k% of features identified by vanilla gradients, integrated gradients, highest standard deviation, or chosen randomly. 
4. https://colab.research.google.com/drive/1FypUxcNedT9J_sIUtop-ioZ0tPe2l2-O?usp=sharing
<br/>This noteboook contains the code to generate results and figures. 
5. https://colab.research.google.com/drive/1Ij1Niv8e0lb3dBoWIrS-KFOvthit1QEH?usp=sharing
  <br/>This notebook contains preprocessing steps. 
  
## Data 

The preprocessed data can be found in the drive folder accessible through the following link: 
<br/>https://drive.google.com/drive/folders/18tquBCVxyCSm70qS9L-EjtLW6qdoaos8?usp=sharing
<br/>*Note that even though the file is labeled "Preprocessed_Train_Data.csv" it contains the entire data set. Apologies for the bad naming!

All artifacts and results generated can be found in this drive folder: 
<br/>https://drive.google.com/drive/folders/1Z6NIQNoOwxkWGPjPJkUFzIVhrxQnltIp?usp=sharing

In this folder there are several types of files: 
1. The average vanilla gradients calculated for each class are in the files class_avg_grads_new_#.csv 
2. The average integrated gradients calculated for each class are in the files class_integrated_grads_#.csv

## Running the Notebookos 

The notebook mounts Google Drive into the notebook to access stored data. Thus to run the notebooks, change the paths to match the structure of your drive or make sure there is a folder called "TCGA Data" with the Preprocessed_Train_Data.csv file and a folder called "Rerun_TCGA_Data" to write the results out to.

## A few notes: 
Apologies for redundant code throughout the notebooks. Only after completing the project did I realize Colab supports the export and import of code modules!
