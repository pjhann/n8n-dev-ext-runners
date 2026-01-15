
# **N8N With External Runners**

This n8n setup includes an **external runner container** for executing Python inside the Code node.  
**Nginx Proxy Manager (NPM)** is used as a reverse proxy and for managing SSL certificates.

---

## **Installation**

### **1) Pull Nginx Proxy Manager**
Clone or download your `nginx-npm` repository.

---

### **2) Start Nginx Proxy Manager**
```bash
docker compose up -d
