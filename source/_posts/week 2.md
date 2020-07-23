title: 2 Week in Poizon
date: 2020-07-21
tags: 实习
---
# django 静态文件404（问题解决）
#### 在总文件夹下创立新的static
#### 将需要放置的静态文件/图片放入新创建的static而不是子程序的static里
#### 将setting中的路径改成 <import os.path>
#### 用Debugger 再次刷新重启网页