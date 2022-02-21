# FluentD with mongo db

## Collecting logs from files

Fluentd enables your apps to insert records to MongoDB asynchronously with batch-insertion, unlike direct insertion of records from your apps. This has the following advantages:

- less impact on application performance
- higher MongoDB insertion throughput while maintaining JSON record structure