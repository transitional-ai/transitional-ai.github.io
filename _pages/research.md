---
title: "t~ai - Research"
layout: textlay
excerpt: "t~ai - Research"
sitemap: false
permalink: /research/
---

# Research 

## Machine Learning 

We developed a transdisciplinary  program of research encircling methodologies and applications of data science.  The methodologies include  Bayesian deep learning, neuroevolution,  ensemble machine  learning, and data augmentation. The applications include climate extremes, geoscientific models, mineral exploration, medical diagnosis and bioinformatics, and COVID-19 drug re-purposing, infection forecasting, and social media  with language models. Our key strength is in the development of novel deep-learning software frameworks with a focus on uncertainty quantification in decision-making. We pioneered the area of language models for studying ancient religious-philosophical texts.  
 
**Machine learning and deep learning**

We developed novel neural network learning algorithms using neuroevolution with motivations from transfer learning and multi-task learning to a wide range of  problems that include multi-step ahead and dynamic time series prediction (Chandra et al., 2017;  Chandra et al., 2018)  and modular pattern recognition for dynamic environments (Chandra and Cripps, 2018) with the goal of modular deep learning. The challenge has been  problems that have missing information, noise and inconsistencies in the organisation of data and these are major research directions for future studies. In order to address class imbalance problems and limited training data, we used generative adversarial networks (GANs) with machine learning models  for  data augmentation  (Sharma et al., 2022). Our current focus is on extending the  method to  extreme-value forecasting, and also combining  it with Bayesian inference for  uncertainty quantification in predictions via the posterior distribution.

 **Bayesian deep learning**
 
We developed novel algorithms for Bayesian neural networks that feature parallel tempering MCMC and parallel computing in order to address computational challenges   (Chandra et al., 2019}. We later extended this for  deep learning models  that feature millions of parameters that were "believed to be unachievable"  in the MCMC sampling community.  We developed Bayesian autoencoders using MCMC (Chandra et al., 2022) and Bayesian Graph convolutional neural networks  (Chandra et al., 2022). Taking into account the benefits of evolutionary algorithms, we developed a framework that provides a synergy of multi-source transfer learning with Bayesian neural networks using MCMC  (Kapoor et al., 2022).   We plan to enhance the Bayesian deep learning models  with data  augmentation methods for multi-modal data fusion utilising a wide range of data streams. Furthermore, we plan to use a combination of variational inference and MCMC sampling methods to provide uncertainty quantification in the data and the model space.

## Earth and Climate Sciences

**Remote sensing and machine learning**

There is a huge potential for remote  sensing when combined with emerging machine learning and deep learning methods. We demonstrated that the extraction of geological lineaments from   satellite data via  remote sensing and machine learning  can be used for mineral exploration  (Farahbakhsh et al.,2020). In collaboration with the   EarthByte Group, we developed deep learning models for lithological mapping  via remote sensing  (Shirmard et al.,2022), and applied the same technology for the detection of alteration zones for mineral exploration.   Currently, we are using variational autoencoders and remote sensing for the identification of lineaments  with novel clustering methods. We are planning to use geochemical datasets with spatial machine learning and data augmentation methods for prospectively of critical metals in Australia.  Furthermore, we are currently developing  an open-source framework for land-cover mapping in Fiji where we plan not only to publish a paper but to release online digital maps that can help in  environment restoration initiatives. We plan  to extend these methods for space exploration projects with the study of the  surfaces of the Moon and Mars using satellite data. We also plan to apply these methods to environmental protection and conservation problems, such as quantifying damages to reefs after high-category cyclones and   monitoring invasive species (eg. African tulips in Fiji). 

**Machine learning for the GBR**

The Great Barrier Reef (GBR) is the world's largest coral reef system which is vital for a healthy ecosystem in Australia and the Pacific Ocean.  In collaboration with the  Geocoastal Research  Group (University of Sydney), we used remote sensing and clustering methods for  reef community mapping from the One-Tree Island of the  Great Barrier Reef (Barve et al., 2023). Our interest is in the study of the geological development of the GBR going back thousands of years in time. We developed an open-source software framework   for reef modelling (Bayesreef) that provides insights into  coral platform growth and demise through time  (Pall et al, 2020) using the Py-Reef-Core model.  We developed a machine learning framework for processing coral reef drill core data (Deo et al. 2023). Currently, we are using novel deep learning models for the study of organisms on the deep sea floor in collaboration with the University of Sydney and Imperial College London. In future, we are interested to use machine learning and Bayesian inference methods in connectinattention mechanism￼g landscape evolution models with reef evolution models to have a better understanding of the development of the GBR. 

**Climate extremes and environmental problems**

The drastic effect of climate change is visible given extreme weather conditions such as tropical storms and cyclones. We used deep learning models for forecasting cyclone wind intensity and trajectory for South Pacific and South Indian Oceans  (Chandra and Dayal, 2015; Deo and Chandra, 2016; Chandra et al.,2016 ). We also focused on the rapid intensification of cyclones  (Chandra, 2017) and  uncertainty quantification in predictions using Bayesian neural networks  (Deo and Chandra, 2019). We developed  variational deep learning models for cyclone trajectory prediction with uncertainty quantification  (Kapoor et al., 2023). Currently, we are using deep learning  for forecasting cyclone genesis in the coming decades  given drastic changes in the climate via sea surface  temperature data from the general circulation model (GCM) in collaboration with the  Natural Hazards and Climate Risk group, Data 61.  Furthermore, we used novel deep learning models for modelling Australian floods by taking into account precipitation and stream flow which led to an Honours thesis with potential publication. We are also combining hydrological models with deep learning models for modelling stream flow.  We   collaborated with UNSW  Water Research Laboratory where we use deep learning models for groundwater modelling.  Apart from climate extremes, we developed a framework that featured machine learning methods to predict precipitation that defines paleoclimate that spans up to  millions of years in the past (Chandra et al., 2021). The data features a range of geological indicators including sedimentary deposits (coal, evaporates, glacial deposits). We addressed the challenges of missing values in the dataset and   uncertainty quantification   with Bayesian machine learning and  developed paleo-maps of forests and vegetation that span 250 million years.  In future work, we would like to use these maps and connect them with other paleoclimate studies.


**Bayesian geoscientific models**
 
Bayesian inference has been a popular methodology for parameter estimation in geological and geophysical forward models, also known as geoscientific models. In collaboration with the  EarthByte Group (University of Sydney), we developed   Bayesian inference  via MCMC framework for parameter estimation and uncertainty quantification for landscape evolution models (Bayeslands) to demonstrate landscape  evolution in synthetic models that span thousands to million years demonstrating surface evolution based on different climate and environmental conditions   (Chandra et al., 2019, Chandra et al., 2020).    We envision that Bayeslands and Bayesreef will create a significant impact on the research community.  We addressed the computational inefficiency of  MCMC for large-scale problems by combining parallel computing features with a surrogate-assisted estimation of likelihood function that describes the plausibility of a model parameter value, given observed data (Chandra et al., 2020). We plan to  use our MCMC sampling framework for estimating parameters in  hydrological models combined with deep learning models.


## Bioinformatics and Medicine
    
    
**Medical diagnosis and bioinformatics**

In this area,  the focus is on applying novel machine learning and deep learning models for medical diagnosis and  bio-informatics  that includes COVID-19.  In  NHMRC funded project, we  developed  an unsupervised  machine learning framework for  COVID-19  drug re-purposing (Bansal et al., 2023) where the goal was to down-select a small subset of drugs for COVID-19 clinical trials. We also used deep learning for COVID-19  infection forecasting in India (Chandra et al., 2022). Furthermore, we used deep learning models for  respiratory rate prediction using bio-signals  (Kumar et al., 2022). Currently, I am leading projects where we   use deep learning models for skin cancer detection given  imbalanced and limited training data. In future, we plan to use Bayesian deep learning for a wide range of medical diagnoses and health-related datasets where uncertainty quantification in model predictions plays a vital role in decision-making. 

## Economics and Society

**Deep learning for forecasting future economic trends**

We developed  Bayesian neural networks that  feature uncertainty quantification in forecasting  future trends in the stock price of selected markets   (Chandra and He, 2021). This led to a project that used recurrent neural networks for decadal economic forecasting focusing on country-wise  GDP growth  (Wang et al., 2023). Currently,  we are developing  novel deep learning models  for the decadal cost of living outlook and variational deep learning for uncertainty quantification in stock price forecasting. We also used multimodal deep learning that incorporates text and numeral data streams with large language models for credit rating forecasting.  In future, there is scope for multimodal data fusion for forecasting decadal economic trends taking into account, energy utilisation, climate change, migration and estimates of poverty elimination. 

## Media and Religion

**Language models for social media analyses**

In this research direction, we used novel deep learning models to develop language models via social media to understand public behaviours in events such as COVID-19 (Chandra and Krishna, 2021). Currently, I am leading a project that reviews anti-vaccine tweets during COVID-19 with sentiment analysis. I led a related project that used sentiment analysis  to model US 2020 Presidential elections  (Chandra and Saini, 2021). Currently, we are working towards the  analysis of  political leaning (left vs right wing) in popular news media reporting using pre-trained deep learning-based language models. In the future, we plan to evaluate the right and left-wing biases of developed and emerging economies and study how it impacts political and economic development.   We are currently developing models to study the emergence of Hinduphobia in India and around the world during COVID-19 via Twitter using sentiment analysis.  

   
**Artificial intelligence for religion**

There is an immense potential for data science methods and language models   in areas of arts and humanities, particularly philosophy and religion. The  Bhagavad Gita is a sacred Hindu  philosophical text that is one of the most translated texts over the course of history. We used language models to analyse the sentiments uncovered with philosophical issues presented in the Bhagavad Gita and study the difference when comparing prominent translations (from Sanskrit to English)   (Chandra and Kulkarni, 2022). We demonstrated  that  deep learning-based language models  can be used to compare  related texts, i.e. the Bhagavad Gita with  Upanishads via topic modelling   (Chandra and Ranjan, 2022). Currently, we are developing model for  metaphor detection in  the Bhagavad Gita and  Sermon of the Mount of the  Holy Bible. We are also using  sentiment analysis for  the comparison of translations of the Sermon of the Mount. In collaboration with  Midam Charitable Trust in India, we evaluated  Google Translate Sanskrit using Bhagavad Gita translations for comparison  (Shukla et al., 2023). Currently, our focus is on  large language models such as  Chat-GPT for developing  Vedanta-GPT. This model will be trained with Bhagavad Gita and Upanishads that will be released as an online  discussion chat-bot for Hindu philosophy. We are also developing language models for humour detection in Hindu texts, and plan to use related language models for Buddhist texts. In future, we plan to use computer vision methods for the automatic archival of ancient sacred scripts in India in collaboration with the Oxford Centre for Hindu Studies.

**Artificial intelligence for music and cinema**

Use language models and deep learning-based computer vision methods for the analysis of movies, scripts, and songs from the viewpoint of social sciences, economics and psychology. 


 
