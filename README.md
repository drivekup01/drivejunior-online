# DriveJunior

[เปิดเว็บไซต์](https://drivejunior-scan-workspace.drivekup01.chatgpt.site/) · [หน้า GitHub Pages](https://drivekup01.github.io/drivejunior-online/) · [ดาวน์โหลดซอร์สโค้ด](https://github.com/drivekup01/drivejunior-online/raw/refs/heads/main/DriveJunior-source.zip)

อ่านออเดอร์จากรูป ตรวจแก้ข้อมูลทีละช่อง อ่านทั้งชุด และส่งออก Excel

- ทุกคนเปิดเว็บได้ ส่วนอ่าน AI ต้องลงชื่อเข้าใช้ด้วย ChatGPT
- ใช้เครดิตเจ้าของเว็บ คนละ 20 คำขอต่อวัน และรวม 200 คำขอต่อวัน
- นับทุกคำขอที่เริ่มส่งไปอ่าน รวมอ่านซ้ำและคำขอที่ล้มเหลว รีเซ็ตเที่ยงคืนเวลาไทย
- ข้อมูลรูปและออเดอร์เก็บในเบราว์เซอร์แต่ละเครื่อง ใช้สำรองงานเพื่อย้ายเครื่อง
- API key อยู่บนเซิร์ฟเวอร์ ไม่อยู่ใน repository หรือ archive นี้

GitHub Pages เป็นหน้าเปิดเข้าแอปที่โฮสต์บน Sites ส่วนอ่าน AI และระบบโควตาทำงานบนเซิร์ฟเวอร์ ไม่ได้รัน backend บน GitHub Pages

## Source archive

DriveJunior-source.zip มีซอร์สแอปและ schema ฐานโควตา ไม่รวมคีย์ ภาพลูกค้า หรือข้อมูลออเดอร์ หากนำไปตั้งเซิร์ฟเวอร์แยก ต้องสร้าง Site identity ใหม่ ตั้ง runtime secret และใช้ migrations ตาม README ใน archive
