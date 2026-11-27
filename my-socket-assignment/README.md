# รายงานแบบฝึกหัด Socket API & Docker (Assignment 1 & 2)

**ข้อมูลผู้จัดทำ**
* ชื่อ-นามสกุล: [นาย.ชัยนวัฒน์ สุขคง]
* รหัสนักศึกษา: [6714951003]
* กลุ่ม/เซคชัน: [1]

---

## 🛠️ แบบฝึกหัดที่ 1: ระบบ Chat ด้วย Docker (2 Clients & 1 Server)
<img width="958" height="341" alt="Screenshot 2026-11-27 135324" src="https://github.com/user-attachments/assets/a252395d-b5c7-4854-be93-96f5855d5ac1" />
<img width="952" height="515" alt="Screenshot 2026-11-27 140207" src="https://github.com/user-attachments/assets/5cff832e-13a2-48dc-8501-598fd8d937ee" />
<img width="958" height="512" alt="Screenshot 2026-11-27 140213" src="https://github.com/user-attachments/assets/817173a4-65e4-4ce6-b987-616a98bf01a5" />

### คำอธิบายการทำงาน
ระบบแชทนี้ประยุกต์ใช้ Socket API แบบ TCP ในการส่งข้อมูลระหว่าง Client 2 ตัว ผ่าน Server กลาง โดยรันอยู่ในรูปแบบของ Docker Multi-container และใช้ Docker Compose ในการจัดการ
<img width="956" height="659" alt="Screenshot 2026-11-27 140813" src="https://github.com/user-attachments/assets/d400a98b-b0d4-48b9-a5b2-72f3f975ad75" />
<img width="957" height="688" alt="Screenshot 2026-11-27 140910" src="https://github.com/user-attachments/assets/26b480bd-fa39-4ad2-94e8-11f0e00e134f" />

### ขั้นตอนการเริ่มทำงาน (How to run)
1. เปิด Terminal และเข้าไปที่โฟลเดอร์แบบฝึกหัดที่ 1:
   ```bash
   cd exercise-1
   แล้วก็ใส่โค้ดแต่ล่ะตัว chat-app/
├── client.py
├── server.py
├── Dockerfile.server
├── Dockerfile.client
└── docker-compose.yml
