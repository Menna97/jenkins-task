# jenkins-task
- Run infrastructure pipeline to provision aws resources using terraform from the following repo https://github.com/Menna97/terraform-infrastructure-aws.git
- Configure ec2 instance to serve as jenkins slave using ansible
- Run application pipeline to build docker image, push image to dockerhub, and deploy a containerized nodejs app on ec2 instance
- Expose application through internet facing load blanacer
## Testing application connectivity to RDS MySQL and ElastiCache Redis
![rds](https://user-images.githubusercontent.com/31425172/169700513-b58cd6b8-b7f8-4c1c-a5ad-21357b42dc46.png)
![redis](https://user-images.githubusercontent.com/31425172/169700519-4d0f13b4-5f7c-4dbe-8701-4f0566dfc59d.png)
