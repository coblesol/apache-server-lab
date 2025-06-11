# 🛠 Apache Server Lab – Zach Coble

This lab demonstrates setting up a basic Apache2 web server using the Linux terminal on Ubuntu-based systems. The goal was to practice foundational system administration skills by installing, managing, and verifying a running HTTP service.

---

## ⚙️ Technologies Used

- Linux Mint (Ubuntu-based)
- Apache2 Web Server
- Command Line Tools (apt, systemctl, curl)

---

## 🧪 Commands Used to Set Up the Server

```bash
# Update packages
sudo apt update && sudo apt upgrade -y

# Install Apache
sudo apt install apache2 -y

# Enable and start Apache
sudo systemctl enable apache2
sudo systemctl start apache2

# Check Apache service status
clear && echo "✅ Zach's Apache Server is Running" && systemctl status apache2 | head -n 20
