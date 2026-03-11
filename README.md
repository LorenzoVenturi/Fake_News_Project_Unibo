# Fake_News_Project_Unibo
**This project aims to assess agents abilities in detecting fake claims.**

It contains 3 sections:
- **SECTION 1** - [_inspired by the workflow of this paper: [Large Language Model Agent for Fake News Detection](https://arxiv.org/pdf/2405.01593)_]: a **fixed** pipeline using LangGraph where a sequence of nodes analyze the claim from various perspectives. The effect of each node is assessed via an ablaton study.
- **SECTION 2** - [_inspired also by this paper: [Large Language Model Agent for Fake News Detection](https://arxiv.org/pdf/2405.01593)_]: a **non**-fixed pipeline where an agent built via LangChain decides which tools to call, and how many times.
- **SECTION 3** - [_inspired by this paper: [Debate-to-Detect: Reformulating Misinformation Detection as a
Real-World Debate with Large Language Models](https://arxiv.org/pdf/2505.18596)_] a **multi-agent** debate settings where two agents with distinct roles discuss between each other, implemented with LangGraph.
