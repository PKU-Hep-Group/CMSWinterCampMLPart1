# CMS China 冬令营机器学习教程第一部分

本仓库是为CMS China冬令营的机器学习教程的第一部分准备的相关材料。讲义内容以`Jupyter Notebook`写成。

## 代码使用（基于PKU集群的`JupyterHub`服务）

1. 首先登录集群，将代码文件复制到自己的主目录`~`下:
 ```bash
cp -r /data/pubfs/pku_visitor/public_write/ML_tutorial_1stpart ~
# or
git clone https://github.com/PKU-Hep-Group/CMSWinterCampMLPart1 ~
 ```
 2. 而后打开JupyterHub服务（参见腾讯文档），进入`ML_tutorial_1stpart`目录
 3. 执行`ipynb`文件，注意应选择`wintercamp_ml`环境
 4. 对于使用清华计算集群的同学，也请选择相应的环境。
 
## 代码使用（单独的环境搭建）

 1. 本仓库中的代码原则上都可以在自己的机器上执行，不过需要安装相应的程序包。如果使用`conda`进行环境管理，可以参考下面的环境设置：
 ```
     conda create -n <env_name> -c conda-forge xgboost graphviz dtreeviz[xgboost] scipy scikit-learn mplhep uproot jupyterlab# 用到的包
 ```
 2. 启用环境后，可以使用利用jupyterlab执行相应的`ipynb`文件
 