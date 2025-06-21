# gemini-fullstack-langgraph-quickstart-n8n
English | [简体中文](README_ZH.md)

A reproduction of `gemini-fullstack-langgraph-quickstart` in lowcode platform **N8N**, nearly 1:1
![snapshot of workflow](./doc/workflow.png)

The [`gemini‑fullstack‑langgraph‑quickstart`](https://github.com/google-gemini/gemini-fullstack-langgraph-quickstart) is a demo by the Google‑Gemini team that showcases how to build a powerful full‑stack AI agent using Gemini 2.5 and LangGraph

## Getting Started

### 1. Additional prerequisites 

- a redis service

> Use external redis to maintain some global variables for whole process (It is difficult to set/get global states only by normal nodes in n8n).


### 2. Import workflow to your n8n instance

copy from n8n template: https://n8n.io/workflows/4758-perplexity-style-iterative-research-with-gemini-and-google-search/

or

1. download **workflow.json** file
2. create a new workflow and open it.
3. click "..." (top right corner) -> import from file -> choose the file

or:

1. create a new workflow and open it.
2. click "..." (top right corner) -> import from url -> input the url: `https://raw.githubusercontent.com/slow-groovin/gemini-fullstack-langgraph-quickstart-n8n/refs/heads/main/workflow.json`

> My version is `1.95.3`, you may encounter nodes unrecognition problems in import if your version is incompatible with this. Maybe you can ask ai about this.

## Screenshot 

### comparison
![](./doc/comparison.png)


