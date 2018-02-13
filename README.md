Somatic Mutation Calling Using Neural Networks
==============================================

![matlab](https://img.shields.io/badge/matlab-.5-green.svg?style=flat)  ![c++](https://img.shields.io/badge/c++-.29-green.svg?style=flat)  ![python](https://img.shields.io/badge/python-.12-green.svg?style=flat)  ![java](https://img.shields.io/badge/java-.9-green.svg?style=flat)  ![license](https://img.shields.io/github/license/mashape/apistatus.svg)

This project was done for the Institute for Pure and Applied Mathematics (IPAM) and the Beijing Genomics Institute (BGI). The research was performed in Hong Kong out of the Hong Kong University of Science and Technology (HKUST).
 
 
 
## Tools used

Programming languages: C++, Python, Java, MATLAB

Bioinformatics tools: SAMTools, GATK


## Project structure

The repo is broken down into the following components:
- **annotation_parser**: a Java SNP annotation parser

- **tumor_parser**: a C++ string parser to handle massive amounts of DNA sequencing data in the form of "AGCT" and delimiters

- **neural_network**: a parallel neural network implementation in C++ with openMP

- **scikit_code**: a voting algorithm using SVM, Random Forest, KNN and other methods for classification

- **report**: report for the Beijing Genomics Institute

## Contributing
