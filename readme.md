Adding creator username to EC2 instance tag automatically via lambda function 

![ec2_tag_by_lambda](https://user-images.githubusercontent.com/56221231/216386980-0f1d9388-b43a-4938-8981-9b6e22695bd7.png)

1 - Creat Lambda Function \
2 - Create Cloud Trail for logging purposes \
3 - Create EventBridge for filtering EC2 instance creation \
4 - Edit lambda function with Boto3 and give EC2 tag create permission
