# Generated-Question-Answer Suitability Report

## Introduction

This report aims to evaluate how suitable questions generated by the "ozcangundes/mt5-multitask-qa-qg-turkish" question-answer generator model are when compared to questions obtained from existing sources. The evaluation is based on BLEU scores, which are an automated translation evaluation measure, with higher scores indicating better alignment.

## BLEU Score Calculation

BLEU scores were calculated based on matched question-answer pairs. BLEU scores range between [0, 1], with higher scores indicating better alignment.

## Special Note and Example

When there is only a single punctuation difference between our question and the question produced by the model 'ozcangundes/mt5-multitask-qa-qg-turkish', for example, 'Mısır meselesi böylece devletlerarası gündeme neyi çıkarmış oluyordu ?' and 'Mısır meselesi böylece devletlerarası gündeme neyi çıkarmış oluyordu?' The questions give the same answer, but since there is no space between the last word and the question mark in the model's question, the score may drop to 0.74.

## Results

The questions generated by the "ozcangundes/mt5-multitask-qa-qg-turkish" model have been categorized based on BLEU scores as follows:

### Category 1: Score < 0.1 (14.5%)

Questions in this category exhibit very low alignment with answers obtained from sources. They are often illogical and may deviate significantly from the context of the original query. However, there are also some consistent questions, although they are in the minority.

### Category 2: 0.1 ≤ Score < 0.3 (20.9%)

Questions in this category demonstrate alignment with answers obtained from sources, but they may have various issues. Some of them could be incorrect or illogical.

### Category 3: Score ≥ 0.3 (64.4%)

Questions in this category exhibit a high alignment with answers obtained from sources, indicating that the "ozcangundes/mt5-multitask-qa-qg-turkish" model successfully generates similar questions.

Please note that the percentages represent the distribution of questions across these categories.
