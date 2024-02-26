# arXiv Dataset

## Download Data

Metadata download [here](https://www.kaggle.com/datasets/Cornell-University/arxiv?resource=download)


To download all the PDFs, use this command:

```bash
gsutil -m cp -r gs://arxiv-dataset/arxiv/arxiv .
```

For more targeted downloads, you can pick a specific [topic](https://arxiv.org/category_taxonomy). This command downloads all computer science related papers:

```bash
gsutil -m cp -r gs://arxiv-dataset/arxiv/cs/ .
```

## Preprocess
- Convert to parquet
- Filter to subset
- Extract text

