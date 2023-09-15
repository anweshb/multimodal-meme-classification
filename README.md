![image](https://github.com/anweshb/multimodal-meme-classification/assets/96538649/4717a893-44dd-41c4-8cfb-9cdc868ffbf0)![image](https://github.com/anweshb/multimodal-meme-classification/assets/96538649/0f31c402-56e9-419c-adfb-813ede729c2f)
# Multimodal Sentiment Analysis

## Table of Contents
*	Introduction
* Motive	
*	Project Overview
*	Model Architecture
*	Late Fusion
*	Contributing

## Introduction
This repository contains code and resources for performing sentiment analysis on memes, which are often rich in both textual and visual content. By leveraging neural networks and late fusion techniques, we combine the information from these modalities to predict the sentiment expressed in memes.

## Motive
The rapid proliferation of memes across the digital landscape has ignited a profound need for advanced content moderation techniques. As the internet's lingua franca evolves, so do the forms of expression, including humor, satire, and sometimes, offensive or harmful content. 
It is in this ever-evolving landscape that multimodal sentiment analysis, employing late fusion techniques, has emerged as a formidable tool in content moderation.
Memes are more than just humorous images or captions; they encapsulate societal trends, viewpoints, and the zeitgeist. They provide a channel for individuals to comment on various subjects, events, or social issues in a succinct and often humorous manner. 
However, with the freedom of expression that memes afford comes the potential for misuse, ranging from hate speech to the dissemination of misinformation.
As memes have become a prominent medium of expression, online platforms and social media networks grapple with the challenges of content moderation. Traditional keyword-based approaches to content moderation often fall short in understanding the nuanced nature of memes. 
This is where multimodal sentiment analysis steps in, offering a nuanced and context-aware approach to assess the sentiment expressed within memes.

![image](https://github.com/anweshb/multimodal-meme-classification/assets/96538649/d8da41ea-7f91-431e-9563-4a55bad08e9c)


## Project Overview
Sentiment analysis is a crucial aspect of understanding how people perceive and respond to content, including memes. Memes often include a combination of text and images, making them challenging but also highly informative for sentiment analysis. This project aims to:
*	Collect and preprocess a dataset of memes with sentiment labels.
*	Develop a multimodal deep learning architecture that can analyze both textual and visual features of memes.
*	Implement late fusion techniques to combine the predictions from individual modalities (text and image).
*	Evaluate the model's performance.


## Model Architecture
Multimodal machine learning is a subfield of artificial intelligence and machine learning that focuses on developing algorithms and models capable of processing and understanding data from multiple modalities or sources.
It has the potential to significantly enhance the capabilities of AI systems by enabling them to understand and interpret the world in a more holistic and human-like manner.
In this context, a modality refers to a distinct type of data source or information channel, such as text, images, audio, video, sensor data, or any other form of structured or unstructured data.

Our multimodal sentiment analysis model consists of two main components: a visual attention branch and a semantic attention branch. These branches are combined using late fusion techniques to make a final sentiment prediction.
![image](https://github.com/anweshb/multimodal-meme-classification/assets/96538649/a5f20381-3395-44a8-b3ff-a0f422702e16)

The Semantic processes textual data using Convolutional Neural Networks with Bidirectional LSTM layers and an Attention layer.
![image](https://github.com/anweshb/multimodal-meme-classification/assets/96538649/72cd569f-5c0f-48c9-ad60-b52ae893417d)

The image analysis branch uses a Convolutional Neural Networks and an Attention layer to extract features from meme images.
![image](https://github.com/anweshb/multimodal-meme-classification/assets/96538649/9363298b-e010-4012-b66f-f498e19cd442)

## Late Fusion
Late fusion is a technique used in multimodal machine learning to combine information from multiple sources or modalities at a later stage of processing, typically after individual models or modules have generated their own predictions or representations. 
It offers several advantages in scenarios where multiple modalities (such as text, images, audio, etc.). In this case, late fusion allows the system to separately analyze the textual and visual aspects of memes, capture sentiment-related information from each modality, and then fuse this information to make a more informed and accurate sentiment prediction. 
It leverages the strengths of both text and image analysis while accommodating their differences. This approach often results in more robust and context-aware sentiment analysis, making it particularly valuable in understanding the nuanced sentiment expressed in memes.

## Contributing
We welcome contributions to this project. Feel free to open issues, suggest improvements, or submit pull requests.

## References
Dataset: https://www.kaggle.com/datasets/victorcallejasf/multimodal-hate-speech
Paper: https://www.sciencedirect.com/science/article/abs/pii/S095070511930019X?via%3Dihub
