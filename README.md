# 计数不对的『豆瓣豆列』抓取

## 豆列计数不对的问题说明

- 总共条目少了。
- 自己通过 总共条目数 小于 分项条目数（书、链接）发现的。

这会导致

- 豆列里后面少于总数的条目编辑顺序。
- 多出1页（1页25个条目）之后的条目不能查看。

----------------

豆列计数不对的截图（以豆列[函数式编程/Functional Programming/FP](https://www.douban.com/doulist/45730623/)示例）：

<img src="https://user-images.githubusercontent.com/1063891/67363289-a21e2300-f59f-11e9-9319-8dd3433195d8.png" width="500" hspace="10px" >

## 通过`Python`抓取页面找出计数不对的豆列

实现参见`Jupyter Notebook`： [doulist_wrong_counter_analysis.ipynb](doulist_wrong_counter_analysis.ipynb)。
