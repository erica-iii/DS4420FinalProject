# Political Speech Party Prediction
CNN CLASSIFIER
A 1D Convolutional Neural Network built to classify presidential speeches as either Democrat or Republican based on textual rhetoric.

Methodology: The text data is obtained directly from local JSON files, cleaned of HTML tags and punctuation, tokenized, and padded to a maximum length of 500 words.

BAYESIAN MODEL
A Bayesian logistic regression model built to classify presidential speeches as Democrat or Republican based on engineered linguistic features, including sentiment, negativity, speech length, sentence structure, and political keyword frequencies.

Methodology: The model uses a Bernoulli outcome with a logit link and places Normal priors on the feature coefficients so party classification is based on how sentiment, negativity, structure, and keyword usage shift the odds of each class.

Languages/Libraries Used:
Python
R
TensorFlow (Keras)
Scikit-Learn
NumPy
pandas
VADER
brms

Data: https://data.millercenter.org | https://www.kaggle.com/datasets/imuhammad/us-2020-presidential-election-speeches?resource=download | https://github.com/ichalkiad/datadescriptor_uselections2020/tree/main/us2020data
