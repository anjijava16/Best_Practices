Apache Spark🚀🪟1-Minute-Read⌛

📊Deep Dive in Spark UI - Executors Page

🤔Explore each metric:

1️⃣ RDD Block:
This metric represents the number of RDD blocks that are currently stored in memory or on disk by the executor. RDD blocks are the partitions of data that are cached or persisted in Spark's memory/disk storage.

2️⃣ Storage Memory:
This metric shows the amount of memory being used by the executor to store data. This includes the memory consumed by RDD blocks, broadcast variables, and other cached data.

3️⃣ Disk Used:
This metric indicates the amount of disk space utilized by the executor to store data that does not fit in memory. When the memory is insufficient to hold all the data, Spark spills the excess data to disk for temporary storage.

4️⃣ Cores:
This metric denotes the number of CPU cores allocated to the executor. Spark applications can be configured to use multiple cores for parallel processing, and this metric shows how many cores are assigned to the executor.

5️⃣ Active Tasks:
This metric represents the number of tasks that are currently being executed by the executor. Tasks are the smallest unit of work in Spark, and multiple tasks can be executed concurrently on an executor.

6️⃣ Failed Tasks:
This metric indicates the number of tasks that have failed to execute successfully on the executor. This can happen due to exceptions, errors, or resource constraints.

7️⃣ Complete Tasks:
This metric shows the number of tasks that have been successfully executed and completed by the executor.

8️⃣ Total Tasks:
This metric represents the total number of tasks (active, failed, and completed) that have been assigned to the executor since its start.

9️⃣ Task Time (GC Time):
This metric measures the total time taken by the executor to execute tasks, including any GC time. GC is the process of reclaiming memory occupied by objects that are no longer needed.

🔟Input:
This indicates the amount of data read by the executor from external sources or from previous stages in the Spark application. It represents the input size processed by the executor.

1️⃣1️⃣ Shuffle Read:
This metric represents the amount of data shuffled and read by the executor during the execution of shuffle operations. Shuffle is a data exchange mechanism in Spark that redistributes data across partitions.

1️⃣2️⃣ Shuffle Write:
This metric shows the amount of data shuffled and written by the executor during the execution of shuffle operations. This metric indicates the amount of data being written to disk or transmitted over the network during shuffling.

1️⃣3️⃣ Excluded:
This metric is typically used in dynamic resource allocation scenarios. It denotes whether the executor is currently excluded from receiving new tasks due to resource management policies or constraints.

Tagging Sumit Mittal TrendyTech for visibility.
#onestepanalytics #spark #learningandgrowing #sparkui #distributedcomputing
Activate to view larger image,
![image](https://github.com/anjijava16/Best_Practices/assets/5849522/2b4124cc-ee8c-41c9-914d-d408f8bfda60)
