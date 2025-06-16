# Protein Classification with Complex and Real-valued 1D Convolutional Neural Networks
The aim of this study is to classify 1D complex-valued data obtained from DNA, codon, and amino acid sequences using the complex-valued convolutional neural networks (CVCNN), based on the complex encoding method proposed in the “ComplexVsRealANNProteinClassify” study. The performance results are then compared with those obtained using an integer-based encoding method and real-valued convolutional neural networks (RVCNN).
## Study Stages:
## 1. DNA Sequence Classification with CVCNN
• DNA sequences belonging to the Kinase and GPCR protein families were downloaded from NCBI.
• DNA sequences were converted into complex number sequences using the proposed complex DNA coding method.
• Protein classification was performed using 1D CVCNN models with complex-valued sequences.
## 2. Classification of Codon Sequences Using CVCNN
• The same DNA sequences were arranged in triplet (codon) format.
• The data were encoded using the proposed complex codon encoding method.
• Protein classification was performed using 1D CVCNN models with complex-valued codon sequences.
## 3. Classification of Amino Acid Sequences Using CVCNN
• Amino acid sequences belonging to the kinase and GPCR families were obtained from NCBI.
• The data were converted into complex number sequences using the proposed complex amino acid encoding method.
• Protein classification was performed using 1D CVCNN models with complex-valued amino acid sequences.
## 4. Classification of DNA/codon/amino acid sequences using RVCNN
• The same DNA, codon, and amino acid sequences were converted into integer sequences using an integer-based encoding method known in the literature.
• Protein classification was performed using separate real-valued 1D RVCNN models for each data type.
• The results obtained were compared with complex-valued models.

##### Technical and Development Notes:
The applications of the study were carried out using the Python programming language in the Jupyter Notebook environment. During the code development process, deep learning libraries and code repositories such as Keras and TensorFlow were utilized. In the debugging and compilation stages of the developed code, the generative artificial intelligence tool ChatGPT-4o (version: 2024-05-13) was used solely for technical support purposes and within the framework of limited and full scientific responsibility principles, with its accuracy verified.
