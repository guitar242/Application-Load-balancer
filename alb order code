#!/bin/bash
yum install httpd -y
systemctl enable httpd
mkdir /var/www/html/orders/
echo "<h1>This is Orders App</h1>" > /var/www/html/orders/index.html
systemctl start httpd
