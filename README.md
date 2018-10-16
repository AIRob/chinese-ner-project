# chinese-ner-project
pytorch tutorial (https://pytorch.org/tutorials/beginner/nlp/advanced_tutorial.html#advanced-making-dynamic-decisions-and-the-bi-lstm-crf)
中文实体识别 根据官网Pytorch BiLSTM+CRF将CPU版改成GPU版

# You need 
* [Pytorch BiSLTM+CRF Demo](https://pytorch.org/tutorials/beginner/nlp/advanced_tutorial.html#advanced-making-dynamic-decisions-and-the-bi-lstm-crf)
* [Python3](https://www.python.org/)
* [PyTorch](https://pytorch.org/docs/stable/index.html)

# BILSTM CRF 

* [Pytorch BiSLTM+CRF Demo]  GPU Demo  
cd ./pytorch/demo  
python bilstm_crf_gpu.py  

* [data]  
data文件夹中有玻森数据(https://bosonnlp.com),boson数据集有6种实体类型

* [run]  
cd data/boson  
python data_util.py  
cd chinese-ner-boson_test  
python train.py  

# REFERENCE 
* [pytorch tutorial](https://pytorch.org/tutorials/beginner/nlp/advanced_tutorial.html#advanced-making-dynamic-decisions-and-the-bi-lstm-crf)
* [ChineseNER](https://github.com/buppt/ChineseNER)
https://github.com/buppt/ChineseNER
