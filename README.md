# BERT for Sentence Sentiment Classification
This repo is used to archive code in a previous class assignment where I built a BERT model from scratch with `torch` and with no other external libraries are allowed (e.g., `transformers`).

Running the following code will reproduce results:
```
python3 classifier.py --option [pretrain/finetune] --epochs NUM_EPOCHS --lr LR --train data/sst-train.txt --dev data/sst-dev.txt --test data/sst-test.txt
```
