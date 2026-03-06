# 统计分析软件

## 软件对比概览

| 软件 | 类型 | 费用 | 适用场景 |
|------|------|------|----------|
| **R** | 开源编程语言 | 免费 | 统计分析、数据可视化、机器学习 |
| **Python** | 开源编程语言 | 免费 | 数据科学、NLP、学习分析 |
| **SPSS** | 商业软件 | 收费（高校订阅） | 问卷数据分析，操作界面友好 |
| **Stata** | 商业软件 | 收费 | 面板数据、计量经济学 |
| **SAS** | 商业软件 | 收费 | 大型数据集、复杂抽样分析 |
| **HLM** | 商业软件 | 收费 | 多层线性模型专用 |
| **Mplus** | 商业软件 | 收费 | SEM、潜在类别分析 |
| **JASP** | 开源软件 | 免费 | 贝叶斯统计，界面友好 |
| **jamovi** | 开源软件 | 免费 | SPSS-like界面，基于R |

---

## R 语言资源

### 入门学习

- **官方网站：** [https://www.r-project.org](https://www.r-project.org)
- **RStudio IDE：** [https://posit.co/download/rstudio-desktop/](https://posit.co/download/rstudio-desktop/)（免费）
- **R for Data Science（中文版）：** [https://r4ds.had.co.nz](https://r4ds.had.co.nz)（Hadley Wickham，免费在线阅读）
- **统计学习导论（R语言）：** [https://www.statlearning.com](https://www.statlearning.com)（免费PDF）

### 教育研究常用包

```r
# 数据处理
library(tidyverse)    # 数据清洗与可视化生态系统
library(haven)        # 读取SPSS/Stata/SAS数据文件

# 问卷与测量
library(psych)        # 信度分析、探索性因子分析
library(lavaan)       # 结构方程模型（SEM）
library(lme4)         # 多层线性模型（混合效应模型）

# PISA/TIMSS复杂抽样
library(survey)       # 复杂抽样设计分析
library(intsvy)       # 国际大规模评估数据专用包

# 元分析
library(metafor)      # 元分析权威包

# 可视化
library(ggplot2)      # 数据可视化
library(ggpubr)       # 出版级别图表
```

### 中文教程推荐

- 《R语言实战》（Robert Kabacoff）— CNKI可借电子版
- 统计之都：[https://cosx.org](https://cosx.org)（中文R社区）
- Bilibili「R语言教程」系列视频

---

## Python 资源

### 教育研究常用库

```python
import pandas as pd       # 数据处理
import numpy as np        # 数值计算
import scipy.stats as stats  # 统计检验
import statsmodels.api as sm  # 回归分析
from sklearn import ...   # 机器学习
import matplotlib.pyplot as plt  # 可视化
import seaborn as sns     # 统计可视化
import pingouin           # 心理统计（效应量等）
```

- **Jupyter Notebook：** 推荐用于教育数据分析与可重复研究
- **Google Colab：** [https://colab.research.google.com](https://colab.research.google.com) — 免费GPU，无需本地安装

---

## SPSS 资源

!!! info "高校授权"
    多数高校通过正版软件协议提供 IBM SPSS Statistics 校园版，请向本校图书馆或信息中心咨询授权账号。

**入门教程：**
- IBM SPSS 官方文档：[https://www.ibm.com/docs/en/spss-statistics](https://www.ibm.com/docs/en/spss-statistics)
- Andy Field *Discovering Statistics Using IBM SPSS Statistics*（配套数据集免费下载）

---

## 专项分析工具

### 多层线性模型（HLM/MLM）

| 工具 | 说明 |
|------|------|
| **HLM 软件**（Scientific Software） | HLM专用软件，处理复杂模型直观 |
| **R: lme4 包** | 免费，功能强大，语法见上文 |
| **Stata: mixed 命令** | Stata内置多层模型命令 |
| **Mplus** | 可处理含潜变量的多层SEM |

### 结构方程模型（SEM）

| 工具 | 说明 |
|------|------|
| **Mplus** | 功能最全面，处理序次变量、复杂抽样 |
| **R: lavaan** | 免费，语法清晰，适合多数SEM需求 |
| **AMOS**（IBM） | SPSS生态，图形界面 |
| **SmartPLS** | 偏最小二乘SEM，适合探索性研究 |

### 复杂抽样分析（PISA/TIMSS等）

!!! warning "重要提示"
    分析PISA等大规模评估数据时，**必须考虑抽样权重与分层抽样设计**，否则标准误将严重低估，显著性检验结果不可信。

- **R: intsvy 包** — 专为 PISA、TIMSS、PIRLS 设计，自动处理合理值（plausible values）
- **OECD PISA 数据分析手册**（官方免费PDF）：操作指南
- **IDB Analyzer**（IEA 免费软件）：TIMSS/PIRLS 数据分析专用工具
