# README

Code repository for Laura Moset Estruch's final Master's Thesis titled "Using Context Variation Indexes for the Detection of Semantic Neologisms" for the Master in Theoretical and Applied Linguistics in Universitat Pompeu Fabra in 2023-24.

### Requirements

The code is written using Python 3.10 in Colab's version published on 2024-02-21. Thus, the author recommends also using Colab for easier and better performance.
You can access the original Colab with this [link](https://colab.research.google.com/drive/1IGtG79BJIETc1KqHh1XNQyW8jAcTVk6Z?usp=sharing). Another option would be using the .ipynb file provided. Or you can use the .py files to run the program on your own computer. Below are stated the packages required and the versions used in the original.

Packages required:
* Downloading the datasets:
   * gdown== 4.7.3
   * os
   * zipfile
   * tqdm
* Preprocessing and tokenization:
   * csv==1.0
   * re==2.2.1
   * spacy==3.7.4
      * spaCy trained pipeline: es_core_news_lg (Spanish) & ca_core_news_lg (Catalan)
* Counting frequency:
   * collections
   * pandas
   * numpy
   * math
* Creating plots:
   * nltk
   * gensim
   * plt
   * TSNE
   * PCA

### Data attribution
The Spanish data was obtained using corpora created by the Real Academia Española: [CREA](https://www.rae.es/crea-anotado/) and [CORPES](https://www.rae.es/corpes/). And the Catalan was obtained from Institut d'Estudis Catalans' [CTILC](https://ctilc.iec.cat/scripts/IniPresentacio.asp).
The .txt and .xlsx files are automatically downloaded when the code is run using _gdown_ in Colab or using the _download\_files.py_ file. 
>[!NOTE]
>If there is any problem with the download, please feel free to contact the author at laura.moset01@estudiant.upf.edu.
