# LLMSurf - AI Agent For macOS

![LLMSurf](https://raw.githubusercontent.com/yyaadet/llmsurf/main/images/logo.png)

An AI agent that can perform tasks on your macOS. It can open applications, search the twitter(X), rednote(xiaohongshu.com), Reddit and Google, and more.

## Application 

- Super Researcher
- Native search engine

## Features

- Search the twitter(X), rednote(xiaohongshu.com), Reddit and Google
- Answer questions with search results or local knowledges, summary and user comment analysis
- Transform conversation to task. You can run the task with one click.
- Support local native LLM models and cloud openai like models.
- Prevent duplicated knowledges
- Visual knowledge crawler
- Manage knowledges, delete knowledges, auto update knowledge, open knowledge in the local desktop and more

## Installation

1. Drag Ollama.app to /Applications
2. Run Ollama
3. Drag LLMSurf-v-xxx.app to /Applications
4. Run LLMSurf


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

## Screenshots

![Main](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/main.png)

![Main](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/knowledge_manage.png)

## Contact US

- Email: yyaadet@qq.com
- Twitter: [yyaadet](https://twitter.com/yyaadet)
- Wechat: yyaadet2002
- GitHub: [yyaadet](https://github.com/yyaadet)