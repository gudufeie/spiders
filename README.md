##**QQSpider1:**##
<br/>
如果出现报错：
```
Traceback (most recent call last):
  File ".\init.py", line 20, in <module>
    my_messages.backups() # 备份爬虫信息
NameError: name 'my_messages' is not defined
```

<br/>
多半的原因是 BitVector 模块用不了，可自行调试。
<br/>
如果确定是BitVector用不了的话可以用 "BitVector模块报错解决" 里面的两个文件替换掉原有文件，不使用BitVector判重，改用python的list判重（数据量不大的话效果是一样的）。

<br/>
<br/>
-------------------------------------------------------&nbsp;&nbsp;&nbsp;分界线&nbsp;&nbsp;&nbsp;-------------------------------------------------------
<br/>
<br/>
##**QQSpider2:**##
<br/>
遇到什么问题请尽量留言，方便后来遇到同样问题的同学查看。
<br/>
<br/>
