# Lib2Desc-Dataset

The datasets proposed in ***Lib2Desc: Automatic generation of security-centric Android app descriptions using third-party libraries*** paper are published in this repository. 

**DATASETS**

**TPL-Dataset**: 

   This is a structured dataset including information about 1900 Android third-party libraries.
   
   - TPL_category_textual-description.csv
   
       It includes the name, category, general textual description of third-party libraries(TPL).
   - TPL_textual_features.csv
   
        It includes rhe name and textual feature vector extracted from the general textual description of TPLs. 
   - TPL_API_features.csv
   
        It includes the name and API feature vector obtained from static analysis of TPLs.
        
**AAPI Dataset**:
    
   This dataset consists of two parts codes of Android API calls and Javadoc comment of the APIs extracted from original Android API documentation. The dataset is split in train, validation, and test sets. 
   
   - code.csv
   
     It includes the Android API calls preprocessed as mentioned in the paper.
     
   - javadoc.csv
     
     It includes the matching API descriptions for the API calls. This textual information is preprocessed as mentioned in the paper.
   
The repository hierarchy:
```
├── AAPI-Dataset
│   ├── dev
│   │   ├── code.csv
│   │   └── javadoc.csv
│   ├── test
│   │   ├── code.csv
│   │   └── javadoc.csv
│   └── train
│       ├── code.csv
│       └── javadoc.csv
├── LICENSE
├── README.md
└── TPL-Dataset
    ├── TPL_API_features.csv
    ├── TPL_category_textual-description.csv
    └── TPL_textual_features.csv
```
---
**Usage**

The datasets can be used for developing machine learning, deep learning, NLG, NLP models. These datasets are constructed and preprocessed for developing classification, NLG, and transformer based seq2seq models.

**Related Sections**

You can find more information about dataset collection, preprocessing and models in the following sections.
```
Section 3 Data Collection
Section 3.1 Collecting Third-Party Libraries
Section 4.3.3 Datasets
```
---
Contact

Author: Beyza Cevik

Contact: beyzaccevik@gmail.com