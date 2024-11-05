This repository is the Python implementation for the CSCWD 2024 accepted paper:
> Wanjun Chen, QiqiChen, Jiexun Shen, Guosheng Kang*, Jianxun Liu, Buqing Cao, Lihong Zhang. Interactive Web API Recommendation via Exploring Mashup-API Interactions and Functional Description Documents. International Conference on Computer Supported Cooperative Work in Design. IEEE Computer Society, pp. 121-126, 2024.

## Requirements

- LightGCN -- The code has been tested running under Python 3.6.5. The required packages are as follows:
  * tensorflow == 2.10.0
  * numpy == 1.22.4
  * scipy == 1.9.1
  * sklearn == 1.1.2
  * cython == 0.29.32
- BERT4WS -- The code has been tested running under Python 3.8. The required packages are as follows:
  - transformers == 4.10.3
  - pandas == 1.2.4
  - pytorch（If you are using a GPU, the version needs to be compatible with the CUDA version.）
  - numpy == 1.21.0
- SANFM -- The code has been tested running under Python 3.8. The required packages are as follows:
  - pytorch（If you are using a GPU, the version needs to be compatible with the CUDA version.）
  - pandas == 1.3.3
  - scikit-learn == 0.24.2

You can execute the code directly according to the readme.md of each module, use Bert and LightGCN to get the representation and then input it into SANFM.
