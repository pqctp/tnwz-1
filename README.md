# tnwz
头脑王者辅助工具

本程序在这位大哥@chxj1992的基础上稍微改进了一下。

另外如果嫌慢，保存问题这部分代码可以注释掉，或者改用其他快点的读写方式。

## 使用说明：

这里以windows为例，linux大同小异。

安装mitmproxy：

```
pip install mitmproxy
```

执行listen.py：

```
mitmdump -p 8123 -s listen.py
```

手机连接到和电脑同一个wifi，设置代理内网ip+端口8123，然后手机浏览器访问`mitm.it`

下载并安装证书，ios需要设置信任(【设置】>【通用】>【关于本机】>【证书信任设置】)

然后就可以开始玩了。 正确的答案标识为`√True`