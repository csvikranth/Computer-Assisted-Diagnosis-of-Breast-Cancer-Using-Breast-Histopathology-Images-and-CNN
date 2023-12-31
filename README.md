# Computer-Assisted-Diagnosis-of-Breast-Cancer-Using-Breast-Histopathology-Images-and-CNN

In recent years, breast cancer has become one of the most prevalent kinds of cancer. Breast Ultrasound, Diagnostic Mammogram, Magnetic Resonance Imaging (MRI), and other imaging modalities are routinely used to diagnose breast cancer. Doctors make final judgments about treatments, drugs, and other matters based on biopsy results, which are regarded the standard diagnostic approach for cancer. However, this is a time-consuming process that also necessitates extensive pathologist training and expertise. Each pathology lab receives around 300-500 slides per day. This overburdens the pathologists and increases the misdiagnosis rate in the biopsy results. In order to provide timely error free results to the patients, the research community focuses more on the development of Computer Aided Diagnosis (CAD) System to assist pathologists to diagnose cancer. Recent developments in Deep Learning techniques made the CAD systems more effective in detecting breast cancer at an early stage with a great accuracy. In this paper, we present a CAD system that recognises histopathology images to diagnose breast cancer using a Convolutional Neural Network (CNN). DenseNet201, ResNet50 and MobileNetV2 are used in this work. These are trained and tested using the openly available BreakHis and BACH datasets. The datasets are subjected to binary and multi-class classifications. Accuracy, Precision, Recall, F1 Score, and AUC are all performance measures that are used to evaluate the model’s performance. For Binary classification, the model built using MobileNetV2 with Sigmoid as activation function displayed a higher accuracy of 97% - 98% and in the case of multi-class classification, again the model built using MobileNetV2 with Softmax as activation function displayed a higher accuracy of 91% - 92% for both Magnifican Independant (MI) and Magnification Dependant (MD) cases.


BreakHis dataset can be found at: https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/


BACH dataset can be found at: https://iciar2018-challenge.grand-challenge.org/Dataset/



Full publication and results can be found at: https://ieeexplore.ieee.org/document/9760669
