Create a Web Server on EC2
Launch an EC2 instance on AWS.
Connect to it via SSH or EC2 Instance Connect.
Create a file named index.html.
Run:
sudo yum update ae -y
sudo yum install httpd -y
sudo systemctl enable --now httpd
sudo mv index.html /var/www/html
sudo systemctl restart httpd
Then visit the public DNS in your browser:ec2-3-25-176-210.ap-southeast-2.compute.amazonaws.com
