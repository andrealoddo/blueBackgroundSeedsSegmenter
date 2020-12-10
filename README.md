# blueBackgroundSeedsSegmenter
ImageJ plugin for automatic segmentation of seeds from blue background images

# Authors
Alessandra Mendes, Andrea Loddo

# Description
This plugin is part of the scientific paper "A new automatic approach to seed image analysis: From acquisition to segmentation", realised by the following authors.

# Manuscript information
Authors: Vale A.M.P.G. 1 , Ucchesu M. 2* , Di Ruberto C. 3 , Loddo A. 3 , Soares J.M. 4 , Bacchetta G. 2,5

1 Escola Agrícola de Jundiaí (EAJ), Universidade Federal do Rio Grande do Norte (UFRN), Rodovia RN 160, Km 03, CEP 59280-000 Macaíba (RN), Brasil.

2 Centro Conservazione Biodiversità (CCB), Dipartimento di Scienze della Vita e dell’Ambiente (DiSVA), Università degli Studi di Cagliari, Viale S. Ignazio da Laconi 13, 09123 Cagliari, Italy.

3 Dipartimento di Matematica e Informatica, Università degli Studi di Cagliari, Via Ospedale 72, 09124 Cagliari, Italy.

4 Universidade Federal do Rio Grande do Norte (UFRN), Rodovia RN 160, Km 03, CEP 59280-000 Macaíba (RN), Brasil.

5 Hortus Botanicus Karalitanus (HBK), Università degli Studi di Cagliari, Viale S. Ignazio da Laconi 11, 09123 Cagliari, Italy.

# Workflow description
The manuscript mentioned above described in detail the plugin's workflow.
For the sake of simplicity: it works on an entire folder of digital seed images, acquired with a blue background.
It requires the user to indicate one file among the several which can present inside a folder (the folder MUST contain only blue background images) and, after the pre-processing and segmentation phase, produces a ResultTable inside ImageJ with some statistical data and, above all, saves original color, gray-level, and black and white mask images under the folder "results", on the same folder containing the images.
E.g.: if the folder containing the images is in C:\Users\User\Desktop\Seeds -> the results will be in C:\Users\User\Desktop\Seeds\results
