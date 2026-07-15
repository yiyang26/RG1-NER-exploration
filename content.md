#From XML to Name Entities

## Subtitile

Exploring Name Entity Recognition in Repertorium Germanicum I

## Introduction

What is Repertorium Germanicum I, what do I want to do with it

## Research Questions

## The XML Dataset

## Corpus Exploration

Basic descriptive data and data exploration

## NER Experiments

What entities I choose to compare and why

## Model Performance

## Error Analysis

## Conclusion and Limitations


Project Spec

1. The interest 
    I'm curious about how the historical data was modelled into this database. And also if the existing NER tools can identify named entities, especially the mixture of Latin and German entities, historical spelling.

2. The answerable question
    Which model would perfom the best and what kinds of named entities will cause most errors 

3. Hypothesis: what do you expect and why
    I expect the multilingual model will have the best performance, because the texts were maily written in Latin but contain a lot of German cities and names. 

4. Dataset: What data, from where, and how much
    https://rg-online.dhi-roma.it/denqRG/index.htm

5. Method
    Parse XML, extract and clean the text, try different NER tools, and compare their results 

6. The result: What will show it
    The result will be a clear comparison between different NER tools and also some manual inspection about which entity tpyes and which features are causing systematic errors

7. One real limitation: what could undercut it
    Mixed language. I don't think any of the NER tools were pre-trained on this kind of text. So I expect none of the NER tools will have good results. Maybe from this project, I can choose the best one for future fine-tuning. But then the question is, is it really worth it to train a model? Or maybe doing this manually is better. 

