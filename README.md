# Warhammer 40k Adaptive RAG 
*(Based on the 10th Edition)*

<img src="images\wp10050146-warhammer-40000-mechanicus-wallpapers.jpg" alt="Alt text" style="width:100%;"/>



Warhammer including its 40 years worth of lore is a very large IP that can be overwhelming for newcomers to get into due to the sheer size of its universe. Its TableTop game has an especially big learning curve, given that there are thousands of pages of rules and guidebooks, with dozens of factions each with their specific niches. This project aims to make the learning curve more manageable by offering a chatbot capable of answering questions regarding the game. Secondary aim of this project is to help the veteran players to get answers without having to scour the documents or alternatively scour the web. 


## Technical Overview
The project contains two main parts:

1) Pre-Processing-1.ipynb -> contains code for pre-processing complex .pdf documents into easy to work with markdown files. All of the .pdf files used can be found on GamesWorkshop official page, here: [Rules Downloads](https://www.warhammer-community.com/warhammer-40000-downloads/)

<p align="center">
    <img src="images\graph_1.png" alt="RAG Graph" style="width:48%;"/>
</p>

2) Warhammer-Tabletop-RAG-2.ipynb -> contains the code implementing state graph for answering queries, including both web search and vectorstore retrieval. The code is based on this paper: [paper](https://arxiv.org/abs/2403.14403)

<p align="center">
    <img src="images\graph_2.png" alt="RAG Graph" style="width:48%;"/>
</p>


## The results

Here are some examples of the system answering questions: 

<div style="display: flex; justify-content: space-between; margin: 0 5%;">
    <img src="images\Question_1.png" alt="Alt text" style="width:48%;"/>
    <img src="images\Question_2.png" alt="Alt text" style="width:48%;"/>
</div>