# AgNOR-Cell-Detection-Classification

● Introduction
 
Nucleolar organiser regions (NORs) are chromosomal regions in the DNA
which contain a set of associated proteins such as argyrophilic proteins.
These proteins are stained by silver methods, hence it can be identified using
silver-staining. After silver staining there can be seen black dots on the
images of the nucleolar area. These dots are called “AgNORs”.
Theaverage number of AgNORs in a nucleus is a good indicator for both
tumour diagnostic and prognostic purposes.

● Dataset

Dataset contains a total of 27 images and a total of 1973 annotattions. There are 12 classes which corresponds to the AgNORs count (from 0 to 11).

● Hardware

Both models were trained on a GTX 1650 4GB (laptop) GPU, Which was sufficient for the task. However, the accuracy of the classification net can be improved with higher number of epochs. On the other hand, it takes a long period of time with the given GPU
