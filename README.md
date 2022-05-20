# jenkins-task
- Run infrastructure pipeline to provision aws resources using terraform from the following repo https://github.com/Menna97/terraform-infrastructure-aws.git
- Configure ec2 instance to serve as jenkins slave using ansible
- Run application pipeline to build docker image, push image to dockerhub, and run a containerized nodejs app on ec2 instance
