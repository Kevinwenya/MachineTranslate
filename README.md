# MachineTranslate
机器翻译--从原理到实现
### 目标: 训练一个端到端的英语到法语的翻译模型
### 数据
    训练数据： training-giga-fren.tar 下载地址
    验证数据： dev-v2.tgz 下载地址
    在脚本data_utils.py中调用相关函数会自动下载上述数据，
    但是如果训练的机器没有网络或者下载很慢，可以单独下载之后再训练。
###### 文件行数为2千万行，每个文件都是一行一个句子：
    22520376 giga-fren.release2.fixed.en
    22520376 giga-fren.release2.fixed.fr
    
    
##### https://github.com/tensorflow/nmt
##### https://www.youyong.top/article/1159672382461
