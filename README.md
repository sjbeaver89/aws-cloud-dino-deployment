# 🦖 Samantha's Kangaroo Kourse: AWS Cloud Deployment

A hands-on cloud infrastructure project demonstrating the deployment of a customized web application on **Amazon Web Services (AWS)**.

## 🚀 Project Overview
This project involved provisioning a virtualized **Ubuntu 24.04** environment to host a globally accessible application. 

### Core Technologies Used:
* **Infrastructure:** AWS EC2 (t2.micro)
* **Web Server:** Nginx
* **OS:** Linux (Ubuntu)
* **Networking:** VPC, Security Groups (SSH/HTTP), and IPv4 Routing
* **DevOps:** Git, CLI-based configuration (Nano)

## 🛡️ Security Features
* **Restricted SSH Access:** Configured Security Groups to limit administrative access to a specific authorized IP.
* **Key Pair Authentication:** Utilized RSA encryption for secure server handshakes.
* **Least Privilege:** Public access limited strictly to Port 80 (HTTP).

## 🔗 Live Demo
> **Note:** This server is active during scheduled demonstration windows. 
> [Check it out here: http://18.119.206.40]

## 🛠️ Application Customization & Refactoring
While the base engine is inspired by the Chromium "Dino" runner, I performed significant code refactoring to transform the application into **Kangaroo Kourse**:

* **Asset Migration:** Replaced all original game sprites with custom Kangaroo assets (Run, Jump, and Duck states).
* **Physics Engine Overhaul:** Adjusted the JavaScript physics logic to accommodate larger sprite scaling. This involved recalculating `scaleRatio`, `GRAVITY`, and `JUMP_SPEED` to maintain a balanced gameplay feel with a "Mega-Roo" character model.
* **Collision Detection Tuning:** Calibrated hitbox parameters to ensure fair gameplay despite the increased sprite size.
* **Dynamic UI Updates:** Modified `index.html` and `index.js` for custom branding and theme-consistent "Game Over" messaging.

## 📈 Developmental Lessons
* **Browser Caching:** Managed challenges with persistent browser cache during live updates, utilizing "Hard Refreshes" to verify server-side code changes.
* **Infrastructure Consistency:** Identified the need for an **Elastic IP** to ensure permanent accessibility for the live demo.

## 📜 Credits & Attributions
* **Base Game Engine:** This project utilizes an open-source version of the classic 'Dino' runner.
* **Objective:** The game is used as a functional "vessel" to demonstrate expertise in **Cloud Infrastructure (IaaS)**, **Linux Administration**, and **Nginx Web Server** configuration.




https://github.com/user-attachments/assets/34924aea-13fc-46a8-8e10-d2af577b2beb




