# CNAME解析

CNAME记录又叫别名记录，用来把域名解析到其他域名上，通常用于mail邮箱解析和CDN加速解析。

如果您的网站需要实现CDN加速，则配置CNAME是最关键的一步。开通CDN服务、添加域名成功后，CDN会分配对应的CNAME地址。您需要将域名指向CNAME地址，访问加速域名的请求才能转发到CDN节点上，达到加速效果。

CNAME指向的域名，最终也要指向A记录。

## 设置CNAME解析

1、登录`虚拟主机控制面板`。

![](https://i.loli.net/2021/08/14/Q46z5WNu8Psj7dq.png)

2、在控制面板的上方导航栏中，在`域名绑定`中，控制面板给出的CNAME解析信息，保存并记录。

![](https://i.loli.net/2021/08/15/xTbYZC7I9OBpAeQ.png)

3、这里以在阿里云注册的域名为例，登录`阿里云`并单击`控制台`>`域名解析`>`您所注册的域名`>`添加记录`。

![](https://i.loli.net/2021/08/15/elBoRy1Ouhtsdgf.png)

![](https://i.loli.net/2021/08/15/q7pmazyLZiAgNxM.png)

![](https://i.loli.net/2021/08/15/AupZs9MWVPrS6OR.png)

4、在`添加记录`中，注册类型选择`CNAME`、主机记录填写`www`或`@`即可。具体使用的方法可将鼠标移动到主机记录一栏右侧的`？`图标。

![](https://i.loli.net/2021/08/15/ovkCdHzasW1YiKt.png)

5、记录值填写虚拟主机控制面板中`域名绑定`给出的CNAME解析信息。

6、解析线路选择`默认`即可，无需更改。TTL选择`10分钟`的默认选项即可。

7、单击`确认`保存设置，输入您的域名即可访问网站。
