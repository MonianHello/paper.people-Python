# 人民日报爬虫
  

> 版权声明：本文为CSDN博主「机灵鹤」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
> 原文链接：https://blog.csdn.net/wenxuhonghe/article/details/90047081

**此仓库代码均来自[「机灵鹤」文章](https://blog.csdn.net/wenxuhonghe/article/details/90047081)，**非原创**，仅为了方便使用创建此库。**

请注意运行之前是否安装了以下库(推荐使用国内镜像站下载)

    import requests
    import bs4
    import os
    import datetime
    import time
    import sys
    import argparse

每日会对当天人民日报文章进行爬取，保存在此仓库内，使用此爬虫得到的文件结构与此相同 


`requests.exceptions.HTTPError: 404 Client Error: Not Found for url`一般表示还没有该天的报纸（即未发布

