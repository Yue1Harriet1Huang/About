---
layout: page
title: Large Datasets in Python
visible: true
tags:
  - python
  - intermediate
---

 - **Authors**: Yue Harriet Huang
 - **Research field**: Probability and Statistics
 - **Lesson topic**: Use PySpark and SparkSQL to Connect Jupyter Notebook to Remote SQL Server DB
 - **Lesson content URL**: <https://github.com/uoftcoders/studyGroup/tree/gh-pages/lessons/python/large-data>

Today on 20190204 I learnt a really cool thing : using PySpark that connects your Jupyter Notebook to execute sql on a SQL database on remote server is so much faster than running SQL directly in the SQL database. I ran the whole process in a RMarkdown file in a R bookdown project. 

1. Specify Python Virtual Environment in RMarkdown Code Chunk in R as

```

````{r}
library(reticulate}
use_python("/home/user/anaconda3/envs/env_var/bin/python") # the python version in the virtual environment
use_virtualenv("/home/user/anaconda3/envs/env_var") # specify directory containing environment
use_condaenv("env_var") # specify conda environment


```

2. Use


 - **Authors**: Wei Zhang
 - **Research field**: Immunology
 - **Lesson topic**: Processing gDNA chip results and single cell PCR results; finding shared motifs.
 - **Lesson content URL**: <https://github.com/uoftcoders/studyGroup/tree/gh-pages/lessons/python/large-data>

This lesson contains two parts: 1st, accessing and storing data from personal genomic DNA sequencing results using the pandas.DataFrame structure; 2nd, finding shared motifs in single-cell PCR sequencing results.

To follow along, visit [the IPython notebook](https://github.com/uoftcoders/studyGroup/blob/gh-pages/lessons/python/large-data/LargeDatasetsPython.ipynb).

The [generic_gdna.txt](https://github.com/uoftcoders/studyGroup/blob/gh-pages/lessons/python/large-data/generic_gdna.txt) file contains a sample personal gDNA chip sequencing output.

The [generic_tcr.txt](https://github.com/uoftcoders/studyGroup/blob/gh-pages/lessons/python/large-data/generic_tcr.txt) file is a tab-separated plain text file containing 10 sample single-cell PCR sequencing results of the [T cell receptor](https://en.wikipedia.org/wiki/T_cell_receptor).

