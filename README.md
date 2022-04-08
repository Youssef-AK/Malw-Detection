## PE-Malware Detection based on BODMAS
![4b5f408ae3a755878ae40be21fd7fa79](https://user-images.githubusercontent.com/40705538/162392756-9881b366-a4c2-42c8-8dd5-744bcba3c4ae.jpg)
### + PE-Malware Classifier
![advanced-malware-protection](https://user-images.githubusercontent.com/40705538/162392884-4d2cc37f-a37b-4d58-9bec-fd5c8433705d.jpg)

BODMAS is short for Blue Hexagon Open Dataset for Malware Analysis. Dataset containing timestamped malware samples and well-curated family information for research purposes.
The BODMAS dataset contains 57,293 malware samples and 77,142 benign samples collected from August 2019 to September 2020, with carefully curated family information 
(**581** families).

The feature vectors extracted by using the [LIEF](https://pypi.org/project/lief/?msclkid=faebb2a1a95811ec8b6a8198d5f1de0b) project (version 0.9.0), the same as the Ember dataset (details can be found [here](https://github.com/elastic/ember/blob/master/ember/features.py)). Each sample is represented as a **2381** feature vector, along with its label (benign or malicious) and malware family if it’s malicious.

## Most Common Family in BODMAS 
![Most_Common_Family](https://user-images.githubusercontent.com/40705538/159366148-251ba6c2-4b9e-4ae2-aa52-fd0b1a600814.png)
