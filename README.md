# en-az-parallel-corpus

The directory contains an information about a parallel corpus for English-Azerbaijani and Azerbaijani-English translation task. The main goal of introducing the data is to help engineers and developers to create a universal language model (fine-tuned models) for Azerbaijani language. 

*Read this in other languages: [English](README.md), [Azerbaijan](README.az.md)*

Download the train data along with the validation and test sets:

```
$ curl https://s3.us-east-2.amazonaws.com/derintelligence/dataset/data.tar.gz | tar xzvf -
```

Corpus Statistics
-----------------

| File           | #sentences |  #words | #vocabulary |
|:---------------|-----------:|--------:|------------:|
| train.en       |     68,201 | 1,205,183 |       42,315 |
| train.az       |     68,201 | 928,474 |       88,002 |
| dev.en         |        500 |   9,015 |         2,867 |
| dev.az         |        500 |   6,852 |         3,832 |
| test.en        |        500 |   9,032 |         2,941 |
| test.az        |        500 |   6,905 |         3,815 |


