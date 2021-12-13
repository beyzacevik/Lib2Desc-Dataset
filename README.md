# Lib2Desc-Dataset

The datasets proposed in in *Lib2Desc: Automatic generation of security-centric Androidapp descriptions using third-party libraries* paper are published in this repository. 

TPL-Dataset: 
   - TPL_category_textual-description.csv
   
       It includes name, category, general textual description of third-party libraries(TPL).
   - TPL_textual_features.csv
   
        It includes name and textual feature vector extracted from the general textual description of TPLs. 
   - TPL_API_features.csv
   
        It includes name and API feature vector obtained from static analysis of TPLs. 
   
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
 
