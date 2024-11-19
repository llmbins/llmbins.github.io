---
description: |
  PromptMap is a tool designed to test adversarial prompt attacks on ChatGPT instances by generating and evaluating attack prompts against system instructions. It helps identify potential vulnerabilities in the system prompts of LLM instances.

  This guide explains how to install, configure, and use PromptMap effectively.

  **Command Reference**:
    - Repository URL: https://github.com/utkusen/promptmap.git
    - Target Model: YOUR_MODEL_HERE
    - Attack Model: YOUR_MODEL_HERE

command: |
  git clone https://github.com/utkusen/promptmap.git
  cd promptmap
  pip3 install -r requirements.txt
  python3 promptmap.py -n 10
items:
  - API_Key
  - Prompt
  - Logs
services:
  - OpenAI
  - Anthropic
  - HuggingFace
attack_types:
  - Prompt_Engineering
  - Security
  - Evaluation
OS:
  - Cloud
  - Local
references:
  - https://github.com/utkusen/promptmap
  - https://platform.openai.com/docs
---

