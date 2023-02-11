# geolocation-preprocess
pre-process pipeline for geolocation annotation task

This repository contains the functions for the pre-process of the documents needed for the geolocation annotation task.
It contains:
- `usage_example.ipynb`: example notebook that shows the pre-processing pipeline.  
This notebook pre-process a text document and outputs a .json file supported by Label Studio NER annotation tool (https://labelstud.io/).   
The original text is created with TextFromFile method from deep_parser package (https://github.com/the-deep/deepex).   
This script computes location predictions from different NER models, and add them as pre-annotations to the Label Studio output.   
Pre-annotations will be uploaded on Label Studio and subject to human revision.
- `src`: functions used in the notebook
- `data`: contains .txt input files to be processed and output .json to be passed to Label Studio
- `requirements`: packages to be installed
