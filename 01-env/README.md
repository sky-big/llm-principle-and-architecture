# 开发运行环境准备

## 1、安装conda

mac上安装命令参考：
```
# brew install --cask miniconda
```

其它linux、windows网上搜索安装方法即可。

## 2、创建环境

(1)、通过conda建独立的python环境

```
# conda create --name my-llm-env python=3.9
```

(2)、进入创建的环境

```
# conda activate my-llm-env
// 验证环境
# pip install --upgrade pip
```

## 3、安装依赖

安装依赖包
```
# pip install -r requirements.txt
```