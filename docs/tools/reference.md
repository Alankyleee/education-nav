# 文献管理工具

## 主流工具对比

| 工具 | 费用 | 平台 | 推荐指数 | 特点 |
|------|------|------|----------|------|
| **Zotero** | 免费（云存储按需付费） | Win/Mac/Linux/Web | ★★★★★ | 开源，浏览器插件强，社区活跃 |
| **EndNote** | 收费（高校常有授权） | Win/Mac | ★★★★ | 功能强大，与Word深度集成 |
| **Mendeley** | 免费（Elsevier旗下） | Win/Mac/Web | ★★★ | PDF注释，学术社交网络 |
| **Papers** | 订阅制 | Mac/iOS | ★★★ | macOS用户友好，文献发现 |
| **NoteExpress** | 收费（国内软件） | Win | ★★★ | 对CNKI支持好，适合中文文献 |

---

## Zotero 深度指南

!!! tip "强烈推荐 Zotero"
    Zotero 是目前教育研究者最推荐的文献管理工具：免费、开源、跨平台，浏览器插件可一键抓取文献元数据。

### 安装与配置

1. 下载：[https://www.zotero.org/download/](https://www.zotero.org/download/)
2. 安装浏览器插件（Zotero Connector）
3. 注册账号（用于云同步）
4. 安装 Word/LibreOffice 插件（自动引用格式）

### 推荐插件

| 插件 | 功能 |
|------|------|
| **Zotero Better BibTeX** | 生成稳定的引用键，LaTeX用户必装 |
| **Zotero PDF Translate** | PDF文献翻译（对中文用户极其有用） |
| **Zotero GPT** | AI辅助文献摘要与问答 |
| **Zotero Reference** | 快速插入参考文献 |
| **Zutilo** | 批量操作文献条目 |

### Zotero 使用技巧

```
文献导入方式（优先级从高到低）：
1. 浏览器插件一键导入（最准确）
2. 通过 DOI/ISBN 导入
3. 拖拽 PDF 后手动补充元数据
4. 从 CNKI/万方 导入（使用 Zotero 中文助手插件）
```

!!! warning "中文文献注意"
    CNKI 导出的文献元数据质量参差不齐，建议导入后检查作者姓名、期刊名称等字段。推荐使用 **茉莉花（Jasminum）** 插件增强中文文献抓取能力。

---

## 引用格式规范

### 常用引用格式

| 格式 | 适用场景 | 示例期刊/领域 |
|------|----------|---------------|
| **APA 7th** | 教育学、心理学主流 | 绝大多数教育学期刊 |
| **MLA 9th** | 人文学科 | 部分比较教育著作 |
| **Chicago/Turabian** | 历史教育研究 | 部分北美期刊 |
| **GB/T 7714-2015** | 中文期刊 | CNKI收录期刊标准 |

### APA 7 常用引用示例

**期刊文章：**
```
Author, A. A., & Author, B. B. (Year). Title of article.
Title of Periodical, volume(issue), page–page.
https://doi.org/xxxxx
```

**书籍：**
```
Author, A. A. (Year). Title of work: Capital letter also for subtitle. Publisher.
```

**数据集：**
```
Author, A. A. (Year). Title of dataset (Version X.X) [Dataset].
Repository Name. https://doi.org/xxxxx
```

### 在线格式参考

- **Purdue OWL：** [https://owl.purdue.edu](https://owl.purdue.edu) — APA/MLA/Chicago权威免费参考
- **APA Style Blog：** [https://apastyle.apa.org/blog](https://apastyle.apa.org/blog) — APA官方答疑
- **Citation Machine：** 在线引用生成工具（核实准确性后使用）
