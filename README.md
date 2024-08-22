<div align="center">
  <a href="https://pypi.org/project/openmacro/">
    <img src="https://raw.githubusercontent.com/Openmacro/openmacro/46bb3481766cb66983cb191db731c41f5f69d18d/docs/images/openmacro-title.svg" width="480" height="auto" alt="Openmacro"/>
  </a>
</div>
<div align="center">
<a href="LICENSE"><img src="https://img.shields.io/static/v1?label=license&message=MIT&color=white&style=flat" alt="License"/></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/commit-activity/m/Openmacro/openmacro" alt="License"/></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/last-commit/Openmacro/openmacro" alt="License"/></a>
</div>

##

> [!NOTE]  
> Project is in its early stage of development.

openmacro is a multimodal personal agent that allows LLMs to run code locally. openmacro aims to act as a personal agent capable of completing and automating simple to complex tasks autonomously via self prompting.

### Get started
You can get started with openmacro by running.
```shell
pip install openmacro
macro
```
> Not working? Raise an issue [here](https://github.com/amooo-ooo/openmacro/issues/new) or try this out instead:
```shell
py -m pip install openmacro
py -m openmacro
```

This provides a cli natural-language interface for you to:

+ Complete and automate simple to complex tasks.
+ Analyse and plot data.
+ Control desktop applications through vision and pyautogui.
+ Manipulate files including photos, videos, PDFs, etc.

At the moment, API keys for models are yet to be supported and by default, models are powered by HuggingFace Spaces and their respective hosts:
+ LLM: [Llama3.1-405B-Instruct](https://huggingface.co/spaces/Corvius/LLaMA-3.1-405B-Instruct) hosted by [Corvius](https://huggingface.co/Corvius).
+ Code: [CodeQwen1.5-7B](https://huggingface.co/spaces/Qwen/CodeQwen1.5-7b-Chat-demo) hosted by [Qwen](https://huggingface.co/Qwen).
+ Vision: [Qwen-VL-Max](https://huggingface.co/spaces/Qwen/Qwen-VL-Max) hosted by [Qwen](https://huggingface.co/Qwen).

This project is heavily inspired by Open Interpreter. 

### Personalisation
Openmacro supports cli args and customised settings! You can view arg options by running:
```shell
macro --help
```
To append your own personalised settings and save it for the future, run:
```shell
macro --config "path\to\config.toml" --save
```

What your personalised `config.toml` might look like:
```toml
[assistant]
name="Basil"
personality="You have a kind, deterministic and professional attitude towards your work and respond in a formal, yet casual manner."
```

### Todo's 
- [x] AI Intepreter
- [x] CLI Interface
- [ ] API Keys Support
- [ ] Extensions Feature
- [ ] Web Search Capability
- [ ] Chunk Streaming and Smart Stalling 
- [ ] Semantic File Search
- [ ] App Interface

...

### Contact
You can contact me at [amor.budiyanto@gmail.com](mailto:amor.budiyanto@gmail.com)
