# Local Business CRM, Tickets & Cash Register

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Interactive-brightgreen?style=for-the-badge&logo=googlechrome&logoColor=white)](https://djidelabdelali.github.io/smart-crm-pos-system/)
[![Portfolio](https://img.shields.io/badge/Portfolio-DJIDEL%20Abdelali%20Rayan-blue?style=for-the-badge&logo=react&logoColor=white)](https://djidelabdelali.github.io/portfolio/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DjidelAbdelali/smart-crm-pos-system)

</div>

---

## 📌 Project Overview

Full-stack offline-first web POS and CRM system designed for commercial businesses (ticketing, cash register, payroll, debt management). Built with 100% browser storage (IndexedDB), Excel export, and deployed in production with a self-resilient Windows NSSM service.

This project is an engineering module built by **DJIDEL Abdelali Rayan** (Systems & Automation Engineer, USTHB).

---

## 🏗️ System Architecture & Data Flow

```mermaid
graph TD
    UI[Web POS & Tickets Interface] --> State[Local State Manager]
    State --> Database[(Browser IndexedDB Storage)]
    State --> Excel[Excel & PDF Invoice Generator]
    State --> Service[NSSM Windows Resilient Service Auto-Restart]
```

---

## 🛠️ Key Technologies & Frameworks

- **JavaScript**
- **IndexedDB**
- **NSSM Windows Service**
- **Excel Export**
- **POS System**

---

## 🚀 Live Interactive Web Demo

No installation required! Test and interact with the full web simulation live in your browser:
🔗 **[Launch Interactive Web Demo](https://djidelabdelali.github.io/smart-crm-pos-system/)**

---

## 🔗 Connected Portfolio Ecosystem

- 🌐 **Main Portfolio**: [djidelabdelali.github.io/portfolio](https://djidelabdelali.github.io/portfolio/)
- 💻 **GitHub Profile**: [github.com/DjidelAbdelali](https://github.com/DjidelAbdelali)
- 💼 **LinkedIn Profile**: [DJIDEL Abdelali Rayan](https://linkedin.com/in/djidel-abdelali-rayan-814b25207)

---

<div align="center">
  <sub>Developed by DJIDEL Abdelali Rayan — Systems & Automation Engineering</sub>
</div>
