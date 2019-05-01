# Racket-Labeling
### 指引
https://hackmd.io/6VUy6z4VQHOJ17etGQK2eQ?view&fbclid=IwAR2cjVNiwKHO-twZYGQPcidJDGNXea9O2QZEARq8dWos_jMw6y3pNO7nrGc
### 環境
WSL:Windows Subsystem Linux
### 修改
python3 install opencv?
### 錯誤
* Cannot connect to X server
  * download Xming
### 啟動 X server
```export DISPLAY=:0```

```xeyes```

```python3 label_tool.py video/0_0_0.avi```
