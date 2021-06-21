## Spark Commands : (From spark home directory)

- Start master : 
  `sbin/start-master.sh`
  
- Start slaves :(in case of multi node cluster):
  `start-slave.sh spark://host_name:7077`
  
- Start worker with one core 
  `start-slave.sh -c 1  spark:// localhost:7077`
  
- Start worker with three core 
  `start-slave.sh -c 3  spark://localhost:7077
  
 - Run Spark on HDFS 
  `spark-submit master yarn sparktest.py  /input/bidWin.log  /output/pysparkout`
    ```bin/spark-submit --class org.apache.spark.examples.SparkPi \
    --master yarn \   
    examples/jars/spark-examples*.jar \
    10```
    
    
- start historyserver
    `sbin/mr-jobhistory-daemon.sh   start historyserver`
