# Receiver Heads in Deceptive Reasoning

Do receiver heads attend to different sentences when models engage in deceptive vs truthful reasoning?

## Notebooks

- **01_load_data.ipynb**: Loads the blackmail-rollouts dataset and extracts 50 blackmail + 50 honest traces
- **02_qwen15b_get_receiver_heads.ipynb**: Identifies receiver heads in Qwen-1.5B for both conditions
- **03_llama8b_get_receiver_heads.ipynb**: Identifies receiver heads in Llama-8B for both conditions
- **04_qwen3_8b_get_receiver_heads.ipynb**: Identifies receiver heads in Qwen3-8B for both conditions
- **05_qwen15b_inspect_receiver_heads.ipynb**: Analyzes and visualizes receiver head patterns for Qwen-1.5B

## Setup

```bash
git clone --recurse-submodules [repo-url]
pip install -r requirements.txt
cd thought-anchors && pip install -r requirements.txt
```
