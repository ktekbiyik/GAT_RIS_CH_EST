
# Graph Attention Networks for Channel Estimation in RIS-assisted Communications

This repository contains the source code for the research article titled "Graph Attention Networks for Channel Estimation in RIS-assisted Satellite IoT Communications" published in https://arxiv.org/abs/2104.00735.



Note that this repository includes a simple form of source codes to allow users to run the project on Google Colab with less effort. 

## Getting Started
To run the code, you will need to have a folder structure given below on your Google Drive:
```
  .
  ├── gcn.ipynb
  ├── gat.ipynb
  ├── train_data
  ├── test_data
  └── results/
      ├── gcn/
      │   ├── channel_est/
      │   ├── loss/
      │   └── K/
      │       └── loss/
      └── gat/
          ├── channel_est/
          ├── loss/
          └── K/
              └── loss/
 ```

## Datasets

Datasets can be accessed over IEEE Dataport via https://ieee-dataport.org/documents/dataset-channel-estimation-ris-assisted-satellite-iot-communications

## License 

This project is licensed under [the MIT License](https://choosealicense.com/licenses/mit/).
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

## Citation

If you find this code useful in your research, please consider citing:

    @article{tekbiyik2022graph,
	Author = {Kürşat Tekbıyık and Güneş Karabulut Kurt and Ali Rıza Ekti and Halim Yanikomeroglu},
	Title = {Graph attention networks for channel estimation in RIS-assisted satellite IoT communications},
	Journal  = {arXiv preprint arXiv:2104.00735},
    url = {(https://arxiv.org/abs/2104.00735)}
	Year = {2022}
    }

