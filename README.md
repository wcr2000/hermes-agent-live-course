# 🤖 Hermes Agent Live Course
## มาสร้างพนักงาน AI กันเถอะ
**ผู้สอน: อ.วัชระ น้อยศรีพันธ์ (เฟิร์ส · AI พารวย)** · Live Online 5 คืน · คืนละ 2 ชั่วโมง · 20:00 – 22:00 น.

Repo นี้คือคู่มือภาคลงมือทำของหลักสูตร — เนื้อหาในนี้เรียงตาม **สไลด์ของแต่ละคืนแบบหน้าต่อหน้า**
สไลด์ใช้สำหรับเล่าและสาธิต ส่วน repo นี้เก็บ Prompt เต็ม ๆ ขั้นตอน และเกณฑ์ตรวจที่อ่านย้อนได้หลังคลาส

## ตารางเรียน

| คืน | วันที่ | บทเรียน | Session / Workshop | สิ่งที่ได้กลับบ้าน |
|---|---|---|---|---|
| 1 | 8 ก.ย. 2569 | [Hermes Fundamentals](day-01-fundamentals/README.md) | Session 1–2 · Workshop 1–2 | Hermes ที่ติดตั้งแล้ว + Personal AI Assistant |
| 2 | 10 ก.ย. 2569 | [Session & Memory](day-02-session-memory/README.md) | Session 3–4 · Workshop 3–4 | `MEMORY.md` ที่จำเราได้ข้าม Session |
| 3 | 14 ก.ย. 2569 | [Tools, Skills & MCP](day-03-tools-skills-mcp/README.md) | Session 5–6 · Workshop 5–6 + MCP | `report.md` จากงานจริง + `SKILL.md` ตัวแรก |
| 4 | 16 ก.ย. 2569 | [Agent Workflow & Multi-Agent](day-04-agent-workflow/README.md) | Session 7–8 · Workshop 7–8 | `workflow.md` + `team.md` |
| 5 | 18 ก.ย. 2569 | [Build Your AI Employee](day-05-ai-employee/README.md) | Master Workshop · Final Demo | `EMPLOYEE.md` + AI Employee ที่รันกับงานจริงได้ |

**[เตรียมเครื่องก่อนเรียน](00-precourse/README.md) · [Outline เต็ม](outlines/README.md) · [คำสั่งที่ใช้บ่อย](resources/commands.md) · [ติดปัญหา](resources/troubleshooting.md)**

## เส้นทางของหลักสูตร

```
Agent → Memory → Tools → Skills → MCP → Workflow → Sub-agents → Multi-Agent → AI Employee
```

แต่ละคืนต่อยอดจากคืนก่อนหน้าด้วย **โจทย์เดียวของตัวเอง** ไม่ใช่โจทย์แยกกันห้าข้อ
จบคืนที่ 5 สิ่งที่ประกอบไว้ทั้งหมดจะกลายเป็น AI Employee หนึ่งตัวที่เอาไปใช้กับงานจริงต่อได้ทันที

## วิธีใช้ repo นี้

1. เปิดโฟลเดอร์ของคืนนั้น แล้วอ่าน `README.md` ก่อนเริ่มคลาส (5 นาทีพอ)
2. ระหว่าง Workshop ให้เปิด `workshop.md` ไว้ข้าง ๆ — Prompt ทุกอันคัดลอกไปวางได้เลย
3. จบแต่ละช่วงให้ตรวจ `checkpoint.md` ก่อนไปต่อ
4. เก็บงานของตัวเองไว้ในโฟลเดอร์ `my-work/` ที่สร้างเอง (มีใน `.gitignore` แล้ว ไม่ถูกอัปขึ้น Git)
5. ไม่ต้องใช้ Git เป็นก็อ่านได้ — กด **Code → Download ZIP** แล้วแตกไฟล์ก็พอ

## โฟลเดอร์งานของแต่ละคืน

Workshop ทุกคืนให้ Agent ทำงานอยู่ในโฟลเดอร์เดียว เพื่อจำกัดขอบเขตความเสียหาย

```
my-work/
├── day1-workshop/      # Agent ตัวแรก + Personal Assistant
├── day2-workshop/      # MEMORY.md
├── day3-workshop/      # report.md + SKILL.md
├── day4-workshop/      # workflow.md + team.md
└── ai-employee/        # บ้านถาวรของ AI Employee (คืนที่ 5)
```

## เทมเพลตที่ใช้ระหว่างคลาส

| ไฟล์ | ใช้คืนไหน |
|---|---|
| [`templates/MEMORY.md`](templates/MEMORY.md) | คืนที่ 2 · Workshop 4 |
| [`templates/SKILL.md`](templates/SKILL.md) | คืนที่ 3 · Workshop 6 |
| [`templates/workflow.md`](templates/workflow.md) | คืนที่ 4 · Workshop 7 |
| [`templates/team.md`](templates/team.md) | คืนที่ 4 · Workshop 8 |
| [`templates/EMPLOYEE.md`](templates/EMPLOYEE.md) | คืนที่ 5 · Master Workshop |
| [`templates/employee-brief.md`](templates/employee-brief.md) | คืนที่ 5 · ใบสรุปงานสำหรับหัวหน้างาน |

## ยังไม่มีงานจริงมาลอง?

ใช้ชุดข้อมูลจำลองใน [`project/`](project/README.md) แทนได้ทุกคืน — เป็นธุรกิจคอร์สเรียนสมมติ
พร้อมข้อความลูกค้า Playbook และกรณีทดสอบ ใช้เกณฑ์ตรวจชุดเดียวกับงานจริง

## ความถูกต้องและเวอร์ชัน

Hermes Agent เป็น Open Source ที่พัฒนาต่อเนื่อง คำสั่งและ Configuration อาจเปลี่ยนตามเวอร์ชัน
ดูสถานะที่ทดสอบแล้วได้ที่ [บันทึกความพร้อม](resources/tested-environment.md) และตรวจกับ [เอกสารทางการ](resources/sources.md) ควบคู่เสมอ

[หน้าคอร์ส](https://hub.itgenius.co.th/live/hermes-agent-build-your-own-ai-employee) · [แหล่งอ้างอิง](resources/sources.md) · [แนวทางผู้สอน](instructor/README.md)
