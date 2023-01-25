# Skin
Diagnosing skin cancer using MobileNetV2 truncated with Partial Layer Freezing and Feature Fusion


Abstract: 
Skin cancer is the deadly diseases in the world. Mainly three types of skin cancer such as basal cell carcinoma, squamous cell carcinoma and melanoma. But melanoma is the dangerous part of three types. Main reasons about skin cancer is Ultraviolet radiation from the sun cases. According to the World Health Organization 132,000 melanoma skin cancers affected every year .Early detection of this lesions may decrease the mortality rate. We are using transfer learning, fine tuning deep learning model to classify skin lesions. In this model we are added two classes like Benign and Malignant. This model trained 80% of training and 20% of validation and accuracy rate is 0.98% .

Dataset: 
 Online Available: https://www.kaggle.com/datasets/fanconic/skin-cancer-malignant-vs-benign


Graphical Abstract:
![Image Diagonsis Hasan Vai (2)](https://user-images.githubusercontent.com/94735396/214030755-4e612a0b-a22e-44e6-a421-a4b4e28fa807.png)

Citation:
 title = {Diagnosing Covid-19 Chest X-Rays with a Lightweight Truncated DenseNet with Partial Layer Freezing and Feature Fusion}, journal = {Biomedical Signal Processing and Control}, pages = {102583}, year = {2021}, issn = {1746-8094}, doi = {https://doi.org/10.1016/j.bspc.2021.102583}, url = {https://www.sciencedirect.com/science/article/pii/S1746809421001804}.
How to use:
Dependencies included in the requirements.txt:

jupyter==1.0.0
keras==2.2.5
matplotlib
numpy==1.16.2
opencv-python==4.4.0.42
pandas==0.25.3
Pillow==7.2.0
scikit-learn
scikit-image
scikit-plot
scipy
tensorflow-gpu==1.14.0 (Note: This is optional and can train even with just a CPU or tensorflow non-gpu variant)

"START HERE"-  You may clone using git or download the repository and extract the files manually:

Once cloned, CD into the folder and enter pip install -r requirements.txt.
After installation of the dependecies, there are one option to train this model and evaluate.

Step to evaluate:

Clone this repository or download as zip.
Install the requirements on a newly created environment to prevent issues with other existing ones.
Directly open the skin cancer diseases detction.ipynb and proceed with the evaluation.

Perfomace analysis:
Accuracy =0.9893    Precision= 0.9497    Recall = 0.9500       F-1 score =  0.8610
