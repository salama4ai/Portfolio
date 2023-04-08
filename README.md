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



# 3- [Rasa Chatbot Project](https://github.com/salama4ai/Rasa-chatbot-) (master-linux firm)

#### Objective:-

The goal is to create Rasa Chatbot that can provide answers for users questions about the Population and the capitel city of collecton of countries, where the chatbot use the restful API to get that information from third-party website

#### Tools:-

+ **Rasa Framework**

# 4- [(NLP) Named Entity Recognition Task](https://github.com/salama4ai/insideaiml) (Insideaiml firm)

#### Tools:-
+ **Pandas**, **Numpy**, **Spacy**, **String**, **BeautifulSoup**, **REGEX**, **Geonamescache**
#### Objective:-
+ the goal of this task is to Create web app through Flask and create POST API and post API will take Name(text) as input parameter and should ruturn is it City or Person in JSON format. it's very simple task sent to as an assessment task from Insideaiml firm.
#### Steps:-
+ i started with preprocessing data, then use Spacy and Geonamescache frameworks to add classification to every column determine wether the column contains person entity or city entity.

# 5- [(NLP) wake word listener](https://github.com/salama4ai/Mycroft-project-salama4ai) (Alkawarizmi firm)

#### Tools:-
+ **Mycroft-core**, **Mycroft-Precise**
#### Objective:-
+ The Wake Word Listener's job is to continually listen to sounds and speech around the Device, and activate when the sounds or speech match a Wake Word. Mycroft provides an open source Wake Word Listener called Precise. which i used in this project to train a model to wake up when it hears hey-savant.

+ Mycroft Precise is fully open source and can be trined to recognize anything from a name to a cough. Precise is a wake word listener. The software monitors an audio stream ( usually a microphone ) and when it recognizes a specific phrase it triggers an event. When the software recognizes this phrase it puts the rest of Mycroft's software into command mode and waits for a command from the person using the device. where i trained this tool to triger when it hear "hey-savant".


# 6- [Data-Manipulation(Elasticsearch) project](https://github.com/salama4ai/salama4ai_homzmart) (Homzmart firm)
#### Tools:-
+ **ElasticSearch**, **Kibana**, **Flask**, **Numpy**, **Pandas**, **requests**, 



# 7- [RPA project](https://github.com/salama4ai/Researcher-Nile-University) (Nile University)
+ i was tasked with devising a robotic system that can paint patterns on athletic fields and roadways. the chosen platform is differentially driven robot with a paint sprayer mounted a distance of "L" from the center along 
+ i asked to implement a control low to drive the robot such that the location of the paint sprayer follows the trajectory given and described by given parametric equations


# 8- [Data wrangling task](https://www.github.com/salama4ai/salama4ai-Finalyst)(Finalyst firm)
#### Objective:-
+ the goal of this small task is to extract tables from pdf file, clean the data and make some preprocessing then save it as an excel file, to be easy for additional manipulation

#### Tools:- 
+ **Numpy**, **Pandas**, **Tabula**



#### sample of python practicing on https://www.hackerrank.com/salama4ai
