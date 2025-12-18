# Mini Project 1 – Hosting a Static Website on AWS EC2

## Objective
Launch an AWS EC2 instance and host a custom static HTML webpage using Apache (httpd).

## Tools & Services Used
- AWS EC2
- Amazon Linux
- Apache (httpd)
- Linux CLI

## Steps Performed
1. Launched an EC2 instance using Amazon Linux.
2. Connected to the instance via SSH.
3. Installed Apache web server:
   ```bash
   sudo yum install httpd -y
   
## Started and enabled Apache:
sudo systemctl start httpd
sudo systemctl enable httpd

## Created a custom HTML file:
sudo vi /var/www/html/index.html

## Verified locally using:
curl http://localhost

## verified in browser:
http://public-ip
