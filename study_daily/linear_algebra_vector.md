# 2017-12-03 vector
```
1. 线性代数课程目标：完成个人线性代数函数库；
2. 点：在笛卡尔坐标系中使用有序的两个数值x，y描述的元素称为一个点，表示一个位置；
3. 向量：描述的是一种变化，没有位置的概念；
4. 向量运算：
  加法：向量各个对应位置数值相加；
  减法：向量各个对应位置数值相减；
  标量乘法：向量每个数值均乘以该标量；
5. 向量大小：
  也就是两个点之间的距离，可以用勾股定理计算得到，是横纵坐标差的平方和再开方；
6. 向量方向：
  移动方向，箭头所指方向，也是一个向量，公式为(1/大小*向量自身)；
7. 单位向量：
  长度为1的向量，将某个向量通过乘法转换为单位向量的过程称之为标准化；
8. 零向量：
  各个位置的值均为0的向量，零向量无法进行标准化；
9. 点积，夹角：
  v1 . v2 = size_v1 * size_v2 * cos(向量夹角)
  v1 . v2 = v1_1 * v2_1 + ..... + v1_n * v2_n
  可以通过两个向量求出夹角
  夹角弧度为1时，向量方向相同，-1时，方向相反，为0时，两个向量正交
10. 平行：
  一个向量与任意标量乘以自身都是平行关系（注意乘以-1方向相反也是平行），两个向量点积结果为1或-1也是平行关系；
11. 正交：
  两个向量相乘为0时，有两种情况，要么其中之一为零向量，要么两个向量正交；
12. 特殊：
  零向量与任何其他向量都平行且正交，零向量是唯一一个与自己正交的向量；
13. 向量投影
  将一个向量投影到另一个向量上，是正交性的一 个场景，得到的两个分别平行和正交与basis向量的向量和即为原向量；
  公式：
  v_parallel = (v . u_b) * u_b
  v_orth = v - v_parallel
14. 向量除以自己的模：
  表示向量方向上的单位向量，也就是相对自己标准化；
15. 向量积 叉乘
  计算公式：
  [x1]   [x2]   [y1*z2 - y2*z1]
  [y1] x [y2] = [-(x1*z2 - x2*z1)]
  [z1]   [z2]   [x1y2 - x2y1]
  叉乘的结果也是一个向量，且该向量的大小为原两个向量形成的平行四边形的面积
```
