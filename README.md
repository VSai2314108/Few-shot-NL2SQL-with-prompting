# Few-shot-NL2SQL-with-prompting

## Table of contents
* [Dataset](#dataset)
* [Setup](#setup)


## dataset
To reproduce the results reported in the paper, please download the Spider dataset from the link below and create a data directory containing the tables.json and dev.json files.

```
$ Spider dataset = "https://drive.google.com/uc?export=download&id=1TqleXec_OykOYFREKKtschzY29dUcVAQ"
```


## setup
To run this project, use the following commands:

```
$ pip3 install -r requirements.txt
$ echo "Start running test.py"
$ python3 CoT.py --dataset ./data/ --output predicted_sql.txt
$ echo "Finished running test.py"
```
