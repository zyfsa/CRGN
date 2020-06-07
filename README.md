# CRGN
Deep Relation Reasoning for Cross-Modal Retrieval

代码是用pytorch实现的

runs文件夹：保存模型和日志文件
data.py：处理数据
evaluation.py，evaluation_zyf.py：评估模型性能Recall
model.py，model_zyf.py：模型网络结构文件
test.py：测试模型
train.py：训练模型
vocab.py：生成词汇表

训练：python train.py --max_violation
测试：python test.py
