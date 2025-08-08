# LLMSurf - AI Agent For macOS

![LLMSurf](https://raw.githubusercontent.com/yyaadet/llmsurf/main/images/logo.png)

An AI agent that can perform tasks on your macOS. Safe Realtime RAG Agent. It can open applications, search the twitter(X), rednote(xiaohongshu.com), Reddit and Google, and more.

## Cases

- Super Researcher
- Native search engine
- Native knowledge library
- Stock market analysis
- Investment analysis

## Features

- Search the twitter(X), rednote(xiaohongshu.com), Reddit and Google
- Answer questions with search results or local knowledges, summary and user comment analysis
- Transform conversation to task. You can run the task with one click.
- Support local native LLM models and cloud openai like models.
- Intelligent multiple round conversation
- Visual web crawler
- Prevent duplicated knowledges
- Manage knowledges, delete knowledges, auto update knowledge, open knowledge in the local desktop and more

## Installation

### Install ollama

1. Drag Ollama.app to /Applications
2. Run Ollama


### Install App

1. Drag LLMSurf-v-xxx.app to /Applications
2. Run LLMSurf

Solve macOS App Opening Issue in One Minute! Fix the error: "Apple cannot verify that 'App Cleaner & Uninstaller' does not contain malware that may harm your Mac or compromise your privacy."

1. Open Terminal (press Command+Space and search for Terminal)
2. Enter these two commands:

```shell
sudo spctl --master-disable

#(navigate to the applications folder)
cd /Applications 

# (use Tab key to auto-complete)
sudo xattr -rd com.apple.quarantine /Applications/LLMSurf.app 
```
3. Enter your user password

Done!

### Install models

If the app downloads models failed or the models are not in the App resources folder, we can download them and install them manually.

You can try download SentenceBERT model manually from [https://github.com/yyaadet/llmsurf/releases/download/v1.0.0/SentenceBERT.mlmodelc.zip].

1. Unzip it. You can see a file named `SentenceBERT.mlmodelc`.
2. Open the Terminal app. If your downloads are in the folder `~/Downloads`, you should run the command: `cd ~/Downloads`
3. Run command in the terminal: `mkdir -p ~/Library/Application\ Support/LLMSurf/Models/SentenceBERT`
4. Run command in the terminal: `cp -rf SentenceBERT.mlmodelc ~/Library/Application\ Support/LLMSurf/Models/SentenceBERT`


Download rerank model from [https://github.com/yyaadet/llmsurf/releases/download/v1.0.0/BGEReranker.mlmodelc.zip] .

1. Unzip it. You can see a file named `BGEReranker.mlmodelc.zip`.
2. Open the Terminal app. If your downloads are in the folder `~/Downloads`, you should run the command: `cd ~/Downloads`
3. Run command in the terminal: `mkdir -p ~/Library/Application\ Support/LLMSurf/Models/BGEReranker`
4. Run command in the terminal: `cp -rf BGEReranker.mlmodelc ~/Library/Application\ Support/LLMSurf/Models/BGEReranker.mlmodelc`


Of course, you can operate in GUI.


## Screenshots

![Main](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/main.png)

![Main](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/knowledge_manage.png)

## Contact US

- Email: yyaadet@qq.com
- Twitter: [yyaadet](https://twitter.com/yyaadet)
- Wechat: yyaadet2002
- GitHub: [yyaadet](https://github.com/yyaadet)

## Recommendation

- [AutoSRT](https://github.com/yyaadet/autosrt_page) is an macOS app that automatically generates dual language subtitles from video files.