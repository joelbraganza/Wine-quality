# Wine-quality
Use Machine  and Deep learning to determine which physio-chemical properties make a wine 'good'!

Classification modification: 
Have changed the multiclass-classification problem to binary-classification problem
by changing the classes 3,4,5,6 to 0 (bad-quality) and classes 7/8 to 1 (good quality)

Feature Analysis and Selection:
ANOVA (all independent variables are continuous, so needed ANOVA to check relationship with the categorical target)
Correlation-heatmap (many continuous-independent variables were collinear, so needed a removal to reduce processing and overfitting)
Lasso-Linear and Random-Forest regression's feature importance/selection technique

Model development:
Decision Trees, 
Random Forest,
Logistic Regression,
K-Nearest-Neighbours
Gaussian Naive-Bayes
DNN using Keras

Have compared the accuracy metrics like accuracy-scores and False-Negative-Rate between all the above applied models over both
the Red wine and the White wine datasets.
