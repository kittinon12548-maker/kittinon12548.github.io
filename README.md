# 💼 Developer Portfolio & Project Showcase

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=220&section=header&text=Kittinon%20Portfolio&fontSize=50&fontAlignY=38&desc=Full-Stack%20%7C%20AI%20%26%20IoT%20Solutions%20%7C%20Software%20Engineer&descAlignY=58&descAlign=50" alt="Header Banner" width="100%">
</p>

<p align="center">
  <a href="#-featured-projects"><img src="https://img.shields.io/badge/Featured-Projects-14b8a6?style=for-the-badge&logo=rocket" alt="Projects"></a>
  <a href="#-technical-skills"><img src="https://img.shields.io/badge/Tech-Stack-3b82f6?style=for-the-badge&logo=codeforces" alt="Tech Stack"></a>
  <a href="#-contact--links"><img src="https://img.shields.io/badge/Get%20in-Touch-6366f1?style=for-the-badge&logo=gmail" alt="Contact"></a>
</p>

---

## 👨‍💻 About Me (แนะนำตัว)
สวัสดีครับ! ยินดีต้อนรับสู่คลังรวบรวมผลงานและโปรเจกต์ของผม พื้นที่นี้สร้างขึ้นเพื่อจัดแสดงผลงานพัฒนาซอฟต์แวร์จริง ทั้งในด้าน **AI/Machine Learning, Backend Web Development, RESTful API Architecture, และ IoT Solutions** สำหรับใช้ประกอบการพิจารณาในเรซูเม (Resume / CV) และพอร์ตโฟลิโอครับ

* 🔭 กำลังมุ่งเน้นการพัฒนา: **AI Integration, B2B Cloud APIs, and Scalable Full-Stack Web Applications**
* 💡 ความสนใจ: **Pet-Tech, Computer Vision, High Performance Backend, Edge AI**
* ⚡ จุดเด่น: สามารถออกแบบระบบได้ตั้งแต่โมเดล AI, API Gateway, ฐานข้อมูล จนถึงหน้าบ้าน (End-to-End Development)

---

## 🌟 Featured Projects (โปรเจกต์ไฮไลท์)

| โปรเจกต์ | หมวดหมู่ | เทคโนโลยีหลัก | ลิงก์รายละเอียด |
| :--- | :--- | :--- | :---: |
| **🐱 PetGuard AI** | **AI / Pet-Tech / B2B API** | Python, PyTorch, YOLO, Laravel, Tailwind CSS | [👉 ดู Case Study](./projects/01-petguard-ai/) |
| **📊 การวิเคราะห์ความเหลื่อมล้ำของรายได้ (มศว)** | **Data Analytics / BI & EDA** | Python, Power BI, Pandas, Gini Index | [👉 ดู Case Study](./projects/02-dashboard-regional-income/) |
| **💡 Project 3 (Coming Soon)** | Mobile / Web App | (เตรียมเพิ่มผลงานถัดไป) | กำลังจัดทำ |

---

### 1. 🐱 [PetGuard AI — B2B AI Module for Smart Pet Care](./projects/01-petguard-ai/)
> **B2B AI Module สำหรับตรวจจับและวิเคราะห์ภาพถ่ายอุจจาระแมว เพื่อเฝ้าระวังสุขภาพในกระบะทรายแมวอัจฉริยะ (Smart Cat Litter Box)**

* **บทบาท:** Lead AI & Full-Stack System Architect
* **ความท้าทาย & วิธีแก้ปัญหา:**
  * แมวมักจะซ่อนอาการป่วย ทำให้เจ้าของสังเกตความผิดปกติได้ช้า
  * พัฒนาระบบ AI Computer Vision จำแนกภาพตามมาตรฐาน Feline Stool Scale (FSS) พร้อมตัดภาพพื้นหลังสิ่งรบกวน (ทรายแมว)
  * สร้าง API Gateway ด้วย Laravel รองรับการส่งภาพจากกล้อง IoT ประมวลผลและตอบกลับแบบ Real-time ด้วยเวลาเพียงระดับเสี้ยววินาที
* **Stack:** `Python`, `PyTorch`, `Laravel 11`, `PHP 8`, `Tailwind CSS`, `Docker`
* 📖 **อ่าน Case Study เต็มรูปแบบ:** [คลิกที่นี่เพื่อดูรายละเอียด](./projects/01-petguard-ai/)
* 🌐 **Landing Page & Testing Playground:** [เปิดไฟล์ HTML พรีวิว](./projects/01-petguard-ai/index.html)

---

### 2. 📊 [การวิเคราะห์ข้อมูลเชิงหลายมิติของรูปแบบและความเหลื่อมล้ำของรายได้ระดับภูมิภาคในประเทศไทย](./projects/02-dashboard-regional-income/)
> **การศึกษาความเหลื่อมล้ำทางรายได้ระดับภูมิภาค (พ.ศ. 2554–2566) ด้วยกระบวนการ EDA, การตรวจจับ Outlier, การคำนวณ Gini Index และพัฒนา Interactive Power BI Dashboard**

* **บทบาท:** Lead Data Researcher & Analytics Developer (ร่วมกับ อ.ดร.สุดา เธียรมนตรี)
* **ความท้าทาย & วิธีแก้ปัญหา:**
  * ปัญหาความเหลื่อมล้ำและการกระจุกตัวของรายได้ในเขตเมืองหลวงที่ยากต่อการเปรียบเทียบเชิงลึก
  * ทำ Data Preprocessing และ Outlier Detection (Z-score & IQR Rule) บนข้อมูลเปิดภาครัฐจาก data.go.th ย้อนหลัง 13 ปี
  * สกัดคุณลักษณะเชิงเวลา (Feature Engineering) คำนวณอัตราการเติบโต (Growth Rate) และดัชนีความเหลื่อมล้ำจีนี (Gini Index: 0.58–0.75)
  * ออกแบบ Interactive Dashboard บน Power BI รองรับการสืบค้นและเปรียบเทียบมิติเชิงพื้นที่เพื่อสนับสนุนการตัดสินใจเชิงนโยบาย
* **Stack:** `Python`, `Pandas`, `NumPy`, `Matplotlib`, `Microsoft Power BI`, `Jupyter Notebook`
* 📖 **อ่าน Case Study เต็มรูปแบบ:** [คลิกที่นี่เพื่อดูรายละเอียด](./projects/02-dashboard-regional-income/)
* 🌐 **Landing Page & Web Showcase:** [เปิดไฟล์ HTML พรีวิว](./projects/02-dashboard-regional-income/index.html)
* 📄 **เอกสารงานวิจัยฉบับเต็ม:** [ดาวน์โหลดบทความ PDF](./projects/02-dashboard-regional-income/033-บทความสมบูรณ์-Edited.pdf)

---

## 🛠️ Technical Skills (ทักษะทางเทคนิค)

### 💻 Languages & Frameworks
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
</p>

### 🗄️ Database & DevOps
<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
</p>

### 🧠 Core Competencies
* **AI & Computer Vision:** Model Inference, Image Segmentation, Dataset Preprocessing
* **API Development:** RESTful API Design, Microservices, API Documentation, Webhooks
* **Software Architecture:** MVC, Clean Code, Modular Design, Security Best Practices

---

## 📁 Repository Structure (โครงสร้างโฟลเดอร์)

```text
├── README.md                          # หน้าหลัก Portfolio สำหรับเรซูเม
└── projects/                          # รวมผลงานโปรเจกต์ทั้งหมด
    ├── 01-petguard-ai/                # โปรเจกต์ที่ 1: PetGuard AI
    │   ├── README.md                  # สรุปเชิงลึก (Case Study & Architecture)
    │   ├── index.html                 # หน้า Landing Page & Testing Demo
    │   └── assets/                    # โลโก้ และสคริปต์
    │
    └── 02-dashboard-regional-income/               # โปรเจกต์ที่ 2: งานวิจัยการวิเคราะห์รายได้ระดับภูมิภาค
        ├── README.md                  # สรุปงานวิจัยเชิงลึก (Case Study & Statistics)
        ├── index.html                 # หน้า Web Showcase สำหรับ GitHub Pages
        ├── 033-บทความสมบูรณ์-Edited.pdf # บทความวิจัยฉบับสมบูรณ์ (Final Paper)
        ├── รายได้ครัวเรือน_code.ipynb  # โค้ด Data Cleaning, EDA & Gini Calculation
        ├── รายได้ครัวเรือน.pbix       # ต้นฉบับ Power BI Dashboard
        ├── assets/                    # แผนภาพขั้นตอนและกราฟแสดงผล
        └── data/                      # ชุดข้อมูลที่ผ่านการประมวลผล (Cleaned Data)
```

---

## 📬 Contact & Links (ช่องทางติดต่อ)
* **GitHub:** [github.com/kittinon12548-maker](https://github.com/kittinon12548-maker)
* **Email:** (ใส่อีเมลสำหรับติดต่อที่นี่)
* **LinkedIn:** (ใส่ลิงก์ LinkedIn ที่นี่)
