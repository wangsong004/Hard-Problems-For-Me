# 
1. 线段(segment)和三角网格(mesh)的最小带符号距离计算 . （有若干条线段都需要对同一个mesh 进行最小带符号距离计算）
2. 对于开轮廓的三角网格面片进行单方向的加厚，生成一个封闭的实体算法
3. 两个封闭的三角网格（a和b）进行布尔运算，通常情况下要分别对a 和b 求出所有自相交的三角形，然后再进行布尔运算。有没有办法不需要分别求出所有的自相交三角形，而能给出一个合理的布尔运算结果？