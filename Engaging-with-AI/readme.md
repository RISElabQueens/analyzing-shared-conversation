## Welcome to the official repository of: "Engaging with AI: An Exploratory Study on Developers’ Sharing and Reactions to ChatGPT in GitHub Pull Requests". 


This is the replication package of our paper **Engaging with AI: An Exploratory Study on Developers’ Sharing and Reactions to ChatGPT in GitHub Pull Requests** which has been accepted In 39th IEEE/ACM International Conference on Automated Software Engineering Workshops (ASEW ’24).

Authors: Huizi Hao, Yuan Tian.

### Folder structure

```bash
├── data_preprocessing
│ |── data_preprocessing
│ |── preprocessing
├── RQ1
│ |── rq1 input: rq1_pr_english_only_no_404.xlsx
│ |── rq1 output: rq1_recent_event_group.csv 
│ |── rq1 code  
├── RQ2
│ ├── rq2 input: rq2_english_only_useful.xlsx
│ |── rq2 output: rq2_sentiment_test.csv
│ |── rq1 output: rq2_sorted.csv  
│ |── rq2 code

```
### How to run

Ensure you have Python 3.8 or higher installed. In your terminal, in the same folder as this README file, execute the following commands:

1. Clone the repository by running 
2. Run ```pip install -r requirements.txt```
3. To run the notebooks of RQ1 and RQ2, make sure you have jupyter/jupyterlab installed in your machine.