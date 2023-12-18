# SJTU STAT6005（研）/MATH4704 课程大作业代码实现

## 说明

本项目适用于熊老师及其布朗运动课程大作业，附代码说明与结果分析

## 程序依赖

项目基于`python`实现，可以使用任意支持`Jupyter Notebook`的`Python 3.x`版本运行

| 库           | 版本（非必须） |
| ------------ | -------------- |
| `numpy`      | 1.24.1         |
| `matplotlib` | 3.7.1          |

## 运行说明

以下说明适用于不熟悉Python环境的用户，建议最好在Conda环境下运行或测试。

1. 获取Python

通过访问以下网址下载适用于当前平台的Python安装包（不推荐3.11以上版本）

```
https://www.python.org/downloads/
```

如果你安装了Conda，也可以

```bash
conda create -n ENV_NAME python==3.8 numpy matplotlib
```

2. 安装运行依赖

如果使用Conda建立环境可以跳过这一步骤

在命令行中运行

```bash
python3 -m pip install jupyter notebook numpy matplotlib
```

3. 运行

在当前程序目录下打开（对应Conda环境的）命令行并输入

```bash
jupyter notebook
```

在打开的网页中打开本文件并按照提示运行。生成的图像会保存在当前目录下的`/plot`目录下