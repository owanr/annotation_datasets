| Year | Reference | Task | Dataset: Has indiv.<sup>[1](#datasymbols)</sup> | Attributes | # annots/<br/>instance | # rows. |  Score | Metric |
|:----- |:----- |:----- |:----- |:----- |:----- |:----- |:----- |:----- |
| 2022 | [ArMIS - The Arabic Misogyny and Sexism Corpus with Annotator Subjective Disagreements](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.244.pdf) (Dina Almanea and Massimo Poesio) | Hate speech identification | [ArMIS](https://le-wi-di.github.io/) | :family_man_woman_girl_boy: | 3 | 964 | 0.525 | Fleiss Kappa |
| 2021 | [Whose Opinions Matter? Perspective-aware Models to Identify Opinions of Hate Speech Victims in Abusive Language Detection](https://arxiv.org/abs/2106.15896) (Sohail Akhtar, Valerio Basile, Viviana Patti) | Hate speech identification | [HS-Brexit](https://le-wi-di.github.io/) | :family_man_woman_girl_boy: | 6 | 1120 |  |  |
| 2021 | [ConvAbuse: Data, Analysis, and Benchmarks for Nuanced Abuse Detection in Conversational AI](https://aclanthology.org/2021.emnlp-main.587/) (Amanda Cercas Curry, Gavin Abercrombie, Verena Rieser) | Hate speech identification | [ConvAbuse](https://le-wi-di.github.io/) | :family_man_woman_girl_boy: |  |  |  |  |
| 2021 | [Designing Toxic Content Classification for a Diversity of Perspectives](https://arxiv.org/abs/2106.04511) (Deepak Kumar, Patrick Gage Kelley, Sunny Consolvo, Joshua Mason, Elie Bursztein, Zakir Durumeric, Kurt Thomas, Michael Bailey) |  Hate speech identification | [Dataset](https://data.esrg.stanford.edu/study/toxicity-perspectives): $\square$ | :family_man_woman_girl_boy: | 5 | 107,620 | 65.2-90% | Percent agreement<sup>[2](#complicatedirr)</sup> |
| 2018 | [Introducing the gab hate corpus: Defining and applying hate-based rhetoric to social media posts at scale.](https://link.springer.com/article/10.1007/s10579-021-09569-x) (Brendan Kennedy, Mohammad Atari, Aida M. Davani, Leigh Yeh, Ali Omrani, Yehsong Kim, Kris Coombs, et al.) | Hate speech identification | [Dataset](https://osf.io/edua3/) |  |  |  |  |  |
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
<a name="complicatedirr">3</a>: The interrater agreemeent is calculated separately by subset using several metrics. Better to refer to the paper for more details.
