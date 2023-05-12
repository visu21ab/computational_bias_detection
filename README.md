# computational_bias_detection
Master Thesis Project 

**Description**
<br>
<br>
The rapid increase of refugees around the world is one of the prominent global issues of the 21st century. It has gained widespread coverage in the news media, and significantly influenced the public's perception about refugees. The feasibility to explore news media is increasing with developments within natural language processing and computational analysis. 

To gain insights into this issue, this study proposes a framework for detecting bias in English written news media. This is executed through investigating a collection of news media articles covering Syrian refugees and Ukrainian refugees, respectively. A comparative computational analysis is conducted through exploring bias by word choice and labeling with the applied methods of frame identification, semantic similarities and aspect based sentiment analysis on full article content. _The research question that this thesis strives to answer is;  How can bias in news media be detected through computational methods?_ The general frames identified for the full dataset were Displacement, Humanitarian, Political and Violence and serves as a contextual segmentation for the further analysis. The findings confirms an indication of bias favoring Ukrainian refugees above Syrian refugees based on the data and is most apparent within the Displacement frame. However, a detected underlying bias in the pre-trained language model for sentiment analysis explains part of this study’s identified bias. This motivates further research to use language models that have been fine-tuned on the specific subject data and remain critical to pre-trained language models. The study emphasizes the usefulness of the framework for primarily humanitarian help organizations to use as a tool in monitoring media bias. By doing so, this study seeks to contribute to the development of more objective, efficient, and scalable methods within the field of bias detection.

**Results from Frame Identification**
<img width="805" alt="Skärmavbild 2023-05-12 kl  11 17 09" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/f8c635ac-f20a-4d6c-b0c2-e072e9fd8924">

The resulting frames from the frame identification code on the merged dataset is Humanitarian, Displacement, Violence and Political. The number four has been chosen since the it was considered an optimal number to have the framed seperated and not overlapping yet distinct. This variable can be modified to present more granular frames is that is relevant for the case.   

**Results of Semantic Similarity and Word Vectors**

*Displacement*
<br>
<img width="805" alt="Skärmavbild 2023-05-12 kl  11 15 52" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/6bc13b6c-1f5d-4bde-98d5-0b4dfc93898f">
<img width="750" alt="Skärmavbild 2023-05-12 kl  11 18 13" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/4e55126d-8b47-454c-9929-e98491387af2">

*Humanitarian*
<br>
<img width="805" alt="Skärmavbild 2023-05-12 kl  11 22 32" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/4104b4be-9452-4ff1-8864-4ff36a7b624b">
<img width="750" alt="Skärmavbild 2023-05-12 kl  11 22 54" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/dc7165b7-8557-4199-ab77-dc07b2d11572">

*Violence*
<br>
<img width="805" alt="Skärmavbild 2023-05-12 kl  11 28 51" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/1ccf57fb-19dc-4ee6-82b0-9fed2c3ea247">
<img width="750" alt="Skärmavbild 2023-05-12 kl  11 29 04" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/e18048fc-a983-440f-820a-6e0fd7172b2a">

*Political*
<br>
<img width="805" alt="Skärmavbild 2023-05-12 kl  11 30 02" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/7b6a2d4e-99ed-427a-a68c-6070da85c712">
<img width="750" alt="Skärmavbild 2023-05-12 kl  11 30 18" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/ca56214d-ea3c-44b8-962d-de5d94b5f0d4">
<br>
<br>
**Reccomendations**

The case study indicates that an underlying bias can be detected in a set of articles which has its origin in modern news media. We want to highlight the usage of NLP methods in computational bias detection and the feasibility of such methods to monitor the media debate. Additionally the result motivates a further investigation of the refugee debate concerning Ukrainian and Syrian refugees based on the detected bias. By studying the articles’ choice of words and sentiment in different contexts, different levels of bias can be detected. 

But, a discovered limitation in the research outcome was that the used pre-trained polarity scoring model Flair contains some prior bias which have affected our results. Therefore, we propose a future research of not using a pre-trained model and fine-tuning it instead with the used dataset to avoid any influences of prior biases towards certain entities. 

