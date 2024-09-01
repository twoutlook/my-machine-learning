# 2024-09-01 成功在 Ubuntu 20.04.6 LTS 安裝 CUDA, 並使用 Docker images GPU version 
- docker pull ghcr.io/coqui-ai/tts
- 之前沒有在 Linux 裝過 CUDA driver
- 之前沒有在 Linux 運行過 Docker
## 今天最大的突破 
### Win11 Python3.9
- 在幾年前的筆記型電腦, 在 Win11 Python3.9, 成功安裝好 Mozilla TTS, 除了慢, 沒有什麼異常 
- 以一樣的方式, Win11 Python3.9, 居然在兩台相對比較新的桌機是裝起來, 但大部分 model 不知原因就是用不起來.
### Win11 WSL2 (Ubuntu 20.04.6) Python3.9  
- 在沒有 GPU 的桌機以 Ubuntu 20.04 加裝 Python 3.9, 裝起來相對好些
- 在有 GPU 的桌機成功運行 TTS 的 CPU 及 GPU 的兩組 Docker
  - 同樣的功能, 對照組一比較, CPU 組就像電瓶車, GPU 組就像 F1 賽車


- https://chatgpt.com/share/4c3a6b52-5a98-466b-afea-6537f28fd18a

<img width="1406" alt="image" src="https://github.com/user-attachments/assets/97b37313-6579-4e44-8503-52d5d2196d3f">
