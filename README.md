# http代理ip提取程序
<p>
<img src='https://img.shields.io/badge/author-%E5%B0%8F%E5%B7%9D-ff69b4.svg'>
<img src='https://img.shields.io/github/license/2239559319/courseDownload.svg?style=flat'>
<img src='https://img.shields.io/badge/python-3.0%2B-blue.svg'>
<img src='https://img.shields.io/badge/python-3.6-blue.svg'>
</p>

-----------

- 运行python3
- 第三方包requests
- 安装
```bash
pip install xiaochuanipproxy
```
- 使用
```python
import xiaochuanipproxy

xiaochuanipproxy.start()    #等到程序输出提取完毕即可调用
print(xiaochuanipproxy.getip())    #返回一个ip
```
- 每次提取的IP大概有30个
- 提取的网站有:西刺代理.快代理.89免费代理.5u代理.米扑.yqie
相应的函数getxiciip(maxpage),getmipuip(),get5uip(),get98mianfeiip(maxpage),getkuaidailiip(maxpage),getyqieip

-----------
<img src="https://pypi.org//static/images/logo-small.6eef541e.svg">

## 开发者版本xiaochuanipproxy已经上传至pypi，[进入pypi页面][1]


  [1]: https://pypi.org/project/xiaochuanipproxy/