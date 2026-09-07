# เตรียมตัวก่อนเรียน
[กลับหน้าแรก](../README.md)

## Checklist
- [ ] มีคอมพิวเตอร์ อินเทอร์เน็ต และ Terminal
- [ ] ดาวน์โหลดและแตกไฟล์ repo แล้ว เปิดไฟล์ Markdown ได้
- [ ] เลือกเครื่องหลักสำหรับเรียน: macOS / Windows ผ่าน WSL2 / Linux
- [ ] ติดตั้ง Hermes ตามคู่มือทางการที่เชื่อมไว้ด้านล่าง
- [ ] ตั้งค่า provider/model ของตนและตรวจงบใช้งานกับผู้ให้บริการ
- [ ] ทดลองสนทนาได้อย่างน้อย 2 รอบ
- [ ] ให้ผู้ช่วยอ่านไฟล์ข้อมูลจำลองได้จริง

## เส้นทางติดตั้ง
ใช้ [Quickstart ทางการ](https://hermes-agent.nousresearch.com/docs/getting-started/quickstart/) สำหรับ macOS/Linux และ [Windows WSL2 Guide](https://hermes-agent.nousresearch.com/docs/user-guide/windows-wsl-quickstart) สำหรับเส้นทาง Windows ที่เสนอให้ใช้ในคลาส
ผู้สอนต้องซ้อมและตรึงเวอร์ชันก่อนแจกคำสั่งติดตั้งจริงสำหรับรุ่นเรียน ดู [สถานะ](../resources/tested-environment.md)

## หลังติดตั้ง
เปิด Terminal ที่โฟลเดอร์ repo แล้วรันทีละคำสั่ง:
```bash
hermes setup
hermes
```
ในช่องสนทนาของ Hermes:
```text
อ่าน project/data/business.md แล้วสรุปชื่อธุรกิจ สินค้าที่ขาย และข้อมูลที่ยังไม่มี ห้ามเดาราคา
```
ผ่านเมื่อคำตอบระบุ Learning Studio Demo และราคา 990 บาท พร้อมบอกว่าไม่มีนโยบายคืนเงิน หาก tool อ่านไฟล์ไม่พร้อม ให้แก้ setup ก่อนเริ่ม Day 1

การติดตั้งโปรแกรมกับค่าใช้ model เป็นคนละส่วน ไม่ถือว่าทุก provider ใช้งานฟรี
VPS เป็นทางเลือกต่อยอด ไม่จำเป็นสำหรับ Workshop หลัก
