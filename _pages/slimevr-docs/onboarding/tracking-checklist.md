---
title: "รายการเตรียมความพร้อมแทร็กเกอร์"
layout: single
permalink: /slimevr-docs/tracking-checklist/
author_profile: false
classes: wide
toc: false

sidebar:
  title: "คู่มือการใช้ SlimeVR"
  nav: sidebar-sample

---

รายการการเตรียมพร้อมแทร็กเกอร์ (Tracking checklist) คือลิสต์การตั้งค่าต่างๆ ที่แนะนำสำหรับ SlimeVR เพื่อให้ได้การจับตำแหน่งที่ดีที่สุด
โดยจะมีทั้งหมด 6 รายการ ได้แก่ 
- 🟩 การแก้ไขโปรไฟลเครือข่าย 
- 🟩 ตรวจสอบว่า steamVR ของคุณนั้นทำงานอยู่หรือไม่
- 🟥 ตรวจสอบว่าแทร็กเกอร์ที่คุณกำหนดมีปัญหาหรือไม่
- 🟥 แว่น VR ของคุณถูกกำหนดอยู่ที่ส่วนหัว
- 🟨 ตั้งค่า Stay aligned เรียบร้อยแล้ว
- 🟨 การตั้งค่าใน VRChat นั้นตรงกับที่ SlimeVR แนะนำ

การตั้งค่าพวกนี้ บางอย่างสามารถข้ามได้ แต่ผมแนะให้ทำตามรายการจะดีกว่า เพื่อการจับตำแหน่งที่ดีที่สุดของแทร็กเกอร์ของคุณ

![slimevronboard-1](/assets/images/slimeonboard/checklist.png){: .align-center}

โดยเราจะเริ่มจากการตั้งโปรไฟลเครือข่ายให้เป็น Private ก่อน โดยกดปุ่ม ไปที่ Control panel เลยครับ

![slimevronboard-1](/assets/images/slimeonboard/checklist1.png){: .align-center}

จากนั้นไปที่ Properties ของเครือข่ายอินเตอร์เน็ตที่่คุณใช้อยู่ 

![slimevronboard-1](/assets/images/slimeonboard/checklist2.png){: .align-center}

จากนั้นเปลี่ยนการตั้งค่าจาก Public เป็น Private ครับ

![slimevronboard-1](/assets/images/slimeonboard/checklist3.png){: .align-center}



ถัดมา ถ้าคุณจะใช้แทร็กเกอร์สไลม์กับ SteamVR ปรกติแล้วเมื่อต่อเข้ากับ Virtual Desktop หรือ Steam Link 
โปรแกรมก็จะเปิด SteamVR โดยอัตโนมัติ ส่วนถ้าคุณจะใช้แทร็กเกอร์สำหรับ Mocap ก็ละเว้นการตั้งค่านี้ไปได้เเลย

![slimevronboard-1](/assets/images/slimeonboard/steamvr.png){: .align-center}

จากนั้น ดูในโปรแกรมเลยครับ ว่าแทร็กเกอร์ทำงานปรกติรึเปล่า
ตามด้วยการตรวจสอบว่าแว่น VR หรือแทร็กเกอร์ส่วนหัวของคุณนั้นถูกกำหนดบนหัวแล้ว แล้วก็ไปต่อได้เลย!

![slimevronboard-1](/assets/images/slimeonboard/trackerhead.png){: .align-center}

ถ้าหากโปรแกรมมีการแนะนำให้ทำการรีเซ็ตแทร็กเกอร์ และตั้งศูนย์ใหม่ สามารถทำตามที่รายการแนะนำได้เลยครับ

![slimevronboard-1](/assets/images/slimeonboard/trackerresetwarn.png){: .align-center}

แล้วก็ ก่อนการเล่นทุกครั้ง เราควรจะต้องวางแทร็กเกอร์ไว้บนพื้นนิ่งๆ ประมาณ 10-15 วินาที เพื่อให้ IMU ด้านในตั้งศูนย์ตัวเอง
ถ้าหากไม่ได้่ตั้งมันจะขึ้นเป็นคำเตือนสีเหลืองๆ แบบนี้

![slimevronboard-1](/assets/images/slimeonboard/calibratewarning.png){: .align-center}


สุดท้ายจะเป็นการตั้งค่า Stay Aligned และการตั้งค่าของ VRchat ซึ่งผมได้ทำเป็นหัวข้อแยกไว้แล้วครับ โดยคลิปไปที่นี่ได้เลย