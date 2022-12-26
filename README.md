#飞机目标检测提取
* 利用圆周滤波进行飞机目标检测，并且用种子生长法提取目标，用Huffman编码保存图像，用c++实现
* 更新了python版本的飞机目标检测，将圆周滤波（实在是太慢了）与种子生长分成两步，同样有c++版本的问题，即圆周滤波找到的坐标点并不是正好在飞机上
- version2里面圆周滤波之前将图像进行二值化处理，提升了精度
