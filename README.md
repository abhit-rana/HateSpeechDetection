# HateSpeechDetection

Given a tweet in Hinglish language, determine whether the tweet is offensive/Hateful. It is a binary classification task. The dataset consists of Hinglish tweets used in 2021's HASOC Subtask A. Implemented a Pipeline where the tweets are given as input and then pre‑processed. Generate their feature vector by contamination of # User Ids in Tweet, Profane Vector, Sentiment Vector, and Sentence Embedding generated through Fine‑Tuned Bert Model on a given dataset. Classification using the Support Vector Machine Model learned on extracted feature patterns from tweets.
Model Architecture:
![redefined - Page 2 (2)](https://user-images.githubusercontent.com/88608893/208653975-193542c8-1a80-4c9b-b019-fd0acce146ed.png)


More detailed information about the project(Related work, Methodology, Experimental Results) can be found in the [Report](https://github.com/abhit-rana/HateSpeechDetection/blob/main/ProjectReport.pdf) and [Slides](https://github.com/abhit-rana/HateSpeechDetection/blob/main/Project_Slides.pdf).
