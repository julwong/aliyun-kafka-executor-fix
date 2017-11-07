# aliyun-spark-kafka-patch
修改 fixKafkaParams，给 executor 的 group.id 增加 CID_ 前缀，适配阿里云的 kafka．
# 使用
git clone git://github.com/apache/spark.git
git checkout -b v2.1.1 v2.1.1
下载 aliyun-spark-kafka.patch
git apply aliyun-spark-kafka.patch
