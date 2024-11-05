# AES-Research
Everything about Automated Eassy Scoring


## Dataset

[ASAP](https://www.kaggle.com/c/asap-aes/data?select=Essay_Set_Descriptions.zip):  
- essay_id: 学生作文的id
- essay_set: 每组论文的 ID, 比赛共有八组作文, 编号为1-8, 每组作文分别对应一个 `prompt` 
- essay: 学生作文回答内容
- rater1_domain1: 评分员1对作文的“Domain 1”评分。此评分是针对作文的第一个评分维度（通常是内容、结构、表达等），并且所有作文都会有这个评分。
- rater2_domain1: 评分员2对作文的“Domain 1”评分。此评分是针对作文的第一个评分维度（通常是内容、结构、表达等），并且所有作文都会有这个评分。
- rater3_domain1: 评分员3对作文的“Domain 1”评分。此评分是针对作文的第一个评分维度（通常是内容、结构、表达等），并且所有作文都会有这个评分。
- domain1_score:  作文的“Domain 1”分数，这是多个评分员评分后的最终分数，通常是一个通过加权或平均得到的综合分数。该分数是最终的评分，代表作文在“Domain 1”维度的整体评分。通过这种方式，减少了评分员之间的评分差异，并给出了统一的标准。
- rater1_domain2: 评分员1对作文的“Domain 2”评分。仅适用于第2组的作文，该维度的评分可能与作文的语言使用、语法等方面相关。
- rater2_domain2: 评分员2对作文的“Domain 2”评分。仅适用于第2组的作文，该维度的评分可能与作文的语言使用、语法等方面相关。
- domain2_score: 作文的“Domain 2”分数，经过多个评分员评分后的最终分数。此分数仅适用于第2集的作文。提供一个统一的“Domain 2”评分，用于分析作文在第二维度上的表现。此分数通过处理评分员之间的差异得出。
- rater1_trait1_score to rater3_trait6_score：这是针对第7组和第8组的评分维度，反映了评分员在多个不同维度上的评分（trait scores）。每个评分员对作文的多个维度进行评分，例如，评分员1对第一个特征维度（trait1）评分，评分员3对第六个特征维度（trait6）评分。
