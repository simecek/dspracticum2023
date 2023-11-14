**Date**: Nov 13, 2023

**Slides**: https://docs.google.com/presentation/d/1dIFdhFoqXiZgqFi7QOsAeS0Kh5VEqmDdaqyo7j79hlQ/edit?usp=drive_link

Large Language Models (LLM)

* ChatGPT (Plus)
* ChatGPT API
* Open LLMs: Llama, Mistral, QLoRA adaptors

**Practical exercises**:

* [ChatGPT API](ChatGPT_API.ipynb)
* [Finetuning Mistral to generate SQL Selects](QLoRA.ipynb)

**Assignment** (due to Friday, Nov 24, 16:00):

Write a Python script using ChatGPT API (`openai` library) that gets as an input a text that is news coverage of some event, e.g. a conference.

The goal is to output `name` and `date` of the event:

* name = string
* date = datetime object

If not present or unable to find, it should output None. It should correctly handle exceptions, for example in case of timeout or too long text.

I have provided you with API key (see Discord) but try to first experiment in web ChatGPT environment and limit number of requests to 100, gpt-3.5-turbo model. Submit the link to solution on Github in a form on Discord.

**Important**: delete API key when pushing code to GitHub or other public repository. Robots will find it and use it.

