# AlphaFold-II-mapping

This is a repository, where AlphaFold2 is tested, studying its prediction capability for different protein structural hierarchies.

## Installation (Linux 5.13.0)
It is necessary to access the WCN repository, created by Martin-Floor and follow the steps to create our working environment and import its dependencies. 

Follow the steps shown in the repository: 
<div class="csl-entry"><i>Martin-Floor/WCN</i>. (n.d.). Retrieved June 29, 2022, from https://github.com/Martin-Floor/WCN</div>
---

Once all the steps have been completed, we proceed to execute the following commands in the created environment: 
    * conda install -c anaconda wget 
    * conda install -c conda-forge matplotlib

## Program execution
First it is necessary to modify the second cell of the code. Where we can define the name of the folders that we will create locally in our machine, although this step is not necessary if we already think that the assigned name is correct.

It is also necessary in this same cell to change the value of the variable, to assign if we want to make a test with 42 proteins or the complete program with the 6631 proteins. 
The value to be assigned to the variable is specified in the program.

## Features
First, it is necessary to perform a hierarchical classification of protein structure, which is done using the CATH database [1].

We proceed to download two files containing all the information necessary for the execution of the program.

The program uses the Protein Data Bank (PDB) database and extracts the UniProt code of the proteins, and then obtains the AlphaFold2 predicted structure and the Alignament Predicted Error (APE) files for each protein. To obtain the predictions, the database provided by AlphaFold (AlphaFold DB) is accessed.

With the results, we proceed to calculate the weigthen contac nomber (WCN) to compare it with the (PAE)  and analyze if there is a relationship between the degree of packing and the accuracy of AlphaFold2.
...

## Get in Touch (Ponerse en contacto)
If you have any questions not covered in this overview, please contact us at the following email address to discuss your concerns: joan.cabanas@uvic.cat
## Acknowledgements (Agradecimiento)



## References
<div class="csl-entry"><i>[1]CATH</i>. (n.d.). Retrieved June 23, 2022, from http://www.cathdb.info/wiki?id=data:index</div>