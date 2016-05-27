# angular.io 中文版

这里是angular.io字幕组，哦不对，是汉化组。译者汪志成(雪狼)和叶志敏(Rex)欢迎您的到访。

我们将和官方英文版保持同步翻译，并同步发布到国内镜像 - <http://www.angular.live>，
将来还会发布到官方中文站 - <https://cn.angular.io/>。

## 授权协议
本文档遵循[“保持署名—非商用”创意共享4.0许可证（CC BY-NC 4.0）](http://creativecommons.org/licenses/by-nc/4.0/deed.zh)，请在**保持署名**、**非商用**的前提下自由使用，你甚至可以把它架设在自己的电脑或内网服务器上。

特别是：

- **不得去掉**“关于中文版”的入口链接，也不得增删改“关于中文版”页的内容。
- 如果您是**商业网站（包括但不限于任何有广告或收费的网站）**要发布或转载，请联系我们 asnowwolf@gmail.com 和 rexebin@gmail.com 。

**违反上述授权协议将面临法律追究。**

## 编译与发布

1. 用`git clone https://github.com/angular/angular-cn.git`把本项目取到本地。
1. 进入`angular-cn`目录
1. 运行`npm install`安装依赖包
1. 运行`gulp check-deploy`命令进行编译并预览（会自动打开浏览器并访问8080端口）
1. 把`./www`目录发布到任何静态文件服务器上

如果是内网服务器，你还可以通过自建CI进行同步更新。

## 更多信息

关于本中文版以及两位译者的更多信息，请参见[“关于中文版”](http://www.angular.live/translate/cn/about.html)链接。
