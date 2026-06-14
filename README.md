# 人口老龄化舆情分析数据新闻

## 项目简介

这是一个关于人口老龄化话题的交互式数据新闻网页，基于微博平台2024年的数据进行舆情分析。

## 项目结构

```
output/
├── index.html          # 主页面
├── charts/             # 可视化图表
│   ├── 情绪分布饼图.png
│   ├── 热门话题标签条形图.png
│   ├── 用户地域分布条形图.png
│   ├── 用户认证类型条形图.png
│   ├── 话题热度趋势折线图.png
│   └── 高频关键词条形图.png
├── 舆情分析报告.txt     # 完整分析报告
├── weibo_data_deduplicated.csv  # 去重后数据
└── weibo_data_processed.csv     # 预处理后数据
```

## 部署到 GitHub Pages

### 步骤 1：创建 GitHub 仓库

1. 登录 GitHub，创建一个新仓库
2. 仓库命名建议：`aging-population-analysis`

### 步骤 2：上传文件

将 `output/` 目录下的所有文件上传到 GitHub 仓库根目录

### 步骤 3：启用 GitHub Pages

1. 进入仓库的 **Settings** 页面
2. 找到 **Pages** 选项
3. 在 **Source** 中选择：
   - Branch: `main`
   - Folder: `/ (root)`
4. 点击 **Save**

### 步骤 4：访问网站

部署完成后，访问地址格式为：
```
https://<username>.github.io/<repository-name>
```

例如：`https://username.github.io/aging-population-analysis`

## 网页功能

### 1. 首页
- 主题介绍
- 数据概览（统计卡片）
- 情绪分布可视化
- 核心话题关键词云

### 2. 数据分析页
- 话题影响力分析（关键传播节点）
- 话题热度趋势图表
- 高频关键词图表
- 用户地域分布图表

### 3. 舆情报告页
- 舆情概述
- 数据采集与处理说明
- 舆情数据分析
- 结论与建议

### 4. 互动数据页
- 数据筛选功能
- 情绪分布图表
- 热门话题标签
- 用户认证类型分布

## 技术栈

- **前端框架**: 纯 HTML/CSS/JavaScript
- **图表生成**: Python (Matplotlib)
- **部署平台**: GitHub Pages

## 数据来源

- **平台**: 微博
- **时间范围**: 2024年1月1日至2024年12月31日
- **采集内容**: 与"人口老龄化"相关的微博帖子及评论

## 本地预览

在本地打开 `index.html` 文件即可预览网页内容。

---

**报告生成时间**: 2024年12月