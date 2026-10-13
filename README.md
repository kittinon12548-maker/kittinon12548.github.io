# 💼 Developer Portfolio & Project Showcase

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=220&section=header&text=Kittinon%20Portfolio&fontSize=50&fontAlignY=38&desc=Data%20Analytics%20%7C%20AI%20%26%20Computer%20Vision%20%7C%20Power%20BI&descAlignY=58&descAlign=50" alt="Header Banner" width="100%">
</p>

<p align="center">
  <a href="#-featured-projects"><img src="https://img.shields.io/badge/Featured-Projects-14b8a6?style=for-the-badge&logo=rocket" alt="Projects"></a>
  <a href="#-technical-skills"><img src="https://img.shields.io/badge/Tech-Stack-3b82f6?style=for-the-badge&logo=codeforces" alt="Tech Stack"></a>
  <a href="#-contact--links"><img src="https://img.shields.io/badge/Get%20in-Touch-6366f1?style=for-the-badge&logo=gmail" alt="Contact"></a>
</p>

---

## 👨‍💻 About Me (แนะนำตัว)
สวัสดีครับ! ยินดีต้อนรับสู่คลังรวบรวมผลงานและโปรเจกต์ของผม พื้นที่นี้จัดทำขึ้นเพื่อนำเสนอผลงานจริงด้าน **Data Analytics, Data & AI (Machine Learning / Computer Vision)** และการพัฒนาแดชบอร์ดสรุปข้อมูลเชิงลึก (Business Intelligence) ควบคู่กับทักษะเสริมด้าน Web Development & API สำหรับประกอบการพิจารณาสมัครฝึกงานตำแหน่ง **Data Analyst** และ **Data & AI** ครับ

* 🔭 กำลังมุ่งเน้น: **Exploratory Data Analysis (EDA), Business Intelligence (Power BI), และ Image Classification Prototype (Computer Vision)**
* 💡 ความสนใจ: **Data Analytics, Machine Learning, Computer Vision, และ Data Visualization** (มี Web/API เป็นทักษะเสริมสำหรับต่อยอดระบบ)
* ⚡ จุดเด่น: ผสานการสกัดและวิเคราะห์ข้อมูลจริง (Data Cleaning, Outlier Detection, Gini Index) เข้ากับความเข้าใจด้านการสร้างต้นแบบ AI Image Classification และการต่อยอดสู่แอปพลิเคชัน

---

## 🌟 Featured Projects (โปรเจกต์ไฮไลท์)

| โปรเจกต์ | หมวดหมู่ | เทคโนโลยีหลัก | ลิงก์รายละเอียด |
| :--- | :--- | :--- | :---: |
| **📊 การวิเคราะห์ความเหลื่อมล้ำของรายได้ระดับภูมิภาคในประเทศไทย (มศว)** | **Data Analytics / BI & EDA** | Python, Pandas, Power BI, Gini Index, EDA | [👉 ดู Case Study](./projects/02-dashboard-regional-income/) |
| **🐱 PetGuard AI — Image Classification Prototype** | **Data & AI / Computer Vision (B2B Concept)** | Python, Image Classification, Roboflow | [👉 ดู Case Study](./projects/01-petguard-ai/) |

---

### 1. 📊 [การวิเคราะห์ข้อมูลเชิงหลายมิติของรูปแบบและความเหลื่อมล้ำของรายได้ระดับภูมิภาคในประเทศไทย](./projects/02-dashboard-regional-income/)
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

### 2. 🐱 [PetGuard AI — ต้นแบบระบบ AI จำแนกภาพอุจจาระแมวเพื่อการเฝ้าระวังสุขภาพ (B2B Concept)](./projects/01-petguard-ai/)
> **ต้นแบบระบบจำแนกภาพ AI (Image Classification Prototype) สำหรับคัดกรองลักษณะอุจจาระแมวเบื้องต้น ออกแบบแนวคิดเพื่อให้บริการในรูปแบบ B2B AI / API แก่ผู้ผลิตอุปกรณ์สัตว์เลี้ยง (ไม่ใช่ผู้ผลิตหรือจำหน่ายกระบะทรายโดยตรง)**

* **บทบาท:** ผู้พัฒนาต้นแบบระบบจำแนกภาพ AI (AI Prototype Developer)
* **สถานะปัจจุบันของ Prototype:**
  * **ประเภทโมเดล:** Image Classification สำหรับจำแนกภาพอุจจาระแมว
  * **ชุดข้อมูล (Dataset):** พัฒนาบนชุดข้อมูลรวม 9,664 ภาพ ผ่านกระบวนการ Preprocessing ปรับขนาดภาพ (Resize แบบ Stretch) เป็น 224×224 พิกเซล
  * **ผลการทดสอบบน Test Set:** ทำนายถูกต้อง 283 จาก 307 ภาพ คิดเป็นความแม่นยำ (Accuracy) **92.2% บน Test set** (ประเมินจาก Confusion Matrix)
  * **คลาสที่จำแนก (4 Classes):** `soft-poop`, `normal`, `diarrhea`, `lack-of-water`  
    *(หมายเหตุ: เป็นชื่อ Label ของชุดข้อมูลเท่านั้น ไม่ใช่การยืนยันภาวะสุขภาพ เช่น `lack-of-water` เป็นเพียงชื่อคลาสในชุดข้อมูล ไม่ได้แปลว่าตรวจพบภาวะขาดน้ำ)*
  * ⚠️ **ข้อจำกัดและคำเตือน:** ระบบนี้เป็นการตรวจคัดกรองลักษณะจากภาพถ่ายเบื้องต้นเท่านั้น ไม่สามารถใช้แทนการวินิจฉัยโรคโดยสัตวแพทย์
* **แผนพัฒนาต่อ (Future Roadmap):**
  * พัฒนา RESTful API Gateway ด้วย Laravel เพื่อรองรับการเชื่อมต่อและส่งภาพจากอุปกรณ์ IoT/กล้องภายนอก
  * ทดสอบและเปรียบเทียบสถาปัตยกรรมโมเดลเชิงลึกเพิ่มเติม เพื่อเพิ่มขีดความสามารถในการแยกแยะสิ่งรบกวน (เช่น ทรายแมว)
* **Stack ปัจจุบัน:** `Python`, `Image Classification`, `Roboflow`, `HTML/Tailwind CSS (UI Showcase)`  
  *(วางแผนเชื่อมต่อกับ `Laravel` ในอนาคต)*
* 📖 **อ่าน Case Study เต็มรูปแบบ:** [คลิกที่นี่เพื่อดูรายละเอียด](./projects/01-petguard-ai/)
* 🌐 **Landing Page & UI Showcase พรีวิว:** [เปิดไฟล์ HTML พรีวิว](./projects/01-petguard-ai/index.html)

---

## 🛠️ Technical Skills (ทักษะทางเทคนิค)

### 💻 Languages & Frameworks
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
</p>

### 🗄️ Database & Tools
<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
</p>

### 🧠 Core Competencies
* **Data Analytics & BI:** Exploratory Data Analysis (EDA), Data Preprocessing, Outlier Detection (Z-score & IQR Rule), Feature Engineering, Gini Index Calculation, Interactive Dashboard Design (Power BI)
* **AI & Machine Learning:** Image Classification Prototype, Dataset Preprocessing & Resizing, Model Evaluation (Confusion Matrix & Test Set Accuracy)
* **Supporting Web & Integration:** RESTful API Design Concepts, Basic Backend Integration (PHP/Laravel), Responsive UI Development

---

## 📁 Repository Structure (โครงสร้างโฟลเดอร์)

```text
├── README.md                                  # หน้าหลัก Portfolio สำหรับการสมัครงาน/ฝึกงาน
└── projects/                                  # รวมผลงานโปรเจกต์
    ├── 02-dashboard-regional-income/          # โปรเจกต์ที่ 1: การวิเคราะห์ความเหลื่อมล้ำของรายได้ (มศว)
    │   ├── README.md                          # สรุปงานวิจัยเชิงลึก (Case Study & Statistics)
    │   ├── index.html                         # หน้า Web Showcase สำหรับ GitHub Pages
    │   ├── 033-บทความสมบูรณ์-Edited.pdf         # บทความวิจัยฉบับสมบูรณ์ (Final Paper)
    │   ├── รายได้ครัวเรือน_code.ipynb          # โค้ด Data Cleaning, EDA & Gini Calculation
    │   ├── รายได้ครัวเรือน.pbix               # ต้นฉบับ Power BI Dashboard
    │   ├── assets/                            # แผนภาพขั้นตอนและกราฟแสดงผล
    │   └── data/                              # ชุดข้อมูลที่ผ่านการประมวลผล (Cleaned Data)
    │
    └── 01-petguard-ai/                        # โปรเจกต์ที่ 2: ต้นแบบระบบ AI จำแนกภาพอุจจาระแมว
        ├── README.md                          # สรุปเชิงลึก (Case Study & Architecture Concept)
        ├── index.html                         # หน้า Landing Page & UI Demo พรีวิว
        └── assets/                            # โลโก้ และสคริปต์
```

---

## 📬 Contact & Links (ช่องทางติดต่อ)
* **GitHub:** [github.com/kittinon12548-maker](https://github.com/kittinon12548-maker)
* **Email:** [Kittinon12548@gmail.com](mailto:Kittinon12548@gmail.com)
* **LinkedIn:** [linkedin.com/in/kittinon-chumboon-73250b369](https://www.linkedin.com/in/kittinon-chumboon-73250b369)