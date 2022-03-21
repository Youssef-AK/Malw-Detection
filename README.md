# PE Detection based on BODMAS

BODMAS is short for Blue Hexagon Open Dataset for Malware Analysis. Dataset containing timestamped malware samples and well-curated family information for research purposes.
The BODMAS dataset contains 57,293 malware samples and 77,142 benign samples collected from August 2019 to September 2020, with carefully curated family information 
(**581** families).

the feature vectors extracted by using the (LIEF)[https://pypi.org/project/lief/?msclkid=faebb2a1a95811ec8b6a8198d5f1de0b] project (version 0.9.0), the same as the Ember dataset (details can be found here). Each sample is represented as a **2381** feature vector, along with its label (benign or malicious) and malware family if it’s malicious.

Further details can be found in paper “BODMAS: An Open Dataset for Learning based Temporal Analysis of PE Malware” [PDF], Deep Learing and Security Workshop 2021 (co-located with IEEE Security and Privacy 2021).
