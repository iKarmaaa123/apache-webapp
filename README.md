# Terraform-Web-Server-Project

When I created a web server using Terraform, I had to go through several steps. First, I created a Virtual Private Cloud (VPC) by defining the VPC resource with specific attributes like the CIDR block and tenancy.

Next, I created an internet gateway by defining the internet gateway resource and attaching it to my VPC. Then, I created a subnet by defining the subnet resource with attributes like the CIDR block, availability zone, and VPC ID.

After that, I associated the subnet to a route table by defining the route table resource and specifying the subnet ID. I also created security groups by defining the security group resource and specifying the inbound and outbound rules.

Then, I created a network interface by defining the network interface resource and specifying the subnet ID and security group ID. I assigned an elastic IP to the network interface by defining the elastic IP resource and associating it with the network interface.

Finally, I created the Ubuntu server and installed/enabled Apache 2 by defining an EC2 instance resource with attributes like the AMI, instance type, and user data script.

Overall, using Terraform to create a web server provided me with a scalable and repeatable way to provision infrastructure as code, making it easier for me to manage and maintain over time.
