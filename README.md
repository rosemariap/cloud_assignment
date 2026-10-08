# AWS EC2 Apache Web Hosting Assignment

## Overview
This project demonstrates how to host a static HTML webpage on an Amazon EC2 instance using the Apache HTTP Server.

## Technologies Used
- Amazon EC2 (Amazon Linux 2023)
- Apache HTTP Server (httpd)
- HTML5
- Git
- GitHub

## Steps Performed
1. Launched an Amazon EC2 instance.
2. Connected to the instance using SSH.
3. Installed Apache HTTP Server.
4. Started and enabled the Apache service.
5. Created a static webpage (`home.html`).
6. Copied the webpage to Apache's web root.
7. Accessed the webpage through the EC2 Public IP.
8. Uploaded the project to GitHub using Git.

## Project Structure

```
aws_assignment/
├── home.html
└── README.md
```

## Commands Used

### Install Apache
```bash
sudo yum install -y httpd
```

### Start Apache
```bash
sudo systemctl start httpd
sudo systemctl enable httpd
```

### Copy Webpage
```bash
sudo cp home.html /var/www/html/
```

### Check Public IP
```bash
curl ifconfig.me
```

## Output

The webpage is successfully hosted on the EC2 instance using Apache and is accessible through the instance's public IP address.

## Author

**Sai Shabari**
