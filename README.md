# AWS DevOps Engineer Internship Assignment

## Candidate Details

- Name: Nishka Patel
- Branch: BCA
- Email: nishkapatel2003@gmail.com

---

## Project Objective

Deploy a simple HTML website on an AWS EC2 Ubuntu instance using Nginx and maintain the project on GitHub.

---

# EC2 Setup Steps

1. Logged into AWS Console.
2. Launched an Ubuntu EC2 instance.
3. Created a Security Group.
4. Allowed inbound ports:
   - SSH (22)
   - HTTP (80)
5. Connected to the EC2 instance using SSH.

---

# Nginx Installation

Updated the package repository and installed Nginx.

Commands used:

```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl status nginx
sudo systemctl restart nginx
```

Verified that Nginx service was running successfully.

---

# Linux Commands Used

### Disk Usage

```bash
df -h
```

### Memory Usage

```bash
free -h
```

### Running Processes

```bash
ps aux
```

---

# Website Deployment

1. Created a custom `index.html` page.
2. Replaced the default Nginx page.
3. Restarted Nginx.
4. Verified the website using the EC2 Public IP.

---

# Project Files

- index.html
- README.md

---

# Git Commands Used

```bash
sudo git init
sudo git add .
sudo git commit -m "Initial commit"
sudo git branch -M main
sudo git remote add origin https://github.com/patelnishka/nishka-aws-devops-intern-assignment.git
sudo git push -u origin main
```

---

# Outcome

Successfully deployed a static website on AWS EC2 using Nginx and uploaded the project to GitHub.
