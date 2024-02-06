# 허깅페이스

- https://huggingface.co/
  - AI 모델 공유
  - AI 모델 학습에 대한 데이터 공유
  - https://huggingface.co/learn/nlp-course/ko/chapter1/1
- [라마2 (Llama 2) 한국어 언어 모델 사용법 (Llama-2-7B 한글 모델)](https://www.youtube.com/watch?v=ohArlOoIVf4)
- https://www.markhneedham.com/blog/2023/10/18/ollama-hugging-face-gguf-models/
  - pip install huggingface-hub
- https://github.com/davidkim205/komt
  - Korean Multi-task Instruction Tuning
  - huggingface-cli download davidkim205/komt-mistral-7b-v1-gguf ggml-model-q8_0.gguf --local-dir downloads --local-dir-use-symlinks False
  - Modelfile
    - echo "FROM ./downloads/ggml-model-q8_0.gguf" > Modelfile
  - ollama create ggml -f Modelfile
