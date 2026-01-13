---
title: "มุมเล็กๆ ของโทโมะ"
layout: single      # เปลี่ยนเลย์เอ้าท์หลัก
author_profile: true   # เปิดหรือปิดโปรไฟล์มุมซ้าย
excerpt: "ยินดีต้อนรับเข้าสู่หลังบ้านผมครับ~"
# 3. การตั้งค่า Header (แถบดำๆ) ของเดิมของคุณ ใช้ได้ต่อเลยครับ
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  # ถ้ามีรูปแล้ว ใส่บรรทัดนี้ได้เลย:
  overlay_image: /assets/images/hero.png
# ส่วนการสร้าง Grid 
feature_row:
  - image_path: /assets/images/slimevrguide.png
    alt: "SlimeVR ไกด์ภาษาไทย"
    title: "คู่มือการใช้งาน SlimeVR ภาษาไทย"
    excerpt: "ศูนย์รวมข้อมูลเบื้องต้นสำหรับผู้สนใจเกี่ยวกับ SlimeVR"
    url: "/slimevr-docs/intro/"
    btn_label: "เข้าสู่หน้าคู่มือสไลม์"
    btn_class: "btn--primary"
  - image_path: /assets/images/tempbox.jpg
    alt: "Temp"
    title: "สารบัญ"
    excerpt: "placeholder"
    url: "/3d-printing/"
    btn_label: "placeholder"
    btn_class: "btn--info"
  - image_path: /assets/images/tempbox.jpg
    alt: "Placeholderh"
    title: "เติมพลังให้ผมและเพื่อนร่วมทาง"
    excerpt: "รวมช่องทางสนันสนุนผมและเพื่อนๆ ในคอมมูนิตี้ที่เดินเคียงข้างผม"
    url: "/support-me-n-friends/"
    btn_label: "สนันสนุนพวกเราที่นี่"
    btn_class: "btn--success"

---

ผมคือโทโมะครับ นี่เป็นเว็บไซดที่ผมรวบรวมข้อมูลของโปรเจ็คที่ผมทำ จดบันทึกข้อมูลต่างๆ ที่ผมสนใจ 
ไม่ว่าจะเป็น SlimeVR, 3D printing หรือจะเป็นเกี่ยวกับ Vtubing ก็ดี
โดยเป้าหมายที่ผมต้องการคือ

- ทำให้ข้อมูลเข้าถึงได้ง่ายขึ้น ในภาษาไทย
- จดบันทึกเส้นทางการเดินทางของผมเอง
- เป็นการโฆษณาหรือสร้างเครดิตให้ตัวเองในอนาคต

ส่วนถ้าใครต้องการสนับสนุนผมโดยตรง ก็สามารถคลิกไปที่ {support me} ได้เลยนะครับ

<br>

{% include feature_row %}

<style>
 <style>
  /* 1. ขยาย Container หลักของหน้า Splash ให้กว้างเท่ากับที่คุณตั้งไว้ใน variables */
  .layout--single .wrapper {
    max-width: calc(100vw - 200px) !important;
  }

  /* 2. บังคับให้แถบเมนูด้านบน (Masthead) กางออกให้สุดขอบเท่ากับเนื้อหา */
  .layout--single .masthead .wrapper {
    max-width: calc(100vw - 200px) !important;
    padding-left: 0 !important;
    padding-right: 0 !important;
  }

  /* 3. จัดตำแหน่งเนื้อหาภายใน (Article) ให้ชิดซ้ายตรงกับโลโก้ */
  .layout--single .single {
    width: 100% !important;
  }

  /* 4. กรณีมี Page Hero (รูปใหญ่ด้านบน) ให้กางออกด้วย */
  .layout--single .page__hero--overlay .wrapper {
    max-width: calc(100vw - 200px) !important;
  }
</style>


