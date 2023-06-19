| Year | Reference | Task | Dataset: Has indiv.<sup>[1](#datasymbols)</sup> | Attributes | # annots/<br/>instance | # rows. |  Score | Metric |
|:----- |:----- |:----- |:----- |:----- |:----- |:----- |:----- |:----- |
| 2022 | [ArMIS - The Arabic Misogyny and Sexism Corpus with Annotator Subjective Disagreements](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.244.pdf) (Dina Almanea and Massimo Poesio) | Hate speech identification | [ArMIS](https://le-wi-di.github.io/) | :family_man_woman_girl_boy: | 3 | 964 | 0.525 | Fleiss' Kappa |
| 2021 | [Whose Opinions Matter? Perspective-aware Models to Identify Opinions of Hate Speech Victims in Abusive Language Detection](https://arxiv.org/abs/2106.15896) (Sohail Akhtar, Valerio Basile, Viviana Patti) | Hate speech identification | [HS-Brexit](https://le-wi-di.github.io/) | :family_man_woman_girl_boy: | 6 | 1120 | 0.35 | Fleiss' Kappa<sup>[2](#complicatedirr)</sup> |
| 2021 | [ConvAbuse: Data, Analysis, and Benchmarks for Nuanced Abuse Detection in Conversational AI](https://aclanthology.org/2021.emnlp-main.587/) (Amanda Cercas Curry, Gavin Abercrombie, Verena Rieser) | Hate speech identification | [ConvAbuse](https://le-wi-di.github.io/) | :family_man_woman_girl_boy: | 3-8 | 4185 | 0.69 | Alpha |
| 2021 | [Agreeing to Disagree: Annotating Offensive Language Datasets with Annotators’ Disagreement](https://aclanthology.org/2021.emnlp-main.822/) (Elisa Leonardelli, Stefano Menini, Alessio Palmero Aprosio, Marco Guerini, Sara Tonelli) | Hate speech identification | [MD-Agreement](https://le-wi-di.github.io/) | :family_man_woman_girl_boy: | 5 | 10K | 71.172 | Percent agreement<sup>[4](#selfcalculated)</sup> |
| 2021 | [Designing Toxic Content Classification for a Diversity of Perspectives](https://arxiv.org/abs/2106.04511) (Deepak Kumar, Patrick Gage Kelley, Sunny Consolvo, Joshua Mason, Elie Bursztein, Zakir Durumeric, Kurt Thomas, Michael Bailey) |  Hate speech identification | [Dataset](https://data.esrg.stanford.edu/study/toxicity-perspectives): $\square$ | :family_man_woman_girl_boy: | 5 | 107,620 | 65.2-90% | Percent agreement<sup>[2](#complicatedirr)</sup> |
| 2020 | [On Faithfulness and Factuality in Abstractive Summarization](https://aclanthology.org/2020.acl-main.173) (Joshua Maynez, Shashi Narayan, Bernd Bohnet, Ryan McDonald) | Hallucination classification | [Dataset](https://github.com/google-research-datasets/xsum_hallucination_annotations) | :family_man_woman_girl_boy: | 3 |  | 0.61-0.80 | Fleiss' Kappa<sup>[2](#complicatedirr)</sup> |
| 2020 | [On Faithfulness and Factuality in Abstractive Summarization](https://aclanthology.org/2020.acl-main.173) (Joshua Maynez, Shashi Narayan, Bernd Bohnet, Ryan McDonald) | Factuality classification | [Dataset](https://github.com/google-research-datasets/xsum_hallucination_annotations) | :family_man_woman_girl_boy: | 3 |  | 0.81-1.00 | Fleiss' Kappa<sup>[2](#complicatedirr)</sup> |
| 2019 | [Understanding Discourse on Work and Job-Related Well-Being in Public Social Media](https://www.aclweb.org/anthology/P16-1099) (Liu, Tong and Homan, Christopher and Ovesdotter Alm, Cecilia and Lytle, Megan and Marie White, Ann and Kautz, Henry) |  | [Dataset](https://github.com/Homan-Lab/pldl_data/tree/master) | :family_man_woman_girl_boy: |  |  |  |  |
| 2019 | [Learning to Predict Population-Level Label Distributions](https://ojs.aaai.org/index.php/HCOMP/article/view/5286/5138) (Tong Liu, Akash Venkatachalam, Pratik Sanjay Bongale, Christopher M. Homan) |  | [Dataset](https://github.com/Homan-Lab/pldl_data/tree/master) | :family_man_woman_girl_boy: |  |  |  |  |
| 2018 | [Introducing the gab hate corpus: Defining and applying hate-based rhetoric to social media posts at scale.](https://link.springer.com/article/10.1007/s10579-021-09569-x) (Brendan Kennedy, Mohammad Atari, Aida M. Davani, Leigh Yeh, Ali Omrani, Yehsong Kim, Kris Coombs, et al.) | Hate speech identification | [Dataset](https://osf.io/edua3/) |  |  |  |  |  |
| 2018 | [A Broad-Coverage Challenge Corpus for Sentence Understanding through Inference](https://cims.nyu.edu/~sbowman/multinli/paper.pdf) (Williams, Adina and Nangia, Nikita and Bowman, Samuel) | Multi-genre NLI | [Dataset](https://cims.nyu.edu/~sbowman/multinli/) | :family_man_woman_girl_boy: |  |  |  |  |
| 2015 | [A large annotated corpus for learning natural language inference](https://nlp.stanford.edu/projects/snli/) (Samuel R. Bowman, Gabor Angeli, Christopher Potts, and Christopher D. Manning) | NLI | [Dataset](https://nlp.stanford.edu/projects/snli/) | :family_man_woman_girl_boy: |  |  |  |  |
| 2014 | [Lexical Acquisition for Opinion Inference: A Sense-Level Lexicon of Benefactive and Malefactive Events](https://aclanthology.org/W14-2618.pdf) (Yoonjung Choi, Lingjia Deng, and Janyce Wiebe) | WSD for sentiment analysis | [Dataset](http://mpqa.cs.pitt.edu/corpora/gfbf/) | $\triangle$ |  |  | 0.84 | Percent agreement|
|"|"|"|"|"|"|"|0.75 | Kappa|
|  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |




<a name="datasymbols">1</a>:
If there is no :family_man_woman_girl_boy: emoji, this dataset contains aggregate level annotations. If there is, it contains annotator-level data as well.<br/>
$\times$ = no data released,<br/>
$\square$ = data can be obtained by reaching out to authors
<br/>

<a name="attributes">2</a>:<br/>
:pencil: = contains annotator instructions<br/>
:family_man_woman_girl_boy: = has annotator-level data<br/>
:computer: = data is crowdsourced as well (not just annotations). For example, having MTurkers write pairs of sentences as opposed to scraping the web<br/>
<br/>
<a name="complicatedirr">3</a>: Refer to the paper for more details. The interrater agreement is reported per subset and/or using several metrics.
<a name="selfcalculated">4</a>: Calculated using information given in paper/from dataset.

Papers talking about calculation methods (todo: organize this table)
- J. Richard Landis and Gary G. Koch. 1977. The measurement of observer agreement for categorical data.
Biometrics, 33(1):159–174.
- 
