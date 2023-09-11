# Deep-Learning-AI-Course-Note---Finetuning-Large-Language-Models

## Why Fine Tune

1. What is Fine-tuning?
- general purpose --> specialized
- put more dat intot he odel than what fits into the prompt
- get the model to learn the data, rather tha just get access to it

2. Why Fine-tuning?
- steers the model to more consistent outputs
- reduces halucinations
- customizes the model the specific use case
- process is similar to the model's ealier training

3. Prompt engineering vs. fine-tuning
![image](https://github.com/lizliu2015/Deep-Learning-AI-Course-Note---Finetuning-Large-Language-Models/assets/13955626/3a474efe-3566-4a3b-a714-13b9e89bbc5c)

4. Tools used to fine tune LLM
- Pytorch
- Huggingface

## Where finetuning fits in
1. Fine tune comes after pre-train
Pretrianing --> base model --> finetuning --> finetuned model
- can also be self-supervised unlabeled data
- can be labeled data your curated
- much less data needed
- tool in your toolbox

2. Fine tune for generative taksks ins not well-defined
- updates entire model, not just part of it
- same training ovjective: next token prediction
- more advanced ways to reduce how much to update the model

3. What fine tune do for you
- Behavorial change
  - learning to response more consistently
  - learn to focus, e.g. moderation
  - teasing out capability, e.g better at conversation
- Gain knowledge
  - increasing knowledge of new specific concepts
  - correcting old incorrect information
 
4. Tasks to finetune -- Text in, text out
- extraction -- text in, less text out
  - reading
  - keywords, topics, routing, agents(planning, reasoning, self critic, tool use) etc.
- expansion -- text in, more text out
  - writing
  - chat, write emails, write code
- Task clarity is th ekey indicator of succcess
  - knowing what is good/bad/better outputs





