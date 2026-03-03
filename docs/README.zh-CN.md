# So（原名：LLMSurf）- macOS AI 搜索与知识整理智能助手

![So(LLMSurf)](https://raw.githubusercontent.com/yyaadet/llmsurf/main/images/llmsurf.jpeg)

一个可在 macOS 上执行信息挖掘的 AI 智能助手。它可以自由搜索 Google、X、Reddit、Baidu、小红书、微信公众号等平台，使用 AI 回答，并对 AI 回答进行事实核查。

## 使用场景

- 超级研究员
- 原生搜索引擎
- 原生知识库
- 原生 R 计算
- 客户发现
- 数据挖掘

## 功能

- 自由搜索并整理知识
- 对 LLM 回答进行事实核查
- 内置 R 运行时
- 支持搜索 Twitter(X)、小红书、Reddit、Baidu、微信公众号和 Google 等
- 基于搜索结果或本地知识回答问题
- 将对话转为任务，一键运行
- 支持本地原生 LLM 模型与云端 OpenAI 类模型
- 防止重复知识
- 知识管理：删除知识、自动更新知识、在本地桌面打开知识等

## 安装

### 安装 Ollama

1. 将 Ollama.app 拖到 /Applications
2. 运行 Ollama

### 安装 App

1. 将 So-v-xxx.app 拖到 /Applications
2. 运行 So

一分钟解决 macOS 应用打开问题！修复报错："Apple cannot verify that 'App Cleaner & Uninstaller' does not contain malware that may harm your Mac or compromise your privacy."

1. 打开终端（按 Command+Space，搜索 Terminal）
2. 输入以下命令：

```shell
sudo spctl --master-disable

# (进入应用目录)
cd /Applications

# (可使用 Tab 自动补全)
sudo xattr -rd com.apple.quarantine /Applications/So.app
```
3. 输入你的用户密码
4. 打开 设置 -> 隐私与安全性 -> 安全性 -> 允许任何来源的开发者
5. 打开 So

![Allow Any developers](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/privacy.png)

完成！

## 截图

![Main](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/main.png)

![Knowledge Manage](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/knowledge_manage.png)

# 对 AI LLM 回答进行事实核查

So 可以对 AI LLM 回答进行事实核查。

1. 在 LLM 回答中展示信息引用来源。
2. 对引用信息进行事实校验。
3. 对 LLM 回答中的数字或结论进行事实核查。

![Factually Check](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/llm_response_check.png)

## 联系我们

- Email: yyaadet@qq.com
- Twitter: [yyaadet](https://twitter.com/yyaadet)
- Wechat: yyaadet2002
- GitHub: [yyaadet](https://github.com/yyaadet)

## 推荐

- [AutoSRT](https://github.com/yyaadet/autosrt_page) 是一款 macOS 应用，可自动从视频文件生成双语字幕。
