# Machine Learning & Analysis on OSD-47 & OSD-48 Datasets 

## About this project: 
This project studies OSD-47 and OSD-48 datasets. The datasets are from NASA’s Open Space Data Repository (OSDR). OSD-47 was studying microgravity effects on muscle wasting, while OSD-48 was for studying systemic responses. 

Why study mice? Mice and humans have similar gene counts and functions. Performing experiments on mice may give insight on how treatments or certain conditions may affect humans. Some genes are orthogonal between mice and humans, meaning that they originated from a common ancestor and were separated by a speciation event. These genes would be of similar function. If some of these genes are affected by spaceflight, studying them would give insight on how spaceflight may impact humans. 

There are three parts to this project:
### Classification using Random Forest Modeling
* Predict high/low ORO% from gene expression values

### Determining if there is a significant difference in ORO%  between flight and nonflight samples
* Hypothesis testing with t-testing
* Boxplots

### DGEA & Volcano Plots
* Perform DGEA
* Create Volcano plots 
* See NCBI summaries of DGEA genes

## Get Started:
Before running “CS123ATermProject.ipynb”, user should add a copy of “projectmethods.iypnb” into their Google Drive. 
After a user mounts to Google Drive, change the file path to where “projectmethods.ipynb” was saved.  If saved to the default Colab Notebooks folder, the line should be changed to this: 
```
m = __import__("mnt/MyDrive/Colab Notebooks/projectmethods")
```
After this, cells should be run sequentially. 
