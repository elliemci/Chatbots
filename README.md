# Chatbots with Transformers
**Hugging Face** [Transformers API](https://huggingface.co/docs/transformers/index) and tools and [Pipelines API](https://huggingface.co/docs/transformers/v4.40.2/en/main_classes/pipelines#transformers.pipeline) for the use of pretrained transformer models for executing Natural Language Processing tasks such as question answering, text classification, summarization, translation, name entity recognition, which are integrated with Telegram Bots via [pyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI); explore hugging face transformer libry in hugging_face_exploration.ipynb, set up a chatbot in telegram_chatbot.ipynb:

## Question Answering task
#### DistilBERT Transformer
which allows the user to ask questions and receive answers based on piecee of context text in qa.ipynb and inteegrate the QA task into a simple Telegram chatbot that answers questions based on Wikipedia information in qa_chatbot.ipynb

## Intent Classification task
#### BART
"zero-shot classification" of possible user intent with classification_bart.ipynb integrateed in msg_intent_chatbot.ipynb
#### BERT
toxic-bert model for text toxicity classification in toxic_bert.ipynb integrated into a chatbot that receives a message from the user and classifies the message content if being toxic toxicity_classification_chatbot.ipynb

## Summarization
#### T5 
Experiment with summarization NLP tasks using BART, T5 and others models, receiving text and returning a summary of it in summarizee_title.ipynb, summarize_bart.ipynb, summarize_bart_t5.ipynb and their summarization functionality integrated into a telegram chatbot in summarrization_chatbot.ipynb

## Translation
#### BART and RoBERTa
Figure out the user's message language language_classification.ipynb. Translate  between different languages with multilingual BART tranformer model in translate_mbart.ipynb. Translate text and convert the translation to audio in translate.ipynb. A chatbot that recognizes the user's message language and translates it into english in classifytranslate_chatbot.ipynb

## Named Entity Recognition
#### BERT-base-NER
Named-entity recognition tool ner_bert.ipynb to extract entities like location and people from user message in ner_chatbot.ipynb

#### BERT-large-uncased_med-ner
Fine tuned to medical context NER model in meds_ner.ipynb, integrated for medication NER tasks into a chatbot: with chatbot token, NER pipline and method that extract entities from medication texts in med_ner_chatbot.ipynb 
