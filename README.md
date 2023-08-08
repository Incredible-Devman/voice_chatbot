

(Used to be called gpt3-speech-to-text-chatbot, but was changed due to plans to add ability to swap model if desired)

This is a bot that allows you to have an engaging and safely emotive spoken conversation with ChatGPT or GPT-4 using your microphone. If you'd prefer to type rather than speak, you can also converse with the bot via the terminal.

The tool uses a modified GPT chat preset, handles keeping track of the conversation, and uses ChatGPT's API by default. You can tell GPT something and it will remember what you said for the session and you can also have the bot develop a memory of you over time if you'd like. Despite limitations based on GPT's max token count, GPT-VCC should still be able to converse with you for as long as you'd like without losing awareness about what you've talked about. In order to use this tool, you will need a valid OpenAI API key.

The bot requires OpenAI's moderation and GPT APIs to be working properly without too much latency. You can find the status here: https://status.openai.com/

The releases should be stable, as far as previous testing goes, but will not have all of the newest features. If you would like to have all the features as listed here, clone the repository and run 'git pull' every now and then. This will get you the newest features and bug fixes as they come, but it could be unstable. 



# Installing

First off, you'll need an OpenAI API key. You can create an account to get an API key here: https://openai.com/api/ .

### Windows

1. Download Python at https://www.python.org/

2. Download this repo either via the releases, git cloning the repo, or pressing the code button towards the upper right and pressing "Download ZIP".

3. Extract contents, then move into folder with the files.

4. If you have Windows Terminal installed, right click the empty part of the folder and select 'Open in Terminal'. Otherwise, use Win + R and enter powershell. Once you're in a terminal window and at the proper directory, use "pip install -r requirements.txt --upgrade". If this is done successfully, you should be ready to go as soon as you get yourself an OpenAI API key.

