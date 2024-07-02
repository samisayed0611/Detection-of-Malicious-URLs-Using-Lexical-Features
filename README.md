# Detection of Malicious URLs Using Lexical Features

## Problem Statement

In this case study, we address the detection of malicious URLs as a multi-class classification problem. We classify raw URLs into different classes such as benign or safe URL, phishing URL, malware URL, or defacement URL.

Machine learning algorithms require numeric inputs, so we will create numeric lexical features from the input URLs. The input to the machine learning algorithms will be these numeric lexical features rather than the actual raw URLs. If you are unfamiliar with lexical features, you can refer to [this discussion](https://stackoverflow.com/questions/33282094/differences-between-lexical-features-and-orthographic-features-in-nlp) on StackOverflow.

In this case study, we will be using three well-known boosting machine learning classifiers: **XGBoost**, **Light GBM**, and **Gradient Boosting Machines**.

## About Data

For training and testing machine learning algorithms, we have used a substantial dataset of 651,191 URLs, comprising:
- 428,103 benign or safe URLs
- 96,457 defacement URLs
- 94,111 phishing URLs
- 32,520 malware URLs

The dataset is curated from five different sources, which are combined and pre-processed to retain only URLs and their class type.

Sources:
- [URL dataset (ISCX-URL-2016)](https://www.unb.ca/cic/datasets/url-2016.html)
- [Malware domain black list dataset](http://www.malwaredomains.com/wordpress/?page_id=66)
- [Faizan Git Repo](https://github.com/faizann24/Using-machine-learning-to-detect-malicious-URLs/tree/master/data)
- [Phishtank dataset](https://www.phishtank.com/developer_info.php)
- [PhishStorm dataset](https://research.aalto.fi/en/datasets/phishstorm--phishing--legitimate-url-dataset(f49465b2-c68a-4182-9171-075f0ed797d5).html)

The final pre-processed dataset is available on Kaggle: [Malicious URL Dataset](https://www.kaggle.com/sid321axn/malicious)

## Project Overview

**Detection of Malicious URLs Using Lexical Features** | Machine Learning, Cybersecurity, NLP, Boosting, Sklearn, Pandas, Regex

Developed a multi-class classification system to detect malicious URLs using lexical features and boosting algorithms (XGBoost, Light GBM, Gradient Boosting Machines), leveraging Pandas and Sklearn for data processing and model training.

Dataset: [Malicious URL Dataset](https://www.kaggle.com/sid321axn/malicious)