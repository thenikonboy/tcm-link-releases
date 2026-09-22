# TCM-Link Release & Distribution Channel 🚀

ศูนย์รวมไฟล์อัปเดตและตัวติดตั้งโปรแกรม **TCM-Link (Trang IMC TCM Fast-Track Referral System)** สำหรับโรงพยาบาลในเครือข่ายจังหวัดตรัง

---

### 📦 ไฟล์สำหรับดาวน์โหลดล่าสุด (Version 2.6.0)

| รายการ | รายละเอียด | ลิงก์ดาวน์โหลด |
| :--- | :--- | :--- |
| **TCM-Link Update v2.6.0 (Installer)** | ตัวติดตั้งอัปเดตแบบ One-Click สำหรับ Windows (ไม่ลบข้อมูลคนไข้เดิม) | [ดาวน์โหลด .exe](https://raw.githubusercontent.com/thenikonboy/tcm-link-releases/main/TCM-Link-Update-v2.6.0-Setup.exe) |
| **Update Payload (.zip)** | ไฟล์แพ็กเกจสำหรับระบบ In-App Auto Update | [ดาวน์โหลด .zip](https://raw.githubusercontent.com/thenikonboy/tcm-link-releases/main/update_payload.zip) |
| **Version Manifest (.json)** | ข้อมูลเมทาดาทาเวอร์ชันและ Changelog | [ดู version.json](https://raw.githubusercontent.com/thenikonboy/tcm-link-releases/main/version.json) |

---

### 💡 บันทึกการปรับปรุง (Changelog v2.6.0)
- **ระบบเข้าสู่ระบบด้วยอีเมลโรงพยาบาล (Hospital Staff Login):** พร้อมรหัส PIN ประจำเครื่อง ใช้งานพร้อมกันได้หลายจุดบริการ
- **อัปเกรด Google Apps Script Template v3.0 (Smart Upsert & Non-Destructive Merge):** แก้ไขปัญหาข้อมูลไม่ตรงกันระหว่างชั้นบน-ชั้นล่าง และเครือข่าย รพ. 4, 5, 6, 7 ซิงค์เคสหากันได้ 100%
- **เคลียร์ข้อมูลเคสทดสอบเดิมทั้งหมด:** ฐานข้อมูลสะอาดหมดจด พร้อมรับเคสคนไข้จริงของโรงพยาบาล
- **ตัวติดตั้งแบบ Clean Install:** ปิดโปรแกรมเดิมและเคลียร์ไฟล์เก่าให้อัตโนมัติก่อนติดตั้ง