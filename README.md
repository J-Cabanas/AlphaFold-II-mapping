# AlphaFold-II-mapping

This is a repository, where AlphaFold2 is tested, studying its prediction capability for different protein structural hierarchies.

## Features
First, it is necessary to perform a hierarchical classification of protein structure, which is done using the CATH database [1].
We proceed to download two files containing all the information necessary for the execution of the program.
The program uses the Protein Data Bank (PDB) database and extracts the UniProt code of the proteins, and then obtains the AlphaFold2 predicted structure and the Alignament Predicted Error (APE) files for each protein.
With the results, we proceed to calculate the weigthen contac nomber (WCN) to compare it with the (PAE) and analyze the relationship between the degree of packing and the accuracy of AlphaFold2.

## Environment construction (Linux)
Enter the dependencies folder to find the necessary steps to perform the installation correctly.

## Get in Touch (Ponerse en contacto)
If you have any questions not covered in this overview, please contact us at the following email address to discuss your concerns: joan.cabanas@uvic.cat
## Acknowledgements (Agradecimiento)

## References
<div class="csl-entry"><i>[1]CATH</i>. (n.d.). Retrieved June 23, 2022, from http://www.cathdb.info/wiki?id=data:index</div>