[![PyPI version](https://badge.fury.io/py/freeGPT.svg)](https://badge.fury.io/py/freeGPT)
[![Downloads](https://static.pepy.tech/personalized-badge/freeGPT?period=month&units=international_system&left_color=grey&right_color=brightgreen&left_text=Downloads)](https://pepy.tech/project/freeGPT)
[![License](https://img.shields.io/badge/License-MIT-bright&green.svg)](LICENSE)
# freeGPT
A Python package that gives access to GPT3 &amp; GPT4 models for free.
<br>
*Get started by doing: `pip install freeGPT`*

## Source:
*Models with .web have internet access on.*
<br>
| Models            | Websites                                 |
| ----------------- | -----------------------------------------|
| gpt3              | [theb.ai](https://theb.ai)               |
| gpt3.web          | [you.com](https://you.com)               |
| gpt4              | [usesless.com](https://ai.usesless.com)  |
| gpt4.web          | [forefront.ai](https://chat.forefront.ai)|

### TODO-List:
- [x] Add GPT-4.
- [x] Make the library well-documented.
- [x] Make the over-all library easier to use.
- [x] Make the over-all library easier to understand.
- [x] Replace you.com with theb.ai for less failed responses.
- [x] Add a internet search model for GPT-3 & GPT-4
- [ ] Make a discord bot
- [ ] Add text to image generation

## Support me:
- Join my [Discord Server](https://discord.gg/NcQ26PrNDp) :D
- Star this repository :D

## Examples:

#### GPT-3:

```python
from freeGPT import gpt3 # If you want to use web just replace `gpt3` with `gpt3.web as gpt3` and no other changes needed.

prompt = input("👦 > ")
resp = gpt3.Completion.create(prompt=prompt)
print(f"🤖 > {resp.text}")
```
#### GPT-4:

```python
from freeGPT import gpt4  # If you want to use web just replace `gpt4` with `gpt4.web as gpt4` and no other changes needed.

token = gpt4.Account.create(logging=True)
prompt = input("👦 > ")
resp = gpt4.Completion.create(prompt=prompt, token=token)
print(f"🤖 > {resp.text}")
```

## Star History:
[![Star History Chart](https://api.star-history.com/svg?repos=Ruu3f/freeGPT&type=Date)](https://github.com/Ruu3f/freeGPT/stargazers)

