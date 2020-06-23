
# 优缺点
## Python的优点很多，简单的可以总结为以下几点。

    简单和明确，做一件事只有一种方法。
    学习曲线低，跟其他很多语言相比，Python更容易上手。
    开放源代码，拥有强大的社区和生态圈。
    解释型语言，天生具有平台可移植性。
    支持两种主流的编程范式（面向对象编程和函数式编程）都提供了支持。
    可扩展性和可嵌入性，可以调用C/C++代码，也可以在C/C++中调用Python。
    代码规范程度高，可读性强，适合有代码洁癖和强迫症的人群。

## Python的缺点主要集中在以下几点。

    执行效率稍低，因此计算密集型任务可以由C/C++编写。
    代码无法加密，但是现在很多公司都不销售卖软件而是销售服务，这个问题会被淡化。
    在开发时可以选择的框架太多（如Web框架就有100多个），有选择的地方就有错误。

# Python的应用领域
    目前Python在Web应用开发、云基础设施、DevOps、网络爬虫开发、数据分析挖掘、机器学习等领域都有着广泛的应用，因此也产生了Web后端开发、数据接口开发、自动化运维、自动化测试、科学计算和可视化、数据分析、量化交易、机器人开发、图像识别和处理等一系列的职位。
    
# 查看python版本
    python --version or python -V
    import sys;print(sys.version);
   
# 运行.py文件
    python demo.py
    python3 demo.py
   
# 注释
    单行注释 - 以#和空格开头的部分
    多行注释 - 三个引号开头，三个引号结尾
    
# 安装notebook
    pip3 install ipython
    pip3 install jupyter
    jupyter notebook

# python之禅


```python
import this
```

    The Zen of Python, by Tim Peters
    
    Beautiful is better than ugly.
    Explicit is better than implicit.
    Simple is better than complex.
    Complex is better than complicated.
    Flat is better than nested.
    Sparse is better than dense.
    Readability counts.
    Special cases aren't special enough to break the rules.
    Although practicality beats purity.
    Errors should never pass silently.
    Unless explicitly silenced.
    In the face of ambiguity, refuse the temptation to guess.
    There should be one-- and preferably only one --obvious way to do it.
    Although that way may not be obvious at first unless you're Dutch.
    Now is better than never.
    Although never is often better than *right* now.
    If the implementation is hard to explain, it's a bad idea.
    If the implementation is easy to explain, it may be a good idea.
    Namespaces are one honking great idea -- let's do more of those!
    

# 使用turtle绘图


```python
import turtle
turtle.pensize(4)
turtle.pencolor('red')
turtle.forward(100)
turtle.right(90)
turtle.forward(100)
turtle.right(90)
turtle.forward(100)
turtle.right(90)
turtle.forward(100)
turtle.mainloop()
```
