# flxe有哪些重要的属性

1. display:flex （让一个元素变成flex容器）
2. flex-direction:row /column （改变items流动方向）
3. flex-wrap:wrap（改变折行）
4. justify-conent:center /space-between（主轴对齐方式）
5. align-items:center (次轴对齐)

## 浏览器的渲染过程
1. 根据HTML构建HTML树（DOM）
2. 根据CSS构建CSS树（CSSOM）
3. 将两棵树合并成一颗渲染树 （render tree）
4. Layout布局 （文档流，盒模型，计算大小和位置）
5. Paint绘画 （把边框颜色，文字颜色，阴影等画出来）
6. Compose合成 （根据层叠关系展示画面）


### transform的四种常用功能
* translate (位移)
* scale (缩放)
* rotate (旋转)
* skew (倾斜)

#### CSS动漫的两种方法（transition和animation）
* transiton的作用：补充中间帧
* 语法
1. transition:属性名 时长 过渡方式 延迟
2. transition:left 200ms linear
3. 可以用逗号分隔两个不同属性
4. transition:left 200ms , top 400ms
5. 可以用all表示所有属性
* animation
1. 声明关键帧
2. 添加动画
3.如何让动画停在最后一帧：加forwards





















