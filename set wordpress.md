##Wordpress构架##

想要本地电脑使用Wordpress构架和测试网页，不断更改和调试，但不会影响其他用户对网页的使用，我们需要下载本地Wordpress以及它的其他应用程序，例如MAMP。

MAMP是一个集合的应用，它可以让你使用本地电脑的PHP和MySQL客户端，便于测试和发展本地的Wordpress。

这种架构方式下载需要如下几步：

- 下载MAMP到应用程序，双击打开并安装
- 下载Wordpress文件夹
- “start server” MAMP
- “Open start page”
- 新建一个文件夹，名为“Wordpress”（database name）
- 打开MAMP文件夹中的htdocs，复制Wordpress文件夹中所有文件，以及本身文件夹和压缩包到htdocs中
- 更改htdocs中wp-config-sample.php为wp-config.php，打开文件，并更改database name为“Wordpress”，以及database user和database password
- 登陆wp-admin/install.php，更改密码与用户名
- 登陆本地Wordpress并进行测试更改
- 完成