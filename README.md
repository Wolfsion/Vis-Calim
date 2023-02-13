# 绘图说明
## 图1 vgg16-cifar10 度量分布箱线图
对应数据为`h-v-layer.csv`，图例为`sub-box.ong`
数据文件需要调用pandas.read_csv()读取，数据内容为度量值-所处卷积层-算法类型。

## 图2 vgg16-cifar10 精度恢复图
对应数据为`acc_restore_path.csv`，图例为`fine-tuning.png`
数据内容为数据内容为精度-轮次-算法类型。


## 图3 resnet110-cifar100 精度恢复图
对应数据为`acc_restore_path_cifar100.csv`，图例，数据文件读取和内容同图2。


## 图4-a resnet56-cifar10 随机数据剪枝精度恢复图 图4-b mobilnetv2-cifar100 随机数据剪枝精度恢复图 *
子图a对应数据为`acc_random_restore_path.csv`，图例为`random.png`，展示纵轴幅度拉大。
数据内容为数据内容为精度-轮次-算法类型。

子图b对应数据为`acc_random_restore_path_cifar100.csv`，图例，数据文件读取和内容同图4-a。


## 图5 vgg16-cifar10-Dirichlet Non-IID划分联邦学习精度图
对应数据为`vgg16-cifar10-hetero-acc.csv`，图例为`vch-Acc-federated.png`
数据文件需要调用pandas.read_csv()读取，数据内容为精度-联邦轮次-算法类型。

## 图6 vgg16-cifar10-Shards Non-IID划分联邦学习精度图
对应数据为`vgg16-cifar10-shards-acc.csv`，图例，数据文件读取和内容同图2。

## 图7 ucm-mobilenetv2-Dirichlet Non-IID划分联邦学习精度图*
对应数据为`mobilenetv2-ucm-hetero-acc.csv`，图例，数据文件读取和内容同图2。

## 图8 ucm-mobilenetv2-Shards Non-IID划分联邦学习精度图*
对应数据为`mobilenetv2-ucm-shards-acc.csv`，图例，数据文件读取和内容同图2。
