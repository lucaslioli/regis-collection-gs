# REGIS Collection GS - Retrieval Evaluation for Geoscientific Information Systems
## Gold Standard repository

Public repository for the paper **Evaluating and Mitigating the Impact of OCR Errors on Information Retrieval: A Case Study in the Geoscientific Domain**, submitted to **International Journal on Digital Libraries**.
This repository contains a sample of 100 sentences, with their corresponding pages, from REGIS collection manually collected and corrected.

Authors: Lucas Lima de Oliveira, Danny Suarez Vargas, Antônio Marcelo Azevedo Alexandre, Fábio Corrêa Cordeiro, Diogo da Silva Magalhães Gomes, Max de Castro Rodrigues, Regis Kruel Romeu, Viviane Pereira Moreira.

REGIS collection link: https://github.com/Petroles/regis-collection

## About

Optical Character Recognition (OCR) is typically used to extract the textual contents of scanned texts. The output of OCR can be noisy, especially when the quality of the scanned image is poor, which in turn can impact downstream tasks such as Information Retrieval (IR). Post-processing OCR-ed documents is an alternative to fix digitization errors and, intuitively, improve the results of downstream tasks. This work evaluates the impact of OCR digitization and correction on IR. We compared different digitization and correction methods on real OCR-ed data from an IR test collection with 22k documents and 34 query topics in Portuguese.
Our results have shown significant differences in IR metrics for the different digitization methods (up to 5 percentage points in terms of Mean Average Precision).
Regarding the impact of error correction, our results showed that on the average for the complete set of query topics, retrieval quality metrics change very little. However, a more detailed analysis revealed it improved 19 out of 34 query topics. Our findings indicate that, contrary to previous work, long documents are impacted by OCR errors.
