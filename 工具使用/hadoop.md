#命令
hadoop-daemon.sh start namenode  启动namenode
hadoop-daemon.sh stop namenode   停止namenode
hadoop-daemon.sh start datanode  启动datanode
hadoop-daemon.sh stop datanode  停止datanode
hadoop fs -ls / 查看hdfs根目录文件
hadoop fs -put xxx.xxx / 上传文件到hdfs根目录
hadoop fs -get /xxx.xxx 下载文件
hadoop fs -mkdir -p /a/b 创建批量文件夹
#hadoop网页页面
kugoufeng00:50070