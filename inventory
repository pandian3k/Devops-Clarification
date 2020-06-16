Ansible Dynamic Inventory
Pre-requisites:
Ansible Server - Get Click here to install on RHEL 8 and click here to install on Amazon Linux
Setup
To get help on dynamic inventory please follow Ansible Official Document

Download ec2.py and ec2.ini files

Create IAM Programmatic access user with EC2 full access on AWS console

IAM --> users --> Add user

Export IAM user credentials on Ansible server.

export AWS_ACCESS_KEY_ID='1bc123'
export AWS_SECRET_ACCESS_KEY='abc123'
To export keys permanently make sure that you have installed pip and boto and add credentials ~/.boto file

add executing permissions to ec2.py script

chmod 755 ec2.py
test the script

./ec2.py --list
List out servers which are running on ap-south-1a AZ

ansible -i ec2.py  ap-south-1a --list-hosts
