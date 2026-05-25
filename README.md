# zecision

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

zecision is a realistic and progressive decision advisor for Thai speakers stuck in analysis paralysis. It helps users cut through indecision and move to action within 24-48 hours.

## About This Skill

zecision operates on six core principles:

- **Speak the truth** — Use real data and direct feedback, not comfort. Comfort slows decisions down.
- **Decisive action** — Distinguish Type 1 (irreversible — think carefully) from Type 2 (reversible — act now) decisions
- **Action-oriented** — Every recommendation must be doable within 24-48 hours. No "gather more information" steps.
- **5-dimension analysis** — Evaluate choices through psychology, logic, business & life, philosophy, and emotion
- **Cost of inaction** — Show how inaction makes things worse over time
- **Energy budget** — Low-stakes decisions should be made quickly, even randomly

The skill assesses the situation, applies the appropriate framework, and delivers a structured verdict with a concrete next step.

## Usage

Open Claude Code and type `/zecision` followed by your dilemma:

```
/zecision ผมกำลังลังเลระหว่างลาออกกับอยู่ต่อ ที่เดิม toxic แต่เงินดี
ควรตัดสินใจยังไง?
```

```
/zecision จะเลือกเรียนต่อ ป.โท หรือ เริ่มธุรกิจของตัวเองดี
ผมอายุ 24 มีเงินเก็บ 5 แสน
```

```
/zecision มีเงินก้อน 1 ล้าน ควรดาวน์คอนโด หรือลงทุนกองทุนรวมดี
อายุ 30 รายได้ 50K/เดือน
```

## Installation

### Claude Code
Clone the repository to your skills directory:
```
git clone https://github.com/hartkitsak/zecision.git ~/.claude/skills/zecision
```

Then type `/zecision` in Claude Code.

### Other tools
Clone anywhere and add the path to your configuration.

## License

MIT — free to use, modify, and share.

Built by [hartkitsak](https://github.com/hartkitsak)
