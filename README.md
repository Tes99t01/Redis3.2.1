
下载redis-3.2.1.tar.gz解压到指定位置，
执行make （对Redis解压后文件进行编译）；
执行make install (安装redis支持环境)；
上述执行无错即可将解压后的文件删除，主要使用Redis-3.2.1.tar进行redis缓存操作。

附件(Redis-3.2.1.tar)是基于linux redis-3.2.1.tar.gz  make 及 make install后的使用文件，将文件放入制定目录即可。解压文件后分别有bin目录、conf目录及redisManager文件，通过配置redisManager中的端口及IP后，可使用redisManager文件进行启动、停止操作。

#启动redis

./redisManager start

#停止redis

./redisManager stop
