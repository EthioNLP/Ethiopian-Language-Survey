# Natural Language Processing in Ethiopian Languages: Current State, Challenges, and Opportunities - [arxiv](https://arxiv.org/abs/2303.14406)

This survey delves into the current state of natural language processing (NLP) for four
Ethiopian languages: Amharic, Afaan Oromo, Tigrinya, and Wolaytta. Through this paper, we identify key challenges and opportunities
for NLP research in Ethiopia. Furthermore, we provide a centralized repository on GitHub that
contains publicly available resources for various NLP tasks in these languages. This reposi
tory can be updated periodically with contributions from other researchers. Our objective is to
disseminate information to NLP researchers interested in Ethiopian languages and encourage
future research in this domain.



## 1. NLP Tools
|Tools Name|Tools task |Language support|Resource link|
|----------|-----------|----------------|-------------|
|amseg     | Segmenter, tokenizer, transliteration, romanization and normalization| Amharic    | [amseg](https://pypi.org/project/amseg/) |
|HornMorpho| Morphological analysis|   Amhric, Afaan Ormo, Tigirgna              |[HornMorpho](https://github.com/hltdi/HornMorpho)      |
|lemma     |   Lemmatizer     |   Amhric      |[lemma](https://universaldependencies.org)|


## 2. NLP Applications
### 2.1. Machine Translation (MT)
We discuss the MT progress for Ethiopian languages in three categories: **English Centeric** -> works done for the above target Ethiopian languages with English pair, **Ethiopian - Ethiopian** -> works done for Ethiopian language pairs without involving other languages  and **Multilingual MT** -> works done for Ethiopian languages with other languages in a multilingual setting.
#### 2.1.1 English centeric
  - [Parallel Corpora Preparation for English-Amharic Machine Translation](https://link.springer.com/chapter/10.1007/978-3-030-85030-2_37)
  - [Extended Parallel Corpus for Amharic-English Machine Translation](https://arxiv.org/abs/2104.03543)
  - [Context based machine translation with recurrent neural network for English–Amharic translation](https://link.springer.com/article/10.1007/s10590-021-09262-4)
  - [Offline Corpus Augmentation for English-Amharic Machine Translation](https://ieeexplore.ieee.org/document/9845019)
  - [The Effect of Normalization for Bi-directional Amharic-English Neural Machine Translation](https://arxiv.org/abs/2210.15224)
  - [Optimal Alignment for Bi-directional Afaan Oromo-English Statistical Machine Translation](http://etd.aau.edu.et/handle/123456789/14063)
  - [English-Afaan Oromo Statistical Machine Translation](https://www.semanticscholar.org/paper/English-Afaan-Oromo-Statistical-Machine-Translation-Solomon/44619213bb56d6385383ab3d914ca2e5296b8e00)
  - [English-Oromo Machine Translation: An Experiment Using a Statistical Approach](https://aclanthology.org/L10-1470/)
  - [Crowdsourcing Parallel Corpus for English-Oromo Neural Machine Translation using Community Engagement Platform](https://arxiv.org/abs/2102.07539)
  - [Machine Learning Approach to English-Afaan Oromo Text-Text Translation: Using Attention based Neural Machine Translation](https://ieeexplore.ieee.org/document/9711807)
  - [The effect of shallow segmentation on English-Tigrinya statistical machine translation](https://ieeexplore.ieee.org/document/7875939)
  - [Morphological Segmentation for English-to-Tigrinya Statistical Machine Translation](https://www.semanticscholar.org/paper/Morphological-Segmentation-for-English-to-Tigrinya-Tedla-Yamamoto/f41eea5a02f3a1ba0ba18b322ca7167cba024e73)
  - [Enhancing Bi-directional English-Tigrigna Machine Translation Using Hybrid Approach](https://www.semanticscholar.org/paper/Enhancing-Bi-directional-English-Tigrigna-Machine-Berihu-Mesfin/98df2f1bda6beecdc56d3ec0ba6aca4939e38389)
  - [Statistical Machine Translator For English To Tigrigna Translation](http://www.ijstr.org/final-print/jan2020/Statistical-Machine-Translator-For-English-To-Tigrigna-Translation.pdf)
  - [An Exploration of Data Augmentation Techniques for Improving English to Tigrinya Translation](https://arxiv.org/abs/2103.16789)
  - [A Parallel Corpora for bi-directional Neural Machine Translation for Low Resourced Ethiopian Languages](https://ieeexplore.ieee.org/document/9672230)
  - [Low-Resource Neural Machine Translation Improvement Using Source-Side Monolingual Data](https://www.mdpi.com/2076-3417/13/2/1201)
  - [English-Ethiopian Languages Statistical Machine Translation](https://aclanthology.org/W19-3611/)

#### 2.1.2 Local to Local
  - [Amharic-Awngi Machine Translation: An Experiment Using Statistical Approach](https://www.ijcseonline.org/pdf_paper_view.php?paper_id=4779&2-IJCSE%2007603.pdf)
  - [Experimenting Statistical Machine Translation for Ethiopic Semitic Languages: The Case of Amharic-Tigrign](https://link.springer.com/chapter/10.1007/978-3-319-95153-9_13)
  - [Context based machine translation with recurrent neural network for English-Amharic translation](https://link.springer.com/article/10.1007/s10590-021-09262-4)

#### 2.1.3 Multilingual
  - [Low resource neural machine translation: A benchmark for five african languages](https://arxiv.org/abs/2003.14402)
  - [WebCrawl African : A Multilingual Parallel Corpora for African Languages](https://aclanthology.org/2022.wmt-1.105/)
  
  
## 2.2. POS Tagging

- [Part of Speech tagging for Amharic using Conditional Random Fields](https://aclanthology.org/W05-0707.pdf)
- [Methods for Amharic Part-of-Speech Tagging](https://www.diva-portal.org/smash/get/diva2:1042595/FULLTEXT01.pdf)
- [Amharic Part-of-Speech Tagger for Factored Language Modeling](https://aclanthology.org/R09-1077.pdf)
- [Part of speech tagging for Amharic](https://pure.mpg.de/rest/items/item_1448968/component/file_1448967/content)
- [POS Tagging for Amharic Text: A Machine Learning Approach](https://infocomp.dcc.ufla.br/index.php/infocomp)
- [Part-of-speech tagging for underresourced and morphologically rich languages—the case of Amharic](https://hal.univ-grenoble-alpes.fr/hal-00959156/)
- [Parts of Speech Tagging for Afaan Oromo](https://thesai.org/Publications/IJACSA)
- [Tigrinya Part-of-Speech Tagging with Morphological Patterns and the New Nagaoka Tigrinya Corpus](https://www.researchgate.net/profile/Kazuhide-Yamamoto/publication/305362037_Tigrinya_Part-of-Speech_Tagging_with_Morphological_Patterns_and_the_New_Nagaoka_Tigrinya_Corpus))
- [Part of Speech Tagging for Wolaita Language using Transformation Based Learning (TBL) Approach](https://www.researchgate.net/profile/Birhanesh-Fikre/publication/345243262_Part_of_Speech_Tagging_for_Wolaita_Language_using_Transformation_based_Learning_TBL_Approach)
- [A comparative study on different techniques for thai part-of-speech tagging](https://ieeexplore.ieee.org/document/6559527)
- [Machine Learning Approaches for Amharic Parts-of-speech Tagging](https://arxiv.org/pdf/2001.03324.pdf)
- [Towards improving Brill’s tagger lexical and transformation rule for Afaan Oromo language](https://www.researchgate.net/publication/308788342_Improving_Brill's_tagger_lexical_and_transformation_rule_for_Afaan_Oromo_language)
- [Deep learning-based part-of-speech tagging of the Tigrinya language](https://link.springer.com/chapter/10.1007/978-3-030-59506-7_29)
- [Introducing various Semantic Models for Amharic: Experimentation and Evaluation with multiple Tasks and Datasets](https://arxiv.org/abs/2011.01154)

## 2.3. Question Classification and Answering
- [Question Classification in Amharic Question Answering System: Machine Learning Approach](https://www.proquest.com/openview/a3d9011a2ef22c6dbd7133b306ddcfac/1?pq-origsite=gscholar&cbl=2028729)
- [Amharic Question Classification System Using Deep Learning Approach](http://etd.aau.edu.et/handle/123456789/27559)
- [Amharic Question Answering for Biography, Definition, and Description Questions](https://aclanthology.org/W19-3635/)
- [TETEYEQ: Amharic Question Answering For Factoid Questions](https://www.inf.uni-hamburg.de/en/inst/ab/lt/people/seid-muhie-yimam/yimam-ms-thesis.pdf)
- [Question Answering Classification for Amharic Social Media Community Based Questions](https://www.inf.uni-hamburg.de/en/inst/ab/lt/publications/2022-belayetal-sigullrec2022.pdf)


## 2.4. Named Entity Recognition (NER)
- [MasakhaNER: Named Entity Recognition for African Languages](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00416/107614/MasakhaNER-Named-Entity-Recognition-for-African)
- [Amharic Named Entity Recognition Using A Hybrid Approach](http://etd.aau.edu.et/handle/123456789/14581)
- [Named entity recognition for Amharic using deep learning](https://ieeexplore.ieee.org/abstract/document/8102402/)
- [Named Entity Recognition for Amharic Using Stack-Based Deep Learning](https://link.springer.com/chapter/10.1007/978-3-319-77113-7_22)
- [ANEC: An Amharic Named Entity Corpus and Transformer Based Recognizer](https://ieeexplore.ieee.org/abstract/document/10040676)
- [Named Entity Recognition for Afan Oromo](http://etd.aau.edu.et/handle/123456789/2440)
- [Afaan Oromo Named Entity Recognition Using Hybrid Approach](http://etd.aau.edu.et/handle/123456789/547)
- [Boosting Afaan Oromo Named Entity Recognition with Multiple Methods](https://mecs-press.net/ijieeb/ijieeb-v13-n5/IJIEEB-V13-N5-5.pdf)
- [Afan-Oromo Named Entity Recognition Using Bidirectional RNN](https://sciresol.s3.us-east-2.amazonaws.com/IJST/Articles/2022/Issue-16/IJST-2021-123.pdf)
- [Named-entity recognition for a low-resource language using pre-trained language model](https://dl.acm.org/doi/abs/10.1145/3477314.3507066)
- [A method of named entity recognition for Tigrinya](https://dl.acm.org/doi/abs/10.1145/3570733.3570737)
- [Named entity recognition for Amharic language](http://etd.aau.edu.et/handle/123456789/2741)
- [A named entity recognition for Amharic](http://etd.aau.edu.et/bitstream/handle/123456789/14502/Besufikad%20Alemu.pdf?sequence=1&isAllowed=y)
## 2.5. Text Classification

#### 2.5.1 Hate Speech Detection

- [Social Network Hate Speech Detection for Amharic Language](https://airccj.org/CSCP/vol8/csit88604.pdf)
- [Vulnerable community identification using hate speech detection on social media](https://www.sciencedirect.com/science/article/abs/pii/S0306457318310902)
- [Multi-channel convolutional neural network for hate speech detection in social media](https://link.springer.com/chapter/10.1007/978-3-030-93709-6_41)
- [Amharic text hate speech detection in social media using deep learning approach](https://ir.bdu.edu.et/handle/123456789/12723)
- [The 5Js in Ethiopia: Amharic Hate Speech Data Annotation Using Toloka Crowdsourcing Platform](https://ieeexplore.ieee.org/document/9971189)

- [Afaan Oromo Hate Speech Detection and Classification on Social Media](https://aclanthology.org/2022.lrec-1.712/)
- [Detection of hate speech text in afan oromo social media using machine learning approach](https://indjst.org/articles/detection-of-hate-speech-text-in-afan-oromo-social-media-using-machine-learning-approach)
- [Automatic Hate and Offensive speech detection framework from social media: the case of Afaan Oromoo language](https://ieeexplore.ieee.org/document/9672232)
- [Hate Speech Detection from Facebook Social Media Posts and Comments in Tigrigna language](http://repository.smuc.edu.et/handle/123456789/6929)


#### 2.5.2 Sentiment Analysis

- [Exploring Amharic Sentiment Analysis from Social Media Texts: Building Annotation Tools and Classification Models](https://aclanthology.org/2020.coling-main.91/)
- [Comparative Analysis of Deep Learning Models for Aspect Level Amharic News Sentiment Analysis](https://ieeexplore.ieee.org/document/9765172)
- [Sentiment Analysis of Afaan Oromo using Machine learning Approach](http://ijrsset.org/pdfs/v7-i9/2.pdf)
- [Sentiment analysis of Afaan Oromoo facebook media using deep learning approach](https://www.iiste.org/Journals/index.php/NMMC/article/view/52606)
- [Multi-Class Sentiment Analysis from Afaan Oromo Text Based On Supervised Machine Learning Approaches](http://ijrsset.org/pdfs/v7-i7/3.pdf)
- [Sentiment Analysis for Low-Resource Language: The Case of Tigrinya](https://erepo.uef.fi/bitstream/handle/123456789/23169/urn_nbn_fi_uef-20201000.pdf?sequence=-1&isAllowed=y)

#### 2.5..3 News Classification

- [An Amharic News Text classification Dataset](https://arxiv.org/abs/2103.05639)
- [Text Classification Based on Convolutional Neural Networks and Word Embedding for Low-Resource Languages: Tigrinya](https://www.mdpi.com/2078-2489/12/2/52)
- [MasakhaNEWS: News Topic Classification for African languages](https://arxiv.org/abs/2304.09972)


#### 2.5.4. Text Summarization

- [XL-Sum: Large-Scale Multilingual Abstractive Summarization for 44 Languages](https://arxiv.org/abs/2106.13822)
