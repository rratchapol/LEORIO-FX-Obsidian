---
type: moc
title: Technical Trading Manual
tags:
  - knowledge-base
  - trading
  - leorio-fx
  - technical-analysis
  - trading-manual
created: 2026-06-26
updated: 2026-06-26
---

# Technical Trading Manual

> เริ่มอ่านจากไฟล์นี้ก่อน แล้วไล่ลำดับ `00` ถึง `07` ในโฟลเดอร์ `03 - Projects`

คู่มือสรุปเทคนิคเทรดจาก Knowledge Base ของ LEORIO FX เรียงจากการอ่านตลาด ไปจนถึงการเข้าออเดอร์และบริหารความเสี่ยง

## เส้นทางการอ่าน

## กราฟภาพรวมระบบ

![[08-framework-flow.svg]]

ภาพนี้คือ flow หลัก: อ่าน bias -> หา zone -> รอ trigger -> คุม risk ก่อนเข้าออเดอร์


1. [[00 - LEORIO FX Trading Framework|LEORIO FX Trading Framework]]
2. [[01 - Market Bias - อ่านทิศทางก่อนเข้าออเดอร์|Market Bias - อ่านทิศทางก่อนเข้าออเดอร์]]
3. [[02 - Entry Model - PA Rejection และการเคลียร์ไส้|Entry Model - PA Rejection และการเคลียร์ไส้]]
4. [[03 - Setup Playbook - FVG Liquidity Breakout|Setup Playbook - FVG Liquidity Breakout]]
5. [[04 - Risk Model - เทรดให้รอดก่อนปั้นพอร์ต|Risk Model - เทรดให้รอดก่อนปั้นพอร์ต]]
6. [[05 - Practice Plan - ฝึกอ่านกราฟ 14 วัน|Practice Plan - ฝึกอ่านกราฟ 14 วัน]]
7. [[07 - Trade Journal Template - LEORIO FX|Trade Journal Template - LEORIO FX]]

## สรุปสั้นที่สุด

ระบบนี้ไม่ได้เริ่มจากการเดาว่าราคาจะขึ้นหรือลง แต่เริ่มจากการถามว่า “โครงสร้างตลาดตอนนี้ฝั่งไหนคุมเกม” จากนั้นรอพื้นที่ที่ราคาน่าจะกลับมาทดสอบ เช่น FVG, liquidity zone, retest หลัง breakout แล้วค่อยใช้ price action rejection หรือการเคลียร์ไส้เป็น trigger เข้าออเดอร์

## สิ่งที่ต้องจำ

- อ่านโครงสร้างก่อนหา entry
- หาโซนก่อนรอสัญญาณแท่งเทียน
- เข้าใกล้จุดผิดทางเพื่อให้ SL สั้น
- อย่าคัดลอกขนาด lot จากวิดีโอ เพราะหลายตัวอย่างเป็นการปั้นพอร์ตเสี่ยงสูง
