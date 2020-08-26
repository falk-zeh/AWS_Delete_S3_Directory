# Delete S3 Directory

By default this script deletes the entire directory/ key header of a given s3 path/ key.

## Example
```./delete_s3_directory.sh s3://dummy_bucket/dummy_key1/```
This will delete dummy_key1 and everything below.

```./delete_s3_directory.sh s3://dummy_bucket/dummy_key1/dummy_key2/dummy_key3/```
This will also delete dummy_key1 and everything below.

FZ
