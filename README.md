# zecision ⚡

**ที่ปรึกษาการตัดสินใจเด็ดขาด** สำหรับคนที่ติด Analysis Paralysis — วิเคราะห์ 5 มิติ, แยก Type 1 vs Type 2, ชี้ขาด + Action Step ภายใน 24-48 ชม.

## Features

- 🎯 6 หลักการ — พูดความจริง, เฉียบขาด, ลงมือได้จริง, วิเคราะห์ 5 มิติ, Cost of Inaction, Energy Budget
- 🧠 วิเคราะห์ 5 มิติ — จิตวิทยา, ตรรกะ, ธุรกิจ/ชีวิต, ปรัชญา, อารมณ์
- 🔀 แยก Type 1 (คิดหนัก) vs Type 2 (ลงมือทันที)
- 💰 Energy Budget Calculator — ประเมินว่าควรใช้สมองคิดเรื่องนี้แค่ไหน
- 🪞 Extreme Perspectives — มุมมองพลิกกรอบ + สัจธรรม
- ⏱️ Action Step — Deadline 24-48 ชม., วัดผลได้, ไม่ใช่ "หาข้อมูลเพิ่ม"

## Installation

```powershell
git clone https://github.com/hartkitsak/zecision.git "$HOME\.config\opencode\skills\zecision"
```

## Usage

```
/zecision ผมลังเลระหว่างลาออกกับอยู่ต่อ ที่เดิม toxic แต่เงินดี ควรตัดสินใจยังไง? (ช่วยคิด)
```

> ใช้ "(ช่วยคิด)" ต่อท้ายเพื่อ activate skill

## Structure

```
zecision/
├── SKILL.md                    ← Entry point (อ่านอัตโนมัติ)
├── workflow/workflow.md        ← 6 Step + language & tone + flowchart
├── scripts/
│   ├── socratic-questions.md   ← คลังคำถามกระตุ้นคิด
│   └── perspective-shifts.md   ← มุมมองพลิกกรอบ + สัจธรรม
├── template/
│   ├── response.md             ← เทมเพลตตอบ 5 ส่วน
│   └── analysis.md             ← 5-D analysis framework
├── tools/
│   ├── decision-tree.md        ← Decision Tree classifier
│   └── energy-budget.md        ← Energy Budget Calculator
├── types/
│   └── decision-types.md       ← Type 1 vs Type 1.5 vs Type 2
└── reference/
    ├── cognitive-biases.md     ← 14 biases + mitigation
    └── decision-frameworks.md  ← 8 frameworks
```

## Example

**User**: "ลังเลจะลาออกกับอยู่ต่อ ที่เดิม toxic แต่เงินดี (ช่วยคิด)"

**Agent จะ**: ฟัง → เช็ค bias → classify Type 1 → วิเคราะห์ 5 มิติ → เสนอมุมมองพลิกกรอบ/สัจธรรม → ชี้ขาด + Action Step

## Requirements

- [Claude Code](https://claude.ai) หรือ [opencode](https://opencode.ai)

## License

MIT
