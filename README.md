# 98tinyPNG

TinyPNG 批量压缩图片脚本



## 一、环境配置



1.Python 环境，

2.tinyPNG sdk
``` ruby
sudo pip install --upgrade tinify
```


## 二、申请 AppKey

到[ TinyPNG 网站](https://tinypng.com/developers)上去申请 AppKey，一个月只能压缩 500 张

## 三、下载并运行脚本


``` python
tinify.key = "your AppKey" # AppKey
fromFilePath = "/Users/zpy/Desktop/test1" # 源路径
toFilePath = "/Users/zpy/Desktop/test2"   # 输出路径
```

运行脚本。打开终端：

``` ruby
python /Users/zpy/Documents/STTinyPNG-Python/98tinyPNG-Python.py
```



