**About Dataset :**
Chest X-Ray Images
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).
Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.
For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.
Link : https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?select=chest_xray

**About Model VGG16 :**
VGG16 has 13 convolutional layers, 5 Max Pooling layers, and 3 Dense layers, which sum up to 21 layers. However, it has only 16 weight layers, which are learnable parameters layers.
It is trained on a subset of the ImageNet dataset, a collection of over 14 million images.

**Quantum Transfer Learning :**
Read my blog on Pnuemonia Detection using Quantum Transfer Learning
Link : https://medium.com/@aanshsavla2453/pneumonia-detection-using-quantum-transfer-learning-3cec9c215b6e
