# Welcome to Python

Python 是一个高级语言，它以简洁著名。
为何说Python的语法简洁？
C语言：
```c
#include <stdio.h>
int main()
{
    printf("hello world/n");
    return 0;
}
```
Python:
```python
print("hello world")
```
看见了嘛，Python就是如此的简单明了。

## 进入Python的大门--Hello world
要想在IDLE中输出Hello world，就得用到一个函数——`print()`什么是print，print在英语中的意思是画，在Python中就对应在屏幕上输出某些东西。
光知道了怎么输出，还得知道要告诉他什么。
你不能直接输入`print(hello world)`，这样他会生气，会出现Syntax error！我们要如何解决呢？
这就不得不讲到数据类型了。
python的数据类型分为4种：
1. 数字类型 数字
2. 字符串 字母，一串话之类的
3. 容器类型 顾名思义 装一大堆数据的
4. 布尔类型 正确和错误

而我们的hello world是字符串，我们要加上""，这是字符串的象征。

接下来，开始尝试吧！

## 逻辑--编程的基础 1
假如一个人让你选择一个东西， 一个是苹果， 一个是柚子，你会选哪个？

Python也能判断选哪个：
```python
apple = "苹果"
apple_price = 5
youzi = "柚子"
youzi_price = 10
if apple_price < youzi_price:
    print(youzi)
else:
    print(apple)
```
看出哪里是判断了嘛？
没错，正是`if ...... else: ......`
if 在 Python中是如果......那么的意思，esle是否则的意思。
那他的结构应该就是这样的：
```python
if 条件:
    代码执行区
else:
    代码执行区
```
当然，你不要下面的`else`也可以的。

古人常说 不可纸上谈兵。快去试一试吧！

## 逻辑--编程的基础 2
假设有一个人要你拖地
你肯定要先洗拖把在*重复*拖地这个动作吧。
### 循环1
先看一段代码：
```python
while 1 < 5:
    print("hi")
```
你能猜出循环在哪里嘛？
没错正是在`while 1 < 5`这个部分。
while的结构是这样的：
```python
while 条件:
    代码执行区
```
while 的执行规则是：一直重复执行到条件不成立为止。
### 循环2
先看一段代码：
```python
for i in range(10):
    print("hi")
```
你能猜出循环在哪里嘛？
没错正是在`for i in range(10)`这个部分。
for .... in .....的结构是这样的：
```python
for 一个变量 in 一个可遍历的数据类型:
    代码执行区
```
for .... in ..... 的执行规则是：遍历对象的所有元素，并将变量设为元素。

