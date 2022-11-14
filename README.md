<img src="images/GEMS Informatics Learning.png" width=600 alt="GEMS Learning Logo" title="GEMS Learning" />

# Spatial Regression in R

Welcome to **GEMS X003.4 Explicitly Accounting for Location in Agriculture: Spatial Regression in R**.  

This course is designed for those who want to learn spatial regression techniques and model spatial dependency explicitly. Through this course, you will learn about  spatial dependency and spatial autocorrelation, the construction of spatial weight matrices, testing for spatial association and correlation and building generalized spatial regression models. You will have the opportunity to immediately practice your new skills via hands-on exercises focused on agri-food applications throughout the 2.5-hour workshop.

This workshop is part of a series on working with and analyzing spatial agricultural data in R. 

Prerequisites: GEMSx003.00 GEMSx003.01 or equivalent


## Initial Setup
1. Login to GEMS Platform at https://gems.agroinformatics.org/
    - GEMS Platform uses Globus to authenticate your account, so if your institution is already linked to Globus (for example, University of Minnesota and many other universities), you can search and select your institution from the list and use your institutional account to log into GEMS Platform. Alternatively, you can log in using Google or ORCID iD, or create  your own Globus account to log in.   

2. Once logged in, click `Analyze > JupyterLab` from the homepage

3. Open a bash terminal by clicking 'Terminal' icon in the Launcher **OR** by clicking `File > New > Terminal`

4. If the directories `classes\GEMSX003` were not created before, create directories for this class in the bash terminal using the following four commands  
    ```shell
    mkdir classes  
    cd classes  
    mkdir GEMSX003  
    cd GEMSX003
    ```  
    If these directories already exist, use the following commands to change to this directory
    ```shell
    cd classes
    cd GEMSX003
    ```
    
5. Clone repository for this classes  
    ```shell
    git clone https://github.com/y-chai/GEMS-X003-Spatial-Regression-R.git
    ```

## Class and Exercises
In your JupyterLab environment, open the newly cloned directory `GEMS-X003-Spatial-Regression-R` and then follow along for in-class exercises 
