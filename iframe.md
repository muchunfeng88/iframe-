iframe  会阻塞主页面的Onland 事件

搜索引擎的 的检索程序无法解读这种页面

ifame 和主页面共享连接池 ,而浏览器对相同域的连接有限制左右,所以影响页面的并行加载





解决方法:



最后通过 javascript 动态给iframe 添加src 属性值

