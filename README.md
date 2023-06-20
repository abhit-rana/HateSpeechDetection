# HateSpeechDetection

Given a tweet in Hinglish language, determine whether the tweet is offensive/Hateful. It is a binary classification task. The dataset consists of Hinglish tweets used in 2021's HASOC Subtask A.

Model Architecture:
![redefined - Page 2 (2)](https://user-images.githubusercontent.com/88608893/208653975-193542c8-1a80-4c9b-b019-fd0acce146ed.png)


Best Experimental Results with:

Language Translation: googletrans.Translate

Word Embeddings:

Transformer Model: bert-base-nli-mean-tokens

Pooling Layer and Dense Layer added after Transformer Model

ML Model: SVM

More detailed information about project(Related work, Methodology, Experimental Results) could be found in the Report.
