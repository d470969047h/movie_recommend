[基于Spark ALS在线电影推荐系统](https://blog.csdn.net/fansy1990/article/details/52289826)

所用技术：
Bootstrap、flat-ui 、 Servlet、Spark、Hadoop


部署：
1. 拷贝spark-assembly-1.4.1-hadoop2.6.0.jar到WebContent/WEB-INF/lib目录；
（spark-assembly-1.4.1-hadoop2.6.0.jar文件由原生spark-assembly-1.4.1-hadoop2.6.0.jar删除javax/servlet包获得，由于太大，所以就没有上传了）；
2. 拷贝原生spark-assembly-1.4.1-hadoop2.6.0.jar文件到HDFS（目录和代码中一致）；
3. 拷贝WebContent/WEB-INF/lib目录中的Spark141-als.jar到HDFS（目录和代码中保持一致）；
4. 拷贝Hadoop集群（调用所使用的集群，每个人不一样）配置文件yarn-site.xml到HDFS（目录和代码中保持一致）；
