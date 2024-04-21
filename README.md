# DS4002Project3
Project 3 of the DS4002 Project Course
## Software and Platforms

### Software
    - Python
    - Jupyter Notebook

### Packages

    - keras
    - matplotlib
    - PIL
    - tensorflow
    - math
    - numpy
    - os
    - zipfile

### Platforms

    - MacOS
    - Google Colab


## Documentation Map
```console
.
├── Data
│  ├── cats-DS4002.zip
│  ├── dogs-DS4002.zip
│  └── Data Appendix.pdf
├── Output
│  ├── ModelLossVis.png
│  ├── plan vis.jpg
│  ├── Sample cats.png
│  ├── Train-Test Split.png
│  └── Sample dogs.png
├── LICENSE
├── README.md
└── Script
   └── model.ipynb
```


## Instructions for Reproducing Results

The python notebook file `model.ipynb`  will clone this repo. Download any necessary packages and run the `model.ipynb` file. Executing each code block in order will reproduce these results including all visulaizations found in the `Output` folder. The file works by first loading and unzipping the two data files. Then using Keras, the files are loaded into workable image dataset data types. Then the model is specified to the given data and tested. Comments throughout the file also help explain the process.
