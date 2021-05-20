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
    """this is docstring"""
    return (';'.join(['%s=%s' % (k, v) for k, v in params.items()]))
```
列表解析，格式：```';'.join(['','',''])```
主体部分：```'%s=%s' % (k, v)```  代表的是：```str(k) = str(v)``` 

### 3 列表 字典 集合 字符
#### 字典 dictionary
