1. Launch an EC2 instance on AWS.
2. Connect to it via SSH or EC2 Instance Connect.
3. Create a file named `index.html`.
4. Run:
   ```bash
   sudo yum update ae -y
   sudo yum install httpd -y
   sudo systemctl enable --now httpd
   sudo mv index.html /var/www/html
   sudo systemctl restart httpd
   ```

Then visit the public DNS in your browser:

[ec2-3-83-145-155.compute-1.amazonaws.com](http://ec2-3-25-176-210.ap-southeast-2.compute.amazonaws.com)
<img width="1857" height="962" alt="17846928532393935622602970493293" src="https://github.com/user-attachments/assets/aad2deff-9852-4773-be82-3c05af761c49" />
