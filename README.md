# Pre-Interview Answers: System Analyst

ผู้สมัคร: **[กชสิทธ์ นิลนนท์]**
ตำแหน่งที่สมัคร: **System Analyst**

## โครงสร้างไฟล์

| ไฟล์ | เนื้อหา |
|---|---|
| [`01-scenario-1-flash-sale.md`](./01-scenario-1-flash-sale.md) | สถานการณ์ที่ 1: Flash Sale 1,000 สิทธิ์ (Architecture + Concurrency/Race Condition) |
| [`02-scenario-2-mentoring-junior.md`](./02-scenario-2-mentoring-junior.md) | สถานการณ์ที่ 2: Mentor น้อง Junior ที่ติดงาน API |
| [`03-scenario-3-coupon-100.md`](./03-scenario-3-coupon-100.md) | สถานการณ์ที่ 3: คูปอง 100 สิทธิ์ ผู้ใช้หลักหมื่น (Overbooking) |
| [`04-scenario-4-hardcoded-secrets.md`](./04-scenario-4-hardcoded-secrets.md) | สถานการณ์ที่ 4: Hardcode API Key / URL ของ 3rd-party |
| [`prompts.md`](./prompts.md) | Prompt ที่ใช้กับ AI ในแต่ละข้อ และสิ่งที่แก้ไขด้วยตนเอง |

## การใช้ AI

มีการใช้ AI ช่วยร่างและเรียบเรียงคำตอบ รายละเอียดอยู่ใน [`prompts.md`](./prompts.md)

## สมมติฐานโดยรวม

- ตัวเลขทราฟฟิกและเครื่องมือที่ยกตัวอย่าง (Redis, Kafka/SQS, PostgreSQL ฯลฯ) เป็นการออกแบบตามโจทย์ ในงานจริงต้องปรับตามงบ ผู้ให้บริการคลาวด์ และ stack เดิมของบริษัท
- ทุกการออกแบบที่เกี่ยวกับประสิทธิภาพควรยืนยันด้วย load test ก่อนใช้งานจริง
