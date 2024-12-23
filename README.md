# Team05 Project

## สมาชิกทีม

- **B6509644** นายธนรัตน์ วิตันติวงศ์
- **B6526399** นายสิทธิโชค เชยงูเหลือม
- **B6513214** นายรามณรงค์ พันธเดช
- **B6506919** นายณัฐวุฒิ ถินราช
- **B6526221** นายณัฐวุฒิ สำรวมจิตต์

---

## Backend Version Control

```go
go mod init github.com/team05
go get -u github.com/gin-gonic/gin
go get -u gorm.io/gorm
go get -u gorm.io/driver/sqlite
go get -u github.com/dgrijalva/jwt-go
go get -u golang.org/x/crypto@v0.16.0
```

- ทดสอบ backend

```go
go mod tidy
go run main.go
```

## Frontend Version Control

```bash
npm create vite@latest Frontend
npm install
npm install --save react-router-dom@6.x
npm install antd --save
npm instal axios --save
npm instal dayjs --save
npm install antd-img-crop --save
```

- ทดสอบ Frontend

```bash
npm run dev
```

## Git Command

- สร้าง brach ใหม่

```bash
git checkout -b issue-XX
```

- ดึง code จาก main มา update issue

```bash
git fetch origin main
git pull origin main
```

- ทำ Todo เสร็จ

```bash
git add .
git commit -m "ข้อความ - close #XX"
git push origin issue-XX
```

- หากอยาก update code โดยไม่ให้ Git Graph เยอะ

```bash
git remote update
git rebase origin/main
```

- อื่นๆ

```bash
git clone <url> # ดึง code จาก Git ลง vs.
git init # เริ่มต้นสร้าง repository ใหม่ในโฟลเดอร์ปัจจุบัน โดยสร้าง .git
git status # ตรวจสอบสถานะของ repository ปัจจุบัน
git merge  # นำการเปลี่ยนแปลงจาก branch ที่เลือกมาไว้ใน branch ปัจจุบัน โดยจะแสดงประวัติบน git graph (เหมาะในการใช้ เอา code ลง main)
git diff origin/main <issue-??> #ตรวจสอบความแตกต่างของ 2 branch

```
