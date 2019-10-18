# oos-eval
Repository that accompanies [An Evaluation Dataset for Intent Classificationand Out-of-Scope Prediction](https://arxiv.org/abs/1909.02027) (to appear in EMNLP 2019)


## FAQs
### 1. What language is the dataset in?
All queries are in English.

### 2. How does your dataset/evaluation handle multi-intent queries?
All samples/queries in our dataset are single-intent samples. We consider the problem of multi-intent classification to be future work.

### 3. How did you gather the dataset?
We used crowdsourcing to generate the dataset. We asked crowd workers to either paraphrase "seed" phrases, or respond to scenarios (e.g. "pretend you need to book a flight, what would you say?"). We used crowdsourcing to generate data for both in-scope and out-of-scope data.

## Citing

If you find our dataset useful, please be sure to cite:

```
@ARTICLE{2019arXiv190902027L,
       author = {{Larson}, Stefan and {Mahendran}, Anish and {Peper}, Joseph J. and
         {Clarke}, Christopher and {Lee}, Andrew and {Hill}, Parker and
         {Kummerfeld}, Jonathan K. and {Leach}, Kevin and
         {Laurenzano}, Michael A. and {Tang}, Lingjia and {Mars}, Jason},
        title = "{An Evaluation Dataset for Intent Classification and Out-of-Scope Prediction}",
      journal = {arXiv e-prints},
         year = "2019",
        month = "Sep",
          eid = {arXiv:1909.02027},
        pages = {arXiv:1909.02027},
archivePrefix = {arXiv},
       eprint = {1909.02027},
}
```
