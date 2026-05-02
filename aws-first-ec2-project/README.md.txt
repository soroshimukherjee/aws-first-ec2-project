# My First AWS EC2 Project

## What I did
I launched an AWS EC2 Ubuntu server, connected to it, installed NGINX, and hosted a simple webpage.

## Services used
- AWS EC2
- Ubuntu
- NGINX

## Steps followed
1. Created an EC2 instance
2. Allowed SSH and HTTP
3. Connected to the server
4. Installed NGINX
5. Hosted a webpage

## Commands used

```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx
cd /var/www/html
echo "<h1>Hello from my first cloud server</h1>" | sudo tee index.html
```

## Screenshot

![Project Output](output.png)
