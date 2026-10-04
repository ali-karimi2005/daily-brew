# The Daily Brew
اجرا روی کامپیوتر: `npm install` سپس `npm start` و باز کردن http://localhost:3000

## گذاشتن روی Render
1. پروژه را روی GitHub بگذار. در Render یک Web Service بساز. Build: `npm install` و Start: `npm start`
2. در Environment این‌ها را بگذار: `ADMIN_USER` و `ADMIN_PASS` (حتماً رمز قوی؛ پیش‌فرض admin / 1234 است)
3. برای اینکه نظرها، سفارش‌ها و رزروها با هر دیپلوی یا ری‌استارت پاک نشوند، یک Disk به سرویس اضافه کن (پلن پولی)، مثلاً با مسیر `/var/data`، و `DB_PATH=/var/data/daily.db` را بگذار. روی پلن رایگان دیسک موقت است و داده‌ها پاک می‌شوند.
4. فایل موزیک خودت را با نام `music.mp3` داخل پوشهٔ `public` بگذار.
5. ورود مدیر: دکمهٔ «ورود مدیر» پایین سایت.
