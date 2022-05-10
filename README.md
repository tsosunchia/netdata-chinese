# netdata 简体中文版

感谢
[@jasoncheng7115](https://github.com/jasoncheng7115/netdata-cpatch)
[@YuanzhuL](https://github.com/YuanzhuL/netdata-cpatch)
做出的贡献

## netdata 的安装

(如果你还没安装 netdata, 安装执行这行即可)

```shell
wget -O /tmp/netdata-kickstart.sh https://my-netdata.io/kickstart.sh && sh /tmp/netdata-kickstart.sh
```

## 使用说明

请将这 4 个文件下载，覆盖至路径 `/usr/share/netdata/web/` (新版 netdata 位置改到了`/var/lib/netdata/www/`，看哪个位置有这几个文件即可)
<br> 【【请先备份】】

- dashboard_info.js
- dashboard.js
- main.js
- index.html

完成后请刷新网页，chrome 请清除浏览器缓存试试
