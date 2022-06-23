</br>

### WebR: Web-Analytics For Review Sentiment Analysis
</br>
</br>


Please visit the [project portfolio]() for full details :D

#### Code & Files
- [bindOI.ipynb](https://colab.research.google.com/drive/1KFYRvok-gteRPb38IKTWJHd-ys0lGyAk?usp=sharing)
- [data](https://drive.google.com/drive/folders/1uGhbZyfKcHRjALYVkDdJGdzI7j3rpMaS?usp=sharing)
</br>
<br/>

#### Motivation
Small(er) businesses may often experiment with new product/service lines or new variations of existing products/services but lack the means to better understand the association (and potential correlation) between these changes/innovations and customer sentiment. For example, a resturant owner releases a new dish, but as exciting as it is, the owner themselves may be anxious about how much the average customer actually likes the new release. Owners may also want to better understand  associations between more extreme/negative sentiments with aspects of the business should toxic comments appears.
This project attempts to provide a solution to the problem statement using _Natural Language Processing (NLP)_ techniques/technologies and online reviews from _(Yelp.com)_. It implements a pipeline for efficient use to get relevant and useful information, i.e. percentage of positive comments.
</br>
</br>
<br/>

#### Data
Large number of Wikipedia comments labeled by human raters for toxicity, provided by the _Jigsaw_ company.
</br>
</br>
<br/>

#### Algorithms
- _Bidirectional Encoder Representations from Transformers (BERT)_ from _Hugging Face_
- _Convolutional Neural Network (CNN)_ (built & train using TensorFlow dependencies)
</br>


--

</br>

#### Version History
- Version 1: Implements barebone text sentiment analysis using the BERT model from Hugging Face
- Version 2: Implements scrapper for scrapping reviews (on all pages) for a given business listed on _Yelp.com_. Also performs data preprocesses when appropriate
- Version 3: Constructs and trains (locally) a Deep Neural Network (see code file for details) for text toxicity classification

#### Future Versions
- Version 4: Combines previous versions (scopes) and performs appropriate analysis to produce relevant and useful information and visualizations
- Version 5: Implement deployment pipeline
