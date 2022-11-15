# Creating an AWS Glue job with custom parquet file names
## Unfortuantely, spark does not allow for the name of a file to be customized on creation.
## However this is fixed by creating a copy of the created file with a custom name and deleting the old file.
