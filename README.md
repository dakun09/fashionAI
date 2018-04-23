# fashionAI
主要环境依赖:caffe+py2.7

训练步骤说明:
1.把图像转成lmdb格式。
2.写好每个模型的prototxt、solver及train.sh。
3.运行训练脚本train.sh。

测试步骤说明:
1.设置好预测参数。
2.运行predict.py脚本，输出预测结果。
3.针对每个属性分别生成txt文件，然后改成csv格式即可。
