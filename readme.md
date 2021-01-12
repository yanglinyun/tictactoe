# 前端实现井字棋
# 演示地址
<a href ="https://yanglinyun.github.io/five-in-a-row/">https://yanglinyun.github.io/five-in-a-row/</a>

# 實現效果UI
<img src="./实现效果.PNG">

# 使用技術: HTML5\CSS3\JS
# 第三方库: Jquery
# 兼容性: chrome\edge\safari\firefox 移动端百分比响应式
# 简介:
1. 使用前端cavas技术绘制 3X3 井字棋标准棋盘、棋子
2. 使用js实现走棋规则 与 吃子规则
# 具体功能:
1. X先O后
3. 使用二维数组存储地图,从当前下子的位置向上下左右，左上右上右下左下2个长度检测是否连3子，连则判胜!
4. 使用对象深拷贝实现可悔棋1步
5. 重玩
