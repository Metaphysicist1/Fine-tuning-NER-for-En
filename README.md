### Fine-tuning NER using PyTorch, 2024 Aug
##### NER - Named Entity Recognition
* Trained on **Jupyter** Notebook + **CUDA** + 4GB **GPU**  (**Nvidia** 1650 Max-Q)
* Public Dataset from **kaggle**: https://paperswithcode.com/dataset/conll-2003
* Used libraries **torch,** **seqeval,** **transformers,**
* Model: **Bert** ["google-bert/bert-base-cased"]
* metrics from **seqeval** [f1_score, recall_score, precision_score]

CoNLL-2003 is a named entity recognition dataset released as a part of CoNLL-2003 shared task: language-independent named entity recognition. The data consists of eight files covering two languages: English and German. For each of the languages there is a training file, a development file, a test file and a large file with unannotated data.

The English data was taken from the Reuters Corpus. This corpus consists of Reuters news stories between August 1996 and August 1997. For the training and development set, ten days worth of data were taken from the files representing the end of August 1996. For the test set, the texts were from December 1996. The preprocessed raw data covers the month of September 1996.

The text for the German data was taken from the ECI Multilingual Text Corpus. This corpus consists of texts in many languages. The portion of data that was used for this task, was extracted from the German newspaper Frankfurter Rundshau. All three of the training, development and test sets were taken from articles written in one week at the end of August 1992. The raw data were taken from the months of September to December 1992.
