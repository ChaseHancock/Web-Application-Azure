# 🌐 Azure Web Application Deployment – Project 1 Technical Brief

> A hands-on cybersecurity project focused on securely deploying a PHP-based web application on Microsoft Azure and configuring secure access using cloud security best practices.

## 👨‍💻 Author
**Chase Hancock**  
Cybersecurity Student | Cloud Security Enthusiast  

---

## 🧭 Project Summary

This project demonstrates how to:
- Deploy a web application on **Microsoft Azure**
- Configure SSL/TLS security and bind certificates
- Implement **Azure Front Door** and **Web Application Firewall (WAF)**
- Analyze web application DNS/networking configurations
- Understand and mitigate common web threats (e.g., directory traversal)

🧠 **Stack:** Azure | PHP | TLS | DNS | WAF | SSL

---

## 🚀 Project Phases

### ✅ Day 1 – Setup & Networking

- Domain: Azure-provided domain
- Runtime stack: PHP (Back-end)
- Website components:
  - `/assets`: CSS styles, images
  - Front-end rendering handled via HTML/CSS
- IP: `20.211.64.15` (Sydney, AU)
- DNS Records: Reviewed NS (Name Server) configurations

### 🔐 Day 2 – SSL & Cryptography

- Key Vault configured with:
  - **Keys**: Encryption & signing
  - **Secrets**: API keys, credentials
  - **Certificates**: SSL/TLS
- SSL Certificate:
  - Valid: `Oct 31, 2023 – Jun 27, 2024`
  - Root CA: DigiCert Global Root G2
- Wildcard, self-signed certs explained
- Verified secure HTTPS connection

### 🛡️ Day 3 – WAF, Front Door & Cloud Security

- Enabled **Azure Front Door**: global entry point, SSL offloading
- Deployed **WAF** (Web Application Firewall)
  - Custom rule: Block traffic from Canada
  - Managed rule: Prevent **Directory Traversal** attacks
- Simulated VPN bypass scenarios for geoblocking

---

## 🧪 Key Concepts Learned

| Concept | Description |
|--------|-------------|
| Azure Front Door | Global load balancer for app acceleration and security |
| SSL Offloading | Offloads encryption tasks from web servers for performance |
| WAF | Protects against Layer 7 (application-level) attacks |
| Directory Traversal | Exploit to access files outside web root directory |
| Wildcard Certificates | Secures a domain and its subdomains with one certificate |

---

- Deployed Azure Web App with custom blog
- SSL certificate details in browser
- Azure Key Vault with secrets and certificates
- Azure Front Door settings
- WAF custom and managed rules in action

---

*Discaimer*
The site created is no longer active.
