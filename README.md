# miRdisNET

## miRdisNET : Discovering microRNA Biomarkers that are Associated with Diseases utilizing Biological Knowledge-based Machine Learning
Amhar Jabeer<sup>1</sup> ,Mustafa Temiz<sup>1</sup>, Burcu Bakir-Gungor<sup>1</sup> and Malik Yousef<sup>2,3</sup> <br>

<sup>1</sup> Department of Computer Engineering, Faculty of Engineering, Abdullah Gul University, Kayseri, Turkey<br>
<sup>2</sup> Department of Information Systems, Zefat Academic College, Zefat, 13206, Israel<br>
<sup>3</sup> Galilee Digital Health Research Center (GDH), Zefat Academic College, Israel<br>


*Correspondence: malik.yousef@gmail.com and mustafa.temiz@agu.edu.tr;
<br>
## Knime ##
miRdisNET tool is a Knime workflow. In order to run the workflow, you need to download Knime and install it in your local machine.
This is the link for downloading Knime: https://www.knime.com/downloads<br>
For more information about the Knime platform you might visit https://www.knime.com/software-overview <br>


## miRdisNET main workflow is: ## 

**Running the workflow:**

You need to use the node “MCCV Iterations” in order to specify the number of Monte Carlo Cross Validation (MCCV) iterations, for example 10 or 100.
You need to configure the node “List Files/Folders” to point it to the folder that has the gene expression dataset in a table format (as described above)
You might [download](BLCA_miRNA.table) an example of such data named [BLCA_miRNA.table](BLCA_miRNA.table)
You might [download](HMDD_V3.2.xlsx) an example of such data named [HMDD_V3.2.xlsx](HMDD_V3.2.xlsx)

![main_workflow](https://user-images.githubusercontent.com/24303536/196436151-a1fb431f-2785-40b3-82cc-e05a4f320cef.png)

## The content of the MetaNode miRdisNET is :


![alt text](https://user-images.githubusercontent.com/24303536/196437220-fa51c4c2-6194-4c99-bf95-3fcf23e8a608.png)

## The content of the G-S-M component ##


![alt text](https://user-images.githubusercontent.com/24303536/196437420-52cc8225-a4b3-4dd5-ad7d-58ec52429287.png)

## The 3 main component of G-S-M ##
![alt text](https://user-images.githubusercontent.com/24303536/196437933-03f9a9c9-b410-4b6f-816c-7dac70337b65.png)


