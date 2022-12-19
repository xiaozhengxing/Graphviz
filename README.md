# Graphviz

这里用来保存一些Graphviz的用法, 直接保存在readme中好了

在之后的snapShot里面需要使用到



# 一、组成 
1. 图: graph(无向图), diagraph(有向图)
2. 子图: subgraph
3. 节点
4. 边
5. 属性


# 命令行格式
将test.dot文件转成test.jpg保存

...>Graphviz\\dot -T jpg test.dot -o test.jpg

将test.dot文件转成test.pdf保存

...>Graphviz\\dot -T pdf test.dot -o test.pdf

# 简单写法
test.dot
```
digraph MyGraph//有向图
{
  a ->b ->c;
  d ->b;
}
```
# 结果
![image](https://user-images.githubusercontent.com/19707595/207047048-c6dfad31-b69c-4627-b33f-b19ffb70e651.jpg)


```
graph//无向图
{
	a--b--c;
	b--d;
}
```
![image](https://github.com/xiaozhengxing/Graphviz/blob/main/imgs/%E6%97%A0%E5%90%91%E5%9B%BE.jpg)
