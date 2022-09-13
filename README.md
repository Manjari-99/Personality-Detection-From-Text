# Personality-Detection-From-Text
A 3-way approach to find out the Big Five Personality Traits from Text.

*Introduction*

Written documents often capture the heart and soul of our thought process. Hence, written texts are preferred over oral contracts. Text messaging, like email and instant messaging, is an emerging means of electronic communication with important implications for our understanding of communication processes. With the developing social media, people are now pouring their hearts out through blogs and write ups.
The spark that ignites here lies the basic domain of linguistics and vocabulary.
It has been observed through various research domains that the linguistic style, textual tone, vocabulary and grammar of a person is consistent with his or her personality. 
The purpose of this project was to undertake some analyses of how the language used in text varies as a function of personality traits and the interpersonal context.
We have opted for multiple models for taking the average of the outcomes for a better accuracy. We use both supervised machine learning as well as deep learning approach. 

*Motivation*

Personality is a combination of an individual’s behaviour, emotion, motivation, and thought pattern. Our personality has a great impact on our mind, our behaviour our course of. Knowing one’s personality can be very helpful in order to analyse one’s mental health. 
Sentiment analysis plays a key role here. 
This project has far-reaching real-world applications like: 
•	Product Recommendations by e-stores
•	Mental health check-ups
•	Forensic application to understand criminal psychology
•	To detect criminal tendency
•	To detect depression and suicidal tendencies.

*Objective*

In the 1970s two research teams led by Paul Costa and Robert R. McCrae of the National Institutes of Health and Warren Norman and Lewis Goldberg of the University of Michigan at Ann Arbor and the University of Oregon, respectively, discovered that most human character traits can be described using five dimensions. Surveys of thousands of people yielded these largely independent traits.
The objective of this model is to detect the absence/presence of five different personality attributes based on texts gathered from various personalities.
These personality attributes are:
•	Extroversion (EXT): - Is the person outgoing, talkative, and energetic versus reserved and solitary?
•	Neuroticism (NEU): - Is the person sensitive and nervous versus secure and confident?
•	Agreeableness (AGR): - Is the person trustworthy, straightforward, generous, and modest versus unreliable, complicated, meagre, and boastful?
•	Conscientiousness (CON): - Is the person efficient and organized versus sloppy and careless?
•	Openness (OPN): - Is the person inventive and curious versus dogmatic and
cautious.

*We took two different approaches to implement our project, the first one is naive
based on Machine Learning and the other approach deals with Neural Networks
which is based on Deep Learning.*

**I. Machine Learning Approach**: In this approach we first clean the gathered
data and store it in a dataframe, after that we remove the unwanted characters and
words and pick-up the words which are then used to create the bag of words, then
we convert the text in the form of vectors and then we build Bayes classifier
model to train and test on our data and then finally we predict the output using the
model built.

**II. Deep Learning Approach**: In this approach we first clean the gathered data
and store it in a dataframe. We fed sentences from the essays to convolution filters to obtain the sentence. We represented each individual essay by aggregating the vectors of its sentences. We concatenated the obtained vectors with the Mairesse features,4 which were extracted from the texts directly at the preprocessing stage;
this improved the method’s performance. then we merge five target attributes into a single target attribute, after that we create the deep learning model of 4 layers using ANN, then we split the data into train and test dataset. After that we measure the accuracy based on the test data of the model built



*Methodology*
 
•	Data Preprocessing 
•	Date Cleaning.
•	Text Preprocessing – coversion to lowercase, removing special characters.
•	Document Level Feature Extraction.
•	Data Filtering – removing stop words.
•	Feature Extraction with Count Vectorizer.
•	Classification Model Creation – Using both Naïve and Deep Learning Approach.
•	Training
•	Testing

*Future Prospects and Plans*

•	To further improve the accuracy.
•	To incorporate new technology.
•	A depression detection tool may be created by comparing the texts of the same person over a period of time.
•	Trying out better deep learning approaches.
•	Using NLTK (Natural Language Toolkit)
•	Creating a front end for a better user interface and an accessible website.



*Conclusion*
So here we are using both deep learning as well as machine-learning approach where we found almost similar accuracy for both scenarios.

Some minor improvement scopes in Deep Learning approach: In the model training part we could have used “callbacks” (it checks if there is any improvement in the accuracy if so, the training continues otherwise the code stops executing) so that the computations could have been lesser.

Purpose of this whole project was to find an effective solution for prediction of personality and mental health behaviour of human beings. And the strategies used, turned out to be quite effective in doing so. Future development of this project will lead to further increase in accuracy of the outcomes.


