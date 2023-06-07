| Year | Reference | Task | Dataset | Has indiv.<sup>[1](#datasymbols)</sup> | Contains instruct. | # annots/<br/>instance | # rows. |  Score | Metric |
|:----- |:----- |:----- |:----- |:----- |:----- |:----- |:----- |:----- |:----- |
| 2022 | [ArMIS - The Arabic Misogyny and Sexism Corpus with Annotator Subjective Disagreements](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.244.pdf) (Dina Almanea and Massimo Poesio) | Hate speech identification | [ArMIS](https://le-wi-di.github.io/) | $\bigcirc$ |  | 3 | 964 | 0.525 | Fleiss Kappa |
| 2021 | [Whose Opinions Matter? Perspective-aware Models to Identify Opinions of Hate Speech Victims in Abusive Language Detection](https://arxiv.org/abs/2106.15896) (Sohail Akhtar, Valerio Basile, Viviana Patti) | Hate speech identification | [HS-Brexit](https://le-wi-di.github.io/) | $\bigcirc$ |  | 6 | 1120 |  |  |
| 2021 | [ConvAbuse: Data, Analysis, and Benchmarks for Nuanced Abuse Detection in Conversational AI](https://aclanthology.org/2021.emnlp-main.587/) (Amanda Cercas Curry, Gavin Abercrombie, Verena Rieser) | Hate speech identification | [ConvAbuse](https://le-wi-di.github.io/) | $\bigcirc$ |  |  |  |  |  |
| 2021 | [Designing Toxic Content Classification for a Diversity of Perspectives](https://arxiv.org/abs/2106.04511) (Deepak Kumar, Patrick Gage Kelley, Sunny Consolvo, Joshua Mason, Elie Bursztein, Zakir Durumeric, Kurt Thomas, Michael Bailey) |  Hate speech identification | [Dataset](https://data.esrg.stanford.edu/study/toxicity-perspectives) | $\bigcirc\square$ |  | 5 | 107,620 | 65.2-90% | Percent agreement<sup>[2](#kumar2021)</sup> |
| 2018 | [Introducing the gab hate corpus: Defining and applying hate-based rhetoric to social media posts at scale.](https://link.springer.com/article/10.1007/s10579-021-09569-x) (Brendan Kennedy, Mohammad Atari, Aida M. Davani, Leigh Yeh, Ali Omrani, Yehsong Kim, Kris Coombs, et al.) | Hate speech identification | [Dataset](https://osf.io/edua3/) |  |  |  |  |  |  |
| 2014 | [Lexical Acquisition for Opinion Inference: A Sense-Level Lexicon of Benefactive and Malefactive Events](https://aclanthology.org/W14-2618.pdf) (Yoonjung Choi, Lingjia Deng, and Janyce Wiebe) | WSD for sentiment analysis | [Dataset](http://mpqa.cs.pitt.edu/corpora/gfbf/) | $\triangle$ |  |  |  | 0.84 | Percent agreement|
|"|"|"|"|"|"|"|"| 0.75 | Kappa|
|  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |




<a name="datasymbols">1</a>: $\bigcirc$ = has annotator-level data, $\triangle$ = has aggregate annotation data, $\times$ = no data released, $\square$ = data can be obtained by reaching out to authors (explicitly written as such in the paper)<br/>
<a name="kumar2021">2</a>: The interrater agreemeent is calculated separately by subset using several metrics. Better to refer to the paper for more details.
