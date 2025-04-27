# Overview

Dermoscopic lesion imaging, like many diagnostic medical exams, produces a long-tailed distribution of clinical findings; while a small subset of diseases are routinely observed, the vast majority of diseases are relatively rare. This poses a challenge for standard AIML methods, which exhibit bias toward the most common classes at the expense of the important, but rare, “tail” classes. Many existing methods have been proposed to tackle this specific type of imbalance, though only recently with attention to long-tailed medical image recognition problems.

Diagnosis on dermoscopic lesion images is a multi-class problem, as each image is associated with a single disease class. This dataset has 10, 015 skin images with 7 lesion classes. This dataset is characterized by an imbalance ratio (IR) of 58, where IR is defined as the ratio of the sample size of the largest majority class and that of the smallest minority class. Thus the larger the value of IR, the larger the imbalance extent.

# Goal

Build automated predictions of disease classification within dermoscopic images.
Possible disease categories are:

1. Melanoma (MEL)
2. Melanocytic nevus (NV)
3. Basal cell carcinoma (BCC)
4. Actinic keratosis / Bowen’s disease (intraepithelial carcinoma) (AKIEC)
5. Benign keratosis (solar lentigo / seborrheic keratosis / lichen planus-like keratosis) (BKL)
6. Dermatofibroma (DF)
7. Vascular lesion (VASC)

