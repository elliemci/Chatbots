# Chatbots with Transformers
**Hugging Face** [Transformers API](https://huggingface.co/docs/transformers/index) and and [Pipelines API](https://huggingface.co/docs/transformers/v4.40.2/en/main_classes/pipelines#transformers.pipeline) are used for the impleementation of pretrained transformer models for execution of Natural Language Processing tasks such as question answering, text classification, summarization, translation, name entity recognition, which are integrated with Telegram Bots via [pyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI); explore hugging face transformer libry in hugging_face_exploration.ipynb, set up a chatbot in telegram_chatbot.ipynb:

## Question Answering task
#### DistilBERT Transformer
which allows the user to ask questions and receive answers based on piecee of context text in qa.ipynb and inteegrate the QA task into a simple Telegram chatbot that answers questions based on Wikipedia information in qa_chatbot.ipynb

## Intent Classification task
#### BART Transformer
"zero-shot classification" of possible user intent with [classification_bart.ipynb](https://github.com/elliemci/chatbots/blob/main/classification_bart.ipynb) integrateed in [msg_intent_chatbot.ipynb](https://github.com/elliemci/chatbots/blob/main/msg_intent_chatbot.ipynb)
#### BERT Transformer
toxic-bert model for text toxicity classification in [toxic_bert.ipynb](https://github.com/elliemci/chatbots/blob/main/toxic_bert.ipynb) integrated into a chatbot that receives a message from the user and classifies the message content if being toxic [toxicity_classification_chatbot.ipynb](https://github.com/elliemci/chatbots/blob/main/toxicity_classification_chatbot.ipynb)

## Summarization
#### T5 Transformer
Experiment with summarization NLP tasks using BART, T5 and others models, receiving text and returning a summary of it in [summarize_title.ipynb](https://github.com/elliemci/chatbots/blob/main/sumarize_title.ipynb), [summarize_bart.ipynb](https://github.com/elliemci/chatbots/blob/main/summarize_bart), [summarize_bart_t5.ipynb](https://github.com/elliemci/chatbots/blob/main/summarize_bart_t5.ipynb) with their functionality integrated into a telegram chatbot in [summarization_chatbot.ipynb](https://github.com/elliemci/chatbots/blob/main/summarization_chatbot.ipynb)

## Translation
#### BART and RoBERTa Transformers
Figure out the user's message language in [language_classification.ipynb](https://github.com/elliemci/chatbots/blob/main/language_classification.ipynb). Translate  between different languages with multilingual BART tranformer model in [translate_mbart.ipynb](https://github.com/elliemci/chatbots/blob/main/translate_mbart.ipynb). Translate text and convert the translation to audio in [translate.ipynb](https://github.com/elliemci/chatbots/blob/main/translate.ipynb). A chatbot that recognizes the user's message language and translates it into english in [classifytranslate_chatbot.ipynb](https://github.com/elliemci/chatbots/blob/main/classifytranslate_chatbot.ipynb)

## Named Entity Recognition
#### BERT-base-NER Transformer
Named-entity recognition tool [ner_bert.ipynb](https://github.com/elliemci/chatbots/blob/main/ner_bert.ipynb) which extracts entities like location and people from user message, inteeegrated in [ner_chatbot.ipynb](https://github.com/elliemci/chatbots/blob/main/ner_chatbot.ipynb)

#### BERT-large-uncased_med-ner Transformer
Fine tuned to medical context NER model which rreecognizes  medical entities in text such as medication name, dossage, frequency and duration in [meds_ner.ipynb](https://github.com/elliemci/chatbots/blob/main/meds_ner.ipynb), integrated for medication NER tasks into a chatbot: with chatbot token, NER pipline and method that extract entities from medication texts in [med_ner_chatbot.ipynb](https://github.com/elliemci/chatbots/blob/main/med_ner_chatbot.ipynb) 
