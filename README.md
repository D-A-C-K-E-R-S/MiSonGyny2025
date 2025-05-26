# MiSonGyny2025
This repository presents a two-stage classification software for detecting misogynistic content in Spanish song lyrics.

 Misogynistic content in song lyrics has become a growing social concern, particularly in music genres
 where degrading or violent references to women are normalized or even glamorized. InSpanish-speaking
 contexts, this issue is of particular pertinence due to the global reach and influence of certain musical
 styles, which are often consumed extensively by younger demographics. From a societal perspective,
 the normalization of misogyny through music has the potential to reinforce gender stereotypes and
 contribute to broader patterns of symbolic violence and discrimination.
 
 From a computational perspective, the automatic detection of misogynistic speech in lyrics poses
 several challenges. These include the presence of figurative language, slang, irony, and ambiguous
 phrasing, all of which are common in creative domains such as music. Furthermore, there is a notable
 scarcity of annotated datasets focused on song lyrics, especially in the Spanish language, and the
 few available resources tend to be highly imbalanced, which hinders the development of robust and
 generalisable models.
 
 In this study, we propose a two-stage classification pipeline for the detection of misogynistic content in
 Spanish-language song lyrics. In the initial phase, we undertake binary classification to differentiate
 between misogynistic and non-misogynistic content. In the second stage of theanalysis, the misogynistic
 lyrics are further classified into four categories: The following categories are not relevant: violence,
 sexual, and harassment.
 
 In this study, we undertake a thorough evaluation of multiple pre-trained transformer models, namely
 BERT, RoBERTa, and LLaMA, in addition to a classical Vector Space Model (VSM) approach. This
 investigation involves a meticulous fine-tuning and evaluation process, ensuring a comprehensive
 assessment of the models’ capabilities and limitations. Furthermore, we have developed multiple
 ensemble strategies that combine the predictions of individual transformer models to improve robustness.
