# Graph Neural network for Fault Diagnosis
# 基于图神经网络的故障诊断

Date: 2022/9/28 23:46

Author: Tan Qiyu

Citation:[1]谭启瑜,马萍,张宏立.基于图卷积神经网络的滚动轴承故障诊断[J].噪声与振动控制,2023,43(06):101-108+116.
               [2]谭启瑜,马萍,张宏立等.基于图注意力网络的风力发电机齿轮箱故障诊断[J].太阳能学报,2024,45(01):265-274.

E-mail：929796695@qq.com

Home: https://github.com/Tan-Qiyu

Dataset Download Link：https://github.com/Tan-Qiyu/Mechanical_Fault_Diagnosis_Dataset

Instructions:
First, the implement is include CWRU、SEU、XJTU、JNU、MFPT、UoC、DC all 7 public fault datasets.
Secondly, in order to compare the effects of different parameters on the experiment more conveniently, almost every parameter is optional，and these changeable parameters include dataset, sampling method, graph structure type, network model, noise, input type, number of nodes, etc. (see code for details).
Finally, you can choose to use confusion matrix and tsne to visualize all the results and the features of each layer of network respectively.

注：Please setting 图神经网络 as root source when you run code.
