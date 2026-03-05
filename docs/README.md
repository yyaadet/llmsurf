# So (Original name: LLMSurf) - Search and Organize AI Agent For macOS

![So(LLMSurf)](https://raw.githubusercontent.com/yyaadet/llmsurf/main/images/llmsurf.jpeg)

A Mining AI agent that can perform information mining on your macOS. It can search the Google, X, Reddit, Baidu, Xiaohongshu, Weixin MP freely etc, response with AI, and check the AI answer factually.

![How to use?]()

## Cases

- Super Researcher
- Native search engine
- Native knowledge library
- Native R calculations
- Customer Discovery
- Data Mining

## Features

- Search freely and organize knowledge
- Factually check LLM answer
- Embedded R runtime
- Search the twitter(X), rednote(xiaohongshu.com), Reddit, Baidu, Weixin MP and Google etc
- Answer questions with search results or local knowledges
- Transform conversation to task. You can run the task with one click.
- Support local native LLM models and cloud openai like models.
- Prevent duplicated knowledges
- Manage knowledges, delete knowledges, auto update knowledge, open knowledge in the local desktop and more

## Installation

### Install ollama

1. Drag Ollama.app to /Applications
2. Run Ollama


### Install App

1. Drag So-v-xxx.app to /Applications
2. Run So

Solve macOS App Opening Issue in One Minute! Fix the error: "Apple cannot verify that 'App Cleaner & Uninstaller' does not contain malware that may harm your Mac or compromise your privacy."

1. Open Terminal (press Command+Space and search for Terminal)
2. Enter these two commands:

```shell
sudo spctl --master-disable

#(navigate to the applications folder)
cd /Applications 

# (use Tab key to auto-complete)
sudo xattr -rd com.apple.quarantine /Applications/So.app 
```
3. Enter your user password
4. Open Settings -> Security & Privacy -> Security -> Allow Any developers
5. Open So

![Allow Any developers](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/privacy.png)

Done!

## Screenshots

![Main](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/main.png)

![Knowledge Manage](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/knowledge_manage.png)

# Factually Check AI LLM Response

So can check the AI LLM response factually.

1. We will show information citation in the LLM response.
2. We will check the information citation factually.
3. The numbers or claims in the LLM response will be checked factually.

![Factually Check](https://raw.githubusercontent.com/yyaadet/llmsurf/main/screenshots/llm_response_check.png)

## Contact US

- Email: yyaadet@qq.com
- Twitter: [yyaadet](https://twitter.com/yyaadet)
- Wechat: yyaadet2002
- GitHub: [yyaadet](https://github.com/yyaadet)

## Recommendation

- [AutoSRT](https://github.com/yyaadet/autosrt_page) is an macOS app that automatically generates dual language subtitles from video files.
