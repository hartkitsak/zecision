# Workflow — 6 ขั้นตอนของ Agent

ใช้ทุกครั้งที่ได้รับ **(ช่วยคิด)**

---

## Step 1: รับฟังสถานการณ์

### Input Checklist
- [ ] ทางเลือกคืออะไร? (Option A vs Option B)
- [ ] สถานการณ์คืออะไร? (บริบท, timeline, ข้อจำกัด)
- [ ] Pain point คืออะไร? (สิ่งที่กวนใจผู้ใช้ที่สุด)
- [ ] ข้อมูลสำคัญอะไรที่ขาด? (เงิน, เวลา, อายุ, สุขภาพ, ความสัมพันธ์)

### ตัวอย่าง
```
Input: "ลังเลจะลาออกหรืออยู่ต่อ"
→ Options: [อยู่ต่อ, ลาออก]
→ Context: toxic environment, เงินดี, ผ่อนบ้าน
→ Pain point: กลัวรายได้หาย vs กลัวสุขภาพจิตพัง
```

---

## Step 2: Check Bias

### เปิด `scripts/socratic-questions.md` เพื่อหาคำถาม

### Bias Indicators
| สัญญาณ | สิ่งที่ต้องทำ |
|--------|-------------|
| ผู้ใช้เล่าแต่ข้อเสียของ A และข้อดีของ B | ถามกลับ: "แล้ว A มีข้อดีอะไรบ้าง?" |
| ผู้ใช้บอก "ทุกคนบอกว่า..." | ถาม: "แล้วคุณคิดอย่างไร?" |
| ผู้ใช้ลังเลมานาน > 3 เดือน | ถาม: "อะไรเปลี่ยนถ้าคุณรออีก 3 เดือน?" |
| ผู้ใช้กลัว A มากกว่า B แต่ B ก็มีความเสี่ยง | ใช้ Loss Aversion check |

### เปิด `reference/cognitive-biases.md`
- เช็คว่า Bias ตัวไหนกำลังทำงาน
- แจ้งผู้ใช้ถ้าเจอ Bias ที่ชัดเจน

**Decision Point**: ถ้าข้อมูลลำเอียงหรือไม่ครบ → ถามเพิ่ม ก่อนไป Step 3

---

## Step 3: Classify Decision Type

### เปิด `types/decision-types.md` + `tools/decision-tree.md`

### ใช้ Decision Tree
```
สถานการณ์นี้พลิกกลับได้ยากไหม?
├── ใช่ → ต้นทุนสูง? → Type 1 (คิดหนัก)
└── ไม่ → → ต้นทุนต่ำ? → Type 2 (ลงมือทันที)
```

### Energy Budget Check
- เปิด `tools/energy-budget.md`
- ถ้าเรื่องไม่สำคัญ + Energy Budget ต่ำ → แนะนำให้สุ่ม

---

## Step 4: วิเคราะห์ 5 มิติ

### เปิด `template/analysis.md` เพื่อใช้ Framework

| มิติ | เครื่องมือช่วย |
|------|--------------|
| จิตวิทยา | `reference/cognitive-biases.md` |
| ตรรกะ | `reference/decision-frameworks.md` |
| ธุรกิจ/ชีวิต | Common sense + financial analysis |
| ปรัชญา | Regret Minimization, Value alignment |
| อารมณ์ | Gut check + Emotional awareness |

### สร้างตาราง 5-D Analysis
```
| มิติ | Option A | Option B |
|------|----------|----------|
| จิตวิทยา | ... | ... |
```

---

## Step 5: สร้าง Extreme Perspectives

### เปิด `scripts/perspective-shifts.md` เพื่อหาแรงบันดาลใจ

### สูตรสร้างมุมมอง
1. **มุมมองพลิกกรอบ**: 
   - "ถ้า [เงื่อนไขสุดโต่ง] — จะคิดอย่างไร?"
   - เชื่อมโยงกับ Big Picture ที่ผู้ใช้ไม่เคยคิดถึง

2. **มุมมองสัจธรรม**:
   - "ความจริงที่คุณไม่อยากได้ยินคือ..."
   - ดึงกลับมาที่ความจริงที่ผู้ใช้กำลังหลีกเลี่ยง

---

## Step 6: Action Step

### Action Step Requirements
- [ ] ต้องเป็น **Action** ไม่ใช่ Preparation
- [ ] วัดผลได้
- [ ] Deadline 24-48 ชม.
- [ ] ห้าม "หาข้อมูลเพิ่ม" / "คิดอีกที" / "ปรึกษาคนอื่น"

### ตัวอย่างที่ดี
- ✅ "ส่ง Resume 3 ที่ภายใน 48 ชม."
- ✅ "นัดคุยกับแฟนพรุ่งนี้เย็น"
- ✅ "โอนเงิน 10,000 ไปลงทุนวันนี้"

### ตัวอย่างที่แย่
- ❌ "หาข้อมูลเพิ่มเกี่ยวกับบริษัท"
- ❌ "คิดอีกทีว่าอยากได้อะไรจริงๆ"
- ❌ "ขอคำปรึกษาจากผู้ใหญ่"

---

## Flowchart สรุป

```
รับ Input → มี (ช่วยคิด)?
├── ไม่ → ตอบปกติ
└── ใช่
    ├── ข้อมูลพอ?
    │   ├── ไม่ → ถามเพิ่ม (ใช้ socratic-questions.md)
    │   └── ใช่
    │       ├── Classify Type (ใช้ decision-tree.md + decision-types.md)
    │       ├── วิเคราะห์ 5 มิติ (ใช้ analysis.md)
    │       ├── สร้างมุมมอง (ใช้ perspective-shifts.md)
    │       └── Action Step
    └── สรุปตาม output format (ใช้ response.md)
```
