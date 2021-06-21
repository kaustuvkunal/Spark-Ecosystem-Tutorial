## Spark Commands : ( run from spark home directory)

- Start master : 
  `sbin/start-master.sh`
  
- Start slaves (in case of multi node cluster):
  `start-slave.sh spark://host_name:7077`
  
- Start worker with one core : 
  ` start-slave.sh -c 1  spark:// localhost:7077 `
  
- Start worker with three core : 
  ` start-slave.sh -c 3  spark://localhost:7077`
  
 - Submiting an example Spark application on HDFS : 
  `spark-submit master yarn sparktest.py  /input/bidWin.log  /output/pysparkout`
    
    
- Start historyserver :
    `sbin/mr-jobhistory-daemon.sh   start historyserver`
