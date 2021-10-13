<!-- markdownlint-disable -->
<h1 align="center">
    python机器学习资源与工具库大全
    <br>
</h1>

<p align="center">
    <strong>python机器学习开源工具库资源大全，划分子版块并梳理排行，每周自动更新</strong>
</p>

<p align="center">
    <a href="#Contents" title="项目数量"><img src="https://img.shields.io/badge/projects-820-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="欢迎完善"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/HanXinzi-AI/awesome-python-machine-learning-resources/releases" title="最近更新"><img src="https://img.shields.io/github/release-date/HanXinzi-AI/awesome-python-machine-learning-resources?color=green&label=updated"></a>
</p>

本资源清单包含820个python机器学习相关的开源工具资源，这些热门工具总共分成32个不同的子板块，这些项目目前在github上已经收到3M个点赞。所有的工具资源每周会自动从GitHub和工具维护平台采集信息，并更新排行展示。本清单参考[best-of模板](https://github.com/best-of-lists/best-of)完成，内容参考了[awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)，欢迎大家提PR丰富本清单。
## 目录

- [机器学习框架](#机器学习框架) _54 个项目_
- [数据可视化](#数据可视化) _49 个项目_
- [文本数据和NLP](#文本数据和NLP) _82 个项目_
- [图像数据与CV](#图像数据与CV) _49 个项目_
- [图数据处理](#图数据处理) _29 个项目_
- [音频处理](#音频处理) _22 个项目_
- [地理Geo处理](#地理Geo处理) _22 个项目_
- [金融数据处理](#金融数据处理) _23 个项目_
- [时间序列](#时间序列) _20 个项目_
- [医疗领域](#医疗领域) _19 个项目_
- [光学字符识别OCR](#光学字符识别OCR) _11 个项目_
- [数据容器和结构](#数据容器和结构) _28 个项目_
- [数据读写与提取](#数据读写与提取) _23 个项目_
- [网页抓取和爬虫](#网页抓取和爬虫) _1 个项目_
- [数据管道和流处理](#数据管道和流处理) _36 个项目_
- [分布式机器学习](#分布式机器学习) _26 个项目_
- [超参数优化和AutoML](#超参数优化和AutoML) _45 个项目_
- [强化学习](#强化学习) _19 个项目_
- [推荐系统](#推荐系统) _13 个项目_
- [隐私机器学习](#隐私机器学习) _6 个项目_
- [工作流程和实验跟踪](#工作流程和实验跟踪) _35 个项目_
- [模型序列化和转换](#模型序列化和转换) _11 个项目_
- [模型的可解释性](#模型的可解释性) _46 个项目_
- [向量相似度搜索（ANN）](#向量相似度搜索（ANN）) _12 个项目_
- [概率统计](#概率统计) _21 个项目_
- [对抗学习与鲁棒性](#对抗学习与鲁棒性) _7 个项目_
- [GPU实用程序](#GPU实用程序) _18 个项目_
- [Tensorflow实用程序](#Tensorflow实用程序) _13 个项目_
- [Sklearn实用程序](#Sklearn实用程序) _17 个项目_
- [Pytorch实用程序](#Pytorch实用程序) _27 个项目_
- [数据库客户端](#数据库客户端) _1 个项目_
- [中文自然语言处理](#中文自然语言处理) _2 个项目_
- [Others](#Others) _33 个项目_

## 图标解释
- 🥇🥈🥉&nbsp; 综合项目质量分
- ⭐️&nbsp; github上star的数量
- 🐣&nbsp; 小于6个月的新项目
- 💤&nbsp; 非活跃项目(6个月未更新)
- 💀&nbsp; 沉寂项目(12个月未更新)
- 📈📉&nbsp; 项目趋势(向上or向下)
- ➕&nbsp; 最近添加的项目
- ❗️&nbsp; 警告(例如 项目没有license)
- 👨‍💻&nbsp; 项目的开发贡献者数量
- 🔀&nbsp; 项目被fork的数量
- 📋&nbsp; 项目issue的数量
- ⏱️&nbsp; 项目包上次更新时间
- 📥&nbsp; 工具库被下载次数
- 📦&nbsp; 项目依赖的工具库数量
- <img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13">&nbsp; Tensorflow相关项目
- <img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13">&nbsp; Sklearn相关项目
- <img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13">&nbsp; pytorch相关项目
- <img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13">&nbsp; MxNet相关项目
- <img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13">&nbsp; Apache Spark相关项目
- <img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13">&nbsp; Jupyter相关项目
- <img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13">&nbsp; PaddlePaddle相关项目
- <img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13">&nbsp; Pandas相关项目

<br>

## 机器学习框架

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_通用机器学习和深度学习框架。_

<details><summary><b><a href="https://github.com/tensorflow/tensorflow">Tensorflow</a></b> (🥇44 ·  ⭐ 160K) - 适用于所有人的开源机器学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensorflow) (👨‍💻 3.8K · 🔀 69K · 📦 160K · 📋 33K - 8% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/tensorflow/tensorflow
	```
- [PyPi](https://pypi.org/project/tensorflow) (📥 12M / month):
	```
	pip install tensorflow
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow) (📥 2.8M · ⏱️ 25.09.2021):
	```
	conda install -c conda-forge tensorflow
	```
- [Docker Hub](https://hub.docker.com/r/tensorflow/tensorflow) (📥 60M · ⭐ 2K · ⏱️ 12.10.2021):
	```
	docker pull tensorflow/tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/xgboost">XGBoost</a></b> (🥇37 ·  ⭐ 22K) - 可扩展，高效和分布式梯度增强（GBDT，GBRT等）的boosting工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/xgboost) (👨‍💻 540 · 🔀 7.7K · 📥 3.1K · 📦 22K · 📋 4.2K - 6% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/dmlc/xgboost
	```
- [PyPi](https://pypi.org/project/xgboost) (📥 7.9M / month):
	```
	pip install xgboost
	```
- [Conda](https://anaconda.org/conda-forge/xgboost) (📥 2M · ⏱️ 17.09.2021):
	```
	conda install -c conda-forge xgboost
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn/scikit-learn">scikit-learn</a></b> (🥇36 ·  ⭐ 48K) - scikit-learn：基于Python的机器学习工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn/scikit-learn) (👨‍💻 2.4K · 🔀 21K · 📥 740 · 📦 270K · 📋 8.8K - 19% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/scikit-learn/scikit-learn
	```
- [PyPi](https://pypi.org/project/scikit-learn) (📥 23M / month):
	```
	pip install scikit-learn
	```
- [Conda](https://anaconda.org/conda-forge/scikit-learn) (📥 9.8M · ⏱️ 26.09.2021):
	```
	conda install -c conda-forge scikit-learn
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/LightGBM">LightGBM</a></b> (🥇36 ·  ⭐ 13K) - 快速，分布式，高性能梯度提升（GBT，GBDT，GBRT等）的boosting工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/LightGBM) (👨‍💻 240 · 🔀 3.3K · 📥 120K · 📦 9.3K · 📋 2.4K - 4% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/microsoft/LightGBM
	```
- [PyPi](https://pypi.org/project/lightgbm) (📥 15M / month):
	```
	pip install lightgbm
	```
- [Conda](https://anaconda.org/conda-forge/lightgbm) (📥 750K · ⏱️ 20.04.2021):
	```
	conda install -c conda-forge lightgbm
	```
</details>
<details><summary><b><a href="https://github.com/PyTorchLightning/pytorch-lightning">pytorch-lightning</a></b> (🥇35 ·  ⭐ 16K) - 轻巧而具备高性能的PyTorch上层封装工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyTorchLightning/pytorch-lightning) (👨‍💻 550 · 🔀 1.9K · 📥 4.4K · 📦 5K · 📋 4K - 7% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/PyTorchLightning/pytorch-lightning
	```
- [PyPi](https://pypi.org/project/pytorch-lightning) (📥 650K / month):
	```
	pip install pytorch-lightning
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-lightning) (📥 300K · ⏱️ 30.09.2021):
	```
	conda install -c conda-forge pytorch-lightning
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/pytorch">PyTorch</a></b> (🥇33 ·  ⭐ 51K) - 具有强大GPU的Python中的张量和动态神经网络构建工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/pytorch) (👨‍💻 2.9K · 🔀 14K · 📋 23K - 30% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/pytorch/pytorch
	```
- [PyPi](https://pypi.org/project/torch) (📥 5.2M / month):
	```
	pip install torch
	```
- [Conda](https://anaconda.org/pytorch/pytorch) (📥 13M · ⏱️ 20.09.2021):
	```
	conda install -c pytorch pytorch
	```
</details>
<details><summary><b><a href="https://github.com/statsmodels/statsmodels">StatsModels</a></b> (🥇33 ·  ⭐ 6.7K) - Statsmodels：Python中的统计建模和计量经济学工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/statsmodels/statsmodels) (👨‍💻 340 · 🔀 2.2K · 📥 26 · 📦 51K · 📋 4.4K - 45% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/statsmodels/statsmodels
	```
- [PyPi](https://pypi.org/project/statsmodels) (📥 6.2M / month):
	```
	pip install statsmodels
	```
- [Conda](https://anaconda.org/conda-forge/statsmodels) (📥 5M · ⏱️ 03.10.2021):
	```
	conda install -c conda-forge statsmodels
	```
</details>
<details><summary><b><a href="https://github.com/explosion/thinc">Thinc</a></b> (🥈32 ·  ⭐ 2.4K) - 深度学习工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/thinc) (👨‍💻 41 · 🔀 210 · 📦 16K · 📋 110 - 12% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/explosion/thinc
	```
- [PyPi](https://pypi.org/project/thinc) (📥 2.6M / month):
	```
	pip install thinc
	```
- [Conda](https://anaconda.org/conda-forge/thinc) (📥 1.6M · ⏱️ 25.09.2021):
	```
	conda install -c conda-forge thinc
	```
</details>
<details><summary><b><a href="https://github.com/apache/spark">PySpark</a></b> (🥈31 ·  ⭐ 31K) - Apache Spark Python API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/apache/spark) (👨‍💻 2.5K · 🔀 24K · ⏱️ 13.10.2021):

	```
	git clone https://github.com/apache/spark
	```
- [PyPi](https://pypi.org/project/pyspark) (📥 14M / month):
	```
	pip install pyspark
	```
- [Conda](https://anaconda.org/conda-forge/pyspark) (📥 1.3M · ⏱️ 29.05.2021):
	```
	conda install -c conda-forge pyspark
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/Paddle">PaddlePaddle</a></b> (🥈31 ·  ⭐ 17K) - paddlepaddle机器学习与深度学习工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/Paddle) (👨‍💻 650 · 🔀 3.9K · 📥 15K · 📦 71 · 📋 14K - 15% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/PaddlePaddle/Paddle
	```
- [PyPi](https://pypi.org/project/paddlepaddle) (📥 36K / month):
	```
	pip install paddlepaddle
	```
</details>
<details><summary><b><a href="https://github.com/davisking/dlib">dlib</a></b> (🥈31 ·  ⭐ 11K) - 进行现实世界机器学习和数据分析的工具包。<code><a href="https://tldrlegal.com/search?q=BSL-1.0">❗️BSL-1.0</a></code></summary>

- [GitHub](https://github.com/davisking/dlib) (👨‍💻 170 · 🔀 2.5K · 📥 25K · 📦 12K · 📋 2K - 1% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/davisking/dlib
	```
- [PyPi](https://pypi.org/project/dlib) (📥 110K / month):
	```
	pip install dlib
	```
- [Conda](https://anaconda.org/conda-forge/dlib) (📥 360K · ⏱️ 03.04.2021):
	```
	conda install -c conda-forge dlib
	```
</details>
<details><summary><b><a href="https://github.com/Theano/Theano">Theano</a></b> (🥈31 ·  ⭐ 9.5K) - Theano是一个Python神经网络工具库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Theano/Theano) (👨‍💻 380 · 🔀 2.4K · 📦 12K · 📋 2.7K - 21% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/Theano/Theano
	```
- [PyPi](https://pypi.org/project/theano) (📥 230K / month):
	```
	pip install theano
	```
- [Conda](https://anaconda.org/conda-forge/theano) (📥 1.7M · ⏱️ 05.06.2021):
	```
	conda install -c conda-forge theano
	```
</details>
<details><summary><b><a href="https://github.com/chainer/chainer">Chainer</a></b> (🥈31 ·  ⭐ 5.6K) - 灵活的深度学习神经网络框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chainer/chainer) (👨‍💻 320 · 🔀 1.3K · 📦 2.4K · 📋 2K - 0% open · ⏱️ 10.06.2021):

	```
	git clone https://github.com/chainer/chainer
	```
- [PyPi](https://pypi.org/project/chainer) (📥 27K / month):
	```
	pip install chainer
	```
</details>
<details><summary><b><a href="https://github.com/google/jax">jax</a></b> (🥈30 ·  ⭐ 14K) - Python + NumPy程序工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/jax) (👨‍💻 330 · 🔀 1.3K · 📦 2.6K · 📋 2.6K - 28% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/google/jax
	```
- [PyPi](https://pypi.org/project/jax) (📥 760K / month):
	```
	pip install jax
	```
- [Conda](https://anaconda.org/conda-forge/jaxlib) (📥 200K · ⏱️ 13.10.2021):
	```
	conda install -c conda-forge jaxlib
	```
</details>
<details><summary><b><a href="https://github.com/jina-ai/jina">Jina</a></b> (🥈30 ·  ⭐ 12K · 📈) - 在云端构建神经搜索的简便方法库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jina-ai/jina) (👨‍💻 120 · 🔀 1.3K · 📦 150 · 📋 1.1K - 7% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/jina-ai/jina
	```
- [PyPi](https://pypi.org/project/jina) (📥 25K / month):
	```
	pip install jina
	```
- [Docker Hub](https://hub.docker.com/r/jinaai/jina) (📥 900K · ⭐ 5 · ⏱️ 12.10.2021):
	```
	docker pull jinaai/jina
	```
</details>
<details><summary><b><a href="https://github.com/VowpalWabbit/vowpal_wabbit">Vowpal Wabbit</a></b> (🥈30 ·  ⭐ 7.7K) - Vowpal Wabbit是一个推动机器学习的机器学习系统。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/VowpalWabbit/vowpal_wabbit) (👨‍💻 300 · 🔀 1.7K · 📦 170 · 📋 1.1K - 14% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/VowpalWabbit/vowpal_wabbit
	```
- [PyPi](https://pypi.org/project/vowpalwabbit) (📥 26K / month):
	```
	pip install vowpalwabbit
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras">Keras</a></b> (🥈29 ·  ⭐ 53K) - 易上手的深度学习工具库。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras) (👨‍💻 990 · 🔀 18K · 📋 11K - 2% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/keras-team/keras
	```
- [PyPi](https://pypi.org/project/keras) (📥 6M / month):
	```
	pip install keras
	```
- [Conda](https://anaconda.org/conda-forge/keras) (📥 1.9M · ⏱️ 03.09.2021):
	```
	conda install -c conda-forge keras
	```
</details>
<details><summary><b><a href="https://github.com/fastai/fastai">Fastai</a></b> (🥈28 ·  ⭐ 22K) - Fastai深度学习库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/fastai/fastai) (👨‍💻 180 · 🔀 7K · 📋 1.5K - 5% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/fastai/fastai
	```
- [PyPi](https://pypi.org/project/fastai) (📥 310K / month):
	```
	pip install fastai
	```
</details>
<details><summary><b><a href="https://github.com/apache/incubator-mxnet">MXNet</a></b> (🥈28 ·  ⭐ 20K) - 轻巧，灵活的分布式/移动深度学习工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/apache/incubator-mxnet) (👨‍💻 960 · 🔀 6.5K · 📥 24K · 📋 9.4K - 18% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/apache/incubator-mxnet
	```
- [PyPi](https://pypi.org/project/mxnet) (📥 430K / month):
	```
	pip install mxnet
	```
- [Conda](https://anaconda.org/anaconda/mxnet) (📥 6.6K · ⏱️ 29.02.2020):
	```
	conda install -c anaconda mxnet
	```
</details>
<details><summary><b><a href="https://github.com/catboost/catboost">Catboost</a></b> (🥈28 ·  ⭐ 6.1K) - 快速，可扩展，高性能的梯度决策提升工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/catboost/catboost) (👨‍💻 890 · 🔀 880 · 📥 65K · 📋 1.6K - 17% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/catboost/catboost
	```
- [PyPi](https://pypi.org/project/catboost) (📥 2.6M / month):
	```
	pip install catboost
	```
- [Conda](https://anaconda.org/conda-forge/catboost) (📥 830K · ⏱️ 05.08.2021):
	```
	conda install -c conda-forge catboost
	```
</details>
<details><summary><b><a href="https://github.com/tensorpack/tensorpack">tensorpack</a></b> (🥈28 ·  ⭐ 6.1K) - TensorFlow上的神经网络训练接口。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorpack/tensorpack) (👨‍💻 57 · 🔀 1.8K · 📥 130 · 📦 880 · 📋 1.3K - 0% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/tensorpack/tensorpack
	```
- [PyPi](https://pypi.org/project/tensorpack) (📥 17K / month):
	```
	pip install tensorpack
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/sonnet">Sonnet</a></b> (🥈27 ·  ⭐ 9K) - 基于TensorFlow的神经网络库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/sonnet) (👨‍💻 52 · 🔀 1.2K · 📦 670 · 📋 160 - 11% open · ⏱️ 08.09.2021):

	```
	git clone https://github.com/deepmind/sonnet
	```
- [PyPi](https://pypi.org/project/dm-sonnet) (📥 360K / month):
	```
	pip install dm-sonnet
	```
- [Conda](https://anaconda.org/conda-forge/sonnet) (📥 12K · ⏱️ 14.11.2020):
	```
	conda install -c conda-forge sonnet
	```
</details>
<details><summary><b><a href="https://github.com/arogozhnikov/einops">einops</a></b> (🥈27 ·  ⭐ 3.7K) - 重塑了深度学习操作（用于pytorch，tensorflow，jax等）的工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/arogozhnikov/einops) (👨‍💻 12 · 🔀 140 · 📦 1.2K · 📋 79 - 34% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/arogozhnikov/einops
	```
- [PyPi](https://pypi.org/project/einops) (📥 380K / month):
	```
	pip install einops
	```
- [Conda](https://anaconda.org/conda-forge/einops) (📥 7.6K · ⏱️ 31.08.2021):
	```
	conda install -c conda-forge einops
	```
</details>
<details><summary><b><a href="https://github.com/clab/dynet">dyNET</a></b> (🥈27 ·  ⭐ 3.3K · 💤) - DyNet：动态神经网络工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/clab/dynet) (👨‍💻 160 · 🔀 670 · 📥 3.8K · 📦 190 · 📋 920 - 27% open · ⏱️ 27.01.2021):

	```
	git clone https://github.com/clab/dynet
	```
- [PyPi](https://pypi.org/project/dyNET) (📥 20K / month):
	```
	pip install dyNET
	```
</details>
<details><summary><b><a href="https://github.com/apache/flink">PyFlink</a></b> (🥉26 ·  ⭐ 17K) - Apache Flink Python API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/flink) (👨‍💻 1.4K · 🔀 9.5K · ⏱️ 12.10.2021):

	```
	git clone https://github.com/apache/flink
	```
- [PyPi](https://pypi.org/project/apache-flink) (📥 7K / month):
	```
	pip install apache-flink
	```
</details>
<details><summary><b><a href="https://github.com/tflearn/tflearn">TFlearn</a></b> (🥉26 ·  ⭐ 9.6K · 💤) - 深度学习库，基于TensorFlow构建上层简单易用的API。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tflearn/tflearn) (👨‍💻 130 · 🔀 2.3K · 📦 3.6K · 📋 910 - 60% open · ⏱️ 30.11.2020):

	```
	git clone https://github.com/tflearn/tflearn
	```
- [PyPi](https://pypi.org/project/tflearn) (📥 23K / month):
	```
	pip install tflearn
	```
</details>
<details><summary><b><a href="https://github.com/skorch-dev/skorch">skorch</a></b> (🥉26 ·  ⭐ 4.2K) - 封装成scikit-learn接口模式的神经网络库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/skorch-dev/skorch) (👨‍💻 44 · 🔀 290 · 📦 400 · 📋 400 - 11% open · ⏱️ 09.10.2021):

	```
	git clone https://github.com/skorch-dev/skorch
	```
- [PyPi](https://pypi.org/project/skorch) (📥 16K / month):
	```
	pip install skorch
	```
- [Conda](https://anaconda.org/conda-forge/skorch) (📥 410K · ⏱️ 24.03.2021):
	```
	conda install -c conda-forge skorch
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/ignite">Ignite</a></b> (🥉26 ·  ⭐ 3.7K) - 用于训练和评估神经等一系列操作的高级深度学习工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/ignite) (👨‍💻 150 · 🔀 490 · 📋 910 - 11% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/pytorch/ignite
	```
- [PyPi](https://pypi.org/project/pytorch-ignite) (📥 67K / month):
	```
	pip install pytorch-ignite
	```
- [Conda](https://anaconda.org/pytorch/ignite) (📥 70K · ⏱️ 02.08.2021):
	```
	conda install -c pytorch ignite
	```
</details>
<details><summary><b><a href="https://github.com/amaiya/ktrain">ktrain</a></b> (🥉26 ·  ⭐ 910) - ktrain是一个Python库，可以使深度学习和AI更简单。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/amaiya/ktrain) (👨‍💻 12 · 🔀 220 · 📦 220 · 📋 360 - 1% open · ⏱️ 03.09.2021):

	```
	git clone https://github.com/amaiya/ktrain
	```
- [PyPi](https://pypi.org/project/ktrain) (📥 20K / month):
	```
	pip install ktrain
	```
</details>
<details><summary><b><a href="https://github.com/apple/turicreate">Turi Create</a></b> (🥉25 ·  ⭐ 10K) - Turi Create简化了自定义机器学习的开发。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/apple/turicreate) (👨‍💻 82 · 🔀 1.1K · 📥 4.9K · 📦 270 · 📋 1.7K - 26% open · ⏱️ 21.09.2021):

	```
	git clone https://github.com/apple/turicreate
	```
- [PyPi](https://pypi.org/project/turicreate) (📥 25K / month):
	```
	pip install turicreate
	```
</details>
<details><summary><b><a href="https://github.com/ludwig-ai/ludwig">Ludwig</a></b> (🥉25 ·  ⭐ 7.9K) - 路德维希（Ludwig）是一个工具箱，可用于深度学习训练和评估。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ludwig-ai/ludwig) (👨‍💻 96 · 🔀 900 · 📦 96 · 📋 590 - 21% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/ludwig-ai/ludwig
	```
- [PyPi](https://pypi.org/project/ludwig) (📥 4K / month):
	```
	pip install ludwig
	```
</details>
<details><summary><b><a href="https://github.com/numenta/nupic">NuPIC</a></b> (🥉24 ·  ⭐ 6.3K · 💀) - Numenta智能计算平台。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/numenta/nupic) (👨‍💻 120 · 🔀 1.5K · 📦 100 · 📋 1.8K - 25% open · ⏱️ 23.10.2019):

	```
	git clone https://github.com/numenta/nupic
	```
- [PyPi](https://pypi.org/project/nupic) (📥 3.8K / month):
	```
	pip install nupic
	```
</details>
<details><summary><b><a href="https://github.com/aksnzhy/xlearn">xLearn</a></b> (🥉24 ·  ⭐ 2.9K · 💀) - 高性能，易于使用且可扩展的机器学习（ML）工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aksnzhy/xlearn) (👨‍💻 30 · 🔀 510 · 📥 2.9K · 📦 68 · 📋 290 - 63% open · ⏱️ 03.03.2020):

	```
	git clone https://github.com/aksnzhy/xlearn
	```
- [PyPi](https://pypi.org/project/xlearn) (📥 2.2K / month):
	```
	pip install xlearn
	```
</details>
<details><summary><b><a href="https://github.com/ROCmSoftwarePlatform/tensorflow-upstream">tensorflow-upstream</a></b> (🥉24 ·  ⭐ 570) - TensorFlow ROCm端口。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ROCmSoftwarePlatform/tensorflow-upstream) (👨‍💻 3.8K · 🔀 65 · 📥 17 · 📋 300 - 16% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/ROCmSoftwarePlatform/tensorflow-upstream
	```
- [PyPi](https://pypi.org/project/tensorflow-rocm) (📥 1.7K / month):
	```
	pip install tensorflow-rocm
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/CNTK">CNTK</a></b> (🥉23 ·  ⭐ 17K · 💀) - Microsoft认知工具包（CNTK），一种开源的深度学习工具包。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/microsoft/CNTK) (👨‍💻 270 · 🔀 4.3K · 📥 14K · 📋 3.3K - 22% open · ⏱️ 31.03.2020):

	```
	git clone https://github.com/microsoft/CNTK
	```
- [PyPi](https://pypi.org/project/cntk) (📥 1.6K / month):
	```
	pip install cntk
	```
</details>
<details><summary><b><a href="https://github.com/mlpack/mlpack">mlpack</a></b> (🥉23 ·  ⭐ 3.8K) - mlpack：可扩展的C++机器学习库-。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mlpack/mlpack) (👨‍💻 280 · 🔀 1.4K · 📋 1.4K - 3% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/mlpack/mlpack
	```
- [PyPi](https://pypi.org/project/mlpack) (📥 780 / month):
	```
	pip install mlpack
	```
- [Conda](https://anaconda.org/conda-forge/mlpack) (📥 91K · ⏱️ 07.07.2021):
	```
	conda install -c conda-forge mlpack
	```
</details>
<details><summary><b><a href="https://github.com/sony/nnabla">Neural Network Libraries</a></b> (🥉23 ·  ⭐ 2.5K) - 神经网络工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sony/nnabla) (👨‍💻 64 · 🔀 300 · 📥 530 · 📋 60 - 30% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/sony/nnabla
	```
- [PyPi](https://pypi.org/project/nnabla) (📥 2.1K / month):
	```
	pip install nnabla
	```
</details>
<details><summary><b><a href="https://github.com/NervanaSystems/neon">neon</a></b> (🥉22 ·  ⭐ 3.9K · 💀) - 英特尔Nervana深度学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/NervanaSystems/neon) (👨‍💻 110 · 🔀 810 · 📥 320 · 📦 50 · 📋 390 - 21% open · ⏱️ 22.05.2019):

	```
	git clone https://github.com/NervanaSystems/neon
	```
- [PyPi](https://pypi.org/project/nervananeon) (📥 110 / month):
	```
	pip install nervananeon
	```
</details>
<details><summary><b><a href="https://github.com/Lasagne/Lasagne">Lasagne</a></b> (🥉22 ·  ⭐ 3.8K · 💀) - 轻量级的库，用于在Theano中构建和训练神经网络。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Lasagne/Lasagne) (👨‍💻 72 · 🔀 930 · 📦 860 · 📋 520 - 22% open · ⏱️ 20.11.2019):

	```
	git clone https://github.com/Lasagne/Lasagne
	```
- [PyPi](https://pypi.org/project/lasagne) (📥 3.2K / month):
	```
	pip install lasagne
	```
</details>
<details><summary><b><a href="https://github.com/shogun-toolbox/shogun">SHOGUN</a></b> (🥉22 ·  ⭐ 2.9K · 💤) - 统一高效的机器学习。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/shogun-toolbox/shogun) (👨‍💻 250 · 🔀 1K · 📋 1.5K - 27% open · ⏱️ 08.12.2020):

	```
	git clone https://github.com/shogun-toolbox/shogun
	```
- [Conda](https://anaconda.org/conda-forge/shogun) (📥 110K · ⏱️ 25.06.2018):
	```
	conda install -c conda-forge shogun
	```
- [Docker Hub](https://hub.docker.com/r/shogun/shogun) (📥 1.5K · ⭐ 1 · ⏱️ 31.01.2019):
	```
	docker pull shogun/shogun
	```
</details>
<details><summary><b><a href="https://github.com/itdxer/neupy">NeuPy</a></b> (🥉22 ·  ⭐ 690 · 💀) - NeuPy是一个基于Tensorflow的python库，用于原型设计和构建。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/itdxer/neupy) (👨‍💻 7 · 🔀 140 · 📦 110 · 📋 260 - 10% open · ⏱️ 02.09.2019):

	```
	git clone https://github.com/itdxer/neupy
	```
- [PyPi](https://pypi.org/project/neupy) (📥 1.7K / month):
	```
	pip install neupy
	```
</details>
<details><summary><b><a href="https://github.com/google/objax">Objax</a></b> (🥉22 ·  ⭐ 650) - Objax是加速研究与应用的开源深度学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>jax</code></summary>

- [GitHub](https://github.com/google/objax) (👨‍💻 22 · 🔀 54 · 📦 16 · 📋 92 - 39% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/google/objax
	```
- [PyPi](https://pypi.org/project/objax) (📥 16K / month):
	```
	pip install objax
	```
</details>
<details><summary><b><a href="https://github.com/XiaoMi/mace">mace</a></b> (🥉20 ·  ⭐ 4.5K) - MACE是针对移动设备优化的深度学习推理框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/XiaoMi/mace) (👨‍💻 64 · 🔀 770 · 📥 1.4K · 📋 650 - 5% open · ⏱️ 16.09.2021):

	```
	git clone https://github.com/XiaoMi/mace
	```
</details>
<details><summary><b><a href="https://github.com/google/flax">Flax</a></b> (🥉20 ·  ⭐ 2.2K · 📉) - Flax是专为.NET设计的用于JAX的神经网络库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>jax</code></summary>

- [GitHub](https://github.com/google/flax) (👨‍💻 120 · 🔀 250 · 📥 26 · 📦 420 · 📋 380 - 34% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/google/flax
	```
- [PyPi](https://pypi.org/project/flax):
	```
	pip install flax
	```
</details>
<details><summary><b><a href="https://github.com/google/neural-tangents">Neural Tangents</a></b> (🥉20 ·  ⭐ 1.6K) - Python中的快速简便的无限神经网络。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/neural-tangents) (👨‍💻 20 · 🔀 170 · 📥 140 · 📦 23 · 📋 94 - 28% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/google/neural-tangents
	```
- [PyPi](https://pypi.org/project/neural-tangents) (📥 590 / month):
	```
	pip install neural-tangents
	```
</details>
<details><summary><b><a href="https://github.com/mindsdb/mindsdb">MindsDB</a></b> (🥉19 ·  ⭐ 4K) - 为各种现有数据库提供预测性AI层。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mindsdb/mindsdb) (👨‍💻 57 · 🔀 500 · 📋 700 - 10% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/mindsdb/mindsdb
	```
- [PyPi](https://pypi.org/project/mindsdb) (📥 2.2K / month):
	```
	pip install mindsdb
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/dm-haiku">Haiku</a></b> (🥉19 ·  ⭐ 1.4K) - 基于JAX的神经网络库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepmind/dm-haiku) (👨‍💻 50 · 🔀 100 · 📦 200 · 📋 110 - 21% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/deepmind/dm-haiku
	```
</details>
<details><summary><b><a href="https://github.com/nubank/fklearn">fklearn</a></b> (🥉19 ·  ⭐ 1.3K) - fklearn：机器学习工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nubank/fklearn) (👨‍💻 37 · 🔀 150 · 📦 10 · 📋 39 - 48% open · ⏱️ 01.09.2021):

	```
	git clone https://github.com/nubank/fklearn
	```
- [PyPi](https://pypi.org/project/fklearn):
	```
	pip install fklearn
	```
</details>
<details><summary><b><a href="https://github.com/Xtra-Computing/thundersvm">ThunderSVM</a></b> (🥉19 ·  ⭐ 1.3K · 💤) - ThunderSVM：在GPU和CPU上的快速SVM库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Xtra-Computing/thundersvm) (👨‍💻 33 · 🔀 180 · 📥 2.3K · 📋 200 - 27% open · ⏱️ 10.02.2021):

	```
	git clone https://github.com/Xtra-Computing/thundersvm
	```
- [PyPi](https://pypi.org/project/thundersvm) (📥 550 / month):
	```
	pip install thundersvm
	```
</details>
<details><summary><b><a href="https://github.com/pytorchbearer/torchbearer">Torchbearer</a></b> (🥉19 ·  ⭐ 610 · 💤) - torchbearer：PyTorch的模型拟合库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorchbearer/torchbearer) (👨‍💻 13 · 🔀 68 · 📦 54 · 📋 240 - 3% open · ⏱️ 26.03.2021):

	```
	git clone https://github.com/pytorchbearer/torchbearer
	```
- [PyPi](https://pypi.org/project/torchbearer) (📥 810 / month):
	```
	pip install torchbearer
	```
</details>
<details><summary><b><a href="https://github.com/poets-ai/elegy">elegy</a></b> (🥉17 ·  ⭐ 270) - Elegy是Jax的与框架无关的Trainer工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code>jax</code></summary>

- [GitHub](https://github.com/poets-ai/elegy) (👨‍💻 14 · 🔀 16 · 📋 64 - 37% open · ⏱️ 13.08.2021):

	```
	git clone https://github.com/poets-ai/elegy
	```
- [PyPi](https://pypi.org/project/elegy) (📥 190 / month):
	```
	pip install elegy
	```
</details>
<details><summary><b><a href="https://github.com/neoml-lib/neoml">NeoML</a></b> (🥉16 ·  ⭐ 650) - neoml是可以用于深度学习和传统机器学习的工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/neoml-lib/neoml) (👨‍💻 23 · 🔀 93 · 📋 44 - 52% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/neoml-lib/neoml
	```
</details>
<details><summary><b><a href="https://github.com/Xtra-Computing/thundergbm">ThunderGBM</a></b> (🥉15 ·  ⭐ 610 · 💤) - ThunderGBM：GPU上的快速GBDT和随机森林。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Xtra-Computing/thundergbm) (👨‍💻 10 · 🔀 79 · 📋 50 - 44% open · ⏱️ 05.01.2021):

	```
	git clone https://github.com/Xtra-Computing/thundergbm
	```
- [PyPi](https://pypi.org/project/thundergbm) (📥 98 / month):
	```
	pip install thundergbm
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/StarSpace">StarSpace</a></b> (🥉13 ·  ⭐ 3.7K · 💀) - 学习embedding嵌入用于分类，检索和排序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/StarSpace) (👨‍💻 17 · 🔀 490 · 📋 200 - 24% open · ⏱️ 13.12.2019):

	```
	git clone https://github.com/facebookresearch/StarSpace
	```
</details>
<br>

## 数据可视化

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_通用和特定于任务的数据可视化库。_

<details><summary><b><a href="https://github.com/matplotlib/matplotlib">Matplotlib</a></b> (🥇40 ·  ⭐ 14K) - matplotlib：Python绘图工具库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/matplotlib/matplotlib) (👨‍💻 1.3K · 🔀 5.9K · 📦 440K · 📋 8K - 17% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/matplotlib/matplotlib
	```
- [PyPi](https://pypi.org/project/matplotlib) (📥 31M / month):
	```
	pip install matplotlib
	```
- [Conda](https://anaconda.org/conda-forge/matplotlib) (📥 10M · ⏱️ 23.09.2021):
	```
	conda install -c conda-forge matplotlib
	```
</details>
<details><summary><b><a href="https://github.com/mwaskom/seaborn">Seaborn</a></b> (🥇38 ·  ⭐ 8.8K) - 使用matplotlib进行统计数据可视化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mwaskom/seaborn) (👨‍💻 160 · 🔀 1.4K · 📥 190 · 📦 120K · 📋 1.9K - 4% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/mwaskom/seaborn
	```
- [PyPi](https://pypi.org/project/seaborn) (📥 16M / month):
	```
	pip install seaborn
	```
- [Conda](https://anaconda.org/conda-forge/seaborn) (📥 2.9M · ⏱️ 16.08.2021):
	```
	conda install -c conda-forge seaborn
	```
</details>
<details><summary><b><a href="https://github.com/pandas-profiling/pandas-profiling">pandas-profiling</a></b> (🥇33 ·  ⭐ 8.1K) - 从pandas DataFrame创建HTML分析报告。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pandas-profiling/pandas-profiling) (👨‍💻 81 · 🔀 1.2K · 📦 5.4K · 📋 510 - 16% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/pandas-profiling/pandas-profiling
	```
- [PyPi](https://pypi.org/project/pandas-profiling) (📥 11M / month):
	```
	pip install pandas-profiling
	```
- [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 170K · ⏱️ 28.09.2021):
	```
	conda install -c conda-forge pandas-profiling
	```
</details>
<details><summary><b><a href="https://github.com/plotly/dash">dash</a></b> (🥇31 ·  ⭐ 15K) - 适用于Python，R，Julia和Jupyter的分析型Web应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/dash) (👨‍💻 100 · 🔀 1.5K · 📦 150 · 📋 1.1K - 44% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/plotly/dash
	```
- [PyPi](https://pypi.org/project/dash) (📥 730K / month):
	```
	pip install dash
	```
- [Conda](https://anaconda.org/conda-forge/dash) (📥 310K · ⏱️ 21.09.2021):
	```
	conda install -c conda-forge dash
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/altair">Altair</a></b> (🥇31 ·  ⭐ 7K) - 用于Python的声明式统计可视化库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair) (👨‍💻 130 · 🔀 590 · 📦 17K · 📋 1.5K - 13% open · ⏱️ 18.08.2021):

	```
	git clone https://github.com/altair-viz/altair
	```
- [PyPi](https://pypi.org/project/altair) (📥 2.9M / month):
	```
	pip install altair
	```
- [Conda](https://anaconda.org/conda-forge/altair) (📥 940K · ⏱️ 01.04.2020):
	```
	conda install -c conda-forge altair
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/bokeh">Bokeh</a></b> (🥈30 ·  ⭐ 16K) - 浏览器中的Python交互式数据可视化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 570 · 🔀 3.7K · 📦 40K · 📋 6.7K - 9% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 5.6M · ⏱️ 22.09.2021):
	```
	conda install -c conda-forge bokeh
	```
</details>
<details><summary><b><a href="https://github.com/lmcinnes/umap">UMAP</a></b> (🥈30 ·  ⭐ 5.1K) - 均匀流形逼近和投影。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lmcinnes/umap) (👨‍💻 93 · 🔀 540 · 📦 3.8K · 📋 560 - 50% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/lmcinnes/umap
	```
- [PyPi](https://pypi.org/project/umap-learn) (📥 1.3M / month):
	```
	pip install umap-learn
	```
</details>
<details><summary><b><a href="https://github.com/plotly/plotly.py">Plotly</a></b> (🥈29 ·  ⭐ 10K) - 适用于Python的交互式图形库（包括Plotly Express）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/plotly.py) (👨‍💻 180 · 🔀 1.9K · 📦 5 · 📋 2.1K - 45% open · ⏱️ 16.09.2021):

	```
	git clone https://github.com/plotly/plotly.py
	```
- [PyPi](https://pypi.org/project/plotly):
	```
	pip install plotly
	```
- [Conda](https://anaconda.org/conda-forge/plotly) (📥 1.9M · ⏱️ 01.09.2021):
	```
	conda install -c conda-forge plotly
	```
- [NPM](https://www.npmjs.com/package/plotlywidget) (📥 44K / month):
	```
	npm install plotlywidget
	```
</details>
<details><summary><b><a href="https://github.com/ResidentMario/missingno">missingno</a></b> (🥈29 ·  ⭐ 2.9K) - 在缺失值和混乱数据下，用于数据可视化的python模块。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ResidentMario/missingno) (👨‍💻 17 · 🔀 370 · 📦 5.1K · 📋 110 - 8% open · ⏱️ 04.07.2021):

	```
	git clone https://github.com/ResidentMario/missingno
	```
- [PyPi](https://pypi.org/project/missingno) (📥 650K / month):
	```
	pip install missingno
	```
- [Conda](https://anaconda.org/conda-forge/missingno) (📥 130K · ⏱️ 15.02.2020):
	```
	conda install -c conda-forge missingno
	```
</details>
<details><summary><b><a href="https://github.com/xflr6/graphviz">Graphviz</a></b> (🥈28 ·  ⭐ 1.1K) - Graphviz的简单Python界面。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/xflr6/graphviz) (👨‍💻 15 · 🔀 160 · 📦 24K · 📋 110 - 6% open · ⏱️ 31.07.2021):

	```
	git clone https://github.com/xflr6/graphviz
	```
- [PyPi](https://pypi.org/project/graphviz) (📥 7.4M / month):
	```
	pip install graphviz
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/data-validation">data-validation</a></b> (🥈28 ·  ⭐ 580) - 用于探索和验证机器学习的库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/data-validation) (👨‍💻 23 · 🔀 100 · 📥 290 · 📦 330 · 📋 130 - 21% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/tensorflow/data-validation
	```
- [PyPi](https://pypi.org/project/tensorflow-data-validation) (📥 12M / month):
	```
	pip install tensorflow-data-validation
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥈27 ·  ⭐ 3.2K) - 用于IPython / Jupyter笔记本的绘图库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 55 · 🔀 420 · 📦 28 · 📋 540 - 35% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/bqplot/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot) (📥 62K / month):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 810K · ⏱️ 01.10.2021):
	```
	conda install -c conda-forge bqplot
	```
- [NPM](https://www.npmjs.com/package/bqplot) (📥 16K / month):
	```
	npm install bqplot
	```
</details>
<details><summary><b><a href="https://github.com/has2k1/plotnine">plotnine</a></b> (🥈27 ·  ⭐ 2.8K) - Python的图形语法。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/has2k1/plotnine) (👨‍💻 86 · 🔀 140 · 📦 2.5K · 📋 440 - 14% open · ⏱️ 21.09.2021):

	```
	git clone https://github.com/has2k1/plotnine
	```
- [PyPi](https://pypi.org/project/plotnine) (📥 180K / month):
	```
	pip install plotnine
	```
- [Conda](https://anaconda.org/conda-forge/plotnine) (📥 130K · ⏱️ 25.03.2021):
	```
	conda install -c conda-forge plotnine
	```
</details>
<details><summary><b><a href="https://github.com/santosjorge/cufflinks">Cufflinks</a></b> (🥈27 ·  ⭐ 2.4K · 💤) - Plotly + Pandas的生产力工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/santosjorge/cufflinks) (👨‍💻 38 · 🔀 550 · 📦 4.4K · 📋 200 - 38% open · ⏱️ 25.02.2021):

	```
	git clone https://github.com/santosjorge/cufflinks
	```
- [PyPi](https://pypi.org/project/cufflinks) (📥 260K / month):
	```
	pip install cufflinks
	```
</details>
<details><summary><b><a href="https://github.com/pyvista/pyvista">PyVista</a></b> (🥈27 ·  ⭐ 950) - 通过简化的界面进行3D绘图和网格分析。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyvista/pyvista) (👨‍💻 61 · 🔀 190 · 📥 320 · 📦 480 · 📋 580 - 29% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/pyvista/pyvista
	```
- [PyPi](https://pypi.org/project/pyvista) (📥 23K / month):
	```
	pip install pyvista
	```
- [Conda](https://anaconda.org/conda-forge/pyvista) (📥 120K · ⏱️ 12.09.2021):
	```
	conda install -c conda-forge pyvista
	```
</details>
<details><summary><b><a href="https://github.com/amueller/word_cloud">wordcloud</a></b> (🥈26 ·  ⭐ 8.4K) - Python中的词云生成器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/amueller/word_cloud) (👨‍💻 62 · 🔀 2.1K · 📋 440 - 20% open · ⏱️ 15.09.2021):

	```
	git clone https://github.com/amueller/word_cloud
	```
- [PyPi](https://pypi.org/project/wordcloud) (📥 640K / month):
	```
	pip install wordcloud
	```
- [Conda](https://anaconda.org/conda-forge/wordcloud) (📥 240K · ⏱️ 30.08.2021):
	```
	conda install -c conda-forge wordcloud
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/facets">Facets Overview</a></b> (🥈26 ·  ⭐ 6.7K) - 机器学习数据集的可视化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PAIR-code/facets) (👨‍💻 28 · 🔀 810 · 📦 70 · 📋 150 - 50% open · ⏱️ 06.05.2021):

	```
	git clone https://github.com/pair-code/facets
	```
- [PyPi](https://pypi.org/project/facets-overview) (📥 150K / month):
	```
	pip install facets-overview
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/datashader">datashader</a></b> (🥈26 ·  ⭐ 2.6K) - 快速准确地渲染大数据。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/holoviz/datashader) (👨‍💻 44 · 🔀 320 · 📦 830 · 📋 480 - 26% open · ⏱️ 29.09.2021):

	```
	git clone https://github.com/holoviz/datashader
	```
- [PyPi](https://pypi.org/project/datashader) (📥 43K / month):
	```
	pip install datashader
	```
- [Conda](https://anaconda.org/conda-forge/datashader) (📥 230K · ⏱️ 10.06.2021):
	```
	conda install -c conda-forge datashader
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/holoviews">HoloViews</a></b> (🥈26 ·  ⭐ 2K) - 使用Holoviews，您的数据可以可视化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/holoviz/holoviews) (👨‍💻 110 · 🔀 320 · 📋 2.7K - 29% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/holoviz/holoviews
	```
- [PyPi](https://pypi.org/project/holoviews) (📥 170K / month):
	```
	pip install holoviews
	```
- [Conda](https://anaconda.org/conda-forge/holoviews) (📥 580K · ⏱️ 17.09.2021):
	```
	conda install -c conda-forge holoviews
	```
- [NPM](https://www.npmjs.com/package/@pyviz/jupyterlab_pyviz) (📥 4K / month):
	```
	npm install @pyviz/jupyterlab_pyviz
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/hvplot">hvPlot</a></b> (🥈26 ·  ⭐ 460) - 用于构建的pandas，dask，xarray和networkx的高级绘图API。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/hvplot) (👨‍💻 32 · 🔀 61 · 📦 820 · 📋 380 - 32% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/holoviz/hvplot
	```
- [PyPi](https://pypi.org/project/hvplot) (📥 60K / month):
	```
	pip install hvplot
	```
- [Conda](https://anaconda.org/conda-forge/hvplot) (📥 130K · ⏱️ 23.07.2021):
	```
	conda install -c conda-forge hvplot
	```
</details>
<details><summary><b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥉25 ·  ⭐ 2.7K) - pandas数据结构的可视化工具。<code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/man-group/dtale) (👨‍💻 18 · 🔀 200 · 📦 240 · 📋 420 - 8% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/man-group/dtale
	```
- [PyPi](https://pypi.org/project/dtale) (📥 55K / month):
	```
	pip install dtale
	```
- [Conda](https://anaconda.org/conda-forge/dtale) (📥 89K · ⏱️ 05.10.2021):
	```
	conda install -c conda-forge dtale
	```
</details>
<details><summary><b><a href="https://github.com/ContextLab/hypertools">HyperTools</a></b> (🥉25 ·  ⭐ 1.7K) - 一个Python工具箱，用于获得对高维的几何洞察力。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ContextLab/hypertools) (👨‍💻 21 · 🔀 150 · 📥 2 · 📦 140 · 📋 190 - 35% open · ⏱️ 19.07.2021):

	```
	git clone https://github.com/ContextLab/hypertools
	```
- [PyPi](https://pypi.org/project/hypertools) (📥 1.2K / month):
	```
	pip install hypertools
	```
</details>
<details><summary><b><a href="https://github.com/pyecharts/pyecharts">pyecharts</a></b> (🥉24 ·  ⭐ 12K) - Python Echarts绘图库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyecharts/pyecharts) (👨‍💻 30 · 🔀 2.5K · 📦 1.8K · 📋 1.5K - 1% open · ⏱️ 07.05.2021):

	```
	git clone https://github.com/pyecharts/pyecharts
	```
- [PyPi](https://pypi.org/project/pyecharts):
	```
	pip install pyecharts
	```
</details>
<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥉24 ·  ⭐ 3.6K) - 通过WebAssembly进行流式透视显示。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/finos/perspective) (👨‍💻 64 · 🔀 390 · 📦 210 · 📋 450 - 13% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/finos/perspective
	```
- [PyPi](https://pypi.org/project/perspective-python):
	```
	pip install perspective-python
	```
- [NPM](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 1.9K / month):
	```
	npm install @finos/perspective-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/spotify/chartify">Chartify</a></b> (🥉24 ·  ⭐ 3K · 💤) - Python库，使数据科学家可以轻松创建。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/chartify) (👨‍💻 21 · 🔀 260 · 📦 57 · 📋 71 - 57% open · ⏱️ 05.02.2021):

	```
	git clone https://github.com/spotify/chartify
	```
- [PyPi](https://pypi.org/project/chartify) (📥 2.3K / month):
	```
	pip install chartify
	```
- [Conda](https://anaconda.org/conda-forge/chartify) (📥 16K · ⏱️ 07.11.2020):
	```
	conda install -c conda-forge chartify
	```
</details>
<details><summary><b><a href="https://github.com/vispy/vispy">VisPy</a></b> (🥉23 ·  ⭐ 2.7K) - 高性能交互式2D / 3D数据可视化库。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/vispy/vispy) (👨‍💻 160 · 🔀 560 · 📦 600 · 📋 1.2K - 26% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/vispy/vispy
	```
- [PyPi](https://pypi.org/project/vispy):
	```
	pip install vispy
	```
- [Conda](https://anaconda.org/conda-forge/vispy) (📥 180K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge vispy
	```
- [NPM](https://www.npmjs.com/package/vispy) (📥 15 / month):
	```
	npm install vispy
	```
</details>
<details><summary><b><a href="https://github.com/pyqtgraph/pyqtgraph">PyQtGraph</a></b> (🥉23 ·  ⭐ 2.6K) - 用于科学/工程的快速数据可视化和GUI工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pyqtgraph/pyqtgraph) (👨‍💻 210 · 🔀 860 · 📋 900 - 29% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/pyqtgraph/pyqtgraph
	```
- [PyPi](https://pypi.org/project/pyqtgraph) (📥 71K / month):
	```
	pip install pyqtgraph
	```
- [Conda](https://anaconda.org/conda-forge/pyqtgraph) (📥 200K · ⏱️ 11.10.2021):
	```
	conda install -c conda-forge pyqtgraph
	```
</details>
<details><summary><b><a href="https://github.com/SauceCat/PDPbox">PDPbox</a></b> (🥉23 ·  ⭐ 620 · 💤) - python部分依赖图工具箱。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SauceCat/PDPbox) (👨‍💻 7 · 🔀 98 · 📦 440 · 📋 55 - 30% open · ⏱️ 14.03.2021):

	```
	git clone https://github.com/SauceCat/PDPbox
	```
- [PyPi](https://pypi.org/project/pdpbox) (📥 87K / month):
	```
	pip install pdpbox
	```
- [Conda](https://anaconda.org/conda-forge/pdpbox) (📥 9.6K · ⏱️ 14.03.2021):
	```
	conda install -c conda-forge pdpbox
	```
</details>
<details><summary><b><a href="https://github.com/marcharper/python-ternary">python-ternary</a></b> (🥉23 ·  ⭐ 480) - 带有matplotlib的python三元绘图库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/marcharper/python-ternary) (👨‍💻 27 · 🔀 120 · 📥 17 · 📦 70 · 📋 110 - 21% open · ⏱️ 24.08.2021):

	```
	git clone https://github.com/marcharper/python-ternary
	```
- [PyPi](https://pypi.org/project/python-ternary) (📥 18K / month):
	```
	pip install python-ternary
	```
- [Conda](https://anaconda.org/conda-forge/python-ternary) (📥 59K · ⏱️ 17.02.2021):
	```
	conda install -c conda-forge python-ternary
	```
</details>
<details><summary><b><a href="https://github.com/DmitryUlyanov/Multicore-TSNE">Multicore-TSNE</a></b> (🥉22 ·  ⭐ 1.6K · 💀) - 使用Python和Torch并行执行t-SNE。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/DmitryUlyanov/Multicore-TSNE) (👨‍💻 15 · 🔀 180 · 📦 250 · 📋 52 - 61% open · ⏱️ 19.08.2020):

	```
	git clone https://github.com/DmitryUlyanov/Multicore-TSNE
	```
- [PyPi](https://pypi.org/project/MulticoreTSNE) (📥 7.8K / month):
	```
	pip install MulticoreTSNE
	```
- [Conda](https://anaconda.org/conda-forge/multicore-tsne) (📥 10K · ⏱️ 23.04.2021):
	```
	conda install -c conda-forge multicore-tsne
	```
</details>
<details><summary><b><a href="https://github.com/pavlin-policar/openTSNE">openTSNE</a></b> (🥉22 ·  ⭐ 890) - t-SNE的可扩展并行实现。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pavlin-policar/openTSNE) (👨‍💻 10 · 🔀 93 · 📦 250 · 📋 94 - 8% open · ⏱️ 06.06.2021):

	```
	git clone https://github.com/pavlin-policar/openTSNE
	```
- [PyPi](https://pypi.org/project/opentsne):
	```
	pip install opentsne
	```
- [Conda](https://anaconda.org/conda-forge/opentsne) (📥 120K · ⏱️ 09.08.2021):
	```
	conda install -c conda-forge opentsne
	```
</details>
<details><summary><b><a href="https://github.com/PatrikHlobil/Pandas-Bokeh">Pandas-Bokeh</a></b> (🥉22 ·  ⭐ 720) - pandas和GeoPandas的Bokeh绘图后端。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PatrikHlobil/Pandas-Bokeh) (👨‍💻 12 · 🔀 88 · 📦 230 · 📋 89 - 25% open · ⏱️ 10.05.2021):

	```
	git clone https://github.com/PatrikHlobil/Pandas-Bokeh
	```
- [PyPi](https://pypi.org/project/pandas-bokeh) (📥 9.1K / month):
	```
	pip install pandas-bokeh
	```
</details>
<details><summary><b><a href="https://github.com/fbdesignpro/sweetviz">Sweetviz</a></b> (🥉21 ·  ⭐ 1.8K) - 可视化和比较数据集，目标值和相关性。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fbdesignpro/sweetviz) (👨‍💻 6 · 🔀 180 · 📋 87 - 20% open · ⏱️ 08.07.2021):

	```
	git clone https://github.com/fbdesignpro/sweetviz
	```
- [PyPi](https://pypi.org/project/sweetviz) (📥 53K / month):
	```
	pip install sweetviz
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥉21 ·  ⭐ 760 · 💤) - Jupyter-Three.js桥。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jupyter-widgets/pythreejs) (👨‍💻 27 · 🔀 160 · 📦 18 · 📋 210 - 30% open · ⏱️ 26.02.2021):

	```
	git clone https://github.com/jupyter-widgets/pythreejs
	```
- [PyPi](https://pypi.org/project/pythreejs) (📥 39K / month):
	```
	pip install pythreejs
	```
- [Conda](https://anaconda.org/conda-forge/pythreejs) (📥 340K · ⏱️ 02.03.2021):
	```
	conda install -c conda-forge pythreejs
	```
- [NPM](https://www.npmjs.com/package/jupyter-threejs) (📥 7.1K / month):
	```
	npm install jupyter-threejs
	```
</details>
<details><summary><b><a href="https://github.com/adamerose/PandasGUI">PandasGUI</a></b> (🥉20 ·  ⭐ 2.4K) - pandas Dataframe的GUI。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/adamerose/PandasGUI) (👨‍💻 10 · 🔀 150 · 📦 99 · 📋 140 - 22% open · ⏱️ 25.09.2021):

	```
	git clone https://github.com/adamerose/pandasgui
	```
- [PyPi](https://pypi.org/project/pandasgui) (📥 6.7K / month):
	```
	pip install pandasgui
	```
</details>
<details><summary><b><a href="https://github.com/JetBrains/lets-plot">lets-plot</a></b> (🥉20 ·  ⭐ 690) - 一个用于统计数据的开源绘图库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/JetBrains/lets-plot) (👨‍💻 16 · 🔀 28 · 📥 110 · 📦 12 · 📋 200 - 34% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/JetBrains/lets-plot
	```
- [PyPi](https://pypi.org/project/lets-plot) (📥 2.1K / month):
	```
	pip install lets-plot
	```
</details>
<details><summary><b><a href="https://github.com/beringresearch/ivis">ivis</a></b> (🥉20 ·  ⭐ 250) - 使用算法对非常大的数据集进行降维。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/beringresearch/ivis) (👨‍💻 10 · 🔀 26 · 📦 17 · 📋 50 - 4% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/beringresearch/ivis
	```
- [PyPi](https://pypi.org/project/ivis) (📥 390 / month):
	```
	pip install ivis
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/hiplot">HiPlot</a></b> (🥉19 ·  ⭐ 2.2K) - HiPlot使理解高维数据变得容易。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/hiplot) (👨‍💻 6 · 🔀 100 · 📦 3 · 📋 68 - 13% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/facebookresearch/hiplot
	```
- [PyPi](https://pypi.org/project/hiplot):
	```
	pip install hiplot
	```
- [Conda](https://anaconda.org/conda-forge/hiplot) (📥 67K · ⏱️ 08.10.2021):
	```
	conda install -c conda-forge hiplot
	```
</details>
<details><summary><b><a href="https://github.com/leotac/joypy">joypy</a></b> (🥉19 ·  ⭐ 350) - 带有matplotlib和pandas的Python中的Joyplots。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/leotac/joypy) (👨‍💻 5 · 🔀 39 · 📦 96 · 📋 44 - 18% open · ⏱️ 13.06.2021):

	```
	git clone https://github.com/sbebo/joypy
	```
- [PyPi](https://pypi.org/project/joypy) (📥 20K / month):
	```
	pip install joypy
	```
- [Conda](https://anaconda.org/conda-forge/joypy) (📥 11K · ⏱️ 28.12.2020):
	```
	conda install -c conda-forge joypy
	```
</details>
<details><summary><b><a href="https://github.com/t-makaro/animatplot">animatplot</a></b> (🥉18 ·  ⭐ 380 · 💤) - 用于在patpliblib上构建动画图的python程序包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/t-makaro/animatplot) (👨‍💻 7 · 🔀 34 · 📦 28 · 📋 30 - 46% open · ⏱️ 05.10.2020):

	```
	git clone https://github.com/t-makaro/animatplot
	```
- [PyPi](https://pypi.org/project/animatplot) (📥 520 / month):
	```
	pip install animatplot
	```
- [Conda](https://anaconda.org/conda-forge/animatplot) (📥 6.8K · ⏱️ 06.10.2020):
	```
	conda install -c conda-forge animatplot
	```
</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉18 ·  ⭐ 310) - 适用于Vega和Vega-Lite的IPython/Jupyter笔记本模块。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/vega/ipyvega) (👨‍💻 10 · 🔀 51 · 📋 91 - 12% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/vega/ipyvega
	```
- [PyPi](https://pypi.org/project/vega) (📥 24K / month):
	```
	pip install vega
	```
- [Conda](https://anaconda.org/conda-forge/vega) (📥 460K · ⏱️ 11.08.2021):
	```
	conda install -c conda-forge vega
	```
</details>
<details><summary><b><a href="https://github.com/voxel51/fiftyone">FiftyOne</a></b> (🥉17 ·  ⭐ 670) - 可视化，创建和调试图像和视频数据集。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/voxel51/fiftyone) (👨‍💻 18 · 🔀 80 · 📦 24 · 📋 530 - 29% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/voxel51/fiftyone
	```
- [PyPi](https://pypi.org/project/fiftyone):
	```
	pip install fiftyone
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/pdvega">pdvega</a></b> (🥉17 ·  ⭐ 340 · 💀) - 使用Vega-Lite交互式绘制pandas数据图。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/altair-viz/pdvega) (👨‍💻 9 · 🔀 31 · 📦 52 · 📋 26 - 61% open · ⏱️ 29.03.2019):

	```
	git clone https://github.com/altair-viz/pdvega
	```
- [PyPi](https://pypi.org/project/pdvega) (📥 210 / month):
	```
	pip install pdvega
	```
</details>
<details><summary><b><a href="https://github.com/gyli/PyWaffle">PyWaffle</a></b> (🥉16 ·  ⭐ 450) - 用Python作图。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gyli/PyWaffle) (👨‍💻 6 · 🔀 76 · 📦 87 · 📋 14 - 21% open · ⏱️ 28.07.2021):

	```
	git clone https://github.com/gyli/PyWaffle
	```
- [PyPi](https://pypi.org/project/pywaffle):
	```
	pip install pywaffle
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/AutoViz">AutoViz</a></b> (🥉15 ·  ⭐ 510) - 自动显示任意行的任何大小的任何数据集。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/AutoViz) (👨‍💻 10 · 🔀 81 · 📦 100 · 📋 32 - 12% open · ⏱️ 27.08.2021):

	```
	git clone https://github.com/AutoViML/AutoViz
	```
- [PyPi](https://pypi.org/project/autoviz):
	```
	pip install autoviz
	```
</details>
<details><summary><b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉15 ·  ⭐ 450 · 💀) - Jupyter/IPython的Dragndrop数据透视表和图表。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nicolaskruchten/jupyter_pivottablejs) (👨‍💻 3 · 🔀 59 · 📦 200 · 📋 56 - 30% open · ⏱️ 04.12.2018):

	```
	git clone https://github.com/nicolaskruchten/jupyter_pivottablejs
	```
- [PyPi](https://pypi.org/project/pivottablejs):
	```
	pip install pivottablejs
	```
</details>
<details><summary><b><a href="https://github.com/data-describe/data-describe">data-describe</a></b> (🥉12 ·  ⭐ 280 · 💤) - 数据描述：Pythonic EDA数据科学加速器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/data-describe/data-describe) (👨‍💻 14 · 🔀 15 · 📋 240 - 28% open · ⏱️ 02.03.2021):

	```
	git clone https://github.com/data-describe/data-describe
	```
- [PyPi](https://pypi.org/project/data-describe) (📥 310 / month):
	```
	pip install data-describe
	```
</details>
<details><summary><b><a href="https://github.com/biovault/nptsne">nptsne</a></b> (🥉12 ·  ⭐ 25 · 💤) - nptsne是numpy兼容的python二进制包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/biovault/nptsne) (👨‍💻 3 · 🔀 2 · 📦 3 · 📋 12 - 58% open · ⏱️ 03.02.2021):

	```
	git clone https://github.com/biovault/nptsne
	```
- [PyPi](https://pypi.org/project/nptsne) (📥 59 / month):
	```
	pip install nptsne
	```
</details>
<details><summary><b><a href="https://github.com/Zsailer/nx_altair">nx-altair</a></b> (🥉10 ·  ⭐ 170 · 💀) - 使用Altair绘制交互式NetworkX图形。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Zsailer/nx_altair) (👨‍💻 3 · 🔀 20 · 📋 10 - 60% open · ⏱️ 02.06.2020):

	```
	git clone https://github.com/Zsailer/nx_altair
	```
- [PyPi](https://pypi.org/project/nx-altair):
	```
	pip install nx-altair
	```
</details>
<br>

## 文本数据和NLP

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于处理，清理，处理和分析文本数据的库，以及用于NLP任务的库，例如语言检测，模糊匹配，文本分类，seq2seq学习，智能对话，关键字提取和机器翻译。_

<details><summary><b><a href="https://github.com/huggingface/transformers">transformers</a></b> (🥇37 ·  ⭐ 52K) - transformers：先进的自然语言模型库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/huggingface/transformers) (👨‍💻 1K · 🔀 12K · 📥 1.4K · 📦 17K · 📋 7.9K - 4% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/huggingface/transformers
	```
- [PyPi](https://pypi.org/project/transformers) (📥 3M / month):
	```
	pip install transformers
	```
- [Conda](https://anaconda.org/conda-forge/transformers) (📥 75K · ⏱️ 01.10.2021):
	```
	conda install -c conda-forge transformers
	```
</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/gensim">gensim</a></b> (🥇36 ·  ⭐ 13K) - 主题模型工具库。<code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/RaRe-Technologies/gensim) (👨‍💻 410 · 🔀 3.9K · 📥 3.5K · 📦 27K · 📋 1.7K - 20% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/RaRe-Technologies/gensim
	```
- [PyPi](https://pypi.org/project/gensim) (📥 14M / month):
	```
	pip install gensim
	```
- [Conda](https://anaconda.org/conda-forge/gensim) (📥 730K · ⏱️ 20.09.2021):
	```
	conda install -c conda-forge gensim
	```
</details>
<details><summary><b><a href="https://github.com/explosion/spaCy">spaCy</a></b> (🥇35 ·  ⭐ 21K) - Python中的工业级自然语言处理（NLP）工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/spaCy) (👨‍💻 630 · 🔀 3.5K · 📥 3.1K · 📦 31K · 📋 4.9K - 1% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/explosion/spaCy
	```
- [PyPi](https://pypi.org/project/spacy):
	```
	pip install spacy
	```
- [Conda](https://anaconda.org/conda-forge/spacy) (📥 2.3M · ⏱️ 21.09.2021):
	```
	conda install -c conda-forge spacy
	```
</details>
<details><summary><b><a href="https://github.com/nltk/nltk">nltk</a></b> (🥇33 ·  ⭐ 10K) - 用于符号和统计自然的库和程序套件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nltk/nltk) (👨‍💻 400 · 🔀 2.4K · 📦 120K · 📋 1.5K - 13% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/nltk/nltk
	```
- [PyPi](https://pypi.org/project/nltk) (📥 9.6M / month):
	```
	pip install nltk
	```
- [Conda](https://anaconda.org/conda-forge/nltk) (📥 940K · ⏱️ 11.10.2021):
	```
	conda install -c conda-forge nltk
	```
</details>
<details><summary><b><a href="https://github.com/gunthercox/ChatterBot">ChatterBot</a></b> (🥇32 ·  ⭐ 12K) - ChatterBot是机器学习的对话引擎。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gunthercox/ChatterBot) (👨‍💻 100 · 🔀 3.8K · 📦 3.9K · 📋 1.5K - 17% open · ⏱️ 01.06.2021):

	```
	git clone https://github.com/gunthercox/ChatterBot
	```
- [PyPi](https://pypi.org/project/chatterbot) (📥 70K / month):
	```
	pip install chatterbot
	```
</details>
<details><summary><b><a href="https://github.com/allenai/allennlp">AllenNLP</a></b> (🥇32 ·  ⭐ 11K) - 基于PyTorch的开源NLP研究库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/allenai/allennlp) (👨‍💻 250 · 🔀 2.1K · 📥 43 · 📦 2K · 📋 2.4K - 3% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/allenai/allennlp
	```
- [PyPi](https://pypi.org/project/allennlp) (📥 39K / month):
	```
	pip install allennlp
	```
</details>
<details><summary><b><a href="https://github.com/seatgeek/fuzzywuzzy">fuzzywuzzy</a></b> (🥇31 ·  ⭐ 8.5K) - Python中的模糊字符串匹配。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/seatgeek/fuzzywuzzy) (👨‍💻 70 · 🔀 860 · 📦 10K · 📋 180 - 43% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/seatgeek/fuzzywuzzy
	```
- [PyPi](https://pypi.org/project/fuzzywuzzy) (📥 4.9M / month):
	```
	pip install fuzzywuzzy
	```
- [Conda](https://anaconda.org/conda-forge/fuzzywuzzy) (📥 330K · ⏱️ 18.11.2020):
	```
	conda install -c conda-forge fuzzywuzzy
	```
</details>
<details><summary><b><a href="https://github.com/UKPLab/sentence-transformers">sentence-transformers</a></b> (🥇31 ·  ⭐ 6.2K) - BERT和XLNet的句子嵌入。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/UKPLab/sentence-transformers) (👨‍💻 64 · 🔀 1.2K · 📦 1.7K · 📋 1.1K - 49% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/UKPLab/sentence-transformers
	```
- [PyPi](https://pypi.org/project/sentence-transformers) (📥 530K / month):
	```
	pip install sentence-transformers
	```
</details>
<details><summary><b><a href="https://github.com/google/sentencepiece">sentencepiece</a></b> (🥇31 ·  ⭐ 5.4K) - 用于基于神经网络的文本的预处理器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/sentencepiece) (👨‍💻 57 · 🔀 720 · 📥 17K · 📦 10K · 📋 480 - 8% open · ⏱️ 02.07.2021):

	```
	git clone https://github.com/google/sentencepiece
	```
- [PyPi](https://pypi.org/project/sentencepiece) (📥 2.7M / month):
	```
	pip install sentencepiece
	```
- [Conda](https://anaconda.org/conda-forge/sentencepiece) (📥 100K · ⏱️ 09.02.2021):
	```
	conda install -c conda-forge sentencepiece
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fastText">fastText</a></b> (🥈30 ·  ⭐ 23K · 💀) - 用于快速文本表示和分类的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/fastText) (👨‍💻 58 · 🔀 4.2K · 📦 2.2K · 📋 990 - 39% open · ⏱️ 18.07.2020):

	```
	git clone https://github.com/facebookresearch/fastText
	```
- [PyPi](https://pypi.org/project/fasttext) (📥 400K / month):
	```
	pip install fasttext
	```
- [Conda](https://anaconda.org/conda-forge/fasttext) (📥 23K · ⏱️ 06.08.2021):
	```
	conda install -c conda-forge fasttext
	```
</details>
<details><summary><b><a href="https://github.com/flairNLP/flair">flair</a></b> (🥈30 ·  ⭐ 11K) - 一个用于最先进的自然语言处理的非常简单的框架。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/flairNLP/flair) (👨‍💻 210 · 🔀 1.4K · 📦 980 · 📋 1.7K - 4% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/flairNLP/flair
	```
- [PyPi](https://pypi.org/project/flair) (📥 100K / month):
	```
	pip install flair
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ParlAI">ParlAI</a></b> (🥈29 ·  ⭐ 8.4K) - 一个用于训练和评估AI模型的框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ParlAI) (👨‍💻 160 · 🔀 1.6K · 📦 46 · 📋 1.1K - 8% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/facebookresearch/ParlAI
	```
- [PyPi](https://pypi.org/project/parlai) (📥 3K / month):
	```
	pip install parlai
	```
</details>
<details><summary><b><a href="https://github.com/deepmipt/DeepPavlov">DeepPavlov</a></b> (🥈28 ·  ⭐ 5.4K) - 一个用于深度学习端到端对话的开源库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmipt/DeepPavlov) (👨‍💻 67 · 🔀 970 · 📦 220 · 📋 590 - 21% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/deepmipt/DeepPavlov
	```
- [PyPi](https://pypi.org/project/deeppavlov) (📥 10K / month):
	```
	pip install deeppavlov
	```
</details>
<details><summary><b><a href="https://github.com/OpenNMT/OpenNMT-py">OpenNMT</a></b> (🥈28 ·  ⭐ 5.3K) - PyTorch中的开源神经机器翻译。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/OpenNMT/OpenNMT-py) (👨‍💻 170 · 🔀 1.8K · 📦 110 · 📋 1.3K - 7% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/OpenNMT/OpenNMT-py
	```
- [PyPi](https://pypi.org/project/OpenNMT-py) (📥 4.6K / month):
	```
	pip install OpenNMT-py
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/tokenizers">Tokenizers</a></b> (🥈28 ·  ⭐ 4.9K) - 针对研究和应用进行了优化的快速最先进的分词器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/huggingface/tokenizers) (👨‍💻 46 · 🔀 390 · 📦 38 · 📋 510 - 26% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/huggingface/tokenizers
	```
- [PyPi](https://pypi.org/project/tokenizers) (📥 3.5M / month):
	```
	pip install tokenizers
	```
- [Conda](https://anaconda.org/conda-forge/tokenizers) (📥 92K · ⏱️ 22.09.2021):
	```
	conda install -c conda-forge tokenizers
	```
</details>
<details><summary><b><a href="https://github.com/rspeer/python-ftfy">ftfy</a></b> (🥈28 ·  ⭐ 3.1K) - 修复Unicode文本中的故障功能的工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rspeer/python-ftfy) (👨‍💻 18 · 🔀 100 · 📦 4K · 📋 120 - 6% open · ⏱️ 17.05.2021):

	```
	git clone https://github.com/LuminosoInsight/python-ftfy
	```
- [PyPi](https://pypi.org/project/ftfy) (📥 1.1M / month):
	```
	pip install ftfy
	```
- [Conda](https://anaconda.org/conda-forge/ftfy) (📥 130K · ⏱️ 25.05.2021):
	```
	conda install -c conda-forge ftfy
	```
</details>
<details><summary><b><a href="https://github.com/sloria/TextBlob">TextBlob</a></b> (🥈27 ·  ⭐ 7.9K) - 包含情感分析、词性标注等等功能的NLP工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sloria/TextBlob) (👨‍💻 34 · 🔀 1K · 📥 96 · 📦 15K · 📋 240 - 35% open · ⏱️ 10.05.2021):

	```
	git clone https://github.com/sloria/TextBlob
	```
- [PyPi](https://pypi.org/project/textblob):
	```
	pip install textblob
	```
- [Conda](https://anaconda.org/conda-forge/textblob) (📥 140K · ⏱️ 24.02.2019):
	```
	conda install -c conda-forge textblob
	```
</details>
<details><summary><b><a href="https://github.com/JohnSnowLabs/spark-nlp">spark-nlp</a></b> (🥈27 ·  ⭐ 2.4K) - 最先进的自然语言处理。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/JohnSnowLabs/spark-nlp) (👨‍💻 99 · 🔀 490 · 📋 560 - 13% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/JohnSnowLabs/spark-nlp
	```
- [PyPi](https://pypi.org/project/spark-nlp) (📥 1.2M / month):
	```
	pip install spark-nlp
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-nlp">GluonNLP</a></b> (🥈27 ·  ⭐ 2.3K) - 可轻松进行文本预处理，数据集加载和处理的工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dmlc/gluon-nlp) (👨‍💻 82 · 🔀 490 · 📦 600 · 📋 530 - 43% open · ⏱️ 24.08.2021):

	```
	git clone https://github.com/dmlc/gluon-nlp
	```
- [PyPi](https://pypi.org/project/gluonnlp) (📥 140K / month):
	```
	pip install gluonnlp
	```
</details>
<details><summary><b><a href="https://github.com/dedupeio/dedupe">Dedupe</a></b> (🥈26 ·  ⭐ 3.2K) - 一个用于准确和可扩展的模糊匹配的python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dedupeio/dedupe) (👨‍💻 59 · 🔀 430 · 📦 200 · 📋 660 - 9% open · ⏱️ 03.09.2021):

	```
	git clone https://github.com/dedupeio/dedupe
	```
- [PyPi](https://pypi.org/project/dedupe) (📥 230K / month):
	```
	pip install dedupe
	```
</details>
<details><summary><b><a href="https://github.com/explosion/spacy-transformers">spacy-transformers</a></b> (🥈26 ·  ⭐ 1K) - 使用经过预训练的transformer模型，例如BERT，XLNet和GPT-2。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>spacy</code></summary>

- [GitHub](https://github.com/explosion/spacy-transformers) (👨‍💻 17 · 🔀 120 · 📦 290 · ⏱️ 12.10.2021):

	```
	git clone https://github.com/explosion/spacy-transformers
	```
- [PyPi](https://pypi.org/project/spacy-transformers) (📥 70K / month):
	```
	pip install spacy-transformers
	```
</details>
<details><summary><b><a href="https://github.com/RasaHQ/rasa">Rasa</a></b> (🥈25 ·  ⭐ 13K) - 开源机器学习框架，可处理文本和语音多场景问题。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/RasaHQ/rasa) (👨‍💻 500 · 🔀 3.6K · 📋 5.9K - 12% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/RasaHQ/rasa
	```
- [PyPi](https://pypi.org/project/rasa) (📥 210K / month):
	```
	pip install rasa
	```
</details>
<details><summary><b><a href="https://github.com/Ciphey/Ciphey">Ciphey</a></b> (🥈25 ·  ⭐ 8.5K) - 在不知道密钥或密码的情况下自动解密加密。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Ciphey/Ciphey) (👨‍💻 46 · 🔀 500 · 📋 260 - 18% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/Ciphey/Ciphey
	```
- [PyPi](https://pypi.org/project/ciphey) (📥 16K / month):
	```
	pip install ciphey
	```
- [Docker Hub](https://hub.docker.com/r/remnux/ciphey) (📥 12K · ⭐ 5 · ⏱️ 06.06.2021):
	```
	docker pull remnux/ciphey
	```
</details>
<details><summary><b><a href="https://github.com/miso-belica/sumy">Sumy</a></b> (🥈25 ·  ⭐ 2.7K) - 自动汇总文本文档和HTML页面的模块。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/miso-belica/sumy) (👨‍💻 21 · 🔀 450 · 📦 930 · 📋 93 - 16% open · ⏱️ 17.06.2021):

	```
	git clone https://github.com/miso-belica/sumy
	```
- [PyPi](https://pypi.org/project/sumy) (📥 26K / month):
	```
	pip install sumy
	```
</details>
<details><summary><b><a href="https://github.com/life4/textdistance">TextDistance</a></b> (🥈25 ·  ⭐ 2.5K) - 计算序列之间的距离，包含30多种算法。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/life4/textdistance) (👨‍💻 11 · 🔀 200 · 📥 240 · 📦 1.1K · ⏱️ 29.07.2021):

	```
	git clone https://github.com/life4/textdistance
	```
- [PyPi](https://pypi.org/project/textdistance) (📥 230K / month):
	```
	pip install textdistance
	```
- [Conda](https://anaconda.org/conda-forge/textdistance) (📥 56K · ⏱️ 29.01.2021):
	```
	conda install -c conda-forge textdistance
	```
</details>
<details><summary><b><a href="https://github.com/deepset-ai/haystack">haystack</a></b> (🥈25 ·  ⭐ 2.5K) - 用于构建自然语言搜索的端到端Python框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepset-ai/haystack) (👨‍💻 72 · 🔀 500 · 📦 89 · 📋 900 - 14% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/deepset-ai/haystack
	```
- [PyPi](https://pypi.org/project/haystack) (📥 1.4K / month):
	```
	pip install haystack
	```
</details>
<details><summary><b><a href="https://github.com/cltk/cltk">CLTK</a></b> (🥈25 ·  ⭐ 690) - 古典语言工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cltk/cltk) (👨‍💻 110 · 🔀 300 · 📥 22 · 📦 180 · 📋 510 - 24% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/cltk/cltk
	```
- [PyPi](https://pypi.org/project/cltk) (📥 1.6K / month):
	```
	pip install cltk
	```
</details>
<details><summary><b><a href="https://github.com/stanfordnlp/stanza">stanza</a></b> (🥈24 ·  ⭐ 5.7K) - 斯坦福NLP官方Python语言库，支持多种语言。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/stanfordnlp/stanza) (👨‍💻 41 · 🔀 720 · 📦 680 · 📋 580 - 10% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/stanfordnlp/stanza
	```
- [PyPi](https://pypi.org/project/stanza) (📥 62K / month):
	```
	pip install stanza
	```
- [Conda](https://anaconda.org/stanfordnlp/stanza) (📥 4.2K · ⏱️ 05.10.2021):
	```
	conda install -c stanfordnlp stanza
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/text">torchtext</a></b> (🥈24 ·  ⭐ 2.9K) - 文本和NLP的数据加载器和抽象。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/text) (👨‍💻 110 · 🔀 630 · 📋 580 - 43% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/pytorch/text
	```
- [PyPi](https://pypi.org/project/torchtext) (📥 110K / month):
	```
	pip install torchtext
	```
</details>
<details><summary><b><a href="https://github.com/PetrochukM/PyTorch-NLP">pytorch-nlp</a></b> (🥈24 ·  ⭐ 2K) - PyTorch自然语言处理（NLP）的基本实用程序。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PetrochukM/PyTorch-NLP) (👨‍💻 18 · 🔀 240 · 📦 300 · 📋 64 - 23% open · ⏱️ 10.07.2021):

	```
	git clone https://github.com/PetrochukM/PyTorch-NLP
	```
- [PyPi](https://pypi.org/project/pytorch-nlp) (📥 5.6K / month):
	```
	pip install pytorch-nlp
	```
</details>
<details><summary><b><a href="https://github.com/DerwenAI/pytextrank">PyTextRank</a></b> (🥈24 ·  ⭐ 1.6K) - TextRank的Python实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/DerwenAI/pytextrank) (👨‍💻 17 · 🔀 280 · 📦 190 · 📋 79 - 27% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/DerwenAI/pytextrank
	```
- [PyPi](https://pypi.org/project/pytextrank) (📥 16K / month):
	```
	pip install pytextrank
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/fairseq">fairseq</a></b> (🥈23 ·  ⭐ 14K · 📉) - 用Python编写的Facebook AI Research Sequence-to-Sequence工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/fairseq) (👨‍💻 360 · 🔀 3.5K · 📥 150 · 📦 540 · 📋 3K - 33% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/pytorch/fairseq
	```
- [PyPi](https://pypi.org/project/fairseq):
	```
	pip install fairseq
	```
</details>
<details><summary><b><a href="https://github.com/cjhutto/vaderSentiment">vaderSentiment</a></b> (🥈23 ·  ⭐ 3.2K · 💤) - VADER情感分析。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cjhutto/vaderSentiment) (👨‍💻 10 · 🔀 810 · 📦 3.1K · 📋 100 - 26% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/cjhutto/vaderSentiment
	```
- [PyPi](https://pypi.org/project/vadersentiment) (📥 170K / month):
	```
	pip install vadersentiment
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/neuralcoref">neuralcoref</a></b> (🥈23 ·  ⭐ 2.4K) - 基于SpaCy的神经网络实现快速共指解析。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/huggingface/neuralcoref) (👨‍💻 21 · 🔀 420 · 📥 260 · 📦 400 · 📋 280 - 20% open · ⏱️ 22.06.2021):

	```
	git clone https://github.com/huggingface/neuralcoref
	```
- [PyPi](https://pypi.org/project/neuralcoref):
	```
	pip install neuralcoref
	```
- [Conda](https://anaconda.org/conda-forge/neuralcoref) (📥 9.9K · ⏱️ 21.02.2020):
	```
	conda install -c conda-forge neuralcoref
	```
</details>
<details><summary><b><a href="https://github.com/aboSamoor/polyglot">polyglot</a></b> (🥈23 ·  ⭐ 1.9K · 💀) - 多语言文本（NLP）处理工具包。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/aboSamoor/polyglot) (👨‍💻 26 · 🔀 300 · 📦 580 · 📋 200 - 67% open · ⏱️ 22.09.2020):

	```
	git clone https://github.com/aboSamoor/polyglot
	```
- [PyPi](https://pypi.org/project/polyglot) (📥 74K / month):
	```
	pip install polyglot
	```
</details>
<details><summary><b><a href="https://github.com/deepset-ai/FARM">FARM</a></b> (🥈23 ·  ⭐ 1.4K) - NLP的快速和轻松迁移学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepset-ai/FARM) (👨‍💻 35 · 🔀 210 · 📋 390 - 5% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/deepset-ai/FARM
	```
- [PyPi](https://pypi.org/project/farm) (📥 9.2K / month):
	```
	pip install farm
	```
</details>
<details><summary><b><a href="https://github.com/explosion/sense2vec">sense2vec</a></b> (🥈23 ·  ⭐ 1.3K) - 上下文相关性构建词向量。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/sense2vec) (👨‍💻 17 · 🔀 210 · 📥 21K · 📦 88 · 📋 100 - 15% open · ⏱️ 16.08.2021):

	```
	git clone https://github.com/explosion/sense2vec
	```
- [PyPi](https://pypi.org/project/sense2vec) (📥 3.5K / month):
	```
	pip install sense2vec
	```
- [Conda](https://anaconda.org/conda-forge/sense2vec) (📥 23K · ⏱️ 14.07.2021):
	```
	conda install -c conda-forge sense2vec
	```
</details>
<details><summary><b><a href="https://github.com/WojciechMula/pyahocorasick">pyahocorasick</a></b> (🥈23 ·  ⭐ 640 · 💤) - Python文本工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/WojciechMula/pyahocorasick) (👨‍💻 21 · 🔀 93 · 📦 770 · 📋 100 - 32% open · ⏱️ 27.03.2021):

	```
	git clone https://github.com/WojciechMula/pyahocorasick
	```
- [PyPi](https://pypi.org/project/pyahocorasick) (📥 230K / month):
	```
	pip install pyahocorasick
	```
- [Conda](https://anaconda.org/conda-forge/pyahocorasick) (📥 130K · ⏱️ 13.10.2020):
	```
	conda install -c conda-forge pyahocorasick
	```
</details>
<details><summary><b><a href="https://github.com/snowballstem/snowball">snowballstemmer</a></b> (🥈23 ·  ⭐ 530) - Snowball编译器和词干算法。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/snowballstem/snowball) (👨‍💻 27 · 🔀 140 · 📦 4 · 📋 56 - 21% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/snowballstem/snowball
	```
- [PyPi](https://pypi.org/project/snowballstemmer) (📥 5.2M / month):
	```
	pip install snowballstemmer
	```
- [Conda](https://anaconda.org/conda-forge/snowballstemmer) (📥 3.2M · ⏱️ 21.01.2021):
	```
	conda install -c conda-forge snowballstemmer
	```
</details>
<details><summary><b><a href="https://github.com/google-research/text-to-text-transfer-transformer">T5</a></b> (🥉22 ·  ⭐ 3.7K) - 探索迁移学习的论文源码<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/text-to-text-transfer-transformer) (👨‍💻 41 · 🔀 500 · 📦 53 · 📋 360 - 9% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/google-research/text-to-text-transfer-transformer
	```
- [PyPi](https://pypi.org/project/t5) (📥 54K / month):
	```
	pip install t5
	```
</details>
<details><summary><b><a href="https://github.com/asyml/texar">Texar</a></b> (🥉22 ·  ⭐ 2.2K · 💀) - 机器学习，自然语言处理等工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/asyml/texar) (👨‍💻 43 · 🔀 360 · 📦 17 · 📋 160 - 19% open · ⏱️ 29.07.2020):

	```
	git clone https://github.com/asyml/texar
	```
- [PyPi](https://pypi.org/project/texar) (📥 130 / month):
	```
	pip install texar
	```
</details>
<details><summary><b><a href="https://github.com/JasonKessler/scattertext">scattertext</a></b> (🥉22 ·  ⭐ 1.7K) - 文件之间语言分布的漂亮可视化效果。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JasonKessler/scattertext) (👨‍💻 11 · 🔀 230 · 📦 220 · 📋 81 - 19% open · ⏱️ 07.07.2021):

	```
	git clone https://github.com/JasonKessler/scattertext
	```
- [PyPi](https://pypi.org/project/scattertext) (📥 3.1K / month):
	```
	pip install scattertext
	```
- [Conda](https://anaconda.org/conda-forge/scattertext) (📥 57K · ⏱️ 07.07.2021):
	```
	conda install -c conda-forge scattertext
	```
</details>
<details><summary><b><a href="https://github.com/jamesturk/jellyfish">jellyfish</a></b> (🥉22 ·  ⭐ 1.5K) - 一个python库，用于进行文本相似度和距离计算。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jamesturk/jellyfish) (👨‍💻 23 · 🔀 140 · 📦 2.8K · 📋 100 - 8% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/jamesturk/jellyfish
	```
- [PyPi](https://pypi.org/project/jellyfish):
	```
	pip install jellyfish
	```
- [Conda](https://anaconda.org/conda-forge/jellyfish) (📥 150K · ⏱️ 27.09.2021):
	```
	conda install -c conda-forge jellyfish
	```
</details>
<details><summary><b><a href="https://github.com/allenai/scispacy">SciSpacy</a></b> (🥉22 ·  ⭐ 1K) - 完整的科学/生物医学的SpaCy应用案例。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/allenai/scispacy) (👨‍💻 21 · 🔀 140 · 📦 340 · 📋 220 - 13% open · ⏱️ 15.07.2021):

	```
	git clone https://github.com/allenai/scispacy
	```
- [PyPi](https://pypi.org/project/scispacy) (📥 30K / month):
	```
	pip install scispacy
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/text">TensorFlow Text</a></b> (🥉22 ·  ⭐ 830 · 📉) - TensorFlow文本处理。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/text) (👨‍💻 57 · 🔀 130 · 📦 1K · 📋 130 - 18% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/tensorflow/text
	```
- [PyPi](https://pypi.org/project/tensorflow-text):
	```
	pip install tensorflow-text
	```
</details>
<details><summary><b><a href="https://github.com/nipunsadvilkar/pySBD">pySBD</a></b> (🥉22 ·  ⭐ 370 · 💤) - pySBD（Python句子边界歧义消除）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nipunsadvilkar/pySBD) (👨‍💻 6 · 🔀 40 · 📦 220 · 📋 59 - 18% open · ⏱️ 11.02.2021):

	```
	git clone https://github.com/nipunsadvilkar/pySBD
	```
- [PyPi](https://pypi.org/project/pysbd) (📥 39K / month):
	```
	pip install pysbd
	```
</details>
<details><summary><b><a href="https://github.com/Alir3z4/python-stop-words">stop-words</a></b> (🥉22 ·  ⭐ 130 · 💀) - 获取Python中各种语言的常用停用词表。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Alir3z4/python-stop-words) (👨‍💻 8 · 🔀 23 · 📦 1.3K · 📋 12 - 25% open · ⏱️ 23.07.2018):

	```
	git clone https://github.com/Alir3z4/python-stop-words
	```
- [PyPi](https://pypi.org/project/stop-words) (📥 150K / month):
	```
	pip install stop-words
	```
</details>
<details><summary><b><a href="https://github.com/minimaxir/textgenrnn">textgenrnn</a></b> (🥉21 ·  ⭐ 4.5K · 💀) - 轻松地训练自己的文本生成神经网络。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/minimaxir/textgenrnn) (👨‍💻 19 · 🔀 700 · 📥 580 · 📦 940 · 📋 200 - 56% open · ⏱️ 14.07.2020):

	```
	git clone https://github.com/minimaxir/textgenrnn
	```
- [PyPi](https://pypi.org/project/textgenrnn) (📥 590 / month):
	```
	pip install textgenrnn
	```
</details>
<details><summary><b><a href="https://github.com/NTMC-Community/MatchZoo">MatchZoo</a></b> (🥉21 ·  ⭐ 3.5K) - 便于深层设计，比较和共享的工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NTMC-Community/MatchZoo) (👨‍💻 36 · 🔀 890 · 📦 10 · 📋 460 - 6% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/NTMC-Community/MatchZoo
	```
- [PyPi](https://pypi.org/project/matchzoo) (📥 250 / month):
	```
	pip install matchzoo
	```
</details>
<details><summary><b><a href="https://github.com/daviddrysdale/python-phonenumbers">phonenumbers</a></b> (🥉21 ·  ⭐ 2.8K) - Google的libphonenumber的Python端口。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/daviddrysdale/python-phonenumbers) (👨‍💻 25 · 🔀 340 · 📋 130 - 2% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/daviddrysdale/python-phonenumbers
	```
- [PyPi](https://pypi.org/project/phonenumbers) (📥 2.2M / month):
	```
	pip install phonenumbers
	```
- [Conda](https://anaconda.org/conda-forge/phonenumbers) (📥 480K · ⏱️ 07.10.2021):
	```
	conda install -c conda-forge phonenumbers
	```
</details>
<details><summary><b><a href="https://github.com/jbesomi/texthero">Texthero</a></b> (🥉21 ·  ⭐ 2.4K) - 文本预处理，表示和可视化从入门到精通。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jbesomi/texthero) (👨‍💻 18 · 🔀 200 · 📥 83 · 📋 100 - 43% open · ⏱️ 19.07.2021):

	```
	git clone https://github.com/jbesomi/texthero
	```
- [PyPi](https://pypi.org/project/texthero) (📥 14K / month):
	```
	pip install texthero
	```
</details>
<details><summary><b><a href="https://github.com/saffsd/langid.py">langid</a></b> (🥉21 ·  ⭐ 1.9K · 💀) - 独立的语言识别系统。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/saffsd/langid.py) (👨‍💻 9 · 🔀 270 · 📦 810 · 📋 71 - 36% open · ⏱️ 15.07.2017):

	```
	git clone https://github.com/saffsd/langid.py
	```
- [PyPi](https://pypi.org/project/langid) (📥 350K / month):
	```
	pip install langid
	```
</details>
<details><summary><b><a href="https://github.com/Hironsan/anago">anaGo</a></b> (🥉21 ·  ⭐ 1.4K) - 双向LSTM-CRF和ELMo实现，可用于命名实体识别和文本分类等任务。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Hironsan/anago) (👨‍💻 11 · 🔀 360 · 📦 27 · 📋 110 - 33% open · ⏱️ 01.04.2021):

	```
	git clone https://github.com/Hironsan/anago
	```
- [PyPi](https://pypi.org/project/anago) (📥 700 / month):
	```
	pip install anago
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytext">PyText</a></b> (🥉20 ·  ⭐ 6.3K) - 基于PyTorch的自然语言建模框架。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pytext) (👨‍💻 210 · 🔀 790 · 📥 270 · 📦 99 · 📋 130 - 44% open · ⏱️ 09.10.2021):

	```
	git clone https://github.com/facebookresearch/pytext
	```
- [PyPi](https://pypi.org/project/pytext-nlp) (📥 280 / month):
	```
	pip install pytext-nlp
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/NeMo">NeMo</a></b> (🥉20 ·  ⭐ 3.4K) - NeMo：用于智能对话的工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NVIDIA/NeMo) (👨‍💻 110 · 🔀 680 · 📥 11K · 📋 770 - 8% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/NVIDIA/NeMo
	```
- [PyPi](https://pypi.org/project/nemo-toolkit) (📥 4.3K / month):
	```
	pip install nemo-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/nlp-architect">NLP Architect</a></b> (🥉20 ·  ⭐ 2.7K) - 用于探索最先进的深度学习的模型库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IntelLabs/nlp-architect) (👨‍💻 37 · 🔀 420 · 📦 8 · 📋 130 - 11% open · ⏱️ 12.09.2021):

	```
	git clone https://github.com/IntelLabs/nlp-architect
	```
- [PyPi](https://pypi.org/project/nlp-architect) (📥 280 / month):
	```
	pip install nlp-architect
	```
</details>
<details><summary><b><a href="https://github.com/fastnlp/fastNLP">fastNLP</a></b> (🥉20 ·  ⭐ 2.3K) - fastNLP：模块化和可扩展的NLP框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fastnlp/fastNLP) (👨‍💻 50 · 🔀 390 · 📥 65 · 📦 41 · 📋 170 - 17% open · ⏱️ 13.07.2021):

	```
	git clone https://github.com/fastnlp/fastNLP
	```
- [PyPi](https://pypi.org/project/fastnlp):
	```
	pip install fastnlp
	```
</details>
<details><summary><b><a href="https://github.com/Delta-ML/delta">DELTA</a></b> (🥉20 ·  ⭐ 1.5K · 💤) - DELTA是一个基于深度学习的自然语言和语音处理平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Delta-ML/delta) (👨‍💻 41 · 🔀 290 · 📋 75 - 1% open · ⏱️ 17.12.2020):

	```
	git clone https://github.com/Delta-ML/delta
	```
- [PyPi](https://pypi.org/project/delta-nlp) (📥 18 / month):
	```
	pip install delta-nlp
	```
- [Docker Hub](https://hub.docker.com/r/zh794390558/delta) (📥 13K · ⏱️ 03.08.2021):
	```
	docker pull zh794390558/delta
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/sockeye">Sockeye</a></b> (🥉20 ·  ⭐ 1K) - 序列到序列框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/sockeye) (👨‍💻 53 · 🔀 280 · 📥 6 · 📋 250 - 6% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/awslabs/sockeye
	```
- [PyPi](https://pypi.org/project/sockeye) (📥 510 / month):
	```
	pip install sockeye
	```
</details>
<details><summary><b><a href="https://github.com/VKCOM/YouTokenToMe">YouTokenToMe</a></b> (🥉20 ·  ⭐ 770 · 💤) - 用于基于神经网络的文本的预处理器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/VKCOM/YouTokenToMe) (👨‍💻 6 · 🔀 54 · 📦 150 · 📋 49 - 55% open · ⏱️ 28.01.2021):

	```
	git clone https://github.com/vkcom/youtokentome
	```
- [PyPi](https://pypi.org/project/youtokentome) (📥 14K / month):
	```
	pip install youtokentome
	```
</details>
<details><summary><b><a href="https://github.com/jaraco/inflect">inflect</a></b> (🥉20 ·  ⭐ 580 · 💤) - 辅助功能，正确生成复数，序数，不定冠词，转换数字。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jaraco/inflect) (👨‍💻 29 · 🔀 62 · 📋 80 - 21% open · ⏱️ 23.03.2021):

	```
	git clone https://github.com/jaraco/inflect
	```
- [PyPi](https://pypi.org/project/inflect) (📥 1.4M / month):
	```
	pip install inflect
	```
- [Conda](https://anaconda.org/conda-forge/inflect) (📥 180K · ⏱️ 06.07.2021):
	```
	conda install -c conda-forge inflect
	```
</details>
<details><summary><b><a href="https://github.com/BrikerMan/Kashgari">Kashgari</a></b> (🥉19 ·  ⭐ 2.2K) - Kashgari是工业级的NLP迁移学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BrikerMan/Kashgari) (👨‍💻 21 · 🔀 410 · 📦 42 · 📋 350 - 8% open · ⏱️ 09.07.2021):

	```
	git clone https://github.com/BrikerMan/Kashgari
	```
- [PyPi](https://pypi.org/project/kashgari-tf) (📥 82 / month):
	```
	pip install kashgari-tf
	```
</details>
<details><summary><b><a href="https://github.com/utterworks/fast-bert">fast-bert</a></b> (🥉19 ·  ⭐ 1.7K) - 用于基于BERT的NLP模型的简单易用工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/utterworks/fast-bert) (👨‍💻 35 · 🔀 320 · 📋 240 - 60% open · ⏱️ 31.08.2021):

	```
	git clone https://github.com/kaushaltrivedi/fast-bert
	```
- [PyPi](https://pypi.org/project/fast-bert) (📥 1.8K / month):
	```
	pip install fast-bert
	```
</details>
<details><summary><b><a href="https://github.com/vrasneur/pyfasttext">pyfasttext</a></b> (🥉19 ·  ⭐ 230 · 💀) - fastText的另一个Python接口。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/vrasneur/pyfasttext) (👨‍💻 4 · 🔀 30 · 📥 340 · 📦 180 · 📋 49 - 42% open · ⏱️ 08.12.2018):

	```
	git clone https://github.com/vrasneur/pyfasttext
	```
- [PyPi](https://pypi.org/project/pyfasttext) (📥 3.8K / month):
	```
	pip install pyfasttext
	```
</details>
<details><summary><b><a href="https://github.com/snipsco/snips-nlu">Snips NLU</a></b> (🥉18 ·  ⭐ 3.6K) - 从文本中提取含义的Python库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/snipsco/snips-nlu) (👨‍💻 22 · 🔀 480 · 📋 250 - 21% open · ⏱️ 03.05.2021):

	```
	git clone https://github.com/snipsco/snips-nlu
	```
- [PyPi](https://pypi.org/project/snips-nlu):
	```
	pip install snips-nlu
	```
</details>
<details><summary><b><a href="https://github.com/minimaxir/gpt-2-simple">gpt-2-simple</a></b> (🥉18 ·  ⭐ 2.8K · 💤) - 可轻松重新训练OpenAI的GPT-2文本模型的Python软件包。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/minimaxir/gpt-2-simple) (👨‍💻 17 · 🔀 560 · 📥 270 · 📋 230 - 59% open · ⏱️ 14.02.2021):

	```
	git clone https://github.com/minimaxir/gpt-2-simple
	```
- [PyPi](https://pypi.org/project/gpt-2-simple) (📥 8.3K / month):
	```
	pip install gpt-2-simple
	```
</details>
<details><summary><b><a href="https://github.com/IndicoDataSolutions/finetune">finetune</a></b> (🥉18 ·  ⭐ 650) - 针对NLP的Scikit风格模型微调。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/IndicoDataSolutions/finetune) (👨‍💻 19 · 🔀 69 · 📦 9 · 📋 140 - 15% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/IndicoDataSolutions/finetune
	```
- [PyPi](https://pypi.org/project/finetune) (📥 100 / month):
	```
	pip install finetune
	```
</details>
<details><summary><b><a href="https://github.com/vi3k6i5/flashtext">flashtext</a></b> (🥉17 ·  ⭐ 5K · 💀) - 从句子中提取关键字或替换句子中的关键字。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vi3k6i5/flashtext) (👨‍💻 7 · 🔀 550 · 📦 590 · 📋 94 - 46% open · ⏱️ 03.05.2020):

	```
	git clone https://github.com/vi3k6i5/flashtext
	```
- [PyPi](https://pypi.org/project/flashtext):
	```
	pip install flashtext
	```
</details>
<details><summary><b><a href="https://github.com/chartbeat-labs/textacy">textacy</a></b> (🥉17 ·  ⭐ 1.8K) - spaCy之前和之后的NLP。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/chartbeat-labs/textacy) (👨‍💻 31 · 🔀 220 · 📋 240 - 13% open · ⏱️ 31.05.2021):

	```
	git clone https://github.com/chartbeat-labs/textacy
	```
- [PyPi](https://pypi.org/project/textacy) (📥 31K / month):
	```
	pip install textacy
	```
- [Conda](https://anaconda.org/conda-forge/textacy) (📥 99K · ⏱️ 13.04.2021):
	```
	conda install -c conda-forge textacy
	```
</details>
<details><summary><b><a href="https://github.com/Franck-Dernoncourt/NeuroNER">NeuroNER</a></b> (🥉17 ·  ⭐ 1.6K · 💀) - 使用神经网络的命名实体识别。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Franck-Dernoncourt/NeuroNER) (👨‍💻 7 · 🔀 440 · 📦 13 · 📋 150 - 54% open · ⏱️ 02.10.2019):

	```
	git clone https://github.com/Franck-Dernoncourt/NeuroNER
	```
- [PyPi](https://pypi.org/project/pyneuroner) (📥 120 / month):
	```
	pip install pyneuroner
	```
</details>
<details><summary><b><a href="https://github.com/PKSHATechnology-Research/camphr">Camphr</a></b> (🥉17 ·  ⭐ 340) - 适用于Transformers，Udify，ELmo等的spaCy插件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>spacy</code></summary>

- [GitHub](https://github.com/PKSHATechnology-Research/camphr) (👨‍💻 7 · 🔀 17 · 📋 27 - 7% open · ⏱️ 18.08.2021):

	```
	git clone https://github.com/PKSHATechnology-Research/camphr
	```
- [PyPi](https://pypi.org/project/camphr) (📥 580 / month):
	```
	pip install camphr
	```
</details>
<details><summary><b><a href="https://github.com/textpipe/textpipe">textpipe</a></b> (🥉17 ·  ⭐ 290) - Textpipe：从文本中清理并提取元数据。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/textpipe/textpipe) (👨‍💻 28 · 🔀 22 · 📦 7 · 📋 40 - 37% open · ⏱️ 09.06.2021):

	```
	git clone https://github.com/textpipe/textpipe
	```
- [PyPi](https://pypi.org/project/textpipe) (📥 1.4K / month):
	```
	pip install textpipe
	```
</details>
<details><summary><b><a href="https://github.com/anhaidgroup/deepmatcher">DeepMatcher</a></b> (🥉16 ·  ⭐ 370) - 用于实体和文本匹配的Python包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anhaidgroup/deepmatcher) (👨‍💻 7 · 🔀 85 · 📦 14 · 📋 76 - 71% open · ⏱️ 13.06.2021):

	```
	git clone https://github.com/anhaidgroup/deepmatcher
	```
- [PyPi](https://pypi.org/project/deepmatcher) (📥 600 / month):
	```
	pip install deepmatcher
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/translate">Translate</a></b> (🥉15 ·  ⭐ 710) - Translate-PyTorch NLP库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/translate) (👨‍💻 87 · 🔀 170 · 📋 38 - 28% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/pytorch/translate
	```
- [PyPi](https://pypi.org/project/pytorch-translate) (📥 6 / month):
	```
	pip install pytorch-translate
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenNRE">OpenNRE</a></b> (🥉14 ·  ⭐ 3.3K) - 神经关系提取（NRE）的开源软件包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thunlp/OpenNRE) (👨‍💻 9 · 🔀 880 · 📋 330 - 3% open · ⏱️ 31.05.2021):

	```
	git clone https://github.com/thunlp/OpenNRE
	```
</details>
<details><summary><b><a href="https://github.com/feedly/transfer-nlp">TransferNLP</a></b> (🥉14 ·  ⭐ 290 · 💀) - 用于可重复的实验的NLP库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/feedly/transfer-nlp) (👨‍💻 7 · 🔀 16 · 📋 23 - 13% open · ⏱️ 28.05.2020):

	```
	git clone https://github.com/feedly/transfer-nlp
	```
- [PyPi](https://pypi.org/project/transfer-nlp) (📥 140 / month):
	```
	pip install transfer-nlp
	```
</details>
<details><summary><b><a href="https://github.com/victordibia/neuralqa">NeuralQA</a></b> (🥉14 ·  ⭐ 210 · 💤) - NeuralQA：用于对大型数据集进行问答构建。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/victordibia/neuralqa) (👨‍💻 3 · 🔀 30 · 📦 2 · 📋 28 - 71% open · ⏱️ 16.12.2020):

	```
	git clone https://github.com/victordibia/neuralqa
	```
- [PyPi](https://pypi.org/project/neuralqa) (📥 95 / month):
	```
	pip install neuralqa
	```
</details>
<details><summary><b><a href="https://github.com/abelriboulot/onnxt5">ONNX-T5</a></b> (🥉14 ·  ⭐ 180 · 💤) - 文本摘要，翻译，情感分析，文本生成等实现。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/abelriboulot/onnxt5) (👨‍💻 3 · 🔀 23 · 📋 14 - 42% open · ⏱️ 28.01.2021):

	```
	git clone https://github.com/abelriboulot/onnxt5
	```
- [PyPi](https://pypi.org/project/onnxt5) (📥 140 / month):
	```
	pip install onnxt5
	```
</details>
<details><summary><b><a href="https://github.com/textvec/textvec">textvec</a></b> (🥉14 ·  ⭐ 180 · 💤) - 胜过TF-IDF文本向量化工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/textvec/textvec) (👨‍💻 4 · 🔀 21 · 📦 4 · 📋 9 - 33% open · ⏱️ 03.12.2020):

	```
	git clone https://github.com/textvec/textvec
	```
- [PyPi](https://pypi.org/project/textvec) (📥 260 / month):
	```
	pip install textvec
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/vizseq">VizSeq</a></b> (🥉13 ·  ⭐ 360) - 用于自然语言生成的分析工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/vizseq) (👨‍💻 3 · 🔀 41 · 📦 2 · 📋 15 - 40% open · ⏱️ 02.09.2021):

	```
	git clone https://github.com/facebookresearch/vizseq
	```
- [PyPi](https://pypi.org/project/vizseq) (📥 250 / month):
	```
	pip install vizseq
	```
</details>
<details><summary><b><a href="https://github.com/shaypal5/skift">skift</a></b> (🥉13 ·  ⭐ 220 · 💤) - 适用于Python fastText的scikit-learn包装器。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/shaypal5/skift) (👨‍💻 7 · 🔀 20 · 📦 10 · 📋 10 - 20% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/shaypal5/skift
	```
- [PyPi](https://pypi.org/project/skift) (📥 540 / month):
	```
	pip install skift
	```
</details>
<details><summary><b><a href="https://github.com/as-ideas/headliner">Headliner</a></b> (🥉12 ·  ⭐ 230 · 💀) - 轻松训练和部署seq2seq模型。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/as-ideas/headliner) (👨‍💻 2 · 🔀 40 · 📦 3 · 📋 14 - 7% open · ⏱️ 14.02.2020):

	```
	git clone https://github.com/as-ideas/headliner
	```
- [PyPi](https://pypi.org/project/headliner) (📥 150 / month):
	```
	pip install headliner
	```
</details>
<br>

## 图像数据与CV

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于图像和视频处理，操纵和扩充的库，以及用于计算机视觉任务（例如面部识别，对象检测和图像分类）的库。_

<details><summary><b><a href="https://github.com/python-pillow/Pillow">Pillow</a></b> (🥇40 ·  ⭐ 9K) - 友好的PIL分支（Python Imaging Library）。<code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code></summary>

- [GitHub](https://github.com/python-pillow/Pillow) (👨‍💻 370 · 🔀 1.6K · 📦 570K · 📋 2.3K - 6% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/python-pillow/Pillow
	```
- [PyPi](https://pypi.org/project/Pillow) (📥 35M / month):
	```
	pip install Pillow
	```
- [Conda](https://anaconda.org/conda-forge/pillow) (📥 11M · ⏱️ 03.09.2021):
	```
	conda install -c conda-forge pillow
	```
</details>
<details><summary><b><a href="https://github.com/albumentations-team/albumentations">Albumentations</a></b> (🥇32 ·  ⭐ 8.9K) - 快速的图像增强库和易于使用的包装器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/albumentations-team/albumentations) (👨‍💻 95 · 🔀 1.1K · 📦 5.3K · 📋 510 - 38% open · ⏱️ 09.10.2021):

	```
	git clone https://github.com/albumentations-team/albumentations
	```
- [PyPi](https://pypi.org/project/albumentations) (📥 170K / month):
	```
	pip install albumentations
	```
- [Conda](https://anaconda.org/conda-forge/albumentations) (📥 26K · ⏱️ 15.07.2021):
	```
	conda install -c conda-forge albumentations
	```
</details>
<details><summary><b><a href="https://github.com/Zulko/moviepy">MoviePy</a></b> (🥇32 ·  ⭐ 8.6K) - 使用Python进行视频编辑。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Zulko/moviepy) (👨‍💻 140 · 🔀 1.1K · 📦 11K · 📋 1.1K - 28% open · ⏱️ 19.08.2021):

	```
	git clone https://github.com/Zulko/moviepy
	```
- [PyPi](https://pypi.org/project/moviepy) (📥 1.5M / month):
	```
	pip install moviepy
	```
- [Conda](https://anaconda.org/conda-forge/moviepy) (📥 94K · ⏱️ 23.02.2020):
	```
	conda install -c conda-forge moviepy
	```
</details>
<details><summary><b><a href="https://github.com/imageio/imageio">imageio</a></b> (🥇32 ·  ⭐ 930) - 用于读取和写入图像数据的Python库。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/imageio/imageio) (👨‍💻 80 · 🔀 180 · 📦 49K · 📋 380 - 17% open · ⏱️ 08.09.2021):

	```
	git clone https://github.com/imageio/imageio
	```
- [PyPi](https://pypi.org/project/imageio) (📥 16M / month):
	```
	pip install imageio
	```
- [Conda](https://anaconda.org/conda-forge/imageio) (📥 2.3M · ⏱️ 06.07.2020):
	```
	conda install -c conda-forge imageio
	```
</details>
<details><summary><b><a href="https://github.com/aleju/imgaug">imgaug</a></b> (🥇31 ·  ⭐ 12K · 💀) - 用于机器学习实验的图像增强。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aleju/imgaug) (👨‍💻 36 · 🔀 2.1K · 📦 7.8K · 📋 460 - 53% open · ⏱️ 01.06.2020):

	```
	git clone https://github.com/aleju/imgaug
	```
- [PyPi](https://pypi.org/project/imgaug) (📥 250K / month):
	```
	pip install imgaug
	```
- [Conda](https://anaconda.org/conda-forge/imgaug) (📥 54K · ⏱️ 14.02.2020):
	```
	conda install -c conda-forge imgaug
	```
</details>
<details><summary><b><a href="https://github.com/emcconville/wand">Wand</a></b> (🥇31 ·  ⭐ 1.1K) - 用于Python的基于ctypes的简单ImageMagick接口。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/emcconville/wand) (👨‍💻 96 · 🔀 180 · 📥 5.3K · 📦 6.8K · 📋 360 - 3% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/emcconville/wand
	```
- [PyPi](https://pypi.org/project/wand) (📥 410K / month):
	```
	pip install wand
	```
</details>
<details><summary><b><a href="https://github.com/rwightman/pytorch-image-models">PyTorch Image Models</a></b> (🥈30 ·  ⭐ 14K) - PyTorch图像模型，脚本，预训练权重。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rwightman/pytorch-image-models) (👨‍💻 58 · 🔀 2.1K · 📥 640K · 📦 1.2K · 📋 380 - 8% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/rwightman/pytorch-image-models
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/vision">torchvision</a></b> (🥈29 ·  ⭐ 10K) - 计算机视觉的数据集，转换和模型。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/vision) (👨‍💻 430 · 🔀 5.1K · 📋 1.9K - 21% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/pytorch/vision
	```
- [PyPi](https://pypi.org/project/torchvision) (📥 2.7M / month):
	```
	pip install torchvision
	```
- [Conda](https://anaconda.org/conda-forge/torchvision) (📥 130K · ⏱️ 27.09.2021):
	```
	conda install -c conda-forge torchvision
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-cv">GluonCV</a></b> (🥈29 ·  ⭐ 4.9K) - Gluon CV工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dmlc/gluon-cv) (👨‍💻 110 · 🔀 1.1K · 📦 580 · 📋 780 - 6% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/dmlc/gluon-cv
	```
- [PyPi](https://pypi.org/project/gluoncv) (📥 660K / month):
	```
	pip install gluoncv
	```
</details>
<details><summary><b><a href="https://github.com/scikit-image/scikit-image">scikit-image</a></b> (🥈29 ·  ⭐ 4.5K) - Python中的图像处理。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/scikit-image/scikit-image) (👨‍💻 520 · 🔀 1.8K · 📦 83K · 📋 2.1K - 24% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/scikit-image/scikit-image
	```
- [PyPi](https://pypi.org/project/scikit-image):
	```
	pip install scikit-image
	```
- [Conda](https://anaconda.org/conda-forge/scikit-image) (📥 2.9M · ⏱️ 04.09.2021):
	```
	conda install -c conda-forge scikit-image
	```
</details>
<details><summary><b><a href="https://github.com/PyImageSearch/imutils">imutils</a></b> (🥈28 ·  ⭐ 3.8K · 💤) - 图像处理库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyImageSearch/imutils) (👨‍💻 20 · 🔀 920 · 📦 20K · 📋 160 - 52% open · ⏱️ 15.01.2021):

	```
	git clone https://github.com/jrosebr1/imutils
	```
- [PyPi](https://pypi.org/project/imutils) (📥 620K / month):
	```
	pip install imutils
	```
- [Conda](https://anaconda.org/conda-forge/imutils) (📥 68K · ⏱️ 15.01.2021):
	```
	conda install -c conda-forge imutils
	```
</details>
<details><summary><b><a href="https://github.com/kornia/kornia">Kornia</a></b> (🥈27 ·  ⭐ 5.1K) - PyTorch的开源可微分计算机视觉库。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kornia/kornia) (👨‍💻 130 · 🔀 480 · 📥 130 · 📦 650 · 📋 460 - 20% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/kornia/kornia
	```
- [PyPi](https://pypi.org/project/kornia) (📥 160K / month):
	```
	pip install kornia
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/detectron2">detectron2</a></b> (🥈26 ·  ⭐ 18K) - Detectron2是Facebook FAIR的高级目标检测平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/detectron2) (👨‍💻 190 · 🔀 4.6K · 📦 360 · 📋 2.7K - 4% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/facebookresearch/detectron2
	```
- [Conda](https://anaconda.org/conda-forge/detectron2) (📥 32K · ⏱️ 30.07.2021):
	```
	conda install -c conda-forge detectron2
	```
</details>
<details><summary><b><a href="https://github.com/open-mmlab/mmdetection">MMDetection</a></b> (🥈26 ·  ⭐ 17K) - OpenMMLab检测工具箱。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/open-mmlab/mmdetection) (👨‍💻 270 · 🔀 5.4K · 📦 140 · 📋 4.5K - 5% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/open-mmlab/mmdetection
	```
</details>
<details><summary><b><a href="https://github.com/deepinsight/insightface">InsightFace</a></b> (🥈26 ·  ⭐ 10K) - MXNet和PyTorch上的人脸分析项目。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepinsight/insightface) (👨‍💻 29 · 🔀 3.4K · 📦 100 · 📋 1.7K - 53% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/deepinsight/insightface
	```
- [PyPi](https://pypi.org/project/insightface) (📥 19K / month):
	```
	pip install insightface
	```
</details>
<details><summary><b><a href="https://github.com/glfw/glfw">glfw</a></b> (🥈26 ·  ⭐ 8.2K) - 一个用于OpenGL，Op​​enGL ES，Vulkan，窗口和输入的多平台库。<code><a href="https://tldrlegal.com/search?q=Zlib">❗️Zlib</a></code></summary>

- [GitHub](https://github.com/glfw/glfw) (👨‍💻 170 · 🔀 2.9K · 📥 2.5M · 📋 1.5K - 28% open · ⏱️ 12.09.2021):

	```
	git clone https://github.com/glfw/glfw
	```
- [PyPi](https://pypi.org/project/glfw) (📥 64K / month):
	```
	pip install glfw
	```
- [Conda](https://anaconda.org/conda-forge/glfw) (📥 39K · ⏱️ 08.04.2021):
	```
	conda install -c conda-forge glfw
	```
</details>
<details><summary><b><a href="https://github.com/OlafenwaMoses/ImageAI">imageai</a></b> (🥈26 ·  ⭐ 6.6K) - python库旨在使开发人员能够构建应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/OlafenwaMoses/ImageAI) (👨‍💻 15 · 🔀 1.8K · 📥 650K · 📦 960 · 📋 640 - 34% open · ⏱️ 08.05.2021):

	```
	git clone https://github.com/OlafenwaMoses/ImageAI
	```
- [PyPi](https://pypi.org/project/imageai):
	```
	pip install imageai
	```
</details>
<details><summary><b><a href="https://github.com/ageitgey/face_recognition">Face Recognition</a></b> (🥈25 ·  ⭐ 42K) - 简单的面部识别API。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ageitgey/face_recognition) (👨‍💻 47 · 🔀 11K · 📥 450 · 📋 1.2K - 53% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/ageitgey/face_recognition
	```
- [PyPi](https://pypi.org/project/face_recognition) (📥 45K / month):
	```
	pip install face_recognition
	```
</details>
<details><summary><b><a href="https://github.com/JohannesBuchner/imagehash">ImageHash</a></b> (🥈25 ·  ⭐ 2.1K) - Python感知图像哈希模块。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/JohannesBuchner/imagehash) (👨‍💻 20 · 🔀 280 · 📦 3.5K · 📋 100 - 8% open · ⏱️ 07.09.2021):

	```
	git clone https://github.com/JohannesBuchner/imagehash
	```
- [PyPi](https://pypi.org/project/ImageHash):
	```
	pip install ImageHash
	```
- [Conda](https://anaconda.org/conda-forge/imagehash) (📥 160K · ⏱️ 15.07.2021):
	```
	conda install -c conda-forge imagehash
	```
</details>
<details><summary><b><a href="https://github.com/chainer/chainercv">chainercv</a></b> (🥈25 ·  ⭐ 1.5K · 💀) - ChainerCV：一个用于计算机视觉深度学习的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chainer/chainercv) (👨‍💻 39 · 🔀 310 · 📦 260 · 📋 200 - 18% open · ⏱️ 07.01.2020):

	```
	git clone https://github.com/chainer/chainercv
	```
- [PyPi](https://pypi.org/project/chainercv) (📥 5.8K / month):
	```
	pip install chainercv
	```
</details>
<details><summary><b><a href="https://github.com/timesler/facenet-pytorch">facenet-pytorch</a></b> (🥉24 ·  ⭐ 2.4K) - 预训练的Pytorch人脸检测（MTCNN）和识别。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/timesler/facenet-pytorch) (👨‍💻 14 · 🔀 520 · 📥 150K · 📦 500 · 📋 140 - 35% open · ⏱️ 23.05.2021):

	```
	git clone https://github.com/timesler/facenet-pytorch
	```
- [PyPi](https://pypi.org/project/facenet-pytorch) (📥 12K / month):
	```
	pip install facenet-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/idealo/image-super-resolution">Image Super-Resolution</a></b> (🥉23 ·  ⭐ 3.1K) - 图像超精度变换。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/idealo/image-super-resolution) (👨‍💻 10 · 🔀 550 · 📦 60 · 📋 180 - 41% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/idealo/image-super-resolution
	```
- [PyPi](https://pypi.org/project/ISR) (📥 10K / month):
	```
	pip install ISR
	```
- [Docker Hub](https://hub.docker.com/r/idealo/image-super-resolution-gpu) (📥 170 · ⏱️ 01.04.2019):
	```
	docker pull idealo/image-super-resolution-gpu
	```
</details>
<details><summary><b><a href="https://github.com/opencv/opencv-python">opencv-python</a></b> (🥉23 ·  ⭐ 2.3K) - 自动化的CI工具链可生成预编译的opencv-python。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/opencv/opencv-python) (👨‍💻 33 · 🔀 440 · 📋 470 - 8% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/skvark/opencv-python
	```
- [PyPi](https://pypi.org/project/opencv-python) (📥 4.7M / month):
	```
	pip install opencv-python
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/vit-pytorch">vit-pytorch</a></b> (🥉22 ·  ⭐ 6K) - 实现视觉transformer，一种简单的方法。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/vit-pytorch) (👨‍💻 11 · 🔀 820 · 📦 44 · 📋 140 - 46% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/lucidrains/vit-pytorch
	```
- [PyPi](https://pypi.org/project/vit-pytorch) (📥 4.4K / month):
	```
	pip install vit-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/idealo/imagededup">Image Deduplicator</a></b> (🥉22 ·  ⭐ 3.8K · 💤) - 图像查重。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/idealo/imagededup) (👨‍💻 9 · 🔀 320 · 📦 18 · 📋 82 - 29% open · ⏱️ 23.11.2020):

	```
	git clone https://github.com/idealo/imagededup
	```
- [PyPi](https://pypi.org/project/imagededup) (📥 2.2K / month):
	```
	pip install imagededup
	```
</details>
<details><summary><b><a href="https://github.com/abhiTronix/vidgear">vidgear</a></b> (🥉22 ·  ⭐ 1.9K) - 高性能跨平台视频处理Python框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/abhiTronix/vidgear) (👨‍💻 6 · 🔀 140 · 📥 440 · 📦 140 · 📋 170 - 0% open · ⏱️ 02.09.2021):

	```
	git clone https://github.com/abhiTronix/vidgear
	```
- [PyPi](https://pypi.org/project/vidgear) (📥 2.4K / month):
	```
	pip install vidgear
	```
</details>
<details><summary><b><a href="https://github.com/ipazc/mtcnn">mtcnn</a></b> (🥉22 ·  ⭐ 1.6K) - TensorFlow的MTCNN人脸检测实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ipazc/mtcnn) (👨‍💻 15 · 🔀 420 · 📦 1.5K · 📋 96 - 61% open · ⏱️ 09.07.2021):

	```
	git clone https://github.com/ipazc/mtcnn
	```
- [PyPi](https://pypi.org/project/mtcnn) (📥 28K / month):
	```
	pip install mtcnn
	```
</details>
<details><summary><b><a href="https://github.com/lightly-ai/lightly">lightly</a></b> (🥉22 ·  ⭐ 1.2K) - 一个用于对图像进行自监督学习的python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lightly-ai/lightly) (👨‍💻 12 · 🔀 75 · 📦 22 · 📋 240 - 20% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/lightly-ai/lightly
	```
- [PyPi](https://pypi.org/project/lightly) (📥 1.4K / month):
	```
	pip install lightly
	```
</details>
<details><summary><b><a href="https://github.com/luispedro/mahotas">mahotas</a></b> (🥉22 ·  ⭐ 720) - Python中的计算机视觉。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/luispedro/mahotas) (👨‍💻 31 · 🔀 130 · 📦 690 · 📋 72 - 19% open · ⏱️ 31.05.2021):

	```
	git clone https://github.com/luispedro/mahotas
	```
- [PyPi](https://pypi.org/project/mahotas) (📥 12K / month):
	```
	pip install mahotas
	```
- [Conda](https://anaconda.org/conda-forge/mahotas) (📥 300K · ⏱️ 22.01.2021):
	```
	conda install -c conda-forge mahotas
	```
</details>
<details><summary><b><a href="https://github.com/libvips/pyvips">pyvips</a></b> (🥉22 ·  ⭐ 360) - 使用cffi的libvips的python接口。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/libvips/pyvips) (👨‍💻 11 · 🔀 30 · 📦 230 · 📋 240 - 35% open · ⏱️ 13.09.2021):

	```
	git clone https://github.com/libvips/pyvips
	```
- [PyPi](https://pypi.org/project/pyvips) (📥 13K / month):
	```
	pip install pyvips
	```
- [Conda](https://anaconda.org/conda-forge/pyvips) (📥 12K · ⏱️ 10.09.2021):
	```
	conda install -c conda-forge pyvips
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytorch3d">PyTorch3D</a></b> (🥉21 ·  ⭐ 5.3K) - PyTorch3D是FAIR的深度学习可重用组件库。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pytorch3d) (👨‍💻 71 · 🔀 690 · 📦 110 · 📋 740 - 7% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/facebookresearch/pytorch3d
	```
- [PyPi](https://pypi.org/project/pytorch3d) (📥 7K / month):
	```
	pip install pytorch3d
	```
- [Conda](https://anaconda.org/pytorch3d/pytorch3d) (📥 20K · ⏱️ 06.10.2021):
	```
	conda install -c pytorch3d pytorch3d
	```
</details>
<details><summary><b><a href="https://github.com/1adrianb/face-alignment">Face Alignment</a></b> (🥉21 ·  ⭐ 5.3K) - 使用pytorch构建2D和3D人脸对齐库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/1adrianb/face-alignment) (👨‍💻 23 · 🔀 1.1K · 📋 260 - 16% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/1adrianb/face-alignment
	```
- [PyPi](https://pypi.org/project/face-alignment) (📥 6.7K / month):
	```
	pip install face-alignment
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/mmf">MMF</a></b> (🥉21 ·  ⭐ 4.6K) - 来自视觉和语言多模态研究的模块化框架。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/mmf) (👨‍💻 79 · 🔀 760 · 📦 9 · 📋 550 - 25% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/facebookresearch/mmf
	```
- [PyPi](https://pypi.org/project/mmf) (📥 530 / month):
	```
	pip install mmf
	```
</details>
<details><summary><b><a href="https://github.com/tryolabs/luminoth">Luminoth</a></b> (🥉21 ·  ⭐ 2.4K · 💀) - 用于计算机视觉的深度学习工具包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tryolabs/luminoth) (👨‍💻 15 · 🔀 400 · 📥 12K · 📦 35 · 📋 180 - 28% open · ⏱️ 07.01.2020):

	```
	git clone https://github.com/tryolabs/luminoth
	```
- [PyPi](https://pypi.org/project/luminoth) (📥 990 / month):
	```
	pip install luminoth
	```
</details>
<details><summary><b><a href="https://github.com/uploadcare/pillow-simd">Pillow-SIMD</a></b> (🥉21 ·  ⭐ 1.7K · 💀) - 友好的PIL fork。<code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code></summary>

- [GitHub](https://github.com/uploadcare/pillow-simd) (👨‍💻 310 · 🔀 71 · 📦 460 · 📋 67 - 16% open · ⏱️ 02.06.2020):

	```
	git clone https://github.com/uploadcare/pillow-simd
	```
- [PyPi](https://pypi.org/project/pillow-simd) (📥 43K / month):
	```
	pip install pillow-simd
	```
</details>
<details><summary><b><a href="https://github.com/CellProfiler/CellProfiler">CellProfiler</a></b> (🥉21 ·  ⭐ 610) - 生物图像分析的开源应用程序。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/CellProfiler/CellProfiler) (👨‍💻 120 · 🔀 290 · 📥 1.6K · 📦 4 · 📋 3K - 6% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/CellProfiler/CellProfiler
	```
- [PyPi](https://pypi.org/project/cellprofiler) (📥 790 / month):
	```
	pip install cellprofiler
	```
</details>
<details><summary><b><a href="https://github.com/qubvel/segmentation_models">segmentation_models</a></b> (🥉20 ·  ⭐ 3.5K · 💀) - Segmentation models with pretrained backbones. Keras.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/qubvel/segmentation_models) (👨‍💻 14 · 🔀 810 · 📋 440 - 43% open · ⏱️ 17.04.2020):

	```
	git clone https://github.com/qubvel/segmentation_models
	```
- [PyPi](https://pypi.org/project/segmentation_models) (📥 38K / month):
	```
	pip install segmentation_models
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/graphics">tensorflow-graphics</a></b> (🥉20 ·  ⭐ 2.5K) - TensorFlow图神经网络：可微分的图layer<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/graphics) (👨‍💻 34 · 🔀 310 · 📋 150 - 44% open · ⏱️ 27.09.2021):

	```
	git clone https://github.com/tensorflow/graphics
	```
- [PyPi](https://pypi.org/project/tensorflow-graphics) (📥 2.3K / month):
	```
	pip install tensorflow-graphics
	```
</details>
<details><summary><b><a href="https://github.com/nicolas-chaulet/torch-points3d">Torch Points 3D</a></b> (🥉20 ·  ⭐ 1.5K) - 用于在点云上进行深度学习的Pytorch框架。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nicolas-chaulet/torch-points3d) (👨‍💻 29 · 🔀 240 · 📦 3 · 📋 280 - 28% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/nicolas-chaulet/torch-points3d
	```
- [PyPi](https://pypi.org/project/torch-points3d):
	```
	pip install torch-points3d
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ClassyVision">Classy Vision</a></b> (🥉20 ·  ⭐ 1.4K) - 用于图像和视频的端到端PyTorch框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ClassyVision) (👨‍💻 66 · 🔀 230 · 📋 73 - 16% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/facebookresearch/ClassyVision
	```
- [PyPi](https://pypi.org/project/classy_vision) (📥 2.6K / month):
	```
	pip install classy_vision
	```
- [Conda](https://anaconda.org/conda-forge/classy_vision) (📥 9.8K · ⏱️ 11.12.2020):
	```
	conda install -c conda-forge classy_vision
	```
</details>
<details><summary><b><a href="https://github.com/tryolabs/norfair">Norfair</a></b> (🥉20 ·  ⭐ 1.1K) - 轻量级Python库，用于向其中添加实时2D对象跟踪。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/tryolabs/norfair) (👨‍💻 9 · 🔀 80 · 📋 36 - 19% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/tryolabs/norfair
	```
- [PyPi](https://pypi.org/project/norfair) (📥 1.8K / month):
	```
	pip install norfair
	```
</details>
<details><summary><b><a href="https://github.com/jasmcaus/caer">Caer</a></b> (🥉20 ·  ⭐ 550) - 轻量级的计算机视觉库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jasmcaus/caer) (👨‍💻 7 · 🔀 60 · 📥 19 · 📋 15 - 20% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/jasmcaus/caer
	```
- [PyPi](https://pypi.org/project/caer) (📥 6.3K / month):
	```
	pip install caer
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleDetection">PaddleDetection</a></b> (🥉19 ·  ⭐ 4.7K) - 对象检测和实例分割工具箱。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleDetection) (👨‍💻 65 · 🔀 1.2K · 📦 6 · 📋 2.4K - 24% open · ⏱️ 23.09.2021):

	```
	git clone https://github.com/PaddlePaddle/PaddleDetection
	```
</details>
<details><summary><b><a href="https://github.com/mdbloice/Augmentor">Augmentor</a></b> (🥉19 ·  ⭐ 4.5K · 💀) - Python中的图像增强库，用于机器学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mdbloice/Augmentor) (👨‍💻 22 · 🔀 800 · 📦 370 · 📋 180 - 61% open · ⏱️ 09.03.2020):

	```
	git clone https://github.com/mdbloice/Augmentor
	```
- [PyPi](https://pypi.org/project/Augmentor):
	```
	pip install Augmentor
	```
</details>
<details><summary><b><a href="https://github.com/hhatto/nude.py">nude.py</a></b> (🥉19 ·  ⭐ 820 · 💤) - 使用Python进行裸露检测。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hhatto/nude.py) (👨‍💻 12 · 🔀 130 · 📦 920 · 📋 10 - 70% open · ⏱️ 23.11.2020):

	```
	git clone https://github.com/hhatto/nude.py
	```
- [PyPi](https://pypi.org/project/nudepy) (📥 6.2K / month):
	```
	pip install nudepy
	```
</details>
<details><summary><b><a href="https://github.com/ProvenanceLabs/image-match">image-match</a></b> (🥉18 ·  ⭐ 2.6K) - 快速搜索数十亿张图像。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ProvenanceLabs/image-match) (👨‍💻 19 · 🔀 370 · 📋 95 - 49% open · ⏱️ 21.09.2021):

	```
	git clone https://github.com/EdjoLabs/image-match
	```
- [PyPi](https://pypi.org/project/image_match) (📥 1.2K / month):
	```
	pip install image_match
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/SlowFast">PySlowFast</a></b> (🥉17 ·  ⭐ 4.2K) - PySlowFast：来自FAIR的视频理解代码库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/SlowFast) (👨‍💻 25 · 🔀 800 · 📦 5 · 📋 460 - 49% open · ⏱️ 21.09.2021):

	```
	git clone https://github.com/facebookresearch/SlowFast
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/detr">DE⫶TR</a></b> (🥉16 ·  ⭐ 7.7K) - End-to-End Object Detection with Transformers. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/detr) (👨‍💻 23 · 🔀 1.3K · 📋 380 - 29% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/facebookresearch/detr
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pycls">pycls</a></b> (🥉16 ·  ⭐ 1.7K) - 用PyTorch编写的图像分类研究代码库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pycls) (👨‍💻 13 · 🔀 190 · 📦 4 · 📋 72 - 26% open · ⏱️ 19.08.2021):

	```
	git clone https://github.com/facebookresearch/pycls
	```
</details>
<br>

## 图数据处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于图数据处理，聚类，图嵌入和机器学习任务的库。_

<details><summary><b><a href="https://github.com/networkx/networkx">networkx</a></b> (🥇33 ·  ⭐ 9.8K) - Python中的网络分析。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/networkx/networkx) (👨‍💻 550 · 🔀 2.3K · 📥 56 · 📦 87K · 📋 2.6K - 6% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/networkx/networkx
	```
- [PyPi](https://pypi.org/project/networkx) (📥 25M / month):
	```
	pip install networkx
	```
- [Conda](https://anaconda.org/conda-forge/networkx) (📥 4.7M · ⏱️ 10.09.2021):
	```
	conda install -c conda-forge networkx
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/dgl">dgl</a></b> (🥇28 ·  ⭐ 8.1K) - 在现有基础之上构建的Python软件包，用于简化图上的深度学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/dgl) (👨‍💻 160 · 🔀 1.7K · 📋 1.2K - 20% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/dmlc/dgl
	```
- [PyPi](https://pypi.org/project/dgl) (📥 80K / month):
	```
	pip install dgl
	```
</details>
<details><summary><b><a href="https://github.com/igraph/python-igraph">igraph</a></b> (🥇28 ·  ⭐ 880) - Igraph的Python接口。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/igraph/python-igraph) (👨‍💻 54 · 🔀 200 · 📥 250K · 📦 2K · 📋 330 - 7% open · ⏱️ 09.10.2021):

	```
	git clone https://github.com/igraph/python-igraph
	```
- [PyPi](https://pypi.org/project/python-igraph) (📥 130K / month):
	```
	pip install python-igraph
	```
- [Conda](https://anaconda.org/conda-forge/igraph) (📥 250K · ⏱️ 16.06.2021):
	```
	conda install -c conda-forge igraph
	```
</details>
<details><summary><b><a href="https://github.com/pyg-team/pytorch_geometric">PyTorch Geometric</a></b> (🥈27 ·  ⭐ 13K) - PyTorch的几何深度学习扩展库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyg-team/pytorch_geometric) (👨‍💻 210 · 🔀 2.1K · 📋 2.2K - 37% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/rusty1s/pytorch_geometric
	```
- [PyPi](https://pypi.org/project/torch-geometric) (📥 42K / month):
	```
	pip install torch-geometric
	```
</details>
<details><summary><b><a href="https://github.com/stellargraph/stellargraph">StellarGraph</a></b> (🥈26 ·  ⭐ 2.2K) - StellarGraph-图机器学习库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/stellargraph/stellargraph) (👨‍💻 36 · 🔀 320 · 📦 91 · 📋 960 - 24% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/stellargraph/stellargraph
	```
- [PyPi](https://pypi.org/project/stellargraph) (📥 13K / month):
	```
	pip install stellargraph
	```
</details>
<details><summary><b><a href="https://github.com/snap-stanford/ogb">ogb</a></b> (🥈24 ·  ⭐ 1.1K) - 用于图机器学习的基准数据集，数据加载器和评估器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snap-stanford/ogb) (👨‍💻 16 · 🔀 220 · 📦 160 · ⏱️ 07.10.2021):

	```
	git clone https://github.com/snap-stanford/ogb
	```
- [PyPi](https://pypi.org/project/ogb) (📥 6.8K / month):
	```
	pip install ogb
	```
</details>
<details><summary><b><a href="https://github.com/Accenture/AmpliGraph">AmpliGraph</a></b> (🥈23 ·  ⭐ 1.6K) - 用于知识表示学习的Python库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Accenture/AmpliGraph) (👨‍💻 19 · 🔀 180 · 📦 16 · 📋 200 - 8% open · ⏱️ 25.05.2021):

	```
	git clone https://github.com/Accenture/AmpliGraph
	```
- [PyPi](https://pypi.org/project/ampligraph) (📥 1.7K / month):
	```
	pip install ampligraph
	```
</details>
<details><summary><b><a href="https://github.com/Kozea/pygal">pygal</a></b> (🥈22 ·  ⭐ 2.4K) - PYthon svg GrAph绘图库。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/Kozea/pygal) (👨‍💻 71 · 🔀 380 · 📋 400 - 38% open · ⏱️ 18.08.2021):

	```
	git clone https://github.com/Kozea/pygal
	```
- [PyPi](https://pypi.org/project/pygal) (📥 120K / month):
	```
	pip install pygal
	```
- [Conda](https://anaconda.org/conda-forge/pygal) (📥 8.6K · ⏱️ 04.06.2019):
	```
	conda install -c conda-forge pygal
	```
</details>
<details><summary><b><a href="https://github.com/danielegrattarola/spektral">Spektral</a></b> (🥈21 ·  ⭐ 1.9K) - 使用Keras和Tensorflow 2的图神经网络。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/danielegrattarola/spektral) (👨‍💻 19 · 🔀 250 · 📦 75 · 📋 180 - 16% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/danielegrattarola/spektral
	```
- [PyPi](https://pypi.org/project/spektral) (📥 7.9K / month):
	```
	pip install spektral
	```
</details>
<details><summary><b><a href="https://github.com/phanein/deepwalk">DeepWalk</a></b> (🥈20 ·  ⭐ 2.3K · 💀) - DeepWalk-图的深度学习。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/phanein/deepwalk) (👨‍💻 10 · 🔀 770 · 📦 44 · 📋 100 - 22% open · ⏱️ 02.04.2020):

	```
	git clone https://github.com/phanein/deepwalk
	```
- [PyPi](https://pypi.org/project/deepwalk) (📥 3.3K / month):
	```
	pip install deepwalk
	```
</details>
<details><summary><b><a href="https://github.com/benedekrozemberczki/karateclub">Karate Club</a></b> (🥈20 ·  ⭐ 1.4K) - 面向API的开源Python框架。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/benedekrozemberczki/karateclub) (👨‍💻 13 · 🔀 160 · 📦 58 · ⏱️ 29.09.2021):

	```
	git clone https://github.com/benedekrozemberczki/karateclub
	```
- [PyPi](https://pypi.org/project/karateclub):
	```
	pip install karateclub
	```
</details>
<details><summary><b><a href="https://github.com/eliorc/node2vec">Node2Vec</a></b> (🥈20 ·  ⭐ 780) - node2vec算法的实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eliorc/node2vec) (👨‍💻 9 · 🔀 170 · ⏱️ 09.10.2021):

	```
	git clone https://github.com/eliorc/node2vec
	```
- [PyPi](https://pypi.org/project/node2vec) (📥 32K / month):
	```
	pip install node2vec
	```
- [Conda](https://anaconda.org/conda-forge/node2vec) (📥 19K · ⏱️ 25.04.2020):
	```
	conda install -c conda-forge node2vec
	```
</details>
<details><summary><b><a href="https://github.com/pykeen/pykeen">PyKEEN</a></b> (🥈20 ·  ⭐ 550) - 一个用于学习和评估知识图嵌入的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pykeen/pykeen) (👨‍💻 21 · 🔀 78 · 📥 92 · 📋 270 - 35% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/pykeen/pykeen
	```
- [PyPi](https://pypi.org/project/pykeen) (📥 680 / month):
	```
	pip install pykeen
	```
</details>
<details><summary><b><a href="https://github.com/benedekrozemberczki/pytorch_geometric_temporal">pytorch_geometric_temporal</a></b> (🥉19 ·  ⭐ 1.1K) - PyTorch Geometric Temporal: Spatiotemporal Signal.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) (👨‍💻 12 · 🔀 140 · 📋 59 - 3% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/benedekrozemberczki/pytorch_geometric_temporal
	```
- [PyPi](https://pypi.org/project/torch-geometric-temporal) (📥 1.3K / month):
	```
	pip install torch-geometric-temporal
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_cluster">torch-cluster</a></b> (🥉19 ·  ⭐ 420) - 优化图聚类的PyTorch扩展库<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_cluster) (👨‍💻 19 · 🔀 80 · 📋 88 - 11% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/rusty1s/pytorch_cluster
	```
- [PyPi](https://pypi.org/project/torch-cluster) (📥 8.5K / month):
	```
	pip install torch-cluster
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PGL">Paddle Graph Learning</a></b> (🥉17 ·  ⭐ 1.1K) - paddle图机器学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PGL) (👨‍💻 19 · 🔀 180 · 📦 20 · 📋 88 - 32% open · ⏱️ 23.08.2021):

	```
	git clone https://github.com/PaddlePaddle/PGL
	```
- [PyPi](https://pypi.org/project/pgl):
	```
	pip install pgl
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/PyTorch-BigGraph">PyTorch-BigGraph</a></b> (🥉16 ·  ⭐ 2.9K) - 从大型图网络结构生成embedding嵌入。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/PyTorch-BigGraph) (👨‍💻 24 · 🔀 390 · 📥 120 · 📋 170 - 29% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/facebookresearch/PyTorch-BigGraph
	```
- [PyPi](https://pypi.org/project/torchbiggraph) (📥 710 / month):
	```
	pip install torchbiggraph
	```
</details>
<details><summary><b><a href="https://github.com/shenweichen/GraphEmbedding">GraphEmbedding</a></b> (🥉16 ·  ⭐ 2.3K · 💤) - 图嵌入算法的实现和实验。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/shenweichen/GraphEmbedding) (👨‍💻 8 · 🔀 700 · 📦 12 · 📋 52 - 73% open · ⏱️ 18.10.2020):

	```
	git clone https://github.com/shenweichen/GraphEmbedding
	```
</details>
<details><summary><b><a href="https://github.com/vaticle/kglib">kglib</a></b> (🥉16 ·  ⭐ 460 · 💤) - Grakn知识图库（ML R＆D）。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/vaticle/kglib) (👨‍💻 7 · 🔀 85 · 📥 210 · 📋 58 - 15% open · ⏱️ 15.01.2021):

	```
	git clone https://github.com/graknlabs/kglib
	```
- [PyPi](https://pypi.org/project/grakn-kglib) (📥 90 / month):
	```
	pip install grakn-kglib
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/graph_nets">graph-nets</a></b> (🥉15 ·  ⭐ 5K · 💤) - 在Tensorflow中构建图神经网络。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/graph_nets) (👨‍💻 10 · 🔀 750 · 📋 120 - 2% open · ⏱️ 04.12.2020):

	```
	git clone https://github.com/deepmind/graph_nets
	```
- [PyPi](https://pypi.org/project/graph-nets) (📥 840 / month):
	```
	pip install graph-nets
	```
</details>
<details><summary><b><a href="https://github.com/IBCNServices/pyRDF2Vec">pyRDF2Vec</a></b> (🥉15 ·  ⭐ 130) - RDF2Vec的Python实现和扩展。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IBCNServices/pyRDF2Vec) (👨‍💻 5 · 🔀 21 · 📋 41 - 4% open · ⏱️ 05.07.2021):

	```
	git clone https://github.com/IBCNServices/pyRDF2Vec
	```
- [PyPi](https://pypi.org/project/pyrdf2vec):
	```
	pip install pyrdf2vec
	```
</details>
<details><summary><b><a href="https://github.com/alibaba/euler">Euler</a></b> (🥉14 ·  ⭐ 2.7K · 💀) - 分布式图深度学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/alibaba/euler) (👨‍💻 3 · 🔀 530 · 📋 320 - 67% open · ⏱️ 29.07.2020):

	```
	git clone https://github.com/alibaba/euler
	```
- [PyPi](https://pypi.org/project/euler-gl) (📥 9 / month):
	```
	pip install euler-gl
	```
</details>
<details><summary><b><a href="https://github.com/williamleif/GraphSAGE">GraphSAGE</a></b> (🥉14 ·  ⭐ 2.5K · 💀) - 大型图上的表示学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/williamleif/GraphSAGE) (👨‍💻 9 · 🔀 700 · 📋 150 - 59% open · ⏱️ 19.09.2018):

	```
	git clone https://github.com/williamleif/GraphSAGE
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenNE">OpenNE</a></b> (🥉14 ·  ⭐ 1.5K · 💀) - 神经关系提取（NRE）的开源软件包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/thunlp/OpenNE) (👨‍💻 10 · 🔀 460 · 📋 95 - 1% open · ⏱️ 12.08.2019):

	```
	git clone https://github.com/thunlp/OpenNE
	```
</details>
<details><summary><b><a href="https://github.com/THUMNLab/AutoGL">AutoGL</a></b> (🥉14 ·  ⭐ 690) - 用于图上机器学习的autoML框架和工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/THUMNLab/AutoGL) (👨‍💻 9 · 🔀 70 · 📋 9 - 11% open · ⏱️ 12.08.2021):

	```
	git clone https://github.com/THUMNLab/AutoGL
	```
- [PyPi](https://pypi.org/project/auto-graph-learning) (📥 27 / month):
	```
	pip install auto-graph-learning
	```
</details>
<details><summary><b><a href="https://github.com/deepgraph/deepgraph">DeepGraph</a></b> (🥉14 ·  ⭐ 240) - 使用基于pandas的网络分析数据。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepgraph/deepgraph) (👨‍💻 2 · 🔀 36 · 📦 1 · 📋 14 - 64% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/deepgraph/deepgraph
	```
- [PyPi](https://pypi.org/project/deepgraph) (📥 340 / month):
	```
	pip install deepgraph
	```
- [Conda](https://anaconda.org/conda-forge/deepgraph) (📥 110K · ⏱️ 26.07.2021):
	```
	conda install -c conda-forge deepgraph
	```
</details>
<details><summary><b><a href="https://github.com/DeepGraphLearning/graphvite">GraphVite</a></b> (🥉13 ·  ⭐ 960 · 💤) - GraphVite：通用的高性能图形嵌入系统。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/DeepGraphLearning/graphvite) (🔀 130 · 📋 88 - 36% open · ⏱️ 14.01.2021):

	```
	git clone https://github.com/DeepGraphLearning/graphvite
	```
- [Conda](https://anaconda.org/milagraph/graphvite) (📥 3.9K · ⏱️ 19.03.2020):
	```
	conda install -c milagraph graphvite
	```
</details>
<details><summary><b><a href="https://github.com/gsi-upm/sematch">Sematch</a></b> (🥉13 ·  ⭐ 360 · 💀) - 知识图的语义相似性框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gsi-upm/sematch) (👨‍💻 5 · 🔀 100 · 📦 29 · 📋 31 - 38% open · ⏱️ 27.03.2019):

	```
	git clone https://github.com/gsi-upm/sematch
	```
- [PyPi](https://pypi.org/project/sematch):
	```
	pip install sematch
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenKE">OpenKE</a></b> (🥉12 ·  ⭐ 2.7K) - 神经关系提取（NRE）的开源软件包。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/thunlp/OpenKE) (👨‍💻 10 · 🔀 820 · 📋 320 - 5% open · ⏱️ 06.04.2021):

	```
	git clone https://github.com/thunlp/OpenKE
	```
</details>
<br>

## 音频处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于音频分析，处理，转换和提取以及语音识别和音乐生成任务的库。_

<details><summary><b><a href="https://github.com/jiaaro/pydub">Pydub</a></b> (🥇30 ·  ⭐ 5.6K) - 使用简单易用的高级界面处理音频。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jiaaro/pydub) (👨‍💻 90 · 🔀 740 · 📦 9K · 📋 440 - 42% open · ⏱️ 08.06.2021):

	```
	git clone https://github.com/jiaaro/pydub
	```
- [PyPi](https://pypi.org/project/pydub) (📥 930K / month):
	```
	pip install pydub
	```
- [Conda](https://anaconda.org/conda-forge/pydub) (📥 18K · ⏱️ 13.03.2021):
	```
	conda install -c conda-forge pydub
	```
</details>
<details><summary><b><a href="https://github.com/Uberi/speech_recognition">SpeechRecognition</a></b> (🥇27 ·  ⭐ 5.9K · 💀) - 适用于Python的语音识别模块。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Uberi/speech_recognition) (👨‍💻 41 · 🔀 1.9K · 📦 11K · 📋 490 - 42% open · ⏱️ 02.07.2019):

	```
	git clone https://github.com/Uberi/speech_recognition
	```
- [PyPi](https://pypi.org/project/SpeechRecognition) (📥 270K / month):
	```
	pip install SpeechRecognition
	```
- [Conda](https://anaconda.org/conda-forge/speechrecognition) (📥 130K · ⏱️ 11.01.2021):
	```
	conda install -c conda-forge speechrecognition
	```
</details>
<details><summary><b><a href="https://github.com/espnet/espnet">espnet</a></b> (🥇27 ·  ⭐ 4.3K) - 端到端语音处理工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/espnet/espnet) (👨‍💻 190 · 🔀 1.3K · 📥 73 · 📦 24 · 📋 1.5K - 12% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/espnet/espnet
	```
- [PyPi](https://pypi.org/project/espnet) (📥 6.2K / month):
	```
	pip install espnet
	```
</details>
<details><summary><b><a href="https://github.com/magenta/magenta">Magenta</a></b> (🥈26 ·  ⭐ 17K) - 借助机器智能进行音乐和艺术创作。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/magenta/magenta) (👨‍💻 150 · 🔀 3.4K · 📦 310 · 📋 850 - 33% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/magenta/magenta
	```
- [PyPi](https://pypi.org/project/magenta) (📥 6.2K / month):
	```
	pip install magenta
	```
</details>
<details><summary><b><a href="https://github.com/deezer/spleeter">spleeter</a></b> (🥈25 ·  ⭐ 18K) - Deezer源分离库，包括预训练的模型。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deezer/spleeter) (👨‍💻 18 · 🔀 1.8K · 📥 1.2M · 📋 580 - 16% open · ⏱️ 03.09.2021):

	```
	git clone https://github.com/deezer/spleeter
	```
- [PyPi](https://pypi.org/project/spleeter) (📥 8.7K / month):
	```
	pip install spleeter
	```
- [Conda](https://anaconda.org/conda-forge/spleeter) (📥 59K · ⏱️ 30.06.2020):
	```
	conda install -c conda-forge spleeter
	```
</details>
<details><summary><b><a href="https://github.com/aubio/aubio">aubio</a></b> (🥈25 ·  ⭐ 2.6K · 💤) - 用于音频和音乐分析的库。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/aubio/aubio) (👨‍💻 24 · 🔀 320 · 📦 250 · 📋 290 - 40% open · ⏱️ 19.01.2021):

	```
	git clone https://github.com/aubio/aubio
	```
- [PyPi](https://pypi.org/project/aubio):
	```
	pip install aubio
	```
- [Conda](https://anaconda.org/conda-forge/aubio) (📥 460K · ⏱️ 19.01.2021):
	```
	conda install -c conda-forge aubio
	```
</details>
<details><summary><b><a href="https://github.com/beetbox/audioread">audioread</a></b> (🥈25 ·  ⭐ 370 · 💤) - 跨库（GStreamer + Core Audio + MAD + FFmpeg）音频编解码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beetbox/audioread) (👨‍💻 20 · 🔀 85 · 📦 6.3K · 📋 71 - 38% open · ⏱️ 20.10.2020):

	```
	git clone https://github.com/beetbox/audioread
	```
- [PyPi](https://pypi.org/project/audioread) (📥 460K / month):
	```
	pip install audioread
	```
- [Conda](https://anaconda.org/conda-forge/audioread) (📥 350K · ⏱️ 16.03.2021):
	```
	conda install -c conda-forge audioread
	```
</details>
<details><summary><b><a href="https://github.com/tyiannak/pyAudioAnalysis">pyAudioAnalysis</a></b> (🥈24 ·  ⭐ 4.2K) - Python音频分析库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tyiannak/pyAudioAnalysis) (👨‍💻 25 · 🔀 1K · 📦 230 · 📋 270 - 59% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/tyiannak/pyAudioAnalysis
	```
- [PyPi](https://pypi.org/project/pyAudioAnalysis) (📥 12K / month):
	```
	pip install pyAudioAnalysis
	```
</details>
<details><summary><b><a href="https://github.com/MTG/essentia">Essentia</a></b> (🥈24 ·  ⭐ 1.9K) - C++库，用于音频和音乐分析，描述等。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/MTG/essentia) (👨‍💻 71 · 🔀 420 · 📦 230 · 📋 900 - 34% open · ⏱️ 22.09.2021):

	```
	git clone https://github.com/MTG/essentia
	```
- [PyPi](https://pypi.org/project/essentia) (📥 2.1K / month):
	```
	pip install essentia
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/audio">torchaudio</a></b> (🥈24 ·  ⭐ 1.4K) - 音频信号的数据处理和转换。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/audio) (👨‍💻 140 · 🔀 340 · 📋 510 - 18% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/pytorch/audio
	```
- [PyPi](https://pypi.org/project/torchaudio) (📥 330K / month):
	```
	pip install torchaudio
	```
</details>
<details><summary><b><a href="https://github.com/librosa/librosa">librosa</a></b> (🥉23 ·  ⭐ 4.8K) - 用于音频和音乐分析的Python库。<code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/librosa/librosa) (👨‍💻 91 · 🔀 750 · 📋 900 - 5% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/librosa/librosa
	```
- [PyPi](https://pypi.org/project/librosa) (📥 460K / month):
	```
	pip install librosa
	```
- [Conda](https://anaconda.org/conda-forge/librosa) (📥 400K · ⏱️ 26.05.2021):
	```
	conda install -c conda-forge librosa
	```
</details>
<details><summary><b><a href="https://github.com/magenta/ddsp">DDSP</a></b> (🥉22 ·  ⭐ 2K) - DDSP：微分数字信号处理。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/magenta/ddsp) (👨‍💻 27 · 🔀 200 · 📦 15 · 📋 120 - 14% open · ⏱️ 28.08.2021):

	```
	git clone https://github.com/magenta/ddsp
	```
- [PyPi](https://pypi.org/project/ddsp) (📥 1.7K / month):
	```
	pip install ddsp
	```
</details>
<details><summary><b><a href="https://github.com/keunwoochoi/kapre">kapre</a></b> (🥉22 ·  ⭐ 770 · 💤) - kapre：Keras音频预处理器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keunwoochoi/kapre) (👨‍💻 13 · 🔀 130 · 📥 16 · 📦 1.1K · 📋 90 - 11% open · ⏱️ 25.03.2021):

	```
	git clone https://github.com/keunwoochoi/kapre
	```
- [PyPi](https://pypi.org/project/kapre) (📥 1.9K / month):
	```
	pip install kapre
	```
</details>
<details><summary><b><a href="https://github.com/bastibe/python-soundfile">python-soundfile</a></b> (🥉21 ·  ⭐ 410) - SoundFile是基于libsndfile，CFFI等的音频库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bastibe/python-soundfile) (👨‍💻 20 · 🔀 56 · 📥 2.6K · 📦 9K · 📋 160 - 37% open · ⏱️ 21.09.2021):

	```
	git clone https://github.com/bastibe/python-soundfile
	```
- [PyPi](https://pypi.org/project/soundfile):
	```
	pip install soundfile
	```
</details>
<details><summary><b><a href="https://github.com/Picovoice/porcupine">Porcupine</a></b> (🥉20 ·  ⭐ 2.6K) - 深度学习支持的设备上唤醒词识别。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Picovoice/porcupine) (👨‍💻 29 · 🔀 360 · 📦 6 · 📋 330 - 1% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/Picovoice/Porcupine
	```
- [PyPi](https://pypi.org/project/pvporcupine) (📥 900 / month):
	```
	pip install pvporcupine
	```
</details>
<details><summary><b><a href="https://github.com/jameslyons/python_speech_features">python_speech_features</a></b> (🥉20 ·  ⭐ 2K · 💤) - This library provides common speech features for ASR.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jameslyons/python_speech_features) (👨‍💻 19 · 🔀 560 · 📋 69 - 27% open · ⏱️ 31.12.2020):

	```
	git clone https://github.com/jameslyons/python_speech_features
	```
- [PyPi](https://pypi.org/project/python_speech_features) (📥 79K / month):
	```
	pip install python_speech_features
	```
</details>
<details><summary><b><a href="https://github.com/CPJKU/madmom">Madmom</a></b> (🥉20 ·  ⭐ 810) - Python音频和音乐信号处理库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/CPJKU/madmom) (👨‍💻 20 · 🔀 140 · 📦 150 · 📋 230 - 20% open · ⏱️ 23.08.2021):

	```
	git clone https://github.com/CPJKU/madmom
	```
- [PyPi](https://pypi.org/project/madmom) (📥 4.5K / month):
	```
	pip install madmom
	```
</details>
<details><summary><b><a href="https://github.com/devsnd/tinytag">tinytag</a></b> (🥉20 ·  ⭐ 490) - 读取音乐元数据和MP3，OGG，OPUS，MP4，M4A，FLAC，WMA等的长度。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/devsnd/tinytag) (👨‍💻 20 · 🔀 82 · 📦 410 · 📋 81 - 16% open · ⏱️ 28.08.2021):

	```
	git clone https://github.com/devsnd/tinytag
	```
- [PyPi](https://pypi.org/project/tinytag) (📥 7.5K / month):
	```
	pip install tinytag
	```
</details>
<details><summary><b><a href="https://github.com/mozilla/TTS">TTS</a></b> (🥉19 ·  ⭐ 5.2K · 💤) - 文本到语音的深度学习。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/mozilla/TTS) (👨‍💻 56 · 🔀 820 · 📥 1.3K · 📋 510 - 1% open · ⏱️ 12.02.2021):

	```
	git clone https://github.com/mozilla/TTS
	```
</details>
<details><summary><b><a href="https://github.com/worldveil/dejavu">Dejavu</a></b> (🥉18 ·  ⭐ 5.6K · 💀) - Python中的音频指纹识别。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/worldveil/dejavu) (👨‍💻 23 · 🔀 1.2K · 📦 18 · 📋 200 - 35% open · ⏱️ 03.06.2020):

	```
	git clone https://github.com/worldveil/dejavu
	```
- [PyPi](https://pypi.org/project/PyDejavu) (📥 70 / month):
	```
	pip install PyDejavu
	```
</details>
<details><summary><b><a href="https://github.com/bmcfee/muda">Muda</a></b> (🥉17 ·  ⭐ 200) - 用于扩充带注释的音频数据的库。<code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/bmcfee/muda) (👨‍💻 7 · 🔀 34 · 📦 12 · 📋 49 - 10% open · ⏱️ 03.05.2021):

	```
	git clone https://github.com/bmcfee/muda
	```
- [PyPi](https://pypi.org/project/muda) (📥 140 / month):
	```
	pip install muda
	```
</details>
<details><summary><b><a href="https://github.com/adefossez/julius">Julius</a></b> (🥉13 ·  ⭐ 230) - 基于PyTorch的快速DSP，用于音频和一维信号。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/adefossez/julius) (👨‍💻 2 · 🔀 10 · 📦 37 · 📋 8 - 25% open · ⏱️ 28.07.2021):

	```
	git clone https://github.com/adefossez/julius
	```
- [PyPi](https://pypi.org/project/julius) (📥 5.9K / month):
	```
	pip install julius
	```
</details>
<br>

## 地理Geo处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于加载，处理，分析和写入geo地理数据的库，以及用于空间分析，地图可视化和地理编码的库。_

<details><summary><b><a href="https://github.com/visgl/deck.gl">pydeck</a></b> (🥇33 ·  ⭐ 9K) - WebGL2支持的地理空间可视化图层。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/visgl/deck.gl) (👨‍💻 180 · 🔀 1.6K · 📦 1.8K · 📋 2.3K - 4% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/visgl/deck.gl
	```
- [PyPi](https://pypi.org/project/pydeck):
	```
	pip install pydeck
	```
- [Conda](https://anaconda.org/conda-forge/pydeck) (📥 55K · ⏱️ 27.08.2021):
	```
	conda install -c conda-forge pydeck
	```
- [NPM](https://www.npmjs.com/package/deck.gl) (📥 230K / month):
	```
	npm install deck.gl
	```
</details>
<details><summary><b><a href="https://github.com/geopy/geopy">geopy</a></b> (🥇33 ·  ⭐ 3.4K) - 适用于Python的地址解析库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/geopy/geopy) (👨‍💻 120 · 🔀 530 · 📦 28K · 📋 250 - 7% open · ⏱️ 26.09.2021):

	```
	git clone https://github.com/geopy/geopy
	```
- [PyPi](https://pypi.org/project/geopy) (📥 3.3M / month):
	```
	pip install geopy
	```
- [Conda](https://anaconda.org/conda-forge/geopy) (📥 610K · ⏱️ 12.07.2021):
	```
	conda install -c conda-forge geopy
	```
</details>
<details><summary><b><a href="https://github.com/geopandas/geopandas">GeoPandas</a></b> (🥇33 ·  ⭐ 2.8K) - 用于地理数据的Python工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geopandas/geopandas) (👨‍💻 150 · 🔀 600 · 📥 1.2K · 📦 10K · 📋 1.1K - 27% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/geopandas/geopandas
	```
- [PyPi](https://pypi.org/project/geopandas) (📥 1.4M / month):
	```
	pip install geopandas
	```
- [Conda](https://anaconda.org/conda-forge/geopandas) (📥 1.2M · ⏱️ 08.10.2021):
	```
	conda install -c conda-forge geopandas
	```
</details>
<details><summary><b><a href="https://github.com/python-visualization/folium">folium</a></b> (🥈32 ·  ⭐ 5.5K) - Leaflet.js地图的Python数据。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-visualization/folium) (👨‍💻 120 · 🔀 2K · 📦 12K · 📋 870 - 18% open · ⏱️ 19.06.2021):

	```
	git clone https://github.com/python-visualization/folium
	```
- [PyPi](https://pypi.org/project/folium) (📥 550K / month):
	```
	pip install folium
	```
- [Conda](https://anaconda.org/conda-forge/folium) (📥 410K · ⏱️ 12.03.2021):
	```
	conda install -c conda-forge folium
	```
</details>
<details><summary><b><a href="https://github.com/pyproj4/pyproj">pyproj</a></b> (🥈32 ·  ⭐ 660) - 与PROJ的Python界面（图形投影和坐标。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyproj4/pyproj) (👨‍💻 43 · 🔀 160 · 📦 11K · 📋 440 - 1% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/pyproj4/pyproj
	```
- [PyPi](https://pypi.org/project/pyproj) (📥 3.3M / month):
	```
	pip install pyproj
	```
- [Conda](https://anaconda.org/conda-forge/pyproj) (📥 2.6M · ⏱️ 01.10.2021):
	```
	conda install -c conda-forge pyproj
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥈29 ·  ⭐ 1.2K) - Jupyter-Leaflet.js桥。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipyleaflet) (👨‍💻 69 · 🔀 290 · 📦 1.2K · 📋 440 - 37% open · ⏱️ 13.09.2021):

	```
	git clone https://github.com/jupyter-widgets/ipyleaflet
	```
- [PyPi](https://pypi.org/project/ipyleaflet) (📥 53K / month):
	```
	pip install ipyleaflet
	```
- [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 760K · ⏱️ 17.06.2021):
	```
	conda install -c conda-forge ipyleaflet
	```
- [NPM](https://www.npmjs.com/package/jupyter-leaflet) (📥 31K / month):
	```
	npm install jupyter-leaflet
	```
</details>
<details><summary><b><a href="https://github.com/DenisCarriere/geocoder">Geocoder</a></b> (🥈28 ·  ⭐ 1.4K · 💀) - Python Geocoder。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/DenisCarriere/geocoder) (👨‍💻 74 · 🔀 260 · 📦 3.9K · 📋 290 - 24% open · ⏱️ 12.10.2018):

	```
	git clone https://github.com/DenisCarriere/geocoder
	```
- [PyPi](https://pypi.org/project/geocoder):
	```
	pip install geocoder
	```
- [Conda](https://anaconda.org/conda-forge/geocoder) (📥 93K · ⏱️ 27.06.2019):
	```
	conda install -c conda-forge geocoder
	```
</details>
<details><summary><b><a href="https://github.com/Toblerity/Shapely">Shapely</a></b> (🥈27 ·  ⭐ 2.4K) - 操作和分析几何对象。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Toblerity/Shapely) (👨‍💻 120 · 🔀 420 · 📦 23K · 📋 780 - 17% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/Toblerity/Shapely
	```
- [PyPi](https://pypi.org/project/shapely):
	```
	pip install shapely
	```
- [Conda](https://anaconda.org/conda-forge/shapely) (📥 2.8M · ⏱️ 05.10.2021):
	```
	conda install -c conda-forge shapely
	```
</details>
<details><summary><b><a href="https://github.com/mapbox/rasterio">Rasterio</a></b> (🥈27 ·  ⭐ 1.6K) - Rasterio读写地理空间栅格数据集。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mapbox/rasterio) (👨‍💻 110 · 🔀 430 · 📥 740 · 📦 3.8K · 📋 1.5K - 9% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/mapbox/rasterio
	```
- [PyPi](https://pypi.org/project/rasterio) (📥 700K / month):
	```
	pip install rasterio
	```
- [Conda](https://anaconda.org/conda-forge/rasterio) (📥 1.3M · ⏱️ 12.10.2021):
	```
	conda install -c conda-forge rasterio
	```
</details>
<details><summary><b><a href="https://github.com/Toblerity/Fiona">Fiona</a></b> (🥈27 ·  ⭐ 850) - Fiona读写地理数据文件。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Toblerity/Fiona) (👨‍💻 65 · 🔀 160 · 📦 6.8K · 📋 640 - 11% open · ⏱️ 23.09.2021):

	```
	git clone https://github.com/Toblerity/Fiona
	```
- [PyPi](https://pypi.org/project/fiona) (📥 1.8M / month):
	```
	pip install fiona
	```
- [Conda](https://anaconda.org/conda-forge/fiona) (📥 2.3M · ⏱️ 12.08.2021):
	```
	conda install -c conda-forge fiona
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/geojson">geojson</a></b> (🥈27 ·  ⭐ 650) - GeoJSON的Python接口。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/geojson) (👨‍💻 44 · 🔀 83 · 📦 7.7K · 📋 77 - 24% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/jazzband/geojson
	```
- [PyPi](https://pypi.org/project/geojson) (📥 670K / month):
	```
	pip install geojson
	```
- [Conda](https://anaconda.org/conda-forge/geojson) (📥 450K · ⏱️ 11.08.2019):
	```
	conda install -c conda-forge geojson
	```
</details>
<details><summary><b><a href="https://github.com/mapbox/rasterio">Cartopy</a></b> (🥉26 ·  ⭐ 1.6K) - Rasterio读写地理空间栅格数据集。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mapbox/rasterio) (👨‍💻 110 · 🔀 430 · 📥 740 · 📦 3.8K · 📋 1.5K - 9% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/mapbox/rasterio
	```
- [PyPi](https://pypi.org/project/Cartopy) (📥 86K / month):
	```
	pip install Cartopy
	```
- [Conda](https://anaconda.org/conda-forge/cartopy) (📥 1.8M · ⏱️ 12.10.2021):
	```
	conda install -c conda-forge cartopy
	```
</details>
<details><summary><b><a href="https://github.com/Esri/arcgis-python-api">ArcGIS API</a></b> (🥉24 ·  ⭐ 1.1K) - ArcGIS API for Python的文档和示例。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Esri/arcgis-python-api) (👨‍💻 71 · 🔀 800 · 📥 100 · 📋 370 - 26% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/Esri/arcgis-python-api
	```
- [PyPi](https://pypi.org/project/arcgis) (📥 48K / month):
	```
	pip install arcgis
	```
- [Docker Hub](https://hub.docker.com/r/esridocker/arcgis-api-python-notebook) (📥 5K · ⭐ 33 · ⏱️ 05.10.2021):
	```
	docker pull esridocker/arcgis-api-python-notebook
	```
</details>
<details><summary><b><a href="https://github.com/pysal/pysal">PySAL</a></b> (🥉23 ·  ⭐ 910) - PySAL：Python空间分析库元包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pysal/pysal) (👨‍💻 72 · 🔀 250 · 📋 600 - 1% open · ⏱️ 03.10.2021):

	```
	git clone https://github.com/pysal/pysal
	```
- [PyPi](https://pypi.org/project/pysal) (📥 15K / month):
	```
	pip install pysal
	```
- [Conda](https://anaconda.org/conda-forge/pysal) (📥 430K · ⏱️ 02.08.2021):
	```
	conda install -c conda-forge pysal
	```
</details>
<details><summary><b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥉23 ·  ⭐ 580) - 使用Mapbox GL JS可视化Python Jupyter笔记本中的数据。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mapbox/mapboxgl-jupyter) (👨‍💻 21 · 🔀 120 · 📦 120 · 📋 97 - 30% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/mapbox/mapboxgl-jupyter
	```
- [PyPi](https://pypi.org/project/mapboxgl) (📥 10K / month):
	```
	pip install mapboxgl
	```
</details>
<details><summary><b><a href="https://github.com/pytroll/satpy">Satpy</a></b> (🥉21 ·  ⭐ 760) - 用于地球观测卫星数据处理的Python软件包。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/pytroll/satpy) (👨‍💻 120 · 🔀 210 · 📦 49 · 📋 670 - 41% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/pytroll/satpy
	```
- [PyPi](https://pypi.org/project/satpy):
	```
	pip install satpy
	```
- [Conda](https://anaconda.org/conda-forge/satpy) (📥 75K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge satpy
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/geoviews">GeoViews</a></b> (🥉21 ·  ⭐ 370) - 使用Python进行简单，简洁的地理可视化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/geoviews) (👨‍💻 23 · 🔀 64 · 📋 280 - 34% open · ⏱️ 29.09.2021):

	```
	git clone https://github.com/holoviz/geoviews
	```
- [PyPi](https://pypi.org/project/geoviews) (📥 6.9K / month):
	```
	pip install geoviews
	```
- [Conda](https://anaconda.org/conda-forge/geoviews) (📥 81K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge geoviews
	```
</details>
<details><summary><b><a href="https://github.com/earthlab/earthpy">EarthPy</a></b> (🥉21 ·  ⭐ 290) - 使用开放源代码处理空间数据。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/earthlab/earthpy) (👨‍💻 40 · 🔀 120 · 📦 110 · 📋 220 - 6% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/earthlab/earthpy
	```
- [PyPi](https://pypi.org/project/earthpy) (📥 3.9K / month):
	```
	pip install earthpy
	```
- [Conda](https://anaconda.org/conda-forge/earthpy) (📥 38K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge earthpy
	```
</details>
<details><summary><b><a href="https://github.com/andrea-cuttone/geoplotlib">geoplotlib</a></b> (🥉19 ·  ⭐ 930 · 💀) - python工具箱，用于可视化地理数据和制作地图。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/andrea-cuttone/geoplotlib) (👨‍💻 8 · 🔀 150 · 📦 110 · 📋 43 - 58% open · ⏱️ 06.05.2019):

	```
	git clone https://github.com/andrea-cuttone/geoplotlib
	```
- [PyPi](https://pypi.org/project/geoplotlib) (📥 1.2K / month):
	```
	pip install geoplotlib
	```
</details>
<details><summary><b><a href="https://github.com/sentinelsat/sentinelsat">Sentinelsat</a></b> (🥉19 ·  ⭐ 670) - 搜索和下载哥白尼前哨卫星图像。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/sentinelsat/sentinelsat) (👨‍💻 41 · 🔀 180 · 📥 220 · 📦 230 · 📋 310 - 1% open · ⏱️ 17.09.2021):

	```
	git clone https://github.com/sentinelsat/sentinelsat
	```
- [PyPi](https://pypi.org/project/sentinelsat):
	```
	pip install sentinelsat
	```
</details>
<details><summary><b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉18 ·  ⭐ 720 · 💀) - Google为Jupyter笔记本电脑映射。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pbugnion/gmaps) (👨‍💻 16 · 🔀 140 · 📦 1 · 📋 200 - 31% open · ⏱️ 22.07.2019):

	```
	git clone https://github.com/pbugnion/gmaps
	```
- [PyPi](https://pypi.org/project/gmaps) (📥 15K / month):
	```
	pip install gmaps
	```
- [Conda](https://anaconda.org/conda-forge/gmaps) (📥 240K · ⏱️ 02.08.2019):
	```
	conda install -c conda-forge gmaps
	```
- [NPM](https://www.npmjs.com/package/jupyter-gmaps) (📥 1.8K / month):
	```
	npm install jupyter-gmaps
	```
</details>
<details><summary><b><a href="https://github.com/geospace-code/pymap3d">pymap3d</a></b> (🥉17 ·  ⭐ 210) - 纯Python实现（Numpy可选）的3D坐标转换。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/geospace-code/pymap3d) (👨‍💻 9 · 🔀 57 · 📋 27 - 11% open · ⏱️ 09.06.2021):

	```
	git clone https://github.com/geospace-code/pymap3d
	```
- [PyPi](https://pypi.org/project/pymap3d) (📥 44K / month):
	```
	pip install pymap3d
	```
- [Conda](https://anaconda.org/conda-forge/pymap3d) (📥 14K · ⏱️ 26.05.2021):
	```
	conda install -c conda-forge pymap3d
	```
</details>
<br>

## 金融数据处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于算法股票/加密交易，风险分析，回测，技术分析以及其他金融数据任务的库。_

<details><summary><b><a href="https://github.com/quantopian/zipline">zipline</a></b> (🥇28 ·  ⭐ 15K · 💤) - Zipline，一个Pythonic算法交易库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/quantopian/zipline) (👨‍💻 150 · 🔀 3.8K · 📦 780 · 📋 960 - 32% open · ⏱️ 14.10.2020):

	```
	git clone https://github.com/quantopian/zipline
	```
- [PyPi](https://pypi.org/project/zipline) (📥 4.6K / month):
	```
	pip install zipline
	```
</details>
<details><summary><b><a href="https://github.com/ranaroussi/yfinance">yfinance</a></b> (🥇28 ·  ⭐ 5.8K) - Yahoo! 金融市场数据下载器（+更快的Pandas数据加载读取器）。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ranaroussi/yfinance) (👨‍💻 41 · 🔀 1.3K · 📦 7.2K · 📋 650 - 57% open · ⏱️ 10.07.2021):

	```
	git clone https://github.com/ranaroussi/yfinance
	```
- [PyPi](https://pypi.org/project/yfinance) (📥 310K / month):
	```
	pip install yfinance
	```
- [Conda](https://anaconda.org/ranaroussi/yfinance) (📥 12K · ⏱️ 10.07.2021):
	```
	conda install -c ranaroussi yfinance
	```
</details>
<details><summary><b><a href="https://github.com/quantopian/pyfolio">pyfolio</a></b> (🥇27 ·  ⭐ 4.1K · 💀) - Python中的投资组合和风险分析。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/quantopian/pyfolio) (👨‍💻 55 · 🔀 1.2K · 📦 310 · 📋 400 - 33% open · ⏱️ 15.07.2020):

	```
	git clone https://github.com/quantopian/pyfolio
	```
- [PyPi](https://pypi.org/project/pyfolio) (📥 6.3K / month):
	```
	pip install pyfolio
	```
- [Conda](https://anaconda.org/conda-forge/pyfolio) (📥 7.4K · ⏱️ 16.05.2020):
	```
	conda install -c conda-forge pyfolio
	```
</details>
<details><summary><b><a href="https://github.com/bukosabino/ta">ta</a></b> (🥈25 ·  ⭐ 2.5K · 💤) - 使用Pandas和Numpy的技术分析库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bukosabino/ta) (👨‍💻 23 · 🔀 600 · 📦 780 · 📋 180 - 51% open · ⏱️ 29.11.2020):

	```
	git clone https://github.com/bukosabino/ta
	```
- [PyPi](https://pypi.org/project/ta) (📥 100K / month):
	```
	pip install ta
	```
</details>
<details><summary><b><a href="https://github.com/quantopian/empyrical">empyrical</a></b> (🥈25 ·  ⭐ 840 · 💤) - 常见的金融风险和绩效指标。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/quantopian/empyrical) (👨‍💻 22 · 🔀 260 · 📦 710 · 📋 49 - 46% open · ⏱️ 14.10.2020):

	```
	git clone https://github.com/quantopian/empyrical
	```
- [PyPi](https://pypi.org/project/empyrical) (📥 64K / month):
	```
	pip install empyrical
	```
- [Conda](https://anaconda.org/conda-forge/empyrical) (📥 14K · ⏱️ 14.10.2020):
	```
	conda install -c conda-forge empyrical
	```
</details>
<details><summary><b><a href="https://github.com/quantopian/alphalens">Alphalens</a></b> (🥈24 ·  ⭐ 2.1K · 💀) - 股票因子预测分析。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/quantopian/alphalens) (👨‍💻 25 · 🔀 770 · 📦 450 · 📋 180 - 20% open · ⏱️ 27.04.2020):

	```
	git clone https://github.com/quantopian/alphalens
	```
- [PyPi](https://pypi.org/project/alphalens) (📥 2.3K / month):
	```
	pip install alphalens
	```
- [Conda](https://anaconda.org/conda-forge/alphalens) (📥 13K · ⏱️ 16.05.2020):
	```
	conda install -c conda-forge alphalens
	```
</details>
<details><summary><b><a href="https://github.com/pmorissette/bt">bt</a></b> (🥈24 ·  ⭐ 1.2K) - bt-Python的灵活回测。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pmorissette/bt) (👨‍💻 24 · 🔀 290 · 📦 76 · 📋 260 - 15% open · ⏱️ 15.05.2021):

	```
	git clone https://github.com/pmorissette/bt
	```
- [PyPi](https://pypi.org/project/bt) (📥 9.8K / month):
	```
	pip install bt
	```
</details>
<details><summary><b><a href="https://github.com/bashtage/arch">arch</a></b> (🥈24 ·  ⭐ 800) - Python中的ARCH模型。<code><a href="https://tldrlegal.com/search?q=NCSA">❗️NCSA</a></code></summary>

- [GitHub](https://github.com/bashtage/arch) (👨‍💻 29 · 🔀 180 · 📦 380 · 📋 160 - 7% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/bashtage/arch
	```
- [PyPi](https://pypi.org/project/arch) (📥 210K / month):
	```
	pip install arch
	```
</details>
<details><summary><b><a href="https://github.com/tensortrade-org/tensortrade">TensorTrade</a></b> (🥈23 ·  ⭐ 3.5K) - 一个开放源代码的强化学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tensortrade-org/tensortrade) (👨‍💻 55 · 🔀 790 · 📦 23 · 📋 180 - 12% open · ⏱️ 18.09.2021):

	```
	git clone https://github.com/tensortrade-org/tensortrade
	```
- [PyPi](https://pypi.org/project/tensortrade) (📥 980 / month):
	```
	pip install tensortrade
	```
</details>
<details><summary><b><a href="https://github.com/RomelTorres/alpha_vantage">Alpha Vantage</a></b> (🥉22 ·  ⭐ 3.5K) - 用于金融数据的Alpha Vantage API的python包装器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RomelTorres/alpha_vantage) (👨‍💻 39 · 🔀 620 · 📋 250 - 7% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/RomelTorres/alpha_vantage
	```
- [PyPi](https://pypi.org/project/alpha_vantage) (📥 22K / month):
	```
	pip install alpha_vantage
	```
</details>
<details><summary><b><a href="https://github.com/enigmampc/catalyst">Enigma Catalyst</a></b> (🥉22 ·  ⭐ 2.3K) - Python中加密资产的算法交易库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/enigmampc/catalyst) (👨‍💻 150 · 🔀 660 · 📦 23 · 📋 480 - 25% open · ⏱️ 22.09.2021):

	```
	git clone https://github.com/enigmampc/catalyst
	```
- [PyPi](https://pypi.org/project/enigma-catalyst) (📥 2.4K / month):
	```
	pip install enigma-catalyst
	```
</details>
<details><summary><b><a href="https://github.com/mementum/backtrader">backtrader</a></b> (🥉21 ·  ⭐ 7.4K) - 用于交易策略的Python Backtesting库。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/mementum/backtrader) (👨‍💻 52 · 🔀 2.2K · 📦 780 · ⏱️ 17.07.2021):

	```
	git clone https://github.com/mementum/backtrader
	```
- [PyPi](https://pypi.org/project/backtrader):
	```
	pip install backtrader
	```
</details>
<details><summary><b><a href="https://github.com/cuemacro/finmarketpy">finmarketpy</a></b> (🥉21 ·  ⭐ 2.7K) - Python库，用于回测交易策略和分析。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cuemacro/finmarketpy) (👨‍💻 14 · 🔀 420 · 📥 40 · 📦 4 · 📋 26 - 88% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/cuemacro/finmarketpy
	```
- [PyPi](https://pypi.org/project/finmarketpy) (📥 220 / month):
	```
	pip install finmarketpy
	```
</details>
<details><summary><b><a href="https://github.com/peerchemist/finta">FinTA</a></b> (🥉21 ·  ⭐ 1.3K) - 基于pandas实现的通用金融技术指标。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/peerchemist/finta) (👨‍💻 25 · 🔀 410 · 📦 110 · 📋 77 - 18% open · ⏱️ 23.07.2021):

	```
	git clone https://github.com/peerchemist/finta
	```
- [PyPi](https://pypi.org/project/finta) (📥 7.3K / month):
	```
	pip install finta
	```
</details>
<details><summary><b><a href="https://github.com/jealous/stockstats">stockstats</a></b> (🥉21 ·  ⭐ 860) - 提供StockDataFrame包装器<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jealous/stockstats) (👨‍💻 8 · 🔀 230 · 📦 330 · 📋 63 - 47% open · ⏱️ 03.08.2021):

	```
	git clone https://github.com/jealous/stockstats
	```
- [PyPi](https://pypi.org/project/stockstats) (📥 18K / month):
	```
	pip install stockstats
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/qlib">Qlib</a></b> (🥉20 ·  ⭐ 6.7K) - Qlib是一个面向AI的量化投资平台。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/qlib) (👨‍💻 67 · 🔀 1.1K · 📥 270 · 📦 5 · 📋 310 - 28% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/microsoft/qlib
	```
- [PyPi](https://pypi.org/project/pyqlib) (📥 4.1K / month):
	```
	pip install pyqlib
	```
</details>
<details><summary><b><a href="https://github.com/gbeced/pyalgotrade">PyAlgoTrade</a></b> (🥉20 ·  ⭐ 3.5K · 💀) - Python算法交易库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gbeced/pyalgotrade) (👨‍💻 11 · 🔀 1.2K · 📦 93 · 📋 120 - 30% open · ⏱️ 21.08.2018):

	```
	git clone https://github.com/gbeced/pyalgotrade
	```
- [PyPi](https://pypi.org/project/pyalgotrade):
	```
	pip install pyalgotrade
	```
</details>
<details><summary><b><a href="https://github.com/CryptoSignal/Crypto-Signal">Crypto Signals</a></b> (🥉19 ·  ⭐ 3.5K) - CryptoSignal量化交易技术。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CryptoSignal/Crypto-Signal) (👨‍💻 28 · 🔀 910 · 📋 240 - 18% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/CryptoSignal/crypto-signal
	```
- [Docker Hub](https://hub.docker.com/r/shadowreaver/crypto-signal) (📥 140K · ⭐ 7 · ⏱️ 03.09.2020):
	```
	docker pull shadowreaver/crypto-signal
	```
</details>
<details><summary><b><a href="https://github.com/google/tf-quant-finance">tf-quant-finance</a></b> (🥉19 ·  ⭐ 2.8K) - 用于量化投资的高性能TensorFlow库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/tf-quant-finance) (👨‍💻 36 · 🔀 370 · 📋 30 - 40% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/google/tf-quant-finance
	```
- [PyPi](https://pypi.org/project/tf-quant-finance) (📥 660 / month):
	```
	pip install tf-quant-finance
	```
</details>
<details><summary><b><a href="https://github.com/erdewit/ib_insync">IB-insync</a></b> (🥉19 ·  ⭐ 1.6K) - 用于Interactive Brokers API的Python同步/异步框架。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/erdewit/ib_insync) (👨‍💻 29 · 🔀 440 · 📋 340 - 1% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/erdewit/ib_insync
	```
- [PyPi](https://pypi.org/project/ib_insync):
	```
	pip install ib_insync
	```
- [Conda](https://anaconda.org/conda-forge/ib-insync) (📥 13K · ⏱️ 12.10.2021):
	```
	conda install -c conda-forge ib-insync
	```
</details>
<details><summary><b><a href="https://github.com/pmorissette/ffn">ffn</a></b> (🥉19 ·  ⭐ 970) - ffn-Python的金融函数库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pmorissette/ffn) (👨‍💻 26 · 🔀 190 · 📦 140 · 📋 95 - 15% open · ⏱️ 24.04.2021):

	```
	git clone https://github.com/pmorissette/ffn
	```
- [PyPi](https://pypi.org/project/ffn):
	```
	pip install ffn
	```
</details>
<details><summary><b><a href="https://github.com/kernc/backtesting.py">Backtesting.py</a></b> (🥉18 ·  ⭐ 1.8K) - 回溯Python中的交易策略。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/kernc/backtesting.py) (👨‍💻 15 · 🔀 380 · 📋 250 - 13% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/kernc/backtesting.py
	```
- [PyPi](https://pypi.org/project/backtesting) (📥 15K / month):
	```
	pip install backtesting
	```
</details>
<details><summary><b><a href="https://github.com/tradytics/surpriver">surpriver</a></b> (🥉13 ·  ⭐ 1.3K · 💀) - 使用机器学习在股票大波动之前找到它。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/tradytics/surpriver) (👨‍💻 6 · 🔀 240 · 📋 14 - 57% open · ⏱️ 21.09.2020):

	```
	git clone https://github.com/tradytics/surpriver
	```
</details>
<br>

## 时间序列

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于按时间序列和顺序数据进行预测，异常检测，特征提取和机器学习的库。_

<details><summary><b><a href="https://github.com/alkaline-ml/pmdarima">pmdarima</a></b> (🥇28 ·  ⭐ 1K) - 一个统计数据库，旨在填补Python时间序列中的空白。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alkaline-ml/pmdarima) (👨‍💻 19 · 🔀 180 · 📦 1.4K · 📋 250 - 6% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/alkaline-ml/pmdarima
	```
- [PyPi](https://pypi.org/project/pmdarima) (📥 1M / month):
	```
	pip install pmdarima
	```
</details>
<details><summary><b><a href="https://github.com/alan-turing-institute/sktime">sktime</a></b> (🥇26 ·  ⭐ 4.5K) - 具有时间序列的机器学习的统一框架。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/alan-turing-institute/sktime) (👨‍💻 120 · 🔀 640 · 📥 64 · 📦 260 · 📋 660 - 34% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/alan-turing-institute/sktime
	```
- [PyPi](https://pypi.org/project/sktime) (📥 110K / month):
	```
	pip install sktime
	```
</details>
<details><summary><b><a href="https://github.com/tslearn-team/tslearn">tslearn</a></b> (🥇26 ·  ⭐ 1.8K) - 专门用于时间序列数据的机器学习工具包。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tslearn-team/tslearn) (👨‍💻 33 · 🔀 240 · 📦 310 · 📋 240 - 27% open · ⏱️ 06.09.2021):

	```
	git clone https://github.com/tslearn-team/tslearn
	```
- [PyPi](https://pypi.org/project/tslearn) (📥 99K / month):
	```
	pip install tslearn
	```
- [Conda](https://anaconda.org/conda-forge/tslearn) (📥 240K · ⏱️ 16.08.2021):
	```
	conda install -c conda-forge tslearn
	```
</details>
<details><summary><b><a href="https://github.com/unit8co/darts">Darts</a></b> (🥈25 ·  ⭐ 2.9K) - 一个易于操作和预测时间序列的python库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/unit8co/darts) (👨‍💻 37 · 🔀 240 · 📦 13 · 📋 160 - 16% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/unit8co/darts
	```
- [PyPi](https://pypi.org/project/u8darts) (📥 13K / month):
	```
	pip install u8darts
	```
- [Docker Hub](https://hub.docker.com/r/unit8/darts) (📥 170 · ⏱️ 25.09.2021):
	```
	docker pull unit8/darts
	```
</details>
<details><summary><b><a href="https://github.com/facebook/prophet">Prophet</a></b> (🥈23 ·  ⭐ 13K) - 产生具有时间序列数据的高质量预测的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/prophet) (👨‍💻 140 · 🔀 3.8K · 📥 630 · 📋 1.7K - 8% open · ⏱️ 03.10.2021):

	```
	git clone https://github.com/facebook/prophet
	```
- [PyPi](https://pypi.org/project/fbprophet) (📥 1.1M / month):
	```
	pip install fbprophet
	```
</details>
<details><summary><b><a href="https://github.com/blue-yonder/tsfresh">tsfresh</a></b> (🥈23 ·  ⭐ 6K) - 从时间序列中自动提取相关特征。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/blue-yonder/tsfresh) (👨‍💻 79 · 🔀 910 · 📋 460 - 7% open · ⏱️ 09.07.2021):

	```
	git clone https://github.com/blue-yonder/tsfresh
	```
- [PyPi](https://pypi.org/project/tsfresh) (📥 310K / month):
	```
	pip install tsfresh
	```
- [Conda](https://anaconda.org/conda-forge/tsfresh) (📥 50K · ⏱️ 07.03.2021):
	```
	conda install -c conda-forge tsfresh
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/gluon-ts">GluonTS</a></b> (🥈23 ·  ⭐ 2.2K) - Python中的概率时间序列建模。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/gluon-ts) (👨‍💻 79 · 🔀 450 · 📋 620 - 32% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/awslabs/gluon-ts
	```
- [PyPi](https://pypi.org/project/gluonts) (📥 55K / month):
	```
	pip install gluonts
	```
</details>
<details><summary><b><a href="https://github.com/jdb78/pytorch-forecasting">pytorch-forecasting</a></b> (🥈23 ·  ⭐ 1.4K) - 使用PyTorch进行时间序列预测。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jdb78/pytorch-forecasting) (👨‍💻 22 · 🔀 190 · 📋 320 - 32% open · ⏱️ 26.09.2021):

	```
	git clone https://github.com/jdb78/pytorch-forecasting
	```
- [PyPi](https://pypi.org/project/pytorch-forecasting) (📥 23K / month):
	```
	pip install pytorch-forecasting
	```
</details>
<details><summary><b><a href="https://github.com/RJT1990/pyflux">PyFlux</a></b> (🥉21 ·  ⭐ 1.9K · 💀) - 适用于Python的开源时间序列库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/RJT1990/pyflux) (👨‍💻 6 · 🔀 220 · 📦 200 · 📋 140 - 55% open · ⏱️ 16.12.2018):

	```
	git clone https://github.com/RJT1990/pyflux
	```
- [PyPi](https://pypi.org/project/pyflux) (📥 50K / month):
	```
	pip install pyflux
	```
</details>
<details><summary><b><a href="https://github.com/johannfaouzi/pyts">pyts</a></b> (🥉20 ·  ⭐ 1.1K) - 用于时间序列分类的Python软件包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/johannfaouzi/pyts) (👨‍💻 9 · 🔀 110 · 📦 140 · 📋 52 - 59% open · ⏱️ 23.09.2021):

	```
	git clone https://github.com/johannfaouzi/pyts
	```
- [PyPi](https://pypi.org/project/pyts) (📥 8.4K / month):
	```
	pip install pyts
	```
- [Conda](https://anaconda.org/conda-forge/pyts) (📥 9.1K · ⏱️ 21.03.2020):
	```
	conda install -c conda-forge pyts
	```
</details>
<details><summary><b><a href="https://github.com/python-streamz/streamz">Streamz</a></b> (🥉20 ·  ⭐ 990) - python的实时流处理。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python-streamz/streamz) (👨‍💻 41 · 🔀 120 · 📦 230 · 📋 230 - 40% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/python-streamz/streamz
	```
- [PyPi](https://pypi.org/project/streamz):
	```
	pip install streamz
	```
- [Conda](https://anaconda.org/conda-forge/streamz) (📥 210K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge streamz
	```
</details>
<details><summary><b><a href="https://github.com/TDAmeritrade/stumpy">STUMPY</a></b> (🥉19 ·  ⭐ 2K) - STUMPY是一个功能强大且可扩展的Python库，用于矩阵计算。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/TDAmeritrade/stumpy) (👨‍💻 26 · 🔀 190 · 📋 260 - 10% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/TDAmeritrade/stumpy
	```
- [PyPi](https://pypi.org/project/stumpy):
	```
	pip install stumpy
	```
- [Conda](https://anaconda.org/conda-forge/stumpy) (📥 31K · ⏱️ 28.07.2021):
	```
	conda install -c conda-forge stumpy
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/luminol">luminol</a></b> (🥉19 ·  ⭐ 970 · 💀) - 异常检测和相关库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/linkedin/luminol) (👨‍💻 8 · 🔀 190 · 📦 43 · 📋 36 - 66% open · ⏱️ 09.01.2018):

	```
	git clone https://github.com/linkedin/luminol
	```
- [PyPi](https://pypi.org/project/luminol) (📥 41K / month):
	```
	pip install luminol
	```
</details>
<details><summary><b><a href="https://github.com/arundo/adtk">ADTK</a></b> (🥉18 ·  ⭐ 730 · 💀) - 一个Python工具包，用于基于规则的/无监督的异常检测。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/arundo/adtk) (👨‍💻 11 · 🔀 90 · 📋 60 - 43% open · ⏱️ 17.04.2020):

	```
	git clone https://github.com/arundo/adtk
	```
- [PyPi](https://pypi.org/project/adtk) (📥 80K / month):
	```
	pip install adtk
	```
</details>
<details><summary><b><a href="https://github.com/wwrechard/pydlm">pydlm</a></b> (🥉18 ·  ⭐ 400 · 💀) - 用于贝叶斯时间序列建模的python库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wwrechard/pydlm) (👨‍💻 6 · 🔀 86 · 📦 23 · 📋 43 - 81% open · ⏱️ 22.10.2019):

	```
	git clone https://github.com/wwrechard/pydlm
	```
- [PyPi](https://pypi.org/project/pydlm) (📥 15K / month):
	```
	pip install pydlm
	```
</details>
<details><summary><b><a href="https://github.com/X-DataInitiative/tick">tick</a></b> (🥉18 ·  ⭐ 360 · 💀) - 统计学习模块。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/X-DataInitiative/tick) (👨‍💻 16 · 🔀 80 · 📥 190 · 📦 41 · 📋 220 - 25% open · ⏱️ 15.06.2020):

	```
	git clone https://github.com/X-DataInitiative/tick
	```
- [PyPi](https://pypi.org/project/tick) (📥 1.2K / month):
	```
	pip install tick
	```
</details>
<details><summary><b><a href="https://github.com/target/matrixprofile-ts">matrixprofile-ts</a></b> (🥉17 ·  ⭐ 660 · 💀) - 一个用于检测模式和异常的Python库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/target/matrixprofile-ts) (👨‍💻 15 · 🔀 93 · 📦 17 · 📋 53 - 35% open · ⏱️ 25.04.2020):

	```
	git clone https://github.com/target/matrixprofile-ts
	```
- [PyPi](https://pypi.org/project/matrixprofile-ts) (📥 1.8K / month):
	```
	pip install matrixprofile-ts
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_TS">Auto TS</a></b> (🥉16 ·  ⭐ 310) - 自动实现ARIMA，SARIMAX，VAR，FB Prophet和XGBoost等模型时序建模。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/Auto_TS) (👨‍💻 6 · 🔀 59 · 📋 51 - 15% open · ⏱️ 27.08.2021):

	```
	git clone https://github.com/AutoViML/Auto_TS
	```
- [PyPi](https://pypi.org/project/auto-ts) (📥 1.1K / month):
	```
	pip install auto-ts
	```
</details>
<details><summary><b><a href="https://github.com/dmbee/seglearn">seglearn</a></b> (🥉14 ·  ⭐ 480 · 💤) - 机器学习时间序列的Python模块。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dmbee/seglearn) (👨‍💻 13 · 🔀 51 · 📦 10 · 📋 28 - 17% open · ⏱️ 12.03.2021):

	```
	git clone https://github.com/dmbee/seglearn
	```
- [PyPi](https://pypi.org/project/seglearn):
	```
	pip install seglearn
	```
</details>
<details><summary><b><a href="https://github.com/firmai/atspy">atspy</a></b> (🥉14 ·  ⭐ 380) - AtsPy：Python中的自动时间序列模型。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/firmai/atspy) (👨‍💻 5 · 🔀 75 · 📦 3 · 📋 20 - 90% open · ⏱️ 30.08.2021):

	```
	git clone https://github.com/firmai/atspy
	```
- [PyPi](https://pypi.org/project/atspy) (📥 1.4K / month):
	```
	pip install atspy
	```
</details>
<br>

## 医疗领域

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于处理和分析MRI，EEG，基因组数据和其他医学成像格式等医学数据的库。_

<details><summary><b><a href="https://github.com/CamDavidsonPilon/lifelines">Lifelines</a></b> (🥇29 ·  ⭐ 1.7K) - Python中的生存分析。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CamDavidsonPilon/lifelines) (👨‍💻 98 · 🔀 430 · 📦 690 · 📋 820 - 24% open · ⏱️ 16.09.2021):

	```
	git clone https://github.com/CamDavidsonPilon/lifelines
	```
- [PyPi](https://pypi.org/project/lifelines) (📥 270K / month):
	```
	pip install lifelines
	```
- [Conda](https://anaconda.org/conda-forge/lifelines) (📥 170K · ⏱️ 16.09.2021):
	```
	conda install -c conda-forge lifelines
	```
</details>
<details><summary><b><a href="https://github.com/nipy/nipype">NIPYPE</a></b> (🥇28 ·  ⭐ 590) - 神经影像软件包的工作流程和接口。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nipy/nipype) (👨‍💻 220 · 🔀 440 · 📦 740 · 📋 1.2K - 27% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/nipy/nipype
	```
- [PyPi](https://pypi.org/project/nipype) (📥 27K / month):
	```
	pip install nipype
	```
- [Conda](https://anaconda.org/conda-forge/nipype) (📥 440K · ⏱️ 13.07.2021):
	```
	conda install -c conda-forge nipype
	```
</details>
<details><summary><b><a href="https://github.com/mne-tools/mne-python">MNE</a></b> (🥈27 ·  ⭐ 1.7K) - MNE：Python中的磁脑图（MEG）和脑电图（EEG）。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mne-tools/mne-python) (👨‍💻 270 · 🔀 930 · 📦 1.2K · 📋 3.8K - 8% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/mne-tools/mne-python
	```
- [PyPi](https://pypi.org/project/mne) (📥 29K / month):
	```
	pip install mne
	```
- [Conda](https://anaconda.org/conda-forge/mne) (📥 170K · ⏱️ 22.09.2021):
	```
	conda install -c conda-forge mne
	```
</details>
<details><summary><b><a href="https://github.com/hail-is/hail">Hail</a></b> (🥈26 ·  ⭐ 750) - 可扩展的基因组数据分析。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hail-is/hail) (👨‍💻 74 · 🔀 190 · 📦 44 · 📋 2K - 1% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/hail-is/hail
	```
- [PyPi](https://pypi.org/project/hail) (📥 45K / month):
	```
	pip install hail
	```
</details>
<details><summary><b><a href="https://github.com/nipy/nibabel">NiBabel</a></b> (🥈25 ·  ⭐ 440) - Python软件包，用于访问神经影像文件格式。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nipy/nibabel) (👨‍💻 93 · 🔀 210 · 📦 5.4K · 📋 410 - 25% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/nipy/nibabel
	```
- [PyPi](https://pypi.org/project/nibabel):
	```
	pip install nibabel
	```
- [Conda](https://anaconda.org/conda-forge/nibabel) (📥 380K · ⏱️ 29.11.2020):
	```
	conda install -c conda-forge nibabel
	```
</details>
<details><summary><b><a href="https://github.com/Project-MONAI/MONAI">MONAI</a></b> (🥈24 ·  ⭐ 2.4K) - 用于医疗成像的AI工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Project-MONAI/MONAI) (👨‍💻 78 · 🔀 440 · 📦 120 · 📋 1.2K - 8% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/Project-MONAI/MONAI
	```
- [PyPi](https://pypi.org/project/monai) (📥 18K / month):
	```
	pip install monai
	```
</details>
<details><summary><b><a href="https://github.com/nilearn/nilearn">Nilearn</a></b> (🥈24 ·  ⭐ 780) - Python中NeuroImaging的机器学习。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nilearn/nilearn) (👨‍💻 170 · 🔀 420 · 📥 9 · 📦 1.2K · 📋 1.5K - 14% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/nilearn/nilearn
	```
- [PyPi](https://pypi.org/project/nilearn) (📥 30K / month):
	```
	pip install nilearn
	```
- [Conda](https://anaconda.org/conda-forge/nilearn) (📥 120K · ⏱️ 16.09.2021):
	```
	conda install -c conda-forge nilearn
	```
</details>
<details><summary><b><a href="https://github.com/dipy/dipy">DIPY</a></b> (🥈24 ·  ⭐ 470) - DIPY是Python中的Paragon 3D/4D +影像库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dipy/dipy) (👨‍💻 130 · 🔀 310 · 📦 440 · 📋 720 - 12% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/dipy/dipy
	```
- [PyPi](https://pypi.org/project/dipy) (📥 8.5K / month):
	```
	pip install dipy
	```
- [Conda](https://anaconda.org/conda-forge/dipy) (📥 260K · ⏱️ 06.05.2021):
	```
	conda install -c conda-forge dipy
	```
</details>
<details><summary><b><a href="https://github.com/NifTK/NiftyNet">NiftyNet</a></b> (🥉22 ·  ⭐ 1.3K · 💀) - 开源医疗卷积神经网络工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NifTK/NiftyNet) (👨‍💻 58 · 🔀 390 · 📦 37 · 📋 320 - 30% open · ⏱️ 21.04.2020):

	```
	git clone https://github.com/NifTK/NiftyNet
	```
- [PyPi](https://pypi.org/project/niftynet) (📥 180 / month):
	```
	pip install niftynet
	```
</details>
<details><summary><b><a href="https://github.com/google/deepvariant">DeepVariant</a></b> (🥉21 ·  ⭐ 2.4K) - DeepVariant是使用深度神经网络的分析管道。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/deepvariant) (👨‍💻 20 · 🔀 570 · 📥 3.5K · 📋 440 - 0% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/google/deepvariant
	```
- [Conda](https://anaconda.org/bioconda/deepvariant) (📥 34K · ⏱️ 30.07.2021):
	```
	conda install -c bioconda deepvariant
	```
</details>
<details><summary><b><a href="https://github.com/loli/medpy">MedPy</a></b> (🥉21 ·  ⭐ 370 · 💀) - Python中的医学图像处理。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/loli/medpy) (👨‍💻 13 · 🔀 110 · 📦 400 · 📋 78 - 14% open · ⏱️ 01.05.2020):

	```
	git clone https://github.com/loli/medpy
	```
- [PyPi](https://pypi.org/project/MedPy) (📥 9.2K / month):
	```
	pip install MedPy
	```
</details>
<details><summary><b><a href="https://github.com/projectglow/glow">Glow</a></b> (🥉20 ·  ⭐ 180) - 一个用于大规模基因组分析的开源工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/projectglow/glow) (👨‍💻 16 · 🔀 50 · 📋 110 - 34% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/projectglow/glow
	```
- [PyPi](https://pypi.org/project/glow.py) (📥 47K / month):
	```
	pip install glow.py
	```
</details>
<details><summary><b><a href="https://github.com/DLTK/DLTK">DLTK</a></b> (🥉19 ·  ⭐ 1.3K · 💀) - 用于医学图像分析的深度学习工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/DLTK/DLTK) (👨‍💻 9 · 🔀 390 · 📦 21 · 📋 31 - 22% open · ⏱️ 21.01.2019):

	```
	git clone https://github.com/DLTK/DLTK
	```
- [PyPi](https://pypi.org/project/dltk) (📥 160 / month):
	```
	pip install dltk
	```
</details>
<details><summary><b><a href="https://github.com/nipy/nipy">NIPY</a></b> (🥉18 ·  ⭐ 310 · 💤) - Python FMRI分析软件包中的Neuroimaging。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nipy/nipy) (👨‍💻 63 · 🔀 130 · 📋 150 - 25% open · ⏱️ 29.03.2021):

	```
	git clone https://github.com/nipy/nipy
	```
- [PyPi](https://pypi.org/project/nipy) (📥 1.5K / month):
	```
	pip install nipy
	```
- [Conda](https://anaconda.org/conda-forge/nipy) (📥 88K · ⏱️ 04.05.2020):
	```
	conda install -c conda-forge nipy
	```
</details>
<details><summary><b><a href="https://github.com/brainiak/brainiak">Brainiak</a></b> (🥉17 ·  ⭐ 250) - 脑成像分析套件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/brainiak/brainiak) (👨‍💻 33 · 🔀 120 · 📦 14 · 📋 190 - 35% open · ⏱️ 28.05.2021):

	```
	git clone https://github.com/brainiak/brainiak
	```
- [PyPi](https://pypi.org/project/brainiak) (📥 180 / month):
	```
	pip install brainiak
	```
- [Docker Hub](https://hub.docker.com/r/brainiak/brainiak) (📥 640 · ⭐ 1 · ⏱️ 15.10.2020):
	```
	docker pull brainiak/brainiak
	```
</details>
<details><summary><b><a href="https://github.com/perone/medicaltorch">MedicalTorch</a></b> (🥉15 ·  ⭐ 750) - Pytorch的医学成像框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/perone/medicaltorch) (👨‍💻 8 · 🔀 110 · 📦 11 · 📋 22 - 59% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/perone/medicaltorch
	```
- [PyPi](https://pypi.org/project/medicaltorch) (📥 160 / month):
	```
	pip install medicaltorch
	```
</details>
<details><summary><b><a href="https://github.com/Tencent/MedicalNet">MedicalNet</a></b> (🥉14 ·  ⭐ 1.2K · 💀) - Transfer Learning for 3D Medical Image Analysis的论文实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Tencent/MedicalNet) (🔀 330 · 📋 60 - 76% open · ⏱️ 27.08.2020):

	```
	git clone https://github.com/Tencent/MedicalNet
	```
</details>
<details><summary><b><a href="https://github.com/MIC-DKFZ/medicaldetectiontoolkit">Medical Detection Toolkit</a></b> (🥉13 ·  ⭐ 1K) - Medical Detection Toolkit包含2D + 3D。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MIC-DKFZ/medicaldetectiontoolkit) (👨‍💻 3 · 🔀 270 · 📋 120 - 30% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/MIC-DKFZ/medicaldetectiontoolkit
	```
</details>
<details><summary><b><a href="https://github.com/QTIM-Lab/DeepNeuro">DeepNeuro</a></b> (🥉12 ·  ⭐ 110 · 💀) - 用于神经影像数据的深度学习python软件包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QTIM-Lab/DeepNeuro) (👨‍💻 6 · 🔀 34 · 📦 1 · 📋 41 - 60% open · ⏱️ 24.06.2020):

	```
	git clone https://github.com/QTIM-Lab/DeepNeuro
	```
- [PyPi](https://pypi.org/project/deepneuro) (📥 35 / month):
	```
	pip install deepneuro
	```
</details>
<br>

## 光学字符识别OCR

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于光学字符识别（OCR）和从图像或视频中提取文本的库。_

<details><summary><b><a href="https://github.com/JaidedAI/EasyOCR">EasyOCR</a></b> (🥇29 ·  ⭐ 13K) - 即用型OCR，具有80多种受支持的语言和所有流行的手写文字。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JaidedAI/EasyOCR) (👨‍💻 89 · 🔀 1.6K · 📥 620K · 📦 570 · 📋 420 - 26% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/JaidedAI/EasyOCR
	```
- [PyPi](https://pypi.org/project/easyocr):
	```
	pip install easyocr
	```
</details>
<details><summary><b><a href="https://github.com/sirfz/tesserocr">tesserocr</a></b> (🥇28 ·  ⭐ 1.5K) - 用于tesseract-ocr API的Python包装器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sirfz/tesserocr) (👨‍💻 26 · 🔀 200 · 📦 560 · 📋 220 - 31% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/sirfz/tesserocr
	```
- [PyPi](https://pypi.org/project/tesserocr) (📥 78K / month):
	```
	pip install tesserocr
	```
- [Conda](https://anaconda.org/conda-forge/tesserocr) (📥 59K · ⏱️ 13.01.2021):
	```
	conda install -c conda-forge tesserocr
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleOCR">PaddleOCR</a></b> (🥈27 ·  ⭐ 17K) - 基于PaddlePaddle的多语言OCR工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleOCR) (👨‍💻 53 · 🔀 3.3K · 📦 340 · 📋 3.1K - 27% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/PaddlePaddle/PaddleOCR
	```
- [PyPi](https://pypi.org/project/paddleocr) (📥 31K / month):
	```
	pip install paddleocr
	```
</details>
<details><summary><b><a href="https://github.com/madmaze/pytesseract">Tesseract</a></b> (🥈25 ·  ⭐ 3.8K) - Python-tesseract是一种光学字符识别（OCR）工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/madmaze/pytesseract) (👨‍💻 38 · 🔀 550 · 📋 280 - 3% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/madmaze/pytesseract
	```
- [PyPi](https://pypi.org/project/pytesseract) (📥 1.1M / month):
	```
	pip install pytesseract
	```
- [Conda](https://anaconda.org/conda-forge/pytesseract) (📥 470K · ⏱️ 05.06.2021):
	```
	conda install -c conda-forge pytesseract
	```
</details>
<details><summary><b><a href="https://github.com/faustomorales/keras-ocr">keras-ocr</a></b> (🥈19 ·  ⭐ 920) - CRAFT文本检测器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/faustomorales/keras-ocr) (👨‍💻 11 · 🔀 220 · 📥 150K · 📋 150 - 31% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/faustomorales/keras-ocr
	```
- [PyPi](https://pypi.org/project/keras-ocr) (📥 4.7K / month):
	```
	pip install keras-ocr
	```
</details>
<details><summary><b><a href="https://github.com/Calamari-OCR/calamari">calamari</a></b> (🥈19 ·  ⭐ 860) - 基于OCRopy的基于行的ATR引擎。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Calamari-OCR/calamari) (👨‍💻 19 · 🔀 180 · 📋 220 - 15% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/Calamari-OCR/calamari
	```
- [PyPi](https://pypi.org/project/calamari_ocr) (📥 930 / month):
	```
	pip install calamari_ocr
	```
</details>
<details><summary><b><a href="https://github.com/jbarlow83/OCRmyPDF">OCRmyPDF</a></b> (🥉18 ·  ⭐ 4.9K) - OCRmyPDF将OCR文本层添加到扫描的PDF文件中使用。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/jbarlow83/OCRmyPDF) (👨‍💻 56 · 🔀 470 · 📋 750 - 11% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/jbarlow83/OCRmyPDF
	```
- [PyPi](https://pypi.org/project/ocrmypdf):
	```
	pip install ocrmypdf
	```
</details>
<details><summary><b><a href="https://github.com/emedvedev/attention-ocr">attention-ocr</a></b> (🥉18 ·  ⭐ 870 · 💤) - 用于文本识别的Tensorflow模型。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/emedvedev/attention-ocr) (👨‍💻 27 · 🔀 240 · 📦 18 · 📋 150 - 14% open · ⏱️ 31.10.2020):

	```
	git clone https://github.com/emedvedev/attention-ocr
	```
- [PyPi](https://pypi.org/project/aocr):
	```
	pip install aocr
	```
</details>
<details><summary><b><a href="https://github.com/WZBSocialScienceCenter/pdftabextract">pdftabextract</a></b> (🥉17 ·  ⭐ 2K · 💀) - 一组用于从PDF文件提取表格的工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/WZBSocialScienceCenter/pdftabextract) (👨‍💻 2 · 🔀 340 · 📦 37 · 📋 21 - 14% open · ⏱️ 26.10.2018):

	```
	git clone https://github.com/WZBSocialScienceCenter/pdftabextract
	```
- [PyPi](https://pypi.org/project/pdftabextract) (📥 340 / month):
	```
	pip install pdftabextract
	```
</details>
<details><summary><b><a href="https://github.com/jlsutherland/doc2text">doc2text</a></b> (🥉15 ·  ⭐ 1.2K · 💤) - 批量检测文本块和OCR扫描不良的PDF。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jlsutherland/doc2text) (👨‍💻 5 · 🔀 94 · 📦 47 · 📋 21 - 57% open · ⏱️ 01.12.2020):

	```
	git clone https://github.com/jlsutherland/doc2text
	```
- [PyPi](https://pypi.org/project/doc2text):
	```
	pip install doc2text
	```
</details>
<details><summary><b><a href="https://github.com/aashrafh/Mozart">Mozart</a></b> (🥉10 ·  ⭐ 300) - 光学音乐识别（OMR）系统。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/aashrafh/Mozart) (👨‍💻 5 · 🔀 45 · 📋 6 - 33% open · ⏱️ 05.05.2021):

	```
	git clone https://github.com/aashrafh/Mozart
	```
</details>
<br>

## 数据容器和结构

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_通用数据容器和结构以及pandas的实用程序和扩展。_

<details><summary><b><a href="https://github.com/pandas-dev/pandas">pandas</a></b> (🥇43 ·  ⭐ 31K) - 灵活而强大的数据分析/操作库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pandas-dev/pandas) (👨‍💻 2.8K · 🔀 13K · 📥 120K · 📦 550K · 📋 21K - 15% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/pandas-dev/pandas
	```
- [PyPi](https://pypi.org/project/pandas) (📥 91M / month):
	```
	pip install pandas
	```
- [Conda](https://anaconda.org/conda-forge/pandas) (📥 20M · ⏱️ 12.09.2021):
	```
	conda install -c conda-forge pandas
	```
</details>
<details><summary><b><a href="https://github.com/numpy/numpy">numpy</a></b> (🥇38 ·  ⭐ 18K) - 使用Python进行科学计算的基本软件包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/numpy/numpy) (👨‍💻 1.3K · 🔀 5.8K · 📥 400K · 📦 850K · 📋 10K - 21% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/numpy/numpy
	```
- [PyPi](https://pypi.org/project/numpy) (📥 89M / month):
	```
	pip install numpy
	```
- [Conda](https://anaconda.org/conda-forge/numpy) (📥 24M · ⏱️ 16.08.2021):
	```
	conda install -c conda-forge numpy
	```
</details>
<details><summary><b><a href="https://github.com/h5py/h5py">h5py</a></b> (🥇36 ·  ⭐ 1.6K) - 适用于Python的HDF5-h5py软件包，HDF5的Pythonic接口。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/h5py/h5py) (👨‍💻 170 · 🔀 410 · 📥 1.5K · 📦 130K · 📋 1.2K - 16% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/h5py/h5py
	```
- [PyPi](https://pypi.org/project/h5py) (📥 10M / month):
	```
	pip install h5py
	```
- [Conda](https://anaconda.org/conda-forge/h5py) (📥 6.3M · ⏱️ 13.09.2021):
	```
	conda install -c conda-forge h5py
	```
</details>
<details><summary><b><a href="https://github.com/apache/arrow">Arrow</a></b> (🥈33 ·  ⭐ 8.5K) - Apache Arrow定义了一种在内存中表示tabular data的格式。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/arrow) (👨‍💻 740 · 🔀 2K · 📦 54 · 📋 660 - 1% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/apache/arrow
	```
- [PyPi](https://pypi.org/project/pyarrow) (📥 36M / month):
	```
	pip install pyarrow
	```
- [Conda](https://anaconda.org/conda-forge/arrow) (📥 790K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge arrow
	```
</details>
<details><summary><b><a href="https://github.com/pydata/xarray">xarray</a></b> (🥈30 ·  ⭐ 2.3K) - Python中带有N-D标签的数组和数据集。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pydata/xarray) (👨‍💻 340 · 🔀 710 · 📦 7.8K · 📋 2.9K - 26% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/pydata/xarray
	```
- [PyPi](https://pypi.org/project/xarray) (📥 940K / month):
	```
	pip install xarray
	```
- [Conda](https://anaconda.org/conda-forge/xarray) (📥 4M · ⏱️ 26.07.2021):
	```
	conda install -c conda-forge xarray
	```
</details>
<details><summary><b><a href="https://github.com/databricks/koalas">Koalas</a></b> (🥈29 ·  ⭐ 3K) - Apache Spark上的pandas API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/databricks/koalas) (👨‍💻 51 · 🔀 320 · 📥 1K · 📦 120 · 📋 560 - 14% open · ⏱️ 26.08.2021):

	```
	git clone https://github.com/databricks/koalas
	```
- [PyPi](https://pypi.org/project/koalas) (📥 2.9M / month):
	```
	pip install koalas
	```
- [Conda](https://anaconda.org/conda-forge/koalas) (📥 100K · ⏱️ 18.06.2021):
	```
	conda install -c conda-forge koalas
	```
</details>
<details><summary><b><a href="https://github.com/pydata/bottleneck">Bottleneck</a></b> (🥈29 ·  ⭐ 650 · 💤) - 用C编写的快速NumPy数组函数。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pydata/bottleneck) (👨‍💻 21 · 🔀 70 · 📦 27K · 📋 210 - 16% open · ⏱️ 24.01.2021):

	```
	git clone https://github.com/pydata/bottleneck
	```
- [PyPi](https://pypi.org/project/Bottleneck) (📥 580K / month):
	```
	pip install Bottleneck
	```
- [Conda](https://anaconda.org/conda-forge/bottleneck) (📥 1.7M · ⏱️ 24.08.2021):
	```
	conda install -c conda-forge bottleneck
	```
</details>
<details><summary><b><a href="https://github.com/zarr-developers/zarr-python">zarr</a></b> (🥈28 ·  ⭐ 780) - Python的分块，压缩N维数组的实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/zarr-developers/zarr-python) (👨‍💻 48 · 🔀 120 · 📦 880 · 📋 430 - 38% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/zarr-developers/zarr-python
	```
- [PyPi](https://pypi.org/project/zarr) (📥 56K / month):
	```
	pip install zarr
	```
- [Conda](https://anaconda.org/conda-forge/zarr) (📥 1M · ⏱️ 30.09.2021):
	```
	conda install -c conda-forge zarr
	```
</details>
<details><summary><b><a href="https://github.com/modin-project/modin">Modin</a></b> (🥈27 ·  ⭐ 6.5K) - Modin：通过更改一行来加快Pandas工作流程。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/modin-project/modin) (👨‍💻 81 · 🔀 450 · 📥 200K · 📦 470 · 📋 2K - 28% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/modin-project/modin
	```
- [PyPi](https://pypi.org/project/modin) (📥 140K / month):
	```
	pip install modin
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/sklearn-pandas">sklearn-pandas</a></b> (🥈27 ·  ⭐ 2.5K) - pandas与sklearn集成。<code><a href="https://tldrlegal.com/search?q=Zlib">❗️Zlib</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/sklearn-pandas) (👨‍💻 37 · 🔀 370 · 📦 2.9K · 📋 140 - 12% open · ⏱️ 08.05.2021):

	```
	git clone https://github.com/scikit-learn-contrib/sklearn-pandas
	```
- [PyPi](https://pypi.org/project/sklearn-pandas) (📥 320K / month):
	```
	pip install sklearn-pandas
	```
</details>
<details><summary><b><a href="https://github.com/blaze/blaze">Blaze</a></b> (🥈26 ·  ⭐ 3K · 💀) - NumPy和Pandas连接到大数据。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/blaze/blaze) (👨‍💻 64 · 🔀 350 · 📦 7.9K · 📋 750 - 33% open · ⏱️ 15.08.2019):

	```
	git clone https://github.com/blaze/blaze
	```
- [PyPi](https://pypi.org/project/blaze) (📥 14K / month):
	```
	pip install blaze
	```
- [Conda](https://anaconda.org/conda-forge/blaze) (📥 190K · ⏱️ 15.07.2018):
	```
	conda install -c conda-forge blaze
	```
</details>
<details><summary><b><a href="https://github.com/ekzhu/datasketch">datasketch</a></b> (🥈26 ·  ⭐ 1.6K) - MinHash, LSH, LSH Forest, Weighted MinHash, HyperLogLog等实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ekzhu/datasketch) (👨‍💻 18 · 🔀 220 · 📥 18 · 📦 320 · 📋 120 - 20% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/ekzhu/datasketch
	```
- [PyPi](https://pypi.org/project/datasketch) (📥 320K / month):
	```
	pip install datasketch
	```
</details>
<details><summary><b><a href="https://github.com/nalepae/pandarallel">Pandaral·lel</a></b> (🥉25 ·  ⭐ 1.8K) - A simple and efficient tool to parallelize Pandas.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nalepae/pandarallel) (👨‍💻 15 · 🔀 120 · 📦 300 · 📋 140 - 56% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/nalepae/pandarallel
	```
- [PyPi](https://pypi.org/project/pandarallel) (📥 110K / month):
	```
	pip install pandarallel
	```
</details>
<details><summary><b><a href="https://github.com/msiemens/tinydb">TinyDB</a></b> (🥉24 ·  ⭐ 4.6K) - TinyDB：轻型面向文档的数据库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/msiemens/tinydb) (👨‍💻 68 · 🔀 400 · 📋 270 - 3% open · ⏱️ 23.09.2021):

	```
	git clone https://github.com/msiemens/tinydb
	```
- [PyPi](https://pypi.org/project/tinydb) (📥 420K / month):
	```
	pip install tinydb
	```
- [Conda](https://anaconda.org/conda-forge/tinydb) (📥 140K · ⏱️ 23.09.2021):
	```
	conda install -c conda-forge tinydb
	```
</details>
<details><summary><b><a href="https://github.com/jmcarpenter2/swifter">swifter</a></b> (🥉24 ·  ⭐ 1.8K) - 一个可以对pandas Dataframe或者series做高效function映射的工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jmcarpenter2/swifter) (👨‍💻 14 · 🔀 83 · 📦 400 · 📋 100 - 20% open · ⏱️ 25.06.2021):

	```
	git clone https://github.com/jmcarpenter2/swifter
	```
- [PyPi](https://pypi.org/project/swifter) (📥 130K / month):
	```
	pip install swifter
	```
- [Conda](https://anaconda.org/conda-forge/swifter) (📥 120K · ⏱️ 26.06.2021):
	```
	conda install -c conda-forge swifter
	```
</details>
<details><summary><b><a href="https://github.com/pydata/numexpr">numexpr</a></b> (🥉24 ·  ⭐ 1.7K · 💤) - 适用于Python，NumPy，PyTables等的快速数值数组表达式评估器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydata/numexpr) (👨‍💻 58 · 🔀 160 · 📋 310 - 18% open · ⏱️ 03.03.2021):

	```
	git clone https://github.com/pydata/numexpr
	```
- [PyPi](https://pypi.org/project/numexpr) (📥 1.6M / month):
	```
	pip install numexpr
	```
- [Conda](https://anaconda.org/conda-forge/numexpr) (📥 3.1M · ⏱️ 02.09.2021):
	```
	conda install -c conda-forge numexpr
	```
</details>
<details><summary><b><a href="https://github.com/PyTables/PyTables">PyTables</a></b> (🥉24 ·  ⭐ 1.1K) - 一个Python包，用于管理大量数据。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/PyTables/PyTables) (👨‍💻 99 · 🔀 200 · 📥 160 · 📋 620 - 26% open · ⏱️ 26.09.2021):

	```
	git clone https://github.com/PyTables/PyTables
	```
- [PyPi](https://pypi.org/project/tables) (📥 920K / month):
	```
	pip install tables
	```
- [Conda](https://anaconda.org/conda-forge/pytables) (📥 3.2M · ⏱️ 03.09.2021):
	```
	conda install -c conda-forge pytables
	```
</details>
<details><summary><b><a href="https://github.com/Blosc/bcolz">bcolz</a></b> (🥉24 ·  ⭐ 940 · 💀) - 可以压缩的列式数据容器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Blosc/bcolz) (👨‍💻 33 · 🔀 120 · 📦 1.6K · 📋 240 - 49% open · ⏱️ 10.09.2020):

	```
	git clone https://github.com/Blosc/bcolz
	```
- [PyPi](https://pypi.org/project/bcolz) (📥 16K / month):
	```
	pip install bcolz
	```
- [Conda](https://anaconda.org/conda-forge/bcolz) (📥 270K · ⏱️ 05.11.2019):
	```
	conda install -c conda-forge bcolz
	```
</details>
<details><summary><b><a href="https://github.com/man-group/arctic">Arctic</a></b> (🥉23 ·  ⭐ 2.4K) - Arctic是用于数字数据的高性能数据存储。<code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/man-group/arctic) (👨‍💻 71 · 🔀 470 · 📥 170 · 📦 140 · 📋 520 - 15% open · ⏱️ 23.07.2021):

	```
	git clone https://github.com/man-group/arctic
	```
- [PyPi](https://pypi.org/project/arctic) (📥 4.7K / month):
	```
	pip install arctic
	```
- [Conda](https://anaconda.org/conda-forge/arctic) (📥 16K · ⏱️ 16.12.2019):
	```
	conda install -c conda-forge arctic
	```
</details>
<details><summary><b><a href="https://github.com/vaexio/vaex">Vaex</a></b> (🥉22 ·  ⭐ 6.6K) - 用于Python，ML的核外混合Apache Arrow / NumPy DataFrame可视化等实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vaexio/vaex) (👨‍💻 57 · 🔀 510 · 📥 220 · 📋 840 - 35% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/vaexio/vaex
	```
- [PyPi](https://pypi.org/project/vaex) (📥 20K / month):
	```
	pip install vaex
	```
- [Conda](https://anaconda.org/conda-forge/vaex) (📥 120K · ⏱️ 27.09.2021):
	```
	conda install -c conda-forge vaex
	```
</details>
<details><summary><b><a href="https://github.com/yhat/pandasql">pandasql</a></b> (🥉22 ·  ⭐ 1K · 💀) - pandas的sqldf。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/yhat/pandasql) (👨‍💻 15 · 🔀 150 · 📦 940 · 📋 64 - 64% open · ⏱️ 01.02.2017):

	```
	git clone https://github.com/yhat/pandasql
	```
- [PyPi](https://pypi.org/project/pandasql) (📥 580K / month):
	```
	pip install pandasql
	```
</details>
<details><summary><b><a href="https://github.com/InvestmentSystems/static-frame">StaticFrame</a></b> (🥉21 ·  ⭐ 240) - 类似Pandas的DataFrame的不可变且仅增长的高效数据结构实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/InvestmentSystems/static-frame) (👨‍💻 16 · 🔀 23 · 📦 9 · 📋 330 - 10% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/InvestmentSystems/static-frame
	```
- [PyPi](https://pypi.org/project/static-frame) (📥 1.6K / month):
	```
	pip install static-frame
	```
- [Conda](https://anaconda.org/conda-forge/static-frame) (📥 120K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge static-frame
	```
</details>
<details><summary><b><a href="https://github.com/h2oai/datatable">datatable</a></b> (🥉20 ·  ⭐ 1.4K) - 一个用于处理二维表格数据的Python包。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/h2oai/datatable) (👨‍💻 30 · 🔀 120 · 📥 1.1K · 📋 1.4K - 10% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/h2oai/datatable
	```
- [PyPi](https://pypi.org/project/datatable) (📥 48K / month):
	```
	pip install datatable
	```
</details>
<details><summary><b><a href="https://github.com/mouradmourafiq/pandas-summary">Pandas Summary</a></b> (🥉19 ·  ⭐ 370 · 💀) - pandas Dataframe的describe函数功能扩展。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mouradmourafiq/pandas-summary) (👨‍💻 6 · 🔀 35 · 📦 670 · 📋 13 - 61% open · ⏱️ 24.08.2019):

	```
	git clone https://github.com/mouradmourafiq/pandas-summary
	```
- [PyPi](https://pypi.org/project/pandas-summary) (📥 45K / month):
	```
	pip install pandas-summary
	```
</details>
<details><summary><b><a href="https://github.com/xhochy/fletcher">fletcher</a></b> (🥉19 ·  ⭐ 220 · 💤) - 由Apache Arrow支持的Pandas ExtensionDType/Array。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/xhochy/fletcher) (👨‍💻 24 · 🔀 34 · 📥 13 · 📦 3 · 📋 73 - 45% open · ⏱️ 18.02.2021):

	```
	git clone https://github.com/xhochy/fletcher
	```
- [PyPi](https://pypi.org/project/fletcher) (📥 310 / month):
	```
	pip install fletcher
	```
- [Conda](https://anaconda.org/conda-forge/fletcher) (📥 32K · ⏱️ 17.01.2021):
	```
	conda install -c conda-forge fletcher
	```
</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/bounter">Bounter</a></b> (🥉18 ·  ⭐ 920) - 使用有限内存的高效计数器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RaRe-Technologies/bounter) (👨‍💻 8 · 🔀 47 · 📦 25 · 📋 23 - 60% open · ⏱️ 24.05.2021):

	```
	git clone https://github.com/RaRe-Technologies/bounter
	```
- [PyPi](https://pypi.org/project/bounter) (📥 92 / month):
	```
	pip install bounter
	```
</details>
<details><summary><b><a href="https://github.com/patx/pickledb">pickleDB</a></b> (🥉15 ·  ⭐ 610 · 💀) - pickleDB是使用Python的json的开源键值存储。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/patx/pickledb) (👨‍💻 12 · 🔀 100 · 📦 710 · 📋 53 - 26% open · ⏱️ 15.11.2019):

	```
	git clone https://github.com/patx/pickledb
	```
- [PyPi](https://pypi.org/project/pickledb):
	```
	pip install pickledb
	```
</details>
<details><summary><b><a href="https://github.com/firmai/pandapy">PandaPy</a></b> (🥉11 ·  ⭐ 480) - PandaPy：具有NumPy的速度，性能高于pandas的表格数据实现。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/firmai/pandapy) (👨‍💻 3 · 🔀 54 · 📦 1 · 📋 2 - 50% open · ⏱️ 30.08.2021):

	```
	git clone https://github.com/firmai/pandapy
	```
- [PyPi](https://pypi.org/project/pandapy) (📥 62 / month):
	```
	pip install pandapy
	```
</details>
<br>

## 数据读写与提取

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于从各种数据源和格式加载，收集和提取数据的库。_

<details><summary><b><a href="https://github.com/joke2k/faker">Faker</a></b> (🥇37 ·  ⭐ 13K) - Faker是一个Python软件包，可为您生成伪造数据。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/joke2k/faker) (👨‍💻 430 · 🔀 1.5K · 📦 40K · 📋 520 - 25% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/joke2k/faker
	```
- [PyPi](https://pypi.org/project/Faker) (📥 4.7M / month):
	```
	pip install Faker
	```
- [Conda](https://anaconda.org/conda-forge/faker) (📥 500K · ⏱️ 11.10.2021):
	```
	conda install -c conda-forge faker
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/datasets">Datasets</a></b> (🥇34 ·  ⭐ 10K) - 具有ML模型的最大的即用型NLP数据集合。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/huggingface/datasets) (👨‍💻 320 · 🔀 1.2K · 📦 1.8K · 📋 1K - 33% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/huggingface/datasets
	```
- [PyPi](https://pypi.org/project/datasets) (📥 490K / month):
	```
	pip install datasets
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/tablib">Tablib</a></b> (🥇31 ·  ⭐ 4K) - 用于XLS，CSV，JSON，YAML和＆c中表格数据集的Python模块。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/tablib) (👨‍💻 110 · 🔀 550 · 📦 12K · 📋 230 - 12% open · ⏱️ 04.09.2021):

	```
	git clone https://github.com/jazzband/tablib
	```
- [PyPi](https://pypi.org/project/tablib) (📥 840K / month):
	```
	pip install tablib
	```
- [Conda](https://anaconda.org/conda-forge/tablib) (📥 67K · ⏱️ 05.12.2020):
	```
	conda install -c conda-forge tablib
	```
</details>
<details><summary><b><a href="https://github.com/martinblech/xmltodict">xmltodict</a></b> (🥈30 ·  ⭐ 4.6K · 💀) - 像处理JSON一样处理XML。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/martinblech/xmltodict) (👨‍💻 41 · 🔀 420 · 📦 31K · 📋 200 - 32% open · ⏱️ 26.04.2020):

	```
	git clone https://github.com/martinblech/xmltodict
	```
- [PyPi](https://pypi.org/project/xmltodict) (📥 13M / month):
	```
	pip install xmltodict
	```
- [Conda](https://anaconda.org/conda-forge/xmltodict) (📥 1.2M · ⏱️ 11.02.2019):
	```
	conda install -c conda-forge xmltodict
	```
</details>
<details><summary><b><a href="https://github.com/python-excel/xlrd">xlrd</a></b> (🥈30 ·  ⭐ 1.9K) - xlrd是python语言中用于读取excel表格内容的库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python-excel/xlrd) (👨‍💻 51 · 🔀 410 · 📦 83K · ⏱️ 21.08.2021):

	```
	git clone https://github.com/python-excel/xlrd
	```
- [PyPi](https://pypi.org/project/xlrd) (📥 11M / month):
	```
	pip install xlrd
	```
- [Conda](https://anaconda.org/conda-forge/xlrd) (📥 1.7M · ⏱️ 09.01.2021):
	```
	conda install -c conda-forge xlrd
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/datasets">TensorFlow Datasets</a></b> (🥈28 ·  ⭐ 3K) - TFDS是一个高级数据集合。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/datasets) (👨‍💻 220 · 🔀 1.1K · 📋 890 - 34% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/tensorflow/datasets
	```
- [PyPi](https://pypi.org/project/tensorflow-datasets) (📥 1.8M / month):
	```
	pip install tensorflow-datasets
	```
</details>
<details><summary><b><a href="https://github.com/ahupp/python-magic">python-magic</a></b> (🥈28 ·  ⭐ 2K) - 用于libmagic的python包装器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ahupp/python-magic) (👨‍💻 52 · 🔀 220 · 📦 19K · 📋 160 - 15% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/ahupp/python-magic
	```
- [PyPi](https://pypi.org/project/python-magic) (📥 3.2M / month):
	```
	pip install python-magic
	```
- [Conda](https://anaconda.org/conda-forge/python-magic) (📥 100K · ⏱️ 08.06.2021):
	```
	conda install -c conda-forge python-magic
	```
</details>
<details><summary><b><a href="https://github.com/wireservice/csvkit">csvkit</a></b> (🥈27 ·  ⭐ 4.7K) - 一套实用工具，可转换为CSV并操作。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wireservice/csvkit) (👨‍💻 100 · 🔀 540 · 📦 950 · 📋 830 - 6% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/wireservice/csvkit
	```
- [PyPi](https://pypi.org/project/csvkit) (📥 49K / month):
	```
	pip install csvkit
	```
- [Conda](https://anaconda.org/conda-forge/csvkit) (📥 56K · ⏱️ 13.07.2021):
	```
	conda install -c conda-forge csvkit
	```
</details>
<details><summary><b><a href="https://github.com/snorkel-team/snorkel">snorkel</a></b> (🥈26 ·  ⭐ 4.9K) - 在弱监督环境下快速生成训练数据的系统。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/snorkel-team/snorkel) (👨‍💻 70 · 🔀 770 · 📥 700 · 📦 120 · 📋 960 - 2% open · ⏱️ 23.09.2021):

	```
	git clone https://github.com/snorkel-team/snorkel
	```
- [PyPi](https://pypi.org/project/snorkel) (📥 58K / month):
	```
	pip install snorkel
	```
- [Conda](https://anaconda.org/conda-forge/snorkel) (📥 23K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge snorkel
	```
</details>
<details><summary><b><a href="https://github.com/euske/pdfminer">PDFMiner</a></b> (🥈26 ·  ⭐ 4.7K · 💀) - Python PDF解析器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/euske/pdfminer) (👨‍💻 28 · 🔀 950 · 📦 2.6K · 📋 230 - 82% open · ⏱️ 18.01.2020):

	```
	git clone https://github.com/euske/pdfminer
	```
- [PyPi](https://pypi.org/project/pdfminer) (📥 150K / month):
	```
	pip install pdfminer
	```
- [Conda](https://anaconda.org/conda-forge/pdfminer) (📥 19K · ⏱️ 15.02.2021):
	```
	conda install -c conda-forge pdfminer
	```
</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/smart_open">smart-open</a></b> (🥈26 ·  ⭐ 2.2K) - 用于大文件（S3，HDFS，gzip，bz2 ...）流传输的实用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RaRe-Technologies/smart_open) (👨‍💻 87 · 🔀 280 · 📋 320 - 16% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/RaRe-Technologies/smart_open
	```
- [PyPi](https://pypi.org/project/smart-open) (📥 17M / month):
	```
	pip install smart-open
	```
</details>
<details><summary><b><a href="https://github.com/deanmalmgren/textract">textract</a></b> (🥉24 ·  ⭐ 3.1K) - 从任何文档中提取文本。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/deanmalmgren/textract) (👨‍💻 39 · 🔀 430 · 📋 200 - 37% open · ⏱️ 21.08.2021):

	```
	git clone https://github.com/deanmalmgren/textract
	```
- [PyPi](https://pypi.org/project/textract) (📥 75K / month):
	```
	pip install textract
	```
- [Conda](https://anaconda.org/conda-forge/textract) (📥 13K · ⏱️ 22.08.2021):
	```
	conda install -c conda-forge textract
	```
</details>
<details><summary><b><a href="https://github.com/intake/intake">Intake</a></b> (🥉24 ·  ⭐ 630) - Intake是一个轻量级的程序包，用于查找，调查，加载等。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/intake/intake) (👨‍💻 64 · 🔀 110 · 📦 300 · 📋 280 - 24% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/intake/intake
	```
- [PyPi](https://pypi.org/project/intake) (📥 12K / month):
	```
	pip install intake
	```
- [Conda](https://anaconda.org/conda-forge/intake) (📥 100K · ⏱️ 11.10.2021):
	```
	conda install -c conda-forge intake
	```
</details>
<details><summary><b><a href="https://github.com/sdv-dev/SDV">SDV</a></b> (🥉23 ·  ⭐ 520) - 用于表格，关系和时间序列数据的综合数据生成。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sdv-dev/SDV) (👨‍💻 38 · 🔀 94 · 📦 35 · 📋 370 - 32% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/sdv-dev/SDV
	```
- [PyPi](https://pypi.org/project/sdv) (📥 12K / month):
	```
	pip install sdv
	```
</details>
<details><summary><b><a href="https://github.com/frictionlessdata/tabulator-py">tabulator-py</a></b> (🥉22 ·  ⭐ 210 · 💤) - 用于读取和写入图像数据的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/frictionlessdata/tabulator-py) (👨‍💻 27 · 🔀 42 · 📦 630 · ⏱️ 22.03.2021):

	```
	git clone https://github.com/frictionlessdata/tabulator-py
	```
- [PyPi](https://pypi.org/project/tabulator) (📥 290K / month):
	```
	pip install tabulator
	```
- [Conda](https://anaconda.org/conda-forge/tabulator-py) (📥 45K · ⏱️ 24.07.2018):
	```
	conda install -c conda-forge tabulator-py
	```
</details>
<details><summary><b><a href="https://github.com/pydata/pandas-datareader">pandas-datareader</a></b> (🥉20 ·  ⭐ 2.1K) - 从各种各样的网络来源中提取数据。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pydata/pandas-datareader) (👨‍💻 83 · 🔀 540 · 📋 480 - 18% open · ⏱️ 07.08.2021):

	```
	git clone https://github.com/pydata/pandas-datareader
	```
- [PyPi](https://pypi.org/project/pandas-datareader) (📥 310K / month):
	```
	pip install pandas-datareader
	```
- [Conda](https://anaconda.org/conda-forge/pandas-datareader) (📥 150K · ⏱️ 14.07.2021):
	```
	conda install -c conda-forge pandas-datareader
	```
</details>
<details><summary><b><a href="https://github.com/turicas/rows">rows</a></b> (🥉20 ·  ⭐ 770) - 通用美观的表格数据界面。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/turicas/rows) (👨‍💻 30 · 🔀 130 · 📥 37 · 📦 130 · 📋 290 - 48% open · ⏱️ 22.05.2021):

	```
	git clone https://github.com/turicas/rows
	```
- [PyPi](https://pypi.org/project/rows) (📥 1.8K / month):
	```
	pip install rows
	```
</details>
<details><summary><b><a href="https://github.com/okfn/messytables">messytables</a></b> (🥉20 ·  ⭐ 380 · 💀) - 解析混乱的表格数据的工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/okfn/messytables) (👨‍💻 44 · 🔀 100 · 📦 210 · 📋 85 - 35% open · ⏱️ 13.11.2019):

	```
	git clone https://github.com/okfn/messytables
	```
- [PyPi](https://pypi.org/project/messytables) (📥 10K / month):
	```
	pip install messytables
	```
</details>
<details><summary><b><a href="https://github.com/pyexcel/pyexcel-xlsx">pyexcel-xlsx</a></b> (🥉20 ·  ⭐ 92 · 💤) - 一个包装器库，用于在xlsx和xlsm等文件格式中读取，操作和写入数据。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pyexcel/pyexcel-xlsx) (👨‍💻 4 · 🔀 16 · 📥 51 · 📦 1.4K · 📋 32 - 37% open · ⏱️ 28.11.2020):

	```
	git clone https://github.com/pyexcel/pyexcel-xlsx
	```
- [PyPi](https://pypi.org/project/pyexcel-xlsx) (📥 79K / month):
	```
	pip install pyexcel-xlsx
	```
- [Conda](https://anaconda.org/conda-forge/pyexcel-xlsx) (📥 18K · ⏱️ 10.10.2020):
	```
	conda install -c conda-forge pyexcel-xlsx
	```
</details>
<details><summary><b><a href="https://github.com/shawnbrown/datatest">datatest</a></b> (🥉19 ·  ⭐ 240) - 用于测试驱动的数据整理和数据验证的工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/shawnbrown/datatest) (👨‍💻 6 · 🔀 11 · 📦 48 · 📋 52 - 19% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/shawnbrown/datatest
	```
- [PyPi](https://pypi.org/project/datatest) (📥 18K / month):
	```
	pip install datatest
	```
</details>
<details><summary><b><a href="https://github.com/atlanhq/camelot">Camelot</a></b> (🥉18 ·  ⭐ 3.1K · 💀) - Camelot：简单的PDF表提取。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/atlanhq/camelot) (👨‍💻 23 · 🔀 320 · 📋 350 - 20% open · ⏱️ 15.10.2019):

	```
	git clone https://github.com/atlanhq/camelot
	```
- [PyPi](https://pypi.org/project/camelot-py) (📥 34K / month):
	```
	pip install camelot-py
	```
</details>
<details><summary><b><a href="https://github.com/singer-io/getting-started">Singer</a></b> (🥉17 ·  ⭐ 870) - 在数据库，Web API，文件，队列等之间移动数据的标准。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/singer-io/getting-started) (👨‍💻 26 · 🔀 120 · 📋 37 - 51% open · ⏱️ 29.04.2021):

	```
	git clone https://github.com/singer-io/getting-started
	```
- [PyPi](https://pypi.org/project/singer-python) (📥 110K / month):
	```
	pip install singer-python
	```
</details>
<details><summary><b><a href="https://foss.heptapod.net/openpyxl/openpyxl">openpyxl</a></b> (🥉15 ·  ⭐ 27) - 一个用于读取/写入Excel 2010 xlsx/xlsm文件的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [PyPi](https://pypi.org/project/openpyxl) (📥 17M / month):
	```
	pip install openpyxl
	```
- [GitLab](https://foss.heptapod.net/openpyxl/openpyxl) (🔀 0 · 📋 1.8K - 12% open · ⏱️ 05.10.2021):

	```
	git clone https://foss.heptapod.net/openpyxl/openpyxl
	```
- [Conda](https://anaconda.org/anaconda/openpyxl) (📥 59K · ⏱️ 05.10.2021):
	```
	conda install -c anaconda openpyxl
	```
- [Docker Hub](https://hub.docker.com/r/openpyxl/openpyxl-ci) (📥 1.2K · ⏱️ 13.09.2018):
	```
	docker pull openpyxl/openpyxl-ci
	```
</details>
<br>

## 网页抓取和爬虫

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于Web抓取、爬虫，下载和挖掘的库以及库。_

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-web-python">Python Web Scraping</a></b> ( ⭐ 1.3K)  - Collection of web-scraping and crawling libraries.

<br>

## 数据管道和流处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于数据批处理和流处理，工作流自动化，作业调度和其他数据管道任务的库。_

<details><summary><b><a href="https://github.com/celery/celery">Celery</a></b> (🥇37 ·  ⭐ 18K) - 基于分布式消息传递的异步任务队列/作业队列。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/celery/celery) (👨‍💻 1.2K · 🔀 4K · 📦 59K · 📋 4.6K - 10% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/celery/celery
	```
- [PyPi](https://pypi.org/project/celery) (📥 4.9M / month):
	```
	pip install celery
	```
- [Conda](https://anaconda.org/conda-forge/celery) (📥 670K · ⏱️ 29.06.2021):
	```
	conda install -c conda-forge celery
	```
</details>
<details><summary><b><a href="https://github.com/spotify/luigi">luigi</a></b> (🥇33 ·  ⭐ 15K) - Luigi是一个Python模块，可帮助您构建复杂的批处理管道。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/luigi) (👨‍💻 560 · 🔀 2.2K · 📦 1.6K · 📋 910 - 7% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/spotify/luigi
	```
- [PyPi](https://pypi.org/project/luigi) (📥 700K / month):
	```
	pip install luigi
	```
- [Conda](https://anaconda.org/anaconda/luigi) (📥 8.2K · ⏱️ 17.04.2021):
	```
	conda install -c anaconda luigi
	```
</details>
<details><summary><b><a href="https://github.com/rq/rq">rq</a></b> (🥇31 ·  ⭐ 7.9K) - 适用于Python的简单作业队列。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/rq/rq) (👨‍💻 250 · 🔀 1.2K · 📦 8.9K · 📋 900 - 16% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/rq/rq
	```
- [PyPi](https://pypi.org/project/rq) (📥 500K / month):
	```
	pip install rq
	```
- [Conda](https://anaconda.org/conda-forge/rq) (📥 62K · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge rq
	```
</details>
<details><summary><b><a href="https://github.com/PrefectHQ/prefect">Prefect</a></b> (🥇31 ·  ⭐ 7.5K) - 自动化数据的最简单方法。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PrefectHQ/prefect) (👨‍💻 250 · 🔀 690 · 📦 460 · 📋 1.9K - 19% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/PrefectHQ/prefect
	```
- [PyPi](https://pypi.org/project/prefect) (📥 160K / month):
	```
	pip install prefect
	```
- [Conda](https://anaconda.org/conda-forge/prefect) (📥 210K · ⏱️ 22.09.2021):
	```
	conda install -c conda-forge prefect
	```
</details>
<details><summary><b><a href="https://github.com/dagster-io/dagster">Dagster</a></b> (🥇31 ·  ⭐ 3.9K) - 用于机器学习，分析和ETL的数据协调器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dagster-io/dagster) (👨‍💻 160 · 🔀 440 · 📦 240 · 📋 3.3K - 22% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/dagster-io/dagster
	```
- [PyPi](https://pypi.org/project/dagster) (📥 160K / month):
	```
	pip install dagster
	```
- [Conda](https://anaconda.org/conda-forge/dagster) (📥 380K · ⏱️ 07.10.2021):
	```
	conda install -c conda-forge dagster
	```
</details>
<details><summary><b><a href="https://github.com/dbt-labs/dbt">dbt</a></b> (🥇31 ·  ⭐ 3.6K) - dbt（数据构建工具）方便数据分析人员和工程师快速使用。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dbt-labs/dbt) (👨‍💻 180 · 🔀 660 · 📦 420 · 📋 2.2K - 14% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/fishtown-analytics/dbt
	```
- [PyPi](https://pypi.org/project/dbt) (📥 660K / month):
	```
	pip install dbt
	```
- [Conda](https://anaconda.org/conda-forge/dbt) (📥 180K · ⏱️ 04.05.2021):
	```
	conda install -c conda-forge dbt
	```
</details>
<details><summary><b><a href="https://github.com/joblib/joblib">joblib</a></b> (🥇31 ·  ⭐ 2.6K) - 使用Python函数进行计算。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/joblib/joblib) (👨‍💻 110 · 🔀 300 · 📦 130K · 📋 660 - 43% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/joblib/joblib
	```
- [PyPi](https://pypi.org/project/joblib):
	```
	pip install joblib
	```
- [Conda](https://anaconda.org/conda-forge/joblib) (📥 5.5M · ⏱️ 07.10.2021):
	```
	conda install -c conda-forge joblib
	```
</details>
<details><summary><b><a href="https://github.com/apache/airflow">Airflow</a></b> (🥈28 ·  ⭐ 24K) - 代码实现的创建，安排和监视工作流的平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/airflow) (👨‍💻 2.1K · 🔀 9K · 📥 190K · 📋 4.2K - 18% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/apache/airflow
	```
- [PyPi](https://pypi.org/project/apache-airflow) (📥 2.4M / month):
	```
	pip install apache-airflow
	```
- [Conda](https://anaconda.org/conda-forge/airflow) (📥 410K · ⏱️ 12.10.2021):
	```
	conda install -c conda-forge airflow
	```
- [Docker Hub](https://hub.docker.com/r/apache/airflow) (📥 44M · ⭐ 290 · ⏱️ 11.10.2021):
	```
	docker pull apache/airflow
	```
</details>
<details><summary><b><a href="https://github.com/apache/beam">Beam</a></b> (🥈28 ·  ⭐ 5K) - 统一的编程模型，用于定义和执行数据处理。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/apache/beam) (👨‍💻 1.1K · 🔀 3.1K · ⏱️ 13.10.2021):

	```
	git clone https://github.com/apache/beam
	```
- [PyPi](https://pypi.org/project/apache-beam) (📥 2.8M / month):
	```
	pip install apache-beam
	```
</details>
<details><summary><b><a href="https://github.com/quantumblacklabs/kedro">Kedro</a></b> (🥈27 ·  ⭐ 4.5K) - 用于创建可重现，可维护和模块化的Python框架。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/quantumblacklabs/kedro) (👨‍💻 120 · 🔀 500 · 📦 570 · 📋 540 - 7% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/quantumblacklabs/kedro
	```
- [PyPi](https://pypi.org/project/kedro) (📥 210K / month):
	```
	pip install kedro
	```
</details>
<details><summary><b><a href="https://github.com/activeloopai/Hub">Hub</a></b> (🥈27 ·  ⭐ 3.6K) - TensorFlow/PyTorch最快的非结构化数据集管理。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/activeloopai/Hub) (👨‍💻 85 · 🔀 290 · 📦 130 · 📋 300 - 13% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/activeloopai/Hub
	```
- [PyPi](https://pypi.org/project/hub) (📥 17K / month):
	```
	pip install hub
	```
</details>
<details><summary><b><a href="https://github.com/Yelp/mrjob">mrjob</a></b> (🥈27 ·  ⭐ 2.6K · 💤) - 在Hadoop或Amazon Web Services上运行MapReduce作业。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Yelp/mrjob) (👨‍💻 140 · 🔀 570 · 📦 850 · 📋 1.3K - 15% open · ⏱️ 16.11.2020):

	```
	git clone https://github.com/Yelp/mrjob
	```
- [PyPi](https://pypi.org/project/mrjob) (📥 100K / month):
	```
	pip install mrjob
	```
- [Conda](https://anaconda.org/conda-forge/mrjob) (📥 400K · ⏱️ 24.12.2020):
	```
	conda install -c conda-forge mrjob
	```
</details>
<details><summary><b><a href="https://github.com/robinhood/faust">faust</a></b> (🥈26 ·  ⭐ 5.8K · 💤) - Python流处理。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/robinhood/faust) (👨‍💻 91 · 🔀 480 · 📦 860 · 📋 450 - 47% open · ⏱️ 09.10.2020):

	```
	git clone https://github.com/robinhood/faust
	```
- [PyPi](https://pypi.org/project/faust) (📥 510K / month):
	```
	pip install faust
	```
</details>
<details><summary><b><a href="https://github.com/EntilZha/PyFunctional">PyFunctional</a></b> (🥈26 ·  ⭐ 1.9K) - 用于创建具有链功能的数据管道的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/EntilZha/PyFunctional) (👨‍💻 24 · 🔀 100 · 📦 340 · 📋 120 - 2% open · ⏱️ 06.07.2021):

	```
	git clone https://github.com/EntilZha/PyFunctional
	```
- [PyPi](https://pypi.org/project/pyfunctional) (📥 74K / month):
	```
	pip install pyfunctional
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tfx">TFX</a></b> (🥈26 ·  ⭐ 1.6K) - TFX是用于部署机器学习生产流水线的端到端平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tfx) (👨‍💻 120 · 🔀 480 · 📋 680 - 33% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/tensorflow/tfx
	```
- [PyPi](https://pypi.org/project/tfx) (📥 780K / month):
	```
	pip install tfx
	```
</details>
<details><summary><b><a href="https://github.com/petl-developers/petl">petl</a></b> (🥈26 ·  ⭐ 930) - Python提取转换并加载数据表。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/petl-developers/petl) (👨‍💻 49 · 🔀 160 · 📦 520 · 📋 420 - 17% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/petl-developers/petl
	```
- [PyPi](https://pypi.org/project/petl) (📥 35K / month):
	```
	pip install petl
	```
- [Conda](https://anaconda.org/conda-forge/petl) (📥 31K · ⏱️ 05.04.2021):
	```
	conda install -c conda-forge petl
	```
</details>
<details><summary><b><a href="https://github.com/great-expectations/great_expectations">Great Expectations</a></b> (🥉24 ·  ⭐ 5.5K) - 通过数据测试，文档编制和性能分析，帮助数据团队加速流水线效率。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/great-expectations/great_expectations) (👨‍💻 230 · 🔀 720 · 📋 1K - 13% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/great-expectations/great_expectations
	```
- [PyPi](https://pypi.org/project/great_expectations) (📥 1.8M / month):
	```
	pip install great_expectations
	```
</details>
<details><summary><b><a href="https://github.com/python-bonobo/bonobo">bonobo</a></b> (🥉21 ·  ⭐ 1.5K · 💤) - 提取适用于Python 3.5+的Transform Load。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/python-bonobo/bonobo) (👨‍💻 37 · 🔀 120 · 📦 120 · 📋 180 - 38% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/python-bonobo/bonobo
	```
- [PyPi](https://pypi.org/project/bonobo) (📥 3.7K / month):
	```
	pip install bonobo
	```
</details>
<details><summary><b><a href="https://github.com/Parsely/streamparse">streamparse</a></b> (🥉21 ·  ⭐ 1.4K · 💤) - 在Apache Storm拓扑中运行Python。 Pythonic API，CLI 等。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Parsely/streamparse) (👨‍💻 41 · 🔀 210 · 📦 50 · 📋 320 - 19% open · ⏱️ 18.12.2020):

	```
	git clone https://github.com/Parsely/streamparse
	```
- [PyPi](https://pypi.org/project/streamparse) (📥 3.5K / month):
	```
	pip install streamparse
	```
</details>
<details><summary><b><a href="https://github.com/svenkreiss/pysparkling">pysparkling</a></b> (🥉21 ·  ⭐ 240 · 💤) - Apache Spark的RDD和DStream的纯Python实现。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/svenkreiss/pysparkling) (👨‍💻 10 · 🔀 39 · 📦 72 · 📋 27 - 22% open · ⏱️ 22.02.2021):

	```
	git clone https://github.com/svenkreiss/pysparkling
	```
- [PyPi](https://pypi.org/project/pysparkling) (📥 20K / month):
	```
	pip install pysparkling
	```
</details>
<details><summary><b><a href="https://github.com/douban/dpark">dpark</a></b> (🥉20 ·  ⭐ 2.7K · 💤) - dpark是Python中与MapReduce相似的框架。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/douban/dpark) (👨‍💻 35 · 🔀 540 · 📦 3 · ⏱️ 25.12.2020):

	```
	git clone https://github.com/douban/dpark
	```
- [PyPi](https://pypi.org/project/dpark) (📥 91 / month):
	```
	pip install dpark
	```
</details>
<details><summary><b><a href="https://github.com/closeio/tasktiger">TaskTiger</a></b> (🥉20 ·  ⭐ 1.1K) - 使用Redis的Python任务队列。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/closeio/tasktiger) (👨‍💻 23 · 🔀 59 · 📦 20 · 📋 57 - 38% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/closeio/tasktiger
	```
- [PyPi](https://pypi.org/project/tasktiger) (📥 4.3K / month):
	```
	pip install tasktiger
	```
</details>
<details><summary><b><a href="https://github.com/cgarciae/pypeln">Pypeline</a></b> (🥉19 ·  ⭐ 1.3K) - Python中的并发数据管道。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cgarciae/pypeln) (👨‍💻 10 · 🔀 74 · 📋 52 - 26% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/cgarciae/pypeln
	```
- [PyPi](https://pypi.org/project/pypeln) (📥 9.6K / month):
	```
	pip install pypeln
	```
</details>
<details><summary><b><a href="https://github.com/pricingassistant/mrq">mrq</a></b> (🥉19 ·  ⭐ 850 · 💤) - Mr. Queue - 使用Redis和gevent的Python中的分布式worker任务队列。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pricingassistant/mrq) (👨‍💻 37 · 🔀 110 · 📦 25 · 📋 170 - 30% open · ⏱️ 13.12.2020):

	```
	git clone https://github.com/pricingassistant/mrq
	```
- [PyPi](https://pypi.org/project/mrq) (📥 380 / month):
	```
	pip install mrq
	```
</details>
<details><summary><b><a href="https://github.com/pdpipe/pdpipe">pdpipe</a></b> (🥉19 ·  ⭐ 620) - pandas DataFrames的简单管道。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pdpipe/pdpipe) (👨‍💻 8 · 🔀 28 · 📦 36 · 📋 24 - 33% open · ⏱️ 29.09.2021):

	```
	git clone https://github.com/pdpipe/pdpipe
	```
- [PyPi](https://pypi.org/project/pdpipe) (📥 2.1K / month):
	```
	pip install pdpipe
	```
</details>
<details><summary><b><a href="https://github.com/databricks/spark-deep-learning">spark-deep-learning</a></b> (🥉18 ·  ⭐ 1.9K) - 适用于Apache Spark的深度学习管道。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/databricks/spark-deep-learning) (👨‍💻 16 · 🔀 460 · 📦 18 · 📋 100 - 73% open · ⏱️ 19.08.2021):

	```
	git clone https://github.com/databricks/spark-deep-learning
	```
</details>
<details><summary><b><a href="https://github.com/hi-primus/optimus">Optimus</a></b> (🥉18 ·  ⭐ 1.1K) - 基于pandas、dask等的敏捷数据预处理工作流程。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hi-primus/optimus) (👨‍💻 23 · 🔀 200 · 📋 220 - 15% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/ironmussa/Optimus
	```
- [PyPi](https://pypi.org/project/optimuspyspark) (📥 7.6K / month):
	```
	pip install optimuspyspark
	```
</details>
<details><summary><b><a href="https://github.com/ploomber/ploomber">ploomber</a></b> (🥉18 ·  ⭐ 600) - 精益数据科学工作流程。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ploomber/ploomber) (👨‍💻 10 · 🔀 20 · 📦 14 · 📋 340 - 15% open · ⏱️ 09.10.2021):

	```
	git clone https://github.com/ploomber/ploomber
	```
- [PyPi](https://pypi.org/project/ploomber) (📥 3.1K / month):
	```
	pip install ploomber
	```
</details>
<details><summary><b><a href="https://github.com/analysiscenter/batchflow">BatchFlow</a></b> (🥉18 ·  ⭐ 160) - BatchFlow可帮助您方便地使用随机或顺序调度数据进行机器学习任务。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/analysiscenter/batchflow) (👨‍💻 30 · 🔀 37 · 📋 100 - 33% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/analysiscenter/batchflow
	```
- [PyPi](https://pypi.org/project/batchflow):
	```
	pip install batchflow
	```
</details>
<details><summary><b><a href="https://github.com/mara/mara-pipelines">Mara Pipelines</a></b> (🥉17 ·  ⭐ 1.8K) - 一个轻量级的ETL框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mara/mara-pipelines) (👨‍💻 16 · 🔀 84 · 📦 7 · 📋 18 - 33% open · ⏱️ 18.09.2021):

	```
	git clone https://github.com/mara/mara-pipelines
	```
- [PyPi](https://pypi.org/project/mara-pipelines) (📥 69 / month):
	```
	pip install mara-pipelines
	```
</details>
<details><summary><b><a href="https://github.com/zenml-io/zenml">zenml</a></b> (🥉17 ·  ⭐ 1.3K) - ZenML：MLOps框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/zenml-io/zenml) (👨‍💻 17 · 🔀 72 · 📋 47 - 10% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/maiot-io/zenml
	```
- [PyPi](https://pypi.org/project/zenml) (📥 680 / month):
	```
	pip install zenml
	```
</details>
<details><summary><b><a href="https://github.com/d6t/d6tflow">Databolt Flow</a></b> (🥉17 ·  ⭐ 930) - Python库，用于构建高效的数据科学工作流程。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/d6t/d6tflow) (👨‍💻 12 · 🔀 68 · 📦 16 · 📋 22 - 40% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/d6t/d6tflow
	```
- [PyPi](https://pypi.org/project/d6tflow) (📥 300 / month):
	```
	pip install d6tflow
	```
</details>
<details><summary><b><a href="https://github.com/nerevu/riko">riko</a></b> (🥉16 ·  ⭐ 1.6K · 💀) - 一个模仿Yahoo!的Python流处理引擎。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nerevu/riko) (👨‍💻 18 · 🔀 66 · 📋 29 - 72% open · ⏱️ 14.08.2020):

	```
	git clone https://github.com/nerevu/riko
	```
- [PyPi](https://pypi.org/project/riko) (📥 250 / month):
	```
	pip install riko
	```
</details>
<details><summary><b><a href="https://github.com/olirice/flupy">flupy</a></b> (🥉15 ·  ⭐ 160) - python中的流利数据管道。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/olirice/flupy) (👨‍💻 5 · 🔀 10 · 📋 8 - 12% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/olirice/flupy
	```
- [PyPi](https://pypi.org/project/flupy) (📥 85K / month):
	```
	pip install flupy
	```
</details>
<details><summary><b><a href="https://github.com/kkyon/botflow">Botflow</a></b> (🥉12 ·  ⭐ 1.2K · 💀) - 适用于数据管道工作的Python快速数据流编程框架。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/kkyon/botflow) (👨‍💻 11 · 🔀 99 · 📦 1 · 📋 4 - 50% open · ⏱️ 23.05.2019):

	```
	git clone https://github.com/kkyon/botflow
	```
- [PyPi](https://pypi.org/project/botflow) (📥 40 / month):
	```
	pip install botflow
	```
</details>
<details><summary><b><a href="https://github.com/bodywork-ml/bodywork-core">bodywork-core</a></b> (🥉12 ·  ⭐ 300) - MLOps工具，用于将机器学习项目部署到Kubernetes。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/bodywork-ml/bodywork-core) (👨‍💻 4 · 🔀 12 · 📦 7 · 📋 55 - 21% open · ⏱️ 05.07.2021):

	```
	git clone https://github.com/bodywork-ml/bodywork-core
	```
- [PyPi](https://pypi.org/project/bodywork-core):
	```
	pip install bodywork-core
	```
</details>
<br>

## 分布式机器学习

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_提供在大型计算基础架构中分布和并行化机器学习任务的功能的库。_

<details><summary><b><a href="https://github.com/dask/dask">dask</a></b> (🥇32 ·  ⭐ 8.9K) - 具有任务调度的并行计算。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask) (👨‍💻 480 · 🔀 1.3K · 📦 31K · 📋 3.9K - 16% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/dask/dask
	```
- [PyPi](https://pypi.org/project/dask) (📥 7.2M / month):
	```
	pip install dask
	```
- [Conda](https://anaconda.org/conda-forge/dask) (📥 4.3M · ⏱️ 22.09.2021):
	```
	conda install -c conda-forge dask
	```
</details>
<details><summary><b><a href="https://github.com/ray-project/ray">Ray</a></b> (🥇29 ·  ⭐ 18K) - 一个开源代码框架，提供了用于构建分布式应用程序的简单通用API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ray-project/ray) (👨‍💻 570 · 🔀 2.9K · 📋 8K - 21% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/ray-project/ray
	```
- [PyPi](https://pypi.org/project/ray) (📥 570K / month):
	```
	pip install ray
	```
</details>
<details><summary><b><a href="https://github.com/dask/distributed">dask.distributed</a></b> (🥇28 ·  ⭐ 1.3K) - Dask的分布式任务调度规划程序。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dask/distributed) (👨‍💻 250 · 🔀 540 · 📦 20K · 📋 2.3K - 34% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/dask/distributed
	```
- [PyPi](https://pypi.org/project/distributed) (📥 6.8M / month):
	```
	pip install distributed
	```
- [Conda](https://anaconda.org/conda-forge/distributed) (📥 5.4M · ⏱️ 22.09.2021):
	```
	conda install -c conda-forge distributed
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/mesh">Mesh</a></b> (🥇28 ·  ⭐ 1.1K) - Mesh TensorFlow：简化模型并行化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/mesh) (👨‍💻 44 · 🔀 180 · 📦 580 · 📋 74 - 81% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/tensorflow/mesh
	```
- [PyPi](https://pypi.org/project/mesh-tensorflow) (📥 450K / month):
	```
	pip install mesh-tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/horovod/horovod">horovod</a></b> (🥈27 ·  ⭐ 12K) - 基于TensorFlow，Keras，PyTorch，MXNet等的分布式训练框架。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/horovod/horovod) (👨‍💻 140 · 🔀 1.9K · 📦 440 · 📋 1.9K - 13% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/horovod/horovod
	```
- [PyPi](https://pypi.org/project/horovod) (📥 48K / month):
	```
	pip install horovod
	```
</details>
<details><summary><b><a href="https://github.com/DEAP/deap">DEAP</a></b> (🥈27 ·  ⭐ 4.4K) - Python中的分布式进化算法。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/DEAP/deap) (👨‍💻 68 · 🔀 910 · 📦 2.1K · 📋 420 - 45% open · ⏱️ 08.05.2021):

	```
	git clone https://github.com/deap/deap
	```
- [PyPi](https://pypi.org/project/deap) (📥 180K / month):
	```
	pip install deap
	```
- [Conda](https://anaconda.org/conda-forge/deap) (📥 150K · ⏱️ 01.08.2021):
	```
	conda install -c conda-forge deap
	```
</details>
<details><summary><b><a href="https://github.com/maxpumperla/elephas">Elephas</a></b> (🥈27 ·  ⭐ 1.5K) - 使用Keras和Spark进行分布式深度学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>keras</code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maxpumperla/elephas) (👨‍💻 27 · 🔀 290 · 📦 47 · 📋 150 - 15% open · ⏱️ 17.08.2021):

	```
	git clone https://github.com/maxpumperla/elephas
	```
- [PyPi](https://pypi.org/project/elephas) (📥 63K / month):
	```
	pip install elephas
	```
</details>
<details><summary><b><a href="https://github.com/uber/petastorm">petastorm</a></b> (🥈27 ·  ⭐ 1.2K) - Petastorm库单机或分布式训练。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber/petastorm) (👨‍💻 41 · 🔀 210 · 📥 310 · 📦 43 · 📋 250 - 48% open · ⏱️ 03.09.2021):

	```
	git clone https://github.com/uber/petastorm
	```
- [PyPi](https://pypi.org/project/petastorm) (📥 150K / month):
	```
	pip install petastorm
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/DeepSpeed">DeepSpeed</a></b> (🥈26 ·  ⭐ 5.7K) - DeepSpeed是一个深度学习优化库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/DeepSpeed) (👨‍💻 71 · 🔀 600 · 📦 100 · 📋 640 - 48% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/microsoft/DeepSpeed
	```
- [PyPi](https://pypi.org/project/deepspeed) (📥 45K / month):
	```
	pip install deepspeed
	```
- [Docker Hub](https://hub.docker.com/r/deepspeed/deepspeed) (📥 11K · ⭐ 3 · ⏱️ 05.05.2021):
	```
	docker pull deepspeed/deepspeed
	```
</details>
<details><summary><b><a href="https://github.com/intel-analytics/BigDL">BigDL</a></b> (🥈25 ·  ⭐ 3.8K) - BigDL：适用于Apache Spark的分布式深度学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/intel-analytics/BigDL) (👨‍💻 74 · 🔀 870 · 📦 27 · 📋 890 - 18% open · ⏱️ 21.09.2021):

	```
	git clone https://github.com/intel-analytics/BigDL
	```
- [PyPi](https://pypi.org/project/bigdl) (📥 2.8K / month):
	```
	pip install bigdl
	```
- [Maven](https://search.maven.org/artifact/com.intel.analytics.bigdl/bigdl-SPARK_2.4):
	```
	<dependency>
		<groupId>com.intel.analytics.bigdl</groupId>
		<artifactId>bigdl-SPARK_2.4</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<details><summary><b><a href="https://github.com/yahoo/TensorFlowOnSpark">TensorFlowOnSpark</a></b> (🥈23 ·  ⭐ 3.7K) - TensorFlowOnSpark将TensorFlow程序引入Spark。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/yahoo/TensorFlowOnSpark) (👨‍💻 33 · 🔀 920 · 📋 360 - 1% open · ⏱️ 07.07.2021):

	```
	git clone https://github.com/yahoo/TensorFlowOnSpark
	```
- [PyPi](https://pypi.org/project/tensorflowonspark) (📥 250K / month):
	```
	pip install tensorflowonspark
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/SynapseML">MMLSpark</a></b> (🥈23 ·  ⭐ 2.4K) - 适用于Apache Spark的Microsoft机器学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/SynapseML) (👨‍💻 70 · 🔀 550 · 📋 440 - 42% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/Azure/mmlspark
	```
- [PyPi](https://pypi.org/project/mmlspark) (📥 38K / month):
	```
	pip install mmlspark
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fairscale">FairScale</a></b> (🥈23 ·  ⭐ 1.4K) - PyTorch扩展用于高性能和大规模训练。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/fairscale) (👨‍💻 44 · 🔀 120 · 📦 86 · 📋 220 - 22% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/facebookresearch/fairscale
	```
- [PyPi](https://pypi.org/project/fairscale) (📥 44K / month):
	```
	pip install fairscale
	```
</details>
<details><summary><b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥉22 ·  ⭐ 2.1K) - Python中的交互式并行计算。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ipython/ipyparallel) (👨‍💻 100 · 🔀 800 · 📦 1.7K · 📋 300 - 16% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/ipython/ipyparallel
	```
- [PyPi](https://pypi.org/project/ipyparallel) (📥 47K / month):
	```
	pip install ipyparallel
	```
- [Conda](https://anaconda.org/conda-forge/ipyparallel) (📥 510K · ⏱️ 30.09.2021):
	```
	conda install -c conda-forge ipyparallel
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask-ml">dask-ml</a></b> (🥉22 ·  ⭐ 750) - 使用Dask进行可扩展的机器学习。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask-ml) (👨‍💻 67 · 🔀 200 · 📦 480 · 📋 410 - 44% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/dask/dask-ml
	```
- [PyPi](https://pypi.org/project/dask-ml) (📥 37K / month):
	```
	pip install dask-ml
	```
- [Conda](https://anaconda.org/conda-forge/dask-ml) (📥 240K · ⏱️ 03.05.2021):
	```
	conda install -c conda-forge dask-ml
	```
</details>
<details><summary><b><a href="https://github.com/intel-analytics/analytics-zoo">analytics-zoo</a></b> (🥉20 ·  ⭐ 2.4K) - Apache上的分布式Tensorflow，Keras和PyTorch。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/intel-analytics/analytics-zoo) (👨‍💻 100 · 🔀 680 · 📦 2 · 📋 1.2K - 34% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/intel-analytics/analytics-zoo
	```
- [PyPi](https://pypi.org/project/analytics-zoo):
	```
	pip install analytics-zoo
	```
</details>
<details><summary><b><a href="https://github.com/databricks/tensorframes">TensorFrames</a></b> (🥉20 ·  ⭐ 760 · 💀) - 用于DataFrames的Tensorflow包装器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/databricks/tensorframes) (👨‍💻 16 · 🔀 160 · 📋 91 - 52% open · ⏱️ 15.11.2019):

	```
	git clone https://github.com/databricks/tensorframes
	```
- [PyPi](https://pypi.org/project/tensorframes) (📥 20K / month):
	```
	pip install tensorframes
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/submitit">Submit it</a></b> (🥉20 ·  ⭐ 480) - 用于将作业提交到Slurm的Python工具箱。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookincubator/submitit) (👨‍💻 16 · 🔀 40 · 📦 240 · 📋 46 - 39% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/facebookincubator/submitit
	```
- [PyPi](https://pypi.org/project/submitit) (📥 6.8K / month):
	```
	pip install submitit
	```
- [Conda](https://anaconda.org/conda-forge/submitit) (📥 4.5K · ⏱️ 10.02.2021):
	```
	conda install -c conda-forge submitit
	```
</details>
<details><summary><b><a href="https://github.com/mpi4py/mpi4py">mpi4py</a></b> (🥉20 ·  ⭐ 460) - MPI的Python接口。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mpi4py/mpi4py) (👨‍💻 19 · 🔀 71 · 📥 1.9K · 📋 45 - 20% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/mpi4py/mpi4py
	```
- [PyPi](https://pypi.org/project/mpi4py) (📥 120K / month):
	```
	pip install mpi4py
	```
- [Conda](https://anaconda.org/conda-forge/mpi4py) (📥 790K · ⏱️ 15.08.2021):
	```
	conda install -c conda-forge mpi4py
	```
</details>
<details><summary><b><a href="https://github.com/apache/singa">Apache Singa</a></b> (🥉19 ·  ⭐ 2.4K) - 分布式深度学习平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/singa) (👨‍💻 76 · 🔀 670 · 📦 1 · 📋 62 - 25% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/apache/singa
	```
- [Conda](https://anaconda.org/nusdbsystem/singa) (📥 310 · ⏱️ 09.08.2021):
	```
	conda install -c nusdbsystem singa
	```
- [Docker Hub](https://hub.docker.com/r/apache/singa) (📥 200 · ⭐ 4 · ⏱️ 04.06.2019):
	```
	docker pull apache/singa
	```
</details>
<details><summary><b><a href="https://github.com/learning-at-home/hivemind">Hivemind</a></b> (🥉18 ·  ⭐ 840) - PyTorch中的分布式深度学习。专为训练模型而设计。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/learning-at-home/hivemind) (👨‍💻 17 · 🔀 48 · 📦 3 · 📋 100 - 39% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/learning-at-home/hivemind
	```
- [PyPi](https://pypi.org/project/hivemind) (📥 130 / month):
	```
	pip install hivemind
	```
</details>
<details><summary><b><a href="https://github.com/bytedance/byteps">BytePS</a></b> (🥉17 ·  ⭐ 3K) - 分布式DNN训练的高性能通用框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bytedance/byteps) (👨‍💻 19 · 🔀 410 · 📋 240 - 37% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/bytedance/byteps
	```
- [PyPi](https://pypi.org/project/byteps) (📥 220 / month):
	```
	pip install byteps
	```
- [Docker Hub](https://hub.docker.com/r/bytepsimage/tensorflow) (📥 1.2K · ⏱️ 03.03.2020):
	```
	docker pull bytepsimage/tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/peterwittek/somoclu">somoclu</a></b> (🥉17 ·  ⭐ 230) - 大规模并行的自组织图：加速训练。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/peterwittek/somoclu) (👨‍💻 19 · 🔀 61 · 📥 1.5K · 📋 130 - 19% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/peterwittek/somoclu
	```
- [PyPi](https://pypi.org/project/somoclu) (📥 970 / month):
	```
	pip install somoclu
	```
- [Conda](https://anaconda.org/conda-forge/somoclu) (📥 55K · ⏱️ 13.10.2020):
	```
	conda install -c conda-forge somoclu
	```
</details>
<details><summary><b><a href="https://github.com/uber/fiber">Fiber</a></b> (🥉16 ·  ⭐ 930 · 💤) - 简化了AI的分布式计算。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber/fiber) (👨‍💻 5 · 🔀 100 · 📦 29 · 📋 24 - 66% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/uber/fiber
	```
- [PyPi](https://pypi.org/project/fiber) (📥 2.7K / month):
	```
	pip install fiber
	```
</details>
<details><summary><b><a href="https://github.com/Ibotta/sk-dist">sk-dist</a></b> (🥉16 ·  ⭐ 270) - PySpark中的分布式scikit学习元估计器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Ibotta/sk-dist) (👨‍💻 7 · 🔀 46 · 📦 8 · 📋 17 - 41% open · ⏱️ 07.07.2021):

	```
	git clone https://github.com/Ibotta/sk-dist
	```
- [PyPi](https://pypi.org/project/sk-dist) (📥 14K / month):
	```
	pip install sk-dist
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/lazycluster">LazyCluster</a></b> (🥉12 ·  ⭐ 44) - 分布式机器学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ml-tooling/lazycluster) (👨‍💻 2 · 🔀 8 · 📦 7 · ⏱️ 19.08.2021):

	```
	git clone https://github.com/ml-tooling/lazycluster
	```
- [PyPi](https://pypi.org/project/lazycluster) (📥 71 / month):
	```
	pip install lazycluster
	```
</details>
<br>

## 超参数优化和AutoML

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于超参数优化，自动机器学习和神经体系结构搜索的库。_

<details><summary><b><a href="https://github.com/optuna/optuna">Optuna</a></b> (🥇33 ·  ⭐ 5.3K) - 超参数优化框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/optuna/optuna) (👨‍💻 150 · 🔀 570 · 📦 2K · 📋 940 - 12% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/optuna/optuna
	```
- [PyPi](https://pypi.org/project/optuna) (📥 840K / month):
	```
	pip install optuna
	```
- [Conda](https://anaconda.org/conda-forge/optuna) (📥 43K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge optuna
	```
</details>
<details><summary><b><a href="https://github.com/scikit-optimize/scikit-optimize">scikit-optimize</a></b> (🥇31 ·  ⭐ 2.2K) - SMBO模型优化实现。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/scikit-optimize/scikit-optimize) (👨‍💻 75 · 🔀 390 · 📦 2K · 📋 580 - 33% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/scikit-optimize/scikit-optimize
	```
- [PyPi](https://pypi.org/project/scikit-optimize) (📥 1M / month):
	```
	pip install scikit-optimize
	```
- [Conda](https://anaconda.org/conda-forge/scikit-optimize) (📥 440K · ⏱️ 04.09.2020):
	```
	conda install -c conda-forge scikit-optimize
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/autokeras">AutoKeras</a></b> (🥇30 ·  ⭐ 8.2K) - 用于深度学习的AutoML库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/autokeras) (👨‍💻 130 · 🔀 1.3K · 📥 790 · 📦 240 · 📋 780 - 6% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/keras-team/autokeras
	```
- [PyPi](https://pypi.org/project/autokeras) (📥 30K / month):
	```
	pip install autokeras
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/nni">NNI</a></b> (🥇29 ·  ⭐ 10K) - 一个开源AutoML工具箱，用于自动化机器学习生命周期。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/nni) (👨‍💻 150 · 🔀 1.4K · 📦 150 · 📋 1.4K - 14% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/microsoft/nni
	```
- [PyPi](https://pypi.org/project/nni) (📥 13K / month):
	```
	pip install nni
	```
</details>
<details><summary><b><a href="https://github.com/fmfn/BayesianOptimization">Bayesian Optimization</a></b> (🥇29 ·  ⭐ 5.4K · 💤) - 全局优化的Python实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fmfn/BayesianOptimization) (👨‍💻 27 · 🔀 1.2K · 📥 67 · 📦 900 · 📋 210 - 19% open · ⏱️ 19.12.2020):

	```
	git clone https://github.com/fmfn/BayesianOptimization
	```
- [PyPi](https://pypi.org/project/bayesian-optimization) (📥 130K / month):
	```
	pip install bayesian-optimization
	```
</details>
<details><summary><b><a href="https://github.com/EpistasisLab/tpot">TPOT</a></b> (🥈28 ·  ⭐ 8.3K · 💤) - Python自动化机器学习工具。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/EpistasisLab/tpot) (👨‍💻 110 · 🔀 1.4K · 📦 1.2K · 📋 830 - 27% open · ⏱️ 06.01.2021):

	```
	git clone https://github.com/EpistasisLab/tpot
	```
- [PyPi](https://pypi.org/project/tpot) (📥 29K / month):
	```
	pip install tpot
	```
- [Conda](https://anaconda.org/conda-forge/tpot) (📥 130K · ⏱️ 05.03.2021):
	```
	conda install -c conda-forge tpot
	```
</details>
<details><summary><b><a href="https://github.com/hyperopt/hyperopt">Hyperopt</a></b> (🥈28 ·  ⭐ 5.9K) - Python中的分布式异步超参数优化。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/hyperopt/hyperopt) (👨‍💻 90 · 🔀 790 · 📦 4.9K · 📋 580 - 60% open · ⏱️ 15.09.2021):

	```
	git clone https://github.com/hyperopt/hyperopt
	```
- [PyPi](https://pypi.org/project/hyperopt) (📥 1.3M / month):
	```
	pip install hyperopt
	```
- [Conda](https://anaconda.org/conda-forge/hyperopt) (📥 270K · ⏱️ 14.10.2020):
	```
	conda install -c conda-forge hyperopt
	```
</details>
<details><summary><b><a href="https://github.com/automl/auto-sklearn">auto-sklearn</a></b> (🥈28 ·  ⭐ 5.8K) - 使用scikit-learn的自动化机器学习。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/automl/auto-sklearn) (👨‍💻 76 · 🔀 1.1K · 📦 200 · 📋 770 - 13% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/automl/auto-sklearn
	```
- [PyPi](https://pypi.org/project/auto-sklearn) (📥 26K / month):
	```
	pip install auto-sklearn
	```
</details>
<details><summary><b><a href="https://github.com/alteryx/featuretools">featuretools</a></b> (🥈27 ·  ⭐ 5.8K) - 一个用于自动化特征工程的开源python库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/alteryx/featuretools) (👨‍💻 56 · 🔀 740 · 📦 850 · 📋 670 - 20% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/alteryx/featuretools
	```
- [PyPi](https://pypi.org/project/featuretools) (📥 830K / month):
	```
	pip install featuretools
	```
- [Conda](https://anaconda.org/conda-forge/featuretools) (📥 67K · ⏱️ 21.09.2021):
	```
	conda install -c conda-forge featuretools
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/autogluon">AutoGluon</a></b> (🥈26 ·  ⭐ 3.7K) - AutoGluon：用于文本，图像和表格数据的AutoML。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/autogluon) (👨‍💻 62 · 🔀 470 · 📦 66 · 📋 530 - 20% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/awslabs/autogluon
	```
- [PyPi](https://pypi.org/project/autogluon) (📥 20K / month):
	```
	pip install autogluon
	```
</details>
<details><summary><b><a href="https://github.com/facebook/Ax">Ax</a></b> (🥈26 ·  ⭐ 1.6K) - 自适应实验平台。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebook/Ax) (👨‍💻 100 · 🔀 170 · 📦 200 · 📋 280 - 4% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/facebook/Ax
	```
- [PyPi](https://pypi.org/project/ax-platform) (📥 100K / month):
	```
	pip install ax-platform
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/botorch">BoTorch</a></b> (🥈25 ·  ⭐ 2.1K) - PyTorch中的贝叶斯优化。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/botorch) (👨‍💻 61 · 🔀 210 · 📦 160 · 📋 210 - 21% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/pytorch/botorch
	```
- [PyPi](https://pypi.org/project/botorch) (📥 120K / month):
	```
	pip install botorch
	```
</details>
<details><summary><b><a href="https://github.com/mljar/mljar-supervised">mljar-supervised</a></b> (🥈25 ·  ⭐ 1.6K) - 使用scikit-learn的自动化机器学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mljar/mljar-supervised) (👨‍💻 13 · 🔀 210 · 📦 23 · 📋 420 - 12% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/mljar/mljar-supervised
	```
- [PyPi](https://pypi.org/project/mljar-supervised) (📥 130K / month):
	```
	pip install mljar-supervised
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras-tuner">Keras Tuner</a></b> (🥈24 ·  ⭐ 2.4K) - 简单易用的超参数调整。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras-tuner) (👨‍💻 39 · 🔀 300 · 📦 890 · 📋 350 - 43% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/keras-team/keras-tuner
	```
- [PyPi](https://pypi.org/project/keras-tuner):
	```
	pip install keras-tuner
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/nevergrad">nevergrad</a></b> (🥈23 ·  ⭐ 3.2K) - 用于执行无梯度优化(gradient-free optimization)的Python工具箱。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/nevergrad) (👨‍💻 46 · 🔀 290 · 📦 240 · 📋 210 - 32% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/facebookresearch/nevergrad
	```
- [PyPi](https://pypi.org/project/nevergrad) (📥 37K / month):
	```
	pip install nevergrad
	```
- [Conda](https://anaconda.org/conda-forge/nevergrad) (📥 16K · ⏱️ 14.06.2021):
	```
	conda install -c conda-forge nevergrad
	```
</details>
<details><summary><b><a href="https://github.com/maxpumperla/hyperas">Hyperas</a></b> (🥈23 ·  ⭐ 2.1K · 💤) - Keras + Hyperopt：一个非常简单的包装，方便使用。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maxpumperla/hyperas) (👨‍💻 21 · 🔀 300 · 📦 220 · 📋 250 - 35% open · ⏱️ 22.12.2020):

	```
	git clone https://github.com/maxpumperla/hyperas
	```
- [PyPi](https://pypi.org/project/hyperas) (📥 20K / month):
	```
	pip install hyperas
	```
</details>
<details><summary><b><a href="https://github.com/SheffieldML/GPyOpt">GPyOpt</a></b> (🥈23 ·  ⭐ 760 · 💤) - 使用GPy进行高斯过程优化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/SheffieldML/GPyOpt) (👨‍💻 49 · 🔀 230 · 📦 220 · 📋 280 - 34% open · ⏱️ 05.11.2020):

	```
	git clone https://github.com/SheffieldML/GPyOpt
	```
- [PyPi](https://pypi.org/project/gpyopt) (📥 14K / month):
	```
	pip install gpyopt
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/adanet">AdaNet</a></b> (🥈22 ·  ⭐ 3.3K) - 具有学习保证的快速灵活的AutoML。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/adanet) (👨‍💻 27 · 🔀 520 · 📦 39 · 📋 110 - 58% open · ⏱️ 30.08.2021):

	```
	git clone https://github.com/tensorflow/adanet
	```
- [PyPi](https://pypi.org/project/adanet) (📥 910 / month):
	```
	pip install adanet
	```
</details>
<details><summary><b><a href="https://github.com/autonomio/talos">Talos</a></b> (🥉21 ·  ⭐ 1.4K) - TensorFlow，Keras和PyTorch的超参数优化。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/autonomio/talos) (👨‍💻 19 · 🔀 240 · 📦 130 · 📋 390 - 9% open · ⏱️ 27.05.2021):

	```
	git clone https://github.com/autonomio/talos
	```
- [PyPi](https://pypi.org/project/talos) (📥 1.4K / month):
	```
	pip install talos
	```
</details>
<details><summary><b><a href="https://github.com/AxeldeRomblay/MLBox">MLBox</a></b> (🥉21 ·  ⭐ 1.3K · 💀) - MLBox是功能强大的自动机器学习python库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/AxeldeRomblay/MLBox) (👨‍💻 9 · 🔀 260 · 📦 26 · 📋 89 - 16% open · ⏱️ 25.08.2020):

	```
	git clone https://github.com/AxeldeRomblay/MLBox
	```
- [PyPi](https://pypi.org/project/mlbox) (📥 2.1K / month):
	```
	pip install mlbox
	```
</details>
<details><summary><b><a href="https://github.com/automl/SMAC3">SMAC3</a></b> (🥉21 ·  ⭐ 620) - Sequential Model-based算法的配置。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/automl/SMAC3) (👨‍💻 38 · 🔀 160 · 📋 340 - 18% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/automl/SMAC3
	```
- [PyPi](https://pypi.org/project/smac) (📥 23K / month):
	```
	pip install smac
	```
</details>
<details><summary><b><a href="https://github.com/claesenm/optunity">optunity</a></b> (🥉21 ·  ⭐ 380 · 💀) - 超参数优化的优化例程。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/claesenm/optunity) (👨‍💻 9 · 🔀 73 · 📥 67 · 📦 66 · 📋 95 - 49% open · ⏱️ 11.05.2020):

	```
	git clone https://github.com/claesenm/optunity
	```
- [PyPi](https://pypi.org/project/optunity) (📥 15K / month):
	```
	pip install optunity
	```
</details>
<details><summary><b><a href="https://github.com/ClimbsRocks/auto_ml">auto_ml</a></b> (🥉20 ·  ⭐ 1.6K · 💀) - [UNMAINTAINED] Automated machine learning for analytics & production. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ClimbsRocks/auto_ml) (👨‍💻 13 · 🔀 300 · 📥 38 · 📋 390 - 45% open · ⏱️ 25.03.2018):

	```
	git clone https://github.com/ClimbsRocks/auto_ml
	```
- [PyPi](https://pypi.org/project/auto_ml) (📥 3K / month):
	```
	pip install auto_ml
	```
</details>
<details><summary><b><a href="https://github.com/Neuraxio/Neuraxle">Neuraxle</a></b> (🥉20 ·  ⭐ 450) - 类似于Sklearn的超参数调整和AutoML输入框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Neuraxio/Neuraxle) (👨‍💻 7 · 🔀 51 · 📦 24 · 📋 300 - 46% open · ⏱️ 26.07.2021):

	```
	git clone https://github.com/Neuraxio/Neuraxle
	```
- [PyPi](https://pypi.org/project/neuraxle) (📥 280 / month):
	```
	pip install neuraxle
	```
</details>
<details><summary><b><a href="https://github.com/Epistimio/orion">Orion</a></b> (🥉20 ·  ⭐ 200) - 异步分布式超参数优化。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Epistimio/orion) (👨‍💻 24 · 🔀 41 · 📦 44 · 📋 190 - 27% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/Epistimio/orion
	```
- [PyPi](https://pypi.org/project/orion) (📥 2.8K / month):
	```
	pip install orion
	```
</details>
<details><summary><b><a href="https://github.com/rsteca/sklearn-deap">sklearn-deap</a></b> (🥉19 ·  ⭐ 650) - 使用进化算法而非gridsearch的超参数优化。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rsteca/sklearn-deap) (👨‍💻 22 · 🔀 110 · 📦 29 · 📋 49 - 30% open · ⏱️ 30.07.2021):

	```
	git clone https://github.com/rsteca/sklearn-deap
	```
- [PyPi](https://pypi.org/project/sklearn-deap) (📥 830 / month):
	```
	pip install sklearn-deap
	```
</details>
<details><summary><b><a href="https://github.com/shankarpandala/lazypredict">lazypredict</a></b> (🥉19 ·  ⭐ 240) - Lazy Predict帮助您无需大量代码即可构建许多基本模型。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/shankarpandala/lazypredict) (👨‍💻 14 · 🔀 31 · 📦 170 · 📋 56 - 46% open · ⏱️ 13.07.2021):

	```
	git clone https://github.com/shankarpandala/lazypredict
	```
- [PyPi](https://pypi.org/project/lazypredict) (📥 5.5K / month):
	```
	pip install lazypredict
	```
</details>
<details><summary><b><a href="https://github.com/ScottfreeLLC/AlphaPy">AlphaPy</a></b> (🥉18 ·  ⭐ 640 · 💤) - 使用scikit-learn的自动化机器学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ScottfreeLLC/AlphaPy) (👨‍💻 3 · 🔀 140 · 📦 3 · 📋 38 - 23% open · ⏱️ 08.02.2021):

	```
	git clone https://github.com/ScottfreeLLC/AlphaPy
	```
- [PyPi](https://pypi.org/project/alphapy) (📥 160 / month):
	```
	pip install alphapy
	```
</details>
<details><summary><b><a href="https://github.com/williamFalcon/test-tube">Test Tube</a></b> (🥉17 ·  ⭐ 700 · 💀) - 可轻松记录实验并进行并行化的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/williamFalcon/test-tube) (👨‍💻 16 · 🔀 65 · 📥 10 · 📋 44 - 52% open · ⏱️ 17.03.2020):

	```
	git clone https://github.com/williamFalcon/test-tube
	```
- [PyPi](https://pypi.org/project/test_tube) (📥 11K / month):
	```
	pip install test_tube
	```
</details>
<details><summary><b><a href="https://github.com/sherpa-ai/sherpa">Sherpa</a></b> (🥉17 ·  ⭐ 300 · 💤) - 超参数优化库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sherpa-ai/sherpa) (👨‍💻 43 · 🔀 46 · 📦 15 · 📋 54 - 24% open · ⏱️ 18.10.2020):

	```
	git clone https://github.com/sherpa-ai/sherpa
	```
- [PyPi](https://pypi.org/project/parameter-sherpa) (📥 420 / month):
	```
	pip install parameter-sherpa
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_ViML">Auto ViML</a></b> (🥉17 ·  ⭐ 300) - 用单行代码自动构建多个ML模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/Auto_ViML) (👨‍💻 6 · 🔀 69 · 📦 15 · 📋 18 - 22% open · ⏱️ 25.07.2021):

	```
	git clone https://github.com/AutoViML/Auto_ViML
	```
- [PyPi](https://pypi.org/project/autoviml) (📥 1.8K / month):
	```
	pip install autoviml
	```
</details>
<details><summary><b><a href="https://github.com/minimaxir/automl-gs">automl-gs</a></b> (🥉16 ·  ⭐ 1.8K · 💀) - 提供输入CSV和目标字段以进行预测，自动生成可运行代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/minimaxir/automl-gs) (👨‍💻 7 · 🔀 160 · 📥 26 · 📋 29 - 79% open · ⏱️ 05.04.2019):

	```
	git clone https://github.com/minimaxir/automl-gs
	```
- [PyPi](https://pypi.org/project/automl_gs) (📥 43 / month):
	```
	pip install automl_gs
	```
</details>
<details><summary><b><a href="https://github.com/reiinakano/xcessiv">Xcessiv</a></b> (🥉16 ·  ⭐ 1.3K · 💀) - 基于Web的应用程序，高效、可扩展且自动化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/reiinakano/xcessiv) (👨‍💻 6 · 🔀 100 · 📦 1 · 📋 34 - 61% open · ⏱️ 21.08.2017):

	```
	git clone https://github.com/reiinakano/xcessiv
	```
- [PyPi](https://pypi.org/project/xcessiv) (📥 71 / month):
	```
	pip install xcessiv
	```
</details>
<details><summary><b><a href="https://github.com/HDI-Project/ATM">Auto Tune Models</a></b> (🥉16 ·  ⭐ 510 · 💀) - 自动调整模型。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HDI-Project/ATM) (👨‍💻 16 · 🔀 130 · 📦 6 · 📋 88 - 19% open · ⏱️ 21.02.2020):

	```
	git clone https://github.com/HDI-Project/ATM
	```
- [PyPi](https://pypi.org/project/atm) (📥 130 / month):
	```
	pip install atm
	```
</details>
<details><summary><b><a href="https://github.com/tobegit3hub/advisor">Advisor</a></b> (🥉15 ·  ⭐ 1.4K · 💀) - Google Vizier的超参数开源实现。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tobegit3hub/advisor) (👨‍💻 11 · 🔀 250 · 📋 32 - 59% open · ⏱️ 11.11.2019):

	```
	git clone https://github.com/tobegit3hub/advisor
	```
- [PyPi](https://pypi.org/project/advisor) (📥 71 / month):
	```
	pip install advisor
	```
- [Docker Hub](https://hub.docker.com/r/tobegit3hub/advisor) (📥 1.6K · ⏱️ 11.11.2019):
	```
	docker pull tobegit3hub/advisor
	```
</details>
<details><summary><b><a href="https://github.com/HunterMcGushion/hyperparameter_hunter">HyperparameterHunter</a></b> (🥉15 ·  ⭐ 670 · 💤) - 轻松进行超参数优化和自动结果评估。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HunterMcGushion/hyperparameter_hunter) (👨‍💻 4 · 🔀 87 · 📥 330 · 📋 120 - 27% open · ⏱️ 20.01.2021):

	```
	git clone https://github.com/HunterMcGushion/hyperparameter_hunter
	```
- [PyPi](https://pypi.org/project/hyperparameter-hunter) (📥 92 / month):
	```
	pip install hyperparameter-hunter
	```
</details>
<details><summary><b><a href="https://github.com/automl/HpBandSter">HpBandSter</a></b> (🥉15 ·  ⭐ 490 · 💀) - 分布式自动化机器学习库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/automl/HpBandSter) (👨‍💻 11 · 🔀 100 · 📦 170 · 📋 85 - 58% open · ⏱️ 26.03.2019):

	```
	git clone https://github.com/automl/HpBandSter
	```
- [PyPi](https://pypi.org/project/hpbandster):
	```
	pip install hpbandster
	```
</details>
<details><summary><b><a href="https://github.com/jmcarpenter2/parfit">Parfit</a></b> (🥉15 ·  ⭐ 200 · 💀) - 并行化拟合与评估工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jmcarpenter2/parfit) (👨‍💻 2 · 🔀 25 · 📦 9 · 📋 11 - 54% open · ⏱️ 04.04.2020):

	```
	git clone https://github.com/jmcarpenter2/parfit
	```
- [PyPi](https://pypi.org/project/parfit) (📥 16K / month):
	```
	pip install parfit
	```
</details>
<details><summary><b><a href="https://github.com/carpedm20/ENAS-pytorch">ENAS</a></b> (🥉13 ·  ⭐ 2.5K · 💀) - Efficient Neural Architecture Search的Pytorch实现。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/carpedm20/ENAS-pytorch) (👨‍💻 6 · 🔀 460 · 📋 44 - 84% open · ⏱️ 16.06.2020):

	```
	git clone https://github.com/carpedm20/ENAS-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/LGE-ARC-AdvancedAI/auptimizer">Auptimizer</a></b> (🥉13 ·  ⭐ 180 · 💤) - 自动ML模型优化工具。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/LGE-ARC-AdvancedAI/auptimizer) (👨‍💻 11 · 🔀 21 · ⏱️ 03.03.2021):

	```
	git clone https://github.com/LGE-ARC-AdvancedAI/auptimizer
	```
- [PyPi](https://pypi.org/project/auptimizer) (📥 59 / month):
	```
	pip install auptimizer
	```
</details>
<details><summary><b><a href="https://github.com/dragonfly/dragonfly">Dragonfly</a></b> (🥉12 ·  ⭐ 600 · 💀) - 一个用于自动化特征工程的开源python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dragonfly/dragonfly) (👨‍💻 12 · 🔀 83 · 📋 47 - 61% open · ⏱️ 03.07.2020):

	```
	git clone https://github.com/dragonfly/dragonfly
	```
- [PyPi](https://pypi.org/project/dragonfly-opt):
	```
	pip install dragonfly-opt
	```
</details>
<details><summary><b><a href="https://github.com/electricbrainio/hypermax">Hypermax</a></b> (🥉12 ·  ⭐ 97 · 💀) - 更好更快的超参数优化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/electricbrainio/hypermax) (👨‍💻 9 · 🔀 14 · 📦 4 · 📋 4 - 75% open · ⏱️ 02.08.2020):

	```
	git clone https://github.com/electricbrainio/hypermax
	```
- [PyPi](https://pypi.org/project/hypermax) (📥 34 / month):
	```
	pip install hypermax
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/featurewiz">featurewiz</a></b> (🥉12 ·  ⭐ 81) - 自动化特征工程并进行特征选择的工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/featurewiz) (👨‍💻 2 · 🔀 26 · 📦 3 · 📋 6 - 83% open · ⏱️ 08.07.2021):

	```
	git clone https://github.com/AutoViML/featurewiz
	```
- [PyPi](https://pypi.org/project/featurewiz) (📥 1.8K / month):
	```
	pip install featurewiz
	```
</details>
<details><summary><b><a href="https://github.com/joeddav/devol">Devol</a></b> (🥉11 ·  ⭐ 940 · 💀) - 使用Keras进行遗传神经体系结构搜索。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/joeddav/devol) (👨‍💻 18 · 🔀 110 · 📋 27 - 25% open · ⏱️ 05.07.2020):

	```
	git clone https://github.com/joeddav/devol
	```
</details>
<details><summary><b><a href="https://github.com/gdikov/hypertunity">Hypertunity</a></b> (🥉11 ·  ⭐ 120 · 💀) - 黑盒超参数优化的工具集。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gdikov/hypertunity) (👨‍💻 2 · 🔀 9 · 📦 2 · ⏱️ 26.01.2020):

	```
	git clone https://github.com/gdikov/hypertunity
	```
- [PyPi](https://pypi.org/project/hypertunity) (📥 23 / month):
	```
	pip install hypertunity
	```
</details>
<br>

## 强化学习

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于构建和评估强化学习和基于agent的系统的库。_

<details><summary><b><a href="https://github.com/openai/gym">OpenAI Gym</a></b> (🥇36 ·  ⭐ 25K) - 开发和比较强化学习的工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/openai/gym) (👨‍💻 320 · 🔀 6.8K · 📦 23K · 📋 1.4K - 6% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/openai/gym
	```
- [PyPi](https://pypi.org/project/gym) (📥 890K / month):
	```
	pip install gym
	```
</details>
<details><summary><b><a href="https://github.com/openai/baselines">baselines</a></b> (🥇25 ·  ⭐ 12K · 💀) - OpenAI基线：强化学习的高质量实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/openai/baselines) (👨‍💻 110 · 🔀 3.3K · 📦 340 · 📋 820 - 47% open · ⏱️ 31.01.2020):

	```
	git clone https://github.com/openai/baselines
	```
- [PyPi](https://pypi.org/project/baselines) (📥 1.1K / month):
	```
	pip install baselines
	```
</details>
<details><summary><b><a href="https://github.com/keras-rl/keras-rl">keras-rl</a></b> (🥇25 ·  ⭐ 5.1K · 💀) - Keras的深度强化学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-rl/keras-rl) (👨‍💻 40 · 🔀 1.3K · 📦 520 · 📋 230 - 4% open · ⏱️ 11.11.2019):

	```
	git clone https://github.com/keras-rl/keras-rl
	```
- [PyPi](https://pypi.org/project/keras-rl) (📥 1.9K / month):
	```
	pip install keras-rl
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/acme">Acme</a></b> (🥇25 ·  ⭐ 2.3K) - 强化学习组件和代理库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/acme) (👨‍💻 49 · 🔀 270 · 📦 44 · 📋 130 - 34% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/deepmind/acme
	```
- [PyPi](https://pypi.org/project/dm-acme) (📥 1.5K / month):
	```
	pip install dm-acme
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/agents">TF-Agents</a></b> (🥇25 ·  ⭐ 2.1K) - TF-Agents：可靠，可扩展且易于使用的TensorFlow的强化学习库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/agents) (👨‍💻 110 · 🔀 540 · 📦 590 · 📋 500 - 18% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/tensorflow/agents
	```
- [PyPi](https://pypi.org/project/tf-agents) (📥 20K / month):
	```
	pip install tf-agents
	```
</details>
<details><summary><b><a href="https://github.com/google/dopamine">Dopamine</a></b> (🥈24 ·  ⭐ 9.6K) - Dopamine是一个用于快速对强化学习进行原型制作的研究框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/dopamine) (👨‍💻 14 · 🔀 1.3K · 📋 140 - 42% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/google/dopamine
	```
- [PyPi](https://pypi.org/project/dopamine-rl) (📥 1.2M / month):
	```
	pip install dopamine-rl
	```
</details>
<details><summary><b><a href="https://github.com/tensorforce/tensorforce">TensorForce</a></b> (🥈23 ·  ⭐ 3K) - Tensorforce：一个基于TensorFlow的强化学习库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorforce/tensorforce) (👨‍💻 80 · 🔀 490 · 📋 610 - 1% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/tensorforce/tensorforce
	```
- [PyPi](https://pypi.org/project/tensorforce) (📥 1.4K / month):
	```
	pip install tensorforce
	```
</details>
<details><summary><b><a href="https://github.com/mwydmuch/ViZDoom">ViZDoom</a></b> (🥈23 ·  ⭐ 1.3K) - 人工智能强化学习工具库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mwydmuch/ViZDoom) (👨‍💻 45 · 🔀 300 · 📥 11K · 📦 120 · 📋 420 - 21% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/mwydmuch/ViZDoom
	```
- [PyPi](https://pypi.org/project/vizdoom) (📥 810 / month):
	```
	pip install vizdoom
	```
</details>
<details><summary><b><a href="https://github.com/chainer/chainerrl">ChainerRL</a></b> (🥈23 ·  ⭐ 1K) - ChainerRL是建立在Chainer之上的深度强化学习库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chainer/chainerrl) (👨‍💻 29 · 🔀 210 · 📦 100 · 📋 200 - 25% open · ⏱️ 17.04.2021):

	```
	git clone https://github.com/chainer/chainerrl
	```
- [PyPi](https://pypi.org/project/chainerrl) (📥 470 / month):
	```
	pip install chainerrl
	```
</details>
<details><summary><b><a href="https://github.com/hill-a/stable-baselines">Stable Baselines</a></b> (🥉22 ·  ⭐ 3.3K) - OpenAI Baselines的一个分支，强化学习的实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hill-a/stable-baselines) (👨‍💻 110 · 🔀 640 · 📋 890 - 11% open · ⏱️ 25.08.2021):

	```
	git clone https://github.com/hill-a/stable-baselines
	```
- [PyPi](https://pypi.org/project/stable-baselines) (📥 8.8K / month):
	```
	pip install stable-baselines
	```
</details>
<details><summary><b><a href="https://github.com/rlworkgroup/garage">garage</a></b> (🥉22 ·  ⭐ 1.3K) - 用于可重复的强化学习研究的工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rlworkgroup/garage) (👨‍💻 77 · 🔀 230 · 📦 19 · 📋 980 - 18% open · ⏱️ 22.06.2021):

	```
	git clone https://github.com/rlworkgroup/garage
	```
- [PyPi](https://pypi.org/project/garage) (📥 480 / month):
	```
	pip install garage
	```
</details>
<details><summary><b><a href="https://github.com/tensorlayer/tensorlayer">TensorLayer</a></b> (🥉21 ·  ⭐ 6.7K) - 深度学习和强化学习库。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorlayer/tensorlayer) (👨‍💻 130 · 🔀 1.5K · 📥 1.3K · 📋 450 - 4% open · ⏱️ 23.09.2021):

	```
	git clone https://github.com/tensorlayer/tensorlayer
	```
- [PyPi](https://pypi.org/project/tensorlayer) (📥 2.2K / month):
	```
	pip install tensorlayer
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PARL">PARL</a></b> (🥉21 ·  ⭐ 2.2K) - 强化学习高性能分布式训练框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PARL) (👨‍💻 27 · 🔀 560 · 📦 78 · 📋 250 - 18% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/PaddlePaddle/PARL
	```
- [PyPi](https://pypi.org/project/parl) (📥 840 / month):
	```
	pip install parl
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/trfl">TRFL</a></b> (🥉20 ·  ⭐ 3.1K) - TensorFlow强化学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/trfl) (👨‍💻 13 · 🔀 370 · 📦 62 · 📋 20 - 20% open · ⏱️ 16.08.2021):

	```
	git clone https://github.com/deepmind/trfl
	```
- [PyPi](https://pypi.org/project/trfl) (📥 1.9K / month):
	```
	pip install trfl
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/coach">Coach</a></b> (🥉20 ·  ⭐ 2.1K) - 英特尔AI实验室的强化学习训练器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IntelLabs/coach) (👨‍💻 35 · 🔀 400 · 📋 260 - 29% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/IntelLabs/coach
	```
- [PyPi](https://pypi.org/project/rl_coach) (📥 300 / month):
	```
	pip install rl_coach
	```
</details>
<details><summary><b><a href="https://github.com/pfnet/pfrl">PFRL</a></b> (🥉20 ·  ⭐ 710) - PFRL：基于PyTorch的深度强化学习库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pfnet/pfrl) (👨‍💻 15 · 🔀 93 · 📦 24 · 📋 54 - 40% open · ⏱️ 07.09.2021):

	```
	git clone https://github.com/pfnet/pfrl
	```
- [PyPi](https://pypi.org/project/pfrl) (📥 880 / month):
	```
	pip install pfrl
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/rlax">RLax</a></b> (🥉19 ·  ⭐ 680) - 强化学习组件和代理库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>jax</code></summary>

- [GitHub](https://github.com/deepmind/rlax) (👨‍💻 15 · 🔀 53 · 📦 25 · 📋 11 - 36% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/deepmind/rlax
	```
- [PyPi](https://pypi.org/project/rlax) (📥 1.8K / month):
	```
	pip install rlax
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ReAgent">ReAgent</a></b> (🥉17 ·  ⭐ 3K) - 推理系统平台。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ReAgent) (👨‍💻 120 · 🔀 420 · 📋 97 - 22% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/facebookresearch/ReAgent
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/lab">DeepMind Lab</a></b> (🥉16 ·  ⭐ 6.5K · 📈) - 可定制的3D平台，用于agent-based AI研究。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/deepmind/lab) (👨‍💻 7 · 🔀 1.3K · 📋 200 - 22% open · ⏱️ 21.07.2021):

	```
	git clone https://github.com/deepmind/lab
	```
</details>
<br>

## 推荐系统

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于建立和评估推荐系统的库。_

<details><summary><b><a href="https://github.com/NicolasHug/Surprise">scikit-surprise</a></b> (🥇26 ·  ⭐ 5K · 💀) - 用于构建和分析推荐算法的Python scikit工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/NicolasHug/Surprise) (👨‍💻 38 · 🔀 880 · 📦 1.3K · 📋 330 - 12% open · ⏱️ 05.08.2020):

	```
	git clone https://github.com/NicolasHug/Surprise
	```
- [PyPi](https://pypi.org/project/scikit-surprise) (📥 71K / month):
	```
	pip install scikit-surprise
	```
- [Conda](https://anaconda.org/conda-forge/scikit-surprise) (📥 200K · ⏱️ 13.10.2020):
	```
	conda install -c conda-forge scikit-surprise
	```
</details>
<details><summary><b><a href="https://github.com/lyst/lightfm">lightfm</a></b> (🥇25 ·  ⭐ 3.8K · 💤) - 全局优化的Python实现。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lyst/lightfm) (👨‍💻 44 · 🔀 600 · 📦 560 · 📋 430 - 19% open · ⏱️ 07.02.2021):

	```
	git clone https://github.com/lyst/lightfm
	```
- [PyPi](https://pypi.org/project/lightfm) (📥 190K / month):
	```
	pip install lightfm
	```
- [Conda](https://anaconda.org/conda-forge/lightfm) (📥 110K · ⏱️ 07.02.2021):
	```
	conda install -c conda-forge lightfm
	```
</details>
<details><summary><b><a href="https://github.com/benfred/implicit">implicit</a></b> (🥈24 ·  ⭐ 2.5K) - 隐式反馈数据集的快速Python协同过滤。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/implicit) (👨‍💻 30 · 🔀 500 · 📦 480 · 📋 360 - 22% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/benfred/implicit
	```
- [PyPi](https://pypi.org/project/implicit) (📥 130K / month):
	```
	pip install implicit
	```
- [Conda](https://anaconda.org/conda-forge/implicit) (📥 300K · ⏱️ 29.08.2021):
	```
	conda install -c conda-forge implicit
	```
</details>
<details><summary><b><a href="https://github.com/PreferredAI/cornac">Cornac</a></b> (🥈24 ·  ⭐ 440) - 多模态推荐系统的比较框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PreferredAI/cornac) (👨‍💻 13 · 🔀 76 · 📦 62 · 📋 63 - 1% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/PreferredAI/cornac
	```
- [PyPi](https://pypi.org/project/cornac) (📥 7.2K / month):
	```
	pip install cornac
	```
- [Conda](https://anaconda.org/conda-forge/cornac) (📥 180K · ⏱️ 26.09.2021):
	```
	conda install -c conda-forge cornac
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/recommenders">TF Recommenders</a></b> (🥈23 ·  ⭐ 1K) - TensorFlow Recommenders是一个用于构建推荐系统的工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/recommenders) (👨‍💻 28 · 🔀 140 · 📦 43 · 📋 190 - 53% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/tensorflow/recommenders
	```
- [PyPi](https://pypi.org/project/tensorflow-recommenders) (📥 120K / month):
	```
	pip install tensorflow-recommenders
	```
</details>
<details><summary><b><a href="https://github.com/RUCAIBox/RecBole">RecBole</a></b> (🥉22 ·  ⭐ 1.3K) - 统一，全面，高效的推荐库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/RUCAIBox/RecBole) (👨‍💻 40 · 🔀 210 · 📋 190 - 19% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/RUCAIBox/RecBole
	```
- [PyPi](https://pypi.org/project/recbole) (📥 670 / month):
	```
	pip install recbole
	```
- [Conda](https://anaconda.org/aibox/recbole) (📥 710 · ⏱️ 16.09.2021):
	```
	conda install -c aibox recbole
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/ranking">TF Ranking</a></b> (🥉21 ·  ⭐ 2.3K) - 在TensorFlow中学习推荐排序。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/ranking) (👨‍💻 20 · 🔀 390 · 📋 260 - 12% open · ⏱️ 22.07.2021):

	```
	git clone https://github.com/tensorflow/ranking
	```
- [PyPi](https://pypi.org/project/tensorflow_ranking) (📥 34K / month):
	```
	pip install tensorflow_ranking
	```
</details>
<details><summary><b><a href="https://github.com/jfkirk/tensorrec">tensorrec</a></b> (🥉19 ·  ⭐ 1.2K · 💀) - TensorFlow推荐算法和框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jfkirk/tensorrec) (👨‍💻 9 · 🔀 220 · 📦 26 · 📋 120 - 28% open · ⏱️ 04.02.2020):

	```
	git clone https://github.com/jfkirk/tensorrec
	```
- [PyPi](https://pypi.org/project/tensorrec) (📥 940 / month):
	```
	pip install tensorrec
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/recommenders">Recommenders</a></b> (🥉18 ·  ⭐ 11K) - 推荐系统最佳实践。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/recommenders) (👨‍💻 100 · 🔀 1.9K · 📥 58 · 📦 1 · 📋 620 - 23% open · ⏱️ 23.09.2021):

	```
	git clone https://github.com/microsoft/recommenders
	```
</details>
<details><summary><b><a href="https://github.com/ibayer/fastFM">fastFM</a></b> (🥉18 ·  ⭐ 940 · 💤) - fastFM：用于分解机的工具库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ibayer/fastFM) (👨‍💻 20 · 🔀 190 · 📥 400 · 📦 88 · 📋 110 - 43% open · ⏱️ 24.03.2021):

	```
	git clone https://github.com/ibayer/fastFM
	```
- [PyPi](https://pypi.org/project/fastfm) (📥 630 / month):
	```
	pip install fastfm
	```
</details>
<details><summary><b><a href="https://github.com/maciejkula/spotlight">Spotlight</a></b> (🥉17 ·  ⭐ 2.6K · 💀) - 使用PyTorch的深度推荐系统模型实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maciejkula/spotlight) (👨‍💻 11 · 🔀 390 · 📋 110 - 55% open · ⏱️ 09.02.2020):

	```
	git clone https://github.com/maciejkula/spotlight
	```
- [Conda](https://anaconda.org/maciejkula/spotlight) (📥 6.5K · ⏱️ 27.05.2018):
	```
	conda install -c maciejkula spotlight
	```
</details>
<details><summary><b><a href="https://github.com/statisticianinstilettos/recmetrics">recmetrics</a></b> (🥉17 ·  ⭐ 300) - 用于评估推荐系统的度量标准库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/statisticianinstilettos/recmetrics) (👨‍💻 12 · 🔀 69 · 📦 20 · 📋 14 - 35% open · ⏱️ 23.09.2021):

	```
	git clone https://github.com/statisticianinstilettos/recmetrics
	```
- [PyPi](https://pypi.org/project/recmetrics) (📥 650 / month):
	```
	pip install recmetrics
	```
</details>
<details><summary><b><a href="https://github.com/caserec/CaseRecommender">Case Recommender</a></b> (🥉16 ·  ⭐ 360) - Case Recommender：灵活且可扩展的Python推荐系统工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/caserec/CaseRecommender) (👨‍💻 11 · 🔀 76 · 📦 9 · 📋 24 - 29% open · ⏱️ 17.06.2021):

	```
	git clone https://github.com/caserec/CaseRecommender
	```
- [PyPi](https://pypi.org/project/caserecommender) (📥 360 / month):
	```
	pip install caserecommender
	```
</details>
<br>

## 隐私机器学习

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_使用联合学习和差异隐私之类的方法进行加密和保留隐私的机器学习的库。_

<details><summary><b><a href="https://github.com/OpenMined/PySyft">PySyft</a></b> (🥇26 ·  ⭐ 7.6K) - 基于内部数据自动化回答问题的工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/OpenMined/PySyft) (👨‍💻 420 · 🔀 1.7K · 📋 3K - 9% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/OpenMined/PySyft
	```
- [PyPi](https://pypi.org/project/syft) (📥 3.1K / month):
	```
	pip install syft
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/privacy">TensorFlow Privacy</a></b> (🥈23 ·  ⭐ 1.5K) - 用于训练机器学习模型的库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/privacy) (👨‍💻 43 · 🔀 310 · 📥 51 · 📋 140 - 40% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/tensorflow/privacy
	```
- [PyPi](https://pypi.org/project/tensorflow-privacy) (📥 17K / month):
	```
	pip install tensorflow-privacy
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/opacus">Opacus</a></b> (🥈22 ·  ⭐ 910) - 使用不同的隐私训练PyTorch模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/opacus) (👨‍💻 33 · 🔀 140 · 📥 40 · 📦 53 · 📋 92 - 11% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/pytorch/opacus
	```
- [PyPi](https://pypi.org/project/opacus) (📥 27K / month):
	```
	pip install opacus
	```
</details>
<details><summary><b><a href="https://github.com/FederatedAI/FATE">FATE</a></b> (🥉20 ·  ⭐ 3.5K) - 工业级联邦学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/FederatedAI/FATE) (👨‍💻 62 · 🔀 1K · 📋 950 - 34% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/FederatedAI/FATE
	```
</details>
<details><summary><b><a href="https://github.com/tf-encrypted/tf-encrypted">TFEncrypted</a></b> (🥉19 ·  ⭐ 940 · 💀) - TensorFlow中的加密机器学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tf-encrypted/tf-encrypted) (👨‍💻 28 · 🔀 170 · 📦 57 · 📋 410 - 42% open · ⏱️ 19.08.2020):

	```
	git clone https://github.com/tf-encrypted/tf-encrypted
	```
- [PyPi](https://pypi.org/project/tf-encrypted) (📥 720 / month):
	```
	pip install tf-encrypted
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/CrypTen">CrypTen</a></b> (🥉16 ·  ⭐ 920) - 隐私保护的机器学习框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/CrypTen) (👨‍💻 25 · 🔀 140 · 📦 11 · 📋 97 - 17% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/facebookresearch/CrypTen
	```
- [PyPi](https://pypi.org/project/crypten) (📥 830 / month):
	```
	pip install crypten
	```
</details>
<br>

## 工作流程和实验跟踪

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_图书馆组织，跟踪和可视化机器学习实验。_

<details><summary><b><a href="https://github.com/tensorflow/tensorboard">Tensorboard</a></b> (🥇37 ·  ⭐ 5.7K) - TensorFlow的可视化工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensorboard) (👨‍💻 270 · 🔀 1.4K · 📦 81K · 📋 1.6K - 33% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/tensorflow/tensorboard
	```
- [PyPi](https://pypi.org/project/tensorboard) (📥 11M / month):
	```
	pip install tensorboard
	```
- [Conda](https://anaconda.org/conda-forge/tensorboard) (📥 2.5M · ⏱️ 23.08.2021):
	```
	conda install -c conda-forge tensorboard
	```
</details>
<details><summary><b><a href="https://github.com/aws/sagemaker-python-sdk">SageMaker SDK</a></b> (🥇32 ·  ⭐ 1.5K) - 一个用于训练和部署机器学习的库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/aws/sagemaker-python-sdk) (👨‍💻 220 · 🔀 670 · 📦 880 · 📋 900 - 29% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/aws/sagemaker-python-sdk
	```
- [PyPi](https://pypi.org/project/sagemaker) (📥 1.4M / month):
	```
	pip install sagemaker
	```
</details>
<details><summary><b><a href="https://github.com/mlflow/mlflow">mlflow</a></b> (🥇30 ·  ⭐ 10K) - 机器学习生命周期的开源平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mlflow/mlflow) (👨‍💻 320 · 🔀 2.2K · 📋 1.9K - 39% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/mlflow/mlflow
	```
- [PyPi](https://pypi.org/project/mlflow) (📥 18M / month):
	```
	pip install mlflow
	```
- [Conda](https://anaconda.org/conda-forge/mlflow) (📥 410K · ⏱️ 27.09.2021):
	```
	conda install -c conda-forge mlflow
	```
</details>
<details><summary><b><a href="https://github.com/lanpa/tensorboardX">tensorboardX</a></b> (🥇30 ·  ⭐ 7.1K) - pytorch（和链接器，mxnet，numpy，...）的张量板。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lanpa/tensorboardX) (👨‍💻 67 · 🔀 820 · 📥 340 · 📦 15K · 📋 420 - 14% open · ⏱️ 12.09.2021):

	```
	git clone https://github.com/lanpa/tensorboardX
	```
- [PyPi](https://pypi.org/project/tensorboardX) (📥 790K / month):
	```
	pip install tensorboardX
	```
- [Conda](https://anaconda.org/conda-forge/tensorboardx) (📥 530K · ⏱️ 10.08.2021):
	```
	conda install -c conda-forge tensorboardx
	```
</details>
<details><summary><b><a href="https://github.com/pycaret/pycaret">PyCaret</a></b> (🥇30 ·  ⭐ 4.1K) - Python中的开源代码，低代码机器学习库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pycaret/pycaret) (👨‍💻 62 · 🔀 930 · 📥 460 · 📦 1.4K · 📋 1.1K - 15% open · ⏱️ 09.10.2021):

	```
	git clone https://github.com/pycaret/pycaret
	```
- [PyPi](https://pypi.org/project/pycaret) (📥 200K / month):
	```
	pip install pycaret
	```
</details>
<details><summary><b><a href="https://github.com/IDSIA/sacred">sacred</a></b> (🥈28 ·  ⭐ 3.6K) - Sacred是可帮助您配置，组织，记录和复现的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IDSIA/sacred) (👨‍💻 94 · 🔀 320 · 📦 1.1K · 📋 520 - 17% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/IDSIA/sacred
	```
- [PyPi](https://pypi.org/project/sacred) (📥 23K / month):
	```
	pip install sacred
	```
</details>
<details><summary><b><a href="https://github.com/iterative/dvc">DVC</a></b> (🥈27 ·  ⭐ 8.7K · 📉) - 数据版本控制|针对数据和模型的Git。<code>|) - 数据版本控制|针对数据和模型的Git。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/iterative/dvc) (👨‍💻 240 · 🔀 820 · 📥 39K · 📋 3.3K - 15% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/iterative/dvc
	```
- [PyPi](https://pypi.org/project/dvc) (📥 310K / month):
	```
	pip install dvc
	```
- [Conda](https://anaconda.org/conda-forge/dvc) (📥 890K · ⏱️ 13.10.2021):
	```
	conda install -c conda-forge dvc
	```
</details>
<details><summary><b><a href="https://github.com/Netflix/metaflow">Metaflow</a></b> (🥈27 ·  ⭐ 4.7K) - 轻松构建和管理现实生活中的数据科学项目。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Netflix/metaflow) (👨‍💻 41 · 🔀 400 · 📦 210 · 📋 320 - 44% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/Netflix/metaflow
	```
- [PyPi](https://pypi.org/project/metaflow) (📥 20K / month):
	```
	pip install metaflow
	```
- [Conda](https://anaconda.org/conda-forge/metaflow) (📥 25K · ⏱️ 05.10.2021):
	```
	conda install -c conda-forge metaflow
	```
</details>
<details><summary><b><a href="https://github.com/Kaggle/kaggle-api">kaggle</a></b> (🥈27 ·  ⭐ 4.4K · 💤) - 官方Kaggle API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Kaggle/kaggle-api) (👨‍💻 36 · 🔀 850 · 📦 6.7K · 📋 310 - 55% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/Kaggle/kaggle-api
	```
- [PyPi](https://pypi.org/project/kaggle) (📥 280K / month):
	```
	pip install kaggle
	```
- [Conda](https://anaconda.org/conda-forge/kaggle) (📥 71K · ⏱️ 16.03.2021):
	```
	conda install -c conda-forge kaggle
	```
</details>
<details><summary><b><a href="https://github.com/allegroai/clearml">ClearML</a></b> (🥈27 ·  ⭐ 2.7K) - ClearML-自动精简工具套件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/allegroai/clearml) (👨‍💻 39 · 🔀 370 · 📥 370 · 📦 120 · 📋 390 - 31% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/allegroai/clearml
	```
- [PyPi](https://pypi.org/project/clearml) (📥 38K / month):
	```
	pip install clearml
	```
- [Docker Hub](https://hub.docker.com/r/allegroai/trains) (📥 30K · ⏱️ 05.10.2020):
	```
	docker pull allegroai/trains
	```
</details>
<details><summary><b><a href="https://github.com/catalyst-team/catalyst">Catalyst</a></b> (🥈27 ·  ⭐ 2.7K) - 加快深度学习研发。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/catalyst-team/catalyst) (👨‍💻 100 · 🔀 340 · 📦 420 · 📋 320 - 3% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/catalyst-team/catalyst
	```
- [PyPi](https://pypi.org/project/catalyst) (📥 12K / month):
	```
	pip install catalyst
	```
</details>
<details><summary><b><a href="https://github.com/snakemake/snakemake">snakemake</a></b> (🥈27 ·  ⭐ 1.1K) - 工作流管理系统snakemake。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snakemake/snakemake) (👨‍💻 220 · 🔀 260 · 📦 930 · 📋 740 - 62% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/snakemake/snakemake
	```
- [PyPi](https://pypi.org/project/snakemake) (📥 22K / month):
	```
	pip install snakemake
	```
- [Conda](https://anaconda.org/bioconda/snakemake) (📥 340K · ⏱️ 30.09.2021):
	```
	conda install -c bioconda snakemake
	```
</details>
<details><summary><b><a href="https://github.com/wandb/client">wandb client</a></b> (🥈26 ·  ⭐ 3.4K) - 用于可视化和跟踪机器学习的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wandb/client) (👨‍💻 93 · 🔀 260 · 📋 1.3K - 25% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/wandb/client
	```
- [PyPi](https://pypi.org/project/wandb) (📥 470K / month):
	```
	pip install wandb
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/VisualDL">VisualDL</a></b> (🥈25 ·  ⭐ 4.2K) - 深度学习可视化工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/VisualDL) (👨‍💻 31 · 🔀 570 · 📥 150 · 📦 700 · 📋 380 - 13% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/PaddlePaddle/VisualDL
	```
- [PyPi](https://pypi.org/project/visualdl) (📥 24K / month):
	```
	pip install visualdl
	```
</details>
<details><summary><b><a href="https://github.com/Azure/MachineLearningNotebooks">AzureML SDK</a></b> (🥈25 ·  ⭐ 2.7K) - 带有ML的Python笔记本和带有Azure的深度学习示例。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Azure/MachineLearningNotebooks) (👨‍💻 57 · 🔀 1.9K · 📥 430 · 📋 1.2K - 14% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/Azure/MachineLearningNotebooks
	```
- [PyPi](https://pypi.org/project/azureml-sdk) (📥 1.3M / month):
	```
	pip install azureml-sdk
	```
</details>
<details><summary><b><a href="https://github.com/google/ml-metadata">ml-metadata</a></b> (🥈25 ·  ⭐ 390) - 用于记录和检索与ML相关的元数据。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/ml-metadata) (👨‍💻 13 · 🔀 67 · 📥 1.5K · 📦 150 · 📋 70 - 24% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/google/ml-metadata
	```
- [PyPi](https://pypi.org/project/ml-metadata) (📥 880K / month):
	```
	pip install ml-metadata
	```
</details>
<details><summary><b><a href="https://github.com/stared/livelossplot">livelossplot</a></b> (🥉23 ·  ⭐ 1.1K) - Jupyter Notebook for Keras的实时训练loss图。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/stared/livelossplot) (👨‍💻 17 · 🔀 140 · 📦 650 · 📋 73 - 4% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/stared/livelossplot
	```
- [PyPi](https://pypi.org/project/livelossplot) (📥 76K / month):
	```
	pip install livelossplot
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/knockknock">knockknock</a></b> (🥉22 ·  ⭐ 2.2K · 💀) - 当您的训练结束后通知您。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/huggingface/knockknock) (👨‍💻 18 · 🔀 190 · 📦 210 · 📋 37 - 37% open · ⏱️ 16.03.2020):

	```
	git clone https://github.com/huggingface/knockknock
	```
- [PyPi](https://pypi.org/project/knockknock) (📥 1K / month):
	```
	pip install knockknock
	```
- [Conda](https://anaconda.org/conda-forge/knockknock) (📥 7.9K · ⏱️ 17.03.2020):
	```
	conda install -c conda-forge knockknock
	```
</details>
<details><summary><b><a href="https://github.com/labmlai/labml">Labml</a></b> (🥉21 ·  ⭐ 760) - 从您的手机监控深度学习模型训练和硬件使用情况。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/labmlai/labml) (🔀 52 · 📦 35 · 📋 24 - 62% open · ⏱️ 06.09.2021):

	```
	git clone https://github.com/lab-ml/labml
	```
- [PyPi](https://pypi.org/project/labml) (📥 800 / month):
	```
	pip install labml
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/tnt">TNT</a></b> (🥉20 ·  ⭐ 1.3K · 💤) - 用于记录和可视化，加载和训练的简单工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/tnt) (👨‍💻 35 · 🔀 190 · 📋 58 - 39% open · ⏱️ 05.01.2021):

	```
	git clone https://github.com/pytorch/tnt
	```
- [PyPi](https://pypi.org/project/torchnet) (📥 13K / month):
	```
	pip install torchnet
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/tensorwatch">TensorWatch</a></b> (🥉19 ·  ⭐ 3.2K · 💤) - Python机器学习的调试，监视和可视化。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/tensorwatch) (👨‍💻 13 · 🔀 340 · 📦 60 · 📋 65 - 76% open · ⏱️ 15.01.2021):

	```
	git clone https://github.com/microsoft/tensorwatch
	```
- [PyPi](https://pypi.org/project/tensorwatch) (📥 3.6K / month):
	```
	pip install tensorwatch
	```
</details>
<details><summary><b><a href="https://github.com/instacart/lore">lore</a></b> (🥉19 ·  ⭐ 1.5K · 💀) - lore使机器学习对软件工程师更易上手，对机器学习研究人员更可维护。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/instacart/lore) (👨‍💻 22 · 🔀 120 · 📦 16 · 📋 34 - 47% open · ⏱️ 11.05.2020):

	```
	git clone https://github.com/instacart/lore
	```
- [PyPi](https://pypi.org/project/lore) (📥 1.1K / month):
	```
	pip install lore
	```
</details>
<details><summary><b><a href="https://github.com/waleedka/hiddenlayer">hiddenlayer</a></b> (🥉19 ·  ⭐ 1.5K · 💀) - 神经网络图和训练指标。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/waleedka/hiddenlayer) (👨‍💻 6 · 🔀 220 · 📦 84 · 📋 80 - 57% open · ⏱️ 24.04.2020):

	```
	git clone https://github.com/waleedka/hiddenlayer
	```
- [PyPi](https://pypi.org/project/hiddenlayer) (📥 2.8K / month):
	```
	pip install hiddenlayer
	```
</details>
<details><summary><b><a href="https://github.com/guildai/guildai">Guild AI</a></b> (🥉19 ·  ⭐ 630) - 实验跟踪，ML开发人员工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/guildai/guildai) (👨‍💻 18 · 🔀 46 · 📦 38 · 📋 280 - 39% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/guildai/guildai
	```
- [PyPi](https://pypi.org/project/guildai) (📥 5.3K / month):
	```
	pip install guildai
	```
</details>
<details><summary><b><a href="https://github.com/m3dev/gokart">gokart</a></b> (🥉19 ·  ⭐ 220) - 数据管道库luigi的包装。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/m3dev/gokart) (👨‍💻 28 · 🔀 36 · 📋 59 - 22% open · ⏱️ 17.09.2021):

	```
	git clone https://github.com/m3dev/gokart
	```
- [PyPi](https://pypi.org/project/gokart) (📥 620 / month):
	```
	pip install gokart
	```
</details>
<details><summary><b><a href="https://github.com/studioml/studio">Studio.ml</a></b> (🥉18 ·  ⭐ 370) - Studio：简化和加快模型构建过程。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/studioml/studio) (👨‍💻 21 · 🔀 51 · 📦 5 · 📋 250 - 22% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/studioml/studio
	```
- [PyPi](https://pypi.org/project/studioml):
	```
	pip install studioml
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/mxboard">MXBoard</a></b> (🥉18 ·  ⭐ 330 · 💀) - MXNet日志记录器，以在TensorBoard中进行可视化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/mxboard) (👨‍💻 9 · 🔀 45 · 📦 120 · 📋 31 - 51% open · ⏱️ 24.01.2020):

	```
	git clone https://github.com/awslabs/mxboard
	```
- [PyPi](https://pypi.org/project/mxboard) (📥 2K / month):
	```
	pip install mxboard
	```
</details>
<details><summary><b><a href="https://github.com/aimhubio/aim">aim</a></b> (🥉17 ·  ⭐ 1.4K) - 以一种非常简单的方式来记录，搜索和比较数千次ML训练。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aimhubio/aim) (👨‍💻 20 · 🔀 84 · 📦 37 · 📋 190 - 51% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/aimhubio/aim
	```
- [PyPi](https://pypi.org/project/aim) (📥 4.9K / month):
	```
	pip install aim
	```
</details>
<details><summary><b><a href="https://github.com/TeamHG-Memex/tensorboard_logger">TensorBoard Logger</a></b> (🥉15 ·  ⭐ 610 · 💀) - 简易TensorBoard日志记录库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/TeamHG-Memex/tensorboard_logger) (👨‍💻 5 · 🔀 50 · 📋 23 - 34% open · ⏱️ 21.10.2019):

	```
	git clone https://github.com/TeamHG-Memex/tensorboard_logger
	```
- [PyPi](https://pypi.org/project/tensorboard_logger) (📥 51K / month):
	```
	pip install tensorboard_logger
	```
</details>
<details><summary><b><a href="https://github.com/MrPowers/quinn">quinn</a></b> (🥉15 ·  ⭐ 280 · 💤) - pyspark方法可提高开发人员的工作效率。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MrPowers/quinn) (👨‍💻 6 · 🔀 33 · 📋 23 - 60% open · ⏱️ 09.02.2021):

	```
	git clone https://github.com/MrPowers/quinn
	```
- [PyPi](https://pypi.org/project/quinn) (📥 400K / month):
	```
	pip install quinn
	```
</details>
<details><summary><b><a href="https://github.com/minerva-ml/steppy">steppy</a></b> (🥉15 ·  ⭐ 130 · 💀) - 轻量级的Python库，可进行快速且可重复的实验。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/minerva-ml/steppy) (👨‍💻 5 · 🔀 33 · 📦 40 · 📋 63 - 20% open · ⏱️ 23.11.2018):

	```
	git clone https://github.com/minerva-ml/steppy
	```
- [PyPi](https://pypi.org/project/steppy) (📥 63 / month):
	```
	pip install steppy
	```
</details>
<details><summary><b><a href="https://github.com/EducationalTestingService/skll">SKLL</a></b> (🥉14 ·  ⭐ 520) - SciKit学习实验室（SKLL）使机器学习易于操作。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/EducationalTestingService/skll) (👨‍💻 35 · 🔀 62 · 📥 11 · 📦 31 · 📋 390 - 10% open · ⏱️ 30.04.2021):

	```
	git clone https://github.com/EducationalTestingService/skll
	```
- [PyPi](https://pypi.org/project/skll) (📥 490 / month):
	```
	pip install skll
	```
</details>
<details><summary><b><a href="https://github.com/datmo/datmo">datmo</a></b> (🥉14 ·  ⭐ 340 · 💀) - 面向数据科学家的开源生产模型管理工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/datmo/datmo) (👨‍💻 6 · 🔀 27 · 📦 5 · 📋 180 - 15% open · ⏱️ 29.11.2019):

	```
	git clone https://github.com/datmo/datmo
	```
- [PyPi](https://pypi.org/project/datmo) (📥 130 / month):
	```
	pip install datmo
	```
</details>
<details><summary><b><a href="https://github.com/ModelChimp/modelchimp">ModelChimp</a></b> (🥉14 ·  ⭐ 120) - 机器和深度学习项目的实验跟踪。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ModelChimp/modelchimp) (👨‍💻 3 · 🔀 12 · 📋 14 - 28% open · ⏱️ 01.08.2021):

	```
	git clone https://github.com/ModelChimp/modelchimp
	```
- [PyPi](https://pypi.org/project/modelchimp) (📥 83 / month):
	```
	pip install modelchimp
	```
- [Docker Hub](https://hub.docker.com/r/modelchimp/modelchimp-server) (📥 640 · ⏱️ 09.04.2019):
	```
	docker pull modelchimp/modelchimp-server
	```
</details>
<details><summary><b><a href="https://github.com/jrieke/traintool">traintool</a></b> (🥉7 ·  ⭐ 9 · 💤) - 一站式训练现成的机器学习模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jrieke/traintool) (🔀 1 · ⏱️ 12.03.2021):

	```
	git clone https://github.com/jrieke/traintool
	```
- [PyPi](https://pypi.org/project/traintool) (📥 17 / month):
	```
	pip install traintool
	```
</details>
<br>

## 模型序列化和转换

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于将模型序列化为文件，在各种模型格式之间进行转换以及优化模型以进行部署的库。_

<details><summary><b><a href="https://github.com/onnx/onnx">onnx</a></b> (🥇35 ·  ⭐ 11K) - 机器学习互操作性的开放标准。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/onnx/onnx) (👨‍💻 210 · 🔀 2.1K · 📥 17K · 📦 4.3K · 📋 1.6K - 25% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/onnx/onnx
	```
- [PyPi](https://pypi.org/project/onnx) (📥 1.5M / month):
	```
	pip install onnx
	```
- [Conda](https://anaconda.org/conda-forge/onnx) (📥 290K · ⏱️ 26.09.2021):
	```
	conda install -c conda-forge onnx
	```
</details>
<details><summary><b><a href="https://github.com/apple/coremltools">Core ML Tools</a></b> (🥇24 ·  ⭐ 2.4K) - 核心ML工具包含用于核心ML模型的支持工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/apple/coremltools) (👨‍💻 120 · 🔀 360 · 📥 3.5K · 📦 640 · 📋 790 - 43% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/apple/coremltools
	```
- [PyPi](https://pypi.org/project/coremltools) (📥 53K / month):
	```
	pip install coremltools
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/serve">TorchServe</a></b> (🥇24 ·  ⭐ 2.1K) - 在PyTorch上进行模型服务。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/serve) (👨‍💻 81 · 🔀 380 · 📥 660 · 📋 690 - 14% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/pytorch/serve
	```
- [PyPi](https://pypi.org/project/torchserve) (📥 11K / month):
	```
	pip install torchserve
	```
- [Conda](https://anaconda.org/pytorch/torchserve) (📥 14K · ⏱️ 02.08.2021):
	```
	conda install -c pytorch torchserve
	```
- [Docker Hub](https://hub.docker.com/r/pytorch/torchserve) (📥 930K · ⭐ 8 · ⏱️ 02.08.2021):
	```
	docker pull pytorch/torchserve
	```
</details>
<details><summary><b><a href="https://github.com/cortexlabs/cortex">cortex</a></b> (🥈23 ·  ⭐ 7.6K) - 具有成本效益的无服务器大规模计算。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cortexlabs/cortex) (👨‍💻 22 · 🔀 570 · 📋 1.1K - 9% open · ⏱️ 05.08.2021):

	```
	git clone https://github.com/cortexlabs/cortex
	```
- [PyPi](https://pypi.org/project/cortex) (📥 1.9K / month):
	```
	pip install cortex
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/MMdnn">mmdnn</a></b> (🥈22 ·  ⭐ 5.4K · 💀) - MMdnn是一组工具，可以帮助用户在不同的深度学习框架之间进行互操作。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/MMdnn) (👨‍💻 85 · 🔀 940 · 📥 3.5K · 📦 66 · 📋 600 - 52% open · ⏱️ 14.08.2020):

	```
	git clone https://github.com/Microsoft/MMdnn
	```
- [PyPi](https://pypi.org/project/mmdnn) (📥 440 / month):
	```
	pip install mmdnn
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/hummingbird">Hummingbird</a></b> (🥈22 ·  ⭐ 2.6K) - 蜂鸟将训练有素的机器学习模型编译为张量计算，以用于..<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/hummingbird) (👨‍💻 25 · 🔀 200 · 📥 140 · 📦 19 · 📋 220 - 21% open · ⏱️ 27.09.2021):

	```
	git clone https://github.com/microsoft/hummingbird
	```
- [PyPi](https://pypi.org/project/hummingbird-ml) (📥 3.9K / month):
	```
	pip install hummingbird-ml
	```
</details>
<details><summary><b><a href="https://github.com/BayesWitnesses/m2cgen">m2cgen</a></b> (🥈22 ·  ⭐ 1.9K) - 将ML模型转换成本机代码（Java，C，Python，Go，JavaScript）等。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/BayesWitnesses/m2cgen) (👨‍💻 12 · 🔀 160 · 📦 6 · 📋 79 - 40% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/BayesWitnesses/m2cgen
	```
- [PyPi](https://pypi.org/project/m2cgen) (📥 45K / month):
	```
	pip install m2cgen
	```
</details>
<details><summary><b><a href="https://github.com/gmalivenko/pytorch2keras">pytorch2keras</a></b> (🥉17 ·  ⭐ 750) - PyTorch到Keras模型转换器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gmalivenko/pytorch2keras) (👨‍💻 13 · 🔀 130 · 📦 24 · 📋 120 - 41% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/nerox8664/pytorch2keras
	```
- [PyPi](https://pypi.org/project/pytorch2keras) (📥 640 / month):
	```
	pip install pytorch2keras
	```
</details>
<details><summary><b><a href="https://github.com/larq/compute-engine">Larq Compute Engine</a></b> (🥉17 ·  ⭐ 170) - 高度优化的二值化推理引擎。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/larq/compute-engine) (👨‍💻 17 · 🔀 26 · 📥 300 · 📦 4 · 📋 120 - 18% open · ⏱️ 08.09.2021):

	```
	git clone https://github.com/larq/compute-engine
	```
- [PyPi](https://pypi.org/project/larq-compute-engine) (📥 540 / month):
	```
	pip install larq-compute-engine
	```
</details>
<details><summary><b><a href="https://github.com/nok/sklearn-porter">sklearn-porter</a></b> (🥉16 ·  ⭐ 1.1K · 💀) - 将经过训练的scikit-learn估计器转换为C，Java等。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nok/sklearn-porter) (👨‍💻 11 · 🔀 140 · 📋 67 - 56% open · ⏱️ 18.12.2019):

	```
	git clone https://github.com/nok/sklearn-porter
	```
- [PyPi](https://pypi.org/project/sklearn-porter) (📥 550 / month):
	```
	pip install sklearn-porter
	```
</details>
<details><summary><b><a href="https://github.com/riga/tfdeploy">tfdeploy</a></b> (🥉15 ·  ⭐ 350 · 💤) - 部署张量流图以进行快速评估并导出到无tensorflow环境中基于numpy运行。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/riga/tfdeploy) (👨‍💻 4 · 🔀 37 · 📋 34 - 32% open · ⏱️ 08.01.2021):

	```
	git clone https://github.com/riga/tfdeploy
	```
- [PyPi](https://pypi.org/project/tfdeploy) (📥 140 / month):
	```
	pip install tfdeploy
	```
</details>
<br>

## 模型的可解释性

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于可视化，解释，调试，评估和解释机器学习模型的库。_

<details><summary><b><a href="https://github.com/slundberg/shap">shap</a></b> (🥇34 ·  ⭐ 14K) - 用于解释任何机器学习模型的输出的一种博弈论方法实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/slundberg/shap) (👨‍💻 160 · 🔀 2.1K · 📦 3.5K · 📋 1.7K - 67% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/slundberg/shap
	```
- [PyPi](https://pypi.org/project/shap) (📥 4M / month):
	```
	pip install shap
	```
- [Conda](https://anaconda.org/conda-forge/shap) (📥 650K · ⏱️ 29.04.2021):
	```
	conda install -c conda-forge shap
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/lime">Lime</a></b> (🥇29 ·  ⭐ 9.2K) - Lime：解释任何机器学习分类器的预测。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/marcotcr/lime) (👨‍💻 61 · 🔀 1.5K · 📦 1.6K · 📋 540 - 2% open · ⏱️ 29.07.2021):

	```
	git clone https://github.com/marcotcr/lime
	```
- [PyPi](https://pypi.org/project/lime) (📥 1.1M / month):
	```
	pip install lime
	```
- [Conda](https://anaconda.org/conda-forge/lime) (📥 83K · ⏱️ 28.06.2020):
	```
	conda install -c conda-forge lime
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/interpret">InterpretML</a></b> (🥇28 ·  ⭐ 4.1K) - 拟合可解释的模型。对机器学习黑匣子进行解释。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/interpret) (👨‍💻 27 · 🔀 510 · 📦 120 · 📋 240 - 33% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/interpretml/interpret
	```
- [PyPi](https://pypi.org/project/interpret) (📥 70K / month):
	```
	pip install interpret
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/captum">Captum</a></b> (🥇27 ·  ⭐ 2.7K) - PyTorch的模型可解释性和理解。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/captum) (👨‍💻 77 · 🔀 280 · 📦 280 · 📋 280 - 23% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/pytorch/captum
	```
- [PyPi](https://pypi.org/project/captum) (📥 30K / month):
	```
	pip install captum
	```
</details>
<details><summary><b><a href="https://github.com/parrt/dtreeviz">dtreeviz</a></b> (🥇27 ·  ⭐ 1.8K) - 用于决策树可视化和模型解释的python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/parrt/dtreeviz) (👨‍💻 16 · 🔀 220 · 📦 240 · 📋 100 - 17% open · ⏱️ 10.09.2021):

	```
	git clone https://github.com/parrt/dtreeviz
	```
- [PyPi](https://pypi.org/project/dtreeviz) (📥 180K / month):
	```
	pip install dtreeviz
	```
</details>
<details><summary><b><a href="https://github.com/bmabey/pyLDAvis">pyLDAvis</a></b> (🥇27 ·  ⭐ 1.5K · 💤) - 用于交互式主题模型可视化的Python库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bmabey/pyLDAvis) (👨‍💻 32 · 🔀 310 · 📦 2.7K · 📋 160 - 50% open · ⏱️ 24.03.2021):

	```
	git clone https://github.com/bmabey/pyLDAvis
	```
- [PyPi](https://pypi.org/project/pyldavis) (📥 420K / month):
	```
	pip install pyldavis
	```
- [Conda](https://anaconda.org/conda-forge/pyldavis) (📥 30K · ⏱️ 24.03.2021):
	```
	conda install -c conda-forge pyldavis
	```
</details>
<details><summary><b><a href="https://github.com/arviz-devs/arviz">arviz</a></b> (🥇27 ·  ⭐ 1.1K) - 使用Python探索性分析贝叶斯模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/arviz-devs/arviz) (👨‍💻 95 · 🔀 240 · 📥 110 · 📦 1.4K · 📋 670 - 23% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/arviz-devs/arviz
	```
- [PyPi](https://pypi.org/project/arviz) (📥 290K / month):
	```
	pip install arviz
	```
- [Conda](https://anaconda.org/conda-forge/arviz) (📥 510K · ⏱️ 03.10.2021):
	```
	conda install -c conda-forge arviz
	```
</details>
<details><summary><b><a href="https://github.com/reiinakano/scikit-plot">scikit-plot</a></b> (🥈26 ·  ⭐ 2.1K · 💀) - 一个直观的库，可向其中添加绘图功能。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/reiinakano/scikit-plot) (👨‍💻 13 · 🔀 250 · 📦 1.4K · 📋 58 - 32% open · ⏱️ 19.08.2018):

	```
	git clone https://github.com/reiinakano/scikit-plot
	```
- [PyPi](https://pypi.org/project/scikit-plot) (📥 410K / month):
	```
	pip install scikit-plot
	```
- [Conda](https://anaconda.org/conda-forge/scikit-plot) (📥 99K · ⏱️ 05.06.2019):
	```
	conda install -c conda-forge scikit-plot
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-analysis">Model Analysis</a></b> (🥈26 ·  ⭐ 1.1K) - TensorFlow的模型分析工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/model-analysis) (👨‍💻 35 · 🔀 220 · 📋 61 - 22% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/tensorflow/model-analysis
	```
- [PyPi](https://pypi.org/project/tensorflow-model-analysis) (📥 11M / month):
	```
	pip install tensorflow-model-analysis
	```
</details>
<details><summary><b><a href="https://github.com/SeldonIO/alibi">Alibi</a></b> (🥈25 ·  ⭐ 1.3K) - 监视和解释机器学习模型的算法。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SeldonIO/alibi) (👨‍💻 16 · 🔀 150 · 📦 100 · 📋 220 - 39% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/SeldonIO/alibi
	```
- [PyPi](https://pypi.org/project/alibi) (📥 13K / month):
	```
	pip install alibi
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/dowhy">DoWhy</a></b> (🥈24 ·  ⭐ 3.3K) - DoWhy是用于因果推断的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/dowhy) (👨‍💻 44 · 🔀 490 · 📥 24 · 📦 64 · 📋 140 - 25% open · ⏱️ 19.09.2021):

	```
	git clone https://github.com/Microsoft/dowhy
	```
- [PyPi](https://pypi.org/project/dowhy) (📥 48K / month):
	```
	pip install dowhy
	```
- [Conda](https://anaconda.org/conda-forge/dowhy) (📥 3.6K · ⏱️ 28.04.2021):
	```
	conda install -c conda-forge dowhy
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIF360">Fairness 360</a></b> (🥈24 ·  ⭐ 1.5K) - 一整套用于数据集的公平度量标准。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/AIF360) (👨‍💻 46 · 🔀 470 · 📦 120 · 📋 110 - 48% open · ⏱️ 18.09.2021):

	```
	git clone https://github.com/Trusted-AI/AIF360
	```
- [PyPi](https://pypi.org/project/aif360) (📥 7.6K / month):
	```
	pip install aif360
	```
</details>
<details><summary><b><a href="https://github.com/raghakot/keras-vis">keras-vis</a></b> (🥈23 ·  ⭐ 2.9K · 💀) - 用于Keras的神经网络可视化工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/raghakot/keras-vis) (👨‍💻 10 · 🔀 600 · 📦 1.3K · 📋 210 - 53% open · ⏱️ 20.04.2020):

	```
	git clone https://github.com/raghakot/keras-vis
	```
- [PyPi](https://pypi.org/project/keras-vis) (📥 3.8K / month):
	```
	pip install keras-vis
	```
</details>
<details><summary><b><a href="https://github.com/philipperemy/keract">keract</a></b> (🥈23 ·  ⭐ 930) - 在Keras中分层输出和渐变。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/philipperemy/keract) (👨‍💻 16 · 🔀 180 · 📦 99 · 📋 83 - 2% open · ⏱️ 28.07.2021):

	```
	git clone https://github.com/philipperemy/keract
	```
- [PyPi](https://pypi.org/project/keract) (📥 1.9K / month):
	```
	pip install keract
	```
</details>
<details><summary><b><a href="https://github.com/TeamHG-Memex/eli5">eli5</a></b> (🥈22 ·  ⭐ 2.5K · 💀) - 一个用于调试/检查机器学习分类器的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/TeamHG-Memex/eli5) (👨‍💻 14 · 🔀 300 · 📋 240 - 54% open · ⏱️ 22.01.2020):

	```
	git clone https://github.com/TeamHG-Memex/eli5
	```
- [PyPi](https://pypi.org/project/eli5) (📥 1.1M / month):
	```
	pip install eli5
	```
- [Conda](https://anaconda.org/conda-forge/eli5) (📥 100K · ⏱️ 25.01.2021):
	```
	conda install -c conda-forge eli5
	```
</details>
<details><summary><b><a href="https://github.com/quantumblacklabs/causalnex">CausalNex</a></b> (🥈22 ·  ⭐ 1.3K) - 一个可帮助数据科学家进行因果推断的Python库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/quantumblacklabs/causalnex) (👨‍💻 22 · 🔀 140 · 📦 27 · 📋 96 - 11% open · ⏱️ 15.09.2021):

	```
	git clone https://github.com/quantumblacklabs/causalnex
	```
- [PyPi](https://pypi.org/project/causalnex) (📥 2.7K / month):
	```
	pip install causalnex
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIX360">Explainability 360</a></b> (🥈22 ·  ⭐ 960) - 数据和机器学习的可解释性。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/AIX360) (👨‍💻 29 · 🔀 190 · 📦 34 · 📋 53 - 56% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/Trusted-AI/AIX360
	```
- [PyPi](https://pypi.org/project/aix360) (📥 1.3K / month):
	```
	pip install aix360
	```
</details>
<details><summary><b><a href="https://github.com/oegedijk/explainerdashboard">explainerdashboard</a></b> (🥈22 ·  ⭐ 640) - 快速构建可显示内部信息的可解释AI仪表板。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oegedijk/explainerdashboard) (👨‍💻 12 · 🔀 81 · 📦 38 · 📋 120 - 11% open · ⏱️ 08.07.2021):

	```
	git clone https://github.com/oegedijk/explainerdashboard
	```
- [PyPi](https://pypi.org/project/explainerdashboard) (📥 8.2K / month):
	```
	pip install explainerdashboard
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/lucid">Lucid</a></b> (🥈21 ·  ⭐ 4.3K · 💤) - 用于神经科学研究的基础设施和工具的集合。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/lucid) (👨‍💻 40 · 🔀 580 · 📦 580 · 📋 170 - 40% open · ⏱️ 19.03.2021):

	```
	git clone https://github.com/tensorflow/lucid
	```
- [PyPi](https://pypi.org/project/lucid):
	```
	pip install lucid
	```
</details>
<details><summary><b><a href="https://github.com/parrt/random-forest-importances">random-forest-importances</a></b> (🥈21 ·  ⭐ 480 · 💤) - 随机森林特征重要度计算。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/parrt/random-forest-importances) (👨‍💻 14 · 🔀 100 · 📦 85 · 📋 32 - 12% open · ⏱️ 30.01.2021):

	```
	git clone https://github.com/parrt/random-forest-importances
	```
- [PyPi](https://pypi.org/project/rfpimp) (📥 19K / month):
	```
	pip install rfpimp
	```
</details>
<details><summary><b><a href="https://github.com/DistrictDataLabs/yellowbrick">yellowbrick</a></b> (🥉20 ·  ⭐ 3.4K) - 可视化分析和诊断工具，方便机器使用。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/DistrictDataLabs/yellowbrick) (👨‍💻 100 · 🔀 480 · 📋 620 - 12% open · ⏱️ 25.09.2021):

	```
	git clone https://github.com/DistrictDataLabs/yellowbrick
	```
- [PyPi](https://pypi.org/project/yellowbrick) (📥 310K / month):
	```
	pip install yellowbrick
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/checklist">checklist</a></b> (🥉20 ·  ⭐ 1.5K) - 超越准确性：使用CheckList对NLP模型进行行为测试。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/marcotcr/checklist) (👨‍💻 12 · 🔀 140 · 📦 37 · ⏱️ 28.09.2021):

	```
	git clone https://github.com/marcotcr/checklist
	```
- [PyPi](https://pypi.org/project/checklist) (📥 14K / month):
	```
	pip install checklist
	```
</details>
<details><summary><b><a href="https://github.com/fairlearn/fairlearn">fairlearn</a></b> (🥉20 ·  ⭐ 1.1K) - 一个用于评估和改善机器公平性的Python程序包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/fairlearn/fairlearn) (👨‍💻 58 · 🔀 260 · 📋 300 - 41% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/fairlearn/fairlearn
	```
- [PyPi](https://pypi.org/project/fairlearn) (📥 33K / month):
	```
	pip install fairlearn
	```
- [Conda](https://anaconda.org/conda-forge/fairlearn) (📥 15K · ⏱️ 07.07.2021):
	```
	conda install -c conda-forge fairlearn
	```
</details>
<details><summary><b><a href="https://github.com/oracle/Skater">Skater</a></b> (🥉20 ·  ⭐ 1K · 💀) - 用于模型解释/说明的Python库。<code><a href="https://tldrlegal.com/search?q=UPL-1.0">❗️UPL-1.0</a></code></summary>

- [GitHub](https://github.com/oracle/Skater) (👨‍💻 34 · 🔀 160 · 📋 160 - 40% open · ⏱️ 29.06.2020):

	```
	git clone https://github.com/oracle/Skater
	```
- [PyPi](https://pypi.org/project/skater) (📥 7.9K / month):
	```
	pip install skater
	```
- [Conda](https://anaconda.org/conda-forge/skater) (📥 44K · ⏱️ 01.11.2020):
	```
	conda install -c conda-forge skater
	```
</details>
<details><summary><b><a href="https://github.com/ModelOriented/DALEX">DALEX</a></b> (🥉20 ·  ⭐ 910) - 用于模型探索和扩展的模块。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/ModelOriented/DALEX) (👨‍💻 20 · 🔀 120 · 📦 20 · 📋 320 - 4% open · ⏱️ 09.10.2021):

	```
	git clone https://github.com/ModelOriented/DALEX
	```
- [PyPi](https://pypi.org/project/dalex) (📥 8.4K / month):
	```
	pip install dalex
	```
</details>
<details><summary><b><a href="https://github.com/sicara/tf-explain">tf-explain</a></b> (🥉20 ·  ⭐ 860) - 使用Tensorflow 2.x的tf.keras模型的可解释性方法。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sicara/tf-explain) (👨‍💻 15 · 🔀 84 · 📦 90 · 📋 84 - 42% open · ⏱️ 22.06.2021):

	```
	git clone https://github.com/sicara/tf-explain
	```
- [PyPi](https://pypi.org/project/tf-explain) (📥 2.3K / month):
	```
	pip install tf-explain
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/DiCE">DiCE</a></b> (🥉20 ·  ⭐ 660) - 生成任何机器学习的各种反事实说明。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/DiCE) (👨‍💻 12 · 🔀 85 · 📋 86 - 43% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/interpretml/DiCE
	```
- [PyPi](https://pypi.org/project/dice-ml) (📥 19K / month):
	```
	pip install dice-ml
	```
</details>
<details><summary><b><a href="https://github.com/andosa/treeinterpreter">TreeInterpreter</a></b> (🥉19 ·  ⭐ 680 · 💤) - 解释scikit-learn决策树的程序包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/andosa/treeinterpreter) (👨‍💻 11 · 🔀 130 · 📦 160 · 📋 23 - 82% open · ⏱️ 28.02.2021):

	```
	git clone https://github.com/andosa/treeinterpreter
	```
- [PyPi](https://pypi.org/project/treeinterpreter) (📥 240K / month):
	```
	pip install treeinterpreter
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥉19 ·  ⭐ 580) - What-If工具的源代码/网页/演示。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/what-if-tool) (👨‍💻 19 · 🔀 110 · 📋 90 - 51% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/PAIR-code/what-if-tool
	```
- [PyPi](https://pypi.org/project/witwidget):
	```
	pip install witwidget
	```
- [NPM](https://www.npmjs.com/package/wit-widget) (📥 2.9K / month):
	```
	npm install wit-widget
	```
</details>
<details><summary><b><a href="https://github.com/edublancas/sklearn-evaluation">sklearn-evaluation</a></b> (🥉19 ·  ⭐ 310) - 机器学习模型评估变得容易。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/edublancas/sklearn-evaluation) (👨‍💻 6 · 🔀 25 · 📦 31 · 📋 37 - 21% open · ⏱️ 10.07.2021):

	```
	git clone https://github.com/edublancas/sklearn-evaluation
	```
- [PyPi](https://pypi.org/project/sklearn-evaluation) (📥 1.1K / month):
	```
	pip install sklearn-evaluation
	```
</details>
<details><summary><b><a href="https://github.com/csinva/imodels">imodels</a></b> (🥉19 ·  ⭐ 280) - 可解释的ML包，用于简洁，透明和准确的预测。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csinva/imodels) (👨‍💻 5 · 🔀 26 · 📦 9 · 📋 15 - 6% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/csinva/imodels
	```
- [PyPi](https://pypi.org/project/imodels) (📥 500 / month):
	```
	pip install imodels
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/fairness-indicators">fairness-indicators</a></b> (🥉19 ·  ⭐ 220) - Tensorflow的公平性评估和可视化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/fairness-indicators) (👨‍💻 23 · 🔀 61 · 📋 10 - 30% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/tensorflow/fairness-indicators
	```
- [PyPi](https://pypi.org/project/fairness-indicators) (📥 780 / month):
	```
	pip install fairness-indicators
	```
</details>
<details><summary><b><a href="https://github.com/kundajelab/deeplift">deeplift</a></b> (🥉18 ·  ⭐ 570 · 💤) - Public facing deeplift repo。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kundajelab/deeplift) (👨‍💻 11 · 🔀 130 · 📦 50 · 📋 79 - 40% open · ⏱️ 11.11.2020):

	```
	git clone https://github.com/kundajelab/deeplift
	```
- [PyPi](https://pypi.org/project/deeplift) (📥 470 / month):
	```
	pip install deeplift
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-card-toolkit">model-card-toolkit</a></b> (🥉18 ·  ⭐ 220) - 模型解释与分析卡片工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tensorflow/model-card-toolkit) (👨‍💻 11 · 🔀 33 · 📦 4 · 📋 6 - 66% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/tensorflow/model-card-toolkit
	```
- [PyPi](https://pypi.org/project/model-card-toolkit) (📥 380 / month):
	```
	pip install model-card-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/dssg/aequitas">aequitas</a></b> (🥉17 ·  ⭐ 420) - 偏差和公平审计工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dssg/aequitas) (👨‍💻 16 · 🔀 78 · 📦 82 · 📋 55 - 61% open · ⏱️ 27.05.2021):

	```
	git clone https://github.com/dssg/aequitas
	```
- [PyPi](https://pypi.org/project/aequitas) (📥 970 / month):
	```
	pip install aequitas
	```
</details>
<details><summary><b><a href="https://github.com/albermax/innvestigate">iNNvestigate</a></b> (🥉16 ·  ⭐ 900) - 神经网络预估分析工具箱。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/albermax/innvestigate) (👨‍💻 19 · 🔀 190 · 📋 220 - 29% open · ⏱️ 03.08.2021):

	```
	git clone https://github.com/albermax/innvestigate
	```
- [PyPi](https://pypi.org/project/innvestigate) (📥 340 / month):
	```
	pip install innvestigate
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tcav">tcav</a></b> (🥉16 ·  ⭐ 490) - TCAV ML可解释性项目的代码。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tcav) (👨‍💻 19 · 🔀 110 · 📦 9 · 📋 55 - 5% open · ⏱️ 16.09.2021):

	```
	git clone https://github.com/tensorflow/tcav
	```
- [PyPi](https://pypi.org/project/tcav) (📥 86 / month):
	```
	pip install tcav
	```
</details>
<details><summary><b><a href="https://github.com/explainX/explainx">ExplainX.ai</a></b> (🥉16 ·  ⭐ 230 · 💤) - 适用于数据科学家的可解释AI框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explainX/explainx) (👨‍💻 4 · 🔀 37 · 📥 2 · 📋 24 - 29% open · ⏱️ 02.02.2021):

	```
	git clone https://github.com/explainX/explainx
	```
- [PyPi](https://pypi.org/project/explainx) (📥 1.2K / month):
	```
	pip install explainx
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/lit">LIT</a></b> (🥉15 ·  ⭐ 2.7K) - 语言可解释性工具：交互式分析NLP模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/lit) (👨‍💻 14 · 🔀 260 · 📦 7 · 📋 80 - 45% open · ⏱️ 05.04.2021):

	```
	git clone https://github.com/PAIR-code/lit
	```
- [PyPi](https://pypi.org/project/lit-nlp):
	```
	pip install lit-nlp
	```
</details>
<details><summary><b><a href="https://github.com/EthicalML/xai">XAI</a></b> (🥉15 ·  ⭐ 710) - XAI-用于机器学习的可解释性工具箱。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/EthicalML/xai) (👨‍💻 3 · 🔀 110 · 📦 11 · 📋 8 - 62% open · ⏱️ 23.04.2021):

	```
	git clone https://github.com/EthicalML/xai
	```
- [PyPi](https://pypi.org/project/xai) (📥 250 / month):
	```
	pip install xai
	```
</details>
<details><summary><b><a href="https://github.com/MisaOgura/flashtorch">FlashTorch</a></b> (🥉15 ·  ⭐ 620) - PyTorch中用于神经网络的可视化工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MisaOgura/flashtorch) (👨‍💻 2 · 🔀 73 · 📦 7 · 📋 28 - 21% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/MisaOgura/flashtorch
	```
- [PyPi](https://pypi.org/project/flashtorch) (📥 300 / month):
	```
	pip install flashtorch
	```
</details>
<details><summary><b><a href="https://github.com/aerdem4/lofo-importance">LOFO</a></b> (🥉15 ·  ⭐ 380) - Leave One Feature Out特征重要度。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aerdem4/lofo-importance) (👨‍💻 3 · 🔀 43 · 📦 6 · 📋 13 - 23% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/aerdem4/lofo-importance
	```
- [PyPi](https://pypi.org/project/lofo-importance) (📥 700 / month):
	```
	pip install lofo-importance
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/anchor">Anchor</a></b> (🥉14 ·  ⭐ 670) - High-Precision Model-Agnostic Explanations论文代码。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/marcotcr/anchor) (👨‍💻 8 · 🔀 91 · 📋 66 - 27% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/marcotcr/anchor
	```
- [PyPi](https://pypi.org/project/anchor_exp) (📥 800 / month):
	```
	pip install anchor_exp
	```
</details>
<details><summary><b><a href="https://github.com/SAP/contextual-ai">contextual-ai</a></b> (🥉13 ·  ⭐ 72) - AI 模型可解释性工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SAP/contextual-ai) (👨‍💻 11 · 🔀 10 · 📋 12 - 58% open · ⏱️ 15.09.2021):

	```
	git clone https://github.com/SAP/contextual-ai
	```
- [PyPi](https://pypi.org/project/contextual-ai) (📥 140 / month):
	```
	pip install contextual-ai
	```
</details>
<details><summary><b><a href="https://github.com/suinleelab/attributionpriors">Attribution Priors</a></b> (🥉12 ·  ⭐ 86 · 💤) - 训练可解释模型的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/suinleelab/attributionpriors) (👨‍💻 6 · 🔀 9 · 📦 3 · 📋 4 - 25% open · ⏱️ 19.03.2021):

	```
	git clone https://github.com/suinleelab/attributionpriors
	```
- [PyPi](https://pypi.org/project/attributionpriors) (📥 33 / month):
	```
	pip install attributionpriors
	```
</details>
<details><summary><b><a href="https://github.com/intuit/bias-detector">bias-detector</a></b> (🥉11 ·  ⭐ 34) - Bias Detector是用于检测机器偏差的python软件包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/intuit/bias-detector) (👨‍💻 4 · 🔀 7 · ⏱️ 01.06.2021):

	```
	git clone https://github.com/intuit/bias-detector
	```
- [PyPi](https://pypi.org/project/bias-detector) (📥 81 / month):
	```
	pip install bias-detector
	```
</details>
<br>

## 向量相似度搜索（ANN）

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于近似最近邻居搜索和向量索引/相似性搜索的库。_

🔗&nbsp;<b><a href="https://github.com/erikbern/ann-benchmarks">ANN Benchmarks</a></b> ( ⭐ 2.5K)  - Benchmarks of approximate nearest neighbor libraries in Python.

<details><summary><b><a href="https://github.com/spotify/annoy">Annoy</a></b> (🥇30 ·  ⭐ 9.1K) - C++/Python中的近似最近邻居实现，并针对内存使用进行了优化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/annoy) (👨‍💻 73 · 🔀 940 · 📦 1.8K · 📋 330 - 10% open · ⏱️ 22.09.2021):

	```
	git clone https://github.com/spotify/annoy
	```
- [PyPi](https://pypi.org/project/annoy) (📥 930K / month):
	```
	pip install annoy
	```
</details>
<details><summary><b><a href="https://github.com/nmslib/nmslib">NMSLIB</a></b> (🥇28 ·  ⭐ 2.6K) - 非度量空间库（NMSLIB）：一种有效的相似度搜索。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nmslib/nmslib) (👨‍💻 45 · 🔀 360 · 📦 480 · 📋 380 - 13% open · ⏱️ 19.09.2021):

	```
	git clone https://github.com/nmslib/nmslib
	```
- [PyPi](https://pypi.org/project/nmslib) (📥 94K / month):
	```
	pip install nmslib
	```
- [Conda](https://anaconda.org/conda-forge/nmslib) (📥 42K · ⏱️ 08.01.2021):
	```
	conda install -c conda-forge nmslib
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/faiss">Faiss</a></b> (🥈27 ·  ⭐ 15K) - 一个用于高效相似性搜索和密集向量聚类的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/faiss) (👨‍💻 89 · 🔀 2.3K · 📦 470 · 📋 1.6K - 12% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/facebookresearch/faiss
	```
- [PyPi](https://pypi.org/project/pymilvus) (📥 22K / month):
	```
	pip install pymilvus
	```
- [Conda](https://anaconda.org/conda-forge/faiss) (📥 190K · ⏱️ 19.04.2021):
	```
	conda install -c conda-forge faiss
	```
</details>
<details><summary><b><a href="https://github.com/milvus-io/milvus">Milvus</a></b> (🥈27 ·  ⭐ 8.3K · 📈) - 一个开源的embedding嵌入向量相似度搜索引擎。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/milvus-io/milvus) (👨‍💻 170 · 🔀 1.1K · 📥 1.7K · 📋 3.6K - 6% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/milvus-io/milvus
	```
- [PyPi](https://pypi.org/project/pymilvus) (📥 22K / month):
	```
	pip install pymilvus
	```
- [Docker Hub](https://hub.docker.com/r/milvusdb/milvus) (📥 520K · ⭐ 14 · ⏱️ 11.10.2021):
	```
	docker pull milvusdb/milvus
	```
</details>
<details><summary><b><a href="https://github.com/lmcinnes/pynndescent">PyNNDescent</a></b> (🥈26 ·  ⭐ 490) - 适用于近似最近邻查找的Python库。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/lmcinnes/pynndescent) (👨‍💻 16 · 🔀 63 · 📦 820 · 📋 80 - 43% open · ⏱️ 27.09.2021):

	```
	git clone https://github.com/lmcinnes/pynndescent
	```
- [PyPi](https://pypi.org/project/pynndescent) (📥 1.3M / month):
	```
	pip install pynndescent
	```
- [Conda](https://anaconda.org/conda-forge/pynndescent) (📥 300K · ⏱️ 06.07.2021):
	```
	conda install -c conda-forge pynndescent
	```
</details>
<details><summary><b><a href="https://github.com/nmslib/hnswlib">hnswlib</a></b> (🥉22 ·  ⭐ 1.7K) - 仅标头的C++/python库，用于快速近似最近邻查找。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nmslib/hnswlib) (👨‍💻 46 · 🔀 320 · 📦 150 · 📋 220 - 45% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/nmslib/hnswlib
	```
- [PyPi](https://pypi.org/project/hnswlib):
	```
	pip install hnswlib
	```
</details>
<details><summary><b><a href="https://github.com/plasticityai/magnitude">Magnitude</a></b> (🥉22 ·  ⭐ 1.5K · 💀) - 快速，高效的通用向量嵌入实用程序包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plasticityai/magnitude) (👨‍💻 4 · 🔀 100 · 📦 200 · 📋 80 - 36% open · ⏱️ 17.07.2020):

	```
	git clone https://github.com/plasticityai/magnitude
	```
- [PyPi](https://pypi.org/project/pymagnitude) (📥 4.8K / month):
	```
	pip install pymagnitude
	```
</details>
<details><summary><b><a href="https://github.com/pixelogik/NearPy">NearPy</a></b> (🥉20 ·  ⭐ 690 · 💀) - 用于快速（近似）最近邻搜索的Python框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pixelogik/NearPy) (👨‍💻 18 · 🔀 140 · 📦 56 · 📋 62 - 38% open · ⏱️ 21.10.2018):

	```
	git clone https://github.com/pixelogik/NearPy
	```
- [PyPi](https://pypi.org/project/NearPy) (📥 1.1K / month):
	```
	pip install NearPy
	```
</details>
<details><summary><b><a href="https://github.com/kakao/n2">N2</a></b> (🥉18 ·  ⭐ 490) - TOROS N2-快速运行的轻量级近似最近邻库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/kakao/n2) (👨‍💻 18 · 🔀 54 · 📦 19 · 📋 31 - 29% open · ⏱️ 20.05.2021):

	```
	git clone https://github.com/kakao/n2
	```
- [PyPi](https://pypi.org/project/n2) (📥 960 / month):
	```
	pip install n2
	```
</details>
<details><summary><b><a href="https://github.com/yahoojapan/NGT">NGT</a></b> (🥉17 ·  ⭐ 800) - 最近邻搜索算法实现包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/yahoojapan/NGT) (👨‍💻 12 · 🔀 81 · 📋 81 - 8% open · ⏱️ 15.07.2021):

	```
	git clone https://github.com/yahoojapan/NGT
	```
- [PyPi](https://pypi.org/project/ngt) (📥 15K / month):
	```
	pip install ngt
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pysparnn">PySparNN</a></b> (🥉11 ·  ⭐ 880 · 💀) - C++/Python中的近似最近邻居实现，并针对内存使用进行了优化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/facebookresearch/pysparnn) (👨‍💻 5 · 🔀 140 · 📋 29 - 51% open · ⏱️ 31.01.2018):

	```
	git clone https://github.com/facebookresearch/pysparnn
	```
</details>
<br>

## 概率统计

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_提供概率编程/推理，贝叶斯推理，高斯过程或统计信息的功能的库。_

<details><summary><b><a href="https://github.com/pyro-ppl/pyro">Pyro</a></b> (🥇29 ·  ⭐ 7.1K) - 使用Python和PyTorch进行深度通用概率编程。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyro-ppl/pyro) (👨‍💻 120 · 🔀 850 · 📦 550 · 📋 880 - 17% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/pyro-ppl/pyro
	```
- [PyPi](https://pypi.org/project/pyro-ppl) (📥 74K / month):
	```
	pip install pyro-ppl
	```
</details>
<details><summary><b><a href="https://github.com/cornellius-gp/gpytorch">GPyTorch</a></b> (🥇29 ·  ⭐ 2.5K) - 高斯过程的高效和模块化实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cornellius-gp/gpytorch) (👨‍💻 87 · 🔀 360 · 📦 390 · 📋 980 - 22% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/cornellius-gp/gpytorch
	```
- [PyPi](https://pypi.org/project/gpytorch) (📥 140K / month):
	```
	pip install gpytorch
	```
</details>
<details><summary><b><a href="https://github.com/hmmlearn/hmmlearn">hmmlearn</a></b> (🥇28 ·  ⭐ 2.4K) - Python中的隐马尔可夫模型，具有类似于scikit-learn的API。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hmmlearn/hmmlearn) (👨‍💻 34 · 🔀 640 · 📦 1.1K · 📋 360 - 15% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/hmmlearn/hmmlearn
	```
- [PyPi](https://pypi.org/project/hmmlearn) (📥 96K / month):
	```
	pip install hmmlearn
	```
- [Conda](https://anaconda.org/conda-forge/hmmlearn) (📥 100K · ⏱️ 31.08.2021):
	```
	conda install -c conda-forge hmmlearn
	```
</details>
<details><summary><b><a href="https://github.com/rlabbe/filterpy">filterpy</a></b> (🥇28 ·  ⭐ 2K) - Python卡尔曼过滤和最佳估计库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rlabbe/filterpy) (👨‍💻 36 · 🔀 450 · 📦 1.1K · 📋 190 - 19% open · ⏱️ 04.05.2021):

	```
	git clone https://github.com/rlabbe/filterpy
	```
- [PyPi](https://pypi.org/project/filterpy) (📥 1M / month):
	```
	pip install filterpy
	```
- [Conda](https://anaconda.org/conda-forge/filterpy) (📥 68K · ⏱️ 05.05.2020):
	```
	conda install -c conda-forge filterpy
	```
</details>
<details><summary><b><a href="https://github.com/pydata/patsy">patsy</a></b> (🥇28 ·  ⭐ 800) - 使用符号公式描述Python中的统计模型。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pydata/patsy) (👨‍💻 16 · 🔀 84 · 📦 42K · 📋 130 - 46% open · ⏱️ 26.09.2021):

	```
	git clone https://github.com/pydata/patsy
	```
- [PyPi](https://pypi.org/project/patsy) (📥 4.1M / month):
	```
	pip install patsy
	```
- [Conda](https://anaconda.org/conda-forge/patsy) (📥 3.6M · ⏱️ 26.09.2021):
	```
	conda install -c conda-forge patsy
	```
</details>
<details><summary><b><a href="https://github.com/pymc-devs/pymc">PyMC3</a></b> (🥈26 ·  ⭐ 6.1K) - Python中的概率编程。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pymc-devs/pymc) (👨‍💻 330 · 🔀 1.4K · 📥 420 · 📦 550 · 📋 2.4K - 8% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/pymc-devs/pymc3
	```
- [PyPi](https://pypi.org/project/pymc3) (📥 270K / month):
	```
	pip install pymc3
	```
- [Conda](https://anaconda.org/conda-forge/pymc3) (📥 320K · ⏱️ 12.10.2021):
	```
	conda install -c conda-forge pymc3
	```
</details>
<details><summary><b><a href="https://github.com/jmschrei/pomegranate">pomegranate</a></b> (🥈26 ·  ⭐ 2.7K) - 在Python中快速，灵活且易于使用的概率建模。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jmschrei/pomegranate) (👨‍💻 63 · 🔀 490 · 📦 540 · 📋 630 - 8% open · ⏱️ 26.07.2021):

	```
	git clone https://github.com/jmschrei/pomegranate
	```
- [PyPi](https://pypi.org/project/pomegranate) (📥 48K / month):
	```
	pip install pomegranate
	```
- [Conda](https://anaconda.org/conda-forge/pomegranate) (📥 73K · ⏱️ 28.08.2021):
	```
	conda install -c conda-forge pomegranate
	```
</details>
<details><summary><b><a href="https://github.com/GPflow/GPflow">GPflow</a></b> (🥈26 ·  ⭐ 1.5K) - TensorFlow中的高斯过程。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/GPflow/GPflow) (👨‍💻 71 · 🔀 400 · 📦 300 · 📋 710 - 13% open · ⏱️ 21.09.2021):

	```
	git clone https://github.com/GPflow/GPflow
	```
- [PyPi](https://pypi.org/project/gpflow) (📥 5.3K / month):
	```
	pip install gpflow
	```
- [Conda](https://anaconda.org/conda-forge/gpflow) (📥 9.6K · ⏱️ 06.11.2018):
	```
	conda install -c conda-forge gpflow
	```
</details>
<details><summary><b><a href="https://github.com/raphaelvallat/pingouin">pingouin</a></b> (🥈26 ·  ⭐ 800) - 基于Pandas的Python统计软件包。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/raphaelvallat/pingouin) (👨‍💻 22 · 🔀 70 · 📦 340 · 📋 160 - 15% open · ⏱️ 02.09.2021):

	```
	git clone https://github.com/raphaelvallat/pingouin
	```
- [PyPi](https://pypi.org/project/pingouin) (📥 190K / month):
	```
	pip install pingouin
	```
- [Conda](https://anaconda.org/conda-forge/pingouin) (📥 46K · ⏱️ 17.08.2021):
	```
	conda install -c conda-forge pingouin
	```
</details>
<details><summary><b><a href="https://github.com/pgmpy/pgmpy">pgmpy</a></b> (🥉25 ·  ⭐ 1.9K) - 用于学习（结构和参数）和推理的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pgmpy/pgmpy) (👨‍💻 98 · 🔀 590 · 📥 110 · 📦 270 · 📋 720 - 24% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/pgmpy/pgmpy
	```
- [PyPi](https://pypi.org/project/pgmpy) (📥 60K / month):
	```
	pip install pgmpy
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/probability">tensorflow-probability</a></b> (🥉24 ·  ⭐ 3.5K) - 概率推理与统计分析。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/probability) (👨‍💻 430 · 🔀 890 · 📋 1.1K - 42% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/tensorflow/probability
	```
- [PyPi](https://pypi.org/project/tensorflow-probability) (📥 1.4M / month):
	```
	pip install tensorflow-probability
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-probability) (📥 44K · ⏱️ 01.10.2021):
	```
	conda install -c conda-forge tensorflow-probability
	```
</details>
<details><summary><b><a href="https://github.com/blei-lab/edward">Edward</a></b> (🥉23 ·  ⭐ 4.7K · 💀) - TensorFlow中的一种概率编程语言。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/blei-lab/edward) (👨‍💻 87 · 🔀 760 · 📥 14 · 📦 240 · 📋 510 - 36% open · ⏱️ 25.07.2018):

	```
	git clone https://github.com/blei-lab/edward
	```
- [PyPi](https://pypi.org/project/edward) (📥 3.5K / month):
	```
	pip install edward
	```
</details>
<details><summary><b><a href="https://github.com/SALib/SALib">SALib</a></b> (🥉23 ·  ⭐ 530) - Python（Numpy）中的灵敏度分析库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SALib/SALib) (👨‍💻 34 · 🔀 160 · 📋 250 - 15% open · ⏱️ 25.09.2021):

	```
	git clone https://github.com/SALib/SALib
	```
- [PyPi](https://pypi.org/project/salib) (📥 100K / month):
	```
	pip install salib
	```
- [Conda](https://anaconda.org/conda-forge/salib) (📥 70K · ⏱️ 04.09.2021):
	```
	conda install -c conda-forge salib
	```
</details>
<details><summary><b><a href="https://github.com/uber/orbit">Orbit</a></b> (🥉19 ·  ⭐ 690) - 用于贝叶斯预测的Python软件包，具有面向对象的设计。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/uber/orbit) (👨‍💻 14 · 🔀 53 · 📦 4 · 📋 270 - 12% open · ⏱️ 09.10.2021):

	```
	git clone https://github.com/uber/orbit
	```
- [PyPi](https://pypi.org/project/orbit-ml) (📥 13K / month):
	```
	pip install orbit-ml
	```
</details>
<details><summary><b><a href="https://github.com/bambinos/bambi">bambi</a></b> (🥉19 ·  ⭐ 680) - Python中的贝叶斯模型构建接口（Bambi）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bambinos/bambi) (👨‍💻 21 · 🔀 62 · 📦 14 · 📋 200 - 14% open · ⏱️ 09.10.2021):

	```
	git clone https://github.com/bambinos/bambi
	```
- [PyPi](https://pypi.org/project/bambi) (📥 840 / month):
	```
	pip install bambi
	```
</details>
<details><summary><b><a href="https://github.com/maximtrp/scikit-posthocs">scikit-posthocs</a></b> (🥉19 ·  ⭐ 220) - Python中的多个成对比较（Post Hoc）测试。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maximtrp/scikit-posthocs) (👨‍💻 8 · 🔀 22 · 📥 23 · 📋 42 - 9% open · ⏱️ 11.09.2021):

	```
	git clone https://github.com/maximtrp/scikit-posthocs
	```
- [PyPi](https://pypi.org/project/scikit-posthocs) (📥 25K / month):
	```
	pip install scikit-posthocs
	```
</details>
<details><summary><b><a href="https://github.com/pyro-ppl/funsor">Funsor</a></b> (🥉19 ·  ⭐ 180) - 用于概率编程的函数张量。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyro-ppl/funsor) (👨‍💻 9 · 🔀 15 · 📦 16 · 📋 140 - 47% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/pyro-ppl/funsor
	```
- [PyPi](https://pypi.org/project/funsor) (📥 830 / month):
	```
	pip install funsor
	```
</details>
<details><summary><b><a href="https://github.com/mattjj/pyhsmm">pyhsmm</a></b> (🥉18 ·  ⭐ 500 · 💀) - HSMM和HMM中的贝叶斯推断。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mattjj/pyhsmm) (👨‍💻 13 · 🔀 160 · 📦 21 · 📋 94 - 36% open · ⏱️ 24.08.2020):

	```
	git clone https://github.com/mattjj/pyhsmm
	```
- [PyPi](https://pypi.org/project/pyhsmm) (📥 190 / month):
	```
	pip install pyhsmm
	```
</details>
<details><summary><b><a href="https://github.com/ElementAI/baal">Baal</a></b> (🥉17 ·  ⭐ 440) - 在深度网络中使用近似贝叶斯后验进行主动学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ElementAI/baal) (👨‍💻 11 · 🔀 43 · 📋 54 - 22% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/ElementAI/baal
	```
- [PyPi](https://pypi.org/project/baal) (📥 410 / month):
	```
	pip install baal
	```
</details>
<details><summary><b><a href="https://github.com/stan-dev/pystan">PyStan</a></b> (🥉17 ·  ⭐ 120) - PyStan是Stan的Python接口。<code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/stan-dev/pystan) (👨‍💻 9 · 🔀 28 · 📋 160 - 4% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/stan-dev/pystan
	```
- [PyPi](https://pypi.org/project/pystan) (📥 1.5M / month):
	```
	pip install pystan
	```
- [Conda](https://anaconda.org/conda-forge/pystan) (📥 1.3M · ⏱️ 21.09.2021):
	```
	conda install -c conda-forge pystan
	```
</details>
<details><summary><b><a href="https://github.com/thu-ml/zhusuan">ZhuSuan</a></b> (🥉14 ·  ⭐ 2.1K · 💀) - TensorFlow中的一种概率编程语言。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/thu-ml/zhusuan) (👨‍💻 20 · 🔀 400 · 📋 60 - 11% open · ⏱️ 05.08.2019):

	```
	git clone https://github.com/thu-ml/zhusuan
	```
</details>
<br>

## 对抗学习与鲁棒性

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于测试机器学习模型抵抗攻击性/恶意示例的鲁棒性的库。_

<details><summary><b><a href="https://github.com/cleverhans-lab/cleverhans">CleverHans</a></b> (🥇28 ·  ⭐ 5.3K) - 一个用于构造攻击的对抗性示例库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cleverhans-lab/cleverhans) (👨‍💻 130 · 🔀 1.3K · 📦 260 · 📋 440 - 3% open · ⏱️ 23.09.2021):

	```
	git clone https://github.com/cleverhans-lab/cleverhans
	```
- [PyPi](https://pypi.org/project/cleverhans) (📥 1.1K / month):
	```
	pip install cleverhans
	```
</details>
<details><summary><b><a href="https://github.com/bethgelab/foolbox">Foolbox</a></b> (🥈26 ·  ⭐ 2K) - 一个Python工具箱，用于创建欺骗神经网络的对抗示例。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bethgelab/foolbox) (👨‍💻 32 · 🔀 360 · 📦 240 · 📋 330 - 17% open · ⏱️ 05.06.2021):

	```
	git clone https://github.com/bethgelab/foolbox
	```
- [PyPi](https://pypi.org/project/foolbox) (📥 2.1K / month):
	```
	pip install foolbox
	```
</details>
<details><summary><b><a href="https://github.com/QData/TextAttack">TextAttack</a></b> (🥈26 ·  ⭐ 1.7K) - TextAttack是用于对抗攻击，数据的Python框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QData/TextAttack) (👨‍💻 43 · 🔀 200 · 📦 32 · 📋 150 - 23% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/QData/TextAttack
	```
- [PyPi](https://pypi.org/project/textattack) (📥 43K / month):
	```
	pip install textattack
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/adversarial-robustness-toolbox">ART</a></b> (🥉23 ·  ⭐ 2.5K) - 对抗性鲁棒性工具箱（ART）- 用于机器学习的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/adversarial-robustness-toolbox) (👨‍💻 87 · 🔀 690 · 📦 160 · 📋 590 - 9% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/Trusted-AI/adversarial-robustness-toolbox
	```
- [PyPi](https://pypi.org/project/adversarial-robustness-toolbox) (📥 4.4K / month):
	```
	pip install adversarial-robustness-toolbox
	```
</details>
<details><summary><b><a href="https://github.com/BorealisAI/advertorch">advertorch</a></b> (🥉18 ·  ⭐ 930) - 对抗性鲁棒性研究的工具箱。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BorealisAI/advertorch) (👨‍💻 18 · 🔀 150 · 📦 50 · 📋 47 - 29% open · ⏱️ 30.07.2021):

	```
	git clone https://github.com/BorealisAI/advertorch
	```
- [PyPi](https://pypi.org/project/advertorch) (📥 550 / month):
	```
	pip install advertorch
	```
</details>
<details><summary><b><a href="https://github.com/MadryLab/robustness">robustness</a></b> (🥉18 ·  ⭐ 600 · 💤) - 一个用于实验，训练和评估神经网络的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MadryLab/robustness) (👨‍💻 12 · 🔀 110 · 📦 62 · 📋 64 - 17% open · ⏱️ 04.03.2021):

	```
	git clone https://github.com/MadryLab/robustness
	```
- [PyPi](https://pypi.org/project/robustness) (📥 2.7K / month):
	```
	pip install robustness
	```
</details>
<details><summary><b><a href="https://github.com/advboxes/AdvBox">AdvBox</a></b> (🥉16 ·  ⭐ 1.2K) - Advbox是一个工具箱，用于生成对抗示例。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/advboxes/AdvBox) (👨‍💻 19 · 🔀 240 · 📋 33 - 12% open · ⏱️ 03.05.2021):

	```
	git clone https://github.com/advboxes/AdvBox
	```
- [PyPi](https://pypi.org/project/advbox) (📥 46 / month):
	```
	pip install advbox
	```
</details>
<br>

## GPU实用程序

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_需要并利用CUDA / GPU系统功能来优化数据处理和机器学习任务的库。_

<details><summary><b><a href="https://github.com/cupy/cupy">CuPy</a></b> (🥇31 ·  ⭐ 5.4K) - CUDA加速了与NumPy兼容的数组库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cupy/cupy) (👨‍💻 270 · 🔀 480 · 📥 22K · 📦 840 · 📋 1.5K - 21% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/cupy/cupy
	```
- [PyPi](https://pypi.org/project/cupy) (📥 100K / month):
	```
	pip install cupy
	```
- [Conda](https://anaconda.org/conda-forge/cupy) (📥 950K · ⏱️ 02.10.2021):
	```
	conda install -c conda-forge cupy
	```
- [Docker Hub](https://hub.docker.com/r/cupy/cupy) (📥 53K · ⭐ 7 · ⏱️ 30.09.2021):
	```
	docker pull cupy/cupy
	```
</details>
<details><summary><b><a href="https://github.com/wookayin/gpustat">gpustat</a></b> (🥇27 ·  ⭐ 2.6K) - 一个简单的命令行实用程序，用于查询和监控GPU状态。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wookayin/gpustat) (👨‍💻 12 · 🔀 200 · 📦 1.3K · 📋 71 - 23% open · ⏱️ 05.08.2021):

	```
	git clone https://github.com/wookayin/gpustat
	```
- [PyPi](https://pypi.org/project/gpustat) (📥 300K / month):
	```
	pip install gpustat
	```
- [Conda](https://anaconda.org/conda-forge/gpustat) (📥 75K · ⏱️ 24.11.2020):
	```
	conda install -c conda-forge gpustat
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/apex">Apex</a></b> (🥈23 ·  ⭐ 5.8K) - PyTorch扩展：易于实现混合精度和分布式的工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NVIDIA/apex) (👨‍💻 86 · 🔀 800 · 📦 740 · 📋 880 - 55% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/NVIDIA/apex
	```
- [Conda](https://anaconda.org/conda-forge/nvidia-apex) (📥 64K · ⏱️ 22.04.2021):
	```
	conda install -c conda-forge nvidia-apex
	```
</details>
<details><summary><b><a href="https://github.com/anderskm/gputil">GPUtil</a></b> (🥈23 ·  ⭐ 770 · 💀) - 一个Python模块，用于从NVIDA GPU获取GPU状态。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/anderskm/gputil) (👨‍💻 13 · 🔀 86 · 📦 1.5K · 📋 25 - 44% open · ⏱️ 16.08.2019):

	```
	git clone https://github.com/anderskm/gputil
	```
- [PyPi](https://pypi.org/project/gputil) (📥 340K / month):
	```
	pip install gputil
	```
</details>
<details><summary><b><a href="https://github.com/fbcotter/py3nvml">py3nvml</a></b> (🥈23 ·  ⭐ 190) - NVML库的Python3接口。在内部获取NVIDIA GPU状态。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/fbcotter/py3nvml) (👨‍💻 8 · 🔀 25 · 📦 320 · 📋 12 - 16% open · ⏱️ 06.09.2021):

	```
	git clone https://github.com/fbcotter/py3nvml
	```
- [PyPi](https://pypi.org/project/py3nvml) (📥 120K / month):
	```
	pip install py3nvml
	```
- [Conda](https://anaconda.org/conda-forge/py3nvml) (📥 22K · ⏱️ 10.10.2020):
	```
	conda install -c conda-forge py3nvml
	```
</details>
<details><summary><b><a href="https://github.com/inducer/pycuda">PyCUDA</a></b> (🥈21 ·  ⭐ 1.2K) - 适用于Python的CUDA集成，有着出色的功能。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/inducer/pycuda) (👨‍💻 74 · 🔀 240 · 📦 1K · 📋 200 - 27% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/inducer/pycuda
	```
- [PyPi](https://pypi.org/project/pycuda) (📥 30K / month):
	```
	pip install pycuda
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cudf">cuDF</a></b> (🥈19 ·  ⭐ 4.2K) - cuDF-GPU DataFrame库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cudf) (👨‍💻 220 · 🔀 550 · 📋 4K - 14% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/rapidsai/cudf
	```
- [PyPi](https://pypi.org/project/cudf) (📥 1K / month):
	```
	pip install cudf
	```
</details>
<details><summary><b><a href="https://github.com/arrayfire/arrayfire">ArrayFire</a></b> (🥈19 ·  ⭐ 3.6K) - ArrayFire：通用GPU库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/arrayfire/arrayfire) (👨‍💻 82 · 🔀 480 · 📥 1.6K · 📋 1.5K - 15% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/arrayfire/arrayfire
	```
- [PyPi](https://pypi.org/project/arrayfire) (📥 540 / month):
	```
	pip install arrayfire
	```
</details>
<details><summary><b><a href="https://github.com/lebedov/scikit-cuda">scikit-cuda</a></b> (🥈19 ·  ⭐ 860) - GPU工具库的python接口。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lebedov/scikit-cuda) (👨‍💻 45 · 🔀 160 · 📦 140 · 📋 220 - 22% open · ⏱️ 13.07.2021):

	```
	git clone https://github.com/lebedov/scikit-cuda
	```
- [PyPi](https://pypi.org/project/scikit-cuda) (📥 730 / month):
	```
	pip install scikit-cuda
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cuml">cuML</a></b> (🥉18 ·  ⭐ 2.4K) - cuML-RAPIDS机器学习库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cuml) (👨‍💻 140 · 🔀 360 · 📋 1.8K - 32% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/rapidsai/cuml
	```
- [PyPi](https://pypi.org/project/cuml) (📥 560 / month):
	```
	pip install cuml
	```
</details>
<details><summary><b><a href="https://github.com/KomputeProject/kompute">Vulkan Kompute</a></b> (🥉18 ·  ⭐ 580) - 适用于跨供应商的通用GPU计算框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/KomputeProject/kompute) (👨‍💻 15 · 🔀 46 · 📥 90 · 📦 2 · 📋 160 - 32% open · ⏱️ 29.09.2021):

	```
	git clone https://github.com/EthicalML/vulkan-kompute
	```
- [PyPi](https://pypi.org/project/kp) (📥 150 / month):
	```
	pip install kp
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/DALI">DALI</a></b> (🥉17 ·  ⭐ 3.5K) - GPU加速的库，其中包含高度优化的构建块。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/NVIDIA/DALI) (👨‍💻 63 · 🔀 430 · 📋 1K - 12% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/NVIDIA/DALI
	```
</details>
<details><summary><b><a href="https://github.com/BlazingDB/blazingsql">BlazingSQL</a></b> (🥉17 ·  ⭐ 1.6K) - BlazingSQL是一种用于GPU的轻量级，GPU加速的引擎。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/BlazingDB/blazingsql) (👨‍💻 47 · 🔀 150 · 📋 700 - 16% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/BlazingDB/blazingsql
	```
- [Conda](https://anaconda.org/blazingsql/blazingsql-protocol) (📥 940 · ⏱️ 11.11.2019):
	```
	conda install -c blazingsql blazingsql-protocol
	```
</details>
<details><summary><b><a href="https://github.com/nicolargo/nvidia-ml-py3">nvidia-ml-py3</a></b> (🥉17 ·  ⭐ 69 · 💀) - NVIDIA Management Library的Python3接口。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nicolargo/nvidia-ml-py3) (👨‍💻 2 · 🔀 15 · 📦 4.2K · ⏱️ 06.03.2019):

	```
	git clone https://github.com/nicolargo/nvidia-ml-py3
	```
- [PyPi](https://pypi.org/project/nvidia-ml-py3) (📥 530K / month):
	```
	pip install nvidia-ml-py3
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cugraph">cuGraph</a></b> (🥉16 ·  ⭐ 820) - cuGraph-RAPIDS图形分析库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cugraph) (👨‍💻 68 · 🔀 160 · 📋 700 - 8% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/rapidsai/cugraph
	```
- [PyPi](https://pypi.org/project/cugraph) (📥 140 / month):
	```
	pip install cugraph
	```
</details>
<details><summary><b><a href="https://github.com/Santosh-Gupta/SpeedTorch">SpeedTorch</a></b> (🥉14 ·  ⭐ 630 · 💀) - 用于更快的Pytorch中CPU-GPU传输的工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Santosh-Gupta/SpeedTorch) (👨‍💻 3 · 🔀 38 · 📦 3 · 📋 5 - 60% open · ⏱️ 21.02.2020):

	```
	git clone https://github.com/Santosh-Gupta/SpeedTorch
	```
- [PyPi](https://pypi.org/project/SpeedTorch) (📥 81 / month):
	```
	pip install SpeedTorch
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cusignal">cuSignal</a></b> (🥉14 ·  ⭐ 530) - GPU加速信号处理。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cusignal) (👨‍💻 35 · 🔀 76 · 📋 120 - 8% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/rapidsai/cusignal
	```
</details>
<details><summary><b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉12 ·  ⭐ 140) - jupyter/ipython实验容器。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/stas00/ipyexperiments) (👨‍💻 3 · 🔀 10 · 📦 5 · ⏱️ 16.09.2021):

	```
	git clone https://github.com/stas00/ipyexperiments
	```
- [PyPi](https://pypi.org/project/ipyexperiments) (📥 160 / month):
	```
	pip install ipyexperiments
	```
</details>
<br>

## Tensorflow实用程序

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_TensorFlow的拓展工具库。_

<details><summary><b><a href="https://github.com/tensorflow/addons">TF Addons</a></b> (🥇34 ·  ⭐ 1.4K) - 由TensorFlow 2.x维护的有用额外功能。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/addons) (👨‍💻 180 · 🔀 470 · 📦 4.3K · 📋 850 - 19% open · ⏱️ 09.10.2021):

	```
	git clone https://github.com/tensorflow/addons
	```
- [PyPi](https://pypi.org/project/tensorflow-addons) (📥 12M / month):
	```
	pip install tensorflow-addons
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tensor2tensor">tensor2tensor</a></b> (🥇32 ·  ⭐ 12K) - 设计深度学习模型和数据集的库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensor2tensor) (👨‍💻 240 · 🔀 2.9K · 📦 1K · 📋 1.2K - 45% open · ⏱️ 17.09.2021):

	```
	git clone https://github.com/tensorflow/tensor2tensor
	```
- [PyPi](https://pypi.org/project/tensor2tensor) (📥 390K / month):
	```
	pip install tensor2tensor
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/hub">tensorflow-hub</a></b> (🥈31 ·  ⭐ 3K) - 通过重用部分库来进行迁移学习的库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/hub) (👨‍💻 77 · 🔀 1.6K · 📦 8.6K · 📋 610 - 1% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/tensorflow/hub
	```
- [PyPi](https://pypi.org/project/tensorflow-hub) (📥 3.1M / month):
	```
	pip install tensorflow-hub
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-hub) (📥 58K · ⏱️ 18.04.2021):
	```
	conda install -c conda-forge tensorflow-hub
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-optimization">TF Model Optimization</a></b> (🥈29 ·  ⭐ 1.1K) - 用于优化ML模型以进行部署的工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/model-optimization) (👨‍💻 62 · 🔀 240 · 📦 1.2K · 📋 250 - 45% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/tensorflow/model-optimization
	```
- [PyPi](https://pypi.org/project/tensorflow-model-optimization) (📥 180K / month):
	```
	pip install tensorflow-model-optimization
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/transform">TensorFlow Transform</a></b> (🥈29 ·  ⭐ 880) - 输入管道框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/transform) (👨‍💻 27 · 🔀 170 · 📦 560 · 📋 160 - 11% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/tensorflow/transform
	```
- [PyPi](https://pypi.org/project/tensorflow-transform) (📥 13M / month):
	```
	pip install tensorflow-transform
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/cloud">TensorFlow Cloud</a></b> (🥉26 ·  ⭐ 310) - TensorFlow Cloud存储库提供的API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/cloud) (👨‍💻 25 · 🔀 58 · 📦 98 · 📋 76 - 65% open · ⏱️ 07.09.2021):

	```
	git clone https://github.com/tensorflow/cloud
	```
- [PyPi](https://pypi.org/project/tensorflow-cloud) (📥 710K / month):
	```
	pip install tensorflow-cloud
	```
</details>
<details><summary><b><a href="https://github.com/qubvel/efficientnet">efficientnet</a></b> (🥉25 ·  ⭐ 1.9K) - EfficientNet模型的实现。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/qubvel/efficientnet) (👨‍💻 10 · 🔀 420 · 📥 190K · 📦 760 · 📋 110 - 47% open · ⏱️ 16.07.2021):

	```
	git clone https://github.com/qubvel/efficientnet
	```
- [PyPi](https://pypi.org/project/efficientnet) (📥 94K / month):
	```
	pip install efficientnet
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/neural-structured-learning">Neural Structured Learning</a></b> (🥉24 ·  ⭐ 870) - 用结构化信号训练神经模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/neural-structured-learning) (👨‍💻 30 · 🔀 160 · 📦 110 · 📋 59 - 3% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/tensorflow/neural-structured-learning
	```
- [PyPi](https://pypi.org/project/neural-structured-learning) (📥 11K / month):
	```
	pip install neural-structured-learning
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/io">TensorFlow I/O</a></b> (🥉24 ·  ⭐ 500) - Dataset, streaming, and file system extensions.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/io) (👨‍💻 78 · 🔀 180 · 📋 460 - 32% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/tensorflow/io
	```
- [PyPi](https://pypi.org/project/tensorflow-io) (📥 140K / month):
	```
	pip install tensorflow-io
	```
</details>
<details><summary><b><a href="https://github.com/taehoonlee/tensornets">TensorNets</a></b> (🥉18 ·  ⭐ 990 · 💤) - 具有预先训练的权重的高级网络定义。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/taehoonlee/tensornets) (👨‍💻 6 · 🔀 180 · 📦 41 · 📋 58 - 27% open · ⏱️ 02.01.2021):

	```
	git clone https://github.com/taehoonlee/tensornets
	```
- [PyPi](https://pypi.org/project/tensornets) (📥 140 / month):
	```
	pip install tensornets
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/compression">TF Compression</a></b> (🥉18 ·  ⭐ 530) - TensorFlow中的数据压缩。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/compression) (👨‍💻 10 · 🔀 190 · 📋 74 - 4% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/tensorflow/compression
	```
- [PyPi](https://pypi.org/project/tensorflow-compression) (📥 710 / month):
	```
	pip install tensorflow-compression
	```
</details>
<details><summary><b><a href="https://github.com/geffy/tffm">tffm</a></b> (🥉17 ·  ⭐ 770 · 💀) - 任意阶乘分解机的TensorFlow实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geffy/tffm) (👨‍💻 10 · 🔀 180 · 📦 11 · 📋 39 - 43% open · ⏱️ 22.05.2020):

	```
	git clone https://github.com/geffy/tffm
	```
- [PyPi](https://pypi.org/project/tffm) (📥 1.9K / month):
	```
	pip install tffm
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/saliency">Saliency</a></b> (🥉16 ·  ⭐ 720) - 与框架无关的实现，可实现最新的显着性。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PAIR-code/saliency) (👨‍💻 14 · 🔀 150 · 📦 18 · ⏱️ 28.07.2021):

	```
	git clone https://github.com/PAIR-code/saliency
	```
- [PyPi](https://pypi.org/project/saliency) (📥 550 / month):
	```
	pip install saliency
	```
</details>
<br>

## Sklearn实用程序

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_scikit-learn的拓展工具库。_

<details><summary><b><a href="https://github.com/scikit-learn-contrib/imbalanced-learn">imbalanced-learn</a></b> (🥇31 ·  ⭐ 5.5K) - 一个解决不平衡类别数据建模的Python程序包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/imbalanced-learn) (👨‍💻 58 · 🔀 1.1K · 📦 7.5K · 📋 480 - 8% open · ⏱️ 29.09.2021):

	```
	git clone https://github.com/scikit-learn-contrib/imbalanced-learn
	```
- [PyPi](https://pypi.org/project/imbalanced-learn) (📥 2.2M / month):
	```
	pip install imbalanced-learn
	```
- [Conda](https://anaconda.org/conda-forge/imbalanced-learn) (📥 160K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge imbalanced-learn
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/mlxtend">MLxtend</a></b> (🥇30 ·  ⭐ 3.7K) - 用于Python数据的扩展和帮助程序模块库。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rasbt/mlxtend) (👨‍💻 85 · 🔀 720 · 📦 4.3K · 📋 380 - 22% open · ⏱️ 02.09.2021):

	```
	git clone https://github.com/rasbt/mlxtend
	```
- [PyPi](https://pypi.org/project/mlxtend) (📥 1.4M / month):
	```
	pip install mlxtend
	```
- [Conda](https://anaconda.org/conda-forge/mlxtend) (📥 180K · ⏱️ 03.09.2021):
	```
	conda install -c conda-forge mlxtend
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/category_encoders">category_encoders</a></b> (🥈25 ·  ⭐ 1.8K) - A library of sklearn compatible categorical variable.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/category_encoders) (👨‍💻 43 · 🔀 320 · 📋 220 - 34% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/scikit-learn-contrib/category_encoders
	```
- [PyPi](https://pypi.org/project/category_encoders) (📥 710K / month):
	```
	pip install category_encoders
	```
- [Conda](https://anaconda.org/conda-forge/category_encoders) (📥 120K · ⏱️ 29.04.2020):
	```
	conda install -c conda-forge category_encoders
	```
</details>
<details><summary><b><a href="https://github.com/iskandr/fancyimpute">fancyimpute</a></b> (🥈24 ·  ⭐ 1K) - 多元插补和矩阵补全算法。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/iskandr/fancyimpute) (👨‍💻 11 · 🔀 150 · 📦 1.1K · 📋 110 - 3% open · ⏱️ 26.08.2021):

	```
	git clone https://github.com/iskandr/fancyimpute
	```
- [PyPi](https://pypi.org/project/fancyimpute) (📥 7.4K / month):
	```
	pip install fancyimpute
	```
</details>
<details><summary><b><a href="https://github.com/guofei9987/scikit-opt">scikit-opt</a></b> (🥈23 ·  ⭐ 2.6K) - 遗传算法，粒子群优化等实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/guofei9987/scikit-opt) (👨‍💻 13 · 🔀 610 · 📦 48 · 📋 120 - 20% open · ⏱️ 26.09.2021):

	```
	git clone https://github.com/guofei9987/scikit-opt
	```
- [PyPi](https://pypi.org/project/scikit-opt) (📥 1K / month):
	```
	pip install scikit-opt
	```
</details>
<details><summary><b><a href="https://github.com/scikit-multilearn/scikit-multilearn">scikit-multilearn</a></b> (🥈23 ·  ⭐ 690 · 💀) - 基于scikit-learn的多标签等模块。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-multilearn/scikit-multilearn) (👨‍💻 15 · 🔀 130 · 📦 550 · 📋 160 - 42% open · ⏱️ 21.05.2019):

	```
	git clone https://github.com/scikit-multilearn/scikit-multilearn
	```
- [PyPi](https://pypi.org/project/scikit-multilearn) (📥 84K / month):
	```
	pip install scikit-multilearn
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/lightning">sklearn-contrib-lightning</a></b> (🥈21 ·  ⭐ 1.5K) - 大规模线性分类，回归分析等。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/lightning) (👨‍💻 17 · 🔀 170 · 📥 71 · 📦 87 · 📋 84 - 52% open · ⏱️ 15.06.2021):

	```
	git clone https://github.com/scikit-learn-contrib/lightning
	```
- [PyPi](https://pypi.org/project/sklearn-contrib-lightning) (📥 2.8K / month):
	```
	pip install sklearn-contrib-lightning
	```
- [Conda](https://anaconda.org/conda-forge/sklearn-contrib-lightning) (📥 160K · ⏱️ 20.12.2020):
	```
	conda install -c conda-forge sklearn-contrib-lightning
	```
</details>
<details><summary><b><a href="https://github.com/koaning/scikit-lego">scikit-lego</a></b> (🥈21 ·  ⭐ 620) - scikit学习管道的额外块。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/koaning/scikit-lego) (👨‍💻 47 · 🔀 75 · 📦 33 · 📋 230 - 13% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/koaning/scikit-lego
	```
- [PyPi](https://pypi.org/project/scikit-lego) (📥 25K / month):
	```
	pip install scikit-lego
	```
- [Conda](https://anaconda.org/conda-forge/scikit-lego) (📥 15K · ⏱️ 03.07.2021):
	```
	conda install -c conda-forge scikit-lego
	```
</details>
<details><summary><b><a href="https://github.com/trent-b/iterative-stratification">iterative-stratification</a></b> (🥈21 ·  ⭐ 600) - scikit-learn交叉验证器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/trent-b/iterative-stratification) (👨‍💻 5 · 🔀 56 · 📦 170 · 📋 17 - 17% open · ⏱️ 03.10.2021):

	```
	git clone https://github.com/trent-b/iterative-stratification
	```
- [PyPi](https://pypi.org/project/iterative-stratification) (📥 5.8K / month):
	```
	pip install iterative-stratification
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/combo">combo</a></b> (🥈21 ·  ⭐ 540) - （AAAI'20）用于机器学习模型的Python工具箱。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code>xgboost</code></summary>

- [GitHub](https://github.com/yzhao062/combo) (🔀 91 · 📦 400 · 📋 12 - 75% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/yzhao062/combo
	```
- [PyPi](https://pypi.org/project/combo) (📥 47K / month):
	```
	pip install combo
	```
</details>
<details><summary><b><a href="https://github.com/TeamHG-Memex/sklearn-crfsuite">sklearn-crfsuite</a></b> (🥉20 ·  ⭐ 380 · 💀) - 用于CRFsuite的scikit-learn启发式API。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/TeamHG-Memex/sklearn-crfsuite) (👨‍💻 6 · 🔀 160 · 📦 3.1K · 📋 52 - 55% open · ⏱️ 05.12.2019):

	```
	git clone https://github.com/TeamHG-Memex/sklearn-crfsuite
	```
- [PyPi](https://pypi.org/project/sklearn-crfsuite) (📥 120K / month):
	```
	pip install sklearn-crfsuite
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/skope-rules">skope-rules</a></b> (🥉19 ·  ⭐ 420 · 💤) - 使用Python中的逻辑规则进行机器学习。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/skope-rules) (👨‍💻 18 · 🔀 68 · 📦 48 · 📋 27 - 81% open · ⏱️ 23.10.2020):

	```
	git clone https://github.com/scikit-learn-contrib/skope-rules
	```
- [PyPi](https://pypi.org/project/skope-rules) (📥 73K / month):
	```
	pip install skope-rules
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/DESlib">DESlib</a></b> (🥉18 ·  ⭐ 350) - 一个用于动态分类器和集成选择的Python库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/DESlib) (👨‍💻 13 · 🔀 54 · 📦 22 · 📋 140 - 7% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/scikit-learn-contrib/DESlib
	```
- [PyPi](https://pypi.org/project/deslib) (📥 1.2K / month):
	```
	pip install deslib
	```
</details>
<details><summary><b><a href="https://github.com/scikit-tda/scikit-tda">scikit-tda</a></b> (🥉18 ·  ⭐ 310) - Python的拓扑数据分析。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-tda/scikit-tda) (👨‍💻 3 · 🔀 37 · 📦 21 · 📋 16 - 75% open · ⏱️ 03.08.2021):

	```
	git clone https://github.com/scikit-tda/scikit-tda
	```
- [PyPi](https://pypi.org/project/scikit-tda) (📥 4.1K / month):
	```
	pip install scikit-tda
	```
</details>
<details><summary><b><a href="https://github.com/skggm/skggm">skggm</a></b> (🥉17 ·  ⭐ 190 · 💤) - 通用图形模型的Scikit学习兼容估计。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/skggm/skggm) (👨‍💻 5 · 🔀 34 · 📦 8 · 📋 75 - 37% open · ⏱️ 24.12.2020):

	```
	git clone https://github.com/skggm/skggm
	```
- [PyPi](https://pypi.org/project/skggm) (📥 110 / month):
	```
	pip install skggm
	```
</details>
<details><summary><b><a href="https://github.com/mathurinm/celer">celer</a></b> (🥉15 ·  ⭐ 120) - L1型问题的快速求解器：Lasso，稀疏Logisitic回归等<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mathurinm/celer) (👨‍💻 9 · 🔀 22 · 📦 8 · 📋 68 - 20% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/mathurinm/celer
	```
- [PyPi](https://pypi.org/project/celer) (📥 220 / month):
	```
	pip install celer
	```
</details>
<details><summary><b><a href="https://github.com/amueller/dabl">dabl</a></b> (🥉12 ·  ⭐ 110) - 数据分析基准库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/amueller/dabl) (👨‍💻 21 · 🔀 9 · ⏱️ 09.07.2021):

	```
	git clone https://github.com/amueller/dabl
	```
- [PyPi](https://pypi.org/project/dabl) (📥 1.7K / month):
	```
	pip install dabl
	```
</details>
<br>

## Pytorch实用程序

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Pytorch的拓展工具库。_

<details><summary><b><a href="https://github.com/jettify/pytorch-optimizer">pytorch-optimizer</a></b> (🥇27 ·  ⭐ 2.1K) - torch-optimizer - pytorch的优化器集合。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jettify/pytorch-optimizer) (👨‍💻 24 · 🔀 200 · 📦 330 · 📋 39 - 30% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/jettify/pytorch-optimizer
	```
- [PyPi](https://pypi.org/project/torch_optimizer) (📥 70K / month):
	```
	pip install torch_optimizer
	```
</details>
<details><summary><b><a href="https://github.com/Cadene/pretrained-models.pytorch">pretrainedmodels</a></b> (🥇26 ·  ⭐ 8.2K · 💀) - pytorch预训练的ConvNets：NASNet，ResNeXt等<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Cadene/pretrained-models.pytorch) (👨‍💻 22 · 🔀 1.7K · 📦 1.2K · 📋 170 - 47% open · ⏱️ 16.04.2020):

	```
	git clone https://github.com/Cadene/pretrained-models.pytorch
	```
- [PyPi](https://pypi.org/project/pretrainedmodels) (📥 46K / month):
	```
	pip install pretrainedmodels
	```
</details>
<details><summary><b><a href="https://github.com/KevinMusgrave/pytorch-metric-learning">PML</a></b> (🥇25 ·  ⭐ 3.7K) - 在应用程序中使用深度度量学习的最简单方法。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/KevinMusgrave/pytorch-metric-learning) (👨‍💻 19 · 🔀 460 · 📦 140 · 📋 290 - 17% open · ⏱️ 03.08.2021):

	```
	git clone https://github.com/KevinMusgrave/pytorch-metric-learning
	```
- [PyPi](https://pypi.org/project/pytorch-metric-learning) (📥 9.7K / month):
	```
	pip install pytorch-metric-learning
	```
- [Conda](https://anaconda.org/metric-learning/pytorch-metric-learning) (📥 4.3K · ⏱️ 10.05.2021):
	```
	conda install -c metric-learning pytorch-metric-learning
	```
</details>
<details><summary><b><a href="https://github.com/sksq96/pytorch-summary">pytorch-summary</a></b> (🥈23 ·  ⭐ 3.3K) - PyTorch中的模型摘要类似于`model.summary（）`。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sksq96/pytorch-summary) (👨‍💻 11 · 🔀 370 · 📦 3.4K · 📋 130 - 70% open · ⏱️ 10.05.2021):

	```
	git clone https://github.com/sksq96/pytorch-summary
	```
- [PyPi](https://pypi.org/project/torchsummary) (📥 110K / month):
	```
	pip install torchsummary
	```
</details>
<details><summary><b><a href="https://github.com/asappresearch/sru">SRU</a></b> (🥈23 ·  ⭐ 2K) - 与CNN一样快地训练RNN（https://arxiv.org/abs/1709.02755）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/asappresearch/sru) (👨‍💻 21 · 🔀 290 · 📦 16 · 📋 120 - 43% open · ⏱️ 19.05.2021):

	```
	git clone https://github.com/asappresearch/sru
	```
- [PyPi](https://pypi.org/project/sru) (📥 3.1K / month):
	```
	pip install sru
	```
</details>
<details><summary><b><a href="https://github.com/lukemelas/EfficientNet-PyTorch">EfficientNet-PyTorch</a></b> (🥈22 ·  ⭐ 6.5K) - EfficientNet等模型的PyTorch实现<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lukemelas/EfficientNet-PyTorch) (👨‍💻 24 · 🔀 1.3K · 📥 860K · 📋 260 - 47% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/lukemelas/EfficientNet-PyTorch
	```
- [PyPi](https://pypi.org/project/efficientnet-pytorch) (📥 590K / month):
	```
	pip install efficientnet-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/rtqichen/torchdiffeq">torchdiffeq</a></b> (🥈22 ·  ⭐ 3.7K) - 具有完整GPU支持的可微分ODE求解器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rtqichen/torchdiffeq) (👨‍💻 21 · 🔀 630 · 📦 150 · 📋 150 - 15% open · ⏱️ 22.09.2021):

	```
	git clone https://github.com/rtqichen/torchdiffeq
	```
- [PyPi](https://pypi.org/project/torchdiffeq) (📥 5.8K / month):
	```
	pip install torchdiffeq
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/reformer-pytorch">reformer-pytorch</a></b> (🥈22 ·  ⭐ 1.6K) - Reformer，Pytorch中高效的transformer实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/reformer-pytorch) (👨‍💻 10 · 🔀 210 · 📋 120 - 10% open · ⏱️ 25.08.2021):

	```
	git clone https://github.com/lucidrains/reformer-pytorch
	```
- [PyPi](https://pypi.org/project/reformer-pytorch) (📥 17K / month):
	```
	pip install reformer-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/tristandeleu/pytorch-meta">Torchmeta</a></b> (🥈22 ·  ⭐ 1.5K) - 少量学习的扩展程序和数据加载器的集合。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tristandeleu/pytorch-meta) (👨‍💻 12 · 🔀 170 · 📦 62 · 📋 120 - 24% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/tristandeleu/pytorch-meta
	```
- [PyPi](https://pypi.org/project/torchmeta) (📥 50K / month):
	```
	pip install torchmeta
	```
</details>
<details><summary><b><a href="https://github.com/dreamquark-ai/tabnet">TabNet</a></b> (🥈21 ·  ⭐ 1.3K) - Efficient Neural Architecture Search的Pytorch实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dreamquark-ai/tabnet) (👨‍💻 18 · 🔀 260 · 📋 160 - 12% open · ⏱️ 27.05.2021):

	```
	git clone https://github.com/dreamquark-ai/tabnet
	```
- [PyPi](https://pypi.org/project/pytorch-tabnet) (📥 17K / month):
	```
	pip install pytorch-tabnet
	```
</details>
<details><summary><b><a href="https://github.com/BloodAxe/pytorch-toolbelt">Pytorch Toolbelt</a></b> (🥈21 ·  ⭐ 1.1K) - PyTorch扩展用于快速研发原型和Kaggle实验。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BloodAxe/pytorch-toolbelt) (👨‍💻 6 · 🔀 80 · 📋 21 - 14% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/BloodAxe/pytorch-toolbelt
	```
- [PyPi](https://pypi.org/project/pytorch_toolbelt) (📥 9.7K / month):
	```
	pip install pytorch_toolbelt
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_scatter">torch-scatter</a></b> (🥉20 ·  ⭐ 780) - 优化图聚类的PyTorch扩展库<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_scatter) (👨‍💻 17 · 🔀 86 · 📋 210 - 10% open · ⏱️ 16.09.2021):

	```
	git clone https://github.com/rusty1s/pytorch_scatter
	```
- [PyPi](https://pypi.org/project/torch-scatter) (📥 27K / month):
	```
	pip install torch-scatter
	```
</details>
<details><summary><b><a href="https://github.com/parrt/tensor-sensor">Tensor Sensor</a></b> (🥉20 ·  ⭐ 600 · 📈) - 该库的目标是为numpy/pytorch矩阵代数表达式生成更有用的异常消息。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/parrt/tensor-sensor) (👨‍💻 3 · 🔀 30 · 📦 5 · 📋 23 - 39% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/parrt/tensor-sensor
	```
- [PyPi](https://pypi.org/project/tensor-sensor) (📥 5.6K / month):
	```
	pip install tensor-sensor
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_sparse">PyTorch Sparse</a></b> (🥉20 ·  ⭐ 500) - 优化图聚类的PyTorch扩展库<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_sparse) (👨‍💻 17 · 🔀 62 · 📋 140 - 15% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/rusty1s/pytorch_sparse
	```
- [PyPi](https://pypi.org/project/torch-sparse) (📥 21K / month):
	```
	pip install torch-sparse
	```
</details>
<details><summary><b><a href="https://github.com/GRAAL-Research/poutyne">Poutyne</a></b> (🥉20 ·  ⭐ 500) - PyTorch的简化框架和实用程序。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/GRAAL-Research/poutyne) (👨‍💻 16 · 🔀 51 · 📦 69 · 📋 44 - 13% open · ⏱️ 12.09.2021):

	```
	git clone https://github.com/GRAAL-Research/poutyne
	```
- [PyPi](https://pypi.org/project/poutyne) (📥 5.5K / month):
	```
	pip install poutyne
	```
</details>
<details><summary><b><a href="https://github.com/Luolc/AdaBound">AdaBound</a></b> (🥉19 ·  ⭐ 2.9K · 💀) - 训练速度与Adam一样快且与SGD一样好的优化器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Luolc/AdaBound) (👨‍💻 2 · 🔀 320 · 📦 120 · 📋 23 - 69% open · ⏱️ 06.03.2019):

	```
	git clone https://github.com/Luolc/AdaBound
	```
- [PyPi](https://pypi.org/project/adabound) (📥 1.1K / month):
	```
	pip install adabound
	```
</details>
<details><summary><b><a href="https://github.com/adobe/antialiased-cnns">Antialiased CNNs</a></b> (🥉19 ·  ⭐ 1.4K) - pip安装antialiased-cnns以提高稳定性等。<code><a href="https://tldrlegal.com/search?q=CC%20BY-NC-SA%204.0">❗️CC BY-NC-SA 4.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/adobe/antialiased-cnns) (👨‍💻 6 · 🔀 180 · 📦 7 · 📋 40 - 22% open · ⏱️ 29.09.2021):

	```
	git clone https://github.com/adobe/antialiased-cnns
	```
- [PyPi](https://pypi.org/project/antialiased-cnns) (📥 1.6K / month):
	```
	pip install antialiased-cnns
	```
</details>
<details><summary><b><a href="https://github.com/rwightman/gen-efficientnet-pytorch">EfficientNets</a></b> (🥉19 ·  ⭐ 1.4K) - 预训练的EfficientNet，EfficientNet-Lite，MixNet等<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rwightman/gen-efficientnet-pytorch) (👨‍💻 5 · 🔀 180 · 📦 77 · ⏱️ 08.07.2021):

	```
	git clone https://github.com/rwightman/gen-efficientnet-pytorch
	```
- [PyPi](https://pypi.org/project/geffnet) (📥 7.2K / month):
	```
	pip install geffnet
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/higher">Higher</a></b> (🥉19 ·  ⭐ 1.2K) - Higher是一个pytorch库，允许用户在跨训练循环而不是单个训练步骤的损失上获得更高阶的梯度。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/higher) (👨‍💻 9 · 🔀 87 · 📦 78 · 📋 88 - 43% open · ⏱️ 21.06.2021):

	```
	git clone https://github.com/facebookresearch/higher
	```
- [PyPi](https://pypi.org/project/higher) (📥 58K / month):
	```
	pip install higher
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/performer-pytorch">Performer Pytorch</a></b> (🥉18 ·  ⭐ 710) - Performer的实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/performer-pytorch) (👨‍💻 4 · 🔀 95 · 📦 30 · 📋 66 - 40% open · ⏱️ 21.08.2021):

	```
	git clone https://github.com/lucidrains/performer-pytorch
	```
- [PyPi](https://pypi.org/project/performer-pytorch) (📥 1.1K / month):
	```
	pip install performer-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/abhishekkrthakur/tez">Tez</a></b> (🥉18 ·  ⭐ 700 · 📈) - Tez是用于PyTorch的超级简单且轻巧的Trainer。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/abhishekkrthakur/tez) (🔀 100 · 📦 11 · 📋 23 - 60% open · ⏱️ 27.09.2021):

	```
	git clone https://github.com/abhishekkrthakur/tez
	```
- [PyPi](https://pypi.org/project/tez) (📥 1.2K / month):
	```
	pip install tez
	```
</details>
<details><summary><b><a href="https://github.com/geohot/tinygrad">tinygrad</a></b> (🥉16 ·  ⭐ 5K) - You like pytorch? You like micrograd? You love tinygrad!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geohot/tinygrad) (👨‍💻 50 · 🔀 550 · 📦 1 · 📋 80 - 20% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/geohot/tinygrad
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/lambda-networks">Lambda Networks</a></b> (🥉16 ·  ⭐ 1.5K · 💤) - LambdaNetworks的实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/lambda-networks) (👨‍💻 3 · 🔀 150 · 📦 3 · 📋 27 - 44% open · ⏱️ 18.11.2020):

	```
	git clone https://github.com/lucidrains/lambda-networks
	```
- [PyPi](https://pypi.org/project/lambda-networks) (📥 130 / month):
	```
	pip install lambda-networks
	```
</details>
<details><summary><b><a href="https://github.com/google-research/torchsde">torchsde</a></b> (🥉15 ·  ⭐ 850) - 具有GPU支持且高效的可微分SDE求解器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/torchsde) (👨‍💻 5 · 🔀 90 · 📦 8 · 📋 41 - 17% open · ⏱️ 26.07.2021):

	```
	git clone https://github.com/google-research/torchsde
	```
</details>
<details><summary><b><a href="https://github.com/achaiah/pywick">Pywick</a></b> (🥉15 ·  ⭐ 330) - 更高层次的pytorch神经网络训练库。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/achaiah/pywick) (👨‍💻 4 · 🔀 37 · 📦 5 · 📋 13 - 23% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/achaiah/pywick
	```
- [PyPi](https://pypi.org/project/pywick) (📥 77 / month):
	```
	pip install pywick
	```
</details>
<details><summary><b><a href="https://github.com/harvardnlp/pytorch-struct">Torch-Struct</a></b> (🥉14 ·  ⭐ 980) - 快速，通用和经过测试的微分结构化预测。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/harvardnlp/pytorch-struct) (👨‍💻 13 · 🔀 75 · 📋 47 - 44% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/harvardnlp/pytorch-struct
	```
</details>
<details><summary><b><a href="https://github.com/karpathy/micrograd">micrograd</a></b> (🥉13 ·  ⭐ 1.8K · 💀) - 一个微型的标量值autograd引擎和一个神经网络库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/karpathy/micrograd) (👨‍💻 2 · 🔀 140 · 📦 4 · 📋 5 - 40% open · ⏱️ 18.04.2020):

	```
	git clone https://github.com/karpathy/micrograd
	```
- [PyPi](https://pypi.org/project/micrograd) (📥 32 / month):
	```
	pip install micrograd
	```
</details>
<br>

## 数据库客户端

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于连接，操作和查询数据库的库。_

🔗&nbsp;<b><a href="https://github.com/HanXinzi2020/awesome-python-resources#数据库">Python DB Clients</a></b> ( ⭐ 1 · 🐣)  - Collection of database clients for python.

<br>

## 中文自然语言处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/fxsjy/jieba">jieba</a></b> (🥇31 ·  ⭐ 27K · 💀) - Chinese Words Segementation Utilities. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fxsjy/jieba) (👨‍💻 48 · 🔀 6.1K · 📦 11K · 📋 780 - 73% open · ⏱️ 15.02.2020):

	```
	git clone https://github.com/fxsjy/jieba
	```
- [PyPi](https://pypi.org/project/jieba) (📥 460K / month):
	```
	pip install jieba
	```
- [Conda](https://anaconda.org/conda-forge/jieba) (📥 94K · ⏱️ 30.05.2021):
	```
	conda install -c conda-forge jieba
	```
</details>
<details><summary><b><a href="https://github.com/isnowfy/snownlp">snownlp</a></b> (🥉21 ·  ⭐ 5.6K · 💀) - Python library for processing Chinese text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/isnowfy/snownlp) (👨‍💻 8 · 🔀 1.3K · 📦 710 · 📋 100 - 36% open · ⏱️ 19.01.2020):

	```
	git clone https://github.com/isnowfy/snownlp
	```
- [PyPi](https://pypi.org/project/snownlp) (📥 4.8K / month):
	```
	pip install snownlp
	```
</details>
<br>

## Others

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/scipy/scipy">scipy</a></b> (🥇42 ·  ⭐ 8.7K) - 用于数学，科学和工程的开源软件生态系统。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/scipy/scipy) (👨‍💻 1.2K · 🔀 3.8K · 📥 330K · 📦 410K · 📋 7.6K - 19% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/scipy/scipy
	```
- [PyPi](https://pypi.org/project/scipy) (📥 30M / month):
	```
	pip install scipy
	```
- [Conda](https://anaconda.org/conda-forge/scipy) (📥 18M · ⏱️ 10.10.2021):
	```
	conda install -c conda-forge scipy
	```
</details>
<details><summary><b><a href="https://github.com/sympy/sympy">SymPy</a></b> (🥇35 ·  ⭐ 8.5K) - 用纯Python编写的计算机代数系统。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sympy/sympy) (👨‍💻 1.1K · 🔀 3.4K · 📥 430K · 📦 36K · 📋 11K - 32% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/sympy/sympy
	```
- [PyPi](https://pypi.org/project/sympy) (📥 1.7M / month):
	```
	pip install sympy
	```
- [Conda](https://anaconda.org/conda-forge/sympy) (📥 1.7M · ⏱️ 09.10.2021):
	```
	conda install -c conda-forge sympy
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/pyod">PyOD</a></b> (🥇30 ·  ⭐ 4.9K) - （JMLR'19）用于可扩展离群值检测的Python工具箱。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/yzhao062/pyod) (👨‍💻 28 · 🔀 960 · 📦 880 · 📋 210 - 51% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/yzhao062/pyod
	```
- [PyPi](https://pypi.org/project/pyod) (📥 320K / month):
	```
	pip install pyod
	```
</details>
<details><summary><b><a href="https://github.com/simonw/datasette">Datasette</a></b> (🥇29 ·  ⭐ 5.5K) - 用于探索和发布数据的开源多功能工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/simonw/datasette) (👨‍💻 57 · 🔀 340 · 📥 32 · 📦 520 · 📋 1.1K - 25% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/simonw/datasette
	```
- [PyPi](https://pypi.org/project/datasette) (📥 120K / month):
	```
	pip install datasette
	```
</details>
<details><summary><b><a href="https://github.com/streamlit/streamlit">Streamlit</a></b> (🥈28 ·  ⭐ 16K) - Streamlit用Python构建数据应用程序的最快方法。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/streamlit/streamlit) (👨‍💻 120 · 🔀 1.4K · 📦 140 · 📋 2K - 27% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/streamlit/streamlit
	```
- [PyPi](https://pypi.org/project/streamlit) (📥 630K / month):
	```
	pip install streamlit
	```
</details>
<details><summary><b><a href="https://github.com/HIPS/autograd">Autograd</a></b> (🥈28 ·  ⭐ 5.5K · 💤) - 高效地计算导数的numpy代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HIPS/autograd) (👨‍💻 51 · 🔀 760 · 📦 2.5K · 📋 360 - 39% open · ⏱️ 03.03.2021):

	```
	git clone https://github.com/HIPS/autograd
	```
- [PyPi](https://pypi.org/project/autograd) (📥 1.3M / month):
	```
	pip install autograd
	```
- [Conda](https://anaconda.org/conda-forge/autograd) (📥 190K · ⏱️ 25.07.2019):
	```
	conda install -c conda-forge autograd
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/hdbscan">hdbscan</a></b> (🥈28 ·  ⭐ 2K) - HDBSCAN群集的高性能实现。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/hdbscan) (👨‍💻 72 · 🔀 340 · 📦 1K · 📋 390 - 62% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/scikit-learn-contrib/hdbscan
	```
- [PyPi](https://pypi.org/project/hdbscan) (📥 360K / month):
	```
	pip install hdbscan
	```
- [Conda](https://anaconda.org/conda-forge/hdbscan) (📥 880K · ⏱️ 14.02.2021):
	```
	conda install -c conda-forge hdbscan
	```
</details>
<details><summary><b><a href="https://github.com/carla-simulator/carla">carla</a></b> (🥈27 ·  ⭐ 6.6K) - 用于自动驾驶研究的开源模拟器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carla-simulator/carla) (👨‍💻 130 · 🔀 1.9K · 📦 91 · 📋 3.4K - 12% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/carla-simulator/carla
	```
- [PyPi](https://pypi.org/project/carla) (📥 1.9K / month):
	```
	pip install carla
	```
</details>
<details><summary><b><a href="https://github.com/deepchem/deepchem">DeepChem</a></b> (🥈26 ·  ⭐ 3.2K) - 在药物发现，量子化学，材料科学和生物学方面普及深度学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepchem/deepchem) (👨‍💻 170 · 🔀 1K · 📦 57 · 📋 1.3K - 29% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/deepchem/deepchem
	```
- [PyPi](https://pypi.org/project/deepchem) (📥 4.5K / month):
	```
	pip install deepchem
	```
</details>
<details><summary><b><a href="https://github.com/tableau/TabPy">TabPy</a></b> (🥈26 ·  ⭐ 1.1K) - 快速执行Python代码，并在Tableau可视化文件中显示结果。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tableau/TabPy) (👨‍💻 43 · 🔀 420 · 📦 76 · 📋 280 - 5% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/tableau/TabPy
	```
- [PyPi](https://pypi.org/project/tabpy) (📥 14K / month):
	```
	pip install tabpy
	```
</details>
<details><summary><b><a href="https://github.com/wireservice/agate">agate</a></b> (🥈26 ·  ⭐ 1.1K) - 为人而不是为机器优化的Python数据分析库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wireservice/agate) (👨‍💻 49 · 🔀 130 · 📦 640 · 📋 640 - 0% open · ⏱️ 15.07.2021):

	```
	git clone https://github.com/wireservice/agate
	```
- [PyPi](https://pypi.org/project/agate) (📥 710K / month):
	```
	pip install agate
	```
- [Conda](https://anaconda.org/conda-forge/agate) (📥 71K · ⏱️ 16.07.2021):
	```
	conda install -c conda-forge agate
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleHub">PaddleHub</a></b> (🥈25 ·  ⭐ 7K) - 基于PaddlePaddle的出色的预训练模型工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleHub) (👨‍💻 46 · 🔀 1.4K · 📥 560 · 📦 480 · 📋 930 - 34% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/PaddlePaddle/PaddleHub
	```
- [PyPi](https://pypi.org/project/paddlehub) (📥 8.8K / month):
	```
	pip install paddlehub
	```
</details>
<details><summary><b><a href="https://github.com/google/trax">Trax</a></b> (🥈25 ·  ⭐ 6.5K) - 借助清晰的代码和速度来进行深度学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/trax) (👨‍💻 71 · 🔀 640 · 📦 38 · 📋 200 - 39% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/google/trax
	```
- [PyPi](https://pypi.org/project/trax) (📥 3.1K / month):
	```
	pip install trax
	```
</details>
<details><summary><b><a href="https://github.com/serge-sans-paille/pythran">Pythran</a></b> (🥈25 ·  ⭐ 1.6K) - 用于数字内核的时间编译器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/serge-sans-paille/pythran) (👨‍💻 63 · 🔀 160 · 📦 70 · 📋 700 - 13% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/serge-sans-paille/pythran
	```
- [PyPi](https://pypi.org/project/pythran) (📥 49K / month):
	```
	pip install pythran
	```
- [Conda](https://anaconda.org/conda-forge/pythran) (📥 200K · ⏱️ 26.09.2021):
	```
	conda install -c conda-forge pythran
	```
</details>
<details><summary><b><a href="https://github.com/annoviko/pyclustering">pyclustering</a></b> (🥈25 ·  ⭐ 880 · 💤) - pyclustring是Python，C++数据挖掘库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/annoviko/pyclustering) (👨‍💻 26 · 🔀 200 · 📥 370 · 📦 230 · 📋 640 - 8% open · ⏱️ 12.02.2021):

	```
	git clone https://github.com/annoviko/pyclustering
	```
- [PyPi](https://pypi.org/project/pyclustering) (📥 45K / month):
	```
	pip install pyclustering
	```
- [Conda](https://anaconda.org/conda-forge/pyclustering) (📥 30K · ⏱️ 13.09.2021):
	```
	conda install -c conda-forge pyclustering
	```
</details>
<details><summary><b><a href="https://github.com/pyjanitor-devs/pyjanitor">pyjanitor</a></b> (🥈25 ·  ⭐ 760) - 用于数据清理的API。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyjanitor-devs/pyjanitor) (👨‍💻 94 · 🔀 130 · 📦 120 · 📋 420 - 23% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/ericmjl/pyjanitor
	```
- [PyPi](https://pypi.org/project/pyjanitor) (📥 11K / month):
	```
	pip install pyjanitor
	```
- [Conda](https://anaconda.org/conda-forge/pyjanitor) (📥 100K · ⏱️ 01.09.2021):
	```
	conda install -c conda-forge pyjanitor
	```
</details>
<details><summary><b><a href="https://github.com/explosion/cython-blis">Cython BLIS</a></b> (🥈25 ·  ⭐ 180) - 快速矩阵乘法库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/explosion/cython-blis) (👨‍💻 10 · 🔀 28 · 📦 13K · 📋 22 - 22% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/explosion/cython-blis
	```
- [PyPi](https://pypi.org/project/blis) (📥 2.5M / month):
	```
	pip install blis
	```
- [Conda](https://anaconda.org/conda-forge/cython-blis) (📥 1M · ⏱️ 31.01.2021):
	```
	conda install -c conda-forge cython-blis
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/metric-learn">metric-learn</a></b> (🥉24 ·  ⭐ 1.2K) - Python中的度量学习算法。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/metric-learn) (👨‍💻 21 · 🔀 210 · 📦 170 · 📋 160 - 29% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/scikit-learn-contrib/metric-learn
	```
- [PyPi](https://pypi.org/project/metric-learn) (📥 8K / month):
	```
	pip install metric-learn
	```
</details>
<details><summary><b><a href="https://github.com/gradio-app/gradio">Gradio</a></b> (🥉23 ·  ⭐ 3.7K) - 对任何模型做UI封装并与他人共享。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gradio-app/gradio) (👨‍💻 28 · 🔀 230 · 📦 340 · 📋 180 - 9% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/gradio-app/gradio
	```
- [PyPi](https://pypi.org/project/gradio):
	```
	pip install gradio
	```
</details>
<details><summary><b><a href="https://github.com/uber/causalml">causalml</a></b> (🥉23 ·  ⭐ 2.3K) - 利用机器学习提升建模和因果推理。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/uber/causalml) (👨‍💻 30 · 🔀 340 · 📦 31 · 📋 210 - 23% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/uber/causalml
	```
- [PyPi](https://pypi.org/project/causalml) (📥 40K / month):
	```
	pip install causalml
	```
</details>
<details><summary><b><a href="https://github.com/ljvmiranda921/pyswarms">PySwarms</a></b> (🥉22 ·  ⭐ 840) - 用于Python中粒子群优化的研究工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ljvmiranda921/pyswarms) (👨‍💻 43 · 🔀 270 · 📦 140 · 📋 190 - 6% open · ⏱️ 23.06.2021):

	```
	git clone https://github.com/ljvmiranda921/pyswarms
	```
- [PyPi](https://pypi.org/project/pyswarms) (📥 32K / month):
	```
	pip install pyswarms
	```
</details>
<details><summary><b><a href="https://github.com/minrk/findspark">findspark</a></b> (🥉22 ·  ⭐ 420) - 查找pyspark并导入的工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/minrk/findspark) (👨‍💻 14 · 🔀 66 · 📦 2K · 📋 20 - 50% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/minrk/findspark
	```
- [PyPi](https://pypi.org/project/findspark) (📥 1.7M / month):
	```
	pip install findspark
	```
- [Conda](https://anaconda.org/conda-forge/findspark) (📥 580K · ⏱️ 06.07.2018):
	```
	conda install -c conda-forge findspark
	```
</details>
<details><summary><b><a href="https://github.com/online-ml/river">River</a></b> (🥉20 ·  ⭐ 2.6K) - Python中的在线机器学习。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/online-ml/river) (👨‍💻 67 · 🔀 280 · 📦 44 · 📋 320 - 0% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/online-ml/river
	```
</details>
<details><summary><b><a href="https://github.com/inducer/pyopencl">pyopencl</a></b> (🥉20 ·  ⭐ 850) - 适用于Python的OpenCL集成。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/inducer/pyopencl) (👨‍💻 88 · 🔀 210 · 📦 560 · 📋 290 - 20% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/inducer/pyopencl
	```
- [PyPi](https://pypi.org/project/pyopencl) (📥 11K / month):
	```
	pip install pyopencl
	```
- [Conda](https://anaconda.org/conda-forge/pyopencl) (📥 510K · ⏱️ 07.10.2021):
	```
	conda install -c conda-forge pyopencl
	```
</details>
<details><summary><b><a href="https://github.com/MaxHalford/prince">Prince</a></b> (🥉20 ·  ⭐ 700) - Python因子分析库（PCA，CA，MCA，MFA，FAMD）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MaxHalford/prince) (👨‍💻 9 · 🔀 120 · 📦 150 · 📋 100 - 34% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/MaxHalford/prince
	```
- [PyPi](https://pypi.org/project/prince) (📥 26K / month):
	```
	pip install prince
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/SUOD">SUOD</a></b> (🥉20 ·  ⭐ 290) - （MLSys' 21）大型无人驾驶加速系统。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/yzhao062/SUOD) (🔀 34 · 📦 370 · 📋 6 - 66% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/yzhao062/SUOD
	```
- [PyPi](https://pypi.org/project/suod) (📥 35K / month):
	```
	pip install suod
	```
</details>
<details><summary><b><a href="https://github.com/airbnb/streamalert">StreamAlert</a></b> (🥉19 ·  ⭐ 2.6K · 💤) - StreamAlert是无服务器的实时数据分析框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airbnb/streamalert) (👨‍💻 31 · 🔀 310 · 📋 340 - 24% open · ⏱️ 10.02.2021):

	```
	git clone https://github.com/airbnb/streamalert
	```
</details>
<details><summary><b><a href="https://github.com/cleanlab/cleanlab">cleanlab</a></b> (🥉19 ·  ⭐ 2.3K) - 机器学习的标准软件包。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/cleanlab/cleanlab) (👨‍💻 6 · 🔀 220 · 📦 19 · 📋 72 - 37% open · ⏱️ 06.06.2021):

	```
	git clone https://github.com/cgnorthcutt/cleanlab
	```
- [PyPi](https://pypi.org/project/cleanlab) (📥 4.3K / month):
	```
	pip install cleanlab
	```
</details>
<details><summary><b><a href="https://github.com/trevorstephens/gplearn">gplearn</a></b> (🥉19 ·  ⭐ 1K) - 使用scikit-learn启发式API进行Python遗传编程。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/trevorstephens/gplearn) (👨‍💻 9 · 🔀 170 · 📦 190 · 📋 170 - 25% open · ⏱️ 01.07.2021):

	```
	git clone https://github.com/trevorstephens/gplearn
	```
- [PyPi](https://pypi.org/project/gplearn) (📥 5.3K / month):
	```
	pip install gplearn
	```
</details>
<details><summary><b><a href="https://github.com/eltonlaw/impyute">impyute</a></b> (🥉18 ·  ⭐ 290 · 💀) - 数据插补库可对缺少数据的数据集进行预处理。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eltonlaw/impyute) (👨‍💻 10 · 🔀 42 · 📦 120 · 📋 63 - 42% open · ⏱️ 05.10.2019):

	```
	git clone https://github.com/eltonlaw/impyute
	```
- [PyPi](https://pypi.org/project/impyute) (📥 1.9K / month):
	```
	pip install impyute
	```
</details>
<details><summary><b><a href="https://github.com/astroML/astroML">AstroML</a></b> (🥉17 ·  ⭐ 780) - 天文学和天体物理学的机器学习，统计和数据挖掘.<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/astroML/astroML) (👨‍💻 30 · 🔀 260 · 📋 140 - 38% open · ⏱️ 07.04.2021):

	```
	git clone https://github.com/astroML/astroML
	```
- [PyPi](https://pypi.org/project/astroML) (📥 1K / month):
	```
	pip install astroML
	```
- [Conda](https://anaconda.org/conda-forge/astroml) (📥 26K · ⏱️ 16.02.2020):
	```
	conda install -c conda-forge astroml
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/biopandas">BioPandas</a></b> (🥉17 ·  ⭐ 380) - 在pandas DataFrames中处理分子结构。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rasbt/biopandas) (👨‍💻 8 · 🔀 86 · 📋 39 - 38% open · ⏱️ 24.09.2021):

	```
	git clone https://github.com/rasbt/biopandas
	```
- [PyPi](https://pypi.org/project/biopandas) (📥 1.9K / month):
	```
	pip install biopandas
	```
- [Conda](https://anaconda.org/conda-forge/biopandas) (📥 88K · ⏱️ 31.08.2021):
	```
	conda install -c conda-forge biopandas
	```
</details>
<details><summary><b><a href="https://github.com/solegalli/feature_engine">Feature Engine</a></b> (🥉14 ·  ⭐ 3) - 具有sklearn类功能的功能工程包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/solegalli/feature_engine) (👨‍💻 24 · 🔀 3 · ⏱️ 06.08.2021):

	```
	git clone https://github.com/solegalli/feature_engine
	```
- [PyPi](https://pypi.org/project/feature_engine) (📥 41K / month):
	```
	pip install feature_engine
	```
- [Conda](https://anaconda.org/conda-forge/feature_engine) (📥 5.6K · ⏱️ 01.09.2021):
	```
	conda install -c conda-forge feature_engine
	```
</details>

---

## 相关资源

- [**Python资源汇集列表**](https://github.com/HanXinzi-AI/awesome-python-resources): 周更新的各种应用方向与主题的资源汇集列表
- [**python机器学习资源大全**](https://github.com/HanXinzi-AI/awesome-python-machine-learning-resources): 周更新的各种python机器学习资源汇集列表
- [**Jupyter及相关工具资源大全**](https://github.com/HanXinzi-AI/awesome-jupyter-resources): 周更新的各种Jupyter及相关工具资源汇集列表
- [**NLP项目和资源大全**](https://github.com/HanXinzi-AI/awesome-NLP-resources): 周更新的各种NLP板块涉及的项目和工具资源汇集列表
- [**CV项目和资源大全**](https://github.com/HanXinzi-AI/awesome-computer-vision-resources): 周更新的各种CV板块涉及的项目和工具资源汇集列表
