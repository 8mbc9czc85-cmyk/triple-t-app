Triple T PWA Wrapper
====================

Web App ที่ฝังอยู่:
https://script.google.com/macros/s/AKfycbxzxMpRPzCP8cEp4uXRQnczy9dWnN8D7UQ3aqrj40SET1xC-5isI5vwmLV15usBWuCP/exec

ไฟล์:
- index.html
- manifest.webmanifest
- sw.js
- icon-180.png
- icon-192.png
- icon-512.png

วิธีใช้งาน:
1) อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ไปยังเว็บโฮสต์ที่เป็น HTTPS
   ตัวอย่าง: GitHub Pages, Cloudflare Pages, Netlify หรือโดเมนของบริษัท
2) เปิด URL ของ index.html ที่โฮสต์แล้วด้วย Safari บน iPhone
3) กด Share > Add to Home Screen
4) เปิดจากไอคอนใหม่

หมายเหตุ:
- อย่า Add to Home Screen จาก URL script.google.com เดิม
- ตัว Wrapper ต้องอยู่บน HTTPS จึงจะติดตั้ง Service Worker/PWA ได้
- Google Apps Script เดิมต้องอนุญาต iframe ซึ่ง Code.gs ปัจจุบันของคุณมี ALLOWALL อยู่แล้ว
