# convenient-tools
工作中的便利工具记录，主要包括：

linux常用工具

1 文件夹操作相关
touch filename #创建文件 
mkdir dirname  #创建文件夹
cp /source-dir/filename /dst-dir/filename  #copy文件
scp $JENKINS_HOME/qar.tar.gz root@10.108.10.99:/data1/tars/hr.tar.gz  #远程copy文件

tar -zcvf /tmp/home.tar.gz /home  #将整个 /home 目录下的文件全部打包成为 /tmp/home.tar  打包后，以 gzip 压缩

