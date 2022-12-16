## Table of Contents
- [Contact Info](#Contact_info)
- [Exploring Data](#exploring_data)
- [Machine Learning](#machine_learning)
- [Paper review](#paper_review)

## Contact Info<a name="Contact_info"></a>
- [LinkedIn](https://www.linkedin.com/in/ching-wen-jasmine-wang/)
- Email: jasminewang6026@gmail.com

## Data Analysis<a name="exploring_data"></a>

### [Twitter-Data-Analysis](https://github.com/JasmineWang553/Jasmine-s-Portfolio/tree/main/twitter-data-wrangling-analysis)

- **Intro**: [WeRateDogs](https://twitter.com/dog_rates?lang=en) is a Twitter account that posts pictures of other people’s dogs with a humorous comment and gives them a rating out of 10 per dog in the picture.  However, the uniqueness comes in that the numerator of the rating can exceed the denominator 10, depending on the content. 
- **Goal**: Therefore it will be interesting to investigate if WeRateDogs' unique rating follows the trend of popularity, which is measured by number of retweets and favorites. 
- **Tech used**: Twitter API, Tweepy, Requests, JSON, Numpy, Pandas, Seaborn

### [Why people don't show up on medical-appointments](https://github.com/JasmineWang553/Jasmine-s-Portfolio/tree/main/no-show-medical-appointments)
- **Intro**: It is not uncommon that people don't show up for medical appointments and miss their chance to receive proper treatments. Different reasons may be present such as forgetting appointments or something urgent had happened. Therefore, it would be helpful to understand the factors affecting people showing up on appointments and predict if a patient will miss their appointment or not next time. The predictions can further help medical staffs to know which patients may need extra reminders.
- **Goal**: What are the factors that most correlate with the show-up rate of medical appointments?
- **Tech used**: Matplotlib, Seaborn, Jupyter Notebook, Pandas, scikit-learn(LogisticRegression)<br>

### [Explore-Profitable-Android-IOS-apps-in-2017-2018](https://github.com/JasmineWang553/Jasmine-s-Portfolio/tree/main/profitable-IOS-android-app-analysis)
- **Intro**: To determine whether or not the company should list their app on Google Play Store or on App Store. Also, in which category and price range should the app be set at?
- **Research Question**: Which store is more profitable? What category and price range should the company choose for the corresponding shop?
- **Tech used**: Matplotlib, Seaborn, Jupyter Notebook<br>


## Machine Learning<a name="machine_learning"></a>


### [COVID and Lung Disease Detection from Xray images](https://github.com/JasmineWang553/Jasmine-s-Portfolio/tree/main/covid19-detection-computer-vision) -- Computer Vision (Deep Learning)
- **Intro**: Due to the quick spread of COVID-19, many patients were unable to access required treatments in time. Therefore, we are motivated to develop deep learning models that can quickly and accurately classify lung diseases and address them with the appropriate treatments in a timely matter.
- **Goal**: Find the best model with lowest misclassification rate for certainly contagious disease such as COVID and Viral Pneumonia, and highest test set accuracy. Utilizing transfer learning on Pytorch pretrained Convolutional Neural Networks (CNN): ResNet, VGG, AlexNet, and a benchmark model with Logistic Regression to predict correct class labels Covid-19, Viral Pneumonia, normal(healthy) and Lung Opacity(non covid, non viral pneumonia infections) from X-ray images. 
- **Tech used**: Pytorch, pandas, numpy, opencv, matplotlib<br>

### [Heart-Failure-Patient-Death-Classification](https://github.com/JasmineWang553/Jasmine-s-Portfolio/tree/main/heart-failure-patient-death-classification) -- Classification
- **Intro**:Heart failure (HF) is a serious chronic condition, which occurs when heart muscles are too weak to pump enough oxygen and blood to other organs and can sometimes lead to death. Therefore, it is reasonable to suspect some body conditions are associated with symptoms and mortality in HF, such as older adults or people with high blood pressure may more likely die from HF. 
- **Goal**: Our goal is to analyze factors contributing to the death of heart failure patients and create a model that predicts if a heart failure patient given different heart conditions and chronic diseases will die or not.
- **Tech used**: Random Forest, Grid Search with Cross Validation, Feature Selection, SciPy, Scikit Learn<br>
- **Award**: Best Oral Presentation<br>


### [Yelp-Rating-Prediction](https://github.com/JasmineWang553/Jasmine-s-Portfolio/tree/main/yelp-rating-prediction) -- Multiple Linear Regression
- **Intro**: Yelp is a site where users can write online reviews for places they visit. 
- **Goal**: We are given data that includes each review’s text, as well as several other characteristics of each review. We are aiming to use a sample of Yelp restaurant reviews to produce a model that will allow us to predict the star ratings of other Yelp restaurant reviews. Although there are better ways to make predictions, such as machine learning, this class focuses on regression analysis, therefore we decided to use multiple linear regression. In order to minimize the mean square error, we also performed feature extractions from comments of the users. 
- **Tech used**: Multiple Linear Regression, k fold Cross Validation, R<br>



### [Construction-of-Knowledge-Graph](https://github.com/JasmineWang553/Jasmine-s-Portfolio/tree/main/construction-of-knowledge-graph) -- Natural Language Processing
- **Intro**: Knowledge graph is an abstract data representation that can be constructed from the unstructured text. Such structured representation helps people and machines to understand the information more efficiently. 
- **Goal**: In this project, our goal is to construct reasonable knowledge graphs from the text appearing our real life. To achieve our goal, we collected and annotated the text data manually from different data sources. Based on our collected text data, we evaluated several method candidates, selected the best method to extract the triplets from sentences, and constructed the knowledge graphs. 
- **Tech used**: NetworkX, spaCy, Stanford openIE, Stanford NLP, Stanford Scene Graph Parser, Python, Java<br>

## Paper Review<a name="paper_review"></a>

### [Topic Modeling using SVD appraoch](https://github.com/JasmineWang553/CS-532-Project-Topic-modeling-LSA-paper-review/blob/main/CS-532-final-project-Chingwen-Wang-Mo-Xiao.pdf)
- **Intro**: As technology advances, massive data/texts are generated everyday. It would cost a lot of time and money to read through every single document to find the information we needed. Therefore, if we can efficiently associate each document with relevant topics it contains, we can improve the process of information retrieval. This goal can be achieved through topic modeling, which discovers abstract topics embedded in a collection of documents. 
- **Goal**: In this project, we will explore a renowned method of topic modeling, latent semantic analysis (LSA), which uses a singular value decomposition (SVD) approach [(Gong & Liu, 2001)](https://www.cs.bham.ac.uk/~pxt/IDA/text_summary.pdf). Also, we would like to know by incorporating syntactic information [(Kanejiya, Kumar & Prasad, 2003)](https://doi.org/10.3115/1118894.1118902), part of speech [(Kakkonen, Myller & Sutinen, 2006)](https://arxiv.org/abs/cs/0610118), or implementing regularization methods of lasso and ridge regression [(Wang, Q., Xu, J., Li, H., & Craswell, N., 2013)](http://www.hangli-hl.com/uploads/3/1/6/8/3168008/rlsi-tois-revision.pdf) can help improve space and time complexity of LSA.



