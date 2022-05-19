### Web-Analytics For Text Sentiment Analysis And Toxicity Classification
</br>
</br>

#### Code & Files
- [sentimentModel.ipynb](https://colab.research.google.com/drive/1KFYRvok-gteRPb38IKTWJHd-ys0lGyAk?usp=sharing)
- [toxicityModel.ipynb](https://colab.research.google.com/drive/1nlEXM98zrhmSnCb8nAnKkUYO61EgFOOp?usp=sharing)
- [data.csv](https://drive.google.com/drive/folders/1cBBcg_C4R-EWTHd-2j5kddEJD5Oo7ntA?usp=sharing)
</br>

#### Motivation
Small(er) businesses may often experiment with new product/service lines or new variations of existing products/services but lack the means to better understand the correlation between these changes/innovations and customer sentiment. For example, a resturant owner releases a new dish, but as exciting as it is, the owner themselves may be anxious about how much the average customer actually likes the new release. Owners may also want to better understand  correlations between more extreme/negative sentiments with aspects of the business should toxic comments appears.
This project attempts to provide a solution to the problem statement using _Natural Language Processing (NLP)_ techniques/technologies and online reviews from _(Yelp.com)_. It implements a pipeline for efficient use to get relevant and useful information, i.e. percentage of positive comments.
</br>
</br>

#### Version History
- Version 1: Implements barebone text sentiment analysis using an appropriate pre-trained model
- Version 2: Preprocesses data for training
- Version 3: Constructs and trains (locally) a _Artificial Neural Network (ANN)_ for text toxicity classification
</br>

#### Data
Large number of Wikipedia comments labeled by human raters for toxicity, provided by the _Jigsaw_ company.
</br>
</br>

#### Algorithms
- _Bidirectional Encoder Representations from Transformers (BERT)_ from _Hugging Face_
- _Convolutional Neural Network (CNN)_ (built & train using TensorFlow dependencies)
</br>

#### Current Results
TBI...
</br>
</br>

#### Future Versions
- Version 4: Implements automated scrapper for obtaining customer reviews on **all** pages for a given business listed on _Yelp.com_
- Version 5: Combines previous versions (scopes) and performs appropriate analysis to produce relevant and useful information
- Version 6: Produces visualizations for the given analysis/information
- Version 7: Implement deployment pipeline using <>
