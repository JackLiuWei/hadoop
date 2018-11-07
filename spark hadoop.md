### spark节点：
![Image text](https://github.com/JackLiuWei/hadoop/blob/master/JLUJLPPOTA28~WT%25CIB%25%7D_9.png)
### （1）Spark：
* Spark应用程序：有几个job构成
* job:由几个stage构成
* stage：对应一个taskset

### DriverProgram
* 它是Spark的核心组件
* 构建SparkContext(spark应用的入口，创建需要的变量，还包含集群的配置信息等)
* 根据策略将DAG图转换成划分为多个stage
