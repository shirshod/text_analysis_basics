# [Text Analysis: An Introduction](https://github.com/shirshod/text_analysis_basics/blob/main/intro_textanalysis.ipynb)

The topics and code covered in this notebook are mainly sourced from Jonathan Soma's website, InvestigateAI (with little tweaks here and there) and from my own research.  

The comments and explanations are either my own or from the website. Refer to the website for more examples and details. 

Read more [here](https://investigate.ai/text-analysis/).

##### Note: 
Some visualizations may not be compatible with viewing directly on Github. View it by copying the URL to the notebook [here](https://nbviewer.org/) or run the code after downloading this repo.

## Contents

### 1. Simple word counting [line 1]
#### 1.1 Using Python counter [1]
##### 1.1.1 Counting words in a list or string [1]
##### 1.1.2 Counting words in a book [6]
##### 1.1.3 Only extracting some words with regular expressions [8]
#### 1.2 Using CountVectorizer [15]
##### 1.2.1 Customizing countvectorizer to read one-letter words [18]
##### 1.2.2 Counting words in a book [19]
##### 1.2.3 Counting words in multiple books [22]
<br> 

### 2. Advanced word analysis [line 25]
#### 2.1 Removing words that are not relevant [27]
#### 2.2 Combining variations using PorterStemmer [29]
#### 2.3 TF-IDF: Term Frequency — Inverse Document Frequency [31]
##### 2.3.1 Term Frequency [31]
##### 2.3.2 Inverse Document Frequency [33]
##### 2.3.3 Comparing TF vs IDF shares for "fish" and "meow" from previous computations [35]
##### 2.3.4 Comparing L1 and L2 vectorizers [37]
#### 2.4 Clustering documents/text [41]
##### 2.4.1 Displaying top terms and sentence clusters [42]
##### 2.4.2 Computing similar example but with three clusters instead of two [44]
##### 2.4.3 Visualizing text similarity [47]
#### 2.5 N-grams and multiword phrases [51]
##### 2.5.1 Counting n-grams [53]
<br> 

### 3. Sentiment analysis [line 57]
#### 3.1 NLTK: Natural Language Toolkit [58]
#### 3.2 TextBlob [63]
#### 3.3 Comparing the different methods [66]
#### 3.4 Designing own sentiment analyzer [68]
##### 3.4.1 Installing scikitlearn [68]
##### 3.4.2 Importing training data [69]
##### 3.4.3 Using TfidVectorizer to vectorize the database of tweets [72]
##### 3.4.4 Initializing variables for analysis [73]
##### 3.4.5 Importing machine-learning modules [74]
##### 3.4.6 Using machine-learning modules to train the computer on the tweet dataset [75]
##### 3.4.7 Testing the machine-learning modules on a block of text to predict whether a sentence is positive or negative [79]
##### 3.4.8 Test/train splits and confusion matrices: Testing modules on the original tweet database itself [85]
#### 3.5 Improving the models [94]
##### 3.5.1 Training modules on more words [97]
##### 3.5.2 Linear SVC method [99]
##### 3.5.3 Multinomial Bayes method [101]
#### 3.6 NRC Emotion Lexicon [103]
##### 3.6.1 Importing NRC Emotion Lexicon database [103]
##### 3.6.2 Displaying what emotions are recorded [105]
##### 3.6.3 Counting words per emotion [106]
##### 3.6.4 Displaying words related to one particular emotion [107]
##### 3.6.5 Displaying database by word [108]
##### 3.6.6 Displaying associated emotions for each word [109]
##### 3.6.7 Filtering database for one emotion [110]
##### 3.6.8 Filtering database for multiple emotions [111]
##### 3.6.9 Displaying words for one emotion [112]
[Note: Also refer to SOTU sentiment analysis]
<br> 


### 4.Topic Modeling: Concepts, People and Places [line 113]
#### 4.1 Importing dataframe of State of the Union speeches [113]
##### 4.1.1 Finalizing data [115]
#### 4.2 Importing libraries for plotting [117]
#### 4.3 NMF Topic Modeling [118]
##### 4.3.1 Applying stemmer to vectorize all words in speeches database [118]
##### 4.3.2 Applying NMF module [120]
##### 4.3.3 Storing topics list as a dataframe [121]
##### 4.3.4 Merging speeches database with topics dataframe [122]
##### 4.3.5 Rearranging dataframe for plotting on Altair [123]
#### 4.4 LDA Topic Modeling [124]
#### 4.5 GridSearchCV: Choose the right number of topics for modeling [129]
##### 4.5.1 Searching for best parameters [129]
##### 4.5.2 Running LDA modeling with params suggested by GridSearchCV [130]
#### 4.6 Gensim Topic Modeling [132]
##### 4.6.1 Using LSI/NMF with Gensim [136]
##### 4.6.2 Using LDA with Gensim [143]
#### 4.7 Introduction to Named Entity Recognition (NER) [149]
##### 4.7.1 Loading a language model [151]
##### 4.7.2 Displaying entities [152]
##### 4.7.3 Highlighting entities [153]
##### 4.7.4 Displaying as a dataframe [154]
##### 4.7.5 Processing longer texts [155]
##### 4.7.6 Processing an article [160]
#### 4.8 Introduction to Word Embeddings [166]
##### 4.8.1 Visualizing with spaCy [177]
#### 4.9 Conceptual document similarity using Cosine Similarity [181]
##### 4.9.1 Counting words [182]
##### 4.9.2 Word embeddings [184]
##### 4.9.3 Limitations of word embeddings [188]
#### 4.10 Comparing documents in different languages: Universal Sentence Encoding and Tensorflow [190]
##### 4.10.1 Importing libraries and modules [192]
##### 4.10.2 Loading the Multilingual Universal Sentence Encoder (version 3) [193]
##### 4.10.3 Testing on a sentence [194]
##### 4.10.4 Loading dataframe and generating dimensions [195]
##### 4.10.5 Running cosine similarity [196]
#### 4.11 Converting documents to text [197]
##### 4.12 Tesseract [198]
##### 4.13 Tika [200]
