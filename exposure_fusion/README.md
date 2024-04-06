将需要融合的图像序列加入到input文件夹中，最终结果会输出在out文件夹中。

out文件夹中会输出三种结果：

naive：最简单的融合，结果较粗糙

gaussi_smoothed：高斯平滑结果

laplace_pyramid：使用laplace金字塔融合结果，一般选用该图像作为最终结果