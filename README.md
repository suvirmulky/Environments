spark.yml : contains the list of necessary packages for data manipulation,visualization and conection to spark

ml.yml : contains the basic packages needed for machine learning

**Steps to create the above environments:**

**1)Clone the repository **
   ```sh
   git clone https://github.com/suvirmulky/Environments.git   
   cd Environments
   ```
**2) Create the environments**
    ```
    conda env create -f ml.yml  
    conda env create -f spark.yml
    ```
    
**3)Lists the environments present** 
    ```
    conda info --envs
    ```
    
**4)Activate the environments**
    ```
    source activate spark
    source activate ml
    ```
