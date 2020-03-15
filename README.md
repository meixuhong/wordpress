# WordPress一键脚本
介绍：适用CentOS7，一键安装wordpress, ssl, v2ray

作者：atrandys, 波仔

修改：meixuhong

已集成破解主题：D85.1、DUX6.0、Git主题（推荐使用）

acme.sh的SSL证书申请为多域名适配，请输入绑定并解析的顶级域名（例：XXX.COM），请不要加上 www



> - ` latest-zh_CN.zip`文件为wordpress程序
> - ` wp_install.sh、wp_install_tls1.3.sh、wp_manual.sh`是atrandys原创脚本
> - ` v2ray_ws_tls_wp.sh`是波仔改进atrandys的脚本，体验最好，不过加载了v2ray
> - `wp_install_meixuhong_dl_from_internet.sh`是我改进波仔的脚本，只安装wordpress与证书，一些脚本与程序是从网上下载
> - `wp_install_meixuhong.sh`是最终改进版本，防止脚本与程序被和谐，均从github下载了，另外增加了Nginx开机自动启动功能，原脚本不含该功能，服务器重启时网站就进不去了

除此之外，把`acme.sh`脚本与wordpress主题都加进来了，包括：

> - D85.1
> - DUX6.0
> - Git