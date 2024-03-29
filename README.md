# Chatbot for Information Retriveal
This chatbox is part of a course-project "https://www.coursera.org/learn/language-processing". All data is provided by course and this can only be used for learning Purpose. 

# Requirements

-Python 3.5

-mathparse>=0.1,<0.2

-nltk>=3.2,<4.0

-pint>=0.8.1

-python-dateutil>=2.7,<2.8

-pyyaml>=5.1,<5.2

-spacy>=2.1,<2.2

-sqlalchemy>=1.3,<1.4

-pytz

-chatterbot>=1.0,<1.1

-nose

-pip

-sphinx>=1.8,<1.9

-Flask>=1.0.0

-chatterbot-corpus>=1.2.0

-SQLAlchemy>=1.2

-Sklearn

-requests

# Data
Preprocessing notebook file can be run using Google Colab/ Jupyter to creater model files necessary for starting a bot. Those files are already uploaded in  a drive here https://drive.google.com/file/d/1QRSDBeXSzJrYPRrGdcxJQJtGOLuACR_w/view?usp=sharing. Some other major embeddings and stackOverflow tagged posts are available in Data folder. You can train your own embeddings as well and place the path in Preprocessing notebook to create the relevant files before booting up the bot.

Files necessary for preprocessing

- word_embeddings.tsv 

- tagged_posts.tsv

- dialogues.tsv

Files Generated by Notebook

-intent_recognizer.pkl 

-tag_classifier.pkl 

-tfidf_vectorizer.pkl 

-thread_embeddings_by_tags


# Developing a bot

Make an account on Telegram and type @BotFather to create a bot. Type "/newbot" , you will be asked for a new and when it is done. You will be provided with a Token. `Token` is ID of your bot to run it. Store it safely.

You can later write @yourchosename and start using it once running is finalize.


# Running

You can run bot on you local machine. It will be up and running till your PC is on. You can also deploy it online on any cloud service like AmazonWebServices, Azure, or Google Cloub. Remeber you will need atleast 2 GB RAM to unfold and run data

On Windows python main.py --token=TOKEN_OBTAINED

On Linux python3 main.py --token=TOKEN_OBTAINED

# Ready.

You can try to ask programming related issues, It will parse relevant answers from stackOverflow DataBase. 
 

