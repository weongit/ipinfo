借助Cloudflare弄的，可以查询ip的一些基础信息。
注：cloudflare规则由我完成，php代码由ChatGPT完成。代码地址 https://github.com/ytree001/ipinfo
要配合以下Cloudflare规则使用。方法二的规则自行研究。
Rules-Transform Rules-Modify Request Header


图1


![图1](https://github.com/weongit/ipinfo/blob/main/img/1.png)


效果：图2


![图2](https://github.com/weongit/ipinfo/blob/main/img/2.png)


2.从响应头里获取


![图3](https://github.com/weongit/ipinfo/blob/main/img/3.png)


里面的威胁指数就是Cloudflare 防火墙里面的IP Threat Score（威胁指数）的值
