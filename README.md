# pycharm

 #Setting Env
 http://dimajix.de/running-pyspark-on-anaconda-in-pycharm/?lang=en

# calling pyspark spark submit
 spark-submit --jars  /home/yp84670g/two_way/spark-streaming-kafka-assembly_2.10-1.6.3.jar --packages com.datastax.spark:spark-cassandra-connector_2.10:1.6.3 --conf spark.cassandra.connection.host=dlake01.creighton.edu  readFromDb.py dlake01:6667 phone_addr_ds


This Project Contains Spark Streaming and Kafka integration for reliable streaming with checkpointing enabled.