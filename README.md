# python
### 1 准备工作
- 1.1 安装 python 3.9, 直接去官网下载。
- 1.2 os 终端输入 python3 查询。
```
[Milins-MacBook-Air:~ Milin$] python3 
Python 3.9.5 (v3.9.5:0a7dcbdb13, May 3 2021, 13:17:02) 
[Clang 6.0 (clang-600.0.57)] on darwin
```
- 1.3 安装 sublime 和 pycharm

### 2 第一个程序
```python
def build_connection_string(params):
    """this is docstring""" # 这里需要使用双引号
    return (';'.join(['%s=%s' % (k, v) for k, v in params.items()]))
```
列表解析，格式：```';'.join(['','',''])```
主体部分：```'%s=%s' % (k, v)```  代表的是：```str(k) = str(v)``` 

### 3 列表 字典 集合 字符
#### 字典 dictionary
- 例如 ： ```dic = {'server':'mp','database':'master'}``` 由 key 和 value 组成，key：value，key就是关键字
- 类比查单词，key就是单词，value就是单词的解释内容，key是不能重复的，因为会把之前的key给覆盖掉。
- dictionary是无序的。
- ```dic.clear()```清除字典内容

#### 列表 lists
列表非常常用，是可以变化的数组，有顺序，元素类型很多
- 例如 ：```lists = ['a','b','c']``` 元素用逗号隔开
- 列表从 0 下标开始，-1 代表最后1个，-2 代表最后第二个 -3...-n
- 列表切片 slice，和切片面包一样，lists[:]代表切了整个列表，通常用来复制列表用的。lists[:3]代表 0-2，
  lists[4:]代表4到最后一个，lists[-3:]代表最后3个
- ```lists.append('d')``` 从列表最后一个后面增加一个
- ```lists.expend(['c','d'])``` 这个是把另一个列表添加进当前列表
- ```lists.insert(2,'c')``` 2代表下标位置插入新元素，后面的元素退一格
- ```lists.pop()``` 列表把最后面的元素删除
- lists里面没有找到该元素，则会报错，查询或者删除，都会报错
- 可以 + * 运算

