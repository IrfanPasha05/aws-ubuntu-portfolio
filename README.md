# 🌈 AWS Ubuntu Portfolio Website

A colorful and animated personal portfolio website hosted on an Ubuntu EC2 instance in AWS.  
The project includes animated UI sections, project cards, icons, and a hosted profile portfolio.

---

## 👤 Portfolio Owner

**Name:** Irfan Pasha  
**Email:** ip.irfanpasha05@gmail.com  
**Phone:** (Add your number here)

---

## 🎨 Features

- 🖥️ Fully hosted on **AWS EC2 (Ubuntu Linux)**
- 🎯 Responsive & colorful UI
- ⚡ Smooth animations and transitions
- 🧩 Animated project cards with icons
- 🖼️ Profile photo section
- 📧 Contact details displayed on the page
- 🌍 Publicly accessible portfolio site
- 💾 Version controlled with **Git & GitHub**

---

## 🏗️ Tech Stack

- **HTML / CSS / JavaScript**
- **Ubuntu Linux**
- **NGINX / Apache (Web Server)**
- **AWS EC2**
- **Git & GitHub**

---

## 🚀 Deployment Architecture

1. Create an **Ubuntu EC2 instance**  
2. Install **NGINX / Apache** web server  
3. Upload portfolio files to `/var/www/html` or `/var/www/portfolio`  
4. Start and enable web service  
5. Push project to **GitHub Repository**

---


---

## 🔧 Hosting Commands (Ubuntu Server)

```bash
sudo apt update
sudo apt install nginx -y
sudo cp -r * /var/www/html/
sudo systemctl restart nginx

git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/IrfanPasha05/aws-ubuntu-portfolio.git
git push -u origin main


## 📂 Project Structure

Author

Developed by Irfan Pasha
If you like this project, ⭐ star the repo!

Project Summary (Interview-Ready Answer)
I built a colorful personal portfolio website hosted on an AWS EC2 Ubuntu server.
I configured the Linux environment, installed a web server, and deployed the application using Git and GitHub for version control.
The site includes animated UI components, project cards, icons, and contact details

Key Responsibilities You Can Mention

Provisioned AWS EC2 Ubuntu instance
Configured Linux environment & directory structure
Installed and configured NGINX/Apache
Deployed website files to /var/www/
Managed source code using Git & GitHub
Added animations, profile section, and project cards
Ensured the site is publicly accessible
Followed deployment best practices

Strong Talking Points for HR / Technical Round

“This project demonstrates my hands-on skills in AWS, Linux, Web Hosting, and Git.”
“I worked with EC2, Ubuntu, NGINX, and deployment pipelines.”
“I used Git and GitHub for version control and project tracking.”
“This helped me understand web server configuration and hosting real-world applications.”
Resume Project Description (Copy-Paste)

Built and deployed a colorful personal portfolio website on AWS EC2 Ubuntu. 
Configured Linux server, installed NGINX, and deployed static web content using Git & GitHub.
Developed animated UI with project cards, icons, and contact details. 
Implemented version control and followed deployment best practices.
Tech Stack: AWS EC2, Ubuntu, Linux, NGINX, HTML, CSS, JavaScript, Git, GitHub.

