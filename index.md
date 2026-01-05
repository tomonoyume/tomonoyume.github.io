---
layout: splash        # เปลี่ยนเลย์เอ้าท์หลัก
author_profile: true   # เปิดหรือปิดโปรไฟล์มุมซ้าย

header: 
  overlay_image: /assets/images/your-hero-image.jpg  # รูป Header ที่คุณต้องการ
  overlay_filter: 0.5     # ช่วยให้ข้อความบนรูปอ่านง่ายขึ้น
  overlay_color: "#000"


# ส่วนการสร้าง Grid 
feature_row:
  - image_path: /assets/images/tempbox.jpg
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
  /* 1. สั่งให้แถบเมนูด้านบน (Masthead) กางออกเท่ากับเนื้อหา */
  .masthead .wrapper {
    max-width: 90% !important; /* หรือใส่ calc(100vw - 200px) ตามที่คุณตั้ง */
    padding-left: 0 !important;
    padding-right: 0 !important;
  }

  /* 2. สั่งให้เนื้อหาหลัก (Main Content) กางออกเท่ากัน */
  #main .wrapper {
    max-width: 90% !important; 
    padding-left: 0 !important;
    padding-right: 0 !important;
  }

  /* 3. จัดหัวข้อใหญ่ให้ตรงแนว */
  .page__inner-wrap {
    margin-left: 0 !important;
    width: 100% !important;
  }
</style>