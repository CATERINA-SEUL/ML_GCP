#### 1. Which of these accurately describes the relationship between Apache Beam and Cloud Dataflow?

A : Cloud Dataflow is the API for data pipeline building in java or python and Apache Beam is the implementation and execution framework.

#### 2. TRUE or FALSE: The Filter method can be carried out in parallel and autoscaled by the execution framework:

A : True: Anything in Map or FlatMap can be parallelized by the Beam execution framework.

#### 3. What is the purpose of a Cloud Dataflow connector?

    .apply(TextIO.write().to(“gs://…”));

A : Connectors allow you to output the results of a pipeline to a specific data sink like Bigtable, Google Cloud Storage, flat file, BigQuery, and more…

#### 4. Below you'll find a Cloud Dataflow preprocessing graph. Correctly identify the terms for A, B, and C.

A : A is a data source, B are transformation steps, and C is a data sink.

#### 5. To run a pipeline you need something called a ________.

A : runner

#### 6. Your development team is about to execute this code block. What is your team about to do?

    mvn compile -e exec:java\
        -Dexec.mainClass=$MAIN\
        -Dexec.args="--project=$PROJECT\
        --stagingLocation=gs://$BUCKET/staging/\
        --tempLocation=gs://$BUCKET/staging/\
        --runner=DataflowRunner"

A : We are compiling our Cloud Dataflow pipeline written in Java and are submitting it to the cloud for execution.

#### 7. TRUE or FALSE: A ParDo acts on all items at once (like a Map in MapReduce).

A : False. A ParDo acts on one item at a time (like a Map in MapReduce)