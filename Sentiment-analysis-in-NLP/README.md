# Sentiment-analysis-in-NLP
the field of Natural Language Processing (NLP) dealing Sentiment Analysis (SA), also named as opinion mining, is an active research area to display emotions and to automatically discover the sentiments expressed within the text . The object of SA is usually a product or service that is of keen interest among people, that they care to put a sentiment towards it. Traditionally, SA has been considered as opinion polarity that whether someone has expressed positive, negative or neutral sentiment about an event. 

## Aspect-based Sentiment Analysis
From studies, SA has been generally categorized at three levels. Document-level , sentence-level and aspect-level SA  to classify whether a whole document, sentence (subjective or objective) and an aspect expresses a sentiment, i.e., positive, negative or neutral. The Aspect-based Sentiment Analysis (AbSA) helps to understand the problem of SA better comparatively, because it directly focuses on sentiments rather than language structure.

Identification of user’s opinions from natural language text has become an exciting field of research due to its growing applications in the real world. The research field is known as sentiment analysis and classification, where aspect category detection (ACD) and aspect category polarity (ACP) are two important sub-tasks of aspect-based sentiment analysis. The goal in ACD is to specify which aspect of the entity comes up in opinion while ACP aims to specify the polarity of each aspect category from the ACD task.

## Deep Learning
Deep learning models in natural language processing work almost similar to the models developed for image processing, where they try to identify relationships between words, sentences, and paragraphs instead of recognizing patterns from pixels. In this work, we have developed basic deep models including CNN, LSTM, and GRU. The input patterns are first preprocessed via the embedding layer, and then, entered into the deep models to generate the output. The output identifies the aspect and its polarity for each input pattern.

## Transfer Learning models
The transfer learning models used in this study are BERT  and ParsBERT. Both BERT and ParsBERT have been reported as the state-of-the-art approaches in NLP related learning tasks. Both models are essentially based on an encoder–decoder net-work, namely a transforme. parameters of BERT are obtained through the masked language modeling, where the model is trained to predict some masked-out words in given sentences.

ParsBERT is evaluated on three NLP downstream tasks: Sentiment Analysis (SA), Text Classification, and Named Entity Recognition (NER). For this matter and due to insufficient resources, two large datasets for SA and two for text classification were manually composed, which are available for public use and benchmarking. ParsBERT outperformed all other language models, including multilingual BERT and other hybrid deep learning models for all tasks, improving the state-of-the-art performance in Persian language modeling.

## References
[1] Ambreen Nazir, Yuan Rao, Lianwei Wu, Ling Sun, "Issues and Challenges of Aspect-based Sentiment Analysis: A Comprehensive Survey," IEEE Transactions on Affective Computing, 2020. <br>
[2]  V. M; R. Jafar . "Jointly Modeling Aspect and Polarity for Aspect-based Sentiment Analysis in Persian Reviews". arXiv:2109 <br>
[3] J. Tao and X. Fang, “Toward multi-label sentiment analysis: a transfer learning based approach,” Journal of Big Data, vol. 7, 2020 <br>
