# 基于python的信号处理工具箱开发（python—DSP）
[![Python](https://img.shields.io/badge/python-3.9-blue)](https://docs.python.org/zh-cn/3.9/)


使用python完成信号产生、信号时域采样与内插恢复、信号变换域分析、滤波器设计等内容，实现基于python的Digital Signal Processing Toolbox开发


## 信号产生

- 波形生成：时间向量和正弦波
  ([Colab Link ](https://colab.research.google.com/drive/1WrB8Z21WtpIRplLLE5osj0cxzDq0qMQE)|[Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E4%BA%A7%E7%94%9F/%E6%B3%A2%E5%BD%A2%E7%94%9F%E6%88%90%EF%BC%9A%E6%97%B6%E9%97%B4%E5%90%91%E9%87%8F%E5%92%8C%E6%AD%A3%E5%BC%A6%E6%B3%A2.ipynb))

- 脉冲函数、阶跃函数和斜坡函数  ([Colab Link](https://colab.research.google.com/drive/1_YvBOIoGfMVOzNXjvkMjc1AGRdpkDyCs)|[Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E4%BA%A7%E7%94%9F/%E8%84%89%E5%86%B2%E5%87%BD%E6%95%B0%E3%80%81%E9%98%B6%E8%B7%83%E5%87%BD%E6%95%B0%E5%92%8C%E6%96%9C%E5%9D%A1%E5%87%BD%E6%95%B0.ipynb))

- 常见的周期波形：锯齿波、三角波、方波  ([Colab Link](https://colab.research.google.com/drive/1REM-jvJX7dDC2SlKk02q8tDhxjB6iCcZ)|[Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E4%BA%A7%E7%94%9F/%E5%B8%B8%E8%A7%81%E7%9A%84%E5%91%A8%E6%9C%9F%E6%B3%A2%E5%BD%A2%EF%BC%9A%E9%94%AF%E9%BD%BF%E6%B3%A2%E3%80%81%E4%B8%89%E8%A7%92%E6%B3%A2%E3%80%81%E6%96%B9%E6%B3%A2.ipynb))


- 非周期波形：三角脉冲、矩形脉冲  ([Colab Link](https://colab.research.google.com/drive/1BYAiuRWjbPADVC9HL_zGoAnZX1PbNnJG)|[Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E4%BA%A7%E7%94%9F/%E9%9D%9E%E5%91%A8%E6%9C%9F%E6%B3%A2%E5%BD%A2%EF%BC%9A%E4%B8%89%E8%A7%92%E8%84%89%E5%86%B2%E3%80%81%E7%9F%A9%E5%BD%A2%E8%84%89%E5%86%B2.ipynb))

- 正弦函数sinc、迪利克雷函数Dlrichlet  ([Colab Link](https://colab.research.google.com/drive/1rVdnpADW4rtRZCUDdrEfF1E2NJ1p71-d)|[Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E4%BA%A7%E7%94%9F/%E6%AD%A3%E5%BC%A6%E5%87%BD%E6%95%B0sinc%E5%92%8C%E8%BF%AA%E5%88%A9%E5%85%8B%E9%9B%B7%E5%87%BD%E6%95%B0Dirichlet.ipynb))




## 信号时域采样与内插恢复

- 采样定理及奈奎斯特率验证  ([Colab Link](https://drive.google.com/drive/folders/1_I0dAk4mYkQ4qW-Wu9AccTXtCtp4TWTS) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E9%87%87%E6%A0%B7%E4%B8%8E%E6%81%A2%E5%A4%8D%EF%BC%88%E6%97%B6%E5%9F%9F%E5%88%86%E6%9E%90%EF%BC%89/%E9%87%87%E6%A0%B7%E5%AE%9A%E7%90%86%E5%8F%8A%E5%A5%88%E5%A5%8E%E6%96%AF%E7%89%B9%E5%AE%9A%E5%BE%8B/%E9%87%87%E6%A0%B7%E5%AE%9A%E7%90%86%EF%BC%88%E5%A5%88%E5%A5%8E%E6%96%AF%E7%89%B9%E5%AE%9A%E5%BE%8B%E9%AA%8C%E8%AF%81%EF%BC%89.ipynb))

- 信号恢复：取样内插恢复([Colab Link](https://colab.research.google.com/drive/1EUKrqNsf97t4mfwhYR1lo-xM7AD7ngCx#scrollTo=52fa4df8) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E9%87%87%E6%A0%B7%E4%B8%8E%E6%81%A2%E5%A4%8D%EF%BC%88%E6%97%B6%E5%9F%9F%E5%88%86%E6%9E%90%EF%BC%89/%E4%BF%A1%E5%8F%B7%E6%81%A2%E5%A4%8D%EF%BC%9A%E5%8F%96%E6%A0%B7%E4%BF%A1%E5%8F%B7%E5%86%85%E6%8F%92/%E4%BF%A1%E5%8F%B7%E5%86%85%E6%8F%92%E6%81%A2%E5%A4%8D.ipynb))

## 信号变换域分析
- 离散时间傅里叶变换DTFT([Colab Link](https://colab.research.google.com/drive/1EjyM8-OAbCmUoXYfpLMW2H6NpuVHj09_) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E5%8F%98%E6%8D%A2%EF%BC%88%E5%8F%98%E6%8D%A2%E5%9F%9F%E5%88%86%E6%9E%90%EF%BC%89/%E7%A6%BB%E6%95%A3%E6%97%B6%E9%97%B4%E5%82%85%E9%87%8C%E5%8F%B6%E5%8F%98%E6%8D%A2%EF%BC%88DTFT%EF%BC%89/%E7%A6%BB%E6%95%A3%E6%97%B6%E9%97%B4%E5%82%85%E9%87%8C%E5%8F%B6%E5%8F%98%E6%8D%A2DTFT.ipynb))
- 离散傅里叶变换DFT（IDFT）([Colab Link](https://drive.google.com/drive/folders/1fhm4oK5dmnZ65EsdrsugvKry9z-Uwo9l) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E5%8F%98%E6%8D%A2%EF%BC%88%E5%8F%98%E6%8D%A2%E5%9F%9F%E5%88%86%E6%9E%90%EF%BC%89/%E7%A6%BB%E6%95%A3%E5%82%85%E9%87%8C%E5%8F%B6%E5%8F%98%E6%8D%A2%EF%BC%88DFT%EF%BC%89/%E7%A6%BB%E6%95%A3%E5%82%85%E9%87%8C%E5%8F%B6%E5%8F%98%E6%8D%A2DFT.ipynb))
- Z变换(IchripZ)  ([Colab Link](https://colab.research.google.com/drive/1ny_vhox0f5vTUJ9nSR9h-bUP2rjSeJQR) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E5%8F%98%E6%8D%A2%EF%BC%88%E5%8F%98%E6%8D%A2%E5%9F%9F%E5%88%86%E6%9E%90%EF%BC%89/Z%E5%8F%98%E6%8D%A2/Z%E5%8F%98%E6%8D%A2%E5%92%8C%E9%80%86Z%E5%8F%98%E6%8D%A2.ipynb))
- 线性卷积  ([Colab Link](https://colab.research.google.com/drive/1-_7dCHcYIMrv7q8P1lxng2Vm4IWsc8aq) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E5%8F%98%E6%8D%A2%EF%BC%88%E5%8F%98%E6%8D%A2%E5%9F%9F%E5%88%86%E6%9E%90%EF%BC%89/%E5%8D%B7%E7%A7%AF/%E7%BA%BF%E6%80%A7%E5%8D%B7%E7%A7%AF.ipynb))
- 圆周卷积  ([Colab Link](https://colab.research.google.com/drive/1lyZECsdBZPDI8T-Q9mrUPrQD2xSjGfQy) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E4%BF%A1%E5%8F%B7%E5%8F%98%E6%8D%A2%EF%BC%88%E5%8F%98%E6%8D%A2%E5%9F%9F%E5%88%86%E6%9E%90%EF%BC%89/%E5%8D%B7%E7%A7%AF/%E5%9C%86%E5%91%A8%E5%8D%B7%E7%A7%AF.ipynb))

## 滤波器设计
### 模拟滤波器设计
- 巴特沃斯滤波器设计([Colab Link](https://colab.research.google.com/drive/1GDrBq8PCcNTgpMjBptYHSLM16h_D4Mdt) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E6%A8%A1%E6%8B%9F%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E5%B7%B4%E7%89%B9%E6%B2%83%E6%96%AF%E6%BB%A4%E6%B3%A2%E5%99%A8.ipynb))
- 切比雪夫滤波器设计([Colab Link](https://colab.research.google.com/drive/1ni1OH0wwhPvZ3L8lC1ZZLfSXk8tni9Gh) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E6%A8%A1%E6%8B%9F%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E5%88%87%E6%AF%94%E9%9B%AA%E5%A4%AB%E6%BB%A4%E6%B3%A2%E5%99%A8.ipynb))
### 窗函数
- 矩形窗、三角形窗、汉宁窗、海明窗、布莱克曼窗、高斯窗、凯塞尔窗  
  ([Colab Link](https://colab.research.google.com/drive/1IjWJpD0anewaeuJ8N1A2paJi0q9ThY6L) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E6%95%B0%E5%AD%97%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E7%AA%97%E5%87%BD%E6%95%B0/%E7%AA%97%E5%87%BD%E6%95%B0.ipynb))

### 数字滤波器设计
#### 无限长单位冲击响应滤波器（IIR）
- 脉冲响应不变法  ([Colab Link](https://colab.research.google.com/drive/1qiIShokbPaidfWswo2POANzBd3z-vf_M) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E6%95%B0%E5%AD%97%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/IIR%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1%E8%84%89%E5%86%B2%E5%93%8D%E5%BA%94%E4%B8%8D%E5%8F%98%E6%B3%95.ipynb))
- 双线性变换法  ([Colab Link](https://colab.research.google.com/drive/1V4qNdEBwOGjbjyGzFJf8XoDXYuHx85E0) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E6%95%B0%E5%AD%97%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/IIR%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1%E5%8F%8C%E7%BA%BF%E6%80%A7%E5%8F%98%E6%8D%A2%E6%B3%95.ipynb))
#### 有限长单位冲激响应滤波器设计（FIR）
- 窗函数设计法  ([Colab Link](https://colab.research.google.com/drive/1tAov4lmtsMO3IJPYrKiDs9Jw850gsxmV) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E6%95%B0%E5%AD%97%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/FIR%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1%E7%AA%97%E5%87%BD%E6%95%B0%E6%B3%95%E8%AE%BE%E8%AE%A1/%E7%AA%97%E5%87%BD%E6%95%B0%E6%B3%95%E8%AE%BE%E8%AE%A1FIR%E6%95%B0%E5%AD%97%E6%BB%A4%E6%B3%A2%E5%99%A8.ipynb))
- 频率取样设计法  ([Colab Link](https://colab.research.google.com/drive/1oKSgQq3MaIRA-2ZaZp3CQVfmRkanNXsl) | [Jupyter Notebook File](https://github.com/Chenying2000/Python-DSP/blob/main/%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1%EF%BC%9A%E4%BF%A1%E5%8F%B7%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7%E7%AE%B1%E5%BC%80%E5%8F%91/%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/%E6%95%B0%E5%AD%97%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1/FIR%E6%BB%A4%E6%B3%A2%E5%99%A8%E8%AE%BE%E8%AE%A1%E9%A2%91%E7%8E%87%E5%8F%96%E6%A0%B7%E6%B3%95.ipynb))
