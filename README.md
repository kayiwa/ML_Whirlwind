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

[Model 1 - Qwen2.5-0.5B-Instruct](https://huggingface.co/Qwen/Qwen2.5-0.5B-Instruct-GGUF) -  A super lightweight model that only clocks in at 450 MB!

[Model 2 
Llama-3.2-1B-Instruct](https://huggingface.co/bartowski/Llama-3.2-1B-Instruct-GGUF/blob/main/Llama-3.2-1B-Instruct-Q5_K_M.gguf) - The smallest version of Meta's Llama model (about 900 MB) that will produce good enough results for our experimenting. 

[Data Set](data/) - A collection of reviews about different Spider Man movies ranking at different scores. (Data orginally from [Kaggle](https://www.kaggle.com/datasets/okancan/spiderman-movies-imdb-reviews)) The data is split up into two files:

- `Spidey_Bad/` - Ten reviews that ranked the movie a 1 out of 10
- `Spider_Good/` - Ten reviews from the dataset that ranked the movie at a perfect 10.


## Agenda


|||
|---|----|
|0930|Welcome & Introductory Discussion<br/>[Intro to AI for GLAM](https://carpentries-incubator.github.io/machine-learning-librarians-archivists/) |
|1000|Multiple Models running locally|
|1045|Adding Data & Retrieval Augmented Generation|
|1115|Concluding Discussion and Wrap-up|

### Actvity 1 - Installing GPT4All

We are using [GPT4All](https://www.nomic.ai/gpt4all) as it is a simple GUI that has all of the generative AI functions put together in an easy to use interface. We will be distributing the model files on USB sticks so that we don't hammer the venue WiFi.

### Activity 2 - Adjusting model parameters

To tweak the individual models we are going to adjust some parameters to see what they do

- System Prompt
- Suggested FollowUp Prompt
- Temperature

### Activity 3 - Two models answering the same thing

We are going to explore asking the same question of two different models to see what difference in results we can get. First we'll try with _Qwen_, then with _LLama_.

### Activity 4 - Does RAG Affect your results


We will use the _Local Docs_ feature of GPT4All to create a basic Retrieval Augemented Generation system. Once we do that we'll ask our models the same questions about Spider-Man movies to see if the results are different. Let's start with the _QWEN 2.5_ model.

Dataset #1 - 10 Reviews of _Spiderman: Into the Spiderverse_ that ranked the movie a 10 out of 10. Save all of these files in a directory called `spidey good_reviews`
[[link]](data/Spidey_Good)

Dataset #2 - 10 Review of _Spiderman: Into the Spiderverse_ that ranked the movie 1 out of 10. Save all of these files in a directory called `spidey_bad_reviews`
[[link]](data/Spidey_Bad)

### Activity 4b - Does RAG Affect your results

Let's try the RAG experiement again, this time with the _Meta Llama_ model


### Actvity 5 - Your Own RAG

Find a few document about something that you know a good deal about. Create a _Local Docs_ of those documents and run your different models against them.

### Activity 6 - Other models

Check out [Hugging Face](https://huggingface.co/) to see all of the different models that are available for you to use. Share any with the class that you find interesting.




