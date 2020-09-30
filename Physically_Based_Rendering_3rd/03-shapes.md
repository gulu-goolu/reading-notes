# Shapes

Shape 可以作为场景中的几何体，提供几何信息。

shape 提供了下面的功能：

- 从模型坐标系到世界坐标系的转换，从世界坐标系到模型坐标系的转换
- 相交检测
  - 光线和包围盒的相交检测
  - 光纤和 shape 的相交检测
- 表面积。

## Questions

### 1. Shape 和 Primitive 的区别

shape 只提供 geometry 的信息，primitive 提供了额外的信息
