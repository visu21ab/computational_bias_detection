# Computational Bias Detection in News Media 
Master Thesis Project 

**Description**
<br>
<br>
The rapid increase of refugees around the world is one of the prominent global issues of the 21st century. It has gained widespread coverage in the news media, and significantly influenced the public's perception about refugees. The feasibility to explore news media is increasing with developments within natural language processing and computational analysis. 

To gain insights into this issue, this study proposes a framework for detecting bias in English written news media. This is executed through investigating a collection of news media articles covering Syrian refugees and Ukrainian refugees, respectively. A comparative computational analysis is conducted through exploring bias by word choice and labeling with the applied methods of frame identification, semantic similarities and aspect based sentiment analysis on full article content. _The research question that this thesis strives to answer is;  How can bias in news media be detected through computational methods?_ The general frames identified for the full dataset were Displacement, Humanitarian, Political and Violence and serves as a contextual segmentation for the further analysis. The findings confirms an indication of bias favoring Ukrainian refugees above Syrian refugees based on the data and is most apparent within the Displacement frame. However, a detected underlying bias in the pre-trained language model for sentiment analysis explains part of this study’s identified bias. This motivates further research to use language models that have been fine-tuned on the specific subject data and remain critical to pre-trained language models. The study emphasizes the usefulness of the framework for primarily humanitarian help organizations to use as a tool in monitoring media bias. By doing so, this study seeks to contribute to the development of more objective, efficient, and scalable methods within the field of bias detection.

**Computational Method Overview**
<br>
<img width="754" alt="overview" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/8714ce4e-37e0-4e31-a36c-f05a9d573a78">


<br><br>**Results from Frame Identification**
![heatmap_syrien](https://github.com/visu21ab/computational_bias_detection/assets/91184444/180de24f-60be-4b52-a97c-769abef94116)


The resulting frames from the frame identification code on the merged dataset is Humanitarian, Displacement, Violence and Political. The number four has been chosen since the it was considered an optimal number to have the framed seperated and not overlapping yet distinct. This variable can be modified to present more granular frames is that is relevant for the case.   

<br><br>**Results of Semantic Similarity and Word Vectors**

*Displacement*
<br>
<img width="805" alt="Displacement" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/fcb11c52-41d1-4860-acc5-e36b5949432c">
<img width="805" alt="Displacement pol" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/9504e3f8-6c1b-43ed-98be-15fb1fd15a63">

<br>*Humanitarian*
<br>
<img width="805" alt="hum" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/33572bac-5c95-4a4f-93fd-d281c6691f90">
<img width="805" alt="hum pol" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/5c530785-76ca-43f3-8945-e8570bdc87bd">

<br>*Violence*
<br>
<img width="805" alt="viol" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/a708365a-9f8d-4434-bced-4267fc9c897a">
<img width="805" alt="viol pol" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/0a1b4209-ba4a-46ad-b89e-4467a6c7481f">

<br>*Political*
<br>
<img width="825" alt="pol" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/2dd078d3-ead7-4930-ade7-538f0185e6b0">
<img width="805" alt="pol pol" src="https://github.com/visu21ab/computational_bias_detection/assets/91184444/8653de7c-26a3-451d-b759-14c6e622af0f">

<br>
<br>

**Reccomendations**

The case study indicates that an underlying bias can be detected in a set of articles which has its origin in modern news media. We want to highlight the usage of NLP methods in computational bias detection and the feasibility of such methods to monitor the media debate. Additionally the result motivates a further investigation of the refugee debate concerning Ukrainian and Syrian refugees based on the detected bias. By studying the articles’ choice of words and sentiment in different contexts, different levels of bias can be detected. 

But, a discovered limitation in the research outcome was that the used pre-trained polarity scoring model Flair contains some prior bias which have affected our results. Therefore, we propose a future research of not using a pre-trained model and fine-tuning it instead with the used dataset to avoid any influences of prior biases towards certain entities. 

