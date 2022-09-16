# SKIN LESION CLASSIFICATION ON IMBALANCED DATA USING DEEP LEARNING WITH SOFT ATTENTION

Today, the rapid development of industrial zones leads to an increased incidence of skin 1
diseases because of polluted air. According to a report by the American Cancer Society, it is estimated 2
that in 2022 there will be about 100,000 people suffering from skin cancer and more than 7600 of 3
these people will not survive. In the context that doctors at provincial hospitals and health facilities 4
are overloaded, doctors at lower levels lack experience, and having a tool to support doctors in 5
the process of diagnosing skin diseases quickly and accurately is essential. Along with the strong 6
development of artificial intelligence technologies, many solutions to support the diagnosis of skin 7
diseases have been researched and developed. In this paper, a combination of one Deep Learning 8
model (DenseNet, InceptionNet, ResNet, etc) with Soft-Attention, which unsupervisedly extract a 9
heat map of main skin lesions. Furthermore, personal information including age and gender is also 10
used. It is worth noting that a new loss function that takes into account the data imbalance is also 11
proposed. Experimental results on data set HAM10000 show that using InceptionResNetV2 with 12
Soft-Attention and new loss function gives 90 percent accuracy, mean of precision, f1-score, recall- 13
score, and AUC scores of 0.81, 0.81, 0.82, and 0.99, respectively. Besides, using MobileNetV3Large 14
combined with Soft-Attention and new loss function, even though the number of parameters is 11 15
times less, the number of hidden layers is 4 times less, it achieves an accuracy of 0.86 and 30 times 16
faster diagnosis than InceptionResNetV2.

Keywords: Skin Lesions, Classification, Deep Learning, Soft-Attention, Imbalance

# Citation
@article{
  title={Soft-Attention Improves Skin Cancer Classification Performance},
  author={Viet Dung Nguyen, Ngoc Dung Nguyen, and Hoang Khoi Do},
  journal={Sensors MDPI},
  year={2022}
}

# Results
## Soft Attention maps of Skin lesion in Inception ResNet V2 on HAM10000 data
![alt text](https://github.com/ScaleMind-C9308A/Skin-Disease-Detection-HAM100000/MDPI/sensors-1915564/Definitions/ROC/denvsirv2.png?raw=true)

# Datasets

**HAM10000  dataset**:

Tschandl, P., Rosendahl, C. & Kittler, H. The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions. 
Sci. Data 5, 180161 doi:10.1038/sdata.2018.161 (2018).Available: https://www.nature.com/articles/sdata2018161, https://arxiv.org/abs/1803.10417

**ISIC-2017 dataset**:

Codella N, Gutman D, Celebi ME, Helba B, Marchetti MA, Dusza S, Kalloo A, Liopyris K, Mishra N, Kittler H, Halpern A. 
"Skin Lesion Analysis Toward Melanoma Detection: A Challenge at the 2017 International Symposium on Biomedical Imaging (ISBI), 
Hosted by the International Skin Imaging Collaboration (ISIC)". arXiv: 1710.05006 [cs.CV] Available: https://arxiv.org/abs/1710.05006 
