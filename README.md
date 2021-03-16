# Tentcent-Word2Vec

说明: 使用腾讯开源的向量搭建的词向量API服务。


## 1. virtualenv 环境搭建


安装 virtualenv

```python
pip3 install virtualenv
```


```python
virtualenv -p python3 w2v_venv
```
进入 virtualenv

```python
source w2v_venv/bin/activate
```

## 2. 安装依赖

安装依赖:

```
pip3 install -r requirements.txt
```

## 3. 启动脚本

```python
python3 w2v.py --model /Users/pan/Desktop/Tencent_AILab_ChineseEmbedding/TencentMin.txt
```






