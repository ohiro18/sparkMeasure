# testSparkMeasureScala

This is example code of how you can use sparkMeasure to instrument your Scala code
running Apache Spark workloads.  
More info at [https://github.com/LucaCanali/sparkMeasure]

How to run a test:
```
# build the jar
sbt package

bin/spark-submit --packages ch.cern.sparkmeasure:spark-measure_2.11:0.15 --class ch.cern.testSparkMeasure.testSparkMeasure <path>/testsparkmeasurescala_2.11-0.1.jar
```
