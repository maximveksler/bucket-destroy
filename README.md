# bucket-destroy
Automatically exported from code.google.com/p/bucket-destroy

Multi threaded utility to delete non empty S3 bucket, supports deleting buckets that have versioning enabled.

Quick setup:

hg clone https://bucket-destroy.googlecode.com/hg/ bucket-destroy 
cd bucket-destroy
mvm install
Now run:

java -cp target/bucket-destroy-0.0.1-SNAPSHOT-jar-with-dependencies.jar \
-Daws.key=KEY -Daws.secret=SECRET BucketDestroy "bucketName"
