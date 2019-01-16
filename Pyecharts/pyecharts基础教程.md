# pyecharts绘图
# 1.柱状图
from pyecharts import Bar  
bar = Bar('基本柱状图', '这里是副标题')  
bar.add('服装',['衬衫', '羊毛衫', '雪纺衫', '裤子', '高跟鞋', '袜子'],  
       [5, 20, 36, 10, 75, 90],  
       is_more_utils = True)  
bar  
![基本柱状图](https://github.com/ytfmqjmqj/data-analysis/blob/master/Pyecharts/%E5%9F%BA%E6%9C%AC%E6%9F%B1%E7%8A%B6%E5%9B%BE.png)
