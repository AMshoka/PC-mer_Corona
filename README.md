# A new profiling approach for DNA sequences based on the nucleotides' physicochemical features: Corona case study
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AMshoka/PC-mer_Corona/blob/main/Code/Training.ipynb)
## PC-mer Workflow
![PC-mer(workflow)](https://user-images.githubusercontent.com/91915096/172617347-b66dff7f-f6fa-4b39-abdf-2ad99c528854.png)
## INTRO
<p style='text-align: justify;'> Our proposed encoding method, PC-mer, is an ultra-fast, alignment-free, accurate, and compact feature extraction method which is compatible with the wide range of machine learning classifiers and can be imple-mented on the simple processing systems. Our simulation results are obtained through a comprehensive analysis of over 5874 unique viral sequences which are divided into 8 datasets, and confirm the superiority of the method, in terms of classification accuracy, runtime, and memory usage. Similar to the k-mer-based methods, the applicability of the PC-mer approach, does not end here and it can be also employed in many computational comparison methods. This capability was examined by using the PC-mer and the Manhattan distance to analyze a dataset in-cluding 5 samples from 7 different classes. We compared the results to those obtained by an alignment approach. The distance matrices derived by these two methods have acorrelation coefficient value of 98%, as reported in this paper. This study suggests that a proper alignment-free approach for comparative genomics study can be used when the timely taxonomic classification is of the essence, such as at critical periods dur-ing novel viral outbreaks. For this purpose, we developed a package based on PC-mer encoding method including two parts: 1) an ML-based classifier, and 2) a computational comparison tool. The ML-based classi-fier is a fast and accurate method classifying the coronaviruses samples from 7 classes by means of the simple classifiers which can also get input sequences from NCBI database by IDs. On the other hand, the computa-tional comparison tool of this package computes a score for each pair of input sequences as an estimation of their dissimilarity. In all, the compre-hensive analysis of the PC-mer approach indicates that it is also applica-ble for more detailed analysis of coronaviruses, examining intraspecies samples, as well as SARS-COV-2 samples from other countries. Fur-thermore, since k-mer-based methods are used in a variety of applica-tions, like metagenomics classification, we will investigate adoption of PC-mer encoding method in these applications in future studies as well.</p>

## PREREQUISITES
The method was implemented in Python 3.8 with the use of scikit-learn library running on a normal desktop computer (CPU: i7-6500 2.5 GHz, RAM: 8 GB RAM, HD: 256GB Lexar, GPU: GeForce GTX 920M. 
## CONTACT

<b>**Somayyeh Koohi**</b> <br>
Department of Computer Engineering <br>
Sharif University of Technology <br>
e-mail: koohi@sharfi.edu <br>
WWW: http://sharif.ir/~koohi/

