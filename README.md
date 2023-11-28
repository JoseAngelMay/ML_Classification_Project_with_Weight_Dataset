# ML Classification Project with Weight Dataset

## Description
#### The goal of this project related to finding out if there was a way to predict one of the limited weight classes form the given features. There were several numeric and categorical attributes and, while there was not any missing data, there were efforts put into this Jupyter notebook such that if there was addition of any instance(s) then imputation, encoding, transforming, and scaling would nonetheless have addressed missing features from such instance(s).

#### The data had been downloaded from the UCI Machine Learning Repository and there was basic data analysis, including a search for correlations, histogram plotting and the like. Notably, because the classes are ordinal (from a class that relates to underweight to normal weight to eventually three ordinal classes for obese status), there was conversion of the labels from the initial labels to an integer from [-1, 5] and then back to the original classes. There was already a high correlation in the dataset once there was this integer-label conversion, with a value over 0.90, but with the feature extraction of a density feature (weight divided by height) and a BMI feature (weight divded by the square of height), there were correlations over 0.95 and 0.97, respectively. 

#### A few algorithms were applied, but the highlight of this Jupyter notebook was to use ensembling to improve performance, specifically in use of a voting classifier. It was fascinating to see how algorithms performed from decently to good on their own, and then to ensemble them. The step of tuning the hyperparameters was temporally costly compared to my other projects, but it resulted in a phenomenal classifier.

#### Python has become one of the most popular and used programming languages in huge part because of how it has one of the largest and ambitious communities. Thus, there has been the development of many applicable and important libraries, modules, packages, and functions. NumPy was used because arrays are essential to anything and everything data analysis and machine learning in Python, with NumPy being foundational to Pandas and Matplotlib. NumPy also provides several important transformations and applications throughout this project. Pandas methods and similar tools were important to the progress of this project, and it was especially helpful in making measurements related to the dataframes themselves. Matplotlib is important for plotting in a lot of machine learing endeavors and is a strong staple for visualizations. Scikit-Learn was essential to this project, as not only does it provide tools for cleaning, scaling, transforming, and preparing data, but also for the algorithms that this project utilized. The metrics for evaluating performance were also important and provided by Scikit-Learn.

#### While there was no missing data, there was still effort to set up a preprocessing pipeline among other items. Still, it was done, with the inclusion of data transforming and scaling of numeric features and encoding of categorical features. One part I learned from was when feature extraction came through and produced two highly correlating features to the numerically ordered and changed classes - it showed me that, with limited features, there can always be the possibility of making even better features, depending on the dataset and context. Debugging was tedious, as there was need to check what items could be insert into what functions and this project dealing with multioutput classification instead of binary made it a tad bit more time-consuming, but was nonetheless informative and revealing to me.

#### My desire is to become an even better feature engineer with even better feature extractions. While several algorithms were applied, I would like to see or personally apply other algorithms with optimzed hyperparameters, with the goal of having an even lower root mean square error and an even better generalization. In addition to multiple algorithms being utilized, ensembling was the main key of this porject, and while tuning this voting classifier's hyperparameters was temporally expensive, it was an enthralling experience for me. I hope and apply myself to also become more familiarized and experienced with more ensembling methods.

## Use
#### Anaconda should be downloaded and with it, Jupyter notebooks should be a familiar topic to any user that wants to use this project. The dataset was downloaded from the UCI Machine Learning Repository website. This specific project falls under the MIT License and should be treated accordingly.

## References
#### Géron, Aurélien. *Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems*. 3rd ed., O’Reilly Media, 2022.

## Dataset Citation
##### Estimation of obesity levels based on eating habits and physical condition . (2019). UCI Machine Learning Repository. https://doi.org/10.24432/C5H31Z.
