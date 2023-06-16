# Emotion Prediction Indonesian English
This project is made for our application, named RAHAYOO, an application to monitor employee mental health by chating with our chatbot and emotion analysis report, which is we will use this model to predict the emotion.

Here we will make emotion prediction with Bidirectional LSTM model using glove pretrained embedding based on tweet dataset to classify 5 emotion which is : Anger, Fear, Sad, Happy, Love.

we Sucessful build two model to each language, Indonesia and English. The architecture of the two is the same as we can see in image below the different is the pretrained embedding.

![Arsitektur Model Bahasa Inggris](https://github.com/rahayoo-bangkit-capstone-2023/emotion-prediction/assets/73153475/07ed4f81-67d3-4b49-b574-b4e789e7ac7c)

We use pretrained glove embedding as listed below : 
1. English Pretrained Embedding Glove 6B 200d (https://nlp.stanford.edu/projects/glove/)
2. Indonesian Pretrained Embedding Glove 50d trained on wikipedia indonesia ( https://drive.google.com/file/d/1jgnvIEp8rE3dh68lZXBHfyxzmeky9z6w/view?usp=sharing)

The dataset we use on this model can be downloaded also in here : 
1. Emotions Dataset for NLP (English) : https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp
2. Indonesian Twitter Emotion Dataset : https://github.com/meisaputri21/Indonesian-Twitter-Emotion-Dataset/blob/master/Twitter_Emotion_Dataset.csv
3. Emotion Dataset from Indonesian Public Opinion : https://github.com/Ricco48/Emotion-Dataset-from-Indonesian-Public-Opinion 


Thank you.
