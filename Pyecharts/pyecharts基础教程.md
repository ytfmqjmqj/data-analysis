# pyecharts绘图
# 1.柱状图
from pyecharts import Bar
bar = Bar('基本柱状图', '这里是副标题')
bar.add('服装',['衬衫', '羊毛衫', '雪纺衫', '裤子', '高跟鞋', '袜子'],
       [5, 20, 36, 10, 75, 90],
       is_more_utils = True)
bar
