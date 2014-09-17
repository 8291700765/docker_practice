##docker仓库

仓库是集中存放镜像文件的场所，分为公有仓库和私有仓库2种形式。

公有仓库，目前仅有[Docker Hub](https://hub.docker.com)，提供了一个数量庞大的镜像库供用户下载。当然，用户也可以在本地网络内创建一个私有仓库。

当用户创建了自己的镜像之后就可以使用push命令将它上传到公有或者私有仓库，这样下次在另外一台机器上使用这个镜像时候，只需要从仓库上pull下来就可以了。


*Docker Hub的功能跟GitHub类似；push和pull操作跟git的操作类似。