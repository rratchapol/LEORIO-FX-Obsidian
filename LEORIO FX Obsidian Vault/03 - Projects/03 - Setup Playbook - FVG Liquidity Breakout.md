---
type: project
title: Setup Playbook - FVG Liquidity Breakout
tags:
  - knowledge-base
  - trading
  - leorio-fx
  - setup-playbook
created: 2026-06-26
updated: 2026-06-26
---

# Setup Playbook - FVG Liquidity Breakout

## Setup 1: FVG Pullback

## กราฟตัวอย่าง FVG Pullback

![[04-fvg-pullback.svg]]

ราคาเคลื่อนที่แรงจนเกิด imbalance แล้วกลับมาทดสอบ FVG ถ้าโซนนี้ตรงกับ bias และมี trigger จึงค่อยพิจารณาเข้า


### ใช้เมื่อ

- โครงสร้างตลาดมี bias ชัด
- ราคาเคลื่อนที่แรงจนเกิด imbalance
- ราคาย้อนกลับมาแตะ FVG

### วิธีเข้า

1. ระบุ bias จาก market structure
2. มาร์ก FVG ที่สอดคล้องกับ bias
3. รอราคากลับมาที่ FVG
4. รอ PA rejection หรือการเคลียร์ไส้
5. เข้าเมื่อ trigger เกิดในโซน
6. SL อยู่นอก FVG หรือหลัง swing ที่ทำให้ setup ผิด

### จุดระวัง

FVG ที่อยู่สวนโครงสร้างใหญ่มีโอกาสกลายเป็นแค่จุดพัก ไม่ใช่จุดกลับตัว

## Setup 2: Liquidity Sweep Reversal

## กราฟตัวอย่าง Liquidity Sweep

![[05-liquidity-sweep.svg]]

ตลาดทะลุ equal highs เพื่อกิน stop แล้วปิดกลับเข้า range จุดนี้ยังไม่ใช่สัญญาณ sell ทันที ต้องรอ rejection หรือ clear wick เพิ่ม


### ใช้เมื่อ

- ราคา sideway ในกรอบหรือมี high/low ชัด
- เห็นราคาทะลุ high/low แล้วรีบกลับเข้ากรอบ
- มีแท่ง rejection หลัง sweep

### วิธีเข้า

1. มาร์ก high/low ที่คนส่วนใหญ่น่าจะตั้ง stop
2. รอราคาทะลุไปกิน liquidity
3. รอปิดกลับหรือ rejection ชัดเจน
4. เข้าเมื่อราคาย้อนเคลียร์ไส้
5. TP แรกที่กลางกรอบหรือปลายกรอบอีกฝั่ง

### จุดระวัง

อย่า sell เพียงเพราะทะลุ high หรือ buy เพียงเพราะทะลุ low ต้องรอหลักฐานว่าการทะลุนั้นล้มเหลว

## Setup 3: Breakout Retest Continuation

## กราฟตัวอย่าง Breakout Retest

![[06-breakout-retest.svg]]

หลังเบรกกรอบ ให้รอราคาย้อนกลับมา retest แล้วทำ higher low ก่อนเข้า buy การเข้าไกลจาก retest จะทำให้ SL กว้างและ RR แย่


### ใช้เมื่อ

- ราคาเบรกกรอบหรือสามเหลี่ยม
- โครงสร้าง timeframe เล็กทำ higher low สำหรับ buy หรือ lower high สำหรับ sell
- ราคา retest โซนที่เพิ่งเบรก

### วิธีเข้า Buy

1. ราคาเบรกแนวต้านหรือกรอบสามเหลี่ยมขึ้น
2. ย่อกลับมาทดสอบโซนเดิม
3. low ล่าสุดยังยกสูงขึ้น
4. มี PA rejection ฝั่ง buy
5. เข้า buy ใกล้ retest/ไส้

### จุดระวัง

ถ้าเข้าไกลจาก retest มากเกินไป จะกลายเป็นการไล่ราคาและต้องใช้ SL กว้าง

## เลือก Setup ไหนดี

- ตลาดมีเทรนด์ชัด: ใช้ FVG Pullback หรือ Breakout Retest
- ตลาด sideway: รอ Liquidity Sweep
- ตลาดเพิ่ง CHoCH: รอ pullback หลัง CHoCH และดูว่าราคาเริ่มสร้างโครงสร้างใหม่หรือยัง

## Sources

- [[Fair Value Gap FVG]]
- [[Liquidity Sweep]]
- [[Breakout Retest]]
- [[เทรดเล่นๆ ให้เด็กมันดู]]
- [[แชร์เทคนิค ที่ทำกำไรได้ 70000]]
- [[เทรด หาเงิน 90000 บาท ในเวลา 35 นาที]]
