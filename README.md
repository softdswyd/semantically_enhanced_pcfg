# Instruction for corpora used in SE#PCFG

## corpora

In our paper, we used 43 different semantic factor types to implement our SE#PCFG.

As shown in Table III, these 43 semantic factor types can be categorized into 22 groups, with 8 of them being composed of external corpora (English related corpora, Germany related corpora, French related corpora, locations, Western names, Wiki name entity, Urban dictionaries, acronyms of Chinese names). In this document, we will provide a detailed explanation of the collection methods for these 8 groups of corpora.

It is worth noting that we have listed the acquisition URLs for all external corpora. This approach offers two main benefits to readers:

- Readers can access the latest corpora (as some corpora, such as dewiktionary, Geonames etc., are continuously being updated).
- Readers can freely process the source data according to their own needs, within the bounds of the licensing permissions granted by each respective corpus.

Additionally, to help readers better understand how we processed these external corpora and applied them to SE#PCFG, we carefully reviewed the licensing rules used by these external corpora. Under the premise of clear authorization, we provided the actual versions used after processing the source data. These contents are located in the folder named 'corpora'. Please note that these contents are based on earlier versions of the corpora, so there may be discrepancies with the current latest versions. However, our experimental results show that these corpora still perform commendably.

### English related corpora

- Brown Corpus
https://raw.githubusercontent.com/nltk/nltk_data/gh-pages/packages/corpora/brown.zip
- WordNet 
https://raw.githubusercontent.com/nltk/nltk_data/gh-pages/packages/corpora/wordnet.zip
- Web Text Corpus
https://raw.githubusercontent.com/nltk/nltk_data/gh-pages/packages/corpora/webtext.zip

### Germany related corpora

- dewiktionary
https://dumps.wikimedia.org/dewiktionary/

  - Under [GNU Free Documentation License (GFDL)](https://www.gnu.org/licenses/fdl-1.3.html) and [Creative Commons Attribution-Share-Alike 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/)

### French related corpora

- frwiktionary
https://dumps.wikimedia.org/frwiktionary/

  - Under [GNU Free Documentation License (GFDL)](https://www.gnu.org/licenses/fdl-1.3.html) and [Creative Commons Attribution-Share-Alike 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/)

### Locations

- Geonames
https://download.geonames.org/export/dump/admin1CodesASCII.txt

  - Under a [Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/#ref-appropriate-credit)

### Western names

- Popular Baby Names
https://www.ssa.gov/oact/babynames/limits.html

### Wiki name entity

- enwiki
https://dumps.wikimedia.org/enwiki/

  - Under [GNU Free Documentation License (GFDL)](https://www.gnu.org/licenses/fdl-1.3.html) and [Creative Commons Attribution-Share-Alike 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/)

### Urban dictionary

- Urban dictionary
https://www.urbandictionary.com/

### Acronyms of Chinese names

- Top 1000 common Chinese names
https://download.csdn.net/download/u011827798/9999625

## Paper

Our paper is available at https://arxiv.org/abs/2306.06824

## Citation

Please kindly cite our paper if you find our materials helpful!

```
@ARTICLE{wang2025sepcfg,
  author={Wang, Yangde and Qiu, Weidong and Tang, Peng and Tian, Hao and Li, Shujun},
  journal={IEEE Transactions on Dependable and Secure Computing}, 
  title={SE#PCFG: Semantically Enhanced PCFG for Password Analysis and Cracking}, 
  year={2025},
  volume={},
  number={},
  pages={1-14},
  doi={10.1109/TDSC.2025.3547773}}
```