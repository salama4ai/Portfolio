# [Portfolio](https://github.com/salama4ai/Portfolio) and [courses](https://github.com/salama4ai/Courses)
my projects sample

# 1- [Deep Learning Project](https://github.com/salama4ai/Proteinea) (protienea firm)
- in this project, i were asked to generate a **date** given a set of conditions, using any neural network architecture i would like. my input (x) is the conditions on the date, and the output (y) is ANY date that complies with those conditions. This means that, like any generative model, there are many right answers per input x.
[here](https://github.com/salama4ai/Proteinea/blob/main/problem%20statement/Deep%20Learning%20Challenge.pdf) is the complete problem statement 

#### Tools:-
+ **Sklearn** , **Matplotlib** , **Numpy** , **Pandas**, **pytorch**, **imblearn**, **calendar**

#### steps:-
+ started by [Exploratory data analysis, then preprocessing](https://github.com/salama4ai/Proteinea/blob/main/model/preprocessing.ipynb)
+ then divide the problem into 2 subproblems:- 
	+ [1- predicting the year submodel](https://github.com/salama4ai/Proteinea/blob/main/model/training_years.ipynb)
	+ [2- predicting the day submodel](https://github.com/salama4ai/Proteinea/blob/main/model/training_days.ipynb)
    
	i started by additional preprocessing step according to the submodel needs, then separete training and test sets  fix the imbalanced data by oversampling(only on training set), then prepare data for neural network, and made traing steps finally save the results to csv file, and the trained model

# 2- [(NLP)Topic Extraction (LDA) project](https://www.github.com/salama4ai/salama4ai-MinaPharm) (MinaPharm firm)

#### Objective:-

i were provided with a medical related dataset, containing 5k articles. i was required to demonstrate my NLP, data-mining & topic extraction skills to extract the topics that are included within the dataset along with mapping each article to the corresponding topic names. Each document should be matched to the top three most relevant topic names including the matching probability score.

#### Tools:-
+ **Numpy**, **Pandas**, **pytorch**, **gensim**, **spacy**, **scispacy**, **NLTK**, **REGEX**, **Sklearn**, **Matplotlib**

#### steps:-
+ i started by [exploratory data analysis(EDA) and preprocessing](https://github.com/salama4ai/salama4ai-MinaPharm/blob/main/scripts/preprocessing.ipynb)
    - Convert the text into lowercase
    - Split text into words (Tokenize)
    - Remove the stop loss words
    - Remove the Punctuation, any symbols, and special characters
    - Normalize the word 
    
then made [**LDA** implementation with both **gensim** and **sklearn**](https://github.com/salama4ai/salama4ai-MinaPharm/blob/main/scripts/topic%20extraction%20using%20LDA%20model.ipynb)



# 3- [Rasa Chatbot Project](https://www.github.com/salama4ai/salama4ai-chatbot)(master-linux firm)

#### Objective:-

The goal is to create Rasa Chatbot that can provide answers for users questions about the Population and the capitel city of collecton of countries, where the chatbot use the restful API to get that information from third-party website

#### Tools:-

+ **Rasa Framework**

# 4- [Data wrangling task](https://www.github.com/salama4ai/salama4ai-Finalyst)(Finalyst firm)
#### Objective:-
+ the goal of this small task is to extract tables from pdf file, clean the data and make some preprocessing then save it as an excel file, to be easy for additional manipulation

#### Tools:- 
+ **Numpy**, **Pandas**, **Tabula**

# 5- [deployment project](https://github.com/salama4ai/salama4ai_homzmart)(Homzmart firm)



# 6- [RPA project](https://github.com/salama4ai/Researcher-Nile-University) (Nile University)
+ i was tasked with devising a robotic system that can paint patterns on athletic fields and roadways. the chosen platform is differentially driven robot with a paint sprayer mounted a distance of "L" from the center along 
+ i asked to implement a control low to drive the robot such that the location of the paint sprayer follows the trajectory given and described by given parametric equations




#### sample of python practicing on https://www.hackerrank.com/salama4ai
