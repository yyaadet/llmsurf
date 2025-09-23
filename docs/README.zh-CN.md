# LLMSurf - macOS AI 智能助手

![LLMSurf](https://raw.githubusercontent.com/yyaadet/llmsurf/main/images/logo.png)

一个可以在您的 macOS 上执行任务的 AI 智能助手。安全实时的 RAG（检索增强生成）智能体。可以搜索 Twitter(X)、小红书(RedNote)、Reddit、百度、Google 等平台。

## 使用场景

- 超级研究员
- 原生搜索引擎
- 原生知识库
- 原生 R 语言计算

## 功能特性

- 嵌入式 R 运行时环境
- 搜索 Twitter(X)、小红书(RedNote)、Reddit 和 Google
- 基于搜索结果或本地知识回答问题，包括摘要和用户评论分析
- 将对话转换为任务，一键执行任务
- 支持本地原生 LLM 模型和云端 OpenAI 类模型
- 智能多轮对话
- 可视化网页爬虫
- 防止重复知识录入
- 知识管理：删除知识、自动更新知识、在本地桌面打开知识等

## 安装指南

### 安装 Ollama

1. 将 Ollama.app 拖拽到 /Applications
2. 运行 Ollama

### 安装应用

1. 将 LLMSurf-v-xxx.app 拖拽到 /Applications
2. 运行 LLMSurf

**解决 macOS 应用打开问题，只需一分钟！** 修复错误："Apple 无法验证 'App Cleaner & Uninstaller' 不包含可能危害您的 Mac 或损害您的隐私的恶意软件。"

1. 打开终端（按 Command+Space 搜索 Terminal）
2. 输入以下两条命令：

```shell
sudo spctl --master-disable

# (导航到应用程序文件夹)
cd /Applications

# (使用 Tab 键自动补全)
sudo xattr -rd com.apple.quarantine /Applications/LLMSurf.app
```
3. 输入您的用户密码

完成！

### 安装模型

如果应用下载模型失败或模型不在 App 资源文件夹中，我们可以手动下载并安装模型。

您可以尝试从以下链接手动下载 SentenceBERT 模型：[https://github.com/yyaadet/llmsurf/releases/download/v1.0.0/SentenceBERT.mlmodelc.zip]。

1. 解压文件。您可以看到一个名为 `SentenceBERT.mlmodelc` 的文件。
2. 打开终端应用。如果您的下载文件在 `~/Downloads` 文件夹中，请运行命令：`cd ~/Downloads`
3. 在终端中运行命令：`mkdir -p ~/Library/Application\ Support/LLMSurf/Models/SentenceBERT`
4. 在终端中运行命令：`cp -rf SentenceBERT.mlmodelc ~/Library/Application\ Support/LLMSurf/Models/SentenceBERT`

从以下链接下载重排序模型：[https://github.com/yyaadet/llmsurf/releases/download/v3.0.0/BGEReranker.mlmodelc.zip]。

1. 解压文件。您可以看到一个名为 `BGEReranker.mlmodelc.zip` 的文件。
2. 打开终端应用。如果您的下载文件在 `~/Downloads` 文件夹中，请运行命令：`cd ~/Downloads`
3. 在终端中运行命令：`mkdir -p ~/Library/Application\ Support/LLMSurf/Models/BGEReranker`
4. 在终端中运行命令：`cp -rf BGEReranker.mlmodelc ~/Library/Application\ Support/LLMSurf/Models/BGEReranker`

当然，您也可以通过图形界面操作。

**或者从百度网盘下载**：

链接: https://pan.baidu.com/s/1L2rWKGX0eDA_WeG_Mu19eA?pwd=t6jv 提取码: t6jv

## 应用截图

![主界面](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/main.png)

![知识管理](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/knowledge_manage.png)

## 联系我们

- 邮箱: yyaadet@qq.com
- Twitter: [yyaadet](https://twitter.com/yyaadet)
- 微信: yyaadet2002
- GitHub: [yyaadet](https://github.com/yyaadet)

## 推荐项目

- [AutoSRT](https://github.com/yyaadet/autosrt_page) 是一个 macOS 应用，可以自动从视频文件中生成双语字幕。
