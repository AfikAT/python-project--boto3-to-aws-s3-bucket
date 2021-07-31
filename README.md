# Python boto3 script for creating buckets on aws s3
## instructions - how to run this python script
1) First install boto3

```
pip install boto3
```
2) Create a new user on aws console <a href="https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users_create.html">Creating an IAM user in your aws account</a>

3) Make sure during the proccess of creating a new user, enable "programmatic access" and add the following permission "AmazonS3FullAccess"

4) Add the following permission "AmazonS3FullAccess"

5) After the creation of the user, you will need to configure his credentials locally as follow:
```
touch ~/.aws/credentials
```
6) open the file you created in the previous step and paste the following configuration, make sure to add your ACCESS_KEY_ID and SECRET_ACCESS_KEY of the user your created in step 2:
```
[default]
aws_access_key_id = YOUR_ACCESS_KEY_ID
aws_secret_access_key = YOUR_SECRET_ACCESS_KEY
```
