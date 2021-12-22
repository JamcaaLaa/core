# core

OpenSpacing 的核心部分，早期用于收集向量、矩阵等基础数学计算，并输出简单的 glTF，处理空间分割（quadtree、octree）等。

暂使用 GeoJSON 作为中间格式，借助 earcut.js 生成三角形平面网格。
