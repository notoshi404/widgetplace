# Live Demo

[Widgetplace](https://widgetplace-a736g.ondigitalocean.app/)

# Documents

- [Setup Guide](../main/docs/setup-obs.md)

---

# วิธีติดตั้งและใช้งาน Widgetplace

## 1. เตรียมความพร้อม
- ติดตั้ง [Node.js 18+](https://nodejs.org/)
- ติดตั้ง [Git](https://git-scm.com/)

## 2. Clone โปรเจกต์
```sh
git clone https://github.com/notoshi404/widgetplace.git
cd widgetplace
```

## 3. ติดตั้ง dependencies
```sh
npm install
```

## 4. สร้างไฟล์ .env
สร้างไฟล์ `.env` ที่ root ของโปรเจกต์ (หรือใช้ไฟล์ `try.env` แล้วเปลี่ยนชื่อเป็น `.env`)  
ตัวอย่าง:
```
NEXT_PUBLIC_RELAY_URLS=wss://relay.damus.io,wss://relay.notoshi.win,wss://relay.nostr.band,wss://nostr.oxtr.dev,wss://relay.siamdev.cc
```

## 5. รันแอปพลิเคชัน (โหมดพัฒนา)
```sh
npm run dev
```
เปิดเบราว์เซอร์ไปที่ [http://localhost:3000](http://localhost:3000)

## 6. Build สำหรับ production
```sh
npm run build
npm start
```

---