# Cross-corpus-readability-assessment-compatibility-for-English-texts

## Background

  

## Install

  

### 跨语料库文本难度兼容性评估

  

###   数据
| Dataset | Description                                                                                                                                                                                                                                                                            |
|---------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| CEFR    | The Common European Framework of Reference for Languages (CEFR) is an internationally recognized standard for describing language proficiency and levels. The standard divides six levels based on language texts of different difficulty levels, from beginner to professional level. |
| CLEC    | Chinese Learner English Corpus (CLEC) is a corpus based on learners' English writing. There are five levels of corpus, including middle school students, college English level 4 and 6, junior and senior professional English.                                                        |
| CLOTH   | CLOTH is a large-scale English cloze test set, which is divided into two grades: junior high school and senior high school.                                                                                                                                                            |
| NES     | Newsela (NES) corpus consists of news articles. It covers articles from grade 2 to grade 12 at different levels, allowing students to practice reading on texts appropriate to their ability level.                                                                                    |
| OSP     | The OneStopEnglish (OSP) corpus contains three levels of reading difficulty (primary, intermediate, and advanced), with 189 texts at each level.                                                                                                                                       |
| RACE    | The Reading Comprehension Dataset From Examination (RACE) is a collection of reading comprehension materials from English exams for middle and high school students in China, divided into two levels based on grades: junior high and senior high.                                    |

### Feature

| Code                 | Description                                          |
|----------------------|------------------------------------------------------|
|   Lexical Features                                                          |
| ASPW                 | average syllables per word                           |
| ALPW                 | average letters per word                             |
| DWP                  | percentage of difficult words                        |
| CWP                  | percentage of complex words                          |
| LWP                  | percentage of long words                             |
|  Syntactic Features                                                         |
| LSP                  | percentage of long sentences                         |
| AWPS                 | average number of words per sentence                 |
| NPS                  | average number of noun phrases per sentence          |
| VPS                  | average number of verb phrases per sentence          |
| PPS                  | average number of prepositional phrases per sentence |
| SPS                  | average number of subordinate clauses per sentence   |
| SQS                  | average number of special subordinate clauses        |
|                      | average (question) per sentence                      |
| ANPS                 | average length of noun phrases                       |
| AVPS                 | average length of verb phrases                       |
| APPS                 | average length of prepositional phrases              |
| APT                  | average length of parse tree                         |
| Grammatical Features                                                        |
| NP                   | percentage of nouns                                  |
| PNP                  | percentage of proper nouns                           |
| PP                   | percentage of pronouns                               |
| CoP                  | percentage of conjunctions                           |
| CP                   | percentage of commas                                 |

### Project Framework
We proposed a method for cross-corpus evaluation that aims to predict the readability of text from different corpora and assess the compatibility of readability systems. The project framework contains six steps: Feature Extraction, Word Vector Representation, Feature Fusion, Training Model, Readability Prediction and Readability System Compatibility Assessment.
![Alt text](image url)

### Model
| ML | XGBoost, SVM         |
|----|----------------------|
| DL | BI-LSTM, ATT-BI-LSTM |

### Compatibility Results

Compatibility Assessment Results of RJSD (ML+Feature)

Compatibility Assessment Results of RJSD (ML/DL+GloVe)

Compatibility Assessment Results of RJSD (ML/DL+fusion feature)













































