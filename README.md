# An Evaluation Dataset for Intent Classification and Out-of-Scope Prediction
Repository that accompanies [An Evaluation Dataset for Intent Classification and Out-of-Scope Prediction](https://www.aclweb.org/anthology/D19-1131/).


## FAQs
### 1. What is this dataset for?
This dataset is for evaluating the performance of intent classification systems in the presence of "out-of-scope" queries. By "out-of-scope", we mean queries that do not fall into any of the system-supported intent classes. Most datasets include only data that is "in-scope". Our dataset includes both in-scope and out-of-scope data.

### 2. What language is the dataset in?
All queries are in English.

### 3. How does your dataset/evaluation handle multi-intent queries?
All samples/queries in our dataset are single-intent samples. We consider the problem of multi-intent classification to be future work.

### 4. How did you gather the dataset?
We used crowdsourcing to generate the dataset. We asked crowd workers to either paraphrase "seed" phrases, or respond to scenarios (e.g. "pretend you need to book a flight, what would you say?"). We used crowdsourcing to generate data for both in-scope and out-of-scope data.

## Citing

If you find our dataset useful, please be sure to cite:

```
@inproceedings{larson-etal-2019-evaluation,
    title = "An Evaluation Dataset for Intent Classification and Out-of-Scope Prediction",
    author = "Larson, Stefan  and
      Mahendran, Anish  and
      Peper, Joseph J.  and
      Clarke, Christopher  and
      Lee, Andrew  and
      Hill, Parker  and
      Kummerfeld, Jonathan K.  and
      Leach, Kevin  and
      Laurenzano, Michael A.  and
      Tang, Lingjia  and
      Mars, Jason",
    booktitle = "Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP)",
    year = "2019",
    url = "https://www.aclweb.org/anthology/D19-1131"
}
```
