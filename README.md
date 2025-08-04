# NexusNew

แอปพลิเคชันอ่านพระคัมภีร์ประจำปีสำหรับ NexusBangkok Church

## 🚀 ฟีเจอร์หลัก

- **ข้อพระคัมภีร์ประจำปี** - อ่านพระคัมภีร์ตามวันที่กำหนด
- **ข้อพระคัมภีร์แบบสุ่ม** - ค้นพบข้อพระคัมภีร์ใหม่ที่ให้กำลังใจ
- **YouTube Integration** - ติดตามคำเทศนาล่าสุดจาก NexusBangkok Church
- **ลงทะเบียนเรียนคลาสพระคัมภีร์** - ลงทะเบียนเรียนคลาสที่ NexusBangkok Church
- **Dashboard** - ติดตามความคืบหน้าการอ่านพระคัมภีร์
- **ระบบ Authentication** - เข้าสู่ระบบด้วย Google หรืออีเมล

## 🛠️ เทคโนโลยีที่ใช้

- **Frontend**: React 18 + TypeScript
- **UI Framework**: Tailwind CSS + shadcn/ui
- **Build Tool**: Vite
- **Database**: Supabase
- **Authentication**: Supabase Auth
- **Routing**: React Router

## 📦 การติดตั้ง

1. **Clone repository**
   ```bash
   git clone https://github.com/candelza/NexusNew.git
   cd NexusNew
   ```

2. **ติดตั้ง dependencies**
   ```bash
   npm install
   ```

3. **ตั้งค่า Environment Variables**
   สร้างไฟล์ `.env.local` และเพิ่ม:
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **รัน Development Server**
   ```bash
   npm run dev
   ```

5. **เปิดเบราว์เซอร์**
   ไปที่ [http://localhost:8080](http://localhost:8080)

## 🏗️ การ Build

```bash
npm run build
```

## 📱 หน้าต่างๆ

- **หน้าหลัก** (`/`) - ข้อพระคัมภีร์ประจำปีและ YouTube
- **ข้อพระคัมภีร์แบบสุ่ม** (`/random`) - สุ่มข้อพระคัมภีร์ใหม่
- **ลงทะเบียนเรียนคลาส** (`/bible-class`) - ลงทะเบียนเรียนคลาสพระคัมภีร์
- **Dashboard** (`/dashboard`) - สถิติการอ่านพระคัมภีร์
- **Authentication** (`/auth`) - เข้าสู่ระบบ/สมัครสมาชิก

## 🎯 ฟีเจอร์ที่กำลังพัฒนา

- [ ] การแจ้งเตือนข้อพระคัมภีร์ประจำปี
- [ ] การแชร์ข้อพระคัมภีร์ในโซเชียลมีเดีย
- [ ] ระบบกลุ่มอ่านพระคัมภีร์
- [ ] การบันทึกโน้ตส่วนตัว
- [ ] การค้นหาข้อพระคัมภีร์

## 🤝 การมีส่วนร่วม

1. Fork โปรเจกต์
2. สร้าง Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit การเปลี่ยนแปลง (`git commit -m 'Add some AmazingFeature'`)
4. Push ไปยัง Branch (`git push origin feature/AmazingFeature`)
5. เปิด Pull Request

## 📞 ติดต่อ

- **Website**: [NexusBangkok Church](https://www.facebook.com/NexusBangkok)
- **YouTube**: [NexusBangkok Church](https://www.youtube.com/@nexusfellowship)
- **Email**: info@nexusbangkok.org

## 📄 License

โปรเจกต์นี้อยู่ภายใต้ MIT License - ดูรายละเอียดในไฟล์ [LICENSE](LICENSE)

## 🙏 ขอบคุณ

ขอบคุณ NexusBangkok Church สำหรับการสนับสนุนและคำแนะนำในการพัฒนาแอปพลิเคชันนี้
