# เตรียมตัวก่อนเรียน
[กลับหน้าแรก](../README.md)

ทำให้เสร็จก่อนคืนที่ 1 — เวลาเตรียมเครื่องคือเวลาที่หายไปจาก Workshop

## Checklist
- [ ] มีคอมพิวเตอร์ อินเทอร์เน็ตที่เสถียร และใช้ Terminal เบื้องต้นได้
- [ ] เลือกเครื่องหลักสำหรับเรียน: macOS / Windows ผ่าน WSL2 / Linux
- [ ] ติดตั้ง VS Code และ Git
- [ ] ดาวน์โหลดและแตกไฟล์ repo นี้แล้ว (Code → Download ZIP) เปิดไฟล์ Markdown ได้
- [ ] ติดตั้ง Hermes ตามคู่มือทางการด้านล่าง
- [ ] มี Account หรือ API Key ของ Model Provider และตรวจงบใช้งานแล้ว
- [ ] ทดลองสนทนากับ Hermes ได้อย่างน้อย 2 รอบ
- [ ] ให้ Agent อ่านไฟล์ในโฟลเดอร์ได้จริง

## เส้นทางติดตั้ง
- macOS / Linux → [Quickstart ทางการ](https://hermes-agent.nousresearch.com/docs/getting-started/quickstart/)
- Windows → [Windows WSL2 Guide](https://hermes-agent.nousresearch.com/docs/user-guide/windows-wsl-quickstart)

## หลังติดตั้ง — ทดสอบสองนาที

```bash
mkdir -p my-work/day1-workshop
cd my-work/day1-workshop

hermes setup
hermes model
hermes
```

ในช่องสนทนาของ Hermes

```text
สร้างไฟล์ hello.md แล้วเขียนว่า "พร้อมเรียนแล้ว"
จากนั้นเปิดไฟล์นั้นอ่านกลับมาให้ผมดู และบอกด้วยว่าใช้เครื่องมืออะไร
```

**ผ่านเมื่อ** · มีไฟล์ `hello.md` อยู่จริงในโฟลเดอร์ (เปิดดูด้วยตาเอง) และ Agent บอกได้ว่าเรียกเครื่องมืออะไร
ถ้า tool อ่านเขียนไฟล์ยังไม่พร้อม ให้แก้ setup ก่อนเริ่ม Day 1

## หมายเหตุ
- การติดตั้งโปรแกรมกับค่าใช้ model เป็นคนละส่วน — ไม่ใช่ทุก provider ใช้งานฟรี
- VPS เป็นทางเลือกต่อยอด ไม่จำเป็นสำหรับ Workshop หลัก
- ไม่จำเป็นต้องเป็น Programmer ระดับ Advanced และไม่จำเป็นต้องเคยใช้ Hermes มาก่อน

ติดปัญหา → [Troubleshooting](../resources/troubleshooting.md) แล้วแจ้งในแชทห้อง
