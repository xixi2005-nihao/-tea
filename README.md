# 任务
- **1.6-1.11：**

下载Anaconda、Vscode，学会怎么使用Anaconda下载Python库和在vscode中新建文件（.ipynb、.py、.md等），在.ipynb文件和.py文件中分别运行如下代码，观察效果

代码1：
```python
print("Hello World")
```
代码2：
```python
import matplotlib.pyplot as plt
import numpy as np
plt.rcParams['font.sans-serif'] = ['SimHei']
plt.rcParams['axes.unicode_minus'] = False
x = np.linspace(0, 10, 1000)
y = np.sin(x)
plt.figure(figsize=(10, 6))
plt.plot(x, y, label='sin(x)')
plt.title('正弦函数图像')
plt.xlabel('x')
plt.ylabel('y')
plt.legend()
plt.show()
```
