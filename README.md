# OpenCV 学习笔记 / OpenCV Learning Notes

这是我个人关于 OpenCV 的学习笔记，记录了我在学习图像处理过程中遇到的重要知识点与代码示例。  
笔记主要通过 Python + OpenCV 实现，并使用 Jupyter Notebook 整理内容。

*This is my personal learning notes on OpenCV, documenting important concepts and code examples encountered during my image processing learning journey.  
The notes are primarily implemented using Python + OpenCV and organized with Jupyter Notebook.*

- 具体代码见 (`.\src\openCV.ipynb`)
- *For detailed code, see (`.\src\openCV.ipynb`)*

## 学习内容包括（已更新）/ Learning Content (Updated):

| 模块 / Module | 内容 / Content |
| ------------- | -------------- |
| **1. 图像基本操作** <br> *Basic Image Operations* | - 数据读取（图像与视频）<br>- ROI区域截取与颜色通道提取<br>- 边界填充<br>- 数值计算与图像融合<br><br>*- Data reading (images and videos)<br>- ROI region extraction and color channel extraction<br>- Border padding<br>- Numerical calculations and image blending* |
| **2. 阈值与图像平滑** <br> *Thresholding and Image Smoothing* | - 图像阈值处理（二值化、截断等）<br>- 图像平滑（均值、方框、高斯、中值滤波）<br><br>*- Image thresholding (binarization, truncation, etc.)<br>- Image smoothing (mean, box, Gaussian, median filtering)* |
| **3. 图像形态学操作** <br> *Morphological Operations* | - 腐蚀与膨胀操作<br>- 开闭运算（腐蚀+膨胀）<br>- 梯度运算（腐蚀与膨胀差值）<br>- 礼帽与黑帽（开闭与原图差）<br><br>*- Erosion and dilation operations<br>- Opening and closing operations (erosion + dilation)<br>- Gradient operations (difference between erosion and dilation)<br>- Top-hat and black-hat (difference between opening/closing and original image)* |
| **4. 图像梯度计算** <br> *Image Gradient Calculation* | - Sobel 算子<br>- Scharr 与 Laplacian 算子<br>- 算子特点比较<br><br>*- Sobel operator<br>- Scharr and Laplacian operators<br>- Comparison of operator characteristics* |
| **5. 边缘检测** <br> *Edge Detection* | - Canny 边缘检测<br>- 非极大值抑制（NMS）<br>- 双阈值检测<br><br>*- Canny edge detection<br>- Non-maximum suppression (NMS)<br>- Double threshold detection* |
| **6. 图像金字塔与轮廓检测** <br> *Image Pyramids and Contour Detection* | - 轮廓检测与模板匹配（单/多）<br>- 高斯与拉普拉斯图像金字塔<br>- 轮廓特征提取与近似<br><br>*- Contour detection and template matching (single/multiple)<br>- Gaussian and Laplacian image pyramids<br>- Contour feature extraction and approximation* |
| **7. 直方图与傅里叶变换** <br> *Histograms and Fourier Transform* | - 直方图定义<br>- 均衡化原理及效果（mask掩码）<br>- 傅里叶概述<br>- 频域变换结果<br>- 低通与高通滤波<br><br>*- Histogram definition<br>- Equalization principles and effects (mask)<br>- Fourier transform overview<br>- Frequency domain transformation results<br>- Low-pass and high-pass filtering* |
| **8. 图像特征-harris** <br> *Image Features - Harris* | - 角点检测<br>- 基本数学原理<br>- 求解化简<br>- 特征归属划分<br>- 角点检测效果<br><br>*- Corner detection<br>- Basic mathematical principles<br>- Solution simplification<br>- Feature classification<br>- Corner detection results* |
| **9. 图像特征-SIFT** <br> *Image Features - SIFT* | - 图像尺度空间<br>- 多分辨率金字塔&高斯差分金字塔（DOG）<br>- 特征关键点的定位<br>- 生成特征描述<br>- 特征向量生成<br>- openCV SIFT函数<br><br>*- Image scale space<br>- Multi-resolution pyramid & Difference of Gaussians (DOG)<br>- Feature keypoint localization<br>- Feature description generation<br>- Feature vector generation<br>- OpenCV SIFT functions* |

## 工具与依赖 / Tools and Dependencies

- Python
- OpenCV (`cv2`)
- Jupyter Notebook

---

> 本笔记仅用于个人学习记录，欢迎参考和改进。  
> *These notes are for personal learning purposes only. Feel free to reference and improve upon them.*
