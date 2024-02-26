# arXiv Dataset

## Download Data

Metadata download [here](https://www.kaggle.com/datasets/Cornell-University/arxiv?resource=download)


To download PDFs, use this command:

```bash
gsutil -m cp -r gs://arxiv-dataset/arxiv/arxiv ./pdf
```

This command will download papers from month \emph{01} of year \emph{(20)24}. I've found each month in recent years's worth of data to contain on the order of 50GB of files. For this project, I've downloaded all PDFs starting from 2017, which is the year that the ``Attention is All You Need``` (\cite{vaswani_attention_2017}) paper arrived on the scene and introduced the Transfomer architecture.

arXiv has a category taxonomy here [topic](https://arxiv.org/category_taxonomy). 


## Preprocess
- Convert to parquet
- Filter to subset
- Extract text

