# Software Engineer Project G18 SEC2

## สมาชิกทีม

- **B6504359** นายณัฐกุล สมานใจ
- **B6512651** นายรัฐพล ผลไธสง
- **B6534240** นายตะวันฉาย บุราคร
- **B6534721** นางสาวกัญญาพร ขุนเดช
- **B6515683** นางสาวจณิสตา ตั้งกระจ่างจิตร
- **B6328726** นายสหพล แสนพวง

---
## Github team18

- clone Git repository 

```bash
git clone git@github.com:sut67/teamxx.git
```

## Backend 

- test backend

```go
go mod tidy
go run main.go
```

## Frontend 

```bash
npm install --force
```

- More Installation for Source Code
```bash
npm install --force
```

- test Frontend

```bash
npm run dev
```

## Git Command Version Control

- Branch

```bash
git branch
git checkout issue-xx
git checkout -b issue-XX
```

- Pull Source Code

```bash
git fetch 
git pull origin main
```

- Megre branch issue-xx to branch Main

```bash
git checkout -b issue-xx
git add .
git commit -m "comment - close #xx"
git push origin issue-xx
-------------------------
git checkout main
git merge issue-xx --no-ff
git push origin main
```

- Other Git Command

```bash
git remote update : ดึงข้อมูลเกี่ยวกับ Branch และ Commit ล่าสุดจาก Remote
git rebase origin/main : ทำให้ brach ปัจจุบัน มี code เทียบเท่า branch Main
----------
git init : สร้าง Git Repository ใหม่ในโฟลเดอร์ปัจจุบัน
Git status : เเสดงสถานะของ branch ปัจจุบัน
Git reset : ย้อนสถานะของไฟล์หรือ Commit กลับไปยังจุดก่อนหน้า
Git merge : วมการเปลี่ยนแปลงจาก Branch อื่นเข้ามายัง Branch(Main) ปัจจุบัน
Git tag : สร้าง Tag เพื่อระบุจุดสำคัญในประวัติ เช่น เวอร์ชันของโค้ด
----
Git Log : ดูประวัติ Commit ทั้งหมดใน Repository
Git Log --graph : แสดงประวัติ Commit ในรูปแบบกราฟ
```

- Advice
```bash
ลงแค่สองตัวนี้ ตั้งค่า NPM ให้ข้ามการตรวจสอบ Peer Dependencies npm config set legacy-peer-deps true 
ปิดการตรวจสอบ คำสั่งนี้จะทำให้ไม่ต้องใส่ --legacy-peer-deps ทุกครั้ง npm config set legacy-peer-deps false 
เปิดการตรวจสอบ npm install
```