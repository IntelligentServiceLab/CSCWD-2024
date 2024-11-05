This repository is the Python implementation for the CSCWD 2024 accepted paper:
> Wanjun Chen, QiqiChen, Jiexun Shen, Guosheng Kang*, Jianxun Liu, Buqing Cao, Lihong Zhang. Interactive Web API Recommendation via Exploring Mashup-API Interactions and Functional Description Documents. International Conference on Computer Supported Cooperative Work in Design. IEEE Computer Society, pp. 121-126, 2024.

## Requirements

- LightGCN -- The code has been tested running under Python 3.6.5. The required packages are as follows:
  * tensorflow 
  * numpy
  * scipy 
  * sklearn 
  * cython
- BERT4WS -- The code has been tested running under Python 3.8. The required packages are as follows:
  - transformers
  - pandas
  - torch
  - numpy
- SANFM -- The code has been tested running under Python 3.8. The required packages are as follows:
  - pytorch
  - pandas
  - scikit-learn

You can execute the code directly according to the readme.md of each module, use Bert and LightGCN to get the representation and then input it into SANFM.
