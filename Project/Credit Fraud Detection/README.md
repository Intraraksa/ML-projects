## Credit Fraud Detection

This inspirational project came from imbalance classifaction problem in the real world dataset. 

In this dataset come from [Credit Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud) from Kaggle.
the dataset contain the incomprehensible information because of PCA preprocessing.

Though, This project are emphasize to solve the problem about **Imbalance classification**

The Methods used in this notebook are
- Resampling by majority class deletions to equal
- Resampling by SMOTE
- Resampling by Nearmiss

The Upsampling by **SMOTE** 
This techic is upsampling for increase minority class by using k-nearest to create temporary data for minority class

![SMOTE](https://miro.medium.com/max/3000/0*UrGYcz_Ab-HTo4-B.png)

Resampling by Near-miss
Near-Miss techic are undersampling by Condensed Nearest Neighbor Rule methods that select examples to keep from the majority class.

![Near-miss](https://miro.medium.com/max/875/1*8WM0gsh_naPEa9HTpE2c1A.png)

### Conclusion
The result is evauated by F1-score after Upsampling or Undersampling method give the better result. 