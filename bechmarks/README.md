# Inference and training benchmarks

List of models run on ada and turing with throughputs and other details documented.

| Hardware | Model | Throughput | Code | Dev notes |
| :--- | :--- | :--- | :--- | :--- |
| ada_3080 | qwen3-32B | XXX | [scripts](https://github.com/d3vdru/anuura/blob/main/bechmarks/ada/qwen3-32B.py) | @ojas.kataria: ada is on cuda 12.8, vllm has moved onto 13.x, hence using llama.cpp |
