# spring-xd
Spring-XD examples

Stream examples

JSON to JDBC: 
  Steps to create a stream to import JSON data into a database
    source tail: text files with JSON content
    sink: jdbc

Job examples

  CSV to JDBC:
    Steps to create a job to import CSV data into a database
      uses built-in batch job filejdbc
      defines database connection properties in job definition
      

Mixing Jobs and Streams

  CSV to HDFS
    Steps to create a job to import CSV data
    Then create a stream with a file source to scan a directory for files and drive the job.
