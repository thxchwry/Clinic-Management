# Clinic Management System (Java Swing + Text-Based Database) 🩺🏥

โปรเจกต์นี้เป็นระบบบริหารจัดการคลินิกขนาดเล็ก (Clinic Management) ที่พัฒนาด้วยภาษา **Java** และใช้ **Java Swing** สำหรับหน้าจอส่วนติดต่อผู้ใช้ (GUI) โดยเน้นการจัดเก็บข้อมูลผ่านไฟล์ข้อความ (File I/O) เพื่อความง่ายในการจัดการและประมวลผล

---

## 🔍 ภาพรวมของโปรเจกต์

ระบบถูกออกแบบมาเพื่อรองรับการทำงานของเจ้าหน้าที่และแพทย์ในคลินิก โดยมีฟังก์ชันตั้งแต่การเข้าสู่ระบบแยกประเภทผู้ใช้งาน (Doctor/Staff/Patient) การจัดการคิวผู้ป่วย การบันทึกประวัติการรักษา และการสืบค้นข้อมูลย้อนหลัง โดยระบบจะจัดเก็บข้อมูลทั้งหมดลงในไฟล์ `.txt` แทนการใช้ฐานข้อมูล SQL ขนาดใหญ่ ทำให้โปรเจกต์มีน้ำหนักเบาและง่ายต่อการเรียนรู้โครงสร้าง Data Persistence

โปรเจกต์นี้เหมาะสำหรับเป็นพื้นฐานในการศึกษาเรื่อง **Object-Oriented Programming (OOP)**, **GUI Design** และ **File Management** ในภาษา Java

---

## 🛠️ เทคโนโลยีที่ใช้

- **Language**: Java 8+
- **GUI Framework**: Java Swing / AWT
- **IDE**: NetBeans / Apache NetBeans
- **Data Storage**: Text Files (.txt) / CSV Simulation
- **Build Tool**: Ant / XML Configuration

---

## 📂 โครงสร้างโปรเจกต์โดยย่อ

```text
clinic-management/
├── src/myproject/
│   ├── MyProject.java       # จุดเริ่มต้นของโปรแกรม (Main Entry)
│   ├── Frame2.java - Frame9.java # หน้าจอ UI ส่วนต่างๆ (Login, Queue, History)
│   └── 5b3b10...jpg         # ไฟล์ทรัพยากรภาพประกอบ
├── Clinic/
│   ├── PersonalHistory/     # โฟลเดอร์เก็บประวัติผู้ป่วยรายบุคคล (.txt)
│   ├── LogInD.txt           # ข้อมูลการเข้าสู่ระบบสำหรับแพทย์
│   ├── LogInP.txt           # ข้อมูลการเข้าสู่ระบบสำหรับเจ้าหน้าที่/ผู้ป่วย
│   └── queue.txt            # ไฟล์จำลองคิวรอรับบริการ
├── build.xml                # ไฟล์สำหรับการ Build โปรเจกต์
└── README.md                # ไฟล์อธิบายโปรเจกต์
```
