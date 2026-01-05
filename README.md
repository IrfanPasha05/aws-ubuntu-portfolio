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

