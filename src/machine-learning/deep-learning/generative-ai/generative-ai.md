# 생성형 AI

## deeplearning4j

- https://github.com/deeplearning4j/
  - https://github.com/clojure-interop/deeplearning4j

- Attention Is All You Need
  - https://blog.research.google/2017/08/transformer-novel-neural-network.html

- [Javaでディープラーニングをするためのファーストステップ](https://qiita.com/tamura__246/items/3893ec292284c7128069)

- 머신러닝 - 데이터주도
  - 딥러닝 - 뉴럴 네트워크
    - 생성형ai

<혼자 공부하는 머신러닝+딥러닝>의 코드 저장소입니다.
https://github.com/rickiepark/hg-mldl

https://namu.wiki/w/%EB%94%A5%20%EB%9F%AC%EB%8B%9D
밑바닥부터 시작하는 딥러닝 1,2,3,4
https://www.coursera.org/learn/neural-networks-deep-learning
[모두를 위한 머신러닝/딥러닝 강의](https://hunkim.github.io/ml/)
- [모두를 위한 딥러닝 강좌 시즌 1](https://www.youtube.com/playlist?list=PLlMkM4tgfjnLSOjrEJN31gZATbcj_MpUm)





## Neural Networks

- Neural networks are function approximators that stack affine transformations followed by nonlinear transformations.

Linear Neural Networks


## NPL(Natural Language Processing)

- 자연어 처리

## etc

github cloud
Llama 2
code llama-7a/34b
mistral-7b


ollama
- https://github.com/jmorganca/ollama
- https://ollama.ai/

- [Running Ollama on Windows ! Ubuntu Version | (Much Awaited Video)](https://www.youtube.com/watch?v=mnsfrQ81IjE)
  - Step 1: Turn Windows Features on or off (Virtual Machine Platform and Windows System for Linux)
  - Step 2: Go to Command Prompt and say “wsl --install”
  - Step 3: In the Command Prompt type “wsl --user root -d ubuntu”
  - Step 4: Type curl https://ollama.ai/install.sh | sh
  - ollama serve
  - ollama run llama2
- ui
  - https://github.com/ollama-webui/ollama-webui
    - git clone https://github.com/ollama-webui/ollama-webui.git && cd ollama-webui/
    - cp -RPp example.env .env
    - https://github.com/nvm-sh/nvm
      - nvm install 16
      - nvm use 16
    - npm i && npm run build
    - cd ./backend
      - sudo apt install python3-pip
    - pip install -r requirements.txt
      - pip install uvicorn
    - sh start.sh
      - python3 -m uvicorn main:app
    - http://localhost:8000
      - Model not selected??
    - cd ~/ollama-webui/backend && python3 -m uvicorn main:app
  - https://github.com/oobabooga/text-generation-webui.git



- taskweaver
  - https://microsoft.github.io/TaskWeaver/docs/llms/ollama

- Google Colab
  - https://colab.research.google.com/
  - https://research.google.com/colaboratory/faq.html?hl=ko


- mojo
  - https://www.modular.com/max/mojo
  - https://github.com/modularml/mojo


|      |                              |            |
| ---- | ---------------------------- | ---------- |
| GGML | GPT-Generated Model Language |            |
| GGUF | GPT-Generated Unified Format | 2023.08.21 |