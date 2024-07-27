
# Previous competition Data
https://www.kaggle.com/competitions/isic-2024-challenge/discussion/515356 \
He resized datasets in 2017, 2018, 2019, 2020.

! 1.Pretraining with previous data.\
! 2.Fine-tuning with current data.

! 1. union previous data in currentdata\
! 2. Pretraining with previous data and fine-tuning with current data.

! 3 species cansers was classified in model head by last(2020) winner.

# Test Data Attributions
https://www.kaggle.com/competitions/isic-2024-challenge/discussion/517139 \
The attributions between Train data and Test data are almost same.

! Ensembling Boosting and CNN is a good way of improving PAUC.\
Setting weights in the loss function to favour tpr/fpr of boosting machine might work.

# CNN verus lightgbm
https://www.kaggle.com/competitions/isic-2024-challenge/discussion/518818 \
Ensembling is a better way. \
He showed us a lot of references for this competition.

# Related Papers
https://www.kaggle.com/competitions/isic-2024-challenge/discussion/515303

# Onboarding materials and references
https://www.kaggle.com/competitions/isic-2024-challenge/discussion/515341 \
He summrized past competition highlights.

# Augmentation 
https://www.kaggle.com/competitions/isic-2024-challenge/discussion/517141 \
He showed us the way of augmentations in the past competitions.

# Removal hair
https://www.kaggle.com/competitions/isic-2024-challenge/discussion/519735

# Noise data
https://www.kaggle.com/competitions/isic-2024-challenge/discussion/521145 \
She found close fabric image as a noise data. \
How we do clensing is important. \
I might make a flg to such images(ids) as irregular. \
Or remove from train data? 


