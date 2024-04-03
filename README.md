# [GPT4 AI Realtime code scanner](https://marketplace.visualstudio.com/items?itemName=Sixth.sixth)

[![VSCode Plugin](https://firebasestorage.googleapis.com/v0/b/thsense-24e43.appspot.com/o/Frame%201261152503.png?alt=media&token=a7b6bcbb-4d93-40b7-a644-6f0ee007d605)](https://marketplace.visualstudio.com/items?itemName=Sixth.sixth&ssr=false#overview)  [![VSCode Plugin](https://firebasestorage.googleapis.com/v0/b/thsense-24e43.appspot.com/o/Frame%201261152503%20(2).png?alt=media&token=3bf49a43-cdbb-40d8-854c-7e01eb82bcf2)](https://marketplace.visualstudio.com/items?itemName=Sixth.sixth&ssr=false#overview) [![Gitpod ready-to-code](https://firebasestorage.googleapis.com/v0/b/thsense-24e43.appspot.com/o/Frame%201261152503%20(3).png?alt=media&token=2c86221b-7d23-45e9-878d-6f2606738512)](https://github.com/SixHq/GPT4-AI-Realtime-code-scanner-Autocomplete-and-Highlighter-for-Javascript-Py-JS-Java-Php-Sixth-SAST) [![Twitter Follow](https://firebasestorage.googleapis.com/v0/b/thsense-24e43.appspot.com/o/Frame%201261152503%20(4).png?alt=media&token=8c7a06bd-f91e-46e9-a344-1a12a0b61797)](https://twitter.com/sixth_hq) [![Discord](https://firebasestorage.googleapis.com/v0/b/thsense-24e43.appspot.com/o/Frame%201261152503%20(5).png?alt=media&token=fe8a5363-1b1b-4756-bd27-539637dd3d38)](https://discord.gg/rHzzPXDDRd)


![image](https://firebasestorage.googleapis.com/v0/b/thsense-24e43.appspot.com/o/Screenshot%202024-03-28%20at%2019.55.42.png?alt=media&token=3f071359-7be7-4dce-b03e-a14c8723e8e0)

[![N|Solid](https://cdn.loom.com/sessions/thumbnails/124587322c2544cab188a54ce2627b0e-with-play.gif)](https://www.loom.com/embed/124587322c2544cab188a54ce2627b0e?sid=a0c79b99-4ef2-461e-97f0-241aaba11921)

A lightweight VS Code extension that helps you automates the boring or repetitive stuffs such as completing your code, scaning your code for vulnenrabilities, generating doc string and many more. It provides a beautiful GUI client experience, bringing [Convention over Configuration](https://en.wikipedia.org/wiki/Convention_over_configuration) into how developers perform the day to day boring and repetivite tasks.

Built with 💖 for developers.

## **Requirements**

- VS Code 1.43 or newer
- [Optional] Python3.9

## **Supported OSes/Platforms:**
- Linux (Linux-x64, Linux-arm64, Linux-arm, Alpine-x64)
- macOS (Darwin-x64, Darwin-arm64 Apple Silicon)
- Windows (Win32-x64)

## **Quick Start**

- In a VS Code project any file within the [supported langauges](#supported-langauges)
- GPT4 AI [auto detects your classes and functions](#chatgpt4-quick-start). You will see some options at the top of every function and classes.

![image](https://firebasestorage.googleapis.com/v0/b/thsense-24e43.appspot.com/o/Frame%201261152555%20(2).png?alt=media&token=3ddd3366-7452-4f53-a732-67117f61e0c3)

## **ChatGPT4 Quick Start**

- Immediately after opening a file or a project, a tab automatically opens on the right sidebar of your project with a ChatGPT interface, you can also open this tab manually by selecting the sixth view on the toolbar and selecting the "ChatGPT4" option

![image](https://firebasestorage.googleapis.com/v0/b/thsense-24e43.appspot.com/o/Group%201261152598.png?alt=media&token=b28cf170-e232-4d39-8c2f-5384796a18cd)

> [!NOTE]
> Additionally, Sixth provides you with some additional [tools](#language-and-framework-integrations) that gives you more control over tasks you want to have ChatGPT4 autuomate for you

## **Generate Code from Images, Audio and Documents**
Generate code from images, audio and txt documents, reducing the amount of boiler plate codes written, Frontend engineers, you'll definitely love this one!!!

## **Troubleshooting**
By default, all functions and classes are detected locally by a python server runninng on port ``` 5011```, and then are encrypted end to end and sent via https to our servers where chatGPT4 process. If you are not getting the codelens on top of every fuctions or class you might have to check if the port is still running you can visit ```http://127.0.0.1:5011``` of which you should see something like this

```json
{
  "detail": "Not Found"
}
```
if you see otherwise it comes up make sure you have the python3.9 installed, you can download it [here](https://www.python.org/downloads/release/python-3919/). After which reopening vscode should fix it, if this issue persists, please send a mail [here](mailto:ope@trysixth.com), or drop a message on our [discord](https://discord.gg/rHzzPXDDRd) or create an issue on our [github](https://github.com/SixHq/GPT4-AI-Realtime-code-scanner-Autocomplete-and-Highlighter-for-Javascript-Py-JS-Java-Php-Sixth-SAST/issues)

> [!TIP]
> Before trouble shooting, try restarting vscode, it fixes the issue most of the times.

## Keybinding

Press `Ctrl+Q Ctrl+L` to bring up Sixth view

## Supported Langauges

The following databases are currently supported:

- Python
- Javascript
- PHP
- Typescript
- GO


> [!NOTE]
>  For Other programming languages, these features will be added in a future upgrade, but 
> for now, users using unsupported programming languages can still make use of the ChatGPT4 features 

## Tools Integrations

To get started with these integrations click on the sixth icon on the toolbar, and then configurations

![image](https://firebasestorage.googleapis.com/v0/b/thsense-24e43.appspot.com/o/Frame%201261152555%20(3).png?alt=media&token=03e355d3-6e89-42bc-afd6-4812602503b9)
### JIRA Integration
  You can sync ChatGPT4 with your JIRA sprints and have it auto complete or recommend soultions to your sprints without breaking a sweat

### Sentry Integrations
   If you have sentry integrated in your project, ChatGPT4 can automatically pick up senntry logs, implement them in your project and raise a PR to your github repo, of which you can view from vscode and either accept or decline the request.
   *NOTE:* You need to first connect to a ChatGPT4 to both sentry and Github accounts.

### Detecting bugs from Terminal
   You can also configure ChatGPT4 to autodetect bugs, error and information logs on your terminal and provide code fixes, information logs and insights about them.
   


## Why Sixth?

Two words: Better DX.

Sixth aims to significantly cut down the time developers spend on doing the boring stuffs such as reading documentations, debugging, writing doc strings or postman docs, optimzing an function and many more, Sixth aims to optimize DX.
Specifically, these experiences:

1. For every bug you face or new doc string or documentation to be written or new JIRA task to be done, there is no way to resolve or manage these these very frequent tasks without switching tabs. 
2. It is common to frequently tab-in and tab-out of project windows, switching between the IDE and ChatGPT or Stack overflow or JIRA board e.t.c. Sometimes, frequent enough to want to get the Solution data directly in the IDE. 

Local DX should be better than this.

Also, most of the other GPTs extensions are clunky or simply overwhelming and require you to generate an openAI key and make a bunch of cryptic configurations, with bells and whistles that are not really easy to use as a beginner or advanced engineer. Usually, getting answers to your bugs or questions all you actually need is a textbox or a button to click.

Furthermore, who doesn't love beautiful UIs? GPTs have evolved to generally not have exciting UIs in my opinion, except just a few with excellent and intuitive UIs.

To address the above, there is a need for a GPT tool that can automate the boring and stuffs without having to worry about generating an OpenAI key or tweaking cryptic options. Getting these tasks done should be simple, fast, intuitive, and clean.

Hence, Sixth 🚀

# What people are saying about us?

![N|Solid](https://firebasestorage.googleapis.com/v0/b/thsense-24e43.appspot.com/o/Group%201261152558.png?alt=media&token=db2880dd-470e-401a-aa04-c7114269af83)
