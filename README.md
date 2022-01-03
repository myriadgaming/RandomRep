Hadoop dfsadmin -safemode leave                        
Hadoop fs -mkdir /input_dir                       
Hadoop fs -put C:/wordcount.txt /input_dir                       
Hadoop dfs – cat /input_dir                      
Hadoop fs -ls /input_dir                      
Hadoop jar C:/MapReduceClient.jar wordcount /input_dir /output_dir                       
Hadoop dfs -cat /output_dir/*
