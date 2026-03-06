# 国际开放数据库

## 大型国际比较评估数据（截至 2026-03）

| 项目 | 机构 | 最新公开轮次 | 覆盖范围（官方口径） | 数据入口 |
|------|------|--------------|----------------------|----------|
| **PISA**（国际学生评估项目） | OECD | 2022 | 81个国家/经济体，约69万名15岁学生 | [PISA Data](https://www.oecd.org/en/about/programmes/pisa/pisa-data.html) |
| **TIMSS**（数学与科学趋势研究） | IEA | 2023 | 超65万名学生，64个国家和6个基准参与体 | [TIMSS Repository](https://www.iea.nl/data-tools/repository/timss) |
| **PIRLS**（国际阅读素养进展研究） | IEA | 2021 | 约40万名学生，57个国家和8个基准参与体 | [PIRLS Repository](https://www.iea.nl/data-tools/repository/pirls) |
| **TALIS**（国际教学与学习调查） | OECD | 2024（结果2025发布） | 主调查覆盖约55个教育系统，面向教师与校长 | [TALIS Data](https://www.oecd.org/en/about/programmes/talis/talis-data.html) |
| **PIAAC**（成人能力评估） | OECD | 2023（首批结果2024发布） | 31个国家/经济体，约16万名16-65岁成人 | [PIAAC Data](https://www.oecd.org/en/about/programmes/piaac/piaac-data.html) |
| **ICILS**（计算机与信息素养） | IEA | 2023 | 35个教育系统，超过13万名八年级学生 | [ICILS Repository](https://www.iea.nl/data-tools/repository/icils) |
| **ICCS**（公民与公民素养教育） | IEA | 2022 | 22个国家和2个基准参与体，约8.2万名学生 | [ICCS Repository](https://www.iea.nl/data-tools/repository/iccs) |

!!! info "选型建议"
    - **学习结果比较（K-12）：** PISA / TIMSS / PIRLS
    - **教师与学校治理：** TALIS
    - **成人技能与终身学习：** PIAAC
    - **数字素养与公民素养：** ICILS / ICCS

## 学术文献与引文数据平台

| 平台 | 定位 | 访问方式 |
|------|------|----------|
| **ERIC** | 教育学文献核心入口（含报告、期刊、灰色文献） | [https://eric.ed.gov](https://eric.ed.gov)（免费） |
| **Education Source**（EBSCO） | 教育学期刊与全文数据库 | 机构订阅 |
| **PsycINFO** | 教育心理学与发展心理学核心文献 | 机构订阅 |
| **Scopus** | 多学科引文数据库，适合文献计量 | 机构订阅 |
| **Web of Science** | SSCI/ESCI 检索与引文分析 | 机构订阅 |
| **OpenAlex** | 开放学术图谱（论文/作者/机构/主题） | [https://openalex.org](https://openalex.org)（免费API） |
| **Crossref** | DOI 元数据检索与批量查询 | [https://www.crossref.org](https://www.crossref.org)（开放API） |
| **Lens** | 学术论文与专利联合检索 | [https://www.lens.org](https://www.lens.org)（免费注册） |
| **CORE** | 聚合全球开放获取全文仓储 | [https://core.ac.uk](https://core.ac.uk)（开放检索/API） |

## 开放获取与预印本

!!! tip "开放获取目录"
    - **DOAJ**（开放获取期刊目录）：[https://doaj.org](https://doaj.org)
    - **OpenDOAR**（开放仓储目录）：[https://v2.sherpa.ac.uk/opendoar/](https://v2.sherpa.ac.uk/opendoar/)
    - **unpaywall**（浏览器插件）：自动定位合法免费全文

!!! tip "预印本平台"
    - **EdArXiv**（教育学）：[https://edarxiv.org](https://edarxiv.org)
    - **PsyArXiv**（心理与教育心理）：[https://psyarxiv.com](https://psyarxiv.com)
    - **SSRN**（社会科学）：[https://www.ssrn.com](https://www.ssrn.com)

## 国际组织宏观教育指标

| 资源 | 链接 | 典型用途 |
|------|------|----------|
| UNESCO UIS | [https://uis.unesco.org](https://uis.unesco.org) | 全球教育指标（入学、完成率、师资、财政） |
| World Bank Education Data | [https://data.worldbank.org/topic/education](https://data.worldbank.org/topic/education) | 跨国宏观教育指标与长期趋势 |
| World Bank EdStats | [https://datatopics.worldbank.org/education/](https://datatopics.worldbank.org/education/) | 指标面板与国别对比 |
| OECD Education at a Glance | [https://www.oecd.org/en/publications/education-at-a-glance_69096873-en.html](https://www.oecd.org/en/publications/education-at-a-glance_69096873-en.html) | OECD国家教育系统年度监测 |

## 分析工具与复现支持

| 工具 | 适用场景 | 链接 |
|------|----------|------|
| IEA IDB Analyzer | IEA/OECD 大规模评估数据合并与复杂抽样分析 | [https://www.iea.nl/data-tools/tools](https://www.iea.nl/data-tools/tools) |
| `EdSurvey`（R） | NAEP / PISA / TIMSS / PIRLS 等教育评估分析 | [https://cran.r-project.org/package=EdSurvey](https://cran.r-project.org/package=EdSurvey) |
| `intsvy`（R） | PISA / TIMSS / PIRLS / TALIS 指标计算与建模 | [https://cran.r-project.org/package=intsvy](https://cran.r-project.org/package=intsvy) |

!!! warning "数据使用规范"
    使用前请阅读各数据库的使用协议（DUA / License / Terms）。
    国际评估数据通常采用复杂抽样和可置信值（Plausible Values）设计，分析时必须使用权重与对应方差估计方法。
