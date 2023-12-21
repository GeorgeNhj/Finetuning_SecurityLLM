# Finetuning_SecurityLLM
This is a computer security course program. 
## dataset
The dataset is based on [iot-23-datasets](https://huggingface.co/datasets/19kmunz/iot-23-preprocessed-minimumcolumns):Aposemat IoT-23 - 具有恶意和良性物联网网络流量的标记数据集
![image](https://github.com/GeorgeNhj/Finetuning_SecurityLLM/assets/110888894/ba606970-71db-467a-86c9-8ddac2fcfa2c)
## base model
[BERT](https://huggingface.co/bert-base-uncased)
## achievements
The model file has been published on [hugging face](https://huggingface.co/GeorgeNhj/BERT_based_My_SecurityLLM) platform
By using Inference API, you can input a string of network flow data, and the model will tell you whether it has malicious intent
![image](https://github.com/GeorgeNhj/Finetuning_SecurityLLM/assets/110888894/0f0a6bc5-56d9-4a0f-a243-67b695ce00cf)
Or you can load my model in pytorch via the **.from_pretrained** function
