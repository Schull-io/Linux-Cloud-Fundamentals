## Launch an Amazon linux instance using AWS CLI

Tasks:

Launch an instance with the following property 
1. instance OS   - Amzon linux
2. instance type - t2.micro
3. Region: Oregon
4. Network: Lab VPC, Public Subnet
5. Tag:  Key: Name     Value: ProdCafeServer
6. Security Group:  Create a  one named serverSG, with TCP port 22 and port 80 open to anywhere



Hint: Associate an elastic ip with this instance, you will need it in later lab.


Grading tip:  Screenshot major cli output and upload with your step by step answer (AWS describe command can help)


Guide:

https://docs.aws.amazon.com/cli/latest/userguide/cli-services-ec2-instances.html
