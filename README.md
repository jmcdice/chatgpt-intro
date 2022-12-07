# gptchat Intro project

This project is just a collection of odds and ends related to learning to use the gptchat AI service

## OpenAI GPT Chat CLI written in bash

Using gtpchat webui, I was able to write a simple bash client for the gtpchat API. 

To install and use it, first export your OpenAI API Key
```console
  export OPENAI_API_KEY='your-openai-key'
```

Install and run the cli
```console
   wget https://raw.githubusercontent.com/jmcdice/gptchat/main/gchat -O /usr/local/bin/gchat
   chmod 755 /usr/local/bin/gchat
   gchat
```

## Example prompts 

[Example gtpchat prompts](prompt_examples.md)
