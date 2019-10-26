# Vaultedge-NLP-Hackathon
### This repository contains code for Named Entity Recognizer made using CRF,for Vaultedge NLP Hackathon 2019.
### We were placed 2nd in the hackathon. Our final F1 Score was 0.6.

<p align="center">
<img width="299" height="451" src="https://github.com/Sreyan88/Vaultedge-NLP-Hackathon/blob/master/Extra/Vaultedge.jpg">
</p></br>


Initially we tried a sequence-to-sequence deep learning model based in LSTM, GRU and word embeddings. However we lagged behind in the leaderboard even after repetitively fine tuning our model. We eventually moved to multinomial naive bayes and finally CRF which gave us the best results.   
### Steps to be followed:
1. Pre-process the text using porting, stemming, cleaning spellings, expanding contractions etc.(This did not help in our case and thus this part is not included in the code.)
2. Convert individual words to complete sentences.
3. Train and test the model and tune hyper-parameters.

