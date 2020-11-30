首先应搭建深度学习的平台，用到的有Anaconda、Pycharm、cuda、cudnn、VS2015等。

搭建平台之前，首先应确定自己的电脑有NVIDIA显卡，我的显卡是GeForce MX250

1.  安装Anaconda

在Anaconda的官网，下载对应python版本和对应电脑位数的Anaconda，我这里为python3.6，下载了Anaconda3.5.1的安装包，然后进行环境配置，检测是否在Anaconda里成功下载了python3.6

1.  安装IDE：Pycharm

在Pycharm的官网下载，选择Community版本，然后下载完成后根据自己的需要去选择一些功能

3.安装VS2015，（VS2015要安装在cuda之前，否则无法生成配置文件）

4.在Anaconda
Navigator中创建虚拟环境，然后在控制台中选择对应的环境，先下载对应版本的tensorflow。因为我的电脑显卡是GeForce
MX250，不支持GPU并行计算，因此我需要安装cpu版的tensorflow，之后下载源代码中需要的第三方库

keras 2.2.4

PyQt5 5.11.3

pandas 0.24.2

scikit-learn 0.21.2

imutils 0.5.2

opencv-python 4.10.25

注意：需要额外导入scikit-image，版本默认

1.  安装CUDA9.0

在官网搜索对应版本的CUDA进行下载，在命令提示符中验证下载成功后，需要在系统环境变量Path中添加cuda的相应路径

1.  安装cudnn7.6.5

在官网搜索对应版本的cudnn进行下载，下载后为zip压缩包解压后包含三个文件夹bin，include，lib。将文件夹中内容分别放入cuda安装目录的bin，include，lib中。

至此，平台搭建的前期工作已经完成，将源代码导入Pycharm之后，运行runMain.py，会出现如图所示的界面，可以对人的面部表情进行识别。

![](media/0b7ae52a9c77592c426258e58e32c202.jpeg)
