# Open-Set-Authorship-Attribution

Jupyter NOtebooks and Dataset link for the paper: Open Set Authorship Attribution towardDemystifying Victorian Periodicals. Accepted to *ICDAR 2021, Switzerland*.
Authors: *Sarkhan Badirli, Mary B. Ton, Abdulmecit Gungor, and Murat Dundar*

Paper at: https://arxiv.org/abs/1912.08259

<p align="center">
  <img width="800" height="300" src="6 authors Word Cloud.jpg">
</p>
<p align="justify">

## Brief Summary

In this paper, we took a pragmatic view of computational AA to highlight the critical role it could play in authorship attribution studies involving historical texts. We consider Victorian texts as a case study as many contemporary literary tropes and publishing strategies originate from this period. We demonstrated the strengths and weaknesses of existing computational AA paradigms. Specifically, we show that common English words are sufficient to a greater extent in distinguishing among writings of most renowned authors, especially when AA is performed in the closed-set setup. Experiments under closed-set assumption produced near perfect attribution accuracy in AA task involving 36 authors using only $1,000$ most frequent words. The performance suffered significantly as we switch to the more realistic open-set setup. Increasing the vocabulary size helped to some extent and provided some interesting insights that would challenge results of manual indexing. Open-set experiments also open interesting avenues for future research to investigate whether authors with the same upbringing may develop similar word usage habits as in the case of Brontë sisters.


## Prerequisites

The code was implemented in Python Jupyter Notebook. For the list of packages please see the `requirements.txt`. You may create a conda virtual environment to have a hassle-free experiment running.

## Data

You can download the datasets used in the paper from [Dropbox](https://www.dropbox.com/s/yvd5kumuamxecsa/AA%20Data%20and%20MFW1000.zip?dl=0).  The dataset contains Authors and their books in a seperate text files, vocabulary list, and most frequent 1000 words.


## Experiments

To reproduce the results from the paper please execute the corresponding jupyter notebook.


### Contact

Feel free to drop me an email if you have any questions: s.badirli@gmail.com
 
