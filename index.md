---
permalink: /
layout: single
classes: wide
author_profile: true
title: ""
excerpt: "ArashSaeidpour.github.io"
header:
  image: /assets/images/header_image.jpg
  #overlay_image: /assets/images/header_image.jpg


analytics:
  provider: "google-gtag"
  google:
    tracking_id: "UA-155267220-1"
    anonymize_ip: false # default
#toc: true



#last_modified_at:
#toc: true
---

## About

<sub> Hello World! I am a postdoc at the University of Georgia's [Center for the Ecology of Infectious Diseases](http://ceid.uga.edu/) working under supervision of [Professor Pejman Rohani](http://rohanilab.ecology.uga.edu/). My research is focused on application of  machine learning  and deep learning for  the detection of human-induced and natural catastrophes and disasters prevention and response. Currently I use a combination of mathematical models and machine-learning algorithms for forecasting reemergence of infectious diseases prior to large scale outbreaks. I got my PhD in Engineering from University of Georgia's College of Engineering in 2017. During my PhD, I became interested in machine learning and began to study it intensively on my own. <sub>



## Select Projects

### Hierarchical Clustering of Odum School of Ecology Faculty based on their publications [[IPython Notebook][102]]<br>

![image-left](/assets/images/dendogram.png){:height="30%" width="30%" : style="float: left; margin-left: auto; margin-right: auto"} <sub> This is part 1 of the project that I did to help strategic planing committee of the Odum School of Ecology develop long-term and short-term hiring plans based on department's current research strengths and future aspirations. I was tasked to cluster department's faculty based on their publications. In this notebook, I have described how I used Ward's method for hierarchical clustering of faculty by their publications. <sub> <br> <br> <br>


<sub> Tags: NLP, Python, Unsupervised Learning, TF-IDF, Ward's method, Dendrogram <sub>

[101]:  /assets/images/dendogram.png
[102]:  https://github.com/ArashSaeidpour/Hierarchical-Clustering-of-Odum-School-of-Ecology-Faculty-based-on-their-publications/blob/master/Hierarchical%20clustering.ipynb
  "IPython notebook"



### Implementation of Skip-gram Word2vec on Stanford Sentiment Treebank (SST) dataset [[IPython Notebook] [2]]

![image-right][1]{:height="20%" width="20%" : style="float: right" } <sub> Skip-gram is an efficient method for learning high-quality vector representations of words from large amounts of unstructured text data introduced by Google researchers [[1][301],[2][302]]. In this notebook, I have described my implementation of Skip-gram model via "Negative Sampling". Scaffolding of the code is taken from [Stanford's CS224n course][303] materials. <sub> <br>


<sub> Tags: NLP, Python, Word embedding, Skip-gram, Word2vec, Negative Sampling <sub>

[1]:  /assets/images/bag_of_words.jpg
[2]:  https://github.com/ArashSaeidpour/word2vec/blob/master/Implementation%20of%20word2vec.ipynb
 "IPython notebook"

 [301]: https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf
 [302]: https://arxiv.org/abs/1301.3781
 [303]: https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1194/



### Odum School of Ecology Coauthorship Graph [[IPython Notebook][104]]

![image-left][103]{:height="38%" width="38%" : style="float: left; margin: 0 auto; display: block" } <sub> This is part 2 of the project that I did to help strategic planing committee of the Odum School of Ecology develop long-term and short-term hiring plans based on department's current research strengths and future aspirations. I was tasked to cluster department's faculty based on their publications. In [part I][102] of this project I did hierarchical analysis to group faculty into distinct clusters representing their sub-field of research. In this notebook, I will be describing how I made a "Coauthorship graph" to demonstrate research collaboration among faculty of the department. <sub> <br> <br> <br>

<sub> Tags: NLP, Python, Unsupervised Learning, TF-IDF, Network analysis, PCA, Multidimensional Scaling  <sub>


[103]:  /assets/images/coauthorship_graph.png
[104]:  https://github.com/ArashSaeidpour/Hierarchical-Clustering-of-Odum-School-of-Ecology-Faculty-based-on-their-publications/blob/master/Coauthorship%20graph.ipynb
 "IPython notebook"



### Neural-network based dependency parser [[IPython Notebook][4]]

 <sub> In this notebook I will describe my implementation of a neural-network based dependency parser via arc-standard system for transitions in PyTorch. A dependency parser examines the grammatical structure of a sentence, finding relationships between head words, and words which modify those heads. Scaffolding of the code is taken from [Stanford's CS224n course][303] materials.<sub>

![homepage][3]{:height="80%" width="80%" style="display: block; margin: 0 auto" }

[3]:  /assets/images/nn_parser.png
[4]:  https://github.com/ArashSaeidpour/NN-based-dependency-parser/blob/master/NN-dependency%20parser.ipynb
"IPython notebook"

<sub> Tags: NLP, Python, Dependency parsing, Arc-standard, PyTorch <sub>


### Attention-based neural machine translation [[IPython Notebook][6]]

<sub> In this notebook I have presented my implementation of a Attention-based LSTM model for translation from spanish to english in PyTorch. Scaffolding of the code is taken from [Stanford's CS224n course][303] materials.  <sub>

![homepage][5]{:height="50%" width="50%" style="display: block; margin: 0 auto" }

[5]:  /assets/images/attention.png
[6]:  https://github.com/ArashSaeidpour/Attention-based-NMT/blob/master/Attention-based%20NMT.ipynb "IPython notebook"

<sub> Tags: NLP, Python, NMT, Attention, LSTM, PyTorch <sub>

### [Sub-word modeling and convolutional networks][[IPython Notebook][8]]

<sub> In this notebook I have described my implementation of a hybrid NMT system which takes advantage of both word-level and character-level embeddings. The advantage of this model to regular word-embedding based models is that whenever the word-level decoder fails to produce a token, we run our character-based decoder to generate the target word character by character. Scaffolding of the code is taken from [Stanford's CS224n course][303] materials.<sub>



![homepage][7]{:height="70%" width="70%" style="display: block; margin: 0 auto" }

<sub> Tags: NLP, Python, NMT, CNN, Character-based embedding, PyTorch <sub>

[7]:  /assets/images/character_cnn.png
[8]:  https://github.com/ArashSaeidpour/Sub-word-modeling-and-convolutional-networks/blob/master/Sub-word%20modeling%20and%20convolutional%20networks.ipynb
 "IPython notebook"


## Publications
#### [Parameterized fragility assessment of bridges subjected to hurricane events using metamodels and multiple environmental parameters][9]
<sub> Arash Saeidpour, Mi Geum Chorzepa, Jason Christian, Stephan Durham <br>
*Journal of Infrastructure Systems, 24(4), 2018* <sub>

#### [Probabilistic hurricane risk analysis of coastal bridges incorporating extreme wave statistics][10]
<sub> Arash Saeidpour, Mi Geum Chorzepa, Jason Christian, Stephan Durham <br>
*Engineering Structures, 182, 2019* <sub>

#### [Hurricane Vulnerability Of Coastal Bridges Using Multiple Environmental Parameters][11]
<sub> Arash Saeidpour, Mi Geum Chorzepa, Jason Christian, Stephan Durham <br>
*Proc. 10th International Conference on Risk Analysis and Hazard Mitigation, Crete, Greece.* <sub>

#### [The shear buckling and postbuckling behavior of laterally pressured curved panels][12]
<sub> MM Alinia, Arash Saeidpour, Mojdeh Amani <br>
*engrXiv, 2019* <sub>

#### [Comparison of Postbuckling Prediction Approaches in Curved Panels][13]
<sub> Arash Saeidpour, Mojdeh Amani, MM Alinia <br>
*Proc. IABSE-IASS 2011 Symposium, London, UK* <sub>

#### [Fragility analysis of coastal bridges susceptible to hurricanes incorporating uncertainties in extreme wave parameters by means of wave spectra and enhancement of vulnerability assessment methodologies][14]
<sub> Arash Saeidpour <br>
*PhD diss., University of Georgia, 2017* <sub>


## Presentations

<sub> - Poster Presentation (2019): "The return’s anatomy: dissection of pertussis resurgence in London", *EEID 2019*, Princeton University, Princeton, New Jersey. \[[Poster](https://docs.google.com/presentation/d/1zfcVHL_W03fepaAiSvXAb_FlHj55GxsHradAE83utzQ/edit?usp=sharing)\]<sub>


<sub> - Oral Presentation (2018): "Leveraging census data to unlock insights from changing dynamics of pertussis in London ", *Joint MIDAS CDC meeting*, Emory University, Atlanta, Georgia. <sub>


<sub> - Oral Presentation (2016): "Multi-Hazard Resilient and Sustainable (or MRS) Bridges – Stronger, Taller, Wider,Smarter? ", *EMI/PMC 2016*, Vanderbilt University, Nashville, Tennessee. <sub>

<sub> - Poster Presentation (2016): "Fragility metamodels for vulnerability assessment of coastal bridges under hurricane hazard", *GDOT/GTI 4th Annual Transportation Research Expo*, Atlanta, Georgia. <sub>

<sub> - Poster Presentation (2015): "Hurricane Risk Assessment for Georgia Coastal Bridges ", *GDOT/GTI 3rd Annual Transportation Research Expo*, Atlanta, Georgia. <sub>

## MOOCS/Certificates

<sub> -  Machine Learning by Stanford University on Coursera \[[Certificate][201]\]

<sub> -  Neural Networks and Deep Learning by deeplearning.ai on Coursera \[[Certificate][202]\] <sub>

<sub> -  Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization by deeplearning.ai on Coursera \[[Certificate][203]\] <sub>

<sub> -  Structuring Machine Learning Projects by deeplearning.ai on Coursera \[[Certificate][204]\] <sub>

<sub> -  Convolutional Neural Networks by deeplearning.ai on Coursera \[[Certificate][205]\] <sub>

<sub> -  Sequence Models by deeplearning.ai on Coursera \[[Certificate][206]\] <sub>

<sub> -  Natural Language Processing with Deep Learning (Stanford CS224N)  <sub>



[201]: https://www.coursera.org/account/accomplishments/certificate/CAT2Q4MM8PSK
[202]: https://www.coursera.org/account/accomplishments/certificate/EVUVCJLZGWGA
[203]: https://www.coursera.org/account/accomplishments/certificate/PG6L3V5ZELWS
[204]: https://www.coursera.org/account/accomplishments/certificate/ZK5JR7YH3J53
[205]: https://www.coursera.org/account/accomplishments/certificate/NNY8NPC66MVE
[206]: https://www.coursera.org/account/accomplishments/certificate/UVAM8PW74ASN








[9]: https://ascelibrary.org/doi/abs/10.1061/%28ASCE%29IS.1943-555X.0000442
[10]: https://www.sciencedirect.com/science/article/pii/S0141029618320546
[11]: https://www.witpress.com/elibrary/SSE-volumes/6/1/1084
[12]: https://engrxiv.org/jg27s/
[13]: https://www.researchgate.net/profile/Arash_Saeidpour/publication/320191091_Comparison_of_Postbuckling_Prediction_Approaches_in_Curved_Panels/links/59d3ecc90f7e9b4fd7ffc4a9/Comparison-of-Postbuckling-Prediction-Approaches-in-Curved-Panels.pdf
[14]: https://athenaeum.libs.uga.edu/handle/10724/37488
