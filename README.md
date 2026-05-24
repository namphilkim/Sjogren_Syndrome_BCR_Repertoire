Code for drawing the respective plots for the Sjogren syndrom BCR repertoire profiling manuscript.

The manuscript is currently in the process of being published.

To recreate figures regarding the total repertoire characteristics (isotypes, clonality), the user should create two directories under the sjogren directory named asm_file and sjogren_file.

From the Gene Expression Omnibus database, download the repertoire data with the accession number GSE308513 and put the HC data and SS data in the asm_file and sjogren_file repectively.

The registration of repertoire characteristics wil take up to ten mintes depending on hardware. 

All other figures are recreated from the intermediate files provided and are generated within a minute.

Run the Sjogren_code_wrapped_up.ipynb on jupyter notebook to obtain figures.

Dependencies:
Matplotlib 3.7.5
Numpy 1.20.1
Scipy 1.6.2
