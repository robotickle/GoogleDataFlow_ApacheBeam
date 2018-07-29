**Repo Details**
- Repository for HandsOn with Apache Beam, to create data pipelines, and deploy them on google cloud.
Languages used are Python and Java.

1. training-data-analyst/courses/data_analysis/lab2/python

**SECTION I**
- Write a simple pipeline in Python
- query execution on the local machine
- query execution on google cloud
- associated files
  1. Job1.py
  2. 2.Submit-Job1-to-DataFlowOnGoogleCloud.py

**move data to Google DataStore Bucket.
-  ```$ gsutil cp ../javahelp/src/main/java/com/google/cloud/training/dataanalyst/javahelp/*.java gs://<Unique-Bucket-ID>/javahelp```
- ```$ python RunDataFlowonGoogleCloud.py```
- check your file on Google cloud storage with bucketID.
- ```$ gsutil cat gs://<YOUR-BUCKET-NAME>/javahelp/output-* ```



**SECTION II**
- Use pipeline options in Dataflow
- Carry out mapping transformations
- Carry out reduce aggregations

- associated files
  1. 3.MapReduce_CloudFlow_ApacheBeam.py


**SECTION III**

Coming Soon.

*source*
- https://github.com/GoogleCloudPlatform/training-data-analyst
- https://cloud.google.com/bigquery/public-data/

