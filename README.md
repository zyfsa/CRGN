# CRGN
Deep Relation Reasoning for Cross-Modal Retrieval<br/>
This code is implemented by pytorch.<br/>
The meaning of file and dir:<br/>
final_CRGN and final_CRGN_f30k is related to MSCOCO and Flickr30K datasets, respectively.
runs：save model and log <br/>
data.py：process data<br/>
evaluation.py，evaluation_zyf.py：evaluating model performance on Recall<br/>
model.py，model_zyf.py：network structure<br/>
test.py：test model <br/>
train.py：train model  <br/>
vocab.py：生成词汇表 <br/>
How to train：python train.py --max_violation<br/>
How to test：python test.py<br/>
