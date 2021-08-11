# GithubFile
一款基于github仓库实现附件储存的typecho插件

最近更新:更新错误定位

服务器我一个人维护太困难了 如果能够提供支持不甚感谢

[![](https://img.shields.io/github/license/MliKiowa/GithubFile)](https://github.com/MliKiowa/GithubFile/blob/master/LICENSE)
[![Test](https://github.com/MliKiowa/GithubFile/actions/workflows/php.yml/badge.svg)](https://github.com/MliKiowa/GithubFile/actions/workflows/php.yml)
# 推荐运行环境
PHP Version：7.4

PHP Http Support：Curl or Socket

System: Linux

# 如何使用？

1.下载插件

2.解压到插件目录，将插件文件夹更名GithubFile

3.启用插件，到设置面板获取Token

4.填入其它插件设置

5.开启伪静态(未开启可导致授权失败)

6.上传附件即可使用插件

# 如何搭建授权服务器?

1.下载Auth.php

2.放置到网站主目录

3.申请github oauth 获取client_id client_secret

4.打开Auth.php修改相应参数 (https_open 在https可开启)

5.到插件设置修改插件的授权服务器
# 查找错误
1.开启调试模式

2.操作引发错误的过程

3.打开插件下Cache目录,找到对应时间的log文件

4.发给开发者
# Todo
## Ver 1.0.3
1.二次验证配置

2.优化插件配置获取函数，提高速度

3.日志快速发送开发者 (并且提供专用log目录)
# 例图
![](https://ftp.bmp.ovh/imgs/2021/07/60dcee304550cc59.jpg)
# 反馈
快进来玩
QGroup 加入群聊[【雪风的茶楼】](https://jq.qq.com/?_wv=1027&k=rua8g2lN)

By Mail : 946735494@qq.com

By QQ : 946735494

# 提示
本插件通过第三方Oauth如果你对此方法介意 
1. 可以获取官方personsal key填入token
2. 搭建自己的授权服务器
