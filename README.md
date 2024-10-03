# Protein Classification with Complex Valued Convolutional Neural Networks
# Encodıng of proteın sequences ınto complex numbers and classıfıcatıon usıng evolutıonary complex-valued artıfıcıal neural networks:
### Step 1 (Data import): Amino acid sequences of kinase and GPCR proteins are imported from the NCBI gene bank in fasta form using accession numbers.
- Note: Due to possible updates to the NCBI Site, the dataset of Amino Acid Sequences used in the study has been uploaded to GitHub. Using this dataset, the Study can start from step 2.
### Step 2 (Data preprocessing): Amino acid sequences of kinase and GPCR proteins are labeled as “1” and “0”, limited to 300, randomly shuffled, concatenated and saved as a single data frame in fasta form.
### Step 3 (Complex Encoding): The data frame of preprocessed amino acid sequences is converted into complex numbers by the proposed Complex Encoding Method and saved as a complex-valued data frame.
### Step 4 (Classification): Using the amino acid sequences encoded into complex values, Kinase and GPCR proteins are classified by Convolutional Complex Neural Networks.
### Step 5 (Results and Graphs): Classification results measured by different metrics are visualized with Graphs.
### Step 6 (Cross Validation): For a more objective evaluation of Amino Acid seq. classification results with Convolutional Neural Networks, 10-fold Cross Validation is applied and metric means and standard deviations are calculated.
