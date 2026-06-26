# LEORIO FX Obsidian Knowledge Base

คลังความรู้ Obsidian สำหรับสรุปและเรียนเทคนิคเทรดจากช่อง YouTube LEORIO FX (@Mrngig)

## เริ่มอ่านตรงไหน

เปิด vault นี้ใน Obsidian:

```text
LEORIO FX Obsidian Vault
```

แล้วเริ่มจากไฟล์:

```text
00 - Maps of Content/01 - Technical Trading Manual.md
```

จากนั้นอ่านไฟล์ใน `03 - Projects` ตามลำดับเลข:

```text
00 - LEORIO FX Trading Framework.md
01 - Market Bias - อ่านทิศทางก่อนเข้าออเดอร์.md
02 - Entry Model - PA Rejection และการเคลียร์ไส้.md
03 - Setup Playbook - FVG Liquidity Breakout.md
04 - Risk Model - เทรดให้รอดก่อนปั้นพอร์ต.md
05 - Practice Plan - ฝึกอ่านกราฟ 14 วัน.md
06 - Trading Study Checklist.md
07 - Trade Journal Template - LEORIO FX.md
```

## โครงสร้าง Vault

```text
LEORIO FX Obsidian Vault/
  00 - Maps of Content/
    00 - Knowledge Base Index.md
    01 - Technical Trading Manual.md
  01 - Sources/
    สรุปรายวิดีโอจากช่อง LEORIO FX
  02 - Concepts/
    โน้ตแนวคิด เช่น FVG, Liquidity Sweep, CHoCH, Price Action
  03 - Projects/
    คู่มือเรียนเทรด เรียงตามลำดับอ่าน
  99 - Attachments/
    Technical Charts/
      กราฟ SVG ตัวอย่างสำหรับเรียน setup
```

## วิธีใช้

1. เปิด Obsidian
2. เลือก `Open folder as vault`
3. เลือกโฟลเดอร์ `LEORIO FX Obsidian Vault`
4. เปิด `00 - Maps of Content/01 - Technical Trading Manual.md`
5. อ่านตามลำดับ `00` ถึง `07` ใน `03 - Projects`

## แกนความรู้ใน Vault

- อ่านโครงสร้างตลาดด้วย `Market Structure` และ `CHoCH`
- หาโซนเทรดจาก `FVG`, `Liquidity Sweep`, และ `Breakout Retest`
- เข้าออเดอร์ด้วย `PA Rejection` และ `การเคลียร์ไส้`
- คุมความเสี่ยงด้วย `Entry / SL / TP / R:R`
- ฝึกผ่านแผน `Practice Plan - ฝึกอ่านกราฟ 14 วัน`
- จดผลด้วย `Trade Journal Template`

## หมายเหตุเรื่องความเสี่ยง

เนื้อหานี้เป็นสรุปเพื่อการศึกษา ไม่ใช่คำแนะนำการลงทุน หลายวิดีโอใน Knowledge Base มีตัวอย่างการปั้นพอร์ตด้วย lot ใหญ่และความเสี่ยงสูง ควรใช้เพื่อศึกษาแนวคิดการอ่านกราฟเท่านั้น และต้องกำหนด risk ต่อออเดอร์ให้เหมาะกับพอร์ตของตัวเอง

## ไฟล์ช่วยสร้าง

ในโฟลเดอร์โปรเจกต์มีสคริปต์ที่ใช้สร้างและจัดระเบียบ vault:

```text
build_leorio_vault.js
build_trading_manual.js
add_technical_chart_examples.js
order_project_reading_files.js
```

สคริปต์เหล่านี้เป็นเครื่องมือช่วย generate/ปรับโครงสร้าง ไม่จำเป็นต้องรันซ้ำถ้าแค่อ่าน vault ใน Obsidian
