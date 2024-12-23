# Software Engineer Project G18 SEC2

## สมาชิกทีม

- **B6504359** นายณัฐกุล สมานใจ
- **B6512651** นายรัฐพล ผลไธสง
- **B6534240** นายตะวันฉาย บุราคร
- **B6534721** นางสาวกัญญาพร ขุนเดช
- **B6515683** นางสาวจณิสตา ตั้งกระจ่างจิตร
- **B6328726** นายสหพล แสนพวง

---

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

- More Installation
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
git remote update
git rebase origin/main
----------
git log
```

- อื่นๆ

```bash
git clone <url> # ดึง code จาก Git ลง vs.
git init # เริ่มต้นสร้าง repository ใหม่ในโฟลเดอร์ปัจจุบัน โดยสร้าง .git
git status # ตรวจสอบสถานะของ repository ปัจจุบัน
git merge  # นำการเปลี่ยนแปลงจาก branch ที่เลือกมาไว้ใน branch ปัจจุบัน โดยจะแสดงประวัติบน git graph (เหมาะในการใช้ เอา code ลง main)
git diff origin/main <issue-??> #ตรวจสอบความแตกต่างของ 2 branch

```
