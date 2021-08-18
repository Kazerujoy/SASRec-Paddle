 ## 本项目为AISTUDIO-飞浆论文复现赛 paddle框架复现Self-Attentive Sequential Recommendation 
 论文： https://arxiv.org/pdf/1808.09781v1.pdf 
 
 数据集： https://grouplens.org/datasets/movielens
 
 要求： Hit Rate@10(Recall@10; Precision@10) andNDCG@10

paddle项目地址： https://aistudio.baidu.com/aistudio/projectdetail/2279989

结果： 使用 原文中结构和参数，在ml-1m数据集上训练601 epoch in 1021s average: 1.7s/epoch ，准确率：NDCG@10: 0.5912, HR@10: 0.8315 符合原文结果，模型参数保存在ml-1m文件夹中

![11111](https://user-images.githubusercontent.com/41670588/129905810-181efa9d-cf36-4054-b0a1-e574970a26f6.png)

