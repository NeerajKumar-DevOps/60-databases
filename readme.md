##  This module created MongoDB micro service in backend.
- Launch EC2 instance
- Configure using Ansible

##  AMI Creation
- Stop instance
- Create AMI → base image (`devops-practice`)

## Auto Scaling Setup
- Create Launch Template
- Create Target Group
- Create Auto Scaling Group (ASG)
- Attach ASG to Target Group

##  Scaling Policies
- Configure Auto Scaling policies

##  Listener Rules
- Add rules for routing traffic

##  Repeat for Other Databases
Same process applies for:
- MySQL
- Redis
- RabbitMQ