# Interview-questions
  
1.我做过的笔试题和一些面试经历  
2.面试难度总共为5星，笔试难度总共为5星  
3.基本为python、web方面
---
1.寒武纪科技  
面试岗位：python web开发实习生  
面试难度：2星  
笔试难度：2星
***
笔试题：
* 另类乘法,123x45=1x4+1x5+2x4+2x5+3x4+3x5=54  
```python
a = '123'
b = '45'
s = 0
for i in a:
    for j in b:
        s += int(i) * int(j)
print(s)
```
* 给一个长度为奇数的数组,n=[1,3,5,7,1,3,5,7,9],求出里面无重复的元素
```python
方法1:
n = [1, 3, 5, 7, 1, 3, 5, 7, 9]
res = set(n)
for i in list(res):
    if n.count(i) == 1:
        print(i)
 
 方法2:
n = [1, 3, 5, 7, 1, 3, 5, 7, 9]
s=set(n)
for i in s:
    if n.count(i)==1:
        print(i)
```
---
评价：面试的很全面，简历上写的东西全问，还涉及一些算法相关的问题。不过整体难度不大，并且数据结构相关没有涉及。

***
---
2.奇游科技  
面试岗位：python web开发实习生  
面试难度：未进面试  
笔试难度： 4星  
----
笔试题：
* 给定列表，统计重复元素个数
```python
n = [1, 2, 3, 1, 2, 2, 4]
a = {}
for i in n:
    if n.count(i) > 1:
        a[i] = n.count(i)
print(len(a))

```
* python实现快排
```python



```
---
评价：笔试过去很久，题目搞忘很多。当时是给45分钟，做大概15道题，除了4道编程题其他都是问答题，笔试时感觉难度很大。不过公司在阿里巴巴大楼里面，而且环境很好。有机会再去试一试吧。
***
---
3.悟空找房  
面试岗位：爬虫工程师(实习)  
面试难度：5星  
笔试难度：无笔试
---
面试内容：  
http协议  
网络报文  
css选择器  
spring mvc中的ioc，aop  
正则表达式  
爬虫业务  
爬虫的反爬  
数据库的操作和优化  
数据库运行原理  
java中接口和抽象类的区别  
---
评价：一共有两轮面试，都是技术面试。问的比较深入，比如http协议，数据库运行原理。总体难度和正式找工作差不多
。
