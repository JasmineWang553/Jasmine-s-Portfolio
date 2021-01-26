## Exploring Data

### [Explore-Free-Android-IOS-apps-in-2017-2018 (DataQuest Guided)](https://github.com/JasmineWang553/Profitable-IOS-android-app-analysis)
- **Intro**: For this project, we pretend that we are working as data analysts for a company that builds Android and iOS mobile apps. We make our apps available on Google Play and the App Store, and we only build apps that are free to download and install, and our main source of revenue consists of in-app ads.
- **Goal**: Explore which kind of free apps are more popular on Google play and Apple store and which age group is associated with the popularity.
- **Tech used**: Matplotlib, Seaborn, Jupyter Notebook

### [Explore-Profitable-Android-IOS-apps-in-2017-2018](https://github.com/JasmineWang553/DQ_Explore-Android-IOS-apps-in-2017-2018)
- **Intro**: Continue on the last project: [Explore-Free-Android-IOS-apps-in-2017-2018](https://github.com/JasmineWang553/Profitable-IOS-android-app-analysis/blob/master/Explore%20profitable%20IOS%20%26%20Android%20App%20Analysis.ipynb), pretend that the company wants revenue from app downloads. The company decided that if this app is successful on Google Play Store then they will also list this app on App Store.
- **Research Question**: Therefore, we want to build an app and set a reasonable price range. What category and price range should the company choose? 
- **Tech used**: Matplotlib, Seaborn, Jupyter Notebook



## Machine Learning
### [Stat-333-Project-Yelp-Rating-Prediction](https://github.com/JasmineWang553/Stat-333-Project-Yelp-Rating-Prediction) -- Multiple Linear Regression
- **Intro**: Yelp is a site where users can write online reviews for places they visit. 
- **Goal**: We are given data that includes each review’s text, as well as several other characteristics of each review. We are aiming to use a sample of Yelp restaurant reviews to produce a model that will allow us to predict the star ratings of other Yelp restaurant reviews. Although there are better ways to make predictions, such as machine learning, this class focuses on regression analysis, therefore we decided to use multiple linear regression. In order to minimize the mean square error, we also performed feature extractions from comments of the users. 
- **Tech used**: Multiple Linear Regression, k fold Cross Validation, R

### [Heart-Failure-Patient-Death-Classification](https://github.com/JasmineWang553/Heart-Failure-Patient-Death-Classification) -- Classification
- **Intro**:Heart failure (HF) is a serious chronic condition, which occurs when heart muscles are too weak to pump enough oxygen and blood to other organs and can sometimes lead to death. Therefore, it is reasonable to suspect some body conditions are associated with symptoms and mortality in HF, such as older adults or people with high blood pressure may more likely die from HF. 
- **Goal**: Our goal is to analyze factors contributing to the death of heart failure patients and create a model that predicts if a heart failure patient given different heart conditions and chronic diseases will die or not.
- **Tech used**: Random Forest, Grid Search with Cross Validation, Feature Selection, SciPy, Scikit Learn
[Code](https://github.com/JasmineWang553/Heart-Failure-Patient-Death-Classification/blob/main/Heart%20Failure%20Patient%20Death%20Classification.ipynb)   [Report](https://github.com/JasmineWang553/Heart-Failure-Patient-Death-Classification/blob/main/Data%20Challenge%20executive%20report.pdf)    [Slides](https://github.com/JasmineWang553/Heart-Failure-Patient-Death-Classification/blob/main/Data%20Challenge.pptx)
### [Stat-451-Project-Construction-of-Knowledge-Graph](https://github.com/JasmineWang553/Stat-451-Project-Construction-of-Knowledge-Graph) -- Natural Language Processing
- **Intro**: Knowledge graph is an abstract data representation that can be constructed from the unstructured text. Such structured representation helps people and machines to understand the information more efficiently. 
- **Goal**: In this project, our goal is to construct reasonable knowledge graphs from the text appearing our real life. To achieve our goal, we collected and annotated the text data manually from different data sources. Based on our collected text data, we evaluated several method candidates, selected the best method to extract the triplets from sentences, and constructed the knowledge graphs. 
- **Tech used**: NetworkX, spaCy, Stanford openIE, Stanford NLP, Stanford Scene Graph Parser, Python, Java


## Paper Review

### [Topic Modeling using SVD appraoch](https://github.com/JasmineWang553/CS-532-Project-Topic-modeling-LSA-paper-review/blob/main/CS-532-final-project-Chingwen-Wang-Mo-Xiao.pdf)
- **Intro**: As technology advances, massive data/texts are generated everyday. It would cost a lot of time and money to read through every single document to find the information we needed. Therefore, if we can efficiently associate each document with relevant topics it contains, we can improve the process of information retrieval. This goal can be achieved through topic modeling, which discovers abstract topics embedded in a collection of documents. 
- **Goal**: In this project, we will explore a renowned method of topic modeling, latent semantic analysis (LSA), which uses a singular value decomposition (SVD) approach [(Gong & Liu, 2001)](https://www.cs.bham.ac.uk/~pxt/IDA/text_summary.pdf). Also, we would like to know by incorporating syntactic information [(Kanejiya, Kumar & Prasad, 2003)](https://doi.org/10.3115/1118894.1118902), part of speech [(Kakkonen, Myller & Sutinen, 2006)](https://arxiv.org/abs/cs/0610118), or implementing regularization methods of lasso and ridge regression [(Wang, Q., Xu, J., Li, H., & Craswell, N., 2013)](http://www.hangli-hl.com/uploads/3/1/6/8/3168008/rlsi-tois-revision.pdf) can help improve space and time complexity of LSA.



