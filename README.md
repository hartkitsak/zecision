# ⚡ zecision — ที่ปรึกษาการตัดสินใจเด็ดขาด

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-2.0.0-green)]()
[![Category](https://img.shields.io/badge/category-decision--making-orange)]()
[![Language](https://img.shields.io/badge/language-Thai-brightgreen)]()
[![Files](https://img.shields.io/badge/files-17-orange)]()
[![Compatibility](https://img.shields.io/badge/compatibility-opencode|claude--code|cursor|copilot-lightgrey)]()

> **Realist & Progressive Decision Advisor**  
> พาคนออกจากกับดักความคิดหมุนวน สู่การลงมือทำจริงภายใน 24-48 ชั่วโมง

Skill นี้ใช้กับ [opencode](https://opencode.ai), Claude Code, Cursor, Copilot หรือ AI agent ที่รองรับ custom skills เหมาะสำหรับสถานการณ์ที่ติด Analysis Paralysis — รู้ว่าต้องเลือกแต่เลือกไม่ได้สักที

---

## 📖 สารบัญ

- [🧠 เกี่ยวกับ zecision](#-เกี่ยวกับ-zecision)
- [⚡ หลักการทำงาน 6 ประการ](#-หลักการทำงาน-6-ประการ)
- [🚀 วิธีใช้ — ตัวอย่าง Prompt จริง](#-วิธีใช้--ตัวอย่าง-prompt-จริง)
- [📋 โครงสร้างการตอบ (Output Format)](#-โครงสร้างการตอบ-output-format)
- [📂 โครงสร้างโฟลเดอร์](#-โครงสร้างโฟลเดอร์)
- [🎯 ตัวอย่างสถานการณ์](#-ตัวอย่างสถานการณ์)
- [🔗 ระบบที่เกี่ยวข้อง](#-ระบบที่เกี่ยวข้อง)
- [📥 ติดตั้ง](#-ติดตั้ง)
- [📄 License](#-license)

---

## 🧠 เกี่ยวกับ zecision

zecision คือ **ที่ปรึกษาทางการตัดสินใจที่มองโลกตามความเป็นจริง (Realist)** และ **มีหัวก้าวหน้า (Progressive)** สำหรับการตัดสินใจที่ยาก ซ้ำซ้อน หรือติดอัมพาต

### ปัญหาที่ zecision แก้

| ปัญหา | อาการ | สิ่งที่ zecision ทำ |
|-------|-------|-------------------|
| 🌀 **Analysis Paralysis** | ลังเลระหว่าง 2 ทางเลือกมานานเป็นเดือน | ตัดวงจรด้วย decision framework + deadline |
| 😰 **กลัวตัดสินใจพลาด** | มีข้อมูลครบแต่ไม่กล้าเลือก | แยก Type 1 vs Type 2 + Pre-mortem |
| ⚖️ **Conflict of Values** | สองสิ่งที่ให้คุณค่าแตกต่างกัน | วิเคราะห์ 5 มิติ + Extreme perspectives |
| 🏔️ **High-Stakes** | ตัดสินใจที่มีผลกระทบสูง | Risk & Strategy + Soft landing |
| 🔀 **Life Crossroads** | จุดเปลี่ยนสำคัญของชีวิต | Cost of Inaction + The Next Step |

---

## ⚡ หลักการทำงาน 6 ประการ

| # | หลักการ | คำอธิบาย | ทำไมสำคัญ |
|---|---------|----------|----------|
| 1 | 🗣️ **พูดความจริง ไม่ต้องเกรงใจ** | ใช้ข้อมูลจริง ไม่ใช่ปลอบใจ ให้ feedback ตรงไปตรงมา | การปลอบใจทำให้ตัดสินใจช้าลง — ความจริงแม้เจ็บปวด แต่พาไปข้างหน้าได้ |
| 2 | ⚡ **ตัดสินใจอย่างเฉียบขาด** | แยก **Type 1** (แก้ไขไม่ได้ — คิดหนัก) vs **Type 2** (แก้ไขได้ — ลงมือทันที) | คนส่วนมากคิดหนักกับ Type 2 ทั้งที่ควรแค่ลงมือทำ |
| 3 | 🎯 **มุ่งเน้นการปฏิบัติ** | ทุกขั้นตอนต้องทำได้จริงภายใน 24-48 ชม. **ห้ามเป็นกิจกรรมเตรียมตัว** | "หาข้อมูลเพิ่ม" ไม่ใช่ action step — มันคือการ procrastinate |
| 4 | 🔍 **วิเคราะห์ผ่าน 5 มิติ** | จิตวิทยา · ตรรกะ · ธุรกิจและชีวิต · ปรัชญา · อารมณ์ | มิติเดียวไม่พอ — ต้องมองให้รอบเพื่อไม่ให้เกิด blind spot |
| 5 | 💸 **การไม่ตัดสินใจมีต้นทุนเสมอ** | ชี้ให้เห็นว่าถ้าปล่อยไว้ไม่เลือกอะไรเลย ชีวิตจะแย่ลงอย่างไร | Cost of inaction มักสูงกว่าความเสี่ยงของการเลือกผิด |
| 6 | 🔋 **Energy Budget** | ถ้าเรื่องไม่สำคัญมาก — แนะนำให้ตัดสินใจเร็ว (สุ่มได้) | สมองมีพลังงานจำกัด อย่าเสียไปกับ decision ระดับต่ำ |

---

## 🚀 วิธีใช้ — ตัวอย่าง Prompt จริง

พิมพ์ `/zecision` ตามด้วยปัญหาที่ลังเลใน Claude Code:

### ลังเลเรื่องอาชีพ

```
/zecision ผมกำลังลังเลระหว่างลาออกกับอยู่ต่อ ที่เดิม toxic แต่เงินดี
ควรตัดสินใจยังไง?
```

### ลังเลเรื่องเรียน vs ทำธุรกิจ

```
/zecision จะเลือกเรียนต่อ ป.โท หรือ เริ่มธุรกิจของตัวเองดี
ผมอายุ 24 มีเงินเก็บ 5 แสน
```

### ลังเลเรื่องความสัมพันธ์

```
/zecision แฟนอยากย้ายไปอยู่ด้วยกัน แต่ผมเพิ่งเริ่มงานใหม่
กลัวเสียสมดุลชีวิต ควรทำยังไง?
```

### ลังเลเรื่องการเงิน

```
/zecision มีเงินก้อน 1 ล้าน ควรดาวน์คอนโด หรือลงทุนกองทุนรวมดี
อายุ 30 รายได้ 50K/เดือน
```

---

## 📋 โครงสร้างการตอบ (Output Format)

เมื่อ user ส่งสถานการณ์ + (ช่วยคิด) zecision จะตอบตามลำดับนี้:

### 1. ⚡ [The Verdict — ชี้ขาด]
- บอกทางเลือกที่แนะนำทันที
- ระบุ **Type 1** (คิดหนัก) หรือ **Type 2** (ลงมือทันที)
- Cost of Inaction: "ถ้าไม่เลือก ภายใน 6 เดือนชีวิตจะแย่ลงอย่างไร"

### 2. 📊 [5-D Analysis Table]

| มิติ | ทางเลือก A | ทางเลือก B |
|------|-----------|-----------|
| 🧠 จิตวิทยา | ... | ... |
| 📐 ตรรกะ | ... | ... |
| 💼 ธุรกิจและชีวิต | ... | ... |
| 🧘 ปรัชญา | ... | ... |
| 💓 อารมณ์ | ... | ... |

### 3. 🛡️ [Risk & Strategy]
- **Type 1**: Pre-mortem (อะไรคือ worst case? รับมือยังไง?)
- **Type 2**: Fail-Fast Protocol (สัญญาณอะไรที่จะบอกให้หยุด?)
- Soft landing 1 วิธี

### 4. 🔄 [Extreme Perspectives]
- **มุมมองพลิกกรอบ** — สิ่งที่ไม่เคยคิดถึง
- **มุมมองสัจธรรม** — สิ่งที่ไม่อยากได้ยินแต่ต้องได้ยิน

### 5. ✅ [The Next Step]
- 1 action step ที่ทำได้ทันทีภายใน 24-48 ชม.
- **ห้าม** เป็น "หาข้อมูลเพิ่ม" หรือ "ลองคิดดู"
- ต้องวัดผลได้จริง

---

## 📂 โครงสร้างโฟลเดอร์

```
zecision/
│
├── SKILL.md              ← 🧠 Entry point หลัก — ให้ AI agent อ่าน
│
├── template/             ← 📋 แม่แบบตอบ
│   ├── response.md           ← เทมเพลตตอบ 5 ส่วน
│   └── analysis.md           ← ตารางวิเคราะห์ 5 มิติ
│
├── example/              ← 👤 ตัวอย่างคำตอบจริง 5 สถานการณ์
│   ├── 01-career.md          ← อาชีพ (ลาออก vs อยู่ต่อ)
│   ├── 02-business.md        ← ธุรกิจ (เปิดร้าน vs แฟรนไชส์)
│   ├── 03-relationship.md    ← ความสัมพันธ์ (ฝืนต่อ vs เลิก)
│   ├── 04-finance.md         ← การเงิน (ซื้อคอนโด vs ลงทุน)
│   └── 05-education.md       ← การศึกษา (เรียน vs เริ่มทำงาน)
│
├── reference/            ← 📚 หลักการ + ความรู้
│   ├── decision-frameworks.md  ← 7 Frameworks การตัดสินใจ
│   ├── cognitive-biases.md     ← 20+ Cognitive biases
│   └── cheatsheet.md           ← สรุป 1 หน้า
│
├── scripts/              ← 💬 คลังคำถาม + มุมมอง
│   ├── socratic-questions.md   ← คำถามกระตุ้นคิด
│   └── perspective-shifts.md   ← มุมมองพลิกกรอบ + สัจธรรม
│
├── workflow/             🔄 6 ขั้นตอนของ agent
│   └── workflow.md
│
├── tools/                ← 🛠️ เครื่องมือช่วยคิด
│   ├── decision-tree.md       ← Decision Tree
│   └── energy-budget.md       ← Energy Budget Calculator
│
└── types/                ← 🏷️ Type 1 vs Type 2
    └── decision-types.md
```

---

## 🎯 ตัวอย่างสถานการณ์

| เรื่อง | สถานการณ์ | ทางเลือก A | ทางเลือก B | สิ่งที่ zecision จะช่วย |
|-------|-----------|-----------|-----------|----------------------|
| 💼 **อาชีพ** | ที่ทำงาน toxic แต่เงินเดือน 80K | ลาออก | อยู่ต่อ | วิเคราะห์ 5 มิติ + Cost of inaction |
| 🏪 **ธุรกิจ** | เปิดร้านกาแฟ vs แฟรนไชส์ชานม | ร้านกาแฟ | แฟรนไชส์ | Risk analysis + Energy budget |
| 💕 **ความสัมพันธ์** | ฝืนต่อ vs เลิก | ฝืนต่อ | เลิก | Extreme perspectives + สัจธรรม |
| 🏦 **การเงิน** | ดาวน์คอนโด vs ลงทุนกองทุน | ซื้อคอนโด | ลงทุนกองทุน | 5-dimension analysis + Pre-mortem |
| 📚 **การศึกษา** | Bootcamp 6 เดือน vs ค่อยๆ เรียนเอง | Bootcamp | เรียนเอง | Decision tree + Fail-fast protocol |

อ่านตัวอย่างเต็มๆ ได้ที่ `example/` ค่ะ

---

## 🔗 ระบบที่เกี่ยวข้อง

| Skill | ใช้คู่กันยังไง |
|-------|--------------|
| 🎌 **[ikigai](https://github.com/hartkitsak/ikigai)** | zecision ช่วยเลือกทาง, ikigai ช่วยค้นหาว่าทางไหนคือทางของคุณ |
| 🎬 **[mrbeginner](https://github.com/hartkitsak/mrbeginner)** | ถ้ากำลังลังเลว่าจะทำ content แนวไหน — zecision ช่วยตัดสินใจ, mrbeginner ช่วยผลิต |

---

## 📥 ติดตั้ง

```bash
# วาง skill ไว้ที่ ~/.claude/skills/
git clone https://github.com/hartkitsak/zecision.git "$env:USERPROFILE\.claude\skills\zecision"
```

จากนั้นพิมพ์ `/zecision` ใน Claude Code

---

## 📄 License

MIT — free to use, modify, and share.

Built by [hartkitsak](https://github.com/hartkitsak)
