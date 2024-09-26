# Access 2024 Workshop 

## Machine Learning and You: A Whirlwind Tour

Location:
Concordia University’s Webster Library, located at 1400 De Maisonneuve Blvd. W. in downtown Montreal
 [[link]](https://accessconference.ca/access-2024-hackfest-workshop/)

John Fink (McMaster University)

Tim Ribaric (Brock University)

9:30 AM to 11:30 AM

Large Language Models have exploded in popularity in the past 2 years prompting the creation of new and exciting ways to do research. It is now possible to use AI to gather insights and develop rich insights into data without being a full fledged data scientist. This workshop will begin with a tour through the Library Carpentry Machine Learning for Librarians curriculum before delving into the hands-on portion where learners will experiment with running different models and environments on their own computers. Participants will learn about the wide variety of options that exist outside of the narrow range of popular tools that find themselves in the news, and learn about the wide world of machine learning, from edge computing on microcontrollers to sophisticated language models running on supercomputers.



## Setup

Due to the fact that working with AI models requires lots and lots of data, we'll be distributing model binaries and test data in class on USB sticks to save bandwidth

[GPT4ALL](https://www.nomic.ai/gpt4all) - This will be the client program that we run on your laptop. This will run the different models that we will experiment with.

[Model 1 - Qwen2.5-0.5B-Instruct](https://huggingface.co/Qwen/Qwen2.5-0.5B-Instruct-GGUF) - Super lightweight model

[Model 2]() -

[Data Set](data/) - A collection of reviews about different Spider Man movies ranking at different scores. (Data orginally from [Kaggle](https://www.kaggle.com/datasets/okancan/spiderman-movies-imdb-reviews)) The data is split up into two files:

- `Spidey_Bad/Spider_Verse_Ranked_1_2_3.txt` - The reviews from the dataset that ranked the movie between 1-3, for a total of about 9000 words

- `Spider_Good/Spider_Verse_Ranked_10.txt` - The review from the dataset that ranked the movie at a perfect 10, for a total of about 10000 words


## Agenda

[Slides](presentation.pdf)

|||
|---|----|
|0930|Welcome & Introductory Discussion<br/>[Intro to AI for GLAM](https://carpentries-incubator.github.io/machine-learning-librarians-archivists/) |
|1000|Multiple Models running locally|
|1045|Adding Data & Retrieval Augmented Generation|
|1115|Concluding Discussion and Wrap-up|

### Activity 1 - Two models answering the same thing

We are going to explore asking the same question of two different models to see what difference in results we can get.

### Activity 1b - Other models

Check out [Hugging Face](https://huggingface.co/) to see all of the different models that are available for you to use. Share any with the class that you find interesting.


### Activity 2 - Does RAG Affect your results

[[pics]](pics/activity_2)

We will use the _Local Docs_ feature of GPT4All to create a basic Retrieval Augemented Generation system. Once we do that we'll ask our models the same questions about Spider-Man movies to see if the results are different. 


